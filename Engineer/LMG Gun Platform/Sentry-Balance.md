# Sentry-Balance-v6
* **Source**: Update 32 Hotfix 11

## "Warthog" Auto 210 – Gear Modification – Tier 5 A – Turret Whip
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

## "Stubby" Voltaic SMG – Overclock – Turret Arc
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

## "Stubby" Voltaic SMG – Overclock – Turret EM Discharge
* **Area Damage**: 40 > 60
  * **Class**: DamageComponent
  * **Property**: RadialDamage
  * **Value Offset**: 1261
  * **File**: `FSD\Content\WeaponsNTools\SentryGun\BP_TurretEMPDischarge`
