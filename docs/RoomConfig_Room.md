---
tags:
  - Class
search:
  boost: 0.25
---
# Class "RoomConfigRoom"
???+ info
    You can get this class by using the following functions:

    * [RoomDescriptor.Data](RoomDescriptor.md#data)
    * [RoomDescriptor.OverrideData](RoomDescriptor.md#overridedata)

    ???+ example "Example Code"
        ```lua
        local game = Game()
        local level = game:GetLevel()
        local roomDescriptor = level:GetCurrentRoomDesc()
        local roomConfigRoom = roomDescriptor.Data
        ```
## Variables
### Difficulty {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const [Difficulty](enums/Difficulty.md) Difficulty {: .copyable aria-label='Variables' }

___
### Doors {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const int Doors  {: .copyable aria-label='Variables' }
Returns a bit mask of the positions of valid door positions in this room. It is  a combination of bit flags of the DoorSlotFlag enum, which is defined as follows:

```lua
enum DoorSlotFlag {
  LEFT0 = 1 << DoorSlot.LEFT0,
  UP0 = 1 << DoorSlot.UP0,
  RIGHT0 = 1 << DoorSlot.RIGHT0,
  DOWN0 = 1 << DoorSlot.DOWN0,
  LEFT1 = 1 << DoorSlot.LEFT1,
  UP1 = 1 << DoorSlot.UP1,
  RIGHT1 = 1 << DoorSlot.RIGHT1,
  DOWN1 = 1 << DoorSlot.DOWN1,
}
```
___
### Height {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const int Height  {: .copyable aria-label='Variables' }

___
### Initial·Weight {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const float InitialWeight  {: .copyable aria-label='Variables' }

___
### Mode {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .rep .tooltip .badge }
#### const userdata Mode  {: .copyable aria-label='Variables' }
???+ bug "Bug"
    This variable is broken and returns userdata.

___
### Name {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const string Name  {: .copyable aria-label='Variables' }

___
### Original·Variant {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### int OriginalVariant  {: .copyable aria-label='Variables' }

___
### Shape {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const [RoomShape](enums/RoomShape.md) Shape  {: .copyable aria-label='Variables' }

___
### Spawn·Count {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const int SpawnCount  {: .copyable aria-label='Variables' }

___
### Spawns {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const [RoomConfigSpawns](CppContainer_ArrayProxy_RoomConfigSpawns.md) Spawns  {: .copyable aria-label='Variables' }

___
### Stage·ID {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const int StageID  {: .copyable aria-label='Variables' }
The ID of the stage the room was designed for.

???- note "Stage IDs (corresponds to IDs in stages.xml)"

	|DLC|ID|Stage|Comment|
	|:--|:--|:--|:--|
	|[ ](#){: .abrep .tooltip .badge }|0 |Special Rooms |  |
	|[ ](#){: .abrep .tooltip .badge }|1 |Basement |  |
	|[ ](#){: .abrep .tooltip .badge }|2 |Cellar |  |
	|[ ](#){: .abrep .tooltip .badge }|3 |Burning Basement |  |
	|[ ](#){: .abrep .tooltip .badge }|4 |Caves |  |
	|[ ](#){: .abrep .tooltip .badge }|5 |Catacombs |  |
	|[ ](#){: .abrep .tooltip .badge }|6 |Flooded Caves |  |
	|[ ](#){: .abrep .tooltip .badge }|7 |Depths |  |
	|[ ](#){: .abrep .tooltip .badge }|8 |Necropolis |  |
	|[ ](#){: .abrep .tooltip .badge }|9 |Dank Depths |  |
	|[ ](#){: .abrep .tooltip .badge }|10 |Womb |  |
	|[ ](#){: .abrep .tooltip .badge }|11 |Utero |  |
	|[ ](#){: .abrep .tooltip .badge }|12 |Scarred Womb |  |
	|[ ](#){: .abrep .tooltip .badge }|13 |Blue Womb |  |
	|[ ](#){: .abrep .tooltip .badge }|14 |Sheol |  |
	|[ ](#){: .abrep .tooltip .badge }|15 |Cathedral |  |
	|[ ](#){: .abrep .tooltip .badge }|16 |Dark Room |  |
	|[ ](#){: .abrep .tooltip .badge }|17 |Chest |  |
	|[ ](#){: .abp .tooltip .badge }|18 |Greed Special Rooms |  |
	|[ ](#){: .abp .tooltip .badge }|19 |Greed Basement |  |
	|[ ](#){: .abp .tooltip .badge }|20 |Greed Caves |  |
	|[ ](#){: .abp .tooltip .badge }|21 |Greed Depths |  |
	|[ ](#){: .abp .tooltip .badge }|22 |Greed Womb |  |
	|[ ](#){: .abp .tooltip .badge }|23 |Greed Sheol |  |
	|[ ](#){: .abrep .tooltip .badge }|24 |The Shop |  |
	|[ ](#){: .abrep .tooltip .badge }|25 |Ultra Greed |  |
	|[ ](#){: .abrep .tooltip .badge }|26 |The Void |  |
	|[ ](#){: .rep .tooltip .badge }|27 |Downpour |  |
	|[ ](#){: .rep .tooltip .badge }|28 |Dross |  |
	|[ ](#){: .rep .tooltip .badge }|29 |Mines |  |
	|[ ](#){: .rep .tooltip .badge }|30 |Ashpit |  |
	|[ ](#){: .rep .tooltip .badge }|31 |Mausoleum |  |
	|[ ](#){: .rep .tooltip .badge }|32 |Gehenna |  |
	|[ ](#){: .rep .tooltip .badge }|33 |Corpse |  |
	|[ ](#){: .rep .tooltip .badge }|35 |Home |The Stage ID of 34 does not exist. |
	|[ ](#){: .rep .tooltip .badge }|36 |Backwards |These rooms are used during the Ascent. |

___
### Subtype {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const int Subtype  {: .copyable aria-label='Variables' }

___
### Type {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const [RoomType](enums/RoomType.md) Type  {: .copyable aria-label='Variables' }

___
### Variant {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const int Variant  {: .copyable aria-label='Variables' }

___
### Weight {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const float Weight  {: .copyable aria-label='Variables' }

___
### Width {: aria-label='Variables' }
[ ](#){: .const .tooltip .badge } [ ](#){: .abrep .tooltip .badge }
#### const int Width  {: .copyable aria-label='Variables' }

___
