There are various ways to interact with your pet. But first, you will need to capture one. Here is how:

## How to capture a pet
Find the animal you want to capture, it can be any friendly mob that you want to tame. Once you have your target in sight, approach them slowly. You will need them to be below a certain health treshold. I am not going to state it here, as I would like you to experiment with this mechanic.

Once the target is below required treshhold, left click them with a leash (lead) and voila; the pet is now yours.

## Pet Skills
Pets may learn several skills such as:

- Backpack
> This skill adds a Backpack to your pet. It can be opened by using the /petinventory command. Items in this inventory will not be dropped when the pet dies unless it's enabled in the skilltree skill settings.
Items picked up by your pet will be added to this inventory. Line added by skill upgrade will add 9 extra slots (up to 54 slots).

- Beacon
> The Beacon skill transforms your pet in a walking and more powerfull beacon. For administration of the buffs the plugin uses a custom menu (see Beacon Buff Selection Menu) that can be opened with the /petbeacon command. By default this skill consumes food when it is active, that means the Saturation-Value decreases continuously while the skill is active.

- Behavior
> With this skill you can change the behavior of the pet. There are **5** possible behavior-modes:
    * Friendly -> Doesn't fight, even when attacked by anything
    * Normal -> Like a neutral wolf.
    * Aggressive -> Attacks everything within 15 blocks of the owner.
    * Farm -> Atacks every Monster within 15 blocks of the owner
    * Raid -> like normal but the pet doesn't attack players and their minions
    * Duel -> pets will attack other pets with aktive duel behavior within a 5 block radius

To toggle the mode type `/petbehavior <normal/friendly/aggressive/farm/raid/duel>`.

- Control
> With this skill you have more control about where you pet walk and what the pet attacks. To use this you have to rightclick with the Control item anywhere you want the pet has to walk to. The item for this skill is a stick.

- Damage
> This skill increases the damage the pet can do. 1 damage point equals to half a heart.

- Fire
> With this skill your pet has a chance to set targets on fire for a short period.

- Heal
> With this skill your pet heals skill itself every few seconds.

- Knockback
> With this skill your pet has a chance to knockback when attacking a target.

- Life
> This skill will increase the max hitpoints the pet can have.

- Lightning
> With this skill your pet has a chance to let a lightning strike at the target.

- Pickup
> With this skill your pet can pickup items (and XP) that lie on the ground. The items are added to the backpack of the pet. This skill can not be activated if the pet doesn't have the **Backpack Skill** with at least 1 row.
Pickup can be enabled/disabled by using `/petpickup` command.

- Poison
> With this skill your pet has a chance to poison targets for a short period.

- Ranged
> With this skill your pet will shot projectiles at their targets that cause damage to them.
**Projectiles**
  - Arrow

  - Egg

  - Wither Skull
 
  - Snowball

  - Small Fireball

  - Large Fireball

*All projectiles deal the same amount of damage that is set by the skill. The only difference is the trajectory of some projectiles.*

- Ride
> With this skill you can ride your pet. To mount your pet right-click your pet with a lead. The controls while riding your pet is like you would ride a horse.

- Shield
> With this skill your pet can shield (some) damage from you and redirect it to itself.

- Slow
> With this skill your pet has a chance to slow his target down for a some seconds.

- Sprint
> With this skill your pet starts sprinting the first time it starts to follow a new target.

- Stomp
> With this skill your pet has a chance to stomp on the ground and damage all enemies around the pet.

- Thorns
> With this skill your pet has a chance to reflect the half of the incoming damage back to the damager.

- Wither
> With this skill your pet has a chance to wither his target for a some seconds.    

## Hunger System

Hunger System is based on saturation. The saturation is a value between 1 and 100, where 100 is the best and 1 is the worst. After a period of time the saturation decreases and affects other stats of your pet. In conclusion, feed your pet nerd.

| Hunger Points | Hitpoints on Respawn |
|---------------|----------------------|
| 100-91        | 100%                 |
| 90-81         | 90%                  |
| 80-71         | 80%                  |
| 70-61         | 70%                  |
| 60-51         | 60%                  |
| 50-41         | 50%                  |
| 40-31         | 40%                  |
| 30-21         | 30%                  |
| 20-11         | 20%                  |
| 10-2          | 10%                  |
| 1             | 1 HP                 |

## Skills Affected By Hunger
**Beacon**

The lower the saturation the less is the range of the beacon effect.

**Ride**

The lower the saturation the slower your pet will run when you ride it.