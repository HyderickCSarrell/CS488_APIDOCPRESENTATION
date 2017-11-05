# JSON Documentation

This is a table that documents the JSON Response.

| Element | Description | Type | Notes |
| ------- | ----------- | ---- | ----- |
| Player | Holds the name of the Player. | String | |
| &nbsp; Stats | The player's stats. | Object | |
|&nbsp; &nbsp; Attack |  The player's attack base. | Integer | |
|&nbsp; &nbsp; Speed |  The player's speed base. | Integer | |
|&nbsp; &nbsp; Defense |  The player's defense base. | Integer | |
|&nbsp; &nbsp; Evasion |  The player's evasion base. | Integer | |
| &nbsp; OnHand | The player's on hand weapons and armor. | Object | |
|&nbsp; &nbsp; Weapons |  The player's current equiped weapons. | Object | |
|&nbsp; &nbsp; &nbsp; RightArm |  The player's right-handed weapon. | String | |
|&nbsp; &nbsp; &nbsp; LeftArm |  The player's left-handed weapon. | String | |
|&nbsp; &nbsp; &nbsp; Ranged |  The player's long-range weapon. | String | |
|&nbsp; &nbsp; Armor |  The player's current equiped armor. | Object | |
|&nbsp; &nbsp; &nbsp; Head |  The player's equipped helm. | String | |
|&nbsp; &nbsp; &nbsp; Body |  The player's equipped body. | String | |
|&nbsp; &nbsp; &nbsp; LeftArm |  The player's equipped left gauntlet. | String | |
|&nbsp; &nbsp; &nbsp; RightArm |  The player's equipped right gauntlet. | String | |
|&nbsp; &nbsp; &nbsp; Legs |  The player's equipped boots. | String | |
| &nbsp; Inventory |  The player's current inventory. | Object | |
|&nbsp; &nbsp; Slot1 |  The first slot in inventory. | String | |
|&nbsp; &nbsp; Slot2 |  The player's slot in inventory. | String | |
|&nbsp; &nbsp; Slot3 |  The player's slot in inventory. | String | |
|&nbsp; &nbsp; Slot4 |  The player's sslot in inventory. | String | |

#Links to the other tables

[JSON Requests](https://github.com/HyderickCSarrell/CS488_APIDOCPRESENTATION/blob/master/JSONRequests.md)
[XML Response](https://github.com/HyderickCSarrell/CS488_APIDOCPRESENTATION/blob/master/XMLResponse.md)
[XML Request](https://github.com/HyderickCSarrell/CS488_APIDOCPRESENTATION/blob/master/XMLRequests.md)