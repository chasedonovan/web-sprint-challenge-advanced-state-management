# Interview Answers
Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?
  makes prop drilling easier/faster.

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?
  actions passes information to the store. 
  reducers are used to change state.
  store is an object that holds the state 

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?
  its a middleware that can let you write action creators, which return functions instead of an action.

4. What is your favorite state management system you've learned and this sprint? Please explain why!
  redux is probably my favorite. It seems to work better with larger apps and multiple components. Context api is easier, but wouldnt be a go-to unless ones building a smaller app.