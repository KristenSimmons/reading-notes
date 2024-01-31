# HTML Images & CSS Styling

## HTML Media

### 1. What is a real world use case for the alt attribute being used in a website?
The alt attribute is a textual description of an image, for use in situations where the image cannot be seen/displayed or takes a long time to render because of a slow internet connection. The user could see the descriptive text, even if they are unable to load the image for whatever reason. If the user is visually impaired and using a screen reader to read the web out to them, the alt description would be very important and helpful. 

### 2. How can you improve accessibility of images in an HTML document?
Accessibility can be improved by using images that are saved in a local file and avoiding using images that are stored on another site. Also, using the best image format available for your particular image. 

### 3. Provide an example of when the figure element would be useful in an HTML document.
The "<figure>" HTML element represents self-contained content, potentially with an optional caption, which is specified using the <figcaption> element. The figure, its caption, and its contents are referenced as a single unit. This can be useful if the image doesn't have a caption and you want to add one to the image and make sure they stay in a certain format. 

### 4. Describe the difference between a gif image and an svg image, pretend you are explaining to an elder in your community.
A GIF is a 'Graphics Interchange Format'. GIF is a good choice for simple images and animations. An SVG is a "Scalable Vector Graphics". An SVG is ideal for user interface elements, icons, diagrams, etc., that must be drawn accurately at different sizes. So a GIF would work well for a basic image or animation, while an SVG would be something that may need to be used repeatedly but at different sizes. 

### 5. What image type would you use to display a screenshot on your website and why?
Unless you're willing to compromise on quality, you should use a lossless format for screenshots. This is particularly important if there's any text in your screenshot, as text easily becomes fuzzy and unclear under lossy compression. PNG is probably your best bet, but lossless WebP is arguably going to be better compressed.

## Using Color & Styling in CSS

### 1. Describe the difference between foreground and background colors of an HTML element, pretend you are talking to someone with no technical knowledge.
The background color is the color of the background. The foreground color would be describing the color of the text. Imagine a piece of white paper with black text writte on it. The background color is white, the foreground color is black. 
### 2. Your friend asks you to give his colorless blog website a touch up. How would you use color to give his blog some character?
Color can be added to the background, as well as the text. It would be best to have contrasting colors for each of those. Another element of color can be added by putting borders around different sections. You could have a body around the entire body of the page, as well as borders around each paragraph. You could also add different colors to the padding and margins for even more variety.
### 3. What should you consider when choosing fonts for an HTML document?
Fonts should be easy to read for the user and accessible by most major operating systems, like Windows, Chrome, Safari, etc.
### 4. What do font-size, font-weight, and font-style do to HTML text elements?
Font-size will change the height and width of each character of text. For example, the way an h1 heading has a larger font than an h2 heading. <br>
Font-weight determines if the text will be bold, normal or lighter than normal. <br>
Font-style determines if the text will be in italics or normal. 
### 5. Describe two ways you could add spacing around the characters displayed in an h1 element.
The 'letter-spacing' and 'word-spacing' properties allow you to set the spacing between letters and words in your text.


## Resources 

- [Images in HTML](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Images_in_HTML)<br>
- [Image file type & Format Guide for HTML](https://developer.mozilla.org/en-US/docs/Web/Media/Formats/Image_types#choosing_an_image_format) <br>
- [CSS Styling](https://developer.mozilla.org/en-US/docs/Learn/CSS/Styling_text/Fundamentals) <br>
- [Applying Color in HTML with CSS](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Colors/Applying_color)
