## To Do List

Build a simple  offline only todo list (store using indexdb/localstorage) with an ability to set due time and get alerts when an item due time is passed

### Assignment

- A simple web app that allows you create todo items and mark them when they are completed. When an item is completed, cross over the item 

- It should be possible to set a due date for any item and get an alert when the item is past due

- Store the items in the browser itself so that it works offline

- The code should be designed in a way that it should be possible to change the storage layer to backend without changing a lot in the code. Same is true about alerts, it should be possible to expand to get alerts using websockets / sse

- Ability to sort items as per due time and completion status. You can also decide to reorder it autmatically as soon as each item is added for bonus points but that should have proper animations and look good and not flicker

- App should support keyboard shortcuts (Create new item, delete item, mark item as done)

- Abilit to search items 




### Directions

- There is no fixed limit for the assignment, you can submit it whenever you are done, but ideally you shouldnt spend more than 4-5 hours on this.

- While we are not looking for a perfect solution, you should at least think through possible edge cases while building an offline enabled todo app which can hold millions of items. Think through about how will you handle caching given that list can be manipulated across multiple devices, handle due dates given there can be millions of items in the list, handle UI responsiveness etc.

- Encourage you to use modern web technologies like Service Worker/Indexdb if it make sense

- While design is not a strong focus, app should be usable and look good. You can check out some of the todo apps here https://zapier.com/blog/best-todo-list-apps/ for inspiration.

- You must use es6 + reactjs for this assignment. Recommend Use [create-react-app](https://github.com/facebookincubator/create-react-app)
for bootstraping.

- Scope of the assignment is intentionally kept broad, so it's totally fine if it's not complete in the stipulated time. We would love to see the assignment anyway.

- Keeping above point in mind, attempt the tasks in the order that they are mentioned.

- Call us if you have any trouble understading anything

- Most importantly, have fun building it :) :)


