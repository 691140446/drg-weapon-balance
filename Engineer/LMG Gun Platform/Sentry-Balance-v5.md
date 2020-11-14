# Sentry-Balance-v5
* **Source**: Update 32 Hotfix 9

## "Warthog" Auto 210 – Gear Modification – Tier 5 A – Turret Whip
* **Maximum Damage Radius**: 150 > 200
  * **Variable Name**: MaxDamageRadius
  * **Value Offset**: 6971
  * **File**: `FSD\Content\WeaponsNTools\SentryGun\SentryGun_Engineer\PRJ_SentryOvercharge_Projectile`
* **Damage Radius** (DamageRadius): 150 > 200
  * **Variable Name**: DamageRadius
  * **Value Offset**: 6942
  * **File**: `FSD\Content\WeaponsNTools\SentryGun\SentryGun_Engineer\PRJ_SentryOvercharge_Projectile`
* **Initial Projectile Speed** (InitialSpeed): 5000 > 7500
  * **Variable Name**: InitialSpeed
  * **Value Offset**: 7472
  * **File**: `FSD\Content\WeaponsNTools\SentryGun\SentryGun_Engineer\PRJ_SentryOvercharge_Projectile`
* **Max Projectile Speed**: 5000 > 7500
  * **Variable Name**: MaxSpeed
  * **Value Offset**: 7501
  * **File**: `FSD\Content\WeaponsNTools\SentryGun\SentryGun_Engineer\PRJ_SentryOvercharge_Projectile`

## "Stubby" Voltaic SMG – Overclock – Turret Arc
* **Duration**: 15 > 20
  * **Variable Name**: InitialLifeSpan
  * **Value Offset**: 551
  * **File**: `FSD\Content\WeaponsNTools\SentryGun\BP_EletrocutedSentry`
* **Damage Min**: 4 > 7
  * **Variable Name**: DamageAmountMin
  * **Value Offset**: 380
  * **File**: `FSD\Content\LevelElements\RoomObjects\Hazards\ElectricPlant\STE_ElecticPlant_slowdown`
  > Since it is based on the Electrocrystal file, this will increase their damage as well.
* **Damage Max**: 4 > 7
  * **Variable Name**: DamageAmountMax
  * **Value Offset**: 409
  * **File**: `FSD\Content\LevelElements\RoomObjects\Hazards\ElectricPlant\STE_ElecticPlant_slowdown`
  > Since it is based on the Electrocrystal file, this will increase their damage as well.

## "Stubby" Voltaic SMG – Overclock – Turret EM Discharge
* **Damage**: 40 > 60
  * **Variable Name**: RadialDamage
  * **Value Offset**: 1261
  * **File**: `FSD\Content\WeaponsNTools\SentryGun\BP_TurretEMPDischarge`
