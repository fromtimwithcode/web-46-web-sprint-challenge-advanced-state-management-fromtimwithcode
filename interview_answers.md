# Interview Answers

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
   -Allows you to directly inject state to the component that needs it without needing to 'prop drill' through components that don't need it.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
   -Actions: object explaining the function action which is created and passed to the reducer
   -Reducers: accepts an action and runs it against possible actions
   -Store: location and method of accessing global state

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
   -Allows async calls before being passed to the reducer and allows ability to dispatch inside of another dispatch when a promise is returned.

4. What is your favorite state management system you've learned and this sprint? Please explain why!
   -Redux was on the more difficult side when it came to my learning and understanding of it, but it also became my favorite. I enjoy it because after you put in the effort of setting up, it becomes quite easy to use.
