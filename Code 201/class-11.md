# Class 11

## Audio, Video, Images

### Audio & Video Content

#### **Explain how the ability to use video and audio on the web has evolved since the early 2000s**

>
>In the early days, native web technologies such as HTML didn't have the ability to embed video and audio on the Web, so proprietary (or plugin-based) technologies like Flash — and later, Silverlight (both of which are now obsolete) — became popular for handling such content. This kind of technology worked OK, but it had a number of problems, including not working well with HTML/CSS features, security issues, and accessibility issues.
>
>A native solution would solve much of this if implemented correctly. Fortunately, a few years later the HTML5 specification had such features added, with the `<video>` and `<audio>` elements, and some shiny new JavaScript APIs for controlling them. We'll not be looking at JavaScript here — just the basic foundations that can be achieved with HTML.
>

Reference: [Video and audio content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content) from mdn web doc_.

#### **Describe the use of the `src` and `controls` attributes in the `<video>` element**

The `src` attribute contains the path to the video you want to imbed, just like witht the `img` element. The `controls` attribute adds the browsers control interface to the video.

#### **Why is it important to have fallback content inside the `<video>` element?**

It is important to have fallback content because this is what will be displayed in the case of the browser not supporting the `<video>` element.

#### **Write a very short story where `<audio>` and `<video>` are characters**

Audio was always jealous of Video. Video was always getting so much more attention than him and he couldn't understand why. Yeah, maybe he had all the looks, but so what? Just because you add one extra sense into the mix, all of a sudden he's the man? Audio was just about to pack it in and let Video handle all the content when he had a thought. "At least I still have the drivers! It's way safer to listen to me while driving than watch him." And just like that, Audio got a little bit of his confidence back.

### CSS Grid

#### **How does Grid layout differ from Flex?**

Grid is a two-dimensional layout as opposed to Flex's one-dimension.

#### **Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences**

- Grid container - The element on which the `display: grid` is applied. It is the direct parent of all the grid items.
- Grid item - The children of the grid container.
- Grid line - The dividing lines that make up the structure of the grid. They can either be vertical or horizontal and reside on both side if the row or column.

### Responsive Images

#### **Besides making a site visually appealing across different screen sizes, why should developers make images responsive?**

Responsive images allow the page to provide all the vital information trying to be conveyed throught the image. It also doesn't waste as much bandwith on the user's device.

#### **Define the following `<img>` attributes `srcset` and `sizes`. Write an example of how they are used**

`srcset` defines the set of images we allow the browser to choose between and the size of each image. `sizes` defines a set of media conditions and indicates which image to use when certain media conditions are true.

```html
  <img srcset="elva-fairy-480w.jpg 480w,
               elva-fairy-800w.jpg 800w"
        sizes="(max-width: 600px) 480px,
            800px"
        src="elva-fairy-800w.jpg"
        alt="Elva dressed as a fairy">
```

#### **How is `srcset` more helpful for responsive images than CSS or JavaScript?**

`srcset` is more useful than CSS or JavaScript because it allows the appropriate image to be loaded onto the page as it is parsed.

## Things I want to know more about

[Home](README.md)
