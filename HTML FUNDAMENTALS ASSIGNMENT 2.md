 1. Absolute vs. Relative URLs

 Absolute URLs: This is the complete, full web address of a file or page. It includes the protocol (like https://) and the domain name, meaning it will successfully locate the resource from anywhere on the internet.
 Example: [https://www.example.com/products/shoes.html](https://www.example.com/products/shoes.html)


 Relative URLs: This is a shorthand or partial address. It relies on the current page's domain and folder structure to fill in the blanks. It only works if the file is hosted on the same website.
 Example: /products/shoes.html



 2. The alt Attribute

The alt (alternative text) attribute within an <img> tag provides a written description of a picture. It is critical for two main reasons:

 Web Accessibility: Visually impaired users rely on screen-reading software to browse the web. The software reads the alt text aloud, ensuring they don't miss out on the visual context.
 Fallback Content: If a user has a weak internet connection or the image file is broken, the browser will display the alt text in its place so the user still understands what was supposed to be there.

 3. Ordered (<ol>) vs. Unordered (<ul>) Lists

 <ol> (Ordered List): This automatically numbers the list items. It should be used when the sequence is strictly important, such as step-by-step instructions or rankings.
 <ul> (Unordered List): This formats the list items with bullet points. It is used for groupings where the exact order doesn't matter, like a standard grocery list.

 4. The target="_blank" Attribute

When you add target="_blank" to a link (<a> tag), it forces the browser to open that specific link in a brand-new tab or window. This keeps the user from navigating away and losing their place on your original page.

 5. Favicons

A favicon is the tiny graphical logo that sits next to a website's title in the browser tab, history, or bookmarks (for example, the red play button for YouTube).

To apply a favicon to a webpage, you must place the code inside the <head> section of your HTML document.

Example:


<head>
   <link rel="icon" href="favicon.ico"> 
</head>
