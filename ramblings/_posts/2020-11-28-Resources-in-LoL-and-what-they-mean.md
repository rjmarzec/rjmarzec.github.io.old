---
published: true
layout: post
comments: true
title: Resources in LoL and what they mean
tags: LoL
permalink: /game-design-ramblings/resources-in-lol-and-what-they-mean
---

Hi there! In this blog post, I'm going to discuss the different resources champions in League of Legends and what those resources mean for their gameplay. It doesn't sound the most exciting on the surface, but bare with me and hopefully I can turn it into something special.

So, for some ground work, what is LoL, and what do I mean by resources? By LoL, I mean the titan of online gaming that is the MOBA [League of Legends](leagueoflegends.com). If you're not living under a rock, you've probably heard about it to some capacity. In short, a game where 2 teams of 5 players fight back and forth to tear down each other's base by playing a character/champion of their choice to pilot their team to victory. Each champion has their own unique strengths and weaknesses, which gives the game its complexity. Among those differences you have the resources each character uses, by which I mean the cost each character has to pay to use their abilities.  

We can separate these resources into 3 main, distinct categories: mana, energy, and resourceless. One by one, lets dive into each and explain what makes them special.  

### Mana

First off, we have mana. You can think of mana as the default resource on champions, because it is by far and away the most popular, and for good reason. Mana can be described as a resource pool for abilities that has a high cap but low natural regeneration. In practice, this means that while characters with mana are able to spam their abilities if they so desire, they can't sustain that spamming for an extended period of time, as one they deplete their mana pool, they have to look for some external way to get it back, which usually means leaving your current fight and returning to your base.  

While I don't make it sound all too great here, mana makes it very nice to balance characters around playing in a very specific way in fights while not being too oppressive in the longer laning phase of the game. The jump to that thought is a bit much, so let me break it down. When designing fun characters, the best place to start is to have their kit be fun when used in teamfights, because a champion that fails to have a good role in fights will likely fall flat and won't be terribly fun. The important thing to note about teamfights is that they usually end up being short-medium length fights, which just so happens to be the ideal case for mana users. If a mana user comes into a teamfight with their full mana pool, they're in a position to use their abilities to maximize their value in terms of damage or support without having to worry about ability costs, since once the fight ends they likely won't need to use them again for a while afterwards. Spamming abilities is what the flow of most champions is built around, so having a champion with mana lets them play the way they were intended to in teamfights.  

As fun as spamming in teamfights is, it can become very problematic for balancing in the laning phase. For example, we probably don't want a character like Ziggs to be able to spam his waveclear abilities off cooldown starting from level 1 because that would mean he would be incredibly oppressive and unfun to play against early on, so we have mana to counteract this. Because the cost of having to get all your mana back is so high (it means missing out on gold from killing minions, exp from said minions, and opening up your opponent to do anything without pressure from you), Ziggs, or really any champion, ends up having to play around their mana costs early on and be more strategic beyond spamming to not hurt themselves. Instead, mana champions become much weaker than they could otherwise be going all out in a fight, putting them into a place where they aren't terribly broken while having moments of high intensity in their play patterns. If necessary, ability costs, passive mana regeneration, and maximum mana can all be fine tuned in order to further pull apart the power of champions to put them in a balanced state.

### Energy

Next up, we have energy, the resource reserved for a grand total of just 5 champions (Akali, Kennen, Lee Sin, Shen, and Zed). What's interesting is that energy is sort of the opposite of mana in some ways. Where mana champions usually have a large base mana pool, energy champions have a relatively small energy pool to work with. However, while mana champions usually have very low mana regeneration, energy champions have very high energy regeneration.  

How this plays out in game is that energy champions end up being able to use all their abilities in short bursts, but having to wait to build up their energy again afterwards in teamfights. This usually works great from a balancing perspective because most energy champions are either assassins or assassin-like, so they usually don't mind having to sit around after their accomplish their goals, so it plays nicely for them from a balancing perspective in fights. What is also interesting is that the high regeneration changes the playstyle dynamic in the laning phase: with high energy regeneration, energy champions are able to use their abilities constantly throughout the laning phase, as the cost of using their abilities is needing to wait a few seconds for the energy to come back, meaning their power in the laning phase is dictated by how strong their abilities are then.  

So while balancing around the laning phase may be more difficult, energy works as a great system to limit how powerful characters can be at bursting while letting their cooldowns be more loose to allow for cooler play making. Granted, designing with these limitations in mind can be pretty hard since you really need just the right fit, which is probably why we haven't seen many new energy champions since the original 5 were released a long time ago.

### Resourceless

And then one game designer said to he next, "but what if there were no costs?" Thats how resourceless champions came to be or something, I guess. Resourceless champions don't have any cost attached to their abilities beyond just the usual cooldowns on abilities. Resourceless champions trade some of the ease of balance in order to make the champions more exciting to play, since not having a resource to manage ever lets players focus on the fun parts of the champions they pilot: doing cool things with their abilities. Before going any deeper I'll note that most resourceless champions technically do have some alternate resource that plays into their kit, but just not as the resource they have to spend to cast abilities. In those cases, they usually play out very similarly to true resourceless champions, so for this discussion I'll treat them all the same.

Because they never have to worry about costs, resourceless champions get to have the best parts of mana and energy champions. Both in teamfights and in lane they to have fun throwing out abilities with no worries in the world. They have no need to worry about having to worry about regeneration, so when laning they can spam their abilities since they will be able to use it again at no cost when the ability is back up. In teamfights, they aren't limited by a maximum amount of resource, so they again get to spam. This often leads to designs with lots of small cooldowns that let players get creative because low cooldowns with costs would otherwise end up with players having a rough time managing between their damage and costs, but having no costs makes everything real easy.  

For as fun as the being resourceless can be, the nightmare comes in the form of how to balance a character that acts the same way in teamfights and laning phase, when unlimited power in the laning phase spells a disaster. Usually this can be mitigated by have abilities start of weak before they get leveled or have them scale well with items. Another strategy could be to push a lot of power into their ultimate abilities, which they don't get access too very early on in the laning phase, while still keeping that power intact for larger fights.  

### To spam or not to spam

A common theme across all these resources is that they all how much champions are able to spam their abilities in different scenarios as follows:
- Many casts in lane + Many casts in fights: Resourceless
- Many casts in lane + Few casts in fights: Energy
- Few casts in lane + Many casts in fights: Mana
- Few casts in lane + Few casts in fights: ???  

As I've rambled through in this post, there are lots of ups and downs to all of them with regards to power and balancing, but to end it off I want to explore what that ??? could be, since it's an interesting area not really much explored. If we expand the definition of "Few casts in lane" to be more like "only very thoughtful ability casts in lane," we actually do have an example of such a champion/resource: Rumble/heat!  

Rumble's heat operates in a way very different than any other champion's. Instead of depleting resource, Rumble's abilities generate heat when cast, with heat depleting over time. There is usually no downside to generating heat, but if Rumble ever maxes out his heat, he silences himself for a few seconds while gaining massive on-hit damage over the duration. On top of all this, Rumble's abilities also get powered up if he is at or above 50% of his maximum heat, so Rumble usually spams random abilities to maintain his heat without going over.  

So what does this mean for Rumble in lane and in fights? Well, in lane this means that Rumble casts a lot of abilities, but most of the time he doesn't use them to do anything, leading to just a few moments where he uses the heat he maintains to actually impact what he is doing (It's a bit of stretch sure, but work with me on this one). In team fights, it's a bit of the same. Rumble doesn't want to be spamming all his abilities in team fights because doing so means that he becomes useless for a few seconds while silenced since he usually won't be able to use that on-hit damage. Instead, in teamfights Rumble has to be very careful about when he uses his abilities because he really needs to few casts he can make count for as much as possible, leading him to make very few ability casts intended to deal damage.

### The main points

As the blog name implies, I figure that I probably rambled on for a bit much and typed out some incoherent thoughts over the course of writing this, so I would like to go over some of the takeaways from this discussion:
- Resources in League of Legends have a lot more depth to them than it might look like on the surface
- Champions with Mana, Energy, no Resource, and even Heat all conduct themselves very differently in practice due to how they are limited by their resources in different ways from one another
- Alongside how different resources make different champions act differently inside of the game, we also have to consider how different resources can affect how you may have to balance champions. Sure, maybe resourceless champions may be more fun because they do more, but they are harder to adjust without breaking than simply changing mana costs and base mana to tweak how powerful mana champions are in lane  

I'll also remind you that all this complexity comes before we even get into considering how cooldowns and items play into all of this, kind of throwing everything for a loop. However, putting those aside to look at a fundamental underlying system hopefully lets us better understand why certain champions have the resource system that they do from the designer point of view. While everything discussed was specific to LoL, thinking about how we can limit what players do though different means is super important to making games what you want them to be. In that sense, I hope you could take some interesting thoughts about all this moving forward to maybe use yourself or appreciate the thinking behind the games you play that much more.  

That's all for my first game design rambling, hopefully the not the last of many interesting write-ups. Thanks for reading this far, and I hope you can find more content in this blog to enjoy. Feel free to share your thoughts on it all in whatever way you find to contact me.  
-Robert
