# HE-Grenade-Balance-v2
* **Source**: Update 32 Hotfix 10

## Base Grenade
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
  > This change allows to  exceed the breakpoint to kill Glyphid Grunt Slasher, killing them in an area slighly bigger than the Maximum Damage Radius (2-2.1m).<br>
  > 140×1.3 = 182 > 177.3
* **Minimum Area Damage**: 0.2 > 0.35
  * **Class**: DamageComponent
  * **Property**: MinDamagePct
  * **Value Offset**: 555
  * **File**: `FSD\Content\WeaponsNTools\Grenades\HighExplosive\Grenade_HighExplosive`
  > This change allows to reach the Glyphid Grunt breakpoint in a larger radius, ~2.8m.
* **Carve Diameter**: 200 > 300
  * **Class**: ExplosionComponent
  * **Property**: CarveDiameterCM
  * **Value Offset**: 625
  * **File**: `FSD\Content\WeaponsNTools\Grenades\HighExplosive\Grenade_HighExplosive`
  > This change allows to use the grenade to mine some otherwise hard to reach minerals, without making it being to compete with TCF.
