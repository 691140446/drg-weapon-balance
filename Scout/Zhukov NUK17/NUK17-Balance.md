# NUK17-Balance-v7_U33H5_P
* **Source**: Update 33 Hotfix 5

## Base Weapon
* **Shot Cost**: 2 > 1
  * **Class**: WPN_DualMPs_C
  * **Property**: ShotCost
  * **Value Offset**: 11624
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\WPN_DualMPs`
  > To change the shot cost from 2 to 1, so we can display the real ammo count of the weapon., most of the changes below are a direct consequence of this.
* **Max Ammo**: 600 > 300
  * **Class**: WPN_DualMPs_C
  * **Property**: MaxAmmo
  * **Value Offset**: 11566
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\WPN_DualMPs`
  > Halved the Max Ammo to match the shot cost reduction.
* **Clip Size**: 50 > 25
  * **Class**: WPN_DualMPs_C
  * **Property**: ClipSize
  * **Value Offset**: 11595
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\WPN_DualMPs`
  > Halved the Clip Size to match the shot cost reduction.
* **Max Horizontal Spread**: 36 > 29
  * **Class**: HitscanComponent
  * **Property**: MaxHorizontalSpread
  * **Value Offset**: 16325
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\WPN_DualMPs`
  > To reduce base spread by ~20%, hopefully the T3 precision mod won’t feel like a must have in most build now.

## Gear Modification – Tier 1 A – Expanded Ammo Bags
* **Max Ammo**: 100 > 50
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\UPG_DualMP_A_Ammo`
  > Halved the Max Ammo to match the shot cost reduction.

## Gear Modification – Tier 2 A – High Capacity Magazine
* **Clip Size**: 10 > 5
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\UPG_DualMP_B_ClipSize`
  > Halved the Clip Size to match the shot cost reduction.

## Gear Modification – Tier 4 C – Expanded Ammo Bags
* **Max Ammo**: 150 > 75
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\UPG_DualMP_D_Ammo_2`
  > Halved the Max Ammo to match the shot cost reduction.

## Overclock – Custom Casings
* **Clip Size**: 30 > 15
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\Overclocks\OC_BonusesAndPenalties\Bonuis_ClipSize15_DualMP`
  > Halved the Clip Size to match the shot cost reduction.

## Overclock – Cryo Minelets
* **Clip Size**: -10 > -5
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\Overclocks\OC_BonusesAndPenalties\Penalty_ClipSize-10_DualMP`
  > Halved the Clip Size to match the shot cost reduction.

## Overclock – Embedded Detonators
* **Max Ammo**: -400 > -200
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\Overclocks\OC_BonusesAndPenalties\Penalty_Ammo-75_DualMP`
  > Halved the Max Ammo to match the shot cost reduction.
* **Clip Size**: -20 > -10
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\Overclocks\OC_BonusesAndPenalties\Penalty_ClipSize-50p_DualMP`
  > Halved the Clip Size to match the shot cost reduction.
