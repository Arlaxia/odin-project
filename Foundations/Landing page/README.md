# Project: Landing page
## Introduction
Odin description: For this project you’ll be creating an entire web page from a design we’ll provide for you. If you’ve been following along you should have the skills you need to accomplish this, but it may not be easy!

## Solving process
First of all, give the main HTML content and structure to the content. I divided every visible section more or less into boxes, for which I used semantic HTML tags, and then use flexbox with a column direction.

After that, it's about working on it section by section. I focused on each section, from top to bottom, styled it so that it looked like the expected end product and added HTML in the cases where some extra was needed.

## Difficulties
I found at some point that some flex items such as the header and footer were shrinking. At first I thought about applying the `flex-shrink: 0` to these, but it seemed to be a bad solution, sine the items shouldn't be shrinking to start with.

I realized then that I had set the body heigth to 100vh as I use to when not using flexbox. That was limiting the space the flex items inside had, and so some where obviously shrinking before overflowing (and the scroll bar appearing). This was a nice practical reminder of how flex containers work.