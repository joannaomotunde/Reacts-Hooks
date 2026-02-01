# React + Vite

## React Hooks Assignment – Week 9

### Description
This project demonstrates the use of React Hooks (`useState` and `useEffect`) through three simple components: a Counter, a Todo List, and a User Data Fetcher.

### Components

#### 1. Counter
- Uses `useState` to manage a count value
- Includes increment, decrement, and reset buttons
- Displays the current count

#### 2. Todo List
- Uses `useState` to manage a list of todos and input value
- Allows users to add new todos
- Displays all todos in a list
- Each todo can be deleted individually

#### 3. User Data Fetcher
- Uses `useState` to manage user data and loading state
- Uses `useEffect` to fetch data when the component mounts
- Fetches data from: https://jsonplaceholder.typicode.com/users/1
- Displays user name, email, and city
- Shows a loading message while fetching data

### Approach
I broke the assignment into separate components to keep the code clean and readable. React hooks were used to manage state and side effects, following best practices.

### Challenges Faced
- Understanding how `useEffect` runs when a component mounts
- Handling loading state while fetching data
- Git and GitHub setup and pushing changes

### Testing Checklist
- Counter increments, decrements, and resets ✔
- Todo list adds new items ✔
- Todo list deletes items ✔
- User data fetches and displays ✔
- No console errors ✔