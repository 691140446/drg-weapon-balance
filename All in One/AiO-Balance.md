# Information
This All in One mod will contain the main changes (mostly from Silaise version when there is several possibliities) from this repository. If you wish to use any alt version, you can simply use the alt mod on top of this one, it will overwrite just the needed value and be loaded in the good order by default.

# Driller
## Flamethrower-Balance-v6
* **Source**: Update 32 Hotfix 10

### Gear Modification – Tier 4 A – It Burns!
* **Fear Factor**: 0.13 > 0.2
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\FlameThrower\UPG_Flamethrower_D_Fear`
  > This increases the fear chance per fuel spent from 6.5% to 10% versus Glyphid Grunts and Glyphid Praetorians, increasing the chance to Fear them from ~33% to ~47% with the base flow rate.

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
  > The Face Melter changes aim to increase the damage output while keeping a good ammo economy.

## Subata-Balance-v3
* **Source**: Update 32 Hotfix 11

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
  > This change aim to improve the feeling of the weapon with this Overclock equiped.

## EPC-Balance-v6
* **Source**: Update 32 Hotfix 10
> The changes on this weapon are heavily focused on the Flying Nightmare mod.<br>
> Increasing the Charged Shot damage by 20% allows to reach the Glyphid Grunt breakpoint with a full damage build and using Overcharger on top of that allows to reach the Mactera Spawn breakpoint thanks to the change on the damage conversion.<br>
> Alternatively the reduced cost of the charged shot allows to go for a build with lower damage and a wider radius, chaining two shot since the weapon doesn’t overheat instantly.
### Base Weapon
* **Heat per Charged Shot**: 1.0 > 0.7
  * **Class**: WPN_ChargeBlaster_C
  * **Property**: HeatPerChargedShot
  * **Value Offset**: 17553
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\WPN_ChargeBlaster`
  > This change allows to chain two shots to open up some build with low (no Grunt breakpoint) damage on Flying Nightmare.
### Base Weapon
* **Charged Shot Damage (Single Target)**: 60 > 72
  * **Class**: DamageComponent
  * **Property**: Damage
  * **Value Offset**: 12955
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\PRJ_ChargedBlasterShot`
### Gear Modification – Tier 1 C – Higher Charged Plasma Energy
* **Charged Shot Damage / Area Damage**: 15 > 18
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 54
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\UPGEffect_ChargeBlaster_ChargeDirectDMG_1`
### Gear Modification – Tier 2 C – Reactive Shockwave
* **Charged Shot Damage / Area Damage**: 15 > 18
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 54
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\UPGEffect_ChargeBlaster_ChargeDirectDMG_2`
  > The changes above increase the Charged Shot direct damage and Flying Nightmare damage by 20%, allowing to reach the Glyphid Grunt breakpoint if both damage upgrade are taken.
### Base Weapon
* **Damage Conversion to Fire (Percentage)**: 0.2 > 0.45
  * **Class**: DamageConversionBonus
  * **Property**: ConversionPercentage
  * **Value Offset**: 13750
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\PRJ_ChargedBlasterShot`
  > This change affects the Charged Shot direct damage, AoE damage and the Flying Nightmare damage, allowing to reach the Mactera Spawn breakpoint on a full damage build with Overcharger.
### Overclock – Overcharger
* **Charged Shot Cost (Multiplier)**: 1.5 > 1.3
  * **Class**: ChargedWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\ChargeBlaster\Overclocks\OC_BonusAndPenalty\OC_Penalty_ChargeCost_EPC`
  > This change gives Overcharger a better ammo economy to make it usable on more builds.

## HE-Grenade-Balance-v2
* **Source**: Update 32 Hotfix 10

### Base Grenade
* **Max Grenades**: 4 > 6
  * **Class**: Grenade_HighExplosive_C
  * **Property**: MaxGrenades
  * **Value Offset**: 279
  * **File**: `FSD\Content\WeaponsNTools\Grenades\HighExplosive\Grenade_HighExplosive`
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

## HE-Grenade-Balance-v2
* **Source**: Update 32 Hotfix 10

### Base Grenade
* **Max Grenades**: 4 > 6
  * **Class**: Grenade_HighExplosive_C
  * **Property**: MaxGrenades
  * **Value Offset**: 279
  * **File**: `FSD\Content\WeaponsNTools\Grenades\HighExplosive\Grenade_HighExplosive`
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
## Warthog-Balance-v3
* **Source**: Update 32 Hotfix 10

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

## Stubby-Balance-v2
* **Source**: Update 32 Hotfix 10

### Overclock – Turret EM Discharge
* **Damage**: -3 > -2
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\SMG\Overclocks\OC_BonusesAndPenalties\Penlaty_DMG-3_SMG`

## PGL-Balance-v3
* **Source**: Update 32 Hotfix 10

### Base Weapon
* **Area Damage**: 110 > 125
  * **Class**: DamageComponent
  * **Property**: RadialDamage
  * **Value Offset**: 18276
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\PRJ_GrenadeLauncher`
* **Maximum Damage Radius**: 150 > 200
  * **Class**: DamageComponent
  * **Property**: MaxDamageRadius
  * **Value Offset**: 18392
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\PRJ_GrenadeLauncher`
* **Minimum Area Damage**: 0.15 > 0.30
  * **Class**: DamageComponent
  * **Property**: MinDamagePct
  * **Value Offset**: 18334
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\PRJ_GrenadeLauncher`

### Gear Modification – Tier 1 A – HE Compound
* **Area Damage**: 15 > 20
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\UPG_GrenadeLauncher_A_Damage`

### Gear Modification – Tier 2 A – Larger Payload
* **Max Ammo**: 3 > 2
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\UPG_GrenadeLauncher_B_Ammo`
* **Max Ammo**: 3 > 2
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\UPG_GrenadeLauncher_B_Ammo.uexp`

### Overclock – Compact Rounds
* **Max Ammo**: 4 > 5
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\GrenadeLauncher\Overclocks\OC_BonusAndPenalty\Bonus_Ammo4_PGL`

## BC-Balance-alt-Silaise-v7
* **Source**: Update 32 Hotfix 10

### Gear Modification – Tier 2 A – Expanded Ammo Bags
* **Max Ammo**: 6 > 3
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\LineCutter\UPG_LineCutter_B_Ammo1`

### Gear Modification – Tier 5 A – Explosive Goodbyes
* **Area Damage**: 40 > 120
  * **Class**: DamageComponent
  * **Property**: RadialDamage
  * **Value Offset**: 26263
  * **File**: `FSD\Content\WeaponsNTools\LineCutter\PRJ_LineCutter2`

### Overclock – Stronger Plasma Current
* **Damage per Tick (Additive)**: 1 > 2
  * **Class**: DamageUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\LineCutter\Overclocks\OC_BonusesAndPenalties\Bonus_DMG+1_LineCutter`

### Overclock – Return to Sender
* **Max Ammo**: -6 > -3
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\LineCutter\Overclocks\OC_BonusesAndPenalties\Penalty_Ammo-4_LineCutter`
  > File shared with Inferno

### Overclock – Inferno
* **Max Ammo**: -6 > -3
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 25
  * **File**: `FSD\Content\WeaponsNTools\LineCutter\Overclocks\OC_BonusesAndPenalties\Penalty_Ammo-4_LineCutter`
  > File shared with Return to Sender

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

## Sentry-Balance-v6
* **Source**: Update 32 Hotfix 10

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

### "Stubby" Voltaic SMG – Overclock – Turret Arc
* **Duration**: 15 > 20
  * **Class**: BP_EletrocutedSentry_C
  * **Property**: InitialLifeSpan
  * **Value Offset**: 551
  * **File**: `FSD\Content\WeaponsNTools\SentryGun\BP_EletrocutedSentry`
* **Damage per Tick Min**: 4 > 7
  * **Class**: DotStatusEffectItem
  * **Property**: DamageAmount.Min
  * **Value Offset**: 380
  * **File**: `FSD\Content\LevelElements\RoomObjects\Hazards\ElectricPlant\STE_ElecticPlant_slowdown`
  > Since it is based on the Electrocrystal file, this will increase their damage as well.
* **Damage per Tick Max**: 4 > 7
  * **Class**: DotStatusEffectItem
  * **Property**: DamageAmount.Max
  * **Value Offset**: 409
  * **File**: `FSD\Content\LevelElements\RoomObjects\Hazards\ElectricPlant\STE_ElecticPlant_slowdown`
  > Since it is based on the Electrocrystal file, this will increase their damage as well.

### "Stubby" Voltaic SMG – Overclock – Turret EM Discharge
* **Area Damage**: 40 > 60
  * **Class**: DamageComponent
  * **Property**: RadialDamage
  * **Value Offset**: 1261
  * **File**: `FSD\Content\WeaponsNTools\SentryGun\BP_TurretEMPDischarge`

# Gunner
## Minigun-Balance-v5
* **Source**: Update 32 Hotfix 10

### Overclock – Bullet Hell
* **Ricochet Chance**: 0.5 > 0.75
  * **Class**: HitscanBaseUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\GatlingGun\Overclocks\OC_BonusesAndPenalties\OC_Bonus_Ricochet_Gatling`

## Bulldog-Balance-v1
* **Source**: Update 32 Hotfix 11

### Overclock – Chain Hit
* **Ricochet Chance**: 0.33 > 0.66
  * **Class**: HitscanBaseUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\Revolver\Overclocks\OC_BonusesAndPenalties\OC_Bonus_ChainHitChance`

## BRT7-Balance-v4
* **Source**: Update 32 Hotfix 10

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

### Overclock – Electro Minelets
* **DoT Duration**: 2 > 6
  * **Class**: STE_Electric_BurstPistolMines_C
  * **Property**: Duration
  * **Value Offset**: 352
  * **File**: `FSD\Content\WeaponsNTools\BurstFirePistol\Overclocks\OCBonusPenalty\STE_Electric_BurstPistolMines`
* ** DoT Duration**: 2 > 6
  * **Value Offset**: 352
  * **File**: `FSD\Content\WeaponsNTools\BurstFirePistol\Overclocks\OCBonusPenalty\STE_Electric_BurstPistolMines.uexp`
* **Magazine Size**: -6 > -12
  * **Class**: AmmoDrivenWeaponUpgrade
  * **Property**: Amount
  * **Value Offset**: 66
  * **File**: `FSD\Content\WeaponsNTools\BurstFirePistol\Overclocks\OCBonusPenalty\Penalty_ClipSize_BRT`

# Scout
## GK2-Balance-v4
* **Source**: Update 32 Hotfix 10

### Base Weapon
* **Max Ammo**: 350 > 420
  * **Class**: WPN_AssaultRifle_C
  * **Property**: MaxAmmo
  * **Value Offset**: 11886
  * **File**: `FSD\Content\WeaponsNTools\AssaultRifle\WPN_AssaultRifle`
* **Clip Size**: 25 > 30
  * **Class**: WPN_AssaultRifle_C
  * **Property**: ClipSize
  * **Value Offset**: 11915
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

## M1000-Balance-v5
* **Source**: Update 32 Hotfix 10

### Base Weapon
* **Weakpoint Damage Multiplier**: 1.1 > 1.2
  * **Class**: DamageComponent
  * **Property**: WeakpointDamageMultiplier
  * **Value Offset**: 13009
  * **File**: `FSD\Content\WeaponsNTools\BoltActionRifle\WPN_M1000`

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

## Boomstick-Balance-v2
* **Source**: Update 32 Hotfix 6

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

## NUK17-Balance-v6
* **Source**: Update 32 Hotfix 10

### Base Weapon
* **Shot Cost**: 2 > 1
  * **Class**: WPN_DualMPs_C
  * **Property**: ShotCost
  * **Value Offset**: 11562
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\WPN_DualMPs`
  > To change the shot cost from 2 to 1.
* **Max Ammo**: 600 > 300
  * **Class**: WPN_DualMPs_C
  * **Property**: MaxAmmo
  * **Value Offset**: 11504
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\WPN_DualMPs`
  > Halved the Max Ammo to match the shot cost reduction.
* **Clip Size**: 50 > 25
  * **Class**: WPN_DualMPs_C
  * **Property**: ClipSize
  * **Value Offset**: 11533
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\WPN_DualMPs`
  > Halved the Clip Size to match the shot cost reduction.
* **Max Horizontal Spread**: 36 > 29
  * **Class**: HitscanComponent
  * **Property**: MaxHorizontalSpread
  * **Value Offset**: 16202
  * **File**: `FSD\Content\WeaponsNTools\DualMachinePistols\WPN_DualMPs`
  > To reduce base spread by ~20%.

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
