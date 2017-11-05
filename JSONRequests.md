# JSON Documentation

This is a table that documents the JSON Required.

| Element | Description | Type | Notes | Requests |
| ------- | ----------- | ---- | ----- | -------- |
| Player | Holds the name of the Player. | String | | Required |
| &nbsp; Stats | The player's stats. | Object | | Required |
|&nbsp; &nbsp; Attack |  The player's attack base. | Integer | | Optional |
|&nbsp; &nbsp; Speed |  The player's speed base. | Integer | | Optional |
|&nbsp; &nbsp; Defense |  The player's defense base. | Integer | | Optional |
|&nbsp; &nbsp; Evasion |  The player's evasion base. | Integer | | Optional |
| &nbsp; OnHand | The player's on hand weapons and armor. | Object | | Required |
|&nbsp; &nbsp; Weapons |  The player's current equiped weapons. | Object | | Optional |
|&nbsp; &nbsp; &nbsp; RightArm |  The player's right-handed weapon. | String | | Optional |
|&nbsp; &nbsp; &nbsp; LeftArm |  The player's left-handed weapon. | String | | Optional |
|&nbsp; &nbsp; &nbsp; Ranged |  The player's long-range weapon. | String | | Optional |
|&nbsp; &nbsp; Armor |  The player's current equiped armor. | Object | | Required |
|&nbsp; &nbsp; &nbsp; Head |  The player's equipped helm. | String | | Optional |
|&nbsp; &nbsp; &nbsp; Body |  The player's equipped body. | String | | Optional |
|&nbsp; &nbsp; &nbsp; LeftArm |  The player's equipped left gauntlet. | String | | Optional |
|&nbsp; &nbsp; &nbsp; RightArm |  The player's equipped right gauntlet. | String | | Optional |
|&nbsp; &nbsp; &nbsp; Legs |  The player's equipped boots. | String | | Optional |
| &nbsp; Inventory |  The player's current inventory. | Object | | Required |
|&nbsp; &nbsp; Slot1 |  The first slot in inventory. | String | | Optional |
|&nbsp; &nbsp; Slot2 |  The player's slot in inventory. | String | | Optional |
|&nbsp; &nbsp; Slot3 |  The player's slot in inventory. | String | | Optional |
|&nbsp; &nbsp; Slot4 |  The player's sslot in inventory. | String | | Optional |