# File "ambush.xml"

This file is used to store spawning patterns for the wave system of Ambush rooms and Boss Rush. 
{: .rep .tooltip .badge } Ambush rooms use a new system that's more similar to Greed Mode waves, so this file only defines the Boss Rush waves.

**Resource-Folder**{: .xmlInfo .green }: Placing this file in your mods "resource" folder will replace the original file.

**Content-Folder**{: .xmlInfo .red }: Placing this file in your mods "content" folder has no effect!

| Variable-Name | Possible Values | Description |
|:--|:--|:--|
|type|int|The type of the entity to spawn|
|variant|int|The variant of the entity|
|count|int|How many of the entity should spawn at the beginning of the wave|
|chunks|int|How many segments a multi-entity NPC (i.e, Larry Jr.) should have|
