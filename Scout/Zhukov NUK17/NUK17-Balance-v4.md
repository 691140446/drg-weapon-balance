# NUK17-Balance-v4.md
* **Source**: Update 32 Hotfix 6
* **Note**: This mod change the shot cost from 2 to 1 and as a consequence all Max Ammo, Clip Size and Fire Rate value will be halved.
* **Note 2**: The mod isn’t done yet, only the readme is up for now.

## Base Weapon
* **Shot Cost**: 2 > 1
  * **Value Offset**: 11562
  * **Type**: Int
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\WPN_DualMPs.uexp`
* **Max Ammo**: 600 > 300
  * **Value Offset**: 11504
  * **Type**: Int
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\WPN_DualMPs.uexp`
* **Clip Size**: 50 > 25
  * **Value Offset**: 11533
  * **Type**: Int
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\WPN_DualMPs.uexp`
* **Max Horizontal Spread (i.e. Base Spread)**: 36 > 29 <!-- ~ 100% > 80% Base Spread -->
  * **Value Offset**: 16804
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\WPN_DualMPs.uexp`

## Gear Modification – Tier 1 A – Expanded Ammo Bags
* **Max Ammo**: 100 > 50
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\UPG_DualMP_A_Ammo.uexp`

## Gear Modification – Tier 2 A – High Capacity Magazine
* **Clip Size**: 10 > 5
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\UPG_DualMP_B_ClipSize.uexp`

## Gear Modification – Tier 4 C – Expanded Ammo Bags
* **Max Ammo**: 150 > 75
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\UPG_DualMP_D_Ammo_2.uexp`

## Overclock – Custom Casings
* **Clip Size**: 30 > 15
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\Overclocks\OC_BonusesAndPenalties\Bonuis_ClipSize15_DualMP.uexp`

## Overclock – Cryo Minelets
* **Clip Size**: -20 > -15
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\Overclocks\OC_BonusesAndPenalties\Penalty_ClipSize-10_DualMP.uexp`

## Overclock – Embedded Detonators
* **Max Ammo**: -400 > -200
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\Overclocks\OC_BonusesAndPenalties\Penalty_Ammo-75_DualMP.uexp`
* **Clip Size**: -20 > -10
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\Overclocks\OC_BonusesAndPenalties\Penalty_ClipSize-50p_DualMP.uexp`