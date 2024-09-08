
To install **larry-state**, follow these simple steps to add it to your React project:

#### Install via npm or yarn:

If you're using npm, run:

```bash
npm install larry-state
```

If you're using yarn, run:

```bash
yarn add larry-state
```

Reach out full [Documentation](https://duckduckgo.com "larry-state react state management").

### What is **larry-state**?

**larry-state** is a lightweight and efficient global state management library tailored for React applications. It simplifies the process of managing application-wide state by providing both persistent and non-persistent options. Designed for small to medium-sized projects, it offers a straightforward alternative to more complex libraries like Redux, allowing developers to manage global state effortlessly while maintaining clean, readable code.

By leveraging React's native `useContext` and `useReducer` hooks, **larry-state** seamlessly integrates into existing React projects with minimal setup. Additionally, the library offers built-in state persistence using `localStorage`, enabling your app to retain data across browser sessions when necessary.

### Why Choose **larry-state**?

- **Simple Setup**: With no complex configuration, you can wrap your app in the `GlobalStateProvider` and start managing state right away.
- **Minimal Boilerplate**: Skip the need for actions, reducers, and middleware. Use simple hooks to access and update global state.
- **Built-in Persistence**: Easily persist global state with `localStorage`, ensuring your app remembers important values across browser sessions.
- **TypeScript Support**: Fully typed, offering developers type-safe state management out of the box, reducing bugs and increasing maintainability.
- **Lightweight & Fast**: Focused on performance, **larry-state** is ideal for small to medium-sized applications where simplicity and speed are priorities.

### Key Features of **larry-state**:

1. **Global State Management**: Manage shared state across your entire application without needing to pass props through multiple levels.
2. **Customizable Hooks**: Take advantage of flexible hooks to update or reset state, including the ability to dynamically persist or reset values.
3. **Zero Middleware**: No need for complex middleware setups—manage your application state with direct, intuitive functions.

### How It Works:

At the core of **larry-state** is a provider component that wraps your application, making global state available anywhere in the component tree. Through the use of a custom hook, you can directly access and update state with minimal effort, allowing you to focus on building features instead of writing boilerplate code.

**larry-state** also simplifies persistence: by enabling state persistence with a single option, your application's critical data can be saved to `localStorage`, so it remains intact even after a page refresh or browser restart.

This combination of flexibility, simplicity, and performance makes **larry-state** an excellent choice for React developers looking for a lightweight yet powerful solution to global state management.

Reach out full [Documentation](https://duckduckgo.com "larry-state react state management").