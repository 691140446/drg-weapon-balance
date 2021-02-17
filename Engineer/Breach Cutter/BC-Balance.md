## BC-Balance-v8_U33H5_P
* **Source**: Update 33 Hotfix 5

### Gear Modification – Tier 2 A – Expanded Ammo Bags
* **Max Ammo**: 6 > 3
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\LineCutter\UPG_LineCutter_B_Ammo1`
  > Nerfed since this choice was way too good compared to the alternatives on this tier and it was way too strong.

### Gear Modification – Tier 5 A – Explosive Goodbyes
* **Area Damage**: 40 > 120
  * **Class**: DamageComponent
  * **Property**: RadialDamage
  * **Value Offset**: 24606
  * **File**: `FSD\Content\WeaponsNTools\LineCutter\PRJ_LineCutter2`

### Overclock – Stronger Plasma Current
* **Damage per Tick (Additive)**: 1 > 2
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\LineCutter\Overclocks\OC_BonusesAndPenalties\Bonus_DMG+1_LineCutter`
  > Increasing the Damage bonus a bit to allow it to compete with the clean Ammo OC.

### Overclock – Return to Sender
* **Max Ammo**: -6 > -3
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\LineCutter\Overclocks\OC_BonusesAndPenalties\Penalty_Ammo-4_LineCutter`
  > File shared with Inferno<br>
  > Reducing the Max Ammo penalty here to compensate for the nerf on the T2 A mod. This way you can still have the same amount of Max Ammo than in vanilla, but the other choices are actually viables.

### Overclock – Inferno
* **Max Ammo**: -6 > -3
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\LineCutter\Overclocks\OC_BonusesAndPenalties\Penalty_Ammo-4_LineCutter`
  > File shared with Return to Sender<br>
  > Reducing the Max Ammo penalty here to compensate for the nerf on the T2 A mod. This way you can still have the same amount of Max Ammo than in vanilla, but the other choices are actually viables.

### Overclock – Spinning Death
* **Max Ammo (Multiplier)**: 0.5 > 0.6
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\LineCutter\Overclocks\OC_BonusesAndPenalties\Penalty_AmmoBig_Linecutter`
* **Damage per Tick (Multiplier)**: 0.2 > 0.24
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\LineCutter\Overclocks\OC_BonusesAndPenalties\Penalty_DMGBig_LineCutter`
  > The changes above should allow to use Spinning Death as either a crowd clearing tool or a single target DPS, depending on the mod choices in T2 and T5.
