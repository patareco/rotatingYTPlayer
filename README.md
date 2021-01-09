# rotatingYTPlayer

A simple custom youtube player that change orientation for videos that are both vertical and horizontal.

Demo: https://nchantre.com/wp/wp-content/experiments/drone.html

## dynamic URL loading

The player assumes a 9:16 aspect ratio. Will implement more options in the future.

### URL Params

- id: Youtube Video ID
- r: comma separated moments of rotation with the following structure: degrees@timecode+duration

The degrees have to have a 'deg' suffix since the value is injected directly in CSS.
The duration has to have an 's' suffix.

### Example

full url:
rotatingYTPlayer.html?id=IUMTaAQ43lY&r=-90deg@20+2s,0deg@40+0.5s,-180deg@60+5s,-90deg@90+5s,-90deg@120+2s