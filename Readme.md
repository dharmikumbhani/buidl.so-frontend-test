# Buidl.so Frontend test
The test is simple.
I have added a html page in the doc folder.
This html page has a lot of css preapplied to it.
Your task is
1. Understand the underlying CSS.
2. Modify the html page so that it looks like the figma design file [here](https://www.figma.com/file/NjU5ionm0MWMnyvzAmriCm/buidl.so-frontend-test?node-id=0%3A1), If you have your own idea for how this program page should look like, then please do that! you don't have to abide by the figma design file attached.
3. Figure out and implement mobile responsiveness on your own + read tips.
4. Create a new css file (stylesheet-6.css) with proper commenting and add it at the end of all stylesheet files in the head tag.

> When you go through the html code you will observe a lot of child divs and  classes like view-contents, view-form, view-items, etc. these divs and classes are coming from backend (since its a coupled architecture) make sure you understand how thats structured. while redeveloping the page you might not necessarily add these extra tags and classes but understanding of this underlying html structure will become v important later on when you join.

## Tips
---
1. Go mobile first
2. Make sure you go through the constants that have been applied (things like typography, margins, gutter) and use them as much as possible. If you still want to customize it then use the css calc function.
3. For media queries we use 2, only 2 queries with default being mobile -
   1. min 720px - for tablets
   2. min 1024px - for desktops (you can better understand this looking at css files)
4. The code changing that you will have to do will be only be for inside #main-content element
5. Whatever content you write it doesn't matter mostly all the content is going to come via the backend. so lorem ipsum at most places will do for this test

## You will be judged based on:
---
- How concise your CSS is
- Amount of css class you had to create to achieve this page.
- Understanding of how the html code was structured in the initially given file

What matters here is how comfortable are you in working with such level of complexities in code and how can you come up with unique solutions with all the various constraints that are there from the backend.

## Extras
---
- We using bootstrap3 (yikes, yup we know) as our underlying CSS framework, so if you are someone who has used it before then thats a plus.
- If you have worked with drupal before and know how layouts work then that a huge plus.


For any doubts or anything reach out to me via [twitter](https://twitter.com/dharmikumbhani) or mail me at [dharmi@buidlerstribe.com](mailto:dharmi@buidlerstribe.com)

