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
