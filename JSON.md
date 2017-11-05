# JSON Documentation

This is a table that documents the JSON Response.

| Element | Description | Type | Notes |
| ------- | ----------- | ---- | ----- |
| Player | Holds the name of the Player. | String | |
| &nbsp; Stats | The player's stats. | Object | |
|		Attack |  The player's attack base. | Integer | |
|		Speed |  The player's speed base. | Integer | |
|		Defense |  The player's defense base. | Integer | |
|		Evasion |  The player's evasion base. | Integer | |
|	OnHand | The player's on hand weapons and armor. | Object | |
|		Weapons |  The player's current equiped weapons. | Object | |
|			RightArm |  The player's right-handed weapon. | String | |
|			LeftArm |  The player's left-handed weapon. | String | |
|			Ranged |  The player's long-range weapon. | String | |
|		Armor |  The player's current equiped armor. | Object | |
|			Head |  The player's equipped helm. | String | |
|			Body |  The player's equipped body. | String | |
|			LeftArm |  The player's equipped left gauntlet. | String | |
|			RightArm |  The player's equipped right gauntlet. | String | |
|			Legs |  The player's equipped boots. | String | |
|		Inventory |  The player's current inventory. | Object | |
|			Slot1 |  The first slot in inventory. | String | |
|			Slot2 |  The player's slot in inventory. | String | |
|			Slot3 |  The player's slot in inventory. | String | |
|			Slot4 |  The player's sslot in inventory. | String | |