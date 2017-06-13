# Typescript_Assignment_15.2


● Create a global service, should be available in whole application.
Make a left section as separate component having only links.

● Then create 4 more components which will be rendered when user clicks
those left section links.

● Make a link active if the user clicks that link.
And if user reloads the page, that link should be active.

Notes:


Angular CLI is used to create app. So, use ng serve to run on localhost:4200

Created a Test Service which just provides a string when a component requests it

Created a left-sided navbar which has a collapsible toggle.
Clicking on the button shows/hides the side menu
The side menu has 4 links: Home, About, Contact and Courses
In addition, there is a brand: Bazaar, which takes you to the home page

Each of the link opens its own page (component)

Implemented router to navigate between pages

Used routerLinkActive to set active link (red color)
Re-loading page still retains active link
