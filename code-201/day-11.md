# Audio, Video, Images & The Grid

## Audio & Video Content

### 1) Explain how the ability to use video and audio on the web has evolved since the early 2000s.
The first influx of online videos and audio were made possible by proprietary plugin-based technologies like Flash and Silverlight. Both of these had security and accessibility issues, and are now obsolete, in favor of native HTML solutions.

### 2) Describe the use of the src and controls attributes in the video element.
The src (source) attribute contains a path to the video you want to embed. It works in exactly the same way you would use for an image. Controls is an attribute that gives the user the ability control the playback. For example, being able to sart, stop and adjust volume on audio and video content.

### 3) Why is it important to have fallback content inside the video element?
The paragraph inside the video tags is called fallback content — this will be displayed if the browser accessing the page doesn't support the < ideo > element, allowing devs to provide a fallback for older browsers. This can be anything you like; such as providing a direct link to the video file, so the user can at least access it some way regardless of what browser they are using.
### 4) Write a very short story where < audio > and < video > are characters.

Once upon the digital horizon, Video and Audio met. Video, vibrant and dynamic, danced with Audio, whose harmonies enchanted the cyber waves. Together, they journeyed through glitchy landscapes, overcoming obstacles and captivating audiences with their immersive harmony. As symbols of creativity and unity, they reminded the digital realm of the magic born from their perfect partnership, forever intertwining sight and sound in a mesmerizing dance.

## A Complete Guide To Grid

### 1) How does Grid layout differ from Flex?
Flex works on a one-dimensional flow. Grid allows for two-dimensiional placement.
### 2) Grid container, grid item, and grid line are a few important terms to understand when using Grid. Please describe these terms in a few sentences.
- Grid container: The element on which "display: grid" is applied. It’s the direct parent of all the grid items.<br>
- Grid item: The children (i.e. direct descendants) of the grid container.<br>
- Grid line: The dividing lines that make up the structure of the grid. They can be either vertical (“column grid lines”) or horizontal (“row grid lines”) and reside on either side of a row or column.<br>
- Grid cell: The space between two adjacent row and two adjacent column grid lines. It’s a single “unit” of the grid. 

## Responsive Images

### 1) Besides making a site visually appealing across different screen sizes, why should developers make images responsive?
Another advantage to using responsive images would be that some devices have high resolution screens that need larger images than you might expect to display nicely.
### 2) Define the following img attributes srcset and sizes. Write an example of how they are used.
We can use two attributes — srcset and sizes — to provide several additional source images along with hints to help the browser pick the right one; "srcset" defines the set of images we will allow the browser to choose between, and what size each image is; "sizes" defines a set of media conditions (e.g. screen widths) and indicates what image size would be best to choose, when certain media conditions are true. Each of these attributes has their own set of values required to function properly.
### 3) How is srcset more helpful for responsive images than CSS or JavaScript?

'srcset' is particularly useful for responsive images because it allows the browser to select the most appropriate image source based on the device's screen size and resolution, thereby optimizing performance and user experience. This offers a convenient and efficient way to implement responsive images directly within HTML, leveraging native browser functionality to deliver an optimized experience across diverse devices and screen resolutions.

## Resources
- [Video & Audio Content](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Video_and_audio_content)<br>
- [Complete Guide to the Grid](https://css-tricks.com/snippets/css/complete-guide-grid/)<br>
- [Responsive Images](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)<br>
- [Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)<br>
- [Other Embedding Technologies](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Other_embedding_technologies)<br>
