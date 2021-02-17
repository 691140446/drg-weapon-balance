## M1000-Balance-v6_U33H5_P
* **Source**: Update 33 Hotfix 5

### Base Weapon
* **Weakpoint Damage Multiplier**: 1.1 > 1.2
  * **Class**: DamageComponent
  * **Property**: WeakpointDamageMultiplier
  * **Value Offset**: 12980
  * **File**: `FSD\Content\WeaponsNTools\BoltActionRifle\WPN_M1000`
  > Increasing the weakpoint damage as much as possible without allowing to reach the Mactera Spawn breakpoint on non focused shot.

### Overclock – Hipster
* **Max Ammo (Multiplier)**: 1.75 > 1.25
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\BoltActionRifle\Overclocks\OC_BonusesAndPenalties\OC_Bonus_Ammo_20`
* **Spread per Shot**: -0.3 > -0.6
  * **Class**: HitscanBaseUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\BoltActionRifle\Overclocks\OC_BonusesAndPenalties\OC_Bonus_SpreadPerShot2_M1000`
* **Damage (Multiplier)**: 0.6 > 0.8
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\BoltActionRifle\Overclocks\OC_BonusesAndPenalties\OC_Penalty_Damage_15_M1000`
  > The changes to Hipster allow it to reach the Grunt breakpoint no matter the build.<br>.
  > Some other interesting breakpoints can be reached, like web spitters depending on T1 and T4 choice.<br>
  > The total potential damage per ressupply with Hipster is the same than the base weapon (without OC), no matter the mod choice, that mean Minimal clip will be more efficient in term of damage per resupply, but Hipster could allow for more kills and be more comfy depending on your build.

### Overclock – Supercooling Chamber
* **Focused Shot Damage Bonus**: 1.25 > 1.65
  * **Class**: BoltActionRifleUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\BoltActionRifle\Overclocks\OC_BonusesAndPenalties\OC_Bonus_FocusDamage_200P_M1000`
* **Max Ammo (Multiplier)**: 0.635 > 0.7
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\BoltActionRifle\Overclocks\OC_BonusesAndPenalties\OC_Penalty_Ammo_20_M1000`
* **Focus Speed (Multiplier)**: 0.5 > 0.6
  * **Class**: BoltActionRifleUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\BoltActionRifle\Overclocks\OC_BonusesAndPenalties\OC_Penalty_FocusSpeed_M1000`
  > The Max Ammo and Focus Speed multiplier has been increased a bit to get a better feeling with the OC.<br>
  > The increased Focused Damage Bonus allows to kill an Oppressor with 4 shots with a full damage build. Praetorians require 4 focused shots as well, but the build will be more flexible if you don’t care about the Oppressor breakpoint.
