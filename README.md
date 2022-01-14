# Heading 1: How did i complete the assignment?

# Notes

I created the html file, once i created the basics i started to do my semnatic html after i did that then i added classes to them. I made my nav, header, section, footer. i applied classes to all of them. i made sure the links were working before i started my styles.css. once everything was complete i linked my styles.css to my html so it can be external file. The first thing i started working was the home page. Once i completed that i went ahead and went to the "about-me" section i used grid for the styling of it like i did with my home. i started to work on the "my work" section this was a little harder to do but the way i did it was i used lniks attached the pcitures and i used a :hover and back-ground to make it notcible that you are going to click on the picture which will direct you to my previous work. after that it was easier to do was the contact me section added back ground used flex and justfied content center, i got the logos using font awesome logos to do this i just added links to them so it wouldn't be empty. In my html i had created a classes with the hamburger, this is what i did to create the j.s for this i used psuedo classes ::before and ::after i had to use the attrubiate transform: rotate to get the x in my hamburger i used the addEventListener 'click' to open up the hamburger and once that was working the "home" "about me" "my work" "contact me" wasn't working properly so i had to add navLinks.forEach and had to give it a function of document.body.classList.remove ('nav-open) i did this so i could have extra protection just incase it wouldnt exit. after i did this i did my media.

## Heading 2: User Story

## Story

User Story
AS AN employer
I WANT to view a potential employee's deployed portfolio of work samples
SO THAT I can review samples of their work and assess whether they're a good candidate for an open position

# Heading 3: Acceptance Criteria

# Requiremtns

Here are the critical requirements necessary to develop a portfolio that satisfies a typical hiring manager’s needs:

GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
