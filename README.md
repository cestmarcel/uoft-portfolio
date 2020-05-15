# UofT Coding - Homework Assignment no. 2 
## Responsive portfolio page built with Bootstrap | May 21, 2020

### 1. The task

The task was to create a digital portfolio consisting of a homepage/about page, a portfolio page, and a contact page. I created these three pages and completed them with my personal info.

### 2. Site features

The page features a consistent navbar, a responsive layout built with Bootstrap, and responsive images. It is fully responsive and leverages Bootstrap's grid system. The CSS does not require any media queries.

#### 2.1 The homepage

The homepage serves as the about page and features a header with a headline and intro as well as a bio-part with a portrait as well as a short profile. There are also buttons to get to the portfolio page as well as the contact page and a dropdown menu features links to my online profiles. These links open in new tabs for the user's convenience.

#### 2.2 The portfolio page

The portfolio features a header with a short intro as well as a grid of six cards that each summarize a digital project I've done. They feature responsive images, a short description text, and a link to get to the respective website.

There are three actual projects and three demo projects. For the demo projects, I have implemented tooltips on the buttons, so when the user clicks them to get to the project they will be notified that this is only a demo section.

The grid is optimized for mobile phones. On desktop, the user sees a 2x3 grid, whereas on smaller screens the projects will be displayed underneath each other.

#### 2.3 The contact page

The contact page features a header with a short intro as well as a dummy-form to submit a message. The form constists of three fields to enter an email address, a name, and a message. I've added a popover to the submit-button to let the user know that this is only a dummy-form and that they cannot actually submit a message.

### 3. Challenges

- It was a bit tricky in the beginning to adjust the initial Bootstrap-design. I fixed the problem by loading my custom CSS after the Bootstrap CSS such that when I use Bootstrap class names in my custom CSS, my custom values will overwrite the initial Bootstrap values.
- I accidentally placed the popover button in the form tags, so by clicking the button the entire page would reload (as triggered by the form-submit button), making the popover disappear after a split second. I fixed this by placing the popover button outside of the form-tags.

### 4. Key learnings

- Adjusting Bootstrap designs
- Using Bootstrap components that require Javascript
- Semantic html: How to use the role-attribute for otherwise undescriptive div-tags