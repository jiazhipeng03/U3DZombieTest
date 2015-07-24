# U3DZombieTest
Zombie game made by u3d

My first U3D game with the guide on http://www.raywenderlich.com/category/unity

ZombieConga-Part1-Resources.zip includes the resources used in this program.

------------Update 2015/7/16---------------------

1.Add animation event.

2.Learn some about State Machines : Any State and Sub-state Machines(http://docs.unity3d.com/Manual/NestedStateMachines.html).

Problems:

1.What's the difference between calling Update and adding events in every frame of animation?
Answer : Update is doing at every tick of game, it is more frequent than the other method. Events only effect at every second.

2.Unity¡¯s animation system was interfering with GameObject¡¯s Transform, changing rotation in Update is invalid.
Add parent object.

3.The cat is not becoming conga immediately when zombie collides with it.
Because transmitted animation is too long.