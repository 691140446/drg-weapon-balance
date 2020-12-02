# EPC-Balance-v6
* **Source**: Update 32 Hotfix 10
> The changes on this weapon are heavily focused on the Flying Nightmare mod.<br>
> Increasing the Charged Shot damage by 20% allows to reach the Glyphid Grunt breakpoint with a full damage build and using Overcharger on top of that allows to reach the Mactera Spawn breakpoint thanks to the change on the damage conversion.<br>
> Alternatively the reduced cost of the charged shot allows to go for a build with lower damage and a wider radius, chaining two shot since the weapon doesn’t overheat instantly.
## Base Weapon
* **Heat per Charged Shot**: 1.0 > 0.7
  * **Class**: WPN_ChargeBlaster_C
  * **Property**: HeatPerChargedShot
  * **Value Offset**: 17553
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\WPN_ChargeBlaster`
  > This change allows to chain two shots to open up some build with low (no Grunt breakpoint) damage on Flying Nightmare.
## Base Weapon
* **Charged Shot Damage (Single Target)**: 60 > 72
  * **Class**: DamageComponent
  * **Property**: Damage
  * **Value Offset**: 12955
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\PRJ_ChargedBlasterShot`
## Gear Modification – Tier 1 C – Higher Charged Plasma Energy
* **Charged Shot Damage / Area Damage**: 15 > 18
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 54
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\UPGEffect_ChargeBlaster_ChargeDirectDMG_1`
## Gear Modification – Tier 2 C – Reactive Shockwave
* **Charged Shot Damage / Area Damage**: 15 > 18
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 54
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\UPGEffect_ChargeBlaster_ChargeDirectDMG_2`
  > The changes above increase the Charged Shot direct damage and Flying Nightmare damage by 20%, allowing to reach the Glyphid Grunt breakpoint if both damage upgrade are taken.
## Base Weapon
* **Damage Conversion to Fire (Percentage)**: 0.2 > 0.45
  * **Class**: DamageConversionBonus
  * **Property**: ConversionPercentage
  * **Value Offset**: 13750
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\PRJ_ChargedBlasterShot`
  > This change affects the Charged Shot direct damage, AoE damage and the Flying Nightmare damage, allowing to reach the Mactera Spawn breakpoint on a full damage build with Overcharger.
## Overclock – Overcharger
* **Charged Shot Cost (Multiplier)**: 1.5 > 1.3
  * **Class**: ChargedWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\Overclocks\OC_BonusAndPenalty\OC_Penalty_ChargeCost_EPC`
  > This change gives Overcharger a better ammo economy to make it usable on more builds.
