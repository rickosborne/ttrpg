# Matt McKaig's Alternate Magic Rituals

**Note**: This document is not the definitive source for these alternate rules.
Only pieces and parts are included here, for the purposes of exploring the implications of the proposed rules.

Also, I've taken the approach of mostly looking at then through Del's eyes.
I'd have to put some additional thought into broader context for other mages.

## Alternate Casting Time

> Cast spells faster by trading against skill penalties: -5 to skill for every 1 sec faster, to a minimum of 1 sec casting time.

In practical terms, there are a few spells which could benefit from this as they are useful in combat but have multi-round casting times.
For Del:

* **Ice Dagger / Sphere**, 1-3 sec

  The proposal doesn't specify it, but let's presume you could use this to "compress" the time it takes to grow a projectile.
  This would let you take a -5 to do two rounds of growth in a single round, or -10 for all three rounds at once.
  
  This might have some very situational utility, mostly as a finishing move.
  Missile spells aren't usually constrained by time but by the FP cost, so dumping that much FP at once would be the opposite of what a mage would want to do in a fight.
  But maybe?
  
  A more potent impact might be taking a negative to skill (maybe the same -5) to allow the caster to take an Aim maneuver while casting — a bit like trying to concentrate on two things at once.
  
  The reverse, taking extra time to improve the skill, would likely not be very useful after the first round of combat.
  Missile spell skills will generally be at a high enough level to not benefit from the bonus, and the constraint for their throughput-vs-utility function is generally the defense of the target, not the skill of the initial spell.

* **Counterspell**, 5 sec

  Counterspell in GURPS is weird.
  It's not the blocking spell, Ward, but is intended more for cases like "disperse the conjured fire tornado".
  But it also has the requirement that the caster know the spell to be countered, so its utility is even further reduced.
  
  It seems unlikely to me that someone would have Counterspell at a high enough level to make the -5 to skill worth the 5 sec to 4 sec reduction, let alone a -10 or -15 to get it down to 3 or 2 sec.
  But this is more a problem with Counterspell than with the proposal.
  
  But since Counterspell is resolved as a contest, maybe the extra bonus to skill might be worth the extra time?
  This would be more true out of combat than in.

* **Shape Water**, 2 sec

  This could have some very interesting implications.
  Shape Water isn't generally thought of as a combat spell, but in combination with other spells it could be used tactically.
  For example, in combination with a Cleric's ability to bless, you could create what amounted to a holy water fire hose.
  Similarly, in combination with Freeze, you could make ice manacles or platforms, or basically become Marvel's Iceman.
  
  The time reduction doesn't seem like it would be huge here, but getting it down to 1 second, or effectively "instant" might open up the opportunity to use it as a blocking spell with some penalties.
  Maybe not useful for dungeons, but possibly quite interesting for pirate-y adventures at sea.

* **Levitation**, 2 sec

  Like Shape Water, the time reduction here could be used to argue for more defensive and tactical uses, especially when combined with the proposed changes to use Magery for calculating effective ST.
  This would allow for more real-time uses like grapples, etc.

### Counter-proposal: percentages

It might be interesting to change this around to allow for longer-cast-time spells.
For example, instead of "-5 to skill for every 1 sec faster", you might say "-1 to skill for every 10% reduction in casting time, down to a lower bound of 20% of the original casting time, or 1 sec, whichever is higher".
This would allow for hour-long spells to get done in 12 minutes if the caster took a -8 to skill.

The reverse might also be reframed to something like "get a +1 to skill for every additional 20% of time (minimum 1 sec) spent, up to a total of +3 to skill for an additional 60% time spent (minimum 3 sec)".
Hour-long spells turn into just under 100-minute spells for that +3.
That's also nice because it can help mitigate the frustration of burning an hour on a single bad dice roll.

## Alternate Energy Cost

> Trade FP against skill, taking a -2 to skill for each point of FP reduction down to 50% FP, or pay +1 FP for each +1 to skill, up to a max of +3.

Let's look at the numbers for the latter case first.

### Improving skill through increased fatigue

At best, a +1 to skill is a 12% swing, specifically when it improves a base 9 or 10 skill.
For 2 FP you could get +2 to skill, which could be a huge 25% swing against that same base 9.
That max 3 FP for +3 to skill could get you a 36% swing against base 8 or 9.

This feels a little underpowered for battle magic — I'd like to see some way of getting up to a 50% better chance of success, which you could almost get to by raising the cap to +4 skill from 4 FP.
That 4 FP would be a pretty large risk, but it might be worth it in the right situation.

But it would also be interesting for improvised non-combat magic.
In those situations the skill level is likely starting off pretty low, so investing some fatigue might make a significant difference.
Thematically, this also makes sense: you're going to throw a bunch of extra effort into something you've never tried before.

### Reducing fatigue through high skill

For the former case, we can relate it to the base rules of 1 FP reduction at 15 skill and 2 FP reduction at 20 skill.
You lose a little at the 15 SL end, because going from 15 to 13 adds 12% to your chance of failure.
At the 20 end, a drop to a 16 for the same 2 FP reduction is effectively no change, as a 17 or 18 is always a failure anyway.
Similarly, the drop from 25 to 19 for the 3 FP reduction is again no change.

Which means that we really need to look at 16 as the "break even" point for this change.
For 1 FP reduction, you break even at a base skill level of 18.
For 2 and 3 FP reduction, you break even at 20 and 22.
Thus we can see that this would be potentially beneficial for high-fatigue spells at levels above 22 or so.

So how would this work practically with the missile spells we saw above?
Under normal rules, a 15 skill gets the caster a 1d missile for free, or a 2d missile for 1 FP.
At 20 skill, the caster gets 2d for free, or 3d for 1 FP.
But that 3d is the max per turn when not combined with the alternate casting time proposal, which means you could not do more than 1 FP of reduction for missile spells with this proposal.
With the proposed rules, that 1 FP reduction at 15 skill now imposes a 12% risk of failure.
At 16 skill that risk goes down to 7%, then 4% at 17 skill.

This alternate FP reduction proposal is thus universally bad for missile spells.

There are two branches here for growing missile spells: do the initial skill roll and penalty affect the overall/total growth of the missile, or just the first round?
Affecting the total would be closer to the normal rules, but it might be more interesting to have the caster re-roll against their skill every round for the possibility of getting reduced fatigue costs at the risk of getting failures and having the spell blow up in their hands.

### Examples

Using Del's spells as examples:

* **Ice Dagger / Sphere**, 1-3 FP per turn

  The option to take additional fatigue for a skill bonus could be useful, but the skill penalties for fatigue reduction are objectively worse than under the normal rules.

* **Counterspell**, half countered spell

  If someone had Counterspell at 22 or better this _might_ make sense in situations where they were casting it often, say against a big boss.
  But Counterspell's casting time and knowledge requirements would make this scenario unlikely at best.

* **Catch Spell** 3 FP, **Return Missile** 2 FP

  These kinds of blocking spells would definitely benefit from the option to take additional fatigue to improve success.
  But the cost-to-benefit of the reverse would be poor unless the mage found themselves casting them often enough to justify the point investment of a 22 base skill or better.

* **Analyze Magic**, 8 FP

  I am already salty about the time and fatigue costs for this spell.
  One or the other would be fine, but the combination of the two is just insulting.
  (It has the same fatigue cost as _Instant Neutralize Poison_ but takes an hour.  Even _Suspended Animation_ costs less and only has a 30 sec casting time!)
  
  Would it benefit by trading skill for FP?
  It's already stupidly expensive, so maybe going from 8 FP to 11 FP might be worth the +3 to skill?
  This would likely be especially true in a ritual context.
  
  In the other direction, you could get Analyze Magic down to 4 FP by taking a -8 to skill.
  This is only break-even at 24 skill or better, but maybe mages with a gambling fixation might take the risk at lower levels?

Del doesn't have healing spells, but maybe Sorven's ridiculously high Major Healing skill might make this worth it?

