# EPC-Balance-v5
* **Source**: Update 32 Hotfix 9

## Base Weapon
* **Heat Per Charged Shot**: 1.0 > 0.7
  * **Variable Name**: HeatPerChargedShot
  * **Value Offset**: 17553
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\WPN_ChargeBlaster`
  > To try opening a few build with Flying Nightmare (since it won’t overheat directly), a bit too powerful in general, if you have a better solution to make FN viable feel free to share it.
* **Charged Shot Damage (Single Target)**: 60 > 72
  * **Variable Name**: Damage
  * **Value Offset**: 12955
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\PRJ_ChargedBlasterShot`
* **Damage Conversion to Fire**: 0.25 > 0.45
  * **Variable Name**: ConversionPercentage
  * **Value Offset**: 13750
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\PRJ_ChargedBlasterShot`

## Gear Modification – Tier 1 C – Higher Charged Plasma Energy
* **Charged Shot Damage/Area Damage**: 15 > 18
  * **Variable Name**: Amount
  * **Value Offset**: 54
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\UPGEffect_ChargeBlaster_ChargeDirectDMG_1`

## Gear Modification – Tier 2 C – Reactive Shockwave
* **Charged Shot Damage/Area Damage**: 15 > 18
  * **Variable Name**: Amount
  * **Value Offset**: 54
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\UPGEffect_ChargeBlaster_ChargeDirectDMG_2`

## Overclock – Overcharger
* **Charged Shot Cost (Multiplier)**: 1.5 > 1.3
  * **Variable Name**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\Overclocks\OC_BonusAndPenalty\OC_Penalty_ChargeCost_EPC`
