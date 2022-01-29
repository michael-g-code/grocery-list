# grocery-list
React Groceries
Build an app that let's you make a list of groceries to buy

Learning Objectives
Practice setting up a React app
Practice Mocking a React app
Practice using state
Practice rendering a list
Practice conditional rendering
Prerequisites
Introduction to React static components, mocking, state, rendering
Getting Started
mkdir react_groceries
cd react_groceries
touch index.html app.js
add all of the scripts for a react app
Deliverables
Build a grocery app that allows users to make a grocery list

Technical Requirements
Read over these specs and draw a mockup of your app (don't worry about bonus features at this point)
Must have grocery items in this shape
{
  item: '',
  brand '',
  units: '',
  quantity: 0,
  isPurchased: false
}
Make an array of 3 objects using the above shape and render the item, quantity and units (12 pack, 1lb, 2 liters, etc.)
Make inputs so that new items can be added
Conditionally render the grocery items based on whether or not they were purchased (ok to have hard coded values for isPurchased)
Add some style to your app
Stretch Add a button that says 'remove' and when clicked the value of isPurchased is toggled
Submission Guidelines
Submit the Github link 