# EPC-Balance-v6
> The changes on this weapon are heavily focused on making Flying Nightmare viable by making it reach the Glyphid Grunt breakpoint without any Overclock and the Mactera Spawn breakpoint with the Overcharger Overclock.
* **Source**: Update 32 Hotfix 10

## Base Weapon
* **Heat Per Charged Shot**: 1.0 > 0.7
  * **Class**: WPN_ChargeBlaster_C
  * **Property**: HeatPerChargedShot
  * **Value Offset**: 17553
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\WPN_ChargeBlaster`
  > This change allows to shoot twice with Flying Nightmare without overheating. There is now a window of 0.15s (1.25s with the Heat Shield mod) once the shot is changed before overheating.
* **Charged Shot Damage (Single Target)**: 60 > 72
  * **Class**: DamageComponent
  * **Property**: Damage
  * **Value Offset**: 12955
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\PRJ_ChargedBlasterShot`
  > This change allow to reach the Glyphid Grunt breakpoint on Flying Nightmare without an Overclock
  > 72+18+18 = 108
* **Damage Conversion to Fire (Percentage)**: 0.2 > 0.45
  * **Class**: DamageConversionBonus
  * **Property**: ConversionPercentage
  * **Value Offset**: 13750
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\PRJ_ChargedBlasterShot`
  > This change allow to exceed the Mactera Spawn Breakpoint with Overcharger. The 10% Damage conversion to Disintegrate was kept so the end damage is 45% Electric / 45% Fire / 10% Disintegrate for both Flying Nightmare and the Charged Projectile (single target).

## Gear Modification – Tier 1 C – Higher Charged Plasma Energy
* **Charged Shot Damage / Area Damage**: 15 > 18
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 54
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\UPGEffect_ChargeBlaster_ChargeDirectDMG_1`
  > This change allow to reach the Glyphid Grunt breakpoint on Flying Nightmare without an Overclock
  > 72+18+18 = 108

## Gear Modification – Tier 2 C – Reactive Shockwave
* **Charged Shot Damage / Area Damage**: 15 > 18
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 54
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\UPGEffect_ChargeBlaster_ChargeDirectDMG_2`
  > This change allow to reach the Glyphid Grunt breakpoint on Flying Nightmare without an Overclock
  > 72+18+18 = 108

## Overclock – Overcharger
* **Charged Shot Cost (Multiplier)**: 1.5 > 1.3
  * **Class**: ChargedWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\Overclocks\OC_BonusAndPenalty\OC_Penalty_ChargeCost_EPC`
  > This change allow to exceed the Mactera Spawn Breakpoint with Overcharger
  > (108×0.45×1.5 + 108×0.45×2 + 108×0.1×1) × 1.5 = 271.35 > 267.6
