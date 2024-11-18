# Kara.cs - Addon
A modified version of Kara.cs including a lot of new things like:

# Features
## Bools:
```csharp
LeafFront() // is a leaf in front of kara
LeafRight() // is a leaf right to kara
LeafLeft() // is a leaf left to kara
isLeafAt(x, y) // is leaf at x, y
isTreeAt(x, y) // is tree at x, y
isAirAt(x, y) // is air/empty at x, y
```
## Values:
```csharp
getX // Get x of player, starts at 0 - left
getY // Get y of player, starts at 0 - top
getFrontX // get x of position in front of kara
getFrontY // get y of position in front of kara
getRightX // get x of position right to kara
getRightY // get y of position right to kara
getLeftX // get x of position left to kara
getLeftY // get y of position right to kara
getDirection // degrees, integer
```
## Commands:
```csharp
PlaceLeafAt(x, y) // places a leaf at x, y
PlaceTreeAt(x, y) // places a tree at x, y
PlaceAirAt(x, y) // places air at x, y
Log(value) // Log something
```
## Speed multiply
Take a look at row 37 in the document
## Instant mode
Runs files at the fastest speed possible
# Samples
```csharp
int kara_x = kara.getY();
if (kara.LeafFront()) {/* Code here */}
```
# How-To install
Drag and replace all files in the Kara main folder
