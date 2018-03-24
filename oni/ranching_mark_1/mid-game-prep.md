---
title: ONI - Mid-game Prep
layout: guide
description: An ONI guide written for Ranching Upgrade Mk. 1
toc: sections
root: "./#sections"
---

# Sections
* [Assembling Your Crew](index#assembling-your-crew) - picking a good initial set of Dupes.
* [A New World](index#a-new-world) - how to survive the early game.
  * [What Do I Have?](index#what-do-i-have)
  * [What Do I Need?](index#what-do-i-need)
  * [Sanitation](index#sanitation)
  * [Critical Storage](index#critical-storage)
  * [Research, Jobs, and Oxygen Production](index#research-jobs-and-oxygen-production)
  * [Careful Dupe Selection](index#careful-dupe-selection)
  * [Farming, Foraging, and Cooking](index#farming-foraging-and-cooking)
  * [Stress Mitigation](index#stress-mitigation)
* [Long-Term Survival Issues](#long-term-survival-issues)
  * [Heat](#heat)
  * [Water](#water)
  * [Power vs Time](#power-vs-time)
  * [Space](#space)
    * [The Swamp Biome](#the-swamp-biome)
    * [The Caustic Biome](#the-caustic-biome)
* [Moving to the Midgame](#moving-to-the-midgame)
  * [Establish Plumbing](#establish-plumbing)
  * [Enhancing Airflow](#enhancing-airflow)
  * [Bristle Farming](#bristle-farming)
  * [Advanced Power Generation](#advanced-power-generation), early Carbon Dioxide processing.
  * [Cooking Tools Upgrade](#cooking-tools-upgrade)

# Long-Term Survival Issues

The previous part of the guide titled ["A New World"](./#a-new-world) established all the basic principles necessary for a base to achieve relative stability for about 50 or cycles.  Without addressing any new issues, you will have plenty of time to experiment with random aspects of the game and test out your own designs, so feel free to do so!

However, to push beyond this point toward long-term survival requires planning for and managing four new critical issues for your base:

* Heat
* Water
* Power vs Time
* Space

You probably won't experience problems with these issues at Cycle 10 or Cycle 20, but what you do now can largely affect the urgency of these issues for your base come Cycle 100, if not Cycle 60.

## Heat

You've probably noticed that the game reports a temperature for _everything_.  Oxygen, Sandstone, and even your Dupes if you bother to check their body temperature.  Speaking of which, as you move into new biomes in the game, some are so hot or cold that they can give your Dupes heat stroke or hypothermia from overexposure over time!

This being stated, the following are the two largest impacts that Heat is likely to have on your base:

* Farming
    - Every farmable plant has a preferred temperature zone for growth.  Too hot or cold, and the plants won't grow.
    - This varies per plant, so be sure to check out the requirements for any farm you go to build!
* Machinery
    - Nearly every piece of machinery generates heat - too much of it, and your machinery will become damaged over time from overheating!

The game simulates heat transfer over time; an area of your base that starts off nice and cool for Mealwood and Bristle Blossom farming may not always stay that way!  Be careful to keep major sources of heat away from your farms!

One of the unintuitive aspects of this game is that thermodynamics isn't always perfectly preserved - as an example, Electrolyzers always produce their output gases at 70 C, regardless of the input temperature, while Water Sieves output clean Water at 40 C.  Make sure to read up on any machinery converting one resource to another for any similar behavior that could dramatically affect your base!

## Water

Another critical aspect of the game is water resource management; your initial supplies of clean water may be large, but they are also finite.  Furthermore, as you continue to unlock Researches, you may notice that research itself consumes quite a quantity of water!  Likewise for Liceloaf - each batch requires 50 kg Water!  Furthermore, you will likely need to swap from Algae-based Oxygen production to Water-based Oxygen production with Electrolyzers, which provides a critical link between your Water supplies and your Oxygen supplies.  Finally, Water is also needed to run Carbon Skimmers, which are the only practical way to remove Carbon Dioxide outright from your base until the late-game!  Strive to make sure you keep enough Water around to keep your base alive and thriving; either this or Heat will generally be your most pressing issue for a long time.

Unfortunately, the quantity of Water at your disposal is hardly the only issue you'll face moving forward.  As you begin to automate your sanitation needs via plumbing, Lavatories, and Sinks, you'll note that your sanitation system outputs contaminated Polluted Water; Water Sieves will do nothing to disinfect the water!  Fortunately, the Electric Grill (the higher-tier Food preparation building) disinfects Food during cooking, but other potential uses of your water supply could pose problems, such as if Slimelung got into your Electrolyzer's Water supply.

Furthermore, note that liquid resources tend to have the highest in-game density when utilized in your base.  As such, the heat (or cold) that your Water and Polluted Water reserves hold tends to affect neighboring parts of the base.  Even more significant is that any plants that require constant Water/Polluted Water supply will be _greatly_ affected by their liquid's incoming temperature.  In general, the temperature of a farm's Water supply will _become_ the temperature of that Farm or something very close; focus on your supply's temperature to keep the farm in check!

To emphasize:

> In general, the temperature of a farm's Water supply will _become_ the temperature of that Farm.

Take great care to manage your Water temperature where it matters!

Polluted Water tends to pose two issues:

* It slowly evaporates directly into Polluted Oxygen over time; large concentrations of this can be bad for Duplicant health, especially if they become contaminated with Slimelung.
* Converting it into Water with a Water Sieve produces Water that is too hot for farms that would rely upon it.

## Power vs Time

One of the wonderful aspects of this game is how it facilitates the automation of many different aspects of running your base.  Much of this is, of course, at the cost of Power consumption.  At first, the only Power production you have is through Manual Generators, which trades Duplicant time for Power to facilitate production of various early-game needs.  As you continue in the game, you will unlock more advanced Generators that need only to be supplied with resources to produce Power over time.

The problem?

* These Generators tend to consume potentially-limited resources.
* They generate non-neglible amounts of Heat and produce other, non-desirable byproducts like Carbon Dioxide or Polluted Water.
  - While the Hydrogen generator has no such issue, your Hydrogen supply tends to be quite limited, as you can only renew it if your Dupes consume enough Oxygen for the Electrolyzer to run.
* While having a nice, constantly-running generator set is nice, running Power wires out to the various parts of your base in need of Power can get tedious and/or tricky.
* Before you get Automation up, you can easily waste precious resources if you can't use all of the generated Power!

When you first begin to build in an isolated area, consider running Power buildings off of Manual Generation until you have a greater need for constant Power there.  That said, this does restrict how useful your Dupes can be otherwise, so try to restrict how much this technique is utilized at any given time.  On the other hand, Coal Generation tends to be relatively low-impact, but it does generate considerable Heat.  Try to keep them away from Farms and make sure there's a way for the Carbon Dioxide to escape to your Carbon Skimmer setup somewhere below.  Of course, you _could_ pump the Carbon Dioxide somewhere else, but keep in mind that doing so will consume Power.  There's always a tradeoff to be considered!

While it may be tempting to substantially increase your Duplicant count in order to "do more" within your base, such as having more Dupes around to handle Power generation, this comes at the heavy cost of Oxygen and Food over time; the more Dupes you have, the faster you will have to swap from Algae-based Oxygen production and the sooner you will run into issues with Water.  Old issues and mechanics do not go away; the number of balls you have to juggle only goes up.

## Space

As you progress through the game, you will progressively expand your base to utilize most of your initial biome.  As you do this, take care to position your "Hot" buildings away from your Farms.  Space, or distance, is one of your more powerful tools in keeping critical areas (like your farms) at the correct temperature.  In fact, it can be quite advantageous to put many of those Heat-producing buildings outside of your initial biome.

Either way, the time will come when you must start utilizing areas that initially pose inconvenient problems...

### The Swamp Biome

![The "Swamp" Biome.](img/toxic-biome.png){:class="img-responsive"}

Pros:
* Its temperature is ideal for your Duplicants and much of your base.
* This biome holds lots of Gold, the best Metal Ore to use for machinery prone to overheating.
* This is where to find Thimble Reeds, the primary material for making Clothing and Exosuits that help when exploring the other biomes.

Cons:
* Has huge quantities of Slime and the germ Slimelung - don't let the latter get into your main base!
  - However, when cleansed, Slime can be transformed into extra Algae!

Other:
* Often has pockets of over-pressurized Polluted Oxygen.  But, with some foresight and planning, these pools can typically be converted into large amounts of (relatively) clean Oxygen for your base!  (All hail the Deodorizer!)

### The Caustic Biome

![The "Caustic" Biome.](img/caustic-biome.png){:class="img-responsive"}

Pros:
* No germs!
* This biome contains Balm Lilies, which can be used to produce immune-system boosting supplements for your Dupes.
* Contains lots of Chlorine, quite useful for disinfection of solids from the Swamp Biome.
* Contains significant amounts of directly-usable Algae.

Cons:
* Contains no Oxygen - only Hydrogen and Chlorine, which tends to mess with your existing environment management schemes.
* Is too hot for your core Food farms.


* Space between base components helps to buffer the temperature.
* As the base becomes more complex, more space needs to be alloted for automation infrastructure.

---

While other biomes do exist, only the Swamp and Caustic biomes will be on the borders of your base.

# Moving to the Midgame

Now that we've covered the core issues that we must face to proceed further in the game, it's time to actually _do_ something about these issues.  For those of you who like "how-to" lists, here's my suggested approach to tackling these issues, starting where we left off from the [A New World](./#a-new-world) section of this guide.  I'll focus on the main tasks here, though each section will also contain other updates and pointers from how I've managed this guide's base, which are listed below as sub-points.

I'll explain my decision making with each section and note the critical researches.  If you've already completed them, I advise looking ahead to the next section's needed research before stopping research tasks.

1. [Establish Plumbing](#establish-plumbing)
  * [Enhancing Airflow](#enhancing-airflow)
2. [Bristle Farming](#bristle-farming)
3. [Advanced Power Generation](#advanced-power-generation)
  * Includes early Carbon Dioxide processing.
  * [Cooking Tools Upgrade](#cooking-tools-upgrade)
  * [Sealed Construction](#sealed-construction)
  * [Hidden Geysers?](#a-hidden-geyser)

## Establish Plumbing

![The eventual reservoir!](img/to-be-reservoir.png){:class="img-responsive"}

As you may recall, one of the earliest steps was to establish a basic, hand-pumped water supply.  Before proceeding further, our first goal will be to establish our first round of plumbing, automating a few of the colony's existing needs and setting things up to facilitate a few others shortly afterward.

Required researches:
* Plumbing (Tier 1)
* Sanitation (Tier 2)

Strongly suggested:
* Pressure Management (Tier 2) - unlocks Valves.

Benefits:
* No more manual upkeep for the base's hygiene levels, freeing up Dupe time.
* Jump-starts our base's core plumbing

Costs:
* We start producing infected Polluted Water.
* Dupes must spend a bit more time on Manual Generators than before.  (It's definitely a net time savings, though!)

---

This guide's World Seed has an incredibly-convenient setup for an initial water reservoir from which to establish plumbing.  It's already rather nicely shaped, which will make it simple to formally convert and build the base around down the road.  In case it's not otherwise obvious, I am committing to turn that existing pool into my core pure water reservoir for the base.  Depending on your world's setup, you may wish to swap your location down the line.  If so, as you become more experienced with ONI, try to plan ahead for how you'll transition your plumbing when that time comes.

You may have noticed that I made some "interesting" spacing decisions in the initial portion of the guide, without calling any attention to them.  That is because while the decisions weren't critical, I was preparing ahead for certain construction decisions being made now.  In particular, at least in previous versions of ONI, water pressure becomes a concern when dealing with large pools of water.  Dealing with leaks can get really annoying when constructing proper walls for the reservoir as well, so I took care to leave a two-thick space for reservoir walls down the line.

I've also decided to convert the space immediately under the Printing Pod to be my first plumbed Lavatory room, which will have two Sinks and one Lavatory to start.  You'll note that I'm using valves fairly heavily here - in the case that two or more Dupes are utilizing the facilities, this allows all buildings in the Lavatory to output at the same time without interference.  Without a Liquid Valve, any time two pipes of fluid meet, only one of them is allowed to continue, regardless of the amount of fluid contained!  The same also holds for splitting a pipe two ways - each tick, water will only flow through one pipe, regardless of whether or not available fluid is left to travel the other!

![The Plumbing Plans](img/lavatory-mk-2-core.png){:class="img-responsive"}

I've decided to make an area to the lower-left of the reservoir the contaminated Polluted Water tank.  To keep the reasoning short, this places it pretty close to that nice Natural Gas Geyser we've already found!  (It's just to the left of the Dusk Cap/mushroom plant you see on the left-hand side.)  I have plans for connecting the two later down the road.  The key idea - _contaminated_ Polluted Water near the Natural Gas Geyser.

Once all the construction is finished, here's what my setup looks like!  The ladders you see remaining in the Lavatory (and the Debris) will be taken care of while I work on the next big goal.

![Hooray for Running Water!](img/lavatory-mk-2.png){:class="img-responsive"}

### Other Notes

A few of my Dupes mastered their first job!  Yay!  I've since moved them on to other relevant jobs that don't increase their expectations much.  I also got my Creative Dupe for doing Artistry, so I've unlocked Artistic Expression as well.  Finally, the Dupes have worked off all their stress thanks to that Decor work we did!  (It did go up for a while after the underwater construction, so be sure you _are_ handling their stress somehow.)

#### Enhancing Airflow

Airflow works a little oddly in ONI.  Any given block of space may only contain one type of gas at a time.  This means that one-tile-wide pathways don't allow mixed gases to pass through very well.  Since even a mixture of Oxygen and Carbon Dioxide is a mixed gas, it can be important to make sure they can separate easily.  Toward that end, I've lined the main hall with Airflow tiles.

![Using Airflow Tiles](img/airflow.png){:class="img-responsive"}

#### Water Relocation

Knowing that I'd have to eventually handle the water immediately below my Printing Pod sometime, I took care to move that water to the main reservoir early.  Fortunately, it's above that reserve, so I let gravity do the work.

![Using physics to solve problems!](img/water-merging.png){:class="img-responsive"}

## Bristle Farming

Now that we have plumbing in place, it's time to make use of our new infrastructure!  Why should hygiene be our only use of water?  Instead, let's upgrade our farming strategies!

Required researches:
* Agriculture (Tier 3) - while possible with just the Tier 2, you'll want to quickly upgrade it use the Tier 3 Hydroponics Tile.
* Interior Decor (Tier 1), in case you skipped it earlier.

It's a pretty short list, but don't get too lazy - the item after this has a lot of requirements!

Benefits:
* Increases the base's available Food quality, facilitating higher-tier Jobs.
* Moves to a _much_ more efficient Food source.
  * Requires far less Dupe interaction
  * Is far more compact when stored
  * When a Dupe reaches the Tier 2 Farming Job, they can double the speed of Bristle growth for minimal extra cost!

Costs:
* We start consuming additional water and must begin worrying more about Heat levels.

---

You might have been wondering what I've been planning to do with that area to the right of the Lavatory and below the Barracks.  It's fairly open and is five tiles high.  Well, it's time to use that area now to create our first Bristle Berry farm!  Five tile height is ideal for these farms, as the Ceiling Light can cast light up to five tiles beneath it, with the area covered growing the higher up it is.  We could go for a more compact setup, but I prefer minimizing the number of lights since this reduces their impact on Heat and Power.

I left a separate valve early in the plumbing to provide a separate water pipe than the one that the Lavatory room is using.  At some point, we may convert the Lavatory to using non-potable Water sources, so it'd be nice to allow the water pathways to be separately managed for later down the line.  So, the main thing is simply to construct the room... which can get a slight bit tricky when working with five-tiles-high rooms, but that's what temporary ladders are for.

![The new Bristle Blossom farm](img/bristle-farm.png){:class="img-responsive"}

### Other Notes

Since the last section, I've acquired an extra Dupe.  She wasn't too stellar statswise but came with Diver's Lung, probably the best positive trait in the game.  That reduced Oxygen intake   I figure she'll be a Supplier-type Dupe, since a developing base can near always use that kind of help and her stats weren't bad for it.

## Automated Power Generation

Around this time, you may have noticed an interesting issue with your food supplies - unrefrigerated food decays, and Dupes seem to actively avoid the oldest food.  Unfortunately, when part of a food stack spoils, the whole thing does, which can wreck your manufactured food supply.  To solve this, we need refrigeration.  Furthermore, now that we're Bristle farming, you may have had a power cut to your farm lights - power interruptions will interrupt your food production as well.  Therefore, it's time to fix our Power problem.

At the same time, there's a secondary problem that may start needing to be addressed that will become even more pronounced once we've started using Coal Generators - our base already has a significant Carbon Dioxide buildup.  Let's look at the Oxygen Overlay (the left-most Overlay option):

![Oxygen vs Carbon Dioxide - who will win?](img/co2-buildup.png){:class="img-responsive"}

Everything red within the current base in the image above averages around 600g of Carbon Dioxide per tile.  This is about half the core base's pressure.  If you're wondering about the reports you've likely been getting about "Insufficient Oxygen Generation", this is a large part of it - though seriously, you probably do also need an extra Algae Deoxydizer at this point.  (I've been lazy about that here.)  Carbon Dioxide pressure will block Oxygen production if the Oxygen runs out of places to flow, and Carbon Dioxide is unbreathable.  We'll take care of this within this step as well.

Required researches:
* Internal Combustion (Tier 2)
* Air Systems (Tier 2)

Strongly suggested:
* Advanced Power Regulation (Tier 3)
* Brute-Force Refinement (Tier 2)
* Automatic Control (Tier 2)
* Generic Sensors (Tier 3)
* Improved Ventilation (Tier 3)

That's quite the research list!  Part of this is because we're actually going to tackle multiple problems at once.

Benefits (with "Required"):
* Frees up Dupes from Manual Generator use
* Provides a near-uninterrupted Power source.

Additional Benefits (with "Suggested"):
* Conserves resources so that minimal Power is wasted and less upkeep is required.
* Begins handling and elimination of your Carbon Dioxide buildup.
* Provides significant Power flexibility moving forward for upcoming tasks.

Costs:
* We're now actively producing extra Carbon Dioxide, even if we're also handling it.
* This results in extra Polluted Water production.  It's up to you whether this water is kept potable or not.
* We now need to keep an eye on Coal levels, though we should be fine for quite a while.

---

One problem with Coal-based Power production is that it generates significant amounts of Heat - 45W of it, as opposed to the 5W of the Manual Generator.  As our Power needs will grow with the base, it would be wise to place such large sources of Heat away from our farms and the core of the base.  Another issue is its production of waste Carbon Dioxide.  This gas has a tendency to settle at the bottom of all other common in-game gases.  Putting the two together... the plan is to place our first Coal Generators below the base.  Simple, right?

With this map, I've identified a spot I like for Coal Generators - the lower Caustic biome!  In particular, look below and slightly to the right of the ladders I'm building in the image below:

![Future dig site detected](img/coal-generator-plans.png){:class="img-responsive"}

That's a lovely block of Coal and Algae down there!  There are no other gases interfering, and this area can be kept quite isolated from the rest of the base, keeping the generated Heat far away.  There's also some Iron to the left that I plan to grab, since Copper's more unique than Iron in the game and I'm planning to start refining metal around now; our initial refining will be suboptimal and thus lose 50% of the metal we process.  That's fine for Iron, but possibly less fine for Copper.  That said, if you have tons of Copper lying around, don't worry about it.

The reason for all of this:

![My beloved Coal setup](img/coal-power.png){:class="img-responsive"}

Let's take a closer look at the core of this setup:

![Time for a Coal close-up](img/coal-central.png){:class="img-responsive"}

That's two Coal Generators, one Smart Battery, a Power Transformer, one Carbon Scrubber, and an Atmo Sensor, hence all the tech requirements.  The Smart Battery is the best Battery on all fronts but one - capacity.  It emits less heat, loses less charge, and is phenomenal for Power-generating automation.  Its Automation output is wired directly to control both Coal Generators for optimal use of Coal.  Note that the Smart Battery is on the Heavi-Watt Wire, not on the "plain wire" side of the transformer.  This allows it to take in all power from both Generators without loss.

![How's that wired, again?](img/coal-central-wiring.png){:class="img-responsive"}

There's a second layer of Automation we bothered to install here - that Atmo Sensor is wired directly into the Carbon Scrubber.  I like setting mine to activate above 1000g gas pressure.  Note the structure of the Coal room - the sides are blocked off with Manual Airlocks and a wall, meaning the only way for gases to enter is "down."  Carbon Dioxide is the heaviest gas, so this room setup allows us to guarantee Carbon Dioxide will be the gas surrounding the Scrubber.  We choose 1000g of pressure so that we don't run the Scrubber under too low of an atmosphere or accidentally run out of the Carbon Dioxide surroundings - it's enough to keep a nice buffer, just in case.

### Other Notes

#### Cooking Tools Upgrade

Now that our Bristle Blossom farm has had time to get started, we should swap from Liceloaf to Pickled Meal + Gristle Berry production.

Benefits:
* Pickled Meal stays fresh far longer than Liceloaf, costs no Water, and is disinfected when cooked.
* The Gristle Berry is higher quality than Liceloaf, costs no extra Water, and holds more kCal per kg for better food storage efficiency!
* Reduced Power consumption:  the Microbe Musher costs 240W while the Electric Grill costs only 60W!

Costs:
* Pickled Meal isn't as high-quality a meal as Liceloaf, so your, uh, "high-maintenance" Dupes might should avoid it.
* The Electric Grill produces slightly more heat than a Microbe Musher.  It's generally not enough to be a problem, though.
* The Electric Grill requires special Job training to use.

If you haven't yet, you should start taking a look at the Consumables menu and start managing that a bit more closely to ensure Dupes have their expectations handled in a well-balanced manner for the state of your base.

It's also a good time to build that Refrigerator I mentioned earlier, since Gristle Berries spoil far more quickly than Pickled Meal if you don't refrigerate them.

#### Sealed Construction

During this phase, I found a desire to build walls somewhere that would cause unwanted gas to leak into my base.  There's a fun trick that can be used to solve these scenarios:

![I call wall hax!](img/sealed-construction.png){:class="img-responsive"}

Gases don't move diagonally - only vertically and horizontally.  The trick here is to build a barrier in front of where you _actually_ want to build, then build in the actual location of interest.  The second build will push the unwanted gas back into where it had already been, allowing you to maintain your sealed atmosphere while changing the walls out into something safe for wires or pipes.

#### A Hidden Geyser?

Did you notice this odd-looking block near our Coal Generators?

![Crouching tiger, hidden geyser](img/crouching-tiger-hidden-geyser.png){:class="img-responsive"}

See that strange, 4-tile-wide block of black blocks?  That's unbreakable Neutronium, which serves as the base of something special.  New to the Ranching Upgrade, we now have random, hidden geysers to discover!  They won't produce anything until they're uncovered, but, uh... you may not want to uncover that one just yet.  Some of the new geysers have immense impacts on their environment that you simply may not be ready to handle this early in the game.  As long as you don't uncover them, they cannot produce and will not cause issues.  Tread lightly around them!

As an example, I'll give you this picture from the in-game database.

![One geyser type you really don't want to uncover right now!](img/volcano.png){:class="img-responsive"}

So that you know, Magma tends to run about 1800 degrees Celsius, give or take.  You know, just a small bit of heat there.  Be SURE you're ready to handle the consequences before opening up one of these hidden geysers!  (Also known as - have mined Abyssalite handy!)

---

Now that we've established a long-term oriented farm and have a stable source of power and plumbing, it's time to formally move to the mid-game!