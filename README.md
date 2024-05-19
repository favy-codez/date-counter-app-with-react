### Things I learnt during thr course of this project
- **Callback Functions in React State Updates** - A callback function is a function that is passed as an argument to another function and is executed after some operation has been completed, callbacks are often used to handle asynchronous operations or to ensure certain tasks are performed in a specific order. 
```
<button onClick={() => setCount((c) => c - step)}>-</button>

```
To ensure that state updates correctly reflect the latest state, you can use a callback function inside the state setter. This callback receives the current state as an argument, allowing you to compute the new state based on the most recent value.

- **How to initializes a base date using new Date -**
```
const date = new Date("september 8, 2024")
```
