# TOKMAK-Framework

TOKMAK Framework is a tool set for Unity that provide basic supports for UI, events, sound, grid (pathfinding) , and object pooling.

## [TOKMAK Universal Event](https://github.com/Fangjun-Zhou/TOKMAK-Universal-Event)

![image](https://user-images.githubusercontent.com/79500078/141885913-4dd55444-c3c7-4898-a440-012b30785767.png)

This is a universal event system for Unity that is easy to use, easy to configure, and really flexible. You can event build up your own MVC framework using this package.

### [Documentation](https://fangjun-zhou.github.io/TOKMAK-Universal-Event/)

## [TOKMAK UI Stack](https://github.com/Fangjun-Zhou/TOKMAK-UI-Stack)

TOKMAK UI Stack is a stack based UGUI manage system.

Using this system, developers can quickly construct an UI stack, and organize multiple layers in the scene by the stack.

On top of that, each layer in the stack (UI Panel) can response to the stack operation. Base on this feature, developers can keep the logic code running in the background, in order to implement complicated UI logic.

### [Documentation](https://fangjun-zhou.github.io/TOKMAK-UI-Stack/index.html)

## [TOKMAK Grid System](https://github.com/Fangjun-Zhou/TOKMAK-Grid-System)

TOKMAK Grid System is a universal grid system that support simulation business game, or tower defense game. It also has a build-in A* pathfinding and has a relatively high pathfinding throughput.

### [Documentation](https://fangjun-zhou.github.io/TOKMAK-Grid-System/)

## [TOKMAK Audio System](https://github.com/Fangjun-Zhou/TOKMAK-Audio-System)

Unity Audio System is a powerful Audio System providing audio extention such as audio mixing, random play, and delay audio play.

This system is easy to use. All you have to do is preparing audio clips for different distance and layer, the system will automatically generate audio source player and mix the audio clips when played.

This system also support random audio play. The player use shuffle algorithm so that the played audio is natural and no repeat audio will be generated.

It also support audio delay which can delay the audio base on distance to the camera. This feature can be used to simulate sound speed, providing a better sound experience.

### [Documentation](https://fangjun-zhou.github.io/TOKMAK-Audio-System/)

## [TOKMAK Object Pool](https://github.com/Fangjun-Zhou/TOKMAK-Object-Pool)

TOKMAK Object Pool is a extended version of [kPooling](https://github.com/Kink3d/kPooling).

### Improvements in TOKMAK Object Pool
TOKMAK Object Pool uses Queue to manage objects in Object Pool, which is more efficient than kPooling.

On top of that, TOKMAK Object Pool provides an extra Pooling mode: Expandable

Using Expandable mode, the Object Pool will instantiate new objects instead of recycling the old one in the pool when there's no more object in the pool. This feature is especially useful when implmenting bullet pool.
