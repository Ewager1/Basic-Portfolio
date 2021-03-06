# Basic Portfolio

[My Basic Portfolio](https://ewager1.github.io/Basic-Portfolio/)

---

## Goals

To use Bootstrap CSS Framework to build a basic but professional portfolio that can display future projects

It must contain:

- A navbar

- A responsive layout

- Responsive images

- HTML validated

- Sticky footer

---

## Results

- Created a responsive website from scratch. Below are exampes of each screen size

- Mobile
  ![Icon Demo](/assets/images/xm-screen-demo.png)

- Small
  ![Icon Demo](./assets/images/sm-screen-demo.png)

- Medium
  ![Icon Demo](./assets/images/med-screen-demo.png)

- Large
  ![Icon Demo](./assets/images/large-screen-demo.png)

I added a few small improvements of my own

- nav anchors are underlined showing what page the user is on

![Icon Demo](./assets/images/nav-demo.png)

- nav anchors have a .hover bold
- Created Contact image links to look more professional
- Contact image links have a .hover event that reduce opacity to 0.7 to look cooler

![Icon Demo](./assets/images/icon-demo.png)

- Added a fancy top-hat Favicon

## New things I learned:

- How to add Boot Strap elements to my work
- How to space elements with bootstrap spacing like ml-3
- How to create responsive layouts from mobile to desktop size using things like ml-sm-3 and col-md-4
- How to create a sticky footer
- How to link icon images (Contact Section)

---

## Challenges I faced:

- One of the challenges I faced was getting img-fluid to work. Whenever I used the img-fluid class, my image would blow up
  to the entire page instead of taking up it's parent div. I spent a lot of time on this, and it seems that using the float-left
  property doesn't play well with img-fluid. I found a workaround by looking up how img-fluid sets width-100% and height-auto, so
  I used basic css to create width-17% and height-auto. This created a close effect of changing the img size to always be relative to
  the page. I also had to add a min-width so it didn't shrink too small.

- Another thing I found challenging in this project was going from the CSS version I built the first week, which had no bootstrap,
  to a boot-strap refactor. replacing margins step by step with bootstrap m- and p- was hard to keep straight. However, I found my
  groove when i created a new "test" page and went section by section. The good news is i learned a lot more about the relationship
  between bootstrap shortcuts and the css they implement.
