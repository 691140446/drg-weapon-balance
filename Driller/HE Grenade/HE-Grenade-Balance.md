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
