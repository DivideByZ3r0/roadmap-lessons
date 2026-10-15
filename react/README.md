# React Developer Roadmap — Lessons

**How to use:** tick `[x]` when done, and rate yourself by replacing ☆ with ★ (★☆☆☆☆ = just heard of it · ★★★★★ = can teach it). Quiz answers are hidden — click *Answer* to reveal.

Source: https://roadmap.sh/react (lesson order follows the roadmap)

---

## 1. CLI Tools — ☆☆☆☆☆

> CLI tools are command line programs that help developers set up, run, and manage a React project without doing everything by hand. They handle tasks like creating a new project structure, starting a development server, or bundling code for production. Most modern React setups rely on a CLI tool instead of manual configuration, since it saves time and avoids mistakes.

**📚 Learn:**

- 📄 Article: [vite](https://vitejs.dev)

**✅ Checklist:**

- [ ] Vite — ☆☆☆☆☆
  - 🏛️ Official: [Vite Website](https://vitejs.dev)
  - 🏛️ Official: [Vite Documentation](https://vitejs.dev/guide)
  - 🎥 Video: [Vite Crash Course](https://youtu.be/LQQ3CR2JTX8)
  - 🎥 Video: [Vite Crash Course | Faster Alternative To CRA | 2023](https://www.youtube.com/watch?v=89NJdbYTgJ8)

### 🧠 Quiz

1. How do you create a new React project with Vite?
   <details><summary>Answer</summary>npm create vite@latest my-app -- --template react-ts (or react).</details>

2. Why is Create React App no longer recommended?
   <details><summary>Answer</summary>It's deprecated and unmaintained; Vite or a framework like Next.js are faster and current.</details>

3. What does npm run build produce?
   <details><summary>Answer</summary>An optimized production bundle (static files) in the dist/ folder.</details>

---

## 2. Components — ☆☆☆☆☆

> Components are the building blocks of a React application. Each one is a piece of code, usually a function, that returns some UI and can be reused across the app. Breaking an interface into components makes the code easier to read, test, and maintain.

**📚 Learn:**

- 🏛️ Official: [Creating and nesting components](https://react.dev/learn#components)
- 📄 Article: [Explore the different types of components in React](https://www.robinwieruch.de/react-component-types/)
- 📄 Article: [What is the difference between components, elements, and instances?](https://www.robinwieruch.de/react-element-component/)
- 🎥 Video: [Components & Templates in React](https://www.youtube.com/watch?v=9D1x7-2FmTA)

**✅ Checklist:**

- [ ] Functional Components — ☆☆☆☆☆
  - 🏛️ Official: [Functional Components and Props](https://react.dev/reference/react/Component)
  - 🏛️ Official: [Your first component](https://react.dev/learn/your-first-component)
  - 🏛️ Official: [Passing props to a component](https://react.dev/learn/passing-props-to-a-component)
  - 📄 Article: [Functional Components in React](https://www.robinwieruch.de/react-function-component/)
  - 🎥 Video: [React JS Functional Components](https://www.youtube.com/watch?v=NJ_qbsLf52w)
- [ ] JSX — ☆☆☆☆☆
  - 🏛️ Official: [Writing markup with JSX](https://react.dev/learn/writing-markup-with-jsx)
  - 🏛️ Official: [JavaScript in JSX with Curly Braces](https://react.dev/learn/javascript-in-jsx-with-curly-braces)
  - 📄 Article: [Working with JSX - React - CodeGuage](https://www.codeguage.com/courses/react/jsx)
- [ ] Props vs State — ☆☆☆☆☆
  - 🏛️ Official: [State: A Component's Memory](https://react.dev/learn/state-a-components-memory)
  - 📄 Article: [How to use Props in React](https://www.robinwieruch.de/react-pass-props-to-component/)
  - 📄 Article: [What is the difference between state and props in React?](https://stackoverflow.com/questions/27991366/what-is-the-difference-between-state-and-props-in-react)
  - 📄 Article: [How to update state from props in React](https://www.robinwieruch.de/react-derive-state-props/)
- [ ] Conditional Rendering — ☆☆☆☆☆
  - 🏛️ Official: [Conditional Rendering](https://react.dev/learn/conditional-rendering)
  - 📄 Article: [Different techniques for conditional rendering in React](https://www.robinwieruch.de/conditional-rendering-react/)
  - 🎥 Video: [Conditional rendering in React](https://www.youtube.com/watch?v=4oCVDkb_EIs)
- [ ] Composition — ☆☆☆☆☆
  - 🏛️ Official: [Passing JSX as children](https://react.dev/learn/passing-props-to-a-component#passing-jsx-as-children)
  - 📄 Article: [Composition vs Inheritance](https://reactjs.org/docs/composition-vs-inheritance.html)
  - 📄 Article: [How to perform component composition in React](https://www.robinwieruch.de/react-component-composition/)
  - 📄 Article: [Achieving Reusability With React Composition](https://formidable.com/blog/2021/react-composition/)

### 🧠 Quiz

1. What is JSX?
   <details><summary>Answer</summary>A syntax extension that lets you write HTML-like markup in JavaScript; it compiles to function calls.</details>

2. What is the difference between props and state?
   <details><summary>Answer</summary>Props are read-only inputs from a parent; state is internal data the component can change, triggering re-renders.</details>

3. How do you render something conditionally?
   <details><summary>Answer</summary>With &amp;&amp;, the ternary operator, or an early return, e.g. {isLoggedIn ? &lt;Profile /&gt; : &lt;Login /&gt;}.</details>

---

## 3. Rendering — ☆☆☆☆☆

> Rendering is the process where React takes your component code and turns it into actual elements on the screen. React decides when to re-render a component based on changes to its state or props. Understanding how rendering works helps explain why an app updates the way it does, and where performance issues can come from.

**📚 Learn:**

- 🏛️ Official: [Render and Commit - Official Docs](https://react.dev/learn/render-and-commit)
- 📄 Article: [Rendering in React - ui.dev](https://ui.dev/why-react-renders)
- 📄 Article: [Fix the slow render before you fix the re-render](https://kentcdodds.com/blog/fix-the-slow-render-before-you-fix-the-re-render)

**✅ Checklist:**

- [ ] Component Lifecycle — ☆☆☆☆☆
  - 🏛️ Official: [Lifecycle of Reactive Effects](https://react.dev/learn/lifecycle-of-reactive-effects)
  - 🏛️ Official: [Class Component](https://react.dev/reference/react/Component)
  - 📄 Article: [React component lifecycle: React lifecycle methods & hooks](https://tsh.io/blog/react-component-lifecycle-methods-vs-hooks/)
  - 📄 Article: [The React lifecycle: methods and hooks explained](https://retool.com/blog/the-react-lifecycle-methods-and-hooks-explained#react-hooks-and-the-component-lifecycle)
- [ ] Lists and Keys — ☆☆☆☆☆
  - 🏛️ Official: [Lists and Keys](https://react.dev/learn/rendering-lists#keeping-list-items-in-order-with-key)
  - 🏛️ Official: [Rendering Lists](https://react.dev/learn/rendering-lists)
  - 📄 Article: [List components in React by Example](https://www.robinwieruch.de/react-list-component/)
  - 📄 Article: [Why do we need the key prop in React?](https://www.robinwieruch.de/react-list-key/)
- [ ] Render Props — ☆☆☆☆☆
  - 🏛️ Official: [Render Props in React](https://react.dev/learn/passing-props-to-a-component)
  - 📄 Article: [How to create a Render Prop Component](https://www.robinwieruch.de/react-render-props/)
  - 📄 Article: [Render Props Pattern](https://www.patterns.dev/posts/render-props-pattern/)
- [ ] Refs — ☆☆☆☆☆
  - 🏛️ Official: [Referencing Values with Refs](https://react.dev/learn/referencing-values-with-refs)
  - 🏛️ Official: [Manipulating the DOM with Refs](https://react.dev/learn/manipulating-the-dom-with-refs)
  - 📄 Article: [Examples of using refs in React](https://www.robinwieruch.de/react-ref/)
  - 🎥 Video: [Learn useRef in 11 Minutes - Web Dev Simplified](https://www.youtube.com/watch?v=t2ypzz6gJm0)
- [ ] Events — ☆☆☆☆☆
  - 🏛️ Official: [Responding to Events](https://react.dev/learn/responding-to-events)
  - 🏛️ Official: [React Event Object (Synthetic Event)](https://react.dev/reference/react-dom/components/common#react-event-object)
  - 📄 Article: [React Event Handler](https://www.robinwieruch.de/react-event-handler/)
- [ ] High Order Components — ☆☆☆☆☆
  - 📄 Article: [High-Order Components](https://reactjs.org/docs/higher-order-components.html)
  - 📄 Article: [How to create a Higher-Order Component](https://www.robinwieruch.de/react-higher-order-components/)
  - 🎥 Video: [Learn React Higher Order Component (HOC) in 10 Minutes](https://youtu.be/J5P0q7EROfw?si=-8s5h1b0mZSGVgLt)
  - 🎥 Video: [ReactJS Tutorial - Higher Order Components (Part 1)](https://www.youtube.com/watch?v=B6aNv8nkUSw)

### 🧠 Quiz

1. What causes a component to re-render?
   <details><summary>Answer</summary>Its state changes, its parent re-renders, or a context it uses changes.</details>

2. Why do list items need a stable key?
   <details><summary>Answer</summary>So React can match items between renders; index keys break on reordering/insertions.</details>

3. What is a ref used for?
   <details><summary>Answer</summary>Accessing a DOM node or keeping a mutable value that doesn't trigger re-renders.</details>

---

## 4. Hooks — ☆☆☆☆☆

> Hooks are functions that let you use React features like state and lifecycle behavior inside function components. They were introduced to avoid the need for class components when handling things like data fetching or subscriptions. Every hook name starts with "use", such as useState or useEffect, and they must be called in the same order on every render.

**📚 Learn:**

- 🏛️ Official: [Hooks Reference](https://react.dev/reference/react)

**✅ Checklist:**

- [ ] useState — ☆☆☆☆☆
  - 🏛️ Official: [useState Documentation](https://react.dev/reference/react/useState)
  - 🏛️ Official: [State: A Component's Memory](https://react.dev/learn/state-a-components-memory)
  - 🏛️ Official: [Adding Interactivity](https://react.dev/learn/adding-interactivity)
  - 📄 Article: [eact Hooks: useState Explained](https://www.robinwieruch.de/react-usestate-hook/)
- [ ] useEffect — ☆☆☆☆☆
  - 🏛️ Official: [Using the Effect Hook](https://react.dev/reference/react/useEffect)
  - 📄 Article: [React useEffect Hook by Example](https://www.robinwieruch.de/react-useeffect-hook/)
- [ ] useRef — ☆☆☆☆☆
  - 🏛️ Official: [useRef](https://react.dev/reference/react/useRef)
  - 🎥 Video: [WebDevSimplified](https://www.youtube.com/watch?v=t2ypzz6gJm0)
- [ ] useContext — ☆☆☆☆☆
  - 🏛️ Official: [Using useContext](https://react.dev/reference/react/useContext)
  - 🏛️ Official: [Explore the concept of context](https://react.dev/learn/passing-data-deeply-with-context)
  - 🎥 Video: [Learn useContext In 13 Minutes](https://www.youtube.com/watch?v=5LrDIWkK_Bc)
- [ ] useReducer — ☆☆☆☆☆
  - 🏛️ Official: [useReducer Docs](https://react.dev/reference/react/useReducer)
  - 📄 Article: [The React useReducer Hook](https://www.telerik.com/blogs/react-usereducer-hook)
  - 📄 Article: [A guide to the React useReducer Hook](https://blog.logrocket.com/react-usereducer-hook-ultimate-guide/)
  - 🎥 Video: [Learn React Hooks: useReducer - Simply Explained!](https://www.youtube.com/watch?v=rgp_iCVS8ys&t)
- [ ] useMemo — ☆☆☆☆☆
  - 🏛️ Official: [useMemo Docs](https://react.dev/reference/react/useMemo)
  - 📄 Article: [useMemo and useCallback - Josh W. Comeau](https://www.joshwcomeau.com/react/usememo-and-usecallback/)
- [ ] useCallback — ☆☆☆☆☆
  - 🏛️ Official: [React Documentation on useCallback](https://react.dev/reference/react/useCallback)
  - 📄 Article: [useCallback Explained in Depth](https://kentcdodds.com/blog/usememo-and-usecallback)
  - 📄 Article: [useCallback Hook: An Introductory Guide](https://dmitripavlutin.com/dont-overuse-react-usecallback/)
- [ ] Creating Custom Hooks — ☆☆☆☆☆
  - 🏛️ Official: [Reusing Logic with Custom Hooks](https://react.dev/learn/reusing-logic-with-custom-hooks)
  - 📄 Article: [How to create a custom Hook (2) followed by Examples](https://www.robinwieruch.de/react-custom-hook/)
  - 🎥 Video: [Custom Hooks in React](https://www.youtube.com/watch?v=I2Bgi0Qcdvc)
- [ ] Hooks Best Practices — ☆☆☆☆☆
  - 🏛️ Official: [Rules of Hooks](https://react.dev/reference/rules/rules-of-hooks/)
  - 📄 Article: [React Hooks Best Practices: Unlocking Efficiency and Elegance](https://medium.com/womenintechnology/react-hooks-best-practices-unlocking-efficiency-and-elegance-da23f7e1418a)
  - 📄 Article: [Mastering React Hooks: Best Practices and Common Pitfalls](https://dev.to/codesensei/mastering-react-hooks-best-practices-and-common-pitfalls-3d9i)
  - 📄 Article: [React Custom Hooks: Best Practices and Examples](https://utopia-insights.dev/react-custom-hooks-best-practices-and-examples/)

### 🧠 Quiz

1. What are the rules of hooks?
   <details><summary>Answer</summary>Only call hooks at the top level (not in loops/conditions) and only from components or custom hooks.</details>

2. What is the dependency array in useEffect?
   <details><summary>Answer</summary>The list of values the effect depends on; it re-runs when they change ([] = only on mount).</details>

3. When should you use useMemo or useCallback?
   <details><summary>Answer</summary>To memoize expensive calculations or keep function identity stable for memoized children — not by default everywhere.</details>

---

## 5. Routers — ☆☆☆☆☆

> A router in React handles navigation between different views or pages without reloading the whole browser page. It matches the current URL to a specific component and renders it, giving the app the feel of multiple pages while staying a single-page application. Several libraries exist to add this functionality, since React itself does not include routing.

**📚 Learn:**

- 📄 Article: [How to use Routing in React JS: A Comprehensive Guide.](https://blog.logrocket.com/react-router-v6-guide/)
- 🎥 Video: [React Router 6 – Tutorial for Beginners.](https://www.youtube.com/watch?v=59IXY5IDrBA)

**✅ Checklist:**

- [ ] React Router — ☆☆☆☆☆
  - 🏛️ Official: [React Router — Official Website](https://reactrouter.com/)
  - 📄 Article: [What is React Router?](https://www.w3schools.com/react/react_router.asp)
  - 📄 Article: [React Router V7: A Crash Course](https://dev.to/pedrotech/react-router-v7-a-crash-course-2m86)
- [ ] Tanstack Router — ☆☆☆☆☆
  - 📄 Article: [TanStack Router Documentation](https://tanstack.com/router/latest/docs/framework/react/overview)
  - 🎥 Video: [TanStack Router - Crash Course](https://www.youtube.com/watch?v=4sslBg8LprE&list=PLOQjd5dsGSxJilh0lBofeY8Qib98kzmF5)
  - 🎥 Video: [TanStack Router Vite: Ultimate Guide for Beginners](https://www.youtube.com/watch?v=AN9rD7y9MS8)

### 🧠 Quiz

1. What does a client-side router do?
   <details><summary>Answer</summary>Maps URLs to components and changes views without full page reloads.</details>

2. How do you read a URL parameter like /users/:id in React Router?
   <details><summary>Answer</summary>const { id } = useParams().</details>

3. What is a key selling point of TanStack Router?
   <details><summary>Answer</summary>Fully type-safe routes, params and search params.</details>

---

## 6. State Management — ☆☆☆☆☆

> Application state management is the process of maintaining knowledge of an application's inputs across multiple related data flows that form a complete business transaction -- or a session -- to understand the condition of the app at any given moment. In computer science, an input is information put into the program by the user and state refers to the condition of an application according to its stored inputs -- saved as variables or constants. State can also be described as the collection of preserved information that forms a complete session.

**📚 Learn:**

- 📄 Article: [What is State Management?](https://www.techtarget.com/searchapparchitecture/definition/state-management)
- 📄 Article: [Overview of State in React](https://www.robinwieruch.de/react-state/)

**✅ Checklist:**

- [ ] Context — ☆☆☆☆☆
  - 🏛️ Official: [Passing Data Deeply with Context](https://react.dev/learn/passing-data-deeply-with-context)
  - 📄 Article: [State with useContext and useState/useReducer](https://www.robinwieruch.de/react-state-usereducer-usestate-usecontext/)
  - 🎥 Video: [React Context API Crash Course](https://www.youtube.com/watch?v=t9WmZFnE6Hg)
- [ ] Zustand — ☆☆☆☆☆
  - 🏛️ Official: [Zustand - Official Website](https://zustand-demo.pmnd.rs/)
  - 💻 Open source: [Zustand Repository](https://github.com/pmndrs/zustand)
  - 📄 Article: [Working with Zustand](https://tkdodo.eu/blog/working-with-zustand)
  - 🎥 Video: [Zustand Tutorial for Beginners](https://www.youtube.com/watch?v=AYO4qHAnLQI&t)
- [ ] Jotai — ☆☆☆☆☆
  - 🏛️ Official: [Official Website: Jotai](https://jotai.org/)
  - 📄 Article: [State Management on React - Jotai](https://dev.to/kevin-uehara/state-management-on-react-part-3-jotai-i7f)
  - 🎥 Video: [Jotai React - Better Global State Management](https://www.youtube.com/watch?v=ZcKzPZN7Ids)
- [ ] MobX — ☆☆☆☆☆
  - 🏛️ Official: [Official Website: MobX](https://mobx.js.org/)
  - 📄 Article: [How to Improve State Management in React with MobX](https://medium.com/whitespectre/how-to-improve-state-management-in-react-with-mobx-568808ff86a4)
  - 🎥 Video: [Mobx React - State Management](https://www.youtube.com/watch?v=AgcaGGkYy_8)
  - 🎥 Video: [MobX Tutorial with React and Typescript](https://www.youtube.com/watch?v=ElgfQdq-Htk)

### 🧠 Quiz

1. When is Context a good fit, and when is it not?
   <details><summary>Answer</summary>Good for rarely changing global values (theme, user); not ideal for frequently changing state, since all consumers re-render.</details>

2. What is prop drilling?
   <details><summary>Answer</summary>Passing props through many layers of components that don't need them.</details>

3. How does Zustand differ from Redux?
   <details><summary>Answer</summary>It's a tiny hook-based store with little boilerplate and no providers or reducers required.</details>

---

## 7. Writing CSS — ☆☆☆☆☆

> While "CSS in JS" is the most predominant way of styling modern frontend applications, there are several different ways to style your React applications whether it is vanilla CSS, [CSS Modules](https://github.com/css-modules/css-modules), or [CSS in JS](https://css-tricks.com/a-thorough-analysis-of-css-in-js/) etc and each has several frameworks available.

**📚 Learn:**

- 🗺️ Roadmap: [Visit the Dedicated CSS Roadmap](https://roadmap.sh/css)
- 📄 Article: [Ways to CSS style a React application](https://www.robinwieruch.de/react-css-styling/)

**✅ Checklist:**

- [ ] Tailwind CSS — ☆☆☆☆☆
  - 🏛️ Official: [Tailwind Website](https://tailwindcss.com)
  - 🎥 Video: [Tailwind CSS Full Course for Beginners](https://www.youtube.com/watch?v=lCxcTsOHrjo)
  - 🎥 Video: [Tailwind CSS Crash Course](https://www.youtube.com/watch?v=UBOj6rqRUME)
  - 🎥 Video: [Should You Use Tailwind CSS?](https://www.youtube.com/watch?v=hdGsFpZ0J2E)
- [ ] CSS Modules — ☆☆☆☆☆
  - 💻 Open source: [Project GitHub Repository](https://github.com/css-modules/css-modules)
  - 📄 Article: [Using CSS Modules In React App](https://medium.com/@ralph1786/using-css-modules-in-react-app-c2079eadbb87)
  - 🎥 Video: [CSS Modules: Why are they great?](https://www.youtube.com/watch?v=pKMWU9OrA2s)
- [ ] Panda CSS — ☆☆☆☆☆
  - 🏛️ Official: [Official Website](https://panda-css.com)
  - 🏛️ Official: [Tutorials and videos to get started with Panda!](https://panda-css.com/learn)
  - 📄 Article: [Panda CSS – CSS-in-JS without Runtime Overhead](https://infinum.com/blog/panda-css-css-in-js-without-runtime-overhead/)
  - 🎥 Video: [Panda CSS First Impressions | Theo Reacts](https://www.youtube.com/watch?v=UlY-Ixddjm0)

### 🧠 Quiz

1. How do CSS Modules avoid class name conflicts?
   <details><summary>Answer</summary>Class names are scoped locally by generating unique names at build time.</details>

2. What is the main idea of Tailwind CSS?
   <details><summary>Answer</summary>Utility-first classes composed directly in JSX.</details>

3. How do you apply a style dynamically in React?
   <details><summary>Answer</summary>Conditionally build className strings (e.g. with clsx) or use the style prop.</details>

---

## 8. Component / Libraries — ☆☆☆☆☆

> React component libraries are collections of pre-built, reusable components that can be used to speed up the development process. They can be styled using CSS in various ways, including traditional CSS files, CSS modules, and CSS-in-JS solutions like styled-components.

**📚 Learn:**

- 📄 Article: [MUI: React Component Library](https://mui.com/)
- 📄 Article: [NextUI.org](https://nextui.org/)

**✅ Checklist:**

- [ ] Shadcn UI — ☆☆☆☆☆
  - 🏛️ Official: [Official Website](https://ui.shadcn.com/)
  - 🏛️ Official: [Documentation](https://ui.shadcn.com/docs)
  - 📄 Article: [Shadcn Guide](https://blog.logrocket.com/shadcn-ui-adoption-guide/)
  - 🎥 Video: [Shadcn Setup and Tutorial](https://www.youtube.com/watch?v=v0_AT8zaLo8)
- [ ] Material UI — ☆☆☆☆☆
  - 🏛️ Official: [Material UI website](https://mui.com/material-ui/getting-started/)
  - 🎥 Video: [React Material UI Course](https://www.youtube.com/watch?v=BHEPVdfBAqE&list=PLC3y8-rFHvwh-K9mDlrrcDywl7CeVL2rO)
  - 🎥 Video: [Material UI with React](https://www.youtube.com/watch?v=5cvg2qZwYrI)
- [ ] Chakra UI — ☆☆☆☆☆
  - 📄 Article: [Chakra UI Website](https://chakra-ui.com/)
  - 📄 Article: [Chakra UI Official Getting Started](https://chakra-ui.com/docs)
  - 🎥 Video: [Official Getting Started Video](https://youtu.be/wI2vqXsjsIo)
  - 🎥 Video: [Chakra UI Crash Course](https://youtu.be/s-bIsz-NR3c)

### 🧠 Quiz

1. What makes shadcn/ui different from Material UI?
   <details><summary>Answer</summary>shadcn/ui copies component source code into your project for you to own and customize; MUI is an installed npm library.</details>

2. Why use a component library?
   <details><summary>Answer</summary>To save time with accessible, tested, consistent components.</details>

3. What is a downside of a heavy component library?
   <details><summary>Answer</summary>Bundle size, harder deep customization, and a fixed look you must override.</details>

---

## 9. Headless Components — ☆☆☆☆☆

> Headless component libraries have some powerful state, logic and data management tools that do not enforce any UI structure. Consequently, developers are able to build custom UI components with unique styles but that still benefit from strong reusable logics. This kind of library simplifies complex behaviors and accessibility issues in outdoor environments allowing you to create innovative interfaces. With headless components, developers keep code clean and maintainable as a result of the reusability aspect inherent in these, this also guarantees efficient and accessible components enhancing application quality.

**📚 Learn:**

- 📄 Article: [What are headless components?](https://dev.to/verthon/headless-ui-libraries-the-key-to-flexible-and-accessible-user-interfaces-546p)
- 📄 Article: [Headless Components: A Comprehensive Guide](https://blog.logrocket.com/the-complete-guide-to-building-headless-interface-components-in-react/)
- 🎥 Video: [Rise of Headless Components](https://www.youtube.com/watch?v=_WtVG_pKsxM)

**✅ Checklist:**

- [ ] Radix UI — ☆☆☆☆☆
  - 🏛️ Official: [Getting Started with Radix UI](https://www.radix-ui.com/themes/docs/overview/getting-started)
  - 🏛️ Official: [Official Website](https://www.radix-ui.com/)
  - 📄 Article: [What is Radix UI?](https://medium.com/@olivier.trinh/what-is-radix-ui-ff535bbb52d5)
  - 🎥 Video: [Radix UI Course](https://www.youtube.com/playlist?list=PLlNdnoKwDZdwANQoaakE8-kYMyKFOETlo)
- [ ] React Aria — ☆☆☆☆☆
  - 🏛️ Official: [Getting Started with React Aria](https://react-spectrum.adobe.com/react-aria/)
  - 🎥 Video: [Why You Should Use React Aria Components](https://www.youtube.com/watch?v=lTPh6NGLAmk)
- [ ] Ark UI — ☆☆☆☆☆
  - 🏛️ Official: [Official Website](https://ark-ui.com/)
  - 🏛️ Official: [Official Website](https://ark-ui.com/react/docs/overview/introduction)
  - 📄 Article: [What is ARK UI?](https://shaxadd.medium.com/enhance-your-user-interfaces-with-ark-ui-a-comprehensive-guide-7e87dd0a79cf)
  - 🎥 Video: [Hands On ARK UI](https://www.youtube.com/watch?v=zjo-77I0unk)
- [ ] Base UI — ☆☆☆☆☆

### 🧠 Quiz

1. What is a headless component?
   <details><summary>Answer</summary>A component that provides behavior and accessibility but no styles, so you style it yourself.</details>

2. Name two headless UI libraries.
   <details><summary>Answer</summary>Radix UI, React Aria, Ark UI or Base UI.</details>

3. Why is building an accessible dropdown from scratch hard?
   <details><summary>Answer</summary>It needs correct keyboard navigation, focus management and ARIA roles/states.</details>

---

## 10. API Calls — ☆☆☆☆☆

> APIs, short for Application Programming Interfaces, are software-to-software interfaces. Meaning, they allow different applications to talk to each other and exchange information or functionality. This allows businesses to access another business’s data, piece of code, software, or services in order to extend the functionality of their own products — all while saving time and money. There are several options available to make API calls from your React.js applications.

**📚 Learn:**

- 📄 Article: [AJAX and APIs](https://reactjs.org/docs/faq-ajax.html)
- 📄 Article: [How to fetch data in React](https://www.robinwieruch.de/react-hooks-fetch-data/)

**✅ Checklist:**

- [ ] REST — ☆☆☆☆☆
  - [ ] Tanstack Query — ☆☆☆☆☆
    - 🏛️ Official: [TanStack Query](https://tanstack.com/query/latest)
    - 💻 Open source: [TanStack Query](https://github.com/TanStack/query)
    - 📄 Article: [TanStack for Beginners: A Complete Guide & Tutorial](https://codeparrot.ai/blogs/tanstack-for-beginners-a-complete-guide-tutorial)
    - 🎥 Video: [TanStack Query - How to become a React Query God](https://www.youtube.com/watch?v=mPaCnwpFvZY)
  - [ ] swr — ☆☆☆☆☆
    - 📄 Article: [SWR: React Hooks for Data Fetching](https://swr.vercel.app/)
  - [ ] rtk-query — ☆☆☆☆☆
    - 📄 Article: [RTK Query - Official Website](https://redux-toolkit.js.org/rtk-query/overview)
  - [ ] Axios — ☆☆☆☆☆
    - 📄 Article: [Axios Getting Started](https://axios-http.com/docs/intro)
    - 📄 Article: [How to make HTTP requests with Axios](https://blog.logrocket.com/how-to-make-http-requests-like-a-pro-with-axios/#why)
- [ ] GraphQL — ☆☆☆☆☆
  - [ ] Apollo — ☆☆☆☆☆
    - 📄 Article: [Apollo Website](https://www.apollographql.com)
    - 📄 Article: [Official Docs](https://www.apollographql.com/docs/)
    - 🎥 Video: [Official YouTube Channel](https://www.youtube.com/c/ApolloGraphQL/)
    - 🎥 Video: [GraphQL With React Tutorial - Apollo Client](https://www.youtube.com/watch?v=YyUWW04HwKY)
  - [ ] Relay — ☆☆☆☆☆
    - 🏛️ Official: [Official Website](https://relay.dev/)
    - 🏛️ Official: [Introduction to Relay modern](https://relay.dev/docs/)
  - [ ] urql — ☆☆☆☆☆
    - 📄 Article: [urql - Formidable Labs](https://formidable.com/open-source/urql/)

### 🧠 Quiz

1. What does TanStack Query (or SWR) give you over fetch in useEffect?
   <details><summary>Answer</summary>Caching, deduplication, background refetching, retries and loading/error states.</details>

2. What is a race condition when fetching in useEffect?
   <details><summary>Answer</summary>An older request finishing after a newer one and overwriting its data; fix with cleanup/AbortController or a data library.</details>

3. Name a GraphQL client for React.
   <details><summary>Answer</summary>Apollo Client, Relay or urql.</details>

---

## 11. Testing — ☆☆☆☆☆

> A key to building software that meets requirements without defects is testing. Software testing helps developers know they are building the right software. When tests are run as part of the development process (often with continuous integration tools), they build confidence and prevent regressions in the code.

**📚 Learn:**

- 📄 Article: [What is Software Testing?](https://www.guru99.com/software-testing-introduction-importance.html)
- 📄 Article: [Testing Pyramid](https://www.browserstack.com/guide/testing-pyramid-for-test-automation)

**✅ Checklist:**

- [ ] Vitest — ☆☆☆☆☆
  - 🏛️ Official: [Vitest Website](https://vitest.dev/)
  - 🎥 Video: [Testing with Vitest](https://www.youtube.com/watch?v=cM_AeQHzlGg)
- [ ] Jest — ☆☆☆☆☆
  - 🏛️ Official: [Jest Website](https://jestjs.io/)
  - 📄 Article: [Testing JavaScript with Jest on Vultr](https://developer.mozilla.org/en-US/blog/test-javascript-with-jest-on-vultr/)
- [ ] react-testing-library — ☆☆☆☆☆
  - 📄 Article: [React Testing Library](https://testing-library.com/docs/react-testing-library/intro/)
  - 📄 Article: [How to use React Testing Library](https://www.robinwieruch.de/react-testing-library/)
- [ ] Playwright — ☆☆☆☆☆
  - 🏛️ Official: [Official Website: Playwright](https://playwright.dev/)
  - 📄 Article: [Playwright Tutorial: Learn Basics and Setup](https://www.browserstack.com/guide/playwright-tutorial)
  - 🎥 Video: [Get started with end-to-end testing: Playwright](https://www.youtube.com/playlist?list=PLQ6Buerc008ed-F9OksF7ek37wR3y916p)
- [ ] Cypress — ☆☆☆☆☆
  - 🏛️ Official: [Official Website](https://www.cypress.io/)
  - 📄 Article: [Official Documentation](https://docs.cypress.io/guides/overview/why-cypress#Other)
  - 🎥 Video: [Cypress End-to-End Testing](https://www.youtube.com/watch?v=7N63cMKosIE)

### 🧠 Quiz

1. What is the philosophy of React Testing Library?
   <details><summary>Answer</summary>Test components the way users use them — query by role/text, not implementation details.</details>

2. Which query should you prefer in Testing Library?
   <details><summary>Answer</summary>getByRole (accessible queries) whenever possible.</details>

3. When would you use Playwright or Cypress instead?
   <details><summary>Answer</summary>For end-to-end tests of the whole app in a real browser.</details>

---

## 12. Forms — ☆☆☆☆☆

> Forms in React need extra handling compared to plain HTML, since input values are usually tied to component state to keep the UI in sync with user input. This includes tracking values, validating input, and showing error messages. Libraries exist to simplify this instead of writing all the state and validation logic by hand.

**📚 Learn:**

- 📄 Article: [How to use Forms in React](https://www.robinwieruch.de/react-form/)
- 🎥 Video: [React Forms: the SIMPLEST way](https://www.youtube.com/watch?v=CT-72lTXdPg)

**✅ Checklist:**

- [ ] React Hook Form — ☆☆☆☆☆
  - 💻 Open source: [react-hook-form/react-hook-form](https://github.com/react-hook-form/react-hook-form)
  - 📄 Article: [React Hook Form: Official Website](https://react-hook-form.com/)
- [ ] Formik — ☆☆☆☆☆
  - 🏛️ Official: [Official Website — Formik](https://formik.org/)
  - 💻 Open source: [formik/formik](https://github.com/formik/formik)
  - 🎥 Video: [Formik - Building React Forms easier](https://www.youtube.com/watch?v=khGypss-RJs)
  - 🎥 Video: [React Formik Tutorial with Yup (React Form Validation)](https://www.youtube.com/watch?v=7Ophfq0lEAY)
- [ ] Formish — ☆☆☆☆☆
  - 🏛️ Official: [Formisch](https://formisch.dev/)
  - 💻 Open source: [formisch](https://github.com/open-circle/formisch)

### 🧠 Quiz

1. What is the difference between controlled and uncontrolled inputs?
   <details><summary>Answer</summary>Controlled inputs get their value from React state; uncontrolled inputs keep their own DOM state, read via refs.</details>

2. Why use React Hook Form?
   <details><summary>Answer</summary>Less boilerplate, fewer re-renders (uncontrolled by default) and easy validation, e.g. with Zod.</details>

3. How do you prevent a form submission from reloading the page?
   <details><summary>Answer</summary>Call event.preventDefault() in the onSubmit handler.</details>

---

## 13. Frameworks — ☆☆☆☆☆

> A framework built on top of React adds extra structure and features, such as routing, server-side rendering, or file-based page organization, that React itself does not provide. Choosing a framework can save time on setup and give a project a more opinionated, consistent structure from the start.

**📚 Learn:**

- 📄 Article: [Next.js](https://nextjs.org/)
- 📄 Article: [Remix](https://remix.run/)
- 🎥 Video: [Next.js 14 Full Course 2024](https://www.youtube.com/watch?v=wm5gMKuwSYk)
- 🎥 Video: [Remix Crash Course](https://www.youtube.com/watch?v=RBYJTop1e-g)

**✅ Checklist:**

- [ ] Next.js — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated Next.js Roadmap](https://roadmap.sh/nextjs)
  - 🏛️ Official: [Official Docs for Getting Started](https://nextjs.org/docs/getting-started)
  - 📄 Article: [Mastering Next.js](https://masteringnextjs.com/)
  - 🎥 Video: [Next.js Full course](https://www.youtube.com/watch?v=9P8mASSREYM&list=PLC3y8-rFHvwgC9mj0qv972IO5DmD-H0ZH)
- [ ] react-router — ☆☆☆☆☆
  - 🏛️ Official: [Official Website](https://reactrouter.com/)
  - 💻 Open source: [remix-run react-router](https://github.com/remix-run/react-router)
- [ ] Astro — ☆☆☆☆☆
  - 🏛️ Official: [Astro Website](https://astro.build/)
  - 🎥 Video: [Astro Crash Course in 60 Minutes](https://www.youtube.com/watch?v=NniT0vKyn-E)
  - 🎥 Video: [How To: Add/Integrate React.js and TailwindCss into Astro framework](https://www.youtube.com/watch?v=d6CsWTVa42o)

### 🧠 Quiz

1. What does a framework like Next.js add to React?
   <details><summary>Answer</summary>Routing, server rendering, data fetching, bundling and deployment conventions.</details>

2. What is a React Server Component?
   <details><summary>Answer</summary>A component that runs only on the server, can access data directly, and sends no JS to the client.</details>

3. When is Astro a good choice?
   <details><summary>Answer</summary>Content-heavy sites where most pages are static and only some parts need interactivity.</details>

---

## 14. Types & Validation — ☆☆☆☆☆

> Types and validation in a React app help catch mistakes early and make sure data matches the expected shape, whether it comes from user input, an API, or props. Static typing checks this at compile time, while validation libraries check it at runtime, and the two are often used together.

**📚 Learn:**

- 📄 Article: [What is TypeScript and why would I use it in place of JavaScript?](https://stackoverflow.com/questions/12694530/what-is-typescript-and-why-would-i-use-it-in-place-of-javascript)
- 📄 Article: [When Use Zod](https://www.totaltypescript.com/when-should-you-use-zod)

**✅ Checklist:**

- [ ] TypeScript — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated TypeScript Roadmap](https://roadmap.sh/typescript)
  - 🏛️ Official: [Official Website](https://www.typescriptlang.org/)
  - 📄 Article: [The TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
  - 🎥 Video: [TypeScript for Beginners](https://www.youtube.com/watch?v=BwuLxPH8IDs)
- [ ] Zod — ☆☆☆☆☆
  - 🏛️ Official: [Zod Website](https://zod.dev/)
  - 🎥 Video: [Learn Zod In 30 Minutes](https://www.youtube.com/watch?v=L6BE-U3oy80)
- [ ] Valibot — ☆☆☆☆☆
  - 🏛️ Official: [Valibot - Alternative to Zod](https://valibot.dev/)
  - 💻 Open source: [valibot](https://github.com/open-circle/valibot)

### 🧠 Quiz

1. How do you type a component's props in TypeScript?
   <details><summary>Answer</summary>type Props = { title: string }; function Card({ title }: Props) { ... }.</details>

2. Why validate API responses at runtime with Zod even if you use TypeScript?
   <details><summary>Answer</summary>TypeScript types don't exist at runtime; external data can be anything.</details>

3. How do you get a TypeScript type from a Zod schema?
   <details><summary>Answer</summary>type User = z.infer&lt;typeof UserSchema&gt;.</details>

---

## 15. Animation — ☆☆☆☆☆

> React Animation allows you to change the visual state of elements over time, such as fading, sliding, or scaling them in response to user interaction or state changes. React does not include animation tools by default, so most projects rely on dedicated libraries to handle timing, easing, and transitions smoothly.

**📚 Learn:**

- 📄 Article: [Framer Motion Docs](https://www.framer.com/motion/)
- 📄 Article: [GSAP Docs](https://gsap.com/docs/v3/)
- 📄 Article: [React Spring Docs](https://www.react-spring.dev/docs/getting-started)

**✅ Checklist:**

- [ ] Framer Motion — ☆☆☆☆☆
  - 🏛️ Official: [Framer Motion Website](https://www.framer.com/motion/introduction/)
  - 🎥 Video: [Framer Motion Crash Course with React & TS](https://www.youtube.com/watch?v=hjbxaYTMhy0&list=PLA4qBVt61k3Phpwt7uqaptIg9NYZ5aNu_)
- [ ] react spring — ☆☆☆☆☆
  - 🏛️ Official: [React Spring — Official Website](https://www.react-spring.dev/)
  - 📄 Article: [How to Create Interactive Animations Using React Spring](https://www.sitepoint.com/react-spring-interactive-animations/)
  - 🎥 Video: [React Spring Crash Course](https://www.youtube.com/watch?v=f2vdduklY20&list=PLLnpHn493BHGrM7tAQL8qVtqwqzbuuE5_)
- [ ] GSock — ☆☆☆☆☆
  - 🏛️ Official: [GSAP: Homepage](https://gsap.com/docs/v3/)
  - 📄 Article: [The Beginner's Guide to the GreenSock Animation Platform](https://www.freecodecamp.org/news/the-beginners-guide-to-the-greensock-animation-platform-7dc9fd9eb826/)
  - 🎥 Video: [Intro to Greensock Web Animation](https://www.youtube.com/watch?v=EOa7ccPWvXg)

### 🧠 Quiz

1. How do you animate a component when it leaves the DOM with Framer Motion (Motion)?
   <details><summary>Answer</summary>Wrap it in AnimatePresence and give it an exit prop.</details>

2. What makes react-spring's animations feel natural?
   <details><summary>Answer</summary>They are physics-based (springs) instead of fixed durations.</details>

3. Which CSS properties are cheapest to animate?
   <details><summary>Answer</summary>transform and opacity.</details>

---

## 16. Error Boundaries — ☆☆☆☆☆

> An error boundary is a component that catches JavaScript errors thrown by its child components during rendering, preventing the whole app from crashing. Instead of showing a broken UI, it can display a fallback message. Error boundaries only catch errors in the component tree below them, not in event handlers or asynchronous code.

**📚 Learn:**

- 🏛️ Official: [Error Boundaries in React](https://react.dev/reference/react/Component#catching-rendering-errors-with-an-error-boundary)

**✅ Checklist:**

- [ ] Error Boundaries — ☆☆☆☆☆

### 🧠 Quiz

1. What is an error boundary?
   <details><summary>Answer</summary>A component that catches render errors in its children and shows a fallback UI.</details>

2. Which errors are NOT caught by error boundaries?
   <details><summary>Answer</summary>Errors in event handlers, async code, and server-side rendering.</details>

3. Can you write an error boundary as a function component?
   <details><summary>Answer</summary>Not natively — it needs a class (componentDidCatch/getDerivedStateFromError) or a library like react-error-boundary.</details>

---

## 17. Server APIs — ☆☆☆☆☆

> The react-dom/server APIs let you render React components to HTML on the server. These APIs are only used on the server at the top level of your app to generate the initial HTML. A [framework](https://react.dev/learn/start-a-new-react-project#production-grade-react-frameworks) may call them for you. Most of your components don’t need to import or use them.

**📚 Learn:**

- 🏛️ Official: [Documentation For API](https://react.dev/reference/react-dom/server)

**✅ Checklist:**

- [ ] Server APIs — ☆☆☆☆☆

### 🧠 Quiz

1. What does renderToString / renderToPipeableStream do?
   <details><summary>Answer</summary>Renders React components to HTML on the server (the latter streams it).</details>

2. What is hydration?
   <details><summary>Answer</summary>Attaching React to server-rendered HTML so it becomes interactive (hydrateRoot).</details>

3. What causes a hydration mismatch?
   <details><summary>Answer</summary>Server and client rendering different output, e.g. using Date.now() or window during render.</details>

---

## 18. Suspense — ☆☆☆☆☆

> Suspense is a React feature that lets a component "wait" for something, such as data or code, before rendering, showing a fallback UI in the meantime. It was originally built for code splitting with lazy loading, and has since been extended to support data fetching in some frameworks and libraries.

**📚 Learn:**

- 🏛️ Official: [React Suspense](https://react.dev/reference/react/Suspense)
- 📄 Article: [React Suspense - A complete guide](https://hygraph.com/blog/react-suspense)

**✅ Checklist:**

- [ ] Suspense — ☆☆☆☆☆

### 🧠 Quiz

1. What does &lt;Suspense&gt; do?
   <details><summary>Answer</summary>Shows a fallback while its children are waiting (lazy-loaded code or data).</details>

2. How do you lazy-load a component?
   <details><summary>Answer</summary>const Page = lazy(() =&gt; import('./Page')) and render it inside &lt;Suspense&gt;.</details>

3. How does Suspense help with streaming SSR?
   <details><summary>Answer</summary>The server can send the page shell first and stream suspended parts when they are ready.</details>

---

## 19. Portals — ☆☆☆☆☆

> A portal lets you render a component's children into a different part of the DOM, outside its parent's normal hierarchy. This is useful for things like modals or tooltips that need to visually sit above other content, even though logically they still belong to their original component in React's tree.

**📚 Learn:**

- 🏛️ Official: [Portals in React](https://react.dev/reference/react-dom/createPortal)
- 🎥 Video: [React Portals](https://www.youtube.com/watch?v=HpHLa-5Wdys)

**✅ Checklist:**

- [ ] Portals — ☆☆☆☆☆

### 🧠 Quiz

1. What is a portal?
   <details><summary>Answer</summary>createPortal renders children into a different DOM node (e.g. document.body) while keeping them in the React tree.</details>

2. Give a typical use case for portals.
   <details><summary>Answer</summary>Modals, tooltips and dropdowns that must escape overflow:hidden or z-index stacking.</details>

3. Do events from a portal bubble to React parents?
   <details><summary>Answer</summary>Yes, they bubble through the React tree, not the DOM tree.</details>

---

## 20. Mobile Applications — ☆☆☆☆☆

> React can be extended beyond the web to build mobile applications, reusing similar concepts like components, props, and state. This lets developers apply React knowledge to build apps that run on iOS and Android, instead of learning a completely separate native development stack.

**📚 Learn:**

- 📄 Article: [React Native Official website](https://reactnative.dev/)
- 🎥 Video: [React Native Course for Beginners](https://www.youtube.com/watch?v=ZBCUegTZF7M)

**✅ Checklist:**

- [ ] React Native — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated React Native Roadmap](https://roadmap.sh/react-native)
  - 🏛️ Official: [React Native: Official Website](https://reactnative.dev/)
  - 🏛️ Official: [Official Getting Started](https://reactnative.dev/docs/getting-started)

### 🧠 Quiz

1. What does React Native render?
   <details><summary>Answer</summary>Real native UI components, not HTML.</details>

2. What is Expo?
   <details><summary>Answer</summary>A framework and toolset on top of React Native that simplifies building, running and deploying apps.</details>

3. What replaces &lt;div&gt; and &lt;span&gt; in React Native?
   <details><summary>Answer</summary>&lt;View&gt; and &lt;Text&gt;.</details>
