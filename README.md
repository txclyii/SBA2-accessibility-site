# SBA - Building a Responsive and Accessible Web Page

This project is for our SBA 2 assignment. Because I love Miffy, I've decided to create a theme around her, but what could be something cute that would also fit into this project? Maybe a little confessions page? You see, I was raised in the height of shows like Gossip Girl and Pretty Little Liars, so this project is 
somewhat an homage to my middle school self. As much as I hate to admit it, I did love listening to gossip back in the day as long as it didn't concern me or anyone I loved.

## Reflective Questions
- What accessibility challenges did you face, and how did you address them?
  <br>
  My biggest challenge was making sure the ARIA labels were implemented correctly and making sure my color palette had a good enough contrast. I addressed the first concern by constantly referring to my notes and searching up on google to verify that each label was addressed correctly in the form.
  Even then, I am still not 100% sure if it is done correctly. To address the color palette, I used the online tool to grade my color palette. Unfortunately, the first pink I have used was way too light, creating very little contrast, so I decided to go a deeper pink color to create
  enough contrast.
  <br>
- How did you ensure that your design was responsive and accessible to all users?
  <br>
  I used two different media queries. The first one was `@media screen and (min-width: 1024px)` which is supposed to make the website fit on a larger screen. I tried to make the website quite minimalist, and when the website breaks to a much smaller screen, I stacked the grid boxes
  on top of each other for a more seemless scroll. Not only that, I tried to implemenet as much semantics as I could into the HTML, making sure every section was labeled properly under the `<nav>`, `<header>`, `<main>`, etc. tags. 

- What tools or resources did you find most helpful during this project?
  <br>
  I find that using websites like [WebAIM](https://webaim.org/resources/contrastchecker/) helped me out stylistically, but when it comes to using a screen reader, I actually did try to download NVDA. However, it did not work unfortunately as it could only read out web applications when I tried to use it.
  Instead, I had to refer to websites like [W3](https://www.w3.org/WAI/fundamentals/accessibility-intro/) as a guide to see if I am labelling everything correctly.
