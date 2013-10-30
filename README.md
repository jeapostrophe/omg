# Oh My Grind

OMG is a PRNG---persistent random numerical grinding---experience that
is a cross between a roguelike, a MUD, and Demon's Souls.

The users log in and connect like TELNET to a server. They set up an
account. They are dropped into the World Navel at 0,0 and can begin
their quest.

The world is persistent, but totally randomly generated. Each
direction out of a room (N,S,E,W,[NS][EW], U, D) is given a random
seed that determines its contents, if it is ever reached. Only some of
the directions are necessarily open, but there is always a way back
and a way forward---however the way forward may connect to an existing
node in the world graph, so the world could eventually close. Some
global measure of how open the universe is could be used to inspire
more openings.

The room population algorithm is dependent on the discoverer of the
room, so if you push the boundaries of the world, you will find
greater challenges and greater rewards.

A hunger system could be used to force forward exploration or giving
up.

A campfire save system would be used to provide check pointing like
facilities.

Mobs would repopulate at a particular interval once they were
discovered and perhaps only once the room was visited since they last
time they spawned.

Some mobs could be "friendly" in the sense that they are not
aggressive and perhaps are "adventurers" themselves.

The experience system would be like FF13 or Demon's Souls with many
small things that can be achieved.

The crafting system would be a form of linear logic theorem proving,
with the size of theorems related to the awesomeness of the item.

There would be two time scales for the world: actions and
meta-actions. Meta-actions would fire immediately but do not effect
the world---viewing stats, inventory, talking, looking, etc. Actions
would evaluate synchronous across all entities (mobs/players) at a
consistent rate. Actions that you could take would be "stance-like",
so you don't have to constantly press Attack, etc.

You could view the world through different goggles: text, Sexpr, XML,
etc.

If you opened yourself up to PvP, then you got double XP. If you beat
someone in PvP, they drop their XP. (Same with monsters. XP is totally
tradeable.)

You can see a map of where you have been, but nowhere else.

Areas have random effects that will have to be discovered and written
down in marks by other players.

Mobs have affinities that are randomly related to their room,
etc. Each adjoining room has an affinity related to those around it
with a random change. The idea is to create contiguous blocks of
"fire" rooms that gradually become lava, then earth. Etc.
