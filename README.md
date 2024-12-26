# Inefficient useEffect in React Component

This repository demonstrates a common performance issue in React applications involving the `useEffect` hook.  The example showcases an `useEffect` that runs after every render, leading to unnecessary re-renders and console logs.  This is inefficient and can negatively impact performance, especially as the application grows in complexity.

The solution demonstrates how to optimize the `useEffect` to run only when necessary, improving performance and efficiency.