# A small gallery of CSS & JavaScript Effects (DGMD E-15, Spring 2015)

Included here are ten, stripped down examples of effects you might consider using as part of your customization of your card on [our `/people` page](http://dgmde15.github.io/people).  Each of these links directly to the demo, but you can see the full source code below, too.

To play around with these demos, [clone this repository](https://www.youtube.com/watch?v=O72FWNeO-xY).  Once you do, you should be able to open up each HTML file in your own text editor and/or browser to explore.

---

In rough order of complexity:
+ [`font.html`](./blob/master/font.html) loads a font remotely [from Google Fonts](https://www.google.com/fonts) and uses it to change the font we use in a given `div`.

+ [`round.html`](./blob/master/round.html) rounds the corners of a `div` using CSS.

+ [`fade.html`](./blob/master/fade.html) uses CSS to animate the fading of an element when we hover over it.

+ [`spin.html`](./blob/master/spin.html) spins our `div` upside down when we hover over it using CSS.

+ [`synthesize.html`](./blob/master/synthesize.html) build our page from scratch using nothing but JavaScript, adding functionality similar to [`fade.html`](./blob/master/fade.html) without CSS.

+ [`sprite.html`](./blob/master/sprite.html) uses a sprite sheet and CSS to achieve flipbook-style animation.

+ [`random.html`](./blob/master/random.html) uses JS to randomly reorder a list whenver you click the mouse.

+ [`mouse.html`](./blob/master/mouse.html) uses JS to place a div randomly, and when we're close enough, make it follow our mouse.

+ [`flickr.html`](./blob/master/flickr.html) uses JS and a technique known as [JSONP](http://en.wikipedia.org/wiki/JSONP) to grab a random photo from [Flickr](http://flickr.com)'s API and set it as a background.

+ [`canvas.html`](./blob/master/canvas.html) uses HTML's `<canvas>` element to draw a smiley face.

---

And finally, a boring PS: [`boilerplate.html`](./blob/master/boilerplate.html) is a bare HTML stub you can use as a template for your own explorations.
