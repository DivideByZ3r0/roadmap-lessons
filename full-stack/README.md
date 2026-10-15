# Full Stack Developer Roadmap — Lessons

**How to use:** tick `[x]` when done, and rate yourself by replacing ☆ with ★ (★☆☆☆☆ = just heard of it · ★★★★★ = can teach it). Quiz answers are hidden — click *Answer* to reveal.

Source: https://roadmap.sh/full-stack (lesson order follows the roadmap)

---

## 1. HTML — ☆☆☆☆☆

> HTML stands for HyperText Markup Language. It is used on the frontend and gives the structure to the webpage which you can style using CSS and make interactive using JavaScript.

**📚 Learn:**

- 🗺️ Roadmap: [Visit the Dedicated HTML Roadmap](https://roadmap.sh/html)
- 🎥 Video: [HTML Full Course for Beginners](https://youtu.be/mJgBOIoGihA)
- 🎥 Video: [HTML Full Course - Build a Website Tutorial](https://www.youtube.com/watch?v=pQN-pnXPaVg)

**✅ Checklist:**

- [ ] HTML — ☆☆☆☆☆

### 🧠 Quiz

1. Why use semantic HTML elements?
   <details><summary>Answer</summary>They convey meaning, improving accessibility, SEO and readability.</details>

2. What is the purpose of the &lt;form&gt; element's action and method attributes?
   <details><summary>Answer</summary>action is the URL the data is sent to; method is the HTTP method (GET or POST).</details>

3. What does the viewport meta tag do?
   <details><summary>Answer</summary>It tells mobile browsers to use the device width and initial zoom, enabling responsive layouts.</details>

---

## 2. CSS — ☆☆☆☆☆

> CSS or Cascading Style Sheets is the language used to style the frontend of any website. CSS is a cornerstone technology of the World Wide Web, alongside HTML and JavaScript.

**📚 Learn:**

- 🗺️ Roadmap: [Visit the Dedicated CSS Roadmap](https://roadmap.sh/css)
- 📄 Article: [Web.dev by Google — Learn CSS](https://web.dev/learn/css/)
- 🎥 Video: [CSS Complete Course](https://youtu.be/n4R2E7O-Ngo)
- 🎥 Video: [HTML and CSS Tutorial](https://www.youtube.com/watch?v=D-h8L5hgW-w)

**✅ Checklist:**

- [ ] Checkpoint - Static Webpages — ☆☆☆☆☆
  - 🛠️ **Checkpoint brief:**
    - Now that you have learnt HTML and CSS, you should be able to build static webpages. I recommend you to build as many test projects at each yellow step of the roadmap as possible to solidify what you learn.
    - The practice that I used to follow when I was learning was this:
      - While you are watching a course or reading a book, make sure to code along with the instructor/author — pause the video at regular intervals and code what you are being taught.
      - Search on YouTube and watch a few project based tutorials on the topic that you are learning. Apart from coding along with the instructor:
        - Try to build the same project at least 2 to 3 times on your own without looking at the video. If you get stuck, refer to the section of the video where the instructor builds that part of the project.
        - Build something else that is similar to the project that you just built. For example, if you just built a todo app, try to build a notes app or a reminder app.
    - Project Ideas
    - Now that you have learnt HTML and CSS, here are a few ideas for you to build:
      - Try to copy the design of a website that you like.
        - Here is a [simple blog design in figma](https://www.figma.com/file/nh0V05z3NB87ue9v5PcO3R/writings.dev?type=design&node-id=0%3A1&t=2iQplaIojU3ydAfW-1) that you can try to copy.
        - Or try to rebuild the [webpages of this website](https://cs.fyi/).
      - Take some inspiration from [personal portfolios of others](https://astro.build/showcase/) and build your own personal portfolio

### 🧠 Quiz

1. What is the box model?
   <details><summary>Answer</summary>Content + padding + border + margin around every element.</details>

2. What are media queries used for?
   <details><summary>Answer</summary>Applying styles based on screen size or device features, for responsive design.</details>

3. Flexbox or Grid for a page layout with rows and columns?
   <details><summary>Answer</summary>Grid (two-dimensional); Flexbox is best for one-dimensional rows or columns.</details>

---

## 3. JavaScript — ☆☆☆☆☆

> JavaScript allows you to add interactivity to your pages. Common examples that you may have seen on the websites are sliders, click interactions, popups and so on.

**📚 Learn:**

- 🗺️ Roadmap: [Visit Dedicated JavaScript Roadmap](https://roadmap.sh/javascript)
- 📄 Article: [The Modern JavaScript Tutorial](https://javascript.info/)
- 📄 Article: [Build 30 Javascript projects in 30 days](https://javascript30.com/)
- 🎥 Video: [JavaScript Crash Course for Beginners](https://youtu.be/hdI2bqOjy3c?t=2)

**✅ Checklist:**

- [ ] Checkpoint - Interactivity — ☆☆☆☆☆
  - 🛠️ **Checkpoint brief:**
    - At this point you should be able to add interactivity to your web pages using JavaScript. You should make sure that you have learnt the following:
      - Know about variables, loops, data types, conditionals, functions.
      - Know about arrays and objects and different ways to access their data.
      - Know how to select DOM elements.
      - Add event listeners to DOM elements (e.g. click, focus, form submission).
      - Use JavaScript to add and remove DOM elements
      - Add and remove classes from DOM elements
      - Use JavaScript to make HTTP requests to external APIs (i.e. `fetch`)
      - Use JavaScript to store data in the browser's local storage
    - Here are few ideas to practice your skills:
      - Create a simple to-do list app that allows users to search, add, edit, and delete items. Use local storage to store the data.
      - Create a simple webpage where user can put in anyone's GitHub username and see their profile information. You can use GitHub's API to fetch the data. For example, here is the [sample URL to fetch my data](https://api.github.com/users/nilbuild). Make sure to add validation and error handling.
      - Create a basic calculator app that allows users to perform basic arithmetic operations.

### 🧠 Quiz

1. How do you add a click handler to a button?
   <details><summary>Answer</summary>button.addEventListener('click', handler).</details>

2. What is the difference between == and ===?
   <details><summary>Answer</summary>== compares after type coercion; === compares value and type without coercion.</details>

3. What does async/await do?
   <details><summary>Answer</summary>Lets you write Promise-based asynchronous code that reads like synchronous code.</details>

---

## 4. npm — ☆☆☆☆☆

> npm is a package manager for the JavaScript programming language maintained by npm, Inc. npm is the default package manager for the JavaScript runtime environment Node.js.

**📚 Learn:**

- 💻 Open source: [How to NPM](https://github.com/workshopper/how-to-npm)
- 📄 Article: [Modern JavaScript for Dinosaurs](https://peterxjang.com/blog/modern-javascript-explained-for-dinosaurs.html)
- 📄 Article: [An Absolute Beginners Guide to Using npm](https://nodesource.com/blog/an-absolute-beginners-guide-to-using-npm/)
- 🎥 Video: [NPM Crash Course](https://www.youtube.com/watch?v=jHDhaSSKmB0)

**✅ Checklist:**

- [ ] Checkpoint - External Packages — ☆☆☆☆☆
  - 🛠️ **Checkpoint brief:**
    - At this point, you should be able to install and use external packages using `npm`. You probably know about [npmjs.com](https://npmjs.com/) where you can search for packages and read their documentation. You should also be familiar with the `package.json` file and how to use it to manage your project dependencies.
    - You don't need to get into the module bundlers and build tools just yet. Just make sure that you are able to use the dependencies installed in the `node_modules` folder using simple link and script tags in your HTML.
    - Regarding projects, here are a few ideas that you can try:
      - Create a simple webpage that shows the current time of user. You can use [dayjs](https://day.js.org/) to get the current time and display it on the page. Here is the [sample design for homepage](https://i.imgur.com/yGIMGkr.png).
      - Install the [micromodal](https://micromodal.vercel.app/#introduction) library. Create a button on the page clicking which should open a modal and let the user select a timezone from a dropdown. Once the user selects a timezone, the modal should close and the time on the page should be updated to show the time in the selected timezone. Here is the [sample design for the modal](https://imgur.com/a/vFY6Sdl).

### 🧠 Quiz

1. What is package.json for?
   <details><summary>Answer</summary>It describes the project, its scripts and its dependencies.</details>

2. What is the difference between npm install and npm ci?
   <details><summary>Answer</summary>npm install can update the lockfile; npm ci does a clean, exact install from the lockfile (ideal for CI).</details>

3. How do you run a script named 'dev' from package.json?
   <details><summary>Answer</summary>npm run dev.</details>

---

## 5. Git — ☆☆☆☆☆

> Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.

**📚 Learn:**

- 🗺️ Roadmap: [Visit Dedicated Git & GitHub Roadmap](https://roadmap.sh/git-github)
- 🎓 Course: [Why use Git? (Interactive Lesson)](https://inter-git.com/lessons/introduction)
- 📄 Article: [Tutorial: Git for Absolutely Everyone](https://thenewstack.io/tutorial-git-for-absolutely-everyone/)
- 🎥 Video: [Git & GitHub Crash Course For Beginners](https://www.youtube.com/watch?v=SWYqp7iY_Tc)

**✅ Checklist:**

- [ ] Git — ☆☆☆☆☆

### 🧠 Quiz

1. What is the basic Git workflow?
   <details><summary>Answer</summary>Edit files, git add to stage, git commit to save a snapshot, git push to share.</details>

2. How do you create and switch to a new branch?
   <details><summary>Answer</summary>git switch -c my-branch (or git checkout -b my-branch).</details>

3. What does .gitignore do?
   <details><summary>Answer</summary>Lists files and folders Git should not track, such as node_modules or .env.</details>

---

## 6. GitHub — ☆☆☆☆☆

> GitHub is a provider of Internet hosting for software development and version control using Git. It offers the distributed version control and source code management functionality of Git, plus its own features.

**📚 Learn:**

- 🏛️ Official: [GitHub Documentation](https://docs.github.com/en/get-started/quickstart)
- 📄 Article: [How to Use Git in a Professional Dev Team](https://ooloo.io/project/github-flow)
- 🎥 Video: [Git vs. GitHub: What's the difference?](https://www.youtube.com/watch?v=wpISo9TNjfU)
- 🎥 Video: [Git and GitHub for Beginners](https://www.youtube.com/watch?v=RGOj5yH7evk)

**✅ Checklist:**

- [ ] Checkpoint - Collaborative Work — ☆☆☆☆☆
  - 🛠️ **Checkpoint brief:**
    - Now that you have learnt git and GitHub you should be ready to work with others. You should now setup your GitHub profile and push all the projects that you have built so far to your GitHub profile. Here are some of my recommendations for your GitHub profile:
      - Keep the repository names lowercase and use hyphens to separate words e.g. `todo-app` instead of `TodoApp` or `Todo-App`.
      - Add a `README.md` file to each repository that you create. This file should contain a description of the project. Put some effort into the readme and make sure it clearly details what the project is about and how anyone can run it locally.
      - Add snapshots of your project to the readme file so that anyone can see what the project looks like without having to run it locally.
      - Add a `LICENSE` file to each repository that you create. This file should contain the license that you want to use for the project. You can use [choosealicense.com](https://choosealicense.com/) to help you choose a license.
    - You can have a look at [my GitHub profile](https://github.com/nilbuild) and see how I have structured my repositories and how [some of my readme files look like](https://github.com/nilbuild/aws-cost-cli).

### 🧠 Quiz

1. What is a pull request?
   <details><summary>Answer</summary>A request to merge changes from one branch into another, with review and discussion.</details>

2. What is the difference between git pull and git fetch?
   <details><summary>Answer</summary>fetch downloads remote changes without merging; pull fetches and merges (or rebases) them into your branch.</details>

3. What are GitHub Issues used for?
   <details><summary>Answer</summary>Tracking bugs, tasks and feature requests.</details>

---

## 7. Tailwind CSS — ☆☆☆☆☆

> CSS Framework that provides atomic CSS classes to help you style components e.g. `flex`, `pt-4`, `text-center` and `rotate-90` that can be composed to build any design, directly in your markup.

**📚 Learn:**

- 🏛️ Official: [Tailwind CSS](https://tailwindcss.com)
- 🎥 Video: [Tailwind CSS Full Course for Beginners](https://www.youtube.com/watch?v=lCxcTsOHrjo)
- 🎥 Video: [Tailwind CSS Crash Course](https://www.youtube.com/watch?v=UBOj6rqRUME)
- 🎥 Video: [Should You Use Tailwind CSS?](https://www.youtube.com/watch?v=hdGsFpZ0J2E)

**✅ Checklist:**

- [ ] Tailwind CSS — ☆☆☆☆☆

### 🧠 Quiz

1. What is utility-first CSS?
   <details><summary>Answer</summary>Styling by composing small single-purpose classes directly in the markup.</details>

2. How do you apply styles on hover and at medium screens in Tailwind?
   <details><summary>Answer</summary>With prefixes, e.g. hover:bg-blue-600 and md:flex.</details>

3. How does Tailwind keep production CSS small?
   <details><summary>Answer</summary>It generates only the classes found in your source files.</details>

---

## 8. React — ☆☆☆☆☆

> React is the most popular front-end JavaScript library for building user interfaces. React can also render on the server using Node and power mobile apps using React Native.

**📚 Learn:**

- 🗺️ Roadmap: [Visit Dedicated React Roadmap](https://roadmap.sh/react)
- 🏛️ Official: [Getting Started with React](https://react.dev/learn/tutorial-tic-tac-toe)
- 🎥 Video: [React JS Course for Beginners](https://www.youtube.com/watch?v=nTeuhbP7wdE)
- 🎥 Video: [React Course - Beginners Tutorial for React](https://www.youtube.com/watch?v=bMknfKXIFA8)

**✅ Checklist:**

- [ ] Checkpoint - Frontend Apps — ☆☆☆☆☆
  - 🛠️ **Checkpoint brief:**
    - At this point you should be able to build a complete frontend application including:
      - Structuring your webpages with HTML
      - Styling your webpages with CSS
      - Adding interactivity to your webpages with JavaScript
      - Using the DOM API to manipulate your webpages
      - Using the Fetch API to make HTTP requests
      - Understand promises and use `async`/`await` syntax to write asynchronous code
      - Installing and using external libraries with npm
      - Version controlling your code with Git
      - Pushing your code to GitHub
    - If you decided to skip React and Tailwind for now, that is fine also but you should be able to build a complete frontend application using vanilla HTML, CSS, and JavaScript. However, keep in mind that the modern frontend applications are mostly built with frameworks like React, Vue, and Angular. So, you should learn at least one of them at any point of time.
    - This marks the end of frontend basics that you needed, we will now be moving to the backend development. While you continue with the backend development, know that there is more to frontend development and remember to checkout the [frontend roadmap](/frontend) later in your journey.

### 🧠 Quiz

1. What is a React component?
   <details><summary>Answer</summary>A reusable function that returns UI (JSX) based on its props and state.</details>

2. What does useState return?
   <details><summary>Answer</summary>The current state value and a function to update it.</details>

3. When does useEffect run?
   <details><summary>Answer</summary>After render; by default after every render, or only when the listed dependencies change.</details>

---

## 9. Node.js — ☆☆☆☆☆

> Node.js is an open-source and cross-platform JavaScript runtime environment. It is a popular tool for almost any kind of project! Node.js runs the V8 JavaScript engine, Google Chrome's core, outside the browser. This allows Node.js to be very performant. A Node.js app runs in a single process, without creating a new thread for every request. Node.js provides a set of asynchronous I/O primitives in its standard library that prevent JavaScript code from blocking and generally, libraries in Node.js are written using non-blocking paradigms, making blocking behavior the exception rather than the norm.

**📚 Learn:**

- 🗺️ Roadmap: [Visit Dedicated Node.js Roadmap](https://roadmap.sh/nodejs)
- 🏛️ Official: [Node.js Website](https://nodejs.org/en/about/)
- 🏛️ Official: [Learn Node.js Official Website](https://nodejs.org/en/learn/getting-started/introduction-to-nodejs)
- 🎥 Video: [Node.js and Express.js Full Course](https://www.youtube.com/watch?v=Oe421EPjeBE)

**✅ Checklist:**

- [ ] Checkpoint — CLI Apps — ☆☆☆☆☆
  - 🛠️ **Checkpoint brief:**
    - At this point you should be able to build CLI applications using Node.js or whatever backend programming language you picked.
    - You should be able to build a CLI application that can:
      - Read and write files
      - Parse command line arguments
      - Make HTTP requests
      - Parse JSON
      - Use a third-party library (e.g. a library for parsing CSV files)
      - Use a third-party API
    - Here are some ideas for CLI applications you can build:
      - Create a CLI application that takes a URL and a CSS selector arguments and prints the text content of the element that matches the selector. **Hint** you can use [cheerio](https://github.com/cheeriojs/cheerio)
      - An application that optionally takes two dates and prints the most starred GitHub projects in that date range. **Hint** you can use [GitHub's search API](https://developer.github.com/v3/search/#search-repositories)
      - Bulk rename files in a directory. **Hint** you can use [fs](https://nodejs.org/api/fs.html) and [path](https://nodejs.org/api/path.html)
      - Write a CLI application that takes a path as input and compresses all the images in that directory. It should accept an option for output path; if the output path is not given it should compress images in place otherwise write the compressed images to the output path. **Hint** you can use [sharp](https://github.com/lovell/sharp).

### 🧠 Quiz

1. What is Node.js?
   <details><summary>Answer</summary>A JavaScript runtime built on V8 that runs JS outside the browser, e.g. for servers and CLIs.</details>

2. How do you read command-line arguments in Node.js?
   <details><summary>Answer</summary>From process.argv (or a library like commander/yargs).</details>

3. Why should you avoid blocking the event loop?
   <details><summary>Answer</summary>Node runs JS on one thread; long synchronous work blocks all other requests.</details>

---

## 10. PostgreSQL — ☆☆☆☆☆

> PostgreSQL, also known as Postgres, is a free and open-source relational database management system emphasizing extensibility and SQL compliance.

**📚 Learn:**

- 🗺️ Roadmap: [Visit Dedicated PostgreSQL DBA Roadmap](https://roadmap.sh/postgresql-dba)
- 🏛️ Official: [PostgreSQL Website](https://www.postgresql.org/)
- 📄 Article: [Learn PostgreSQL - Full Tutorial for Beginners](https://www.postgresqltutorial.com/)
- 🎥 Video: [Postgres tutorial for Beginners](https://www.youtube.com/watch?v=eMIxuk0nOkU)

**✅ Checklist:**

- [ ] PostgreSQL — ☆☆☆☆☆

### 🧠 Quiz

1. Write a SQL query to get all users older than 18, newest first.
   <details><summary>Answer</summary>SELECT * FROM users WHERE age &gt; 18 ORDER BY created_at DESC;</details>

2. What is a transaction?
   <details><summary>Answer</summary>A group of statements that succeed or fail together (BEGIN ... COMMIT / ROLLBACK).</details>

3. Why add an index to a column?
   <details><summary>Answer</summary>To speed up queries that filter, join or sort by that column.</details>

---

## 11. RESTful APIs — ☆☆☆☆☆

> REST, or REpresentational State Transfer, is an architectural style for providing standards between computer systems on the web, making it easier for systems to communicate with each other.

**📚 Learn:**

- 🗺️ Roadmap: [Visit the Dedicated API Design Roadmap](https://roadmap.sh/api-design)
- 📄 Article: [What is a REST API?](https://www.redhat.com/en/topics/api/what-is-a-rest-api)
- 📄 Article: [Learn REST: A RESTful Tutorial](https://restapitutorial.com/)
- 🎥 Video: [What Is A RESTful API? Explanation of REST & HTTP](https://www.youtube.com/watch?v=Q-BpqyOT3a8)

**✅ Checklist:**

- [ ] Checkpoint — Simple CRUD Apps — ☆☆☆☆☆
  - 🛠️ **Checkpoint brief:**
    - **CRUD** stands for **Create, Read, Update, and Delete**. These are the four basic operations you can perform on any data when working with web applications, databases, and APIs.
    - Now that you know about programming language and the databases, you should be able to build a simple CLI application that interacts with database. We haven't talked about the APIs yet but you don't need an API to practice CRUD operations. Here are some of the CLI applications you can build to practice CRUD operations:
      - A simple todo list application for the CLI with the following options:
        - `--new` to add a new todo item
        - `--list [all|pending|done]` to list the todo items
        - `--done [id]` to update a todo item
        - `--delete [id]` to delete a todo item
        - `--help` to list all the available options
        - `--version` to print the version of the application

### 🧠 Quiz

1. Map CRUD operations to HTTP methods.
   <details><summary>Answer</summary>Create = POST, Read = GET, Update = PUT/PATCH, Delete = DELETE.</details>

2. What status codes should a create and a not-found response return?
   <details><summary>Answer</summary>201 Created and 404 Not Found.</details>

3. What does it mean that REST is stateless?
   <details><summary>Answer</summary>Each request contains all the information needed; the server doesn't store client session state between requests.</details>

---

## 12. JWT Auth — ☆☆☆☆☆

> JWT stands for JSON Web Token is a token-based encryption open standard/methodology that is used to transfer information securely as a JSON object. Clients and Servers use JWT to securely share information, with the JWT containing encoded JSON objects and claims. JWTs are designed to be compact, safe to use within URLs, and ideal for SSO contexts.

**📚 Learn:**

- 🏛️ Official: [Introduction to JSON Web Tokens](https://jwt.io/introduction)
- 📄 Article: [What is JWT?](https://www.akana.com/blog/what-is-jwt)
- 🎥 Video: [What Is JWT and Why Should You Use JWT](https://www.youtube.com/watch?v=7Q17ubqLfaM)
- 🎥 Video: [JWT Authentication Tutorial - Node.js](https://www.youtube.com/watch?v=mbsmsi7l3r4)

**✅ Checklist:**

- [ ] JWT Auth — ☆☆☆☆☆

### 🧠 Quiz

1. How does JWT authentication work?
   <details><summary>Answer</summary>After login the server issues a signed token; the client sends it (e.g. Authorization: Bearer ...) and the server verifies the signature on each request.</details>

2. Is the JWT payload encrypted?
   <details><summary>Answer</summary>No, it is only base64-encoded and signed, so never put secrets in it.</details>

3. Why use short-lived access tokens with refresh tokens?
   <details><summary>Answer</summary>To limit damage if an access token leaks while keeping users logged in.</details>

---

## 13. Redis — ☆☆☆☆☆

> Redis is an open source (BSD licensed), in-memory data structure store used as a database, cache, message broker, and streaming engine. Redis provides data structures such as strings, hashes, lists, sets, sorted sets with range queries, bitmaps, hyperloglogs, geospatial indexes, and streams. Redis has built-in replication, Lua scripting, LRU eviction, transactions, and different levels of on-disk persistence, and provides high availability via Redis Sentinel and automatic partitioning with Redis Cluster.

**📚 Learn:**

- 🗺️ Roadmap: [Visit Dedicated Redis Roadmap](https://roadmap.sh/redis)
- 🏛️ Official: [Redis Documentation](https://redis.io/docs/latest/)
- 🎥 Video: [Redis in 100 Seconds](https://www.youtube.com/watch?v=G1rOthIU-uo)
- 🎥 Video: [Redis Caching in Node.js](https://www.youtube.com/watch?v=oaJq1mQ3dFI)

**✅ Checklist:**

- [ ] Checkpoint — Complete App — ☆☆☆☆☆
  - 🛠️ **Checkpoint brief:**
    - At this point, you should have everything that you need to build a complete application that:
      - Has a responsive frontend that users can interact with
      - Has a backend API that is secured with JWT authentication
      - Has a database that stores data
    - At this point you should practice building as much as you can on your own to solidify your knowledge. If you need inspiration, here are some ideas:
      - Build a simple blogging application where users can register, login, setup their blog and write posts.
      - A single page site builder where users can pick a template, modify it and publish it. **Hint** you will need filesystem to store the design templates. Template files will have placeholders that you will need to replace with user data.
      - Build a simple e-commerce application which will have two types of users i.e. **Sellers** who can: Register as Seller, Login, Setup their store, Add products, Edit products, Delete products, View Received Orders, Update Order Status (Pending, Shipped, Delivered), **Buyers** who can register, Login, Browse products by all sellers, Add products to cart, Checkout, View order history, View order status, Cancel order, View seller profile, View seller products
    - These are just some ideas to get you started. You can build anything you want. The goal is to practice building a complete application from scratch.

### 🧠 Quiz

1. What is Redis?
   <details><summary>Answer</summary>An in-memory key-value data store used for caching, sessions, queues and pub/sub.</details>

2. What does setting a TTL on a key do?
   <details><summary>Answer</summary>The key expires automatically after the given time.</details>

3. Give a common use case for Redis in a web app.
   <details><summary>Answer</summary>Caching database results, storing sessions, rate limiting, or background job queues.</details>

---

## 14. Linux Basics — ☆☆☆☆☆

> Knowledge of UNIX is a must for almost all kind of development as most of the code that you write is most likely going to be finally deployed on a UNIX/Linux machine. Linux has been the backbone of the free and open source software movement, providing a simple and elegant operating system for almost all your needs.

**📚 Learn:**

- 🗺️ Roadmap: [Visit Dedicated Linux Roadmap](https://roadmap.sh/linux)
- 🎓 Course: [Coursera - Unix Courses](https://www.coursera.org/courses?query=unix)
- 📄 Article: [Unix / Linux Tutorial](https://www.tutorialspoint.com/unix/index.htm)
- 🎥 Video: [Linux Operating System - Crash Course](https://www.youtube.com/watch?v=ROjZy1WbCIA)

**✅ Checklist:**

- [ ] Linux Basics — ☆☆☆☆☆

### 🧠 Quiz

1. What do ls, cd, cp, mv and rm do?
   <details><summary>Answer</summary>List files, change directory, copy, move/rename, remove.</details>

2. What does chmod 755 file mean?
   <details><summary>Answer</summary>Owner can read/write/execute; group and others can read/execute.</details>

3. How do you see running processes and kill one?
   <details><summary>Answer</summary>ps aux (or top/htop) to see them; kill &lt;pid&gt; to stop one.</details>

---

## 15. Basic AWS Services — ☆☆☆☆☆

> AWS has several services but you don't need to know all of them. Some common ones that you can start with are EC2, VPC, S3, Route 53, and SES.

**📚 Learn:**

- 🗺️ Roadmap: [Visit the Dedicated AWS Roadmap](https://roadmap.sh/aws)
- 📄 Article: [VPC Basics](https://cloudcasts.io/course/vpc-basics)
- 📄 Article: [EC2 Essentials](https://cloudcasts.io/course/ec2-essentials)
- 🎥 Video: [Deploy Node App on AWS EC2](https://youtu.be/oHAQ3TzUTro)

**✅ Checklist:**

- [ ] EC2 — ☆☆☆☆☆
  - 🏛️ Official: [Amazon AWS EC2](https://aws.amazon.com/ec2/)
  - 📄 Article: [Up and Running with AWS EC2](https://cs.fyi/guide/up-and-running-with-aws-ec2)
  - 📄 Article: [EC2 Essentials](https://cloudcasts.io/course/ec2-essentials)
  - 🎥 Video: [Deploy Node App on AWS EC2](https://youtu.be/oHAQ3TzUTro)
- [ ] VPC — ☆☆☆☆☆
  - 🏛️ Official: [Amazon AWS VPC](https://docs.aws.amazon.com/vpc/latest/userguide/what-is-amazon-vpc.html)
  - 📄 Article: [Up and Running with AWS VPC](https://cs.fyi/guide/up-and-running-with-aws-vpc)
  - 📄 Article: [VPC Basics](https://cloudcasts.io/course/vpc-basics)
  - 🎥 Video: [AWS VPC & Subnets For Beginners](https://youtu.be/TUTqYEZZUdc)
- [ ] Route53 — ☆☆☆☆☆
  - 🏛️ Official: [Route53](https://aws.amazon.com/route53/)
  - 🎥 Video: [Amazon Route 53](https://www.youtube.com/watch?v=RGWgfhZByAI)
  - 🎥 Video: [AWS Route 53 Domain Name](https://www.youtube.com/watch?v=jDz4j_kkyLA)
  - 🎥 Video: [DNS with AWS Route 53](https://www.youtube.com/watch?v=yRIY7BJohfo&t=2s)
- [ ] SES — ☆☆☆☆☆
  - 🏛️ Official: [Amazon AWS SES](https://aws.amazon.com/ses/)
  - 🎥 Video: [Contact Form Submission With AWS SES](https://www.youtube.com/watch?v=HiHflLTqiwU)
- [ ] S3 — ☆☆☆☆☆
  - 🏛️ Official: [Amazon AWS S3](https://aws.amazon.com/s3/)
  - 🎥 Video: [Upload Images to S3 from Node Back End](https://www.youtube.com/watch?v=NZElg91l_ms)
  - 🎥 Video: [S3 Bucket Hosting a Static Website](https://www.youtube.com/watch?v=RoY3ekCCxKc&list=PL0X6fGhFFNTcU-_MCPe9dkH6sqmgfhy_M)
- [ ] Checkpoint — Deployment — ☆☆☆☆☆
  - 🎥 Video: [Deploy Node App on AWS EC2](https://youtu.be/oHAQ3TzUTro)
  - 🛠️ **Checkpoint brief:**
    - Now that you know the basics of AWS, you should be able to deploy your application to AWS. You don't need to use all the AWS services, here is what you can probably get started with:
      - Setup an EC2 instance using any AMI (e.g. latest version of Ubuntu)
      - SSH into the EC2 instance using the key pair you created
      - Install Node.js on the EC2 instance
      - Install Git on the EC2 instance
      - Clone your application from GitHub
      - Install and configure database on the EC2 instance (e.g. PostgreSQL)
      - Make sure that the security group of the EC2 instance allows HTTP and HTTPS traffic
      - Try to access your application using the public IP address of the EC2 instance
      - Purchase or setup a domain name using Route53 (or any other domain name provider) and point it to the public IP address of the EC2 instance
      - Setup HTTPs using [certbot](https://roadmap.sh/guides/setup-and-auto-renew-ssl-certificates)
      - And voilla! You have deployed your application to AWS!

### 🧠 Quiz

1. What are EC2, S3 and VPC?
   <details><summary>Answer</summary>EC2 = virtual servers, S3 = object storage, VPC = your private virtual network.</details>

2. What are Route53 and SES used for?
   <details><summary>Answer</summary>Route53 is DNS and domain management; SES is sending email.</details>

3. What is a security group?
   <details><summary>Answer</summary>A virtual firewall controlling inbound and outbound traffic for EC2 instances.</details>

---

## 16. Monit — ☆☆☆☆☆

> When it comes to monitoring the health of your applications, there are several different options available. My favorite monitoring stack is Prometheus and Grafana, but it can be a bit overwhelming to set up and configure. If you're looking for a simpler solution, **Monit** is a great alternative that can be utilized to monitor and manage system resources such as services, processes, files, directories, devices, and network connections, making your application more reliable and resilient to issues like crashes, unresponsiveness, or resource exhaustion.

**📚 Learn:**

- 🏛️ Official: [Monit Documentation](https://mmonit.com/monit/documentation/)

**✅ Checklist:**

- [ ] Checkpoint — Monitoring — ☆☆☆☆☆
  - 🛠️ **Checkpoint brief:**
    - You should now implement monitoring and autorestarts for your application using monit. Regarding autorestarts, you can also use [pm2](https://pm2.keymetrics.io/).
    - Here are some of the monitors you should implement for the application.
      - CPU Usage
      - Memory Usage
      - Disk Usage
      - Network Usage
      - Service Availability
      - Process Availability
    - Monit comes with existing configurations for many services. You can find them in `/etc/monit/conf-available`. You can copy them (and modify if required) to `/etc/monit/conf-enabled` to enable them.

### 🧠 Quiz

1. What is Monit used for?
   <details><summary>Answer</summary>Monitoring processes, files and system resources on a server and automatically restarting or alerting on failure.</details>

2. Why monitor a production server?
   <details><summary>Answer</summary>To detect crashes, high resource usage and outages quickly, ideally before users notice.</details>

3. Give an example of something Monit can do automatically.
   <details><summary>Answer</summary>Restart a Node.js process if it crashes, or alert when disk usage exceeds 90%.</details>

---

## 17. GitHub Actions — ☆☆☆☆☆

> GitHub Actions is a workflow automation tool provided by GitHub that can be used to automate various tasks in the app development process.

**📚 Learn:**

- 🗺️ Roadmap: [Visit Dedicated Git & GitHub Roadmap](https://roadmap.sh/git-github)
- 🏛️ Official: [GitHub Actions Documentation](https://docs.github.com/en/actions)
- 🎥 Video: [5 Ways to DevOps-ify your App](https://www.youtube.com/watch?v=eB0nUzAI7M8)
- 🎥 Video: [DevOps CI/CD Explained in 100 Seconds](https://www.youtube.com/watch?v=scEDHsr3APg)

**✅ Checklist:**

- [ ] Checkpoint — CI / CD — ☆☆☆☆☆
  - 🛠️ **Checkpoint brief:**
    - Now that you have the infrastructure setup, it's time to automate the deployment process. This is where CI / CD comes in. If you don't know what CI/CD are, you should watch [DevOps CI/CD Explained in 100 Seconds](https://www.youtube.com/watch?v=scEDHsr3APg).
    - The next step at this point is to implement CI/CD for your application using GitHub actions. Setup a GitHub action that, whenever you push to master, will automatically:
      - Run your tests (ignore this step if you haven't learnt it yet)
      - Deploy your application to AWS
    - Regarding the deployment to AWS you can use `rsync` to copy the files to the server. Here's a [sample GitHub workflow](https://gist.github.com/nilbuild/1e94b412006040f38e24b9443b2da41a) using `rsync`.

### 🧠 Quiz

1. Where are GitHub Actions workflows defined?
   <details><summary>Answer</summary>In YAML files in .github/workflows/.</details>

2. What triggers a workflow?
   <details><summary>Answer</summary>Events defined under on:, such as push, pull_request, schedule or manual workflow_dispatch.</details>

3. How should you store secrets like SSH keys for deployment?
   <details><summary>Answer</summary>In GitHub repository/environment secrets, accessed as ${{ secrets.NAME }}.</details>

---

## 18. Ansible — ☆☆☆☆☆

> Ansible is an open-source configuration management, application deployment and provisioning tool that uses its own declarative language in YAML. Ansible is agentless, meaning you only need remote connections via SSH or Windows Remote Management via Powershell in order to function

**📚 Learn:**

- 🏛️ Official: [Ansible Documentation](https://docs.ansible.com/)
- 🏛️ Official: [Ansible Getting Started Guide](https://www.ansible.com/resources/get-started)
- 🎥 Video: [Ansible Full Course for Beginners](https://www.youtube.com/watch?v=9Ua2b06oAr4)

**✅ Checklist:**

- [ ] Checkpoint — Automation — ☆☆☆☆☆
  - 🛠️ **Checkpoint brief:**
    - Now that you have learnt ansible, you can use it to automate the deployment of your application.
    - A task for you at this point would be to automate the steps that you manually performed earlier when setting up the EC2 instance i.e. SSH into the server, install Node.js, Git, PostgreSQL, Running the application etc. Write an ansible playbook that automates these and see if you can spin up a new EC2 instance without SSHing into it and manually installing all the dependencies.

### 🧠 Quiz

1. What is Ansible?
   <details><summary>Answer</summary>An agentless configuration management/automation tool that runs tasks on servers over SSH.</details>

2. What is a playbook?
   <details><summary>Answer</summary>A YAML file describing tasks to run on a set of hosts.</details>

3. What does idempotent mean for Ansible tasks?
   <details><summary>Answer</summary>Running them again leaves the system in the same state without making unnecessary changes.</details>

---

## 19. Terraform — ☆☆☆☆☆

> Terraform is an extremely popular open source Infrastructure as Code (IaC) tool that can be used with many different cloud and service provider APIs. Terraform focuses on an immutable approach to infrastructure, with a terraform state file center to tracking the status of your real world infrastructure.

**📚 Learn:**

- 🗺️ Roadmap: [Visit Dedicated Terraform Roadmap](https://roadmap.sh/terraform)
- 🏛️ Official: [Terraform Documentation](https://www.terraform.io/docs)
- 🏛️ Official: [Terraform Tutorials](https://learn.hashicorp.com/terraform)
- 🎥 Video: [Intro to Terraform](https://www.youtube.com/watch?v=h970ZBgKINg&ab_channel=HashiCorp)

**✅ Checklist:**

- [ ] Checkpoint — Infrastructure — ☆☆☆☆☆
  - 🛠️ **Checkpoint brief:**
    - If you remember, earlier in the roadmap, you manually logged into the AWS console and had to setup the services. Now that you know terraform, go ahead and automate the process of creating the infrastructure for your application using terraform and with that your deployments will be fully automated i.e., you should have:
      - Infrastructure setup using terraform
      - Provisioning using Ansible
      - CI/CD using GitHub Actions
      - Monitoring using Monit
    - And that is it! You have successfully completed the roadmap and are now a full-stack developer. Congratulations! 🎉
    - What's next?
    - Go ahead and build something cool! Share your learnings with the community and help others learn as well. If you have any questions, feel free to join our [discord server](https://roadmap.sh/discord) and ask away!

### 🧠 Quiz

1. What is Infrastructure as Code?
   <details><summary>Answer</summary>Defining and managing infrastructure (servers, networks, DNS) in code files instead of manual clicks.</details>

2. What do terraform plan and terraform apply do?
   <details><summary>Answer</summary>plan shows the changes that would be made; apply makes them.</details>

3. What is the Terraform state file?
   <details><summary>Answer</summary>A record of the real resources Terraform manages, used to compute differences; it should be stored safely (e.g. remote backend).</details>
