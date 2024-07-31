Learn HTML by Building a Cat Photo App

HTML tags give a webpage its structure. You can use HTML tags to add photos, buttons, and other elements to your webpage.

In this course, you'll learn the most common HTML tags by building your own cat photo app.

Step 1

HTML elements have an opening and closing tag with content in between.

Here is the basic syntax:

Example Code
<openingTag>content</closingTag>

The first element you will learn about is the h1 element. The h1 element is a heading element and is used for the main heading of a webpage.

Example Code
<h1>This is a main heading</h1>

Change the text of the h1 element below from Hello World to CatPhotoApp and watch the change in the browser preview.

When you are done, press the "Check Your Code" button to see if it's correct.

Step 2

The h1 through h6 heading elements are used to signify the importance of content below them. The lower the number, the higher the importance, so h2 elements have less importance than h1 elements.

Example Code

<h1>most important heading element</h1>
<h2>second most important heading element</h2>
<h3>third most important heading element</h3>
<h4>fourth most important heading element</h4>
<h5>fifth most important heading element</h5>
<h6>least important heading element</h6>

Only use one h1 element per page and place lower importance headings below higher importance headings.

Below the h1 element, add an h2 element with this text:

Cat Photos

Step 3

The p element is used to create a paragraph of text on websites. Create a p element below your h2 element and give it the following text:

See more cat photos in our gallery.

Step 4

Commenting allows you to leave messages without affecting the browser display. It also allows you to make code inactive. A comment in HTML starts with <!--, contains any number of lines of text, and ends with -->.

Here is an example of a comment with the TODO: Remove h1:

Example Code

<!-- TODO: Remove h1 -->
Add a comment above the p element with this text:

TODO: Add link to cat photos

Step 5

HTML5 has some elements that identify different content areas. These elements make your HTML easier to read and help with Search Engine Optimization (SEO) and accessibility.

The main element is used to represent the main content of the body of an HTML document. Content inside the main element should be unique to the document and should not be repeated in other parts of the document.

Example Code

<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>

Identify the main section of this page by adding a <main> opening tag before the h1 element, and a </main> closing tag after the p element.

Step 6

In the previous step, you put the h1, h2, comment, and p elements inside the main element. This is called nesting. Nested elements should be placed two spaces further to the right of the element they are nested in. This spacing is called indentation and it is used to make HTML easier to read.

Here is an example of nesting and indentation:

Example Code

<main>
  <h1>Most important content of the document</h1>
  <p>Some more important content...</p>
</main>

The h1 element, h2 element and the comment are indented two spaces more than the main element in the code below. Use the space bar on your keyboard to add two more spaces in front of the p element so that it is indented properly as well.

Step 7

You can add images to your website by using the img element. img elements have an opening tag without a closing tag. An element without a closing tag is known as a void element.

Add an img element below the p element. At this point, no image will show up in the browser.

Step 8

HTML attributes are special words used inside the opening tag of an element to control the element's behavior. The src attribute in an img element specifies the image's URL (where the image is located).

Here is an example of an img element with a src attribute pointing to the freeCodeCamp logo:

Example Code

<img src="https://cdn.freecodecamp.org/platform/universal/fcc_secondary.svg">

Inside the existing img element, add a src attribute with this URL:

https://cdn.freecodecamp.org/curriculum/cat-photo-app/relaxing-cat.jpg

Step 9

All img elements should have an alt attribute. The alt attribute's text is used for screen readers to improve accessibility and is displayed if the image fails to load.

Here is an example of an img element with an alt attribute:

Example Code

<img src="cat.jpg" alt="A cat">
Inside the img element, add an alt attribute with this text:

A cute orange cat lying on its back

Step 10

You can link to another page with the anchor (a) element.

Here is an example linking to https://www.freecodecamp.org:

Example Code

<a href="https://www.freecodecamp.org"></a>

Add an anchor element after the paragraph that links to https://freecatphotoapp.com. At this point, the link won’t show up in the preview.

Step 11

A link's text must be placed between the opening and closing tags of an anchor (a) element.

Here is an example of a link with the text click here to go to freeCodeCamp.org:

Example Code

<a href="https://www.freecodecamp.org">click here to go to freeCodeCamp.org</a>

Add the anchor text link to cat pictures to the anchor element. This will become the link's text.

Step 12

You can turn any text into a link, such as the text inside of a p element.

Example Code
<p>I think <a href="https://www.freecodecamp.org">freeCodeCamp</a> is great.</p>

In the text of your p element, turn the words cat photos into a link by adding opening and closing anchor (a) tags around these words. Then set the href attribute to https://freecatphotoapp.com

Step 13

Now that you turned the text cat photos inside the p element into a link, you don't need the second link below the p element. Delete the entire anchor element below the p element.

Step 14

To open links in a new tab, you can use the target attribute on the anchor (a) element.

The target attribute specifies where to open the linked document. target="_blank" opens the linked document in a new tab or window.

Here is the basic syntax for an a element with a target attribute:

Example Code

<a href="https://www.freecodecamp.org" target="_blank">freeCodeCamp</a>

Add a target attribute with the value _blank to the anchor (a) element's opening tag, so that the link opens in a new tab.

Step 15

In previous steps you used an anchor element to turn text into a link. Other types of content can also be turned into a link by wrapping it in anchor tags.

Here is an example of turning an image into a link:

Example Code

<a href="example-link">
  <img src="image-link.jpg" alt="A photo of a cat.">
</a>

Turn the image into a link by surrounding it with necessary element tags. Use https://freecatphotoapp.com as the anchor's href attribute value.

Step 16

Before adding any new content, you should make use of a section element to separate the cat photos content from the future content.

The section element is used to define sections in a document, such as chapters, headers, footers, or any other sections of the document. It is a semantic element that helps with SEO and accessibility.

Example Code

<section>
  <h2>Section Title</h2>
  <p>Section content...</p>
</section>

Take your h2, comment, p, and anchor (a) elements and nest them in a section element.

Step 17

It is time to add a new section. Add a second section element below the existing section element.

Step 18

Within the second section element, add a new h2 element with the text Cat Lists.

Step 19

When you add a lower rank heading element to the page, it's implied that you're starting a new subsection.

After the last h2 element of the second section element, add an h3 element with this text:

Things cats love:

Step 20

To create an unordered list of items, you can use the ul element.

After the h3 element with the Things cats love: text, add an unordered list (ul) element. Note that nothing will be displayed at this point.

