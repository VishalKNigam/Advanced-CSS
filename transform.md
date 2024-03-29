CSS KEYFRAME
ANIMATIONS

CSS Animation Properties

CSS allows the animation of HTML
elements without using JavaScript. You
can change as many CSS properties as
you want, as often as you wish.
To use CSS animation, you must first
specify some keyframes for the
animation.
Keyframes hold what styles the element
will have at certain times.

animation-name
animation-duration
animation-delay
animation-iteration-count
animation-direction
animation-timing-function
animation-fill-mode

animation-direction

The animation-direction property specifies whether an animation should be
played forwards, backwards or in alternate cycles.
The animation-direction property can have the following values:
normal - The animation is played as normal (forwards). This is default
reverse - The animation is played in reverse direction (backwards)
alternate - The animation is played forwards first, then backwards
alternate-reverse - The animation is played backwards first, then forwards

animation-timing-function
The animation-timing-function property specifies the speed curve of the
animation.
ease - Specifies an animation with a slow start, then fast, then end slowly (this
is default)
linear - Specifies an animation with the same speed from start to end
ease-in - Specifies an animation with a slow start
ease-out - Specifies an animation with a slow end
ease-in-out - Specifies an animation with a slow start and end
cubic-bezier(n,n,n,n) - Lets you define your own values in a cubic-bezier
function

animation-fill-mode
The animation-fill-mode property specifies a style for the target element when
the animation is not playing (before it starts, after it ends, or both).
none - Default value. Animation will not apply any styles to the element before
or after it is executing
forwards - The element will retain the style values that is set by the last
keyframe (depends on animation-direction and animation-iteration-count)
backwards - The element will get the style values that is set by the first
keyframe (depends on animation-direction), and retain this during the
animation-delay period
both - The animation will follow the rules for both forwards and backwards,
extending the animation properties in both directions

