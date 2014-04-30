The final "project" is meant to be relatively small, a (hopefully) fun way to end the course, and (again, hopefully) some "easier" points. Though this will involve reading chapter 20 for some more specific information; you should be able to handle it based on the brief introduction given in class combined with the contents of chapters 19 and 20 from the text.

The additional requirements are:

You should be able to move "back" as well as "forward"
If it makes things easier, you may change forward, left, right, back to north, west, east, south. (Personally, I think this makes it easier to keep track of where you are going... but that's just me...)
You may even add "aliases" as simply, n, s, e, and w for much easier testing.
 
 You should add at least two more "features" of your own design in addition to those described in the exercise.
 For example, you could add an additional item with a special purpose and new creature or obstacle to encounter.
 If you are suffering from a creative block, you might consider a sword which can be found and used to defeat the ogre, or a magic ring which must be found and worn to sneak past the ogre.  (Ok... my ideas are not all that creative either, but they merely serve as examples.)
 You are encouraged to be as imaginative as you desire!  (Unless you have a particularly disturbed imagination...)
  
  You should be able to pickup and drop any object in the world.
  Items should be "visible" if in a location that contains the item, but not if you are carrying it.
  You should be able to "drop" things anywhere where it would make sense to be able to do so.
  As a frame of reference, the original Zork (from which the game in the text is derived) is available for download. The Interactive Fiction Archive is also a trove of these types of games.
  Assignment Tips and Hints:
  You don't actually need to use any Prolog lists, though you certainly may use lists to manage and maintain a complex inventory, for example.
  Everything can be done by "asserting" and "retracting" rules as the player moves around.
  All basic "inventory/state information" can be stored as rules from which you can assert and retract.
  For example, a "has" predicate could be introduced like: has(you, sword).
  Of course, if you pick something up, it should should be removed from the "world" (the at predicate in the sample). Then dropping something would retract the has predicate and assert an at predicate.
