# Bird Game for a coding challenge

I spent some time working for a coding challenge and since I spent the time I might as well share it here.
You can find the source code for running in unity at https://github.com/iomeanslife/bird-chase-demo

{{ bird-chase-webgl}}

## Some Thoughts

* It already took too much time but I feel I could have designed the code better and do a more coherent on using the component system.

* I made faster progress creating the city in Blender than I expected, even though I haven't used it in years. Something about duplicating vertices and faces, extruding etc. just stuck with me. Don't ask me to texture anything though 😅

* A requirement for input was, that keyboard and mouse would be alright, but game controller input would be preffered. Since I only have a steam controller, I had to install software that changes it to an xinput device, because the new input system in Unity only recognize them.

* Working with the physics system was annoying, especilly when I needed both collision and triggering. using mass, torque and force to control both dragon and bird took away some of the annoying things I would have to do by hand, but the controls are spongy, Definetely something I'd research much more up on if I would ever try to create something propper.

* The requirement said something about a bird of prey, a dragon and a city, so the setting is all over from the get go. So I replaced the bird and dragon with paper planes versions, since those work better in a city.

