# Navigation Mesh
Exported data is from GTA V *.ynv files in compressed (Lz4BlockArray) messagepack format as it would get too huge otherwise. 

For C# I recommend using following NuGet package to deserialize the dump: https://www.nuget.org/packages/messagepack

## System.NotSupportedException: A non-collectible assembly may not reference a collectible assembly.
If you receive that exception on loading, the reason is that probably the MessagePack NuGet package is written for .NET Standard 2. You can work around this by setting the following environment in your project properties or on windows environment variables:
`CSHARP_MODULE_DISABLE_COLLECTIBLE = true`

Changing this will disable the possibility for resource hot-reloading (on runtime).

## C# Example on loading the data
```csharp
private TDumpType LoadDataFromDumpFile<TDumpType>(string dumpFileName)
    where TDumpType : new()
{
    TDumpType dumpResult = default;
    string filePath = Path.Combine(AppDomain.CurrentDomain.BaseDirectory, "resources", yourResourceName, "data", dumpFileName);
    if (!File.Exists(filePath))
    {
        Alt.Log($"Could not find dump file at {filePath}");
        return default;
    }

    try
    {
        MessagePackSerializerOptions lz4Options = MessagePackSerializerOptions.Standard.WithCompression(MessagePackCompression.Lz4BlockArray);
        dumpResult = MessagePackSerializer.Deserialize<TDumpType>(File.ReadAllBytes(filePath), lz4Options);
        Alt.Log($"Successfully loaded dump file {dumpFileName}.");
    }
    catch (Exception e)
    {
        Alt.Log($"Failed loading dump: {e}");
    }

    return dumpResult;
}
```
```csharp
List<NavigationMesh> navigationMeshes = LoadDataFromDumpFile<List<NavigationMesh>>("navigationmeshes.json");
```

## Models (C#)
Export contains a List of NavigationMesh model.

### NavigationMesh
```csharp
[MessagePackObject]
public class NavigationMesh
{
    [Key(0)]
    public int AreaId { get; set; }

    [Key(1)]
    public int CellX { get; set; }

    [Key(2)]
    public int CellY { get; set; }

    [Key(3)]
    public List<NavigationMeshPoly> Polygons { get; set; }
}
```

### NavigationMeshPoly
```csharp
[MessagePackObject]
public class NavigationMeshPoly
{
    [Key(0)]
    public int Index { get; set; }

    [Key(1)]
    public int PartId { get; set; }

    [Key(2)]
    public bool IsFootpath { get; set; }

    [Key(3)]
    public bool IsUnderground { get; set; }

    [Key(4)]
    public bool IsSteepSlope { get; set; }

    [Key(5)]
    public bool IsWater { get; set; }

    [Key(6)]
    public bool HasPathNode { get; set; }

    [Key(7)]
    public bool IsInterior { get; set; }

    [Key(8)]
    public bool IsFlatGround { get; set; }

    [Key(9)]
    public bool IsRoad { get; set; }

    [Key(10)]
    public bool IsCellEdge { get; set; }

    [Key(11)]
    public bool IsTrainTrack { get; set; }

    [Key(12)]
    public bool IsShallowWater { get; set; }

    [Key(13)]
    public bool IsFootpathUnk1 { get; set; }

    [Key(14)]
    public bool IsFootpathUnk2 { get; set; }

    [Key(15)]
    public bool IsFootpathMall { get; set; }

    [Key(16)]
    public bool IsSlopeSouth { get; set; }

    [Key(17)]
    public bool IsSlopeSouthEast { get; set; }

    [Key(18)]
    public bool IsSlopeEast { get; set; }

    [Key(19)]
    public bool IsSlopeNorthEast { get; set; }

    [Key(20)]
    public bool IsSlopeNorth { get; set; }

    [Key(21)]
    public bool IsSlopeNorthWest { get; set; }

    [Key(22)]
    public bool IsSlopeWest { get; set; }

    [Key(23)]
    public bool IsSlopeSouthWest { get; set; }

    [Key(24)]
    public int UnkX { get; set; }

    [Key(25)]
    public int UnkY { get; set; }

    [Key(26)]
    public WorldVector3 Position { get; set; }

    [Key(27)]
    public List<WorldVector3> Vertices { get; set; }

    [Key(28)]
    public List<NavigationMeshPolyEdge> Edges { get; set; }
}
```

### NavigationMeshPolyEdge
```csharp
[MessagePackObject]
public class NavigationMeshPolyEdge
{
    [Key(0)]
    public uint AreaId { get; set; }

    [Key(1)]
    public uint PolyIndex { get; set; }
}
```

### WorldVector3
```csharp
[MessagePackObject]
public class WorldVector3
{
    [Key(0)]
    public float X { get; set; }

    [Key(1)]
    public float Y { get; set; }

    [Key(2)]
    public float Z { get; set; }
}
```