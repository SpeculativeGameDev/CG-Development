# CG stands for City Game

## DISCLAIMER: CG is a long-term project
This project has been on pre-production since 2018. There is no release date in the horizon. Expect 10+ years of development. We are **not** in the development phase.


## Journal



### 2023-08-12 - Resources, growth, commerce and staying neutral

Resources are finite. We humans valued them for their scarcity and their usefulness. That's why, for most of human history, Helium had a value of zero. Even such a scarce gas had no value to us until we found uses for it. Now it's expensive, protected and its commerce is artificially limited. 

### 2023-08-06 - On real isolation and what it entails

I've been thinking about the ethics and morals of City Game's island.
For this mental exercise, let's asume there is some guiding intelligence on the history of the island. Given its utopian qualities, it would be easier to asume the existence of an age-old well-meaning and highly educated being focused on the welfare of the island than believing on the long-term planning and true kindness capacities of a handful of secluded humans, or chance.

Congratulations, you got an island. 500km² of mediterranean land. You are so proud. As the only protector and developer of this small community, you take control of its leaders whenever necessary.

#### You, the government
You hypocrite. You treat this land as sacred and eternal. As a closed system, with no dependency from the outside. Nothing enters, nothing exits the environment. Everything is preserved for future generations. Theirs is the gift to be enjoyed, and the burden to maintain it.
Yet, there is nothing sacred or eternal in this maganement.
If you import goods or services from afar, knowing no other country holds itself to such great standards, you are turning a blind eye on the question. How was that product manufactured? Did it respect the declaration of human rights, not just in words, but in its spirit? How were the raw materials obtained, and where? Was something robbed of its real owner's hands? Do all the steps of manufacturing observe a cautious treatment of the waste and the environment? Is buying this product... **ethical**?

Almost nothing passes such filters.

You could try to undo the harm done to the world and its inhabitants. Estimate the lost value, then make some reparations. Plant some trees, capture CO2, clean the oceans... you could charge extra in customs, then employ it on all those aura-cleaning rituals. Did it work? I thought so.
Putting a price to bad behaviour does not avoid it, just restricts it to the people that can afford it. Your island won't be sacred anymore if its rooted on the mud of the mundane.
Unethical consumerism is always unethical. No price tag will change that.

The dilemma here is, you need the mundane. A small island like yours won't stand eternal by itself.

Let's think about the third option: You reject goods and services from the continent. It's simple at the beginning, just set aside some land for farming and crops. Life is easy. Your population grows steadily until foreign countries see what you have and want it for them, or until every resource is consumed and commerce is a necessity just to survive. This will happen. Your population will grow above the point of equilibrium. The environment won't be able to support that growth and will eventually collapse. We'll have to take some actions to avoid that. But that will be on another day.


### 2023-06-26 - About conflict in storytelling
As an interactive medium, videogames require -or at least expect- the player's input for the plot (if any) to move forward. Most of the time, the player's input is obtained as a given, by the own will of the player to explore and/or entertain themselves. Nonetheless, games tend to propose some kind of story. But not any kind of story: If the player is going to spend their time (and money in some cases), shouldn't they be rewarded in some way for the effort? And, to cover all bases, the reward could be some praise. Reverence, even. The player is given a story where they possess special powers, or face extreme difficulties, or the most evil of foes. Conflict is exacerbated in order to elevate the player through the gameplay and to the very end of the story. We understand that and see it as a requirement.

Yet, cinema has shown us quite notable movies where conflict is almost non existent. Theatre has, too, gifted us with plays like Cinco horas con Mario. Literature has La casa de Bernarda Alba.
Games, specially indie games in nature, have tiptoed into this style with "walking simulators" and "cozy games", where the pacing is more relaxed and the treated themes are either shallow, or deep but laser-focused.
I love moving through the cities in GTA series. I hate the story, though. Conflict follows the player everywhere, and it's the only language a player can speak on them. Let's talk about games' verbs. Before point and click adventures had its peak, it was common for games to have a text input. The variety and complexity of such games relied on how many verbs there were. You could take, see, read, pinch, open, throw, eat... an object. FPS games have lots of locomotion verbs, but only one or two interaction verbs: Use/activate and shoot. GTA games have lots of locomotion verbs, but lack in interactions. It's not as barebones as with pure FPS games, but if you only can *run over*, *punch* or *shoot* someone, no interactions of value will be achieved. NPCs become just moving targets to avoid or confront. RDR and RDR2 offer a much richer experience, but violence is ingrained in the genre and often becomes a necessity.

My take: Let's forget about conflict. It's barely there on our day to day. We should enlarge the list of verbs instead. I want a game where characters and NPCs alike can sit on a bench, talk with each other, plug a cable, read a poem, pet animals, play an instrument, open the mailbox, wash the dishes, climb a wall, jump over a puddle, carry a box, make an omelette, watch some birds, pull a cord, switch on a light, stamp a stamp, eat a sandwich, take a photo, hold a lamp. Life has its difficulties without foes and open conflict.


### 2023-01-14 - Workflowy

All game design ideas will be added on this Workflowy document: https://workflowy.com/s/citygame/aA0jhxBa4BncYTPX


### 2022-10-23

I have decided to use Godot as the game engine for CG. Reasons:
- Open source and dedicated community - Not a dead project
- C++ code can be added via GDExtensions where GDScript performance is not enough
- Unity is in an unsafe situation right now. Everything is in alpha or deprecated. Running target. Developers are not the priority.
- Unreal requires C++ and I don't feel comfortable enough writing a whole game with C++. Blueprints would not cut it, as any complexity makes them very hard to understand and debug.

In order to stablish a good project structure and to work within Godot's strengths, I'm reading all of Godot's documentation and various tutorials about some use-cases that I suspect we'll encounter during the development.

Some stress points are the Data Oriented Design principles (not enforced in Godot, but present somewhat), the need for an ECS (not sure yet), use of compute shaders for simulations and how they sync to CPU.

As a longtime Unity User, Godot's proposal seems familiar but alienates me on some basic asumptions. I'll have to re-learn some trivialities but the engine looks robust.
