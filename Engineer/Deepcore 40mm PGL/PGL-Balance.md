# PGL-Balance-v4_U33H5_P
* **Source**: Update 33 Hotfix 5

## Base Weapon
* **Area Damage**: 110 > 125
  * **Class**: DamageComponent
  * **Property**: RadialDamage
  * **Value Offset**: 18495
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\PRJ_GrenadeLauncher`
* **Maximum Damage Radius**: 150 > 200
  * **Class**: DamageComponent
  * **Property**: MaxDamageRadius
  * **Value Offset**: 18611
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\PRJ_GrenadeLauncher`
  > The changes above allow to kill grunts in a wider radius and to reach the slasher breakpoint when taking a damage upgrade.
* **Minimum Area Damage**: 0.15 > 0.30
  * **Class**: DamageComponent
  * **Property**: MinDamagePct
  * **Value Offset**: 18553
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\PRJ_GrenadeLauncher`
  > This change allow to have a guarantee minimum damage even when using an explosive build. In vanilla some build could fail to kill even a swarmer at the edge of the radius.

## Gear Modification – Tier 1 A – HE Compound
* **Area Damage**: 15 > 20
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\UPG_GrenadeLauncher_A_Damage`
  > Changed to match the T2 B Area Damage mod.

## Gear Modification – Tier 2 A – Larger Payload
* **Max Ammo**: 3 > 2
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\UPG_GrenadeLauncher_B_Ammo`
  > Changed to match the T1 B Ammo mod.

## Overclock – Compact Rounds
* **Max Ammo**: 4 > 5
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\Overclocks\OC_BonusAndPenalty\Bonus_Ammo4_PGL`
  > Increased its value to allow it to compete with the clean OC Pack Rat (+2 Ammo).
