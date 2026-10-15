# Frontend Developer Roadmap — Lessons

**How to use:** tick `[x]` when done, and rate yourself by replacing ☆ with ★ (★☆☆☆☆ = just heard of it · ★★★★★ = can teach it). Quiz answers are hidden — click *Answer* to reveal.

Source: https://roadmap.sh/frontend (lesson order follows the roadmap)

---

## Part 1 — Fundamentals

### 1. Internet — ☆☆☆☆☆

> The Internet is a global network of interconnected computers using TCP/IP protocols, connecting billions of devices worldwide. Revolutionized communication, commerce, education, and entertainment. Enables web browsing, streaming, and diverse applications while presenting privacy and security challenges.

**📚 Learn:**

- 📄 Article: [Introduction to Internet](https://roadmap.sh/guides/what-is-internet)
- 📄 Article: [The Internet](https://en.wikipedia.org/wiki/Internet)

**✅ Checklist:**

- [ ] How does the internet work? — ☆☆☆☆☆
  - 📄 Article: [Introduction to Internet](https://roadmap.sh/guides/what-is-internet)
  - 📄 Article: [How does the Internet Work?](https://cs.fyi/guide/how-does-internet-work)
  - 📄 Article: [How Does the Internet Work? MDN Docs](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/How_does_the_Internet_work)
  - 🎥 Video: [How the Internet Works in 5 Minutes](https://www.youtube.com/watch?v=7_LPdttKXPc)
- [ ] What is HTTP? — ☆☆☆☆☆
  - 📄 Article: [Everything you need to know about HTTP](https://cs.fyi/guide/http-in-depth)
  - 📄 Article: [What is HTTP?](https://www.cloudflare.com/en-gb/learning/ddos/glossary/hypertext-transfer-protocol-http/)
  - 📄 Article: [How HTTPS Works](https://howhttps.works)
  - 📄 Article: [HTTP/3 Is Now a Standard: Why Use It and How to Get Started](https://thenewstack.io/http-3-is-now-a-standard-why-use-it-and-how-to-get-started/)
- [ ] What is Domain Name? — ☆☆☆☆☆
  - 📄 Article: [What is a Domain Name?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name)
  - 📄 Article: [What is a Domain Name? | Domain name vs. URL](https://www.cloudflare.com/en-gb/learning/dns/glossary/what-is-a-domain-name/)
  - 🎥 Video: [What is a Domain Name?](https://www.youtube.com/watch?v=lMHzpBwPuG8)
- [ ] What is hosting? — ☆☆☆☆☆
  - 📄 Article: [What is Web Hosting?](https://www.namecheap.com/hosting/what-is-web-hosting-definition/)
  - 🎥 Video: [Different Types of Web Hosting Explained](https://www.youtube.com/watch?v=AXVZYzw8geg)
  - 🎥 Video: [Where to Host a Fullstack Project on a Budget](https://www.youtube.com/watch?v=Kx_1NYYJS7Q)
- [ ] DNS and how it works? — ☆☆☆☆☆
  - 📄 Article: [What is DNS?](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/)
  - 📄 Article: [Mess with DNS - DNS Playground](https://messwithdns.net/)
  - 📄 Article: [How DNS works (comic)](https://howdns.works/)
  - 🎥 Video: [DNS and How does it Work?](https://www.youtube.com/watch?v=Wj0od2ag5sk)
- [ ] Browsers and how they work? — ☆☆☆☆☆
  - 📄 Article: [How Browsers Work](https://www.ramotion.com/blog/what-is-web-browser/)
  - 📄 Article: [Populating the Page: How Browsers Work](https://developer.mozilla.org/en-US/docs/Web/Performance/How_browsers_work)
  - 🎥 Video: [How Do Web Browsers Work?](https://www.youtube.com/watch?v=5rLFYtXHo9s)

#### 🧠 Quiz

1. What happens, step by step, when you type a URL into the browser and press Enter?
   <details><summary>Answer</summary>The browser resolves the domain to an IP via DNS, opens a TCP (and TLS for HTTPS) connection, sends an HTTP request, receives the response, then parses HTML, fetches CSS/JS/images, builds the DOM/CSSOM, lays out and paints the page.</details>

2. What is the difference between HTTP status codes 301, 404 and 500?
   <details><summary>Answer</summary>301 = moved permanently (redirect), 404 = resource not found (client error), 500 = internal server error.</details>

3. What does a DNS A record do?
   <details><summary>Answer</summary>It maps a domain name to an IPv4 address (AAAA maps to IPv6).</details>

### 2. HTML — ☆☆☆☆☆

> HTML (Hypertext Markup Language) is the standard for creating web pages, structuring content with elements and attributes. Browsers interpret HTML tags to render pages. HTML5, the current standard, adds semantic elements, multimedia support, and form controls. It works with CSS for styling and JavaScript for interactivity, forming web development's foundation.

**📚 Learn:**

- 🗺️ Roadmap: [Visit the Dedicated HTML Roadmap](https://roadmap.sh/html)
- 🎓 Course: [Responsive Web Design Certification](https://www.freecodecamp.org/learn/2022/responsive-web-design/)
- 🎥 Video: [HTML Full Course for Beginners](https://youtu.be/mJgBOIoGihA)
- 🎥 Video: [HTML Full Course - Build a Website Tutorial](https://www.youtube.com/watch?v=pQN-pnXPaVg)

**✅ Checklist:**

- [ ] HTML — ☆☆☆☆☆

#### 🧠 Quiz

1. Why should you use semantic elements like &lt;header&gt;, &lt;nav&gt;, &lt;main&gt; and &lt;article&gt; instead of only &lt;div&gt;?
   <details><summary>Answer</summary>They describe meaning, which improves accessibility (screen readers), SEO and code readability.</details>

2. What is the difference between block and inline elements?
   <details><summary>Answer</summary>Block elements start on a new line and take full width (div, p, h1); inline elements flow within text and only take the width they need (span, a, strong).</details>

3. Which attribute is required on &lt;img&gt; for accessibility, and what goes in it?
   <details><summary>Answer</summary>alt — a text description of the image (empty alt="" for purely decorative images).</details>

### 3. CSS — ☆☆☆☆☆

> CSS (Cascading Style Sheets) styles HTML documents, controlling layout, colors, and fonts. Separates design from content using selectors to target elements. Features responsive design with media queries, cascade rules, inheritance, and specificity. Modern CSS includes Flexbox, Grid, animations, and transitions.

**📚 Learn:**

- 🗺️ Roadmap: [Visit the Dedicated CSS Roadmap](https://roadmap.sh/css)
- 🎓 Course: [Responsive Web Design Certification](https://www.freecodecamp.org/learn/2022/responsive-web-design/)
- 📄 Article: [Web.dev by Google — Learn CSS](https://web.dev/learn/css/)
- 🎥 Video: [CSS Complete Course](https://youtu.be/n4R2E7O-Ngo)

**✅ Checklist:**

- [ ] CSS — ☆☆☆☆☆

#### 🧠 Quiz

1. Explain the CSS box model.
   <details><summary>Answer</summary>Every element is a box of content + padding + border + margin. box-sizing: border-box makes width include padding and border.</details>

2. When would you use Flexbox vs Grid?
   <details><summary>Answer</summary>Flexbox for one-dimensional layouts (a row or a column); Grid for two-dimensional layouts (rows and columns together).</details>

3. How is specificity calculated, and which wins: #id, .class or element selector?
   <details><summary>Answer</summary>Inline styles &gt; IDs &gt; classes/attributes/pseudo-classes &gt; elements. #id wins over .class, which wins over element.</details>

### 4. JavaScript — ☆☆☆☆☆

> JavaScript is a versatile programming language that makes websites interactive. Runs in browsers, servers (Node.js), and desktop applications. Features dynamic typing, event-driven programming, and constant evolution. Essential for modern web development across frontend and backend.

**📚 Learn:**

- 🗺️ Roadmap: [Visit Dedicated JavaScript Roadmap](https://roadmap.sh/javascript)
- 📄 Article: [The Modern JavaScript Tutorial](https://javascript.info/)
- 📄 Article: [Build 30 Javascript projects in 30 days](https://javascript30.com/)

**✅ Checklist:**

- [ ] JavaScript — ☆☆☆☆☆

#### 🧠 Quiz

1. What is the difference between let, const and var?
   <details><summary>Answer</summary>var is function-scoped and hoisted; let and const are block-scoped. const cannot be reassigned (but objects it holds can be mutated).</details>

2. What is a closure?
   <details><summary>Answer</summary>A function that remembers variables from the scope where it was created, even after that scope has finished executing.</details>

3. What does the event loop do, and in what order do a setTimeout(fn, 0) and a resolved Promise's .then run?
   <details><summary>Answer</summary>It runs queued tasks when the call stack is empty. Microtasks (Promise .then) run before the next macrotask (setTimeout), so .then runs first.</details>

> Project: Beginner Project Ideas

### 5. Version Control — ☆☆☆☆☆

> Version Control Systems (VCS) like Git track code changes and enable developer collaboration through modification history. Features include branching, merging, reverting, remote repositories, pull requests, and code reviews. Essential for modern software development productivity, quality, and teamwork.

**📚 Learn:**

- 🗺️ Roadmap: [Visit Dedicated Git & GitHub Roadmap](https://roadmap.sh/git-github)
- 🎓 Course: [Why version control? (Interactive Lesson)](https://inter-git.com/lessons/introduction)
- 📄 Article: [What is version control?](https://www.atlassian.com/git/tutorials/what-is-version-control)
- 🎥 Video: [What is a Version Control System and why you should always use it](https://www.youtube.com/watch?v=IeXhYROClZk)

**✅ Checklist:**

- [ ] Git — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated Git & GitHub Roadmap](https://roadmap.sh/git-github)
  - 🎓 Course: [Why use Git? (Interactive Lesson)](https://inter-git.com/lessons/introduction)
  - 📄 Article: [Tutorial: Git for Absolutely Everyone](https://thenewstack.io/tutorial-git-for-absolutely-everyone/)
  - 🎥 Video: [Git & GitHub Crash Course For Beginners](https://www.youtube.com/watch?v=SWYqp7iY_Tc)

#### 🧠 Quiz

1. What is the difference between git merge and git rebase?
   <details><summary>Answer</summary>Merge joins histories with a merge commit; rebase replays your commits on top of another branch, producing a linear history.</details>

2. What do git add, git commit and git push each do?
   <details><summary>Answer</summary>add stages changes, commit records staged changes locally, push uploads local commits to a remote.</details>

3. How do you undo the last commit but keep the changes in your working tree?
   <details><summary>Answer</summary>git reset --soft HEAD~1 (keeps changes staged) or git reset HEAD~1 (keeps them unstaged).</details>

### 6. VCS Hosting — ☆☆☆☆☆

> Repository hosting services (GitHub, GitLab, Bitbucket) provide platforms for storing, managing, and collaborating on software projects using Git version control. Facilitate teamwork, code sharing, project tracking, and distributed software development workflows.

**📚 Learn:**

- 🗺️ Roadmap: [Visit Dedicated Git & GitHub Roadmap](https://roadmap.sh/git-github)
- 🏛️ Official: [GitHub Website](https://github.com)
- 🏛️ Official: [GitLab Website](https://about.gitlab.com)
- 🏛️ Official: [BitBucket Website](https://bitbucket.com)

**✅ Checklist:**

- [ ] GitHub — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated Git & GitHub Roadmap](https://roadmap.sh/git-github)
  - 🏛️ Official: [GitHub: Quickstart](https://docs.github.com/en/get-started/quickstart/hello-world)
  - 🏛️ Official: [Learn GitHub by doing](https://skills.github.com/)
  - 🎥 Video: [What is GitHub?](https://www.youtube.com/watch?v=w3jLJU7DT5E)
- [ ] GitLab — ☆☆☆☆☆
  - 🏛️ Official: [GitLab Website](https://gitlab.com/)
  - 🏛️ Official: [GitLab Documentation](https://docs.gitlab.com/)
  - 📄 Article: [Development: Connect git to GitLab for Small Projects](https://thenewstack.io/development-connect-git-to-gitlab-for-small-projects/)

#### 🧠 Quiz

1. What is a pull request (merge request)?
   <details><summary>Answer</summary>A request to merge a branch into another, with a place for code review, discussion and CI checks.</details>

2. What is the difference between a fork and a clone?
   <details><summary>Answer</summary>A fork is your own server-side copy of a repository on GitHub/GitLab; a clone is a local copy on your machine.</details>

3. What is CI (e.g. GitHub Actions) used for?
   <details><summary>Answer</summary>Automatically running tests, linting, builds and deployments on every push or pull request.</details>

### 7. Package Managers — ☆☆☆☆☆

> Package managers automate software package installation, updates, and dependency management. Examples include npm (JavaScript), pip (Python), and yarn. Enable code sharing, reuse, and consistent project setups. Essential for modern development workflows and team collaboration.

**📚 Learn:**

- 🏛️ Official: [PNPM: The Faster, More Performant NPM](https://pnpm.io/)
- 🏛️ Official: [Yarn - Getting Started](https://yarnpkg.com/en/docs/getting-started)
- 📄 Article: [An Absolute Beginners Guide to Using npm](https://nodesource.com/blog/an-absolute-beginners-guide-to-using-npm/)
- 🎥 Video: [NPM Crash Course](https://www.youtube.com/watch?v=jHDhaSSKmB0)

**✅ Checklist:**

- [ ] npm — ☆☆☆☆☆
  - 🏛️ Official: [NPM Documentation](https://docs.npmjs.com/)
  - 📄 Article: [Modern JavaScript for Dinosaurs](https://peterxjang.com/blog/modern-javascript-explained-for-dinosaurs.html)
  - 🎥 Video: [NPM Tutorial for Beginners](https://www.youtube.com/watch?v=2V1UUhBJ62Y)
- [ ] pnpm — ☆☆☆☆☆
  - 🏛️ Official: [PNPM Website](https://pnpm.io)
  - 📄 Article: [Meet PNPM: The Faster, More Performant NPM](https://blog.bitsrc.io/pnpm-javascript-package-manager-4b5abd59dc9)
  - 🎥 Video: [Get started with pnpm](https://www.youtube.com/watch?v=MvbReZDSKHI)
- [ ] yarn — ☆☆☆☆☆
  - 🏛️ Official: [Yarn - Getting Started](https://yarnpkg.com/en/docs/getting-started)
  - 🎥 Video: [Yarn Crash Course](https://www.youtube.com/watch?v=g9_6KmiBISk)
- [ ] Bun — ☆☆☆☆☆
  - 🏛️ Official: [Bun Docs](https://bun.com/docs)
  - 💻 Open source: [bun](https://github.com/oven-sh/bun)
  - 📄 Article: [What Is Bun? An All-in-One Runtime Taking on Node.js](https://kinsta.com/blog/bun-sh/)
  - 🎥 Video: [Bun Crash Course | JavaScript Runtime, Bundler & Transpiler](https://www.youtube.com/watch?v=U4JVw8K19uY)

#### 🧠 Quiz

1. What is the difference between dependencies and devDependencies?
   <details><summary>Answer</summary>dependencies are needed at runtime; devDependencies are only needed for development and building (tests, linters, bundlers).</details>

2. Why should you commit the lockfile (package-lock.json / pnpm-lock.yaml / yarn.lock)?
   <details><summary>Answer</summary>It pins exact versions of every dependency so installs are reproducible across machines and CI.</details>

3. What does ^1.2.3 mean in package.json?
   <details><summary>Answer</summary>Any compatible version &gt;=1.2.3 and &lt;2.0.0 (same major version).</details>

### 8. CSS Frameworks — ☆☆☆☆☆

> Modern CSS creates responsive designs using media queries, flexible typography, CSS-in-JS, and frameworks like Tailwind. Features CSS Logical Properties for internationalization and CSS Houdini for custom styling. Goals: performance, maintainability, and accessible designs across all devices.

**📚 Learn:**

- 🗺️ Roadmap: [Visit the Dedicated CSS Roadmap](https://roadmap.sh/css)
- 📄 Article: [Modern CSS: A Comprehensive Guide](https://moderncss.dev/)
- 📄 Article: [CSS-Tricks: Modern CSS](https://css-tricks.com/modern-css/)

**✅ Checklist:**

- [ ] Tailwind — ☆☆☆☆☆
  - 🎓 Course: [Tailwind CSS Full Course for Beginners](https://www.youtube.com/watch?v=lCxcTsOHrjo)
  - 🏛️ Official: [Tailwind Website](https://tailwindcss.com)
  - 🏛️ Official: [Online Playground](https://play.tailwindcss.com)
  - 🎥 Video: [Official Screencasts](https://www.youtube.com/c/TailwindLabs/videos)

#### 🧠 Quiz

1. What is a utility-first CSS framework?
   <details><summary>Answer</summary>One that gives small single-purpose classes (e.g. p-4, flex, text-center) that you compose in markup instead of writing custom CSS.</details>

2. How does Tailwind keep the final CSS file small?
   <details><summary>Answer</summary>It scans your source files and only generates the classes you actually use.</details>

3. How do you apply a style only on medium screens and up in Tailwind?
   <details><summary>Answer</summary>Use a responsive prefix, e.g. md:flex or md:text-lg (mobile-first breakpoints).</details>

> Checkpoint: you should be able to build modern vanilla JS frontend applications.
> Project: Intermediate Project Ideas

### 9. Learn a Framework — ☆☆☆☆☆

> Web frameworks are development toolkits providing libraries, structure, rules, and tools for building applications. Different frameworks offer varying features based on project needs. Popular examples include React, Angular, and Vue, each with unique strengths and capabilities.

**📚 Learn:**

- 🎥 Video: [15 Crazy New JS Framework Features You Don't Know Yet](https://www.youtube.com/watch?v=466U-2D86bc)
- 🎥 Video: [Which JS Framework is Best?](https://www.youtube.com/watch?v=cuHDQhDhvPE)

**✅ Checklist:**

- [ ] React — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated React Roadmap](https://roadmap.sh/react)
  - 🎓 Course: [Full Stack React Developer Course](https://www.youtube.com/watch?v=Bvwq_S0n2pk)
  - 🏛️ Official: [React Website](https://react.dev)
- [ ] Vue.js — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated Vue Roadmap](https://roadmap.sh/vue)
  - 🏛️ Official: [Vue.js Website](https://vuejs.org/)
  - 🎥 Video: [Vue.js Course for Beginners](https://www.youtube.com/watch?v=VeNfHj6MhgA)
- [ ] Angular — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated Angular Roadmap](https://roadmap.sh/angular)
  - 🏛️ Official: [Getting started with Angular](https://angular.dev/tutorials/learn-angular)
  - 🎥 Video: [Angular for Beginners Course](https://www.youtube.com/watch?v=3qBXWUpoPHo)
- [ ] Svelte — ☆☆☆☆☆
  - 🎓 Course: [Svelte Course Playlist for beginners](https://www.youtube.com/playlist?list=PL4cUxeGkcC9hlbrVO_2QFVqVPhlZmz7tO)
  - 🏛️ Official: [Svelte Website](https://svelte.dev/)
  - 📄 Article: [Svelte and the Future of Frontend Development](https://thenewstack.io/svelte-and-the-future-of-front-end-development/)
- [ ] Solid JS — ☆☆☆☆☆
  - 🏛️ Official: [SolidJS Website](https://www.solidjs.com/)
  - 🏛️ Official: [SolidJS Tutorial](https://www.solidjs.com/tutorial/introduction_basics)
  - 🎥 Video: [SolidJS in 100 Seconds](https://www.youtube.com/watch?v=hw3Bx5vxKl0)

#### 🧠 Quiz

1. What problem do frontend frameworks solve compared to vanilla JS?
   <details><summary>Answer</summary>They keep the UI in sync with state declaratively, provide component reuse, and manage DOM updates efficiently.</details>

2. What is the difference between props and state (in React terms)?
   <details><summary>Answer</summary>Props are inputs passed from a parent and are read-only; state is data owned by a component that can change and trigger re-renders.</details>

3. Why do list items need a key?
   <details><summary>Answer</summary>So the framework can identify items between renders and update, reorder or remove them correctly and efficiently.</details>

---

## Part 2 — AI in Development

### 10. Learn the Basics — ☆☆☆☆☆

> Generative AI uses algorithms to create new content, like code or designs, based on the data it's trained on. This means it can help frontend developers by automatically generating things like UI elements, suggesting code snippets, or even creating entire webpage layouts based on specific requirements and examples. Essentially, it's a tool that can automate repetitive tasks and inspire new ideas in the frontend development workflow.

**📚 Learn:**

- 📄 Article: [AI in software development - IBM](https://www.ibm.com/think/topics/ai-in-software-development)
- 📄 Article: [AI in software development](https://github.com/resources/articles/ai-in-software-development)
- 📄 Article: [The right way to implement AI into your frontend workflow](https://blog.logrocket.com/frontend-ai-tools-for-developers/)
- 📄 Article: [5 Best AI Models For Frontend Development and UI Design](https://www.index.dev/blog/ai-models-frontend-development-ui-generation)

**✅ Checklist:**

- [ ] How LLMs work — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated AI Engineer Roadmap](https://roadmap.sh/ai-engineer)
  - 📄 Article: [What is a large language model (LLM)?](https://www.cloudflare.com/en-gb/learning/ai/what-is-large-language-model/)
  - 📄 Article: [New to LLMs? Start Here](https://towardsdatascience.com/new-to-llms-start-here/)
  - 🎥 Video: [How Large Language Models Work](https://www.youtube.com/watch?v=5sLYAQS9sWQ)
- [ ] AI vs Traditional Coding — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated Vibe Coding Roadmap](https://roadmap.sh/vibe-coding)
  - 📄 Article: [What is vibe coding?](https://www.ibm.com/think/topics/vibe-coding)
  - 📄 Article: [How AI is transforming work at Anthropic](https://www.anthropic.com/research/how-ai-is-transforming-work-at-anthropic)
  - 🎥 Video: [AI Systems vs Traditional Coding](https://www.youtube.com/watch?v=P7lryCIvxgA)
- [ ] Applications — ☆☆☆☆☆
  - 📄 Article: [AI in software development](https://www.ibm.com/think/topics/ai-in-software-development)
  - 📄 Article: [AI in software development: How to use it, benefits, and key trends](https://appfire.com/resources/blog/ai-in-software-development)
  - 📄 Article: [AI-Assisted Software Development: A Comprehensive Guide with Practical Prompts (Part 1/3)](https://aalapdavjekar.medium.com/ai-assisted-software-development-a-comprehensive-guide-with-practical-prompts-part-1-3-989a529908e0)
  - [ ] Code Reviews — ☆☆☆☆☆
    - 🏛️ Official: [Common workflows - Claude Code](https://code.claude.com/docs/en/common-workflows)
    - 📄 Article: [AI Code Reviews](https://github.com/resources/articles/ai-code-reviews)
    - 📄 Article: [AI Code Review: How to Make it Work for You](https://www.startearly.ai/post/ai-code-review-how-to-make-it-work-for-you)
    - 🎥 Video: [Automatic code reviews with OpenAI Codex](https://www.youtube.com/watch?v=HwbSWVg5Ln4&t=83s)
  - [ ] Refactoring — ☆☆☆☆☆
    - 📄 Article: [What is AI code refactoring? - IBM](https://www.ibm.com/think/topics/ai-code-refactoring)
    - 📄 Article: [What is AI code refactoring?](https://graphite.com/guides/what-is-ai-code-refactoring)
    - 🎥 Video: [Using AI to Refactor Legacy Code:](https://www.youtube.com/watch?v=B7Yt-WmlW2I)
    - 🎥 Video: [AI-Driven Code Refactoring: Improving Legacy Codebases](https://www.youtube.com/watch?v=u8tvVxUOwvY)
  - [ ] Docs Generation — ☆☆☆☆☆
    - 📄 Article: [AI code documentation: Benefits and top tips](https://www.ibm.com/think/insights/ai-code-documentation-benefits-top-tips)
    - 📄 Article: [AI Code Documentation Generators: A Guide](https://overcast.blog/ai-code-documentation-generators-a-guide-b6cd72cd0ec4)
    - 📄 Article: [Automate Your Docs with Claude Code & GitHub Actions](https://medium.com/@fra.bernhardt/automate-your-documentation-with-claude-code-github-actions-a-step-by-step-guide-2be2d315ed45)
    - 🎥 Video: [How I Built a Tool to Auto-Generate GitHub docs](https://www.youtube.com/watch?v=QYchuz6nBR8)

#### 🧠 Quiz

1. At a high level, how does an LLM generate text?
   <details><summary>Answer</summary>It predicts the next token repeatedly, based on patterns learned from training data and the current context.</details>

2. What is a context window?
   <details><summary>Answer</summary>The maximum amount of text (tokens) the model can consider at once, including your prompt and its answer.</details>

3. Why must you review AI-generated code?
   <details><summary>Answer</summary>It can be plausible but wrong: hallucinated APIs, subtle bugs, security issues or code that doesn't fit your project.</details>

### 11. AI Assisted Coding — ☆☆☆☆☆

> AI-assisted coding involves using artificial intelligence tools to help developers write code more efficiently and effectively. These tools can provide real-time suggestions, automate repetitive tasks, identify potential errors, and even generate code snippets based on natural language descriptions, ultimately speeding up development and improving code quality.

**📚 Learn:**

- 📚 Book: [AI-Assisted Programming](https://www.hkdca.com/wp-content/uploads/2025/06/ai-assisted-programming-oreilly.pdf)
- 📄 Article: [How to Become an Expert in AI-Assisted Coding](https://www.freecodecamp.org/news/how-to-become-an-expert-in-ai-assisted-coding-a-handbook-for-developers/)
- 📄 Article: [The 10 Best Vibe Coding Tools in 2026: Our Choices](https://roadmap.sh/vibe-coding/best-tools)
- 🎥 Video: [How to elevate software development with AI-assisted coding](https://www.youtube.com/watch?v=S2GqQ4gJAH0)

**✅ Checklist:**

- [ ] Claude Code — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated Claude Code Roadmap](https://roadmap.sh/claude-code)
  - 🏛️ Official: [Claude Code Overview](https://code.claude.com/docs/en/overview)
  - 📄 Article: [Vibe coding tutorial: Build your first app with Claude Code](https://roadmap.sh/vibe-coding/tutorial)
  - 🎥 Video: [Introducing Claude Code](https://www.youtube.com/watch?v=AJpK3YTTKZ4)
- [ ] Cursor — ☆☆☆☆☆
  - 🏛️ Official: [Cursor Docs](https://cursor.com/docs)
  - 📄 Article: [Claude Code vs Cursor: Which AI Coding Tool To Choose](https://roadmap.sh/claude-code/vs-cursor)
  - 🎥 Video: [Cursor AI Tutorial for Beginners](https://www.youtube.com/watch?v=3289vhOUdKA)
  - 🎥 Video: [Cursor Tutorial for Beginners (AI Code Editor)](https://www.youtube.com/watch?v=ocMOZpuAMw4)
- [ ] Copilot — ☆☆☆☆☆
  - 🏛️ Official: [Quickstart for GitHub Copilot](https://docs.github.com/en/copilot/quickstart)
  - 🏛️ Official: [Tutorials for GitHub Copilot](https://docs.github.com/en/copilot/tutorials)
  - 📄 Article: [Github Copilot Tutorial](https://www.tutorialspoint.com/github-copilot/index.htm)
  - 🎥 Video: [Intro to GitHob Copilot in Visual Studio](https://www.youtube.com/watch?v=z1ycDvspv8U)
- [ ] Antigravity — ☆☆☆☆☆
  - 🏛️ Official: [Google Antigravity](https://antigravity.google/)
  - 🏛️ Official: [Getting Started with Google Antigravity](https://codelabs.developers.google.com/getting-started-google-antigravity#0)
  - 📄 Article: [Hands-On With Antigravity: Google’s Newest AI Coding Experiment](https://thenewstack.io/hands-on-with-antigravity-googles-newest-ai-coding-experiment/)
  - 🎥 Video: [Welcome to Google Antigravity 🚀](https://www.youtube.com/watch?v=SVCBA-pBgt0)

#### 🧠 Quiz

1. What is the difference between inline autocomplete and an agentic coding tool?
   <details><summary>Answer</summary>Autocomplete suggests the next lines as you type; an agent (e.g. Claude Code) can plan, read and edit many files, and run commands to complete a task.</details>

2. What context helps an AI coding tool give better results?
   <details><summary>Answer</summary>Relevant files, project conventions (e.g. a CLAUDE.md), error messages, and a clear description of the goal and constraints.</details>

3. Name one risk of letting an AI tool run commands in your project.
   <details><summary>Answer</summary>It can make destructive or unintended changes, so use permissions, version control and review its actions.</details>

### 12. Prompting Techniques — ☆☆☆☆☆

> Prompt engineering is the process of crafting effective inputs (prompts) to guide AI models to generate desired outputs. It involves strategically designing prompts to optimize the model’s performance by providing clear instructions, context, and examples. Effective prompt engineering can improve the quality, relevance, and accuracy of responses, making it essential for applications like chatbots, content generation, and automated support. By refining prompts, developers can better control the model’s behavior, reduce ambiguity, and achieve more consistent results, enhancing the overall effectiveness of AI-driven systems.

**📚 Learn:**

- 🗺️ Roadmap: [Visit Dedicated Prompt Engineering Roadmap](https://roadmap.sh/prompt-engineering)
- 🎓 Course: [Introduction to Prompt Engineering](https://learnprompting.org/courses/intro-to-prompt-engineering)
- 📄 Article: [Prompt engineering techniques](https://www.ibm.com/think/topics/prompt-engineering-techniques)
- 🎥 Video: [What is Prompt Engineering?](https://www.youtube.com/watch?v=nf1e-55KKbg)

**✅ Checklist:**

- [ ] Prompting Techniques (see also: Prompt Engineering roadmap) — ☆☆☆☆☆

#### 🧠 Quiz

1. What is few-shot prompting?
   <details><summary>Answer</summary>Giving the model a few examples of input and desired output in the prompt so it follows the pattern.</details>

2. Why does being specific help a prompt?
   <details><summary>Answer</summary>It reduces ambiguity: stating the goal, constraints, format and context gets more accurate, usable answers.</details>

3. What is chain-of-thought prompting?
   <details><summary>Answer</summary>Asking the model to reason step by step before answering, which often improves results on complex problems.</details>

### 13. Agents — ☆☆☆☆☆

> AI agents are autonomous programs designed to help developers write code more efficiently. These agents can automate repetitive tasks, suggest code completions, identify errors, and even generate entire code blocks based on natural language descriptions or existing code patterns. They leverage machine learning models to understand code syntax, semantics, and context, enabling them to provide intelligent and relevant assistance throughout the software development lifecycle.

**📚 Learn:**

- 🗺️ Roadmap: [Visit the Dedicated AI Agents Roadmap](https://roadmap.sh/ai-agents)
- 📄 Article: [What are AI Agents? - IBM](https://www.ibm.com/think/topics/ai-agents)
- 🎥 Video: [From Zero to Your First AI Agent in 25 Minutes (No Coding)](https://www.youtube.com/watch?v=EH5jx5qPabU)
- 🎥 Video: [What are AI Agents?](https://www.youtube.com/watch?v=F8NKVhkZZWI)

**✅ Checklist:**

- [ ] Agents (see also: AI Agents roadmap) — ☆☆☆☆☆

#### 🧠 Quiz

1. What makes an AI 'agent' different from a single chat response?
   <details><summary>Answer</summary>An agent works in a loop: it plans, calls tools, observes results and continues until the goal is done.</details>

2. What is a 'tool' in the context of AI agents?
   <details><summary>Answer</summary>A function the model can call (e.g. search, read a file, run code) with structured inputs, whose output is fed back to the model.</details>

3. Why should agents have limits or human approval steps?
   <details><summary>Answer</summary>To prevent costly, destructive or unsafe actions and keep the human in control.</details>

### 14. MCP — ☆☆☆☆☆

> Model Context Protocol (MCP) is a rulebook that tells an AI agent how to pack background information before it sends a prompt to a language model. It lists what pieces go into the prompt—things like the system role, the user’s request, past memory, tool calls, or code snippets—and fixes their order. Clear tags mark each piece, so both humans and machines can see where one part ends and the next begins. Keeping the format steady cuts confusion, lets different tools work together, and makes it easier to test or swap models later. When agents follow MCP, the model gets a clean, complete prompt and can give better answers.

**📚 Learn:**

- 🎓 Course: [MCP: Build Rich-Context AI Apps with Anthropic](https://www.deeplearning.ai/short-courses/mcp-build-rich-context-ai-apps-with-anthropic/)
- 🏛️ Official: [Model Context Protocol](https://modelcontextprotocol.io/introduction)
- 💻 Open source: [modelcontexprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol)
- 📄 Article: [The Ultimate Guide to MCP](https://guangzhengli.com/blog/en/model-context-protocol)

**✅ Checklist:**

- [ ] MCP — ☆☆☆☆☆

#### 🧠 Quiz

1. What is MCP (Model Context Protocol)?
   <details><summary>Answer</summary>An open standard for connecting AI applications to external tools and data sources through MCP servers.</details>

2. What does an MCP server provide?
   <details><summary>Answer</summary>Tools, resources and prompts that an AI client can discover and use.</details>

3. Give an example of how MCP helps a frontend developer.
   <details><summary>Answer</summary>E.g. a browser-automation or design-tool MCP server lets the AI inspect a running page or read designs directly.</details>

### 15. Skills — ☆☆☆☆☆

> AI coding assistants can leverage "skills" – pre-defined functions or tools exposed to the AI that allow it to perform specific actions. Instead of relying solely on their internal knowledge and large language models, these assistants can call upon these skills (like running tests, deploying code, or querying databases) when needed. This allows the AI to interact with the development environment and execute tasks directly, improving accuracy and efficiency, all while minimizing the context window required for each action.

**📚 Learn:**

- 🎓 Course: [Agent Skills with Anthropic](https://www.deeplearning.ai/short-courses/agent-skills-with-anthropic/)
- 📄 Article: [Agent Skills: The Universal Standard Transforming AI Agents](https://medium.com/@richardhightower/agent-skills-the-universal-standard-transforming-how-ai-agents-work-fc7397406e2e)
- 🎥 Video: [Claude Agent Skills Explained](https://www.youtube.com/watch?v=fOxC44g8vig)
- 🎥 Video: [Agent Skills Explained](https://www.youtube.com/watch?v=Ihoxov5x66k)

**✅ Checklist:**

- [ ] Skills — ☆☆☆☆☆

#### 🧠 Quiz

1. What is an agent skill?
   <details><summary>Answer</summary>A packaged set of instructions (and optionally scripts/resources) an AI agent loads to perform a specific kind of task well.</details>

2. Why are skills useful compared to repeating instructions in every prompt?
   <details><summary>Answer</summary>They are reusable, consistent and loaded only when relevant, saving context and effort.</details>

3. What is a good candidate for a skill in a frontend team?
   <details><summary>Answer</summary>A repeatable workflow, e.g. creating a component following team conventions, or a code-review checklist.</details>

### 16. Implementing AI — ☆☆☆☆☆

> Implementing AI in frontend development involves integrating artificial intelligence capabilities directly into user interfaces and workflows. This can range from simple tasks like intelligent form validation to complex features such as personalized content recommendations or AI-powered chatbots. Several major providers offer generative AI solutions that can be leveraged for frontend implementation, including Google with its AI platform, Antropic with its models like Claude, and OpenAI with its popular GPT series. These tools provide developers with the ability to incorporate AI functionalities to improve user experience and streamline development processes.

**📚 Learn:**

- 📄 Article: [Anthropic vs OpenAI vs Gemini](https://www.aqedigital.com/blog/anthropic-vs-openai-vs-gemini/)

**✅ Checklist:**

- [ ] OpenAI — ☆☆☆☆☆
  - 🏛️ Official: [OpenAI](https://platform.openai.com/docs/overview)
  - 🏛️ Official: [OpenAI Models](https://platform.openai.com/docs/models)
  - 🏛️ Official: [OpenAI Academy](https://academy.openai.com/)
- [ ] Anthropic — ☆☆☆☆☆
  - 🏛️ Official: [Anthropic](https://www.anthropic.com/)
  - 🏛️ Official: [Anthropic Academy](https://www.anthropic.com/learn)
  - 🏛️ Official: [Anthropic Tutorials](https://claude.com/resources/tutorials)
  - 📄 Article: [Anthropic: What We Know About the Company Behind Claude AI](https://builtin.com/articles/anthropic)
- [ ] Gemini — ☆☆☆☆☆
  - 🏛️ Official: [Google Gemini](https://gemini.google.com/)
  - 🏛️ Official: [Google Gemini Docs](https://workspace.google.com/solutions/ai/)
  - 🎥 Video: [Welcome to the Gemini era](https://www.youtube.com/watch?v=_fuimO6ErKI)

#### 🧠 Quiz

1. Why should you never call an AI provider API directly from the browser with your secret key?
   <details><summary>Answer</summary>The key would be exposed to anyone. Call the API from your server (or a serverless function) instead.</details>

2. Why is streaming responses useful in an AI chat UI?
   <details><summary>Answer</summary>Users see text as it is generated, which feels much faster than waiting for the full response.</details>

3. How can you get structured data (e.g. JSON) back from a model reliably?
   <details><summary>Answer</summary>Use the provider's structured output / tool-use features with a schema, and validate the result.</details>

---

## Part 3 — Advanced Frontend

### 17. Linters & Formatters — ☆☆☆☆☆

> Linters and formatters improve code quality by finding errors, bugs, and style issues (linters) and automatically fixing formatting like indentation and spacing (formatters). Ensure consistency, readability, and early error detection. Examples: ESLint, Prettier.

**📚 Learn:**

- 📄 Article: [What Is a Linter?](https://www.testim.io/blog/what-is-a-linter-heres-a-definition-and-quick-start-guide/)

**✅ Checklist:**

- [ ] ESLint — ☆☆☆☆☆
  - 🏛️ Official: [ESLint Website](https://eslint.org/)
  - 📄 Article: [What is ESLint and How to Use it](https://2coffee.dev/en/articles/what-is-eslint-and-how-to-use-eslint-to-detect-fix-code-for-javascript-projects)
  - 🎥 Video: [ESLint Quickstart - find errors automatically](https://www.youtube.com/watch?v=qhuFviJn-es)
- [ ] Prettier — ☆☆☆☆☆
  - 🏛️ Official: [Prettier Website](https://prettier.io)
  - 🏛️ Official: [Why Prettier](https://prettier.io/docs/en/why-prettier.html)
  - 🎥 Video: [How to set up Prettier](https://www.youtube.com/watch?v=DqfQ4DPnRqI)
- [ ] Biome — ☆☆☆☆☆
  - 🏛️ Official: [Biome](https://biomejs.dev/)
  - 💻 Open source: [biome](https://github.com/biomejs/biome)
  - 📄 Article: [Biome: The All-in-One Toolchain for Modern Frontend Projects](https://blog.openreplay.com/biome-toolchain-modern-frontend-projects/)
  - 🎥 Video: [The EASIEST Way To Switch to Biome](https://www.youtube.com/watch?v=lEkXbneUnWg)

#### 🧠 Quiz

1. What is the difference between a linter and a formatter?
   <details><summary>Answer</summary>A linter (ESLint) finds code-quality problems and bugs; a formatter (Prettier) only enforces consistent code style.</details>

2. How can you make sure code is linted before it's committed?
   <details><summary>Answer</summary>Run the linter in a pre-commit hook (e.g. husky + lint-staged) and in CI.</details>

3. What does Biome offer compared to ESLint + Prettier?
   <details><summary>Answer</summary>A single, fast (Rust-based) tool that does both linting and formatting.</details>

### 18. Module Bundlers — ☆☆☆☆☆

> Module bundlers combine multiple JavaScript files into optimized bundles for browsers. Handle dependencies, code transformation, and splitting for performance. Examples: Webpack, Rollup, Parcel. Enable modern JavaScript features, improve load times, and streamline development workflows.

**📚 Learn:**

- 🏛️ Official: [Rollup Bundler](https://rollupjs.org/)
- 🏛️ Official: [Webpack Website](https://webpack.js.org/)
- 📄 Article: [The Complete JavaScript Module Bundlers Guide](https://snipcart.com/blog/javascript-module-bundler)
- 🎥 Video: [Module Bundlers Explained](https://www.youtube.com/watch?v=5IG4UmULyoA)

**✅ Checklist:**

- [ ] Vite — ☆☆☆☆☆
  - 🏛️ Official: [Vite - The Build Tool for the Web](https://vite.dev)
  - 🏛️ Official: [Vite Documentation](https://vite.dev/guide/)
  - 🎥 Video: [Vite Crash Course](https://youtu.be/LQQ3CR2JTX8)
  - 🎥 Video: [Vite Tutorial Video](https://www.youtube.com/watch?v=VAeRhmpcWEQ)
- [ ] esbuild — ☆☆☆☆☆
  - 🎓 Course: [Let's Learn esbuild! (with Sunil Pai) — Learn With Jason](https://www.youtube.com/watch?v=KLdF1yu_bmI)
  - 🏛️ Official: [Esbuild Website](https://esbuild.github.io/)
  - 🎥 Video: [What Is ESBuild?](https://www.youtube.com/watch?v=ZY8Vu8cbWF0)
- [ ] SWC — ☆☆☆☆☆
  - 🏛️ Official: [SWC Website](https://swc.rs/)
  - 🏛️ Official: [SWC Documentation](https://swc.rs/docs/)
  - 🎥 Video: [Introduction to Speedy Web Compiler](https://www.youtube.com/watch?v=RXQlPpbdn_E)
- [ ] Rollup — ☆☆☆☆☆
  - 📄 Article: [Rollup Website and Docs](https://rollupjs.org/)
  - 🎥 Video: [How to Set Up JavaScript Bundling Using Rollup](https://www.youtube.com/watch?v=ICYLOZuFMz8)
- [ ] Rolldown — ☆☆☆☆☆
  - 🏛️ Official: [Rolldown Docs](https://rolldown.rs/guide/getting-started)
  - 💻 Open source: [rolldown](https://github.com/rolldown/rolldown)
  - 🎥 Video: [Rolldown: How Vite bundles at the speed of Rust](https://www.youtube.com/watch?v=3PFLeteDuyQ)
- [ ] Parcel — ☆☆☆☆☆
  - 🏛️ Official: [Parcel Website](https://parceljs.org/plugin-system/bundler/)
  - 🎥 Video: [How to Build a Web App with Parcel.js](https://www.youtube.com/watch?v=R02ehdTzi3I)

#### 🧠 Quiz

1. Why do we need a bundler?
   <details><summary>Answer</summary>To combine and optimize modules and assets for the browser: resolving imports, transpiling, minifying and code splitting.</details>

2. What is tree shaking?
   <details><summary>Answer</summary>Removing unused exports from the final bundle, which relies on static ES module imports.</details>

3. Why is Vite's dev server so fast?
   <details><summary>Answer</summary>It serves native ES modules on demand instead of bundling everything up front, and pre-bundles dependencies with esbuild.</details>

### 19. Auth Strategies — ☆☆☆☆☆

> Authentication strategies verify a user's identity to grant access. Common methods include Basic Auth (username/password), Session-based (server remembers login), Token-based (like JWT, a secure digital key), OAuth (for third-party access like "Login with Google"), and SSO (Single Sign-On, one login for many apps). Knowing these helps choose the right security for your app.

**📚 Learn:**

- 📄 Article: [Basic Authentication](https://roadmap.sh/guides/basic-authentication)
- 📄 Article: [Session Based Authentication](https://roadmap.sh/guides/session-based-authentication-visually-explained)
- 📄 Article: [Token Based Authentication](https://roadmap.sh/guides/token-authentication)
- 📄 Article: [JWT Authentication](https://roadmap.sh/guides/jwt-authentication)
- 📄 Article: [OAuth](https://roadmap.sh/guides/oauth)
- 📄 Article: [SSO - Single Sign On](https://roadmap.sh/guides/sso)

**✅ Checklist:**

- [ ] Auth Strategies — ☆☆☆☆☆

#### 🧠 Quiz

1. What is the difference between session-based and token-based (JWT) auth?
   <details><summary>Answer</summary>Sessions store state on the server and use a cookie ID; JWTs are self-contained signed tokens the client sends on each request.</details>

2. Why is storing tokens in localStorage risky?
   <details><summary>Answer</summary>Any XSS script can read them. HttpOnly, Secure, SameSite cookies are safer.</details>

3. What is OAuth used for?
   <details><summary>Answer</summary>Letting users log in or grant access via a third party (e.g. 'Sign in with Google') without sharing their password.</details>

### 20. Testing — ☆☆☆☆☆

> Testing verifies software functionality and quality through unit, integration, functional, UI/UX, performance, security, accessibility, and compatibility testing. Modern approaches use automated tools, CI/CD pipelines, TDD, and BDD methodologies. Early bug detection improves application reliability.

**📚 Learn:**

- 📄 Article: [The Different Types of Software Tests](https://www.atlassian.com/continuous-delivery/software-testing/types-of-software-testing)
- 🎥 Video: [How to Test Web Applications - dotJS 2024](https://www.youtube.com/watch?v=l3qjQpYBR8c)

**✅ Checklist:**

- [ ] Vitest — ☆☆☆☆☆
  - 🏛️ Official: [Vitest - Next Generation Testing Framework](https://vitest.dev/)
  - 🏛️ Official: [Vitest Documentation](https://vitest.dev/guide/)
  - 🎥 Video: [Vitest Simplified](https://www.youtube.com/watch?v=snCLQmINqCU)
- [ ] Jest — ☆☆☆☆☆
  - 🏛️ Official: [Jest Website](https://jestjs.io/)
  - 🎥 Video: [JavaScript Testing With Jest](https://youtu.be/IPiUDhwnZxA?si=2_lE2bDo2fRuo2CU)
- [ ] Playwright — ☆☆☆☆☆
  - 🏛️ Official: [Playwright Website](https://playwright.dev/)
  - 📄 Article: [Playwright, a Time-Saving End-to-End Testing Framework](https://thenewstack.io/playwright-a-time-saving-end-to-end-testing-framework/)
  - 🎥 Video: [Get started with end-to-end testing: Playwright](https://www.youtube.com/playlist?list=PLQ6Buerc008ed-F9OksF7ek37wR3y916p)
- [ ] Cypress — ☆☆☆☆☆
  - 🏛️ Official: [Cypress Website](https://www.cypress.io/)
  - 🏛️ Official: [Cypress Documentation](https://docs.cypress.io/)
  - 🎥 Video: [Cypress End-to-End Testing](https://www.youtube.com/watch?v=BQqzfHQkREo)

#### 🧠 Quiz

1. What is the difference between unit, integration and end-to-end tests?
   <details><summary>Answer</summary>Unit tests check a single function/component in isolation; integration tests check pieces working together; E2E tests run the whole app in a real browser like a user.</details>

2. Which tools fit which test type: Vitest, Jest, Playwright, Cypress?
   <details><summary>Answer</summary>Vitest/Jest for unit and integration tests; Playwright/Cypress for end-to-end browser tests.</details>

3. What is mocking and when is it useful?
   <details><summary>Answer</summary>Replacing a real dependency (API, timer, module) with a fake to make tests fast, isolated and deterministic.</details>

> Checkpoint: you should have the expertise of an intermediate level frontend developer.
> Project: Advanced Project Ideas

### 21. Web APIs — ☆☆☆☆☆

> Web APIs are interfaces provided by web browsers that allow JavaScript code to interact with the browser environment and the wider web. These APIs provide access to functionalities like manipulating the Document Object Model (DOM), handling user input, making network requests, managing browser history, and accessing device hardware like the camera or microphone. They essentially bridge the gap between JavaScript and the capabilities of the browser and the underlying operating system.

**📚 Learn:**

- 📄 Article: [Web APIs](https://developer.mozilla.org/en-US/docs/Web/API)
- 📄 Article: [Web APIs - Introduction](https://www.w3schools.com/js/js_api_intro.asp)
- 🎥 Video: [What is a Web API?](https://www.youtube.com/watch?v=_7rT-ixivWU)

**✅ Checklist:**

- [ ] Web APIs — ☆☆☆☆☆

#### 🧠 Quiz

1. What does fetch() return, and how do you get JSON from it?
   <details><summary>Answer</summary>A Promise of a Response; call await response.json() (and check response.ok for errors).</details>

2. What is the difference between localStorage and sessionStorage?
   <details><summary>Answer</summary>localStorage persists until cleared; sessionStorage is cleared when the tab closes.</details>

3. Name an API for running code off the main thread.
   <details><summary>Answer</summary>Web Workers.</details>

### 22. Web Security — ☆☆☆☆☆

> Web security protects websites from cyber threats through HTTPS/TLS, XSS/SQL injection/CSRF prevention, CSP, secure authentication, input validation, and regular updates. Involves understanding OWASP Top Ten vulnerabilities, access controls, secure coding practices, and threat awareness for comprehensive protection.

**📚 Learn:**

- 🏛️ Official: [OWASP Website](https://owasp.org/)
- 📄 Article: [OWASP Cheatsheets](https://cheatsheetseries.owasp.org/cheatsheets/AJAX_Security_Cheat_Sheet.html)
- 📄 Article: [Content Security Policy (CSP)](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP)
- 🎥 Video: [OWASP ZAP Step-by-Step Tutorial](https://www.youtube.com/playlist?list=PLH8n_ayg-60J9i3nsLybper-DR3zJw6Z5)

**✅ Checklist:**

- [ ] CORS — ☆☆☆☆☆
  - 📄 Article: [Cross-Origin Resource Sharing (CORS)](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)
  - 📄 Article: [Understanding CORS](https://rbika.com/blog/understanding-cors)
  - 🎥 Video: [CORS in 6 minutes](https://www.youtube.com/watch?v=PNtFSVU-YTI)
- [ ] HTTPS — ☆☆☆☆☆
  - 📄 Article: [What is HTTPS?](https://www.cloudflare.com/en-gb/learning/ssl/what-is-https/)
  - 📄 Article: [Why HTTPS Matters](https://developers.google.com/web/fundamentals/security/encrypt-in-transit/why-https)
  - 📄 Article: [Enabling HTTPS on Your Servers](https://web.dev/enable-https/)
  - 🎥 Video: [SSL, TLS, HTTP, HTTPS Explained](https://www.youtube.com/watch?v=hExRDVZHhig)
- [ ] CSP — ☆☆☆☆☆
  - 📄 Article: [MDN Content Security Policy (CSP)](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP)
  - 📄 Article: [Web.dev - Content Security Policy (CSP)](https://web.dev/csp/)
- [ ] OWASP Risks — ☆☆☆☆☆
  - 🏛️ Official: [OWASP Website](https://owasp.org/)
  - 🏛️ Official: [OWASP Cheatsheets](https://cheatsheetseries.owasp.org/cheatsheets/AJAX_Security_Cheat_Sheet.html)
  - 💻 Open source: [OWASP Web Application Security Testing Checklist](https://github.com/0xRadi/OWASP-Web-Checklist)
  - 📄 Article: [OWASP Top 10: A Guide to the Worst Software Vulnerabilities](https://thenewstack.io/owasp-top-10-a-guide-to-the-worst-software-vulnerabilities/)

#### 🧠 Quiz

1. What is CORS and who enforces it?
   <details><summary>Answer</summary>Cross-Origin Resource Sharing: the browser blocks cross-origin requests unless the server sends headers allowing them.</details>

2. What is XSS and how does CSP help?
   <details><summary>Answer</summary>Cross-Site Scripting injects malicious scripts into a page; a Content Security Policy restricts which scripts can run.</details>

3. Why is HTTPS important beyond encryption?
   <details><summary>Answer</summary>It also verifies the server's identity and prevents tampering; many browser features require it.</details>

### 23. SSR (Server-Side Rendering) — ☆☆☆☆☆

> Server-side rendering (SSR) generates complete HTML on the server before sending to browsers. Improves initial load times, SEO, and performance on slow devices. Frameworks: Next.js (React), Nuxt.js (Vue). Increases server load but enhances user experience.

**📚 Learn:**

- 📄 Article: [Server-Side Rendering (SSR)](https://vuejs.org/guide/scaling-up/ssr.html)
- 🎥 Video: [What are SSR & CSR](https://www.youtube.com/watch?v=ObrSuDYMl1s)
- 🎥 Video: [What is server-side rendering for web development?](https://www.youtube.com/watch?v=okvg3MRAPs0)

**✅ Checklist:**

- [ ] React — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated React Roadmap](https://roadmap.sh/react)
  - 🎓 Course: [Full Stack React Developer Course](https://www.youtube.com/watch?v=Bvwq_S0n2pk)
  - 🏛️ Official: [React Website](https://react.dev)
  - [ ] Next.js — ☆☆☆☆☆
    - 🗺️ Roadmap: [Visit the Dedicated Next.js Roadmap](https://roadmap.sh/nextjs)
    - 🏛️ Official: [Official Website](https://nextjs.org/)
    - 🎥 Video: [Next.js for Beginners](https://youtu.be/1WmNXEVia8I)
  - [ ] react-router — ☆☆☆☆☆
    - 🏛️ Official: [React Router Website](https://reactrouter.com/)
    - 📄 Article: [A Complete Guide to Routing in React](https://hygraph.com/blog/routing-in-react)
    - 🎥 Video: [React Router - Complete tutorial](https://www.youtube.com/watch?v=oTIJunBa6MA)
  - [ ] Tanstack Start — ☆☆☆☆☆
    - 🏛️ Official: [Tanstack Start Docs](https://tanstack.com/start/latest/docs/framework/react/overview)
    - 🏛️ Official: [Getting Started](https://tanstack.com/start/latest/docs/framework/react/getting-started)
    - 📄 Article: [An introduction to the TanStack Start framework](https://blog.logrocket.com/tanstack-start-overview/)
    - 🎥 Video: [TanStack Start Full Course 2025](https://www.youtube.com/watch?v=s4I4JtOZNgg)
  - [ ] Astro — ☆☆☆☆☆
    - 🎓 Course: [Astro Web Framework Crash Course](https://www.youtube.com/watch?v=e-hTm5VmofI)
    - 🏛️ Official: [Astro Website](https://astro.build/)
    - 📄 Article: [What is Astro?](https://www.contentful.com/blog/what-is-astro/)
- [ ] Vue.js — ☆☆☆☆☆
  - 🏛️ Official: [Vue.js Website](https://vuejs.org/)
  - 📄 Article: [Meet Vue.js, the Flexible JavaScript Framework](https://thenewstack.io/meet-vue-js-flexible-javascript-framework/)
  - 🎥 Video: [Vue.js Course for Beginners](https://www.youtube.com/watch?v=VeNfHj6MhgA)
  - [ ] Nuxt.js — ☆☆☆☆☆
    - 🎓 Course: [Nuxt.js Fundamentals](https://vueschool.io/courses/nuxtjs-fundamentals)
    - 🏛️ Official: [Nuxt Website](https://nuxtjs.org/)
    - 📄 Article: [Get Started with Nuxt](https://explorers.netlify.com/learn/get-started-with-nuxt)
- [ ] Angular — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated Angular Roadmap](https://roadmap.sh/angular)
  - 🏛️ Official: [Getting started with Angular](https://angular.dev/tutorials/learn-angular)
  - 🎥 Video: [Angular for Beginners Course](https://www.youtube.com/watch?v=3qBXWUpoPHo)
- [ ] SvelteKit — ☆☆☆☆☆
  - 🏛️ Official: [Svelte Kit](https://kit.svelte.dev/)
  - 🏛️ Official: [Svelte Kit Docs](https://kit.svelte.dev/docs/introduction)
  - 🎥 Video: [Sveltekit in 100 Seconds](https://www.youtube.com/watch?v=H1eEFfAkIik)

#### 🧠 Quiz

1. What is the difference between CSR and SSR?
   <details><summary>Answer</summary>CSR renders HTML in the browser with JS; SSR renders HTML on the server per request, so content shows faster and is SEO-friendly.</details>

2. What is hydration?
   <details><summary>Answer</summary>Attaching JavaScript event handlers and state to server-rendered HTML so it becomes interactive.</details>

3. Name the SSR meta-framework for React, Vue and Svelte.
   <details><summary>Answer</summary>Next.js (or React Router / TanStack Start) for React, Nuxt for Vue, SvelteKit for Svelte.</details>

### 24. SSG (Static Site Generation) — ☆☆☆☆☆

> Static Site Generators (SSGs) build websites as pre-generated HTML files from content and templates. Make sites fast, secure, and easy to host. Examples: Jekyll, Hugo, Eleventy. Ideal for blogs, documentation, and content-focused sites with excellent performance.

**📚 Learn:**

- 📄 Article: [What is a Static Site Generator?](https://www.cloudflare.com/learning/performance/static-site-generator/)
- 📄 Article: [Get Back to Basics With Static Website Generators](https://thenewstack.io/get-back-basics-static-website-generators/)
- 🎥 Video: [What is a static site generator](https://www.youtube.com/watch?v=Qms4k6y7OgI)

**✅ Checklist:**

- [ ] Astro — ☆☆☆☆☆
  - 🎓 Course: [Astro Web Framework Crash Course](https://www.youtube.com/watch?v=e-hTm5VmofI)
  - 🏛️ Official: [Getting Started with Astro](https://docs.astro.build/en/getting-started/)
  - 📄 Article: [What is Astro?](https://www.contentful.com/blog/what-is-astro/)
- [ ] Next.js — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated Next.js Roadmap](https://roadmap.sh/nextjs)
  - 🏛️ Official: [Next.js Website](https://nextjs.org/)
  - 🎥 Video: [Next.js for Beginners - Full Course at freeCodeCamp YouTube Channel](https://youtu.be/1WmNXEVia8I)
- [ ] Nuxt.js — ☆☆☆☆☆
  - 🎓 Course: [Nuxt.js Fundamentals](https://vueschool.io/courses/nuxtjs-fundamentals)
  - 🏛️ Official: [Nuxt Website](https://nuxtjs.org/)
  - 📄 Article: [Get Started with Nuxt](https://explorers.netlify.com/learn/get-started-with-nuxt)
- [ ] Vuepress — ☆☆☆☆☆
  - 🏛️ Official: [Vuepress](https://vuepress.vuejs.org/)
  - 🎥 Video: [What is VuePress?](https://www.youtube.com/watch?v=iRhRdY7SQJg)
- [ ] Eleventy — ☆☆☆☆☆
  - 🏛️ Official: [Eleventy](https://www.11ty.dev/)
  - 🏛️ Official: [A collection of 11ty starters, projects, plugins, and resources](https://11ty.rocks/)
  - 🎥 Video: [Introduction to Eleventy](https://www.youtube.com/watch?v=-dM6AmNmMFA)

#### 🧠 Quiz

1. What is the difference between SSG and SSR?
   <details><summary>Answer</summary>SSG generates HTML at build time once; SSR generates it on each request.</details>

2. What kinds of sites suit SSG best?
   <details><summary>Answer</summary>Content that rarely changes: blogs, docs, marketing and portfolio sites.</details>

3. What is the 'islands architecture' used by Astro?
   <details><summary>Answer</summary>Pages are static HTML by default, and only specific interactive components ('islands') ship JavaScript.</details>

### 25. Type Checkers — ☆☆☆☆☆

> Type checkers are tools that analyze code to verify that the types of values used in a program are consistent with their declared or inferred types. They help catch type-related errors during development, before the code is run, by identifying mismatches between expected and actual data types. This process ensures that operations are performed on compatible data, reducing the likelihood of runtime errors and improving code reliability.

**📚 Learn:**

- 📄 Article: [Type checking](https://finchtrade.com/glossary/type-checking)

**✅ Checklist:**

- [ ] TypeScript — ☆☆☆☆☆
  - 🏛️ Official: [TypeScript Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
  - 🗺️ Roadmap: [Visit the Dedicated TypeScript Roadmap](https://roadmap.sh/typescript)

#### 🧠 Quiz

1. What is the difference between interface and type in TypeScript?
   <details><summary>Answer</summary>Both describe shapes; interfaces can be extended and merged, while type aliases can also express unions, intersections and primitives.</details>

2. What is the difference between any and unknown?
   <details><summary>Answer</summary>any disables type checking; unknown forces you to narrow the type before using it, so it's safer.</details>

3. What are generics?
   <details><summary>Answer</summary>Type parameters that let functions and types work with many types while keeping type safety, e.g. function first&lt;T&gt;(arr: T[]): T.</details>

### 26. Deployment — ☆☆☆☆☆

> Deployment is the process of making a website or web application available for users to access on the internet. It involves taking the code, assets (like images and fonts), and configuration files and placing them on a server or hosting platform. This process often includes steps like bundling the code, optimizing assets for performance, and configuring the server to properly serve the application.

**📚 Learn:**

- 📄 Article: [A Beginner’s Guide To Web Deployment](https://medium.com/devjavu/a-beginners-guide-to-web-deployment-b4ce704fe097)
- 📄 Article: [Deploying frontend applications — the fun way](https://hackernoon.com/deploying-frontend-applications-the-fun-way-bc3f69e15331)
- 📄 Article: [Top 5 Platforms to Deploy Your Frontend Projects](https://strapi.io/blog/top-platforms-for-frontend-projects)
- 🎥 Video: [How To Deploy a Website (to the internet)](https://www.youtube.com/watch?v=NBrQp6-721c)

**✅ Checklist:**

- [ ] GitHub Pages — ☆☆☆☆☆
  - 🏛️ Official: [GitHub Pages Documentation](https://docs.github.com/en/pages)
  - 🏛️ Official: [GitHub Pages Quickstart](https://docs.github.com/en/pages/quickstart)
  - 📄 Article: [How do I use GitHub Pages?](https://developer.mozilla.org/en-US/docs/Learn_web_development/Howto/Tools_and_setup/Using_GitHub_pages)
  - 🎥 Video: [GitHub Pages - Full Tutorial](https://www.youtube.com/watch?v=o5g-lUuFgpg)
- [ ] Vercel — ☆☆☆☆☆
  - 🏛️ Official: [Vercel Documentation](https://vercel.com/docs)
  - 🏛️ Official: [Vercel Quick Start](https://vercel.com/docs/getting-started-with-vercel)
  - 🎥 Video: [Vercel Tutorial - Host a Website for Free](https://www.youtube.com/watch?v=Vx5nPGdsFaU)
- [ ] Netlify — ☆☆☆☆☆
  - 🏛️ Official: [Netlify Docs](https://docs.netlify.com/)
  - 🏛️ Official: [Get Started with Netlify](https://docs.netlify.com/start/get-started-guide/)
  - 🎥 Video: [Getting started with Netlify Edge Functions](https://www.youtube.com/watch?v=6pEVhH37xQE&list=PLzlG0L9jlhEPMR8haUPkxj2hJ_3jh5qa6)
  - 🎥 Video: [Netlify Dev Crash Course | Easy Dev & Deploy](https://www.youtube.com/watch?v=FMhVXOA54x8)
- [ ] Cloudflare — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated Cloudflare Roadmap](https://roadmap.sh/cloudflare)
  - 🏛️ Official: [Getting started](https://developers.cloudflare.com/pages/get-started/)
  - 🎥 Video: [What is Cloudflare?](https://www.youtube.com/watch?v=XHvmX3FhTwU)
  - 🎥 Video: [Learn Cloudflare Workers 101 - Full Course for Beginners](https://www.youtube.com/watch?v=H7Qe96fqg1M)
- [ ] Railway — ☆☆☆☆☆
  - 🏛️ Official: [Railway](https://railway.com/)
  - 🏛️ Official: [Quick Start Tutorial](https://docs.railway.com/quick-start)
  - 🎥 Video: [Fastest Way to Deploy a Full Stack Web App (Railway)](https://www.youtube.com/watch?v=JQIKobOcQ9k)
  - 🎥 Video: [Intro to Railway - Config Free Deploys](https://www.youtube.com/watch?v=DyQz2DgSToU)
- [ ] Render — ☆☆☆☆☆
  - 🏛️ Official: [Render](https://render.com/)
  - 🏛️ Official: [Render Docs + Quickstarts](https://render.com/docs)
  - 📄 Article: [Render: Cloud Deployment with Less Engineering](https://thenewstack.io/render-cloud-deployment-with-less-engineering/)
  - 🎥 Video: [Deploy any application with one click using Render](https://www.youtube.com/watch?v=yWxBUcG_C7g)

#### 🧠 Quiz

1. What is a preview deployment?
   <details><summary>Answer</summary>An automatic deployment of each branch/PR to a unique URL so changes can be reviewed before merging.</details>

2. Why do you need to configure a fallback/rewrite for single-page apps?
   <details><summary>Answer</summary>So any route (e.g. /about) serves index.html and the client-side router can handle it, instead of returning 404.</details>

3. Where should secrets like API keys live when deploying?
   <details><summary>Answer</summary>In the platform's environment variables, never committed to the repository or shipped to the client.</details>

### 27. Design Systems — ☆☆☆☆☆

> A design system is a structured collection of reusable components, guidelines, standards, and best practices that ensure consistency across an application's visual design and user experience. It typically includes typography, colors, spacing, icons, UI components, interaction patterns, and documentation on how to use everything correctly.

**📚 Learn:**

- 🗺️ Roadmap: [Visit the Dedicated Design System Roadmap](https://roadmap.sh/design-system)
- 📄 Article: [Design system 101: What is a design system?](https://www.figma.com/blog/design-systems-101-what-is-a-design-system/)
- 📄 Article: [Design Systems 101](https://www.nngroup.com/articles/design-systems-101/)
- 🎥 Video: [Welcome to design systems - Lesson 1 : Introduction to design systems](https://www.youtube.com/watch?v=YLo6g58vUm0)

**✅ Checklist:**

- [ ] Design Systems — ☆☆☆☆☆

#### 🧠 Quiz

1. What is a design system?
   <details><summary>Answer</summary>A shared set of reusable components, design tokens, guidelines and documentation that keeps a product consistent.</details>

2. What are design tokens?
   <details><summary>Answer</summary>Named values for design decisions (colors, spacing, typography), e.g. --color-primary, used across code and design tools.</details>

3. Name a tool for developing and documenting components in isolation.
   <details><summary>Answer</summary>Storybook.</details>

### 28. Performance — ☆☆☆☆☆

> Performance, in the context of web development, refers to how quickly and efficiently a website or web application loads and responds to user interactions. It encompasses various aspects like loading times, rendering speed, and overall responsiveness. Optimizing performance ensures a smooth and enjoyable user experience, leading to increased engagement and satisfaction.

**📚 Learn:**

- 📄 Article: [Web performance](https://developer.mozilla.org/en-US/docs/Web/Performance)
- 📄 Article: [9 Essential Strategies for Web Performance Optimization](https://www.shopify.com/enterprise/blog/web-performance-optimization)
- 🎥 Video: [The ultimate guide to web performance](https://www.youtube.com/watch?v=0fONene3OIA)
- 🎥 Video: [Frontend System Design: The 2025 Web Performance Roadmap](https://www.youtube.com/watch?v=KUdqbIHn8Ic)

**✅ Checklist:**

- [ ] Lighthouse — ☆☆☆☆☆
  - 🏛️ Official: [Introduction to Lighthouse](https://developer.chrome.com/docs/lighthouse/overview)
  - 💻 Open source: [lighthouse](https://github.com/GoogleChrome/lighthouse)
  - 📄 Article: [Google Lighthouse: What It Is & How to Use It](https://www.semrush.com/blog/google-lighthouse/)
  - 🎥 Video: [What Is Google Lighthouse and How to Use It?](https://www.youtube.com/watch?v=VyaHwvPWuZU)
- [ ] DevTools Usage — ☆☆☆☆☆
  - 📄 Article: [What are browser developer tools?](https://developer.mozilla.org/en-US/docs/Learn_web_development/Howto/Tools_and_setup/What_are_browser_developer_tools)
  - 📄 Article: [What are Developer Tools?](https://aws.amazon.com/what-is/developer-tools/)
  - 📄 Article: [Google DevTools](https://developer.chrome.com/docs/devtools)
  - 🎥 Video: [Understand Browser Dev Tools Network Tab (and avoid these mistakes...)](https://www.youtube.com/watch?v=2CC0fugc_2o)
- [ ] Service Workers — ☆☆☆☆☆
  - 📄 Article: [Service Worker API](https://developer.mozilla.org/en-US/docs/Web/API/Service_Worker_API)
  - 📄 Article: [Service workers](https://web.dev/learn/pwa/service-workers)
  - 📄 Article: [Service worker overview - Chrome](https://developer.chrome.com/docs/workbox/service-worker-overview)
  - 🎥 Video: [What is a service workers](https://www.youtube.com/watch?v=A6MHtKkA0CA)
- [ ] Cache-Control — ☆☆☆☆☆
  - 📄 Article: [Cache-Control header](https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Headers/Cache-Control)
  - 📄 Article: [What is cache-control? | Cache explained](https://www.cloudflare.com/en-gb/learning/cdn/glossary/what-is-cache-control/)
  - 🎥 Video: [Two-Minute Tech Tuesdays - Cache-Control Header](https://www.youtube.com/watch?v=8TBWJo094yA)
  - 🎥 Video: [Deep Dive into HTTP Caching](https://www.youtube.com/watch?v=Cy2ZJOBgk84)
- [ ] Streamed Responses — ☆☆☆☆☆
  - 📄 Article: [Streams API](https://developer.mozilla.org/en-US/docs/Web/API/Streams_API)
  - 📄 Article: [Streaming API responses for AI - OpenAI](https://platform.openai.com/docs/guides/streaming-responses)
  - 📄 Article: [Streaming Responses in AI](https://dev.to/pranshu_kabra_fe98a73547a/streaming-responses-in-ai-how-ai-outputs-are-generated-in-real-time-18kb)

#### 🧠 Quiz

1. What are the Core Web Vitals?
   <details><summary>Answer</summary>LCP (loading), INP (interactivity) and CLS (visual stability).</details>

2. Name three ways to make a page load faster.
   <details><summary>Answer</summary>E.g. compress and lazy-load images, code-split JS, cache assets with Cache-Control, use a CDN, reduce render-blocking resources.</details>

3. What does Cache-Control: max-age=31536000, immutable mean?
   <details><summary>Answer</summary>The browser can cache the file for a year without revalidating; used for hashed/fingerprinted asset filenames.</details>

### 29. Web Components — ☆☆☆☆☆

> Web Components create reusable HTML elements using Custom Elements, Shadow DOM, and HTML Templates. Work across browsers and frameworks with encapsulated styles and structure. Enable modular, shareable code with reduced style conflicts. Standard for building interoperable web parts.

**📚 Learn:**

- 📄 Article: [Web Components - MDN](https://developer.mozilla.org/en-US/docs/Web/Web_Components)
- 📄 Article: [WebComponents.org](https://webcomponents.github.io/)
- 🎥 Video: [Web Components Crash Course](https://www.youtube.com/watch?v=PCWaFLy3VUo)

**✅ Checklist:**

- [ ] HTML Templates — ☆☆☆☆☆
  - 📄 Article: [Using Templates and Slots - MDN](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_templates_and_slots)
- [ ] Custom Elements — ☆☆☆☆☆
  - 📄 Article: [Using Custom Elements - MDN](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_custom_elements)
  - 🎥 Video: [Web Components | Custom Elements](https://www.youtube.com/watch?v=1GT35DSdZbI)
- [ ] Shadow DOM — ☆☆☆☆☆
  - 📄 Article: [Using shadow DOM | MDN web docs](https://developer.mozilla.org/en-US/docs/Web/Web_Components/Using_shadow_DOM)
  - 🎥 Video: [DOM vs Virtual DOM vs Shadow DOM](https://youtu.be/7Tok22qxPzQ?si=2cw36PNSgFTcNHWx)

#### 🧠 Quiz

1. What are the three main technologies behind Web Components?
   <details><summary>Answer</summary>Custom Elements, Shadow DOM and HTML Templates.</details>

2. What does the Shadow DOM give you?
   <details><summary>Answer</summary>Encapsulation: the component's markup and styles are isolated from the rest of the page.</details>

3. What naming rule must custom element names follow?
   <details><summary>Answer</summary>They must contain a hyphen, e.g. &lt;my-button&gt;.</details>

### 30. GraphQL — ☆☆☆☆☆

> GraphQL is Facebook's query language for APIs allowing clients to request exactly the data needed. Reduces over-fetching and under-fetching compared to REST. Ideal for mobile applications, complex APIs, and rapidly changing requirements with strong typing.

**📚 Learn:**

- 🗺️ Roadmap: [Visit Dedicated GraphQL Roadmap](https://roadmap.sh/graphql)
- 🏛️ Official: [Introduction to GraphQL](https://graphql.org/learn/)
- 📄 Article: [Introduction to GraphQL](https://thenewstack.io/introduction-to-graphql/)
- 🎥 Video: [GraphQL Course for Beginners](https://www.youtube.com/watch?v=ed8SzALpx1Q)

**✅ Checklist:**

- [ ] Apollo — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated GraphQL Roadmap](https://roadmap.sh/graphql)
  - 🏛️ Official: [Apollo Website](https://www.apollographql.com)
  - 🏛️ Official: [Apollo Docs](https://www.apollographql.com/docs/)
- [ ] Relay Modern — ☆☆☆☆☆
  - 🏛️ Official: [Relay Website](https://relay.dev/)
  - 💻 Open source: [facebook/relay](https://github.com/facebook/relay)
  - 🎥 Video: [ELI5 - Relay](https://www.youtube.com/watch?v=A4POd93GI_I)

#### 🧠 Quiz

1. How does GraphQL differ from REST?
   <details><summary>Answer</summary>Clients ask for exactly the fields they need from a single endpoint, avoiding over- and under-fetching.</details>

2. What is the difference between a query and a mutation?
   <details><summary>Answer</summary>Queries read data; mutations change data.</details>

3. What does a GraphQL client like Apollo or Relay add?
   <details><summary>Answer</summary>Caching, loading/error states, and hooks to bind query results to components.</details>

### 31. Accessibility — ☆☆☆☆☆

> Website accessibility ensures sites are usable by everyone, including people with disabilities. Involves alt text for images, keyboard navigation, color contrast, and captions. Benefits all users, supports legal compliance, and expands audience reach.

**📚 Learn:**

- 📄 Article: [Accessibility for Developers by Google](https://web.dev/accessibility)
- 🎥 Video: [Complete Playlist on Accessibility](https://youtube.com/playlist?list=PLNYkxOF6rcICWx0C9LVWWVqvHlYJyqw7g)

**✅ Checklist:**

- [ ] Accessibility — ☆☆☆☆☆

#### 🧠 Quiz

1. What is the first rule of ARIA?
   <details><summary>Answer</summary>Don't use ARIA if a native HTML element already provides the semantics and behavior (e.g. use &lt;button&gt;, not &lt;div role="button"&gt;).</details>

2. How can you check your site works with the keyboard only?
   <details><summary>Answer</summary>Navigate with Tab/Shift+Tab/Enter/Space: every interactive element must be reachable, have a visible focus style and work.</details>

3. What contrast ratio does WCAG AA require for normal text?
   <details><summary>Answer</summary>At least 4.5:1.</details>

### 32. PWAs — ☆☆☆☆☆

> Progressive Web Apps (PWAs) are web applications behaving like native apps using HTML, CSS, JavaScript. Feature offline functionality, push notifications, home screen installation, and service workers for caching. Cross-platform, discoverable, and cost-effective alternative to native apps.

**📚 Learn:**

- 📄 Article: [Learn PWA](https://web.dev/learn/pwa/)
- 📄 Article: [MDN - Progressive Web Apps](https://developer.mozilla.org/en-US/docs/Web/Progressive_web_apps/)
- 🎥 Video: [Progressive Web Apps in 2024](https://www.youtube.com/watch?v=3ODP6tTpjqA)

**✅ Checklist:**

- [ ] PWAs — ☆☆☆☆☆

#### 🧠 Quiz

1. What makes a web app a PWA?
   <details><summary>Answer</summary>HTTPS, a web app manifest, and a service worker, making it installable and able to work offline.</details>

2. What does a service worker do?
   <details><summary>Answer</summary>Acts as a programmable network proxy in the background: caching, offline support, push notifications.</details>

3. What is the web app manifest for?
   <details><summary>Answer</summary>A JSON file describing the app's name, icons, colors and display mode for installation.</details>

### 33. Mobile Apps — ☆☆☆☆☆

> Mobile applications are software programs designed to run specifically on smartphones, tablets, and other portable handheld devices. They are typically accessed through dedicated app stores and are developed to leverage device-specific features like GPS, cameras, and push notifications to provide an optimized user experience. While native apps are built with platform-specific languages, developers can also use cross-platform frameworks to write a single codebase that deploys across both iOS and Android environments.

**📚 Learn:**

- 🏛️ Official: [React Native](https://reactnative.dev/)
- 🏛️ Official: [Flutter](https://flutter.dev)
- 🏛️ Official: [Ionic](https://ionicframework.com)
- 🏛️ Official: [NativeScript](https://nativescript.org/)

**✅ Checklist:**

- [ ] React Native — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated React Roadmap](https://roadmap.sh/react-native)
  - 🏛️ Official: [React Native Website](https://reactnative.dev/)
- [ ] Flutter — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated Flutter Roadmap](https://roadmap.sh/flutter)
  - 🎓 Course: [Flutter course for beginners](https://www.youtube.com/watch?v=VPvVD8t02U8)
  - 🏛️ Official: [Flutter for Desktop](https://flutter.dev/multi-platform/desktop)
  - 📄 Article: [12 Ways Flutter Streamlines App Development](https://thenewstack.io/12-ways-flutter-streamlines-app-development/)
- [ ] Ionic — ☆☆☆☆☆
  - 🏛️ Official: [Ionic Docs](https://ionicframework.com/docs)
  - 🎥 Video: [Ionic Tutorial](https://www.youtube.com/watch?v=5Gj4Y8zvl-s&list=PLlyAM-8-I7S9iNcZRfP4SQJhm4Mw5q5ku)

#### 🧠 Quiz

1. How does React Native differ from a web app in a WebView?
   <details><summary>Answer</summary>React Native renders real native UI components, while a WebView app (e.g. Ionic/Capacitor) renders HTML inside a native shell.</details>

2. What language does Flutter use?
   <details><summary>Answer</summary>Dart.</details>

3. Name one reason to build a native/cross-platform app instead of a PWA.
   <details><summary>Answer</summary>Better access to device APIs, app-store distribution, or native performance and look-and-feel.</details>

### 34. Desktop Apps — ☆☆☆☆☆

> JavaScript builds desktop apps using Electron, NW.js, or Tauri for cross-platform development (Windows, Mac, Linux). Electron powers VS Code and Discord. Provides file system access and native integration. Trade-offs: faster development vs. performance and resource usage compared to native apps.

**📚 Learn:**

- 🏛️ Official: [Electron Website](https://www.electronjs.org/)
- 🏛️ Official: [NW.js Website](https://nwjs.io/)
- 🏛️ Official: [Tauri Website](https://tauri.app/)

**✅ Checklist:**

- [ ] Electron — ☆☆☆☆☆
  - 🏛️ Official: [Electron Website](https://www.electronjs.org/)
  - 🏛️ Official: [Electron Docs](https://www.electronjs.org/docs/latest/)
  - 🎥 Video: [Create a Desktop App With JavaScript & Electron](https://www.youtube.com/watch?v=ML743nrkMHw)
- [ ] Tauri — ☆☆☆☆☆
  - 🏛️ Official: [Tauri Website](https://tauri.app/)
  - 🏛️ Official: [Tauri Docs](https://tauri.app/v1/guides/)
  - 📄 Article: [How Tauri Turns Web Designs into Compact Native Apps](https://thenewstack.io/how-tauri-turns-web-designs-into-compact-native-apps/)
- [ ] Flutter — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated Flutter Roadmap](https://roadmap.sh/flutter)
  - 🎓 Course: [Flutter course for beginners](https://www.youtube.com/watch?v=VPvVD8t02U8)
  - 🏛️ Official: [Flutter for Desktop](https://flutter.dev/multi-platform/desktop)
  - 📄 Article: [12 Ways Flutter Streamlines App Development](https://thenewstack.io/12-ways-flutter-streamlines-app-development/)

#### 🧠 Quiz

1. How does Electron work?
   <details><summary>Answer</summary>It bundles Chromium and Node.js so you build desktop apps with web technologies.</details>

2. Why might you choose Tauri over Electron?
   <details><summary>Answer</summary>Much smaller and lighter apps: it uses the OS's native webview and a Rust backend instead of shipping Chromium.</details>

3. What security concern is common in Electron apps?
   <details><summary>Answer</summary>Exposing Node.js APIs to untrusted web content; use contextIsolation and disable nodeIntegration in renderers.</details>

