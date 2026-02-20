# mini-project-04

## Spring 2026

### Topic: React Hooks (useEffect, useState) + TailwindCSS

### Reading:

1. React Hooks:

- React Hooks are special functions that allow you to use state and other React features in functional components without writing a class. They were introduced in React 16.8 to simplify code, improve readability, and facilitate the reuse of stateful logic.

- Some popular and useful React Hooks are:
  - `useState`
  - `useEffect`
  - `useContext`
  - `useReducer`
  - `useRef`

- We will use `useEffect` and `useState` in today's lab.

  a) `useEffect`: It performs side effects (e.g., data fetching, subscriptions, manual DOM updates) in functional components.
  - check `TestUseEffect.jsx`. While testing it, comment out `<App / >` from the `main.jsx` file and add `<TestUseEffect />` instead. Notice how `useEffect` is triggered/called when the dependency (`count`) changes. -**Note:** if the dependency array is left empty, it means, the `useEffect` function will be called only once (first time DOM rendering).

  - More examples: https://www.w3schools.com/react/react_useeffect.asp (please check before moving forward)

    b) `useState`: The React useState Hook allows us to track state in a function component. State generally refers to data or properties that need to be tracking in an application.

2. Styling Web Apps:

   a) **Semantic CSS**: It focuses on naming classes based on the content's meaning or purpose (e.g., .site-header, .main-navigation), keeping the HTML clean and the styling logic separate in a dedicated CSS file.
   - **Advantages:**
     - **Clean HTML:** Keeps the HTML markup clean and focused on structure and content.
     - **Strong Separation of Concerns:** Styles are kept entirely separate from the content in dedicated .css files, which aligns with traditional web development principles.

     - **Ease of Theming/Reskinning:** A single stylesheet can be swapped out to completely change the look of an entire website.
     - **Standardized Components:** Component-based frameworks offer consistent, pre-built UI elements that reduce design decision fatigue and make onboarding new developers easier.

   - **Disadvantages:**
     - **CSS Bloat:** Can lead to large CSS files as projects grow, sometimes with unused or overridden styles.
     - **Customization Difficulties:** Deviating from a component framework's default design can require significant effort, often involving complex overrides or !important rules.
     - **"Naming Things" Problem:** Developers often spend time debating class names and managing naming collisions.

### ToDos:

### Resources:

- https://www.w3schools.com/react/react_hooks.asp
