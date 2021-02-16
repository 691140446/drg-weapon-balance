# EPC-Balance-v9_U33H5_P
* **Source**: Update 33 Hotfix 5
> The changes on this weapon are heavily focused on the Flying Nightmare mod.<br>
> Increasing the Charged Shot damage by 20% allows to reach the Glyphid Grunt breakpoint with a full damage build and using Overcharger on top of that allows to reach the Mactera Spawn breakpoint thanks to the change on the damage conversion.<br>
> Alternatively reducing the charged shot cost to 0.7 opens builds lower damage and a wider radius, chaining two shots since the weapon doesn’t overheat instantly.

## Base Weapon
* **Heat per Charged Shot**: 1.0 > 0.7
  * **Class**: WPN_ChargeBlaster_C
  * **Property**: HeatPerChargedShot
  * **Value Offset**: 17553
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\WPN_ChargeBlaster`
  > This change allows to chain two charged shots to open up some builds with low (no Grunt breakpoint) damage on Flying Nightmare.

## Base Weapon
* **Charged Shot Damage**: 60 > 72
  * **Class**: DamageComponent
  * **Property**: Damage
  * **Value Offset**: 12955
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\PRJ_ChargedBlasterShot`
* **Charged Shot Area Damage**: 60 > 72
  * **Class**: DamageComponent
  * **Property**: RadialDamage
  * **Value Offset**: 13142
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\PRJ_ChargedBlasterShot`
  > To simulate a 20% damage increase for the charged shot.

## Gear Modification – Tier 1 C – Higher Charged Plasma Energy
* **Charged Shot Damage**: 15 > 18
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 54
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\UPGEffect_ChargeBlaster_ChargeDirectDMG_1`
* **Charged Shot Area Damage**: 15 > 18
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 95
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\UPGEffect_ChargeBlaster_ChargeAoEDMG_1`
  > To simulate a 20% damage increase for the charged shot.

## Gear Modification – Tier 2 C – Reactive Shockwave
* **Charged Shot Damage**: 15 > 18
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 54
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\UPGEffect_ChargeBlaster_ChargeDirectDMG_2`
* **Charged Shot Area Damage**: 15 > 18
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 95
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\UPGEffect_ChargeBlaster_ChargeAoEDMG_2`
  > To simulate a 20% damage increase for the charged shot.<br><br>
  > The changes above simulate a 20% damage increase for the Charged Shot and Flying Nightmare, allowing to reach the Glyphid Grunt breakpoint if both damage upgrades are taken.

## Gear Modification – Tier 5 B – Thin Containment Field
* **Heat per Charged Shot (Multplier)**: 0.25 > 0.7
  * **Class**: ChargedWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\UPGEffect_ChargeShotHeat_EPC`
* **Heat per Normal Shot (Multplier)**: 0.8 > 1.0
  * **Class**: ChargedWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\UPGEffect_HeatPerNormalShot_EPC`
  > The changes above increase the heat generated when using Thin Containment. The goal here is to nerf it slightly by making it harder to use it several times in quick succession.

## Base Weapon
* **Damage Conversion to Fire (Percentage)**: 0.25 > 0.45
  * **Class**: DamageConversionBonus
  * **Property**: ConversionPercentage
  * **Value Offset**: 13779
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\PRJ_ChargedBlasterShot`
  > This change affects the Charged Shot direct damage, AoE damage and the Flying Nightmare damage, allowing to reach the Mactera Spawn breakpoint on a full damage Flying Nightmare build with Overcharger.

## Overclock – Overcharger
* **Charged Shot Cost (Multiplier)**: 1.5 > 1.3
  * **Class**: ChargedWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\Overclocks\OC_BonusAndPenalty\OC_Penalty_ChargeCost_EPC`
  > This change gives Overcharger a better ammo economy to make it usable on more builds.

## Overclock – Persistent Plasma
* **Charged Shot Damage**: -20 > -18
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 54
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\Overclocks\OC_BonusAndPenalty\OC_Penalty_ChargeDirectDmg_EPC`
## Overclock – Persistent Plasma
* **Charged Shot Area Damage**: -20 > -18
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 95
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\Overclocks\OC_BonusAndPenalty\OC_Penalty_ChargedExplosionDamage-20_EPC`
