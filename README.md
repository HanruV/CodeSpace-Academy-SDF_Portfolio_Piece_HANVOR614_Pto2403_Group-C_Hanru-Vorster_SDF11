# Cache Bank web-app main page. This is a portfolio piece done with Code Space Academy

## IMPORTANT LINKS

- Recording: https://www.loom.com/share/b1bbf678811746dfb066c2e8d05fd261?sid=72c350e7-ad91-4fd7-bc75-3061cfad8777

- Presentation: https://docs.google.com/presentation/d/1phNoyYUizIhx37zwAZO_2atLe7wU2mY3/edit?usp=sharing&ouid=102580903647944006369&rtpof=true&sd=true

## Objectives

- Demonstrate Web Development Skills
    - Media design
    - Web structuring
    - Styling of elements
    - Responsive design
    - Version control

- Soft Skills
    - Presenting code
    - Adhering to briefs

- Other
    - Adhering to best coding practices
    - Documentation

## Tech-stack used
    
- HTML
- CSS (Tailwind)
- Java Script

## Project structure

- Component 1 (Navigation)
- Component 2 (Products)
- Component 3 (Features)
- Component 4 (Getting Started)
- Component 5 (Contact)
- Footer

#### Component 1

- Showcasing the use of **"hidden"** and the **"md:"** utility classes to reveal/hide "a" and "button" elements for responsive design
- Using JS to toggel a **"hidden"** utility class on a "button" to reveale a **moblie-menu**

#### Component 2

- Here the endorsements are showcased to show credibility and establish trust with future clients
- The call to action "buttons" have been imported from tailwindcomponents and custom project styles have been applied. The use of 3D buttons and vivid colors grabs the attention of users more
- In this component grid has been used on a mobile 1st approach, as 1 col for smaller screens and then span into 2 cols for bigger screens. The grid composes of 2 sections, 1 for the heading, paragragh, and buttons; The other for the image. The grid display allows us more flexibility on bigger layouts to control how data is displayd on various screens sizes

#### Component 3

- Layout: Using grid and flex for responsive design (main focus here is on the 6 cards - having 1 grid on mobile, 2 on medium sizes, and 3 on large sizes). The main container and all of the cards are flex:col to stack the content vertically
- ARIA has been used to assist with tabbing and where a user is within the tab order of the cards via aria-labels, role="tab"

#### Component 4

- Engaging design: Here we make use of numbers, color, and order of content to make it easy to follow the steps to get users started
- JS for animations: JS is used here to count up the stat numbers when users come to the section, this draws attention to accombplishments, and credibility

#### Component 5

- Layout: 3 contact cards are displayed in 1 column on mobile, and 3 on medium screens. Flex box is used to stack and space items
- Accessibility/design: by using similar colors for icons and information relating to them, correlation is created. Accessibility with aria as been added as roles, and titles to the svgs (icons)