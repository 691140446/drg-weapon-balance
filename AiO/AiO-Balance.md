# AiO-Balance-v1.13
<!-- This All in One mod will contain the main changes (mostly from Silaise version when there is several possibliities) from this repository. If you wish to use any alt version, you can simply use the alt mod on top of this one, it will overwrite just the needed value and be loaded in the good order by default. -->

## Flamethrower-Balance-v7_U33H5_P
* **Source**: Update 33 Hotfix 5

### Gear Modification – Tier 4 A – It Burns!
* **Fear Factor**: 0.13 > 0.2
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\FlameThrower\UPG_Flamethrower_D_Fear`
  > This increases the fear chance per fuel spent from 6.5% to 10% versus Glyphid Grunts and Glyphid Praetorians, increasing the chance to Fear them from ~33% to ~47% per second with the base flow rate.<br>
  > This should make this mod a viable choice compared to the other mods on this tier.

### Overclock – Face Melter
* **Damage**: 2 > 4
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\FlameThrower\Overclocks\OC_BonusesAndPenalties\Bonus_DMG+3_Flamethrower`
* **Rate of Fire (Additive)**: 1.8 > 0.9 <!-- 30% > 15% -->
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\FlameThrower\Overclocks\OC_BonusesAndPenalties\Bonus_RoF_Flamethrower`
  > The Face Melter changes aim to keep a dps similar to the live version while keeping a decent ammo economy.

## Subata-Balance-v4_U33H5_P
* **Source**: Update 33 Hotfix 5

### Overclock – Chain Hit
* **Ricochet Chance (Weakpoint only)**: 0.5 > 0.66
  * **Class**: HitscanBaseUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\Pistol\Overclocks\OC_BonusesAndPenalties\OC_Bonus_Ricochet_Pistol`

### Overclock – Tranquilizer Rounds
* **Rate of Fire**: -4 > -2
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\Pistol\Overclocks\OC_BonusesAndPenalties\OC_Penalty_RoF_Pistol`

## EPC-Balance-v9_U33H5_P
* **Source**: Update 33 Hotfix 5
> The changes on this weapon are heavily focused on the Flying Nightmare mod.<br>
> Increasing the Charged Shot damage by 20% allows to reach the Glyphid Grunt breakpoint with a full damage build and using Overcharger on top of that allows to reach the Mactera Spawn breakpoint thanks to the change on the damage conversion.<br>
> Alternatively reducing the charged shot cost to 0.7 opens builds lower damage and a wider radius, chaining two shots since the weapon doesn’t overheat instantly.

### Base Weapon
* **Heat per Charged Shot**: 1.0 > 0.7
  * **Class**: WPN_ChargeBlaster_C
  * **Property**: HeatPerChargedShot
  * **Value Offset**: 17553
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\WPN_ChargeBlaster`
  > This change allows to chain two charged shots to open up some builds with low (no Grunt breakpoint) damage on Flying Nightmare.

### Base Weapon
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

### Gear Modification – Tier 1 C – Higher Charged Plasma Energy
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

### Gear Modification – Tier 2 C – Reactive Shockwave
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

### Gear Modification – Tier 5 B – Thin Containment Field
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

### Base Weapon
* **Damage Conversion to Fire (Percentage)**: 0.25 > 0.45
  * **Class**: DamageConversionBonus
  * **Property**: ConversionPercentage
  * **Value Offset**: 13779
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\PRJ_ChargedBlasterShot`
  > This change affects the Charged Shot direct damage, AoE damage and the Flying Nightmare damage, allowing to reach the Mactera Spawn breakpoint on a full damage Flying Nightmare build with Overcharger.

### Overclock – Overcharger
* **Charged Shot Cost (Multiplier)**: 1.5 > 1.3
  * **Class**: ChargedWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\Overclocks\OC_BonusAndPenalty\OC_Penalty_ChargeCost_EPC`
  > This change gives Overcharger a better ammo economy to make it usable on more builds.

### Overclock – Persistent Plasma
* **Charged Shot Damage**: -20 > -18
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 54
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\Overclocks\OC_BonusAndPenalty\OC_Penalty_ChargeDirectDmg_EPC`
### Overclock – Persistent Plasma
* **Charged Shot Area Damage**: -20 > -18
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 95
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\Overclocks\OC_BonusAndPenalty\OC_Penalty_ChargedExplosionDamage-20_EPC`

## HE-Grenade-Balance-v3_U33H5_P
* **Source**: Update 33 Hotfix 5

### Base Grenade
* **Max Grenades**: 4 > 6
  * **Class**: Grenade_HighExplosive_C
  * **Property**: MaxGrenades
  * **Value Offset**: 279
  * **File**: `FSD\Content\WeaponsNTools\Grenades\HighExplosive\Grenade_HighExplosive`
  > The number of grenade was increased to match the amount of Sticky Grenade carried by the Gunner since their stats is similar.
* **Area Damage**: 130 > 140
  * **Class**: DamageComponent
  * **Property**: RadialDamage
  * **Value Offset**: 526
  * **File**: `FSD\Content\WeaponsNTools\Grenades\HighExplosive\Grenade_HighExplosive`
  > This change allows to reach the Glyphid Grunt Slasher breakpoint, killing them in an area slighly bigger than the Maximum Damage Radius (2-2.1m).
* **Minimum Area Damage**: 0.2 > 0.35
  * **Class**: DamageComponent
  * **Property**: MinDamagePct
  * **Value Offset**: 555
  * **File**: `FSD\Content\WeaponsNTools\Grenades\HighExplosive\Grenade_HighExplosive`
  > This change allows to reach the Glyphid Grunt breakpoint in a larger radius (~2.8m).
* **Carve Diameter**: 200 > 300
  * **Class**: ExplosionComponent
  * **Property**: CarveDiameterCM
  * **Value Offset**: 625
  * **File**: `FSD\Content\WeaponsNTools\Grenades\HighExplosive\Grenade_HighExplosive`
  > This change allows to use the grenade to mine some otherwise hard to reach minerals, without making it being to compete with TCF.

# Engineer
## Warthog-Balance-v4_U33H5_P
* **Source**: Update 33 Hotfix 5

### Base Weapon
* **Max Ammo**: 90 > 105
  * **Class**: WPN_CombatShotgun_C
  * **Property**: MaxAmmo
  * **Value Offset**: 9096
  * **File**: `FSD\Content\WeaponsNTools\CombatShotgun\WPN_CombatShotgun`
* **Clip Size**: 6 > 7
  * **Class**: WPN_CombatShotgun_C
  * **Property**: ClipSize
  * **Value Offset**: 9125
  * **File**: `FSD\Content\WeaponsNTools\CombatShotgun\WPN_CombatShotgun`

### Gear Modification – Tier 2 A – Expanded Ammo Bags
* **Max Ammo**: 40 > 35
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\CombatShotgun\UPG_CombatShotgun_B_MaxAmmo`

### Gear Modification – Tier 3 C – High Capacity Magazine
* **Clip Size**: 3 > 2
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\CombatShotgun\UPG_CombatShotgun_B_ClipSize+3`

### Overclock – Mini Shells
* **Max Ammo**: 90 > 70
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\CombatShotgun\Overclocks\OC_BonusesAndPenalties\OC_Bonus_Ammo50_CombatShotguin`

### Overclock – Cycle Overload
* **Damage**: 1 > 2
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\CombatShotgun\Overclocks\OC_BonusesAndPenalties\OC_Bonus_Damage+1_CombatShotgun`

## Stubby-Balance-v3_U33H5_P
* **Source**: Update 33 Hotfix 5

### Overclock – Turret EM Discharge
* **Damage**: -3 > -2
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\SMG\Overclocks\OC_BonusesAndPenalties\Penlaty_DMG-3_SMG`

## PGL-Balance-v4_U33H5_P
* **Source**: Update 33 Hotfix 5

### Base Weapon
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

### Gear Modification – Tier 1 A – HE Compound
* **Area Damage**: 15 > 20
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\UPG_GrenadeLauncher_A_Damage`
  > Changed to match the T2 B Area Damage mod.

### Gear Modification – Tier 2 A – Larger Payload
* **Max Ammo**: 3 > 2
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\UPG_GrenadeLauncher_B_Ammo`
  > Changed to match the T1 B Ammo mod.

### Overclock – Compact Rounds
* **Max Ammo**: 4 > 5
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\Overclocks\OC_BonusAndPenalty\Bonus_Ammo4_PGL`
  > Increased its value to allow it to compete with the clean OC Pack Rat (+2 Ammo).

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

## Sentry-Balance-v7_U33H5_P
* **Source**: Update 33 Hotfix 5

### "Warthog" Auto 210 – Gear Modification – Tier 5 A – Turret Whip
* **Radius**: 150 > 200
  * **Class**: DamageComponent
  * **Property**: DamageRadius
  * **Value Offset**: 6942
  * **File**: `FSD\Content\WeaponsNTools\SentryGun\SentryGun_Engineer\PRJ_SentryOvercharge_Projectile`
* **Maximum Damage Radius**: 150 > 200
  * **Class**: DamageComponent
  * **Property**: MaxDamageRadius
  * **Value Offset**: 6971
  * **File**: `FSD\Content\WeaponsNTools\SentryGun\SentryGun_Engineer\PRJ_SentryOvercharge_Projectile`
* **Initial Projectile Speed**: 5000 > 7500
  * **Class**: ProjectileMovementComponent
  * **Property**: InitialSpeed
  * **Value Offset**: 7472
  * **File**: `FSD\Content\WeaponsNTools\SentryGun\SentryGun_Engineer\PRJ_SentryOvercharge_Projectile`
* **Maximum Projectile Speed**: 5000 > 7500
  * **Class**: ProjectileMovementComponent
  * **Property**: MaxSpeed
  * **Value Offset**: 7501
  * **File**: `FSD\Content\WeaponsNTools\SentryGun\SentryGun_Engineer\PRJ_SentryOvercharge_Projectile`
  > Increased radius so the AoE will be a bit more useful. The Projectile Speed has been increased, making it a lot easier to hit the intended target.

### "Stubby" Voltaic SMG – Overclock – Turret Arc
* **Duration**: 15 > 20
  * **Class**: BP_EletrocutedSentry_C
  * **Property**: InitialLifeSpan
  * **Value Offset**: 551
  * **File**: `FSD\Content\WeaponsNTools\SentryGun\BP_EletrocutedSentry`
  > Increasing a bit the buff duration on each turret so you can have an arc that actually last about 15s.
* **Damage per Tick Min**: 4 > 7
  * **Class**: DotStatusEffectItem
  * **Property**: DamageAmount.Min
  * **Value Offset**: 380
  * **File**: `FSD\Content\LevelElements\RoomObjects\Hazards\ElectricPlant\STE_ElecticPlant_slowdown`
* **Damage per Tick Max**: 4 > 7
  * **Class**: DotStatusEffectItem
  * **Property**: DamageAmount.Max
  * **Value Offset**: 409
  * **File**: `FSD\Content\LevelElements\RoomObjects\Hazards\ElectricPlant\STE_ElecticPlant_slowdown`
  > Since it is based on the Electrocrystal file, this will increase their damage as well.<br>
  > Increased the damage from 20 to 35 per second (interval is 0.2), allowing it to kill a grunt in 3.2s and a slasher in 5.2s in hazard 4+.

### "Stubby" Voltaic SMG – Overclock – Turret EM Discharge
* **Area Damage**: 40 > 60
  * **Class**: DamageComponent
  * **Property**: RadialDamage
  * **Value Offset**: 1261
  * **File**: `FSD\Content\WeaponsNTools\SentryGun\BP_TurretEMPDischarge`
  > Allows to reach the Grunt breakpoint with 2 Sentries. With a single turrets, the Area Damage plus the electrocution will leave them with sliver of health left.

# Gunner
## Minigun-Balance-v6_U33H5_P
* **Source**: Update 33 Hotfix 5

### Overclock – Bullet Hell
* **Ricochet Chance**: 0.5 > 0.75
  * **Class**: HitscanBaseUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\GatlingGun\Overclocks\OC_BonusesAndPenalties\OC_Bonus_Ricochet_Gatling`

## Bulldog-Balance-v2_U33H5_P
* **Source**: Update 33 Hotfix 5

### Overclock – Chain Hit
* **Ricochet Chance (Weakpoint only)**: 0.33 > 0.66
  * **Class**: HitscanBaseUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\Revolver\Overclocks\OC_BonusesAndPenalties\OC_Bonus_ChainHitChance`

## BRT7-Balance-v6_U33H5_P
* **Source**: Update 33 Hotfix 5

### Overclock – Full Chamber Seal
* **Damage**: 1 > 2
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\BurstFirePistol\Overclocks\OCBonusPenalty\Bonus_Damage1_BRT`
* **Reload Time**: -0.2 > -0.3
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\BurstFirePistol\Overclocks\OCBonusPenalty\Bonus_ReloadTime_BRT`
  > Theses changes aim to buff a bit this OC to allow it to compete with the other clean OC Composite Casings.

### Overclock – Electro Minelets
* **DoT Duration**: 2 > 6
  * **Class**: STE_Electric_BurstPistolMines_C
  * **Property**: Duration
  * **Value Offset**: 352
  * **File**: `FSD\Content\WeaponsNTools\BurstFirePistol\Overclocks\OCBonusPenalty\STE_Electric_BurstPistolMines`
* **Magazine Size**: -6 > -12
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\BurstFirePistol\Overclocks\OCBonusPenalty\Penalty_ClipSize_BRT`
  > Theses changes allow for a much better crowd control without increasing the dps too much.

# Scout

## GK2-Balance-v7_U33H5_P
* **Source**: Update 33 Hotfix 5

### Base Weapon
* **Max Ammo**: 350 > 490
  * **Class**: WPN_AssaultRifle_C
  * **Property**: MaxAmmo
  * **Value Offset**: 11912
  * **File**: `FSD\Content\WeaponsNTools\AssaultRifle\WPN_AssaultRifle`
* **Clip Size**: 25 > 30
  * **Class**: WPN_AssaultRifle_C
  * **Property**: ClipSize
  * **Value Offset**: 11941
  * **File**: `FSD\Content\WeaponsNTools\AssaultRifle\WPN_AssaultRifle`

### Gear Modification – Tier 2 B – Expanded Ammo Bags
* **Max Ammo**: 100 > 90
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\AssaultRifle\UPG_AssaultRifle_MaxAmmo`

### Gear Modification – Tier 3 C – High Capacity Magazine
* **Clip Size**: 10 > 5
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\AssaultRifle\UPG_AssaultRifle_ClipSize`

### Overclock – Electrifying Reload
* **Damage**: -3 > -2
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\AssaultRifle\Overclocks\OC_BonusesAndPenalties\OC_Penalty_DMG_25P_Assault`
  > Reduced the Damage penalty, allowing to reach the Swarmer breakpoint with more builds.

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

## Boomstick-Balance-v4_U33H5_P
* **Source**: Update 33 Hotfix 5

### Overclock – Shaped Shells
* **Base Spread**: 0.65 > 0.55
  * **Class**: HitscanBaseUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\SawedOffShotgun\Overclocks\OC_BonusesAndPenalties\OC_Bonus_Spread_SawedOff`
* **Pellets**: -2 > -1
  * **Class**: MultiHitscanUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\SawedOffShotgun\Overclocks\OC_BonusesAndPenalties\OC_Penalty_Pellets-2_SawedOff`

## NUK17-Balance-v7_U33H5_P
* **Source**: Update 33 Hotfix 5

### Base Weapon
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

### Gear Modification – Tier 1 A – Expanded Ammo Bags
* **Max Ammo**: 100 > 50
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\UPG_DualMP_A_Ammo`
  > Halved the Max Ammo to match the shot cost reduction.

### Gear Modification – Tier 2 A – High Capacity Magazine
* **Clip Size**: 10 > 5
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\UPG_DualMP_B_ClipSize`
  > Halved the Clip Size to match the shot cost reduction.

### Gear Modification – Tier 4 C – Expanded Ammo Bags
* **Max Ammo**: 150 > 75
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\UPG_DualMP_D_Ammo_2`
  > Halved the Max Ammo to match the shot cost reduction.

### Overclock – Custom Casings
* **Clip Size**: 30 > 15
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\Overclocks\OC_BonusesAndPenalties\Bonuis_ClipSize15_DualMP`
  > Halved the Clip Size to match the shot cost reduction.

### Overclock – Cryo Minelets
* **Clip Size**: -10 > -5
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\Overclocks\OC_BonusesAndPenalties\Penalty_ClipSize-10_DualMP`
  > Halved the Clip Size to match the shot cost reduction.

### Overclock – Embedded Detonators
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
