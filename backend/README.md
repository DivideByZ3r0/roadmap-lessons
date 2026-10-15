# Backend Developer Roadmap — Lessons

**How to use:** tick `[x]` when done, and rate yourself by replacing ☆ with ★ (★☆☆☆☆ = just heard of it · ★★★★★ = can teach it). Quiz answers are hidden — click *Answer* to reveal.

Source: https://roadmap.sh/backend (lesson order follows the roadmap)

---

## 1. Introduction — ☆☆☆☆☆

> Backend development focuses on the server-side logic of a web application, handling data storage, processing, and security. It involves building and maintaining the infrastructure that powers the user-facing frontend, ensuring seamless communication between the client and the database. This includes tasks like creating APIs, managing databases, and implementing authentication and authorization mechanisms.

**📚 Learn:**

- 📄 Article: [What is backend? A comprehensive intro to server-side development](https://alokai.com/blog/what-is-backend)
- 📄 Article: [What is Back-End Architecture?](https://www.codecademy.com/article/what-is-back-end-architecture)
- 🎥 Video: [Backend web development - a complete overview](https://www.youtube.com/watch?v=XBu54nfzxAQ)
- 🎥 Video: [How The Backend Works](https://www.youtube.com/watch?v=4r6WdaY3SOA)

**✅ Checklist:**

- [ ] How does the internet work? — ☆☆☆☆☆
  - 📄 Article: [How does the Internet Work?](https://cs.fyi/guide/how-does-internet-work)
  - 📄 Article: [The Internet Explained](https://www.vox.com/2014/6/16/18076282/the-internet)
  - 🎥 Video: [How does the internet work? (Full Course)](https://www.youtube.com/watch?v=zN8YNNHcaZc)
- [ ] What is HTTP? — ☆☆☆☆☆
  - 🎓 Course: [Full HTTP Networking Course](https://www.youtube.com/watch?v=2JYT5f2isg4)
  - 📄 Article: [What is HTTP?](https://www.cloudflare.com/en-gb/learning/ddos/glossary/hypertext-transfer-protocol-http/)
  - 📄 Article: [HTTP/3 From A To Z: Core Concepts](https://www.smashingmagazine.com/2021/08/http3-core-concepts-part1/)
  - 🎥 Video: [HTTP/1 to HTTP/2 to HTTP/3](https://www.youtube.com/watch?v=a-sBfyiXysI)
- [ ] What is Domain Name? — ☆☆☆☆☆
  - 📄 Article: [What is a Domain Name?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_domain_name)
  - 📄 Article: [What is a Domain Name? | Domain name vs. URL](https://www.cloudflare.com/en-gb/learning/dns/glossary/what-is-a-domain-name/)
  - 🎥 Video: [A Beginners Guide to How Domain Names Work](https://www.youtube.com/watch?v=Y4cRx19nhJk)
  - 🎥 Video: [Everything You Need to Know About Domain Names](https://www.youtube.com/watch?v=qO5qcQgiNX4)
- [ ] What is hosting? — ☆☆☆☆☆
  - 📄 Article: [What is the difference between Webpage, Website, Web server, and search engine?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/Pages_sites_servers_and_search_engines)
  - 📄 Article: [What is a web server?](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/Web_mechanics/What_is_a_web_server)
  - 🎥 Video: [What is Web Hosting and How Does It Work?](https://www.youtube.com/watch?v=H8oAvyqQwew)
  - 🎥 Video: [Different Types of Web Hosting Explained](https://www.youtube.com/watch?v=AXVZYzw8geg)
- [ ] DNS and how it works? — ☆☆☆☆☆
  - 📄 Article: [Everything You Need to Know About DNS](https://cs.fyi/guide/everything-you-need-to-know-about-dns)
  - 📄 Article: [What is DNS?](https://www.cloudflare.com/en-gb/learning/dns/what-is-dns/)
  - 📄 Article: [How DNS works (comic)](https://howdns.works/)
  - 🎥 Video: [DNS and How does it Work?](https://www.youtube.com/watch?v=Wj0od2ag5sk)
- [ ] Browsers and how they work? — ☆☆☆☆☆
  - 📄 Article: [How Browsers Work](https://www.ramotion.com/blog/what-is-web-browser/)
  - 📄 Article: [Populating the Page: How Browsers Work](https://developer.mozilla.org/en-US/docs/Web/Performance/How_browsers_work)
  - 🎥 Video: [How Do Web Browsers Work?](https://www.youtube.com/watch?v=5rLFYtXHo9s)

### 🧠 Quiz

1. What happens when a browser requests https://example.com?
   <details><summary>Answer</summary>DNS resolves the domain to an IP, the browser opens a TCP + TLS connection, sends an HTTP request, the server responds, and the browser renders the response.</details>

2. What is the difference between GET and POST?
   <details><summary>Answer</summary>GET retrieves data and should have no side effects (idempotent, cacheable); POST sends data to create or process something.</details>

3. What is the difference between TCP and UDP?
   <details><summary>Answer</summary>TCP is connection-based and reliable (ordered, retransmitted); UDP is connectionless and faster but with no delivery guarantees.</details>

---

## 2. Frontend Basics — ☆☆☆☆☆

> Frontend basics encompass the core technologies and principles used to build the user interface of a web application. This includes HTML for structuring content, CSS for styling and visual presentation, and JavaScript for adding interactivity and dynamic behavior. Understanding these fundamentals is crucial for backend developers to effectively collaborate with frontend teams, design APIs that cater to frontend needs, and troubleshoot issues that may arise between the client and server sides.

**📚 Learn:**

- 🗺️ Roadmap: [Visit the dedicated Frontend Developer Roadmap](https://roadmap.sh/frontend)
- 📄 Article: [What Is Front-End Development?](https://cloudinary.com/guides/front-end-development/front-end-development-the-complete-guide)
- 🎥 Video: [Frontend web development - a complete overview](https://www.youtube.com/watch?v=WG5ikvJ2TKA)

**✅ Checklist:**

- [ ] HTML — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the dedicated HTML roadmap](https://roadmap.sh/html)
  - 📄 Article: [Responsive Web Design Certification - Co-Learn HTML & CSS with guided projects](https://www.freecodecamp.org/learn/2022/responsive-web-design/)
  - 🎥 Video: [HTML Full Course for Beginners](https://www.youtube.com/watch?v=mJgBOIoGihA)
  - 🎥 Video: [HTML Full Course - Build a Website Tutorial](https://www.youtube.com/watch?v=pQN-pnXPaVg)
- [ ] CSS — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated CSS Roadmap](https://roadmap.sh/css)
  - 📄 Article: [CSS MDN Docs](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/What_is_CSS)
  - 🎥 Video: [CSS Tutorial – Full Course for Beginners](https://www.youtube.com/watch?v=OXGznpKZ_sA)
- [ ] JavaScript — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated JavaScript Roadmap](https://roadmap.sh/javascript)
  - 📚 Book: [JavaScript from Beginner to Professional](https://www.gurukultti.org/admin/notice/javascript.pdf)
  - 📄 Article: [The Modern JavaScript Tutorial](https://javascript.info/)
  - 🎥 Video: [JavaScript Crash Course For Beginners](https://www.youtube.com/watch?v=hdI2bqOjy3c&t=4s)

### 🧠 Quiz

1. Why should a backend developer know HTML, CSS and JavaScript?
   <details><summary>Answer</summary>To understand how clients consume APIs, build simple UIs, debug integration issues and communicate with frontend developers.</details>

2. What does a browser do with the HTML a server returns?
   <details><summary>Answer</summary>Parses it into the DOM, loads referenced CSS/JS, then lays out and paints the page.</details>

3. What is the difference between server-side and client-side rendering?
   <details><summary>Answer</summary>Server-side sends ready HTML; client-side sends JS that builds the HTML in the browser.</details>

---

## 3. Pick a Backend Language — ☆☆☆☆☆

> Web development divides into Frontend (HTML, CSS, JavaScript) and Backend Development. Backend uses server-side languages like Python, Java, or Node.js, complemented by databases, frameworks, and web servers for website functionality. Choose a language based on project needs and preferences.

**✅ Checklist:**

- [ ] JavaScript — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated JavaScript Roadmap](https://roadmap.sh/javascript)
  - 📄 Article: [The Modern JavaScript Tutorial](https://javascript.info/)
  - 📄 Article: [Build 30 Javascript Projects in 30 days](https://javascript30.com/)
  - 🎥 Video: [JavaScript Crash Course for Beginners](https://youtu.be/hdI2bqOjy3c?t=2)
- [ ] Go — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated Go Roadmap](https://roadmap.sh/golang)
  - 🏛️ Official: [Go Reference Documentation](https://go.dev/doc/)
  - 📄 Article: [Go by Example - annotated example programs](https://gobyexample.com/)
  - 🎥 Video: [Go Programming – Golang Course with Bonus Projects](https://www.youtube.com/watch?v=un6ZyFkqFKo)
- [ ] Python — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated Python Roadmap](https://roadmap.sh/python)
  - 🎓 Course: [Python Full Course for free](https://www.youtube.com/watch?v=ix9cRaBkVe0)
  - 🏛️ Official: [Python Website](https://www.python.org/)
  - 📄 Article: [Automate the Boring Stuff](https://automatetheboringstuff.com/)
- [ ] Ruby — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated Ruby Roadmap](https://roadmap.sh/ruby)
  - 📄 Article: [Learn Ruby in 20 minutes](https://www.ruby-lang.org/en/documentation/quickstart/)
  - 📄 Article: [Ruby, An Introduction to a Programmer’s Best Friend](https://thenewstack.io/ruby-a-programmers-best-friend/)
  - 🎥 Video: [Ruby Comprehensive courses](https://www.youtube.com/playlist?list=PL_EzhIKp343lBMH4UuklrMRL_WkilGoXe)
- [ ] Java — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated Java Roadmap](https://roadmap.sh/java)
  - 🏛️ Official: [Java Website](https://www.java.com/)
  - 🎥 Video: [Complete Java course](https://www.youtube.com/watch?v=xk4_1vDrzzo)
- [ ] C# — ☆☆☆☆☆
  - 🎓 Course: [C# Learning Path](https://docs.microsoft.com/en-us/learn/paths/csharp-first-steps/?WT.mc_id=dotnet-35129-website)
  - 🏛️ Official: [C# Tour](https://learn.microsoft.com/en-us/dotnet/csharp/tour-of-csharp/)
  - 🎥 Video: [Learn C# Programming – Full Course with Mini-Projects](https://www.youtube.com/watch?v=YrtFtdTTfv0)
- [ ] PHP — ☆☆☆☆☆
  - 🏛️ Official: [Visit Dedicated PHP Roadmap](https://roadmap.sh/php)
  - 🏛️ Official: [PHP](https://php.net/)
  - 📄 Article: [PHP - The Right Way](https://phptherightway.com/)
  - 🎥 Video: [PHP for Beginners](https://www.youtube.com/watch?v=zZ6vybT1HQs)
- [ ] Rust — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated Rust Roadmap](https://roadmap.sh/rust)
  - 🏛️ Official: [The Rust Programming Language - Book](https://doc.rust-lang.org/book/)
  - 📄 Article: [Rust vs. Go: Why They’re Better Together](https://thenewstack.io/rust-vs-go-why-theyre-better-together/)
  - 🎥 Video: [Learn Rust Programming](https://www.youtube.com/watch?v=BpPEoZW5IiY)

### 🧠 Quiz

1. What is the difference between a compiled and an interpreted language?
   <details><summary>Answer</summary>Compiled languages (Go, Rust) are translated to machine code ahead of time; interpreted ones (Python, Ruby) are executed by an interpreter at runtime (often with JIT/bytecode in between).</details>

2. Why is Node.js good at handling many concurrent I/O requests?
   <details><summary>Answer</summary>It uses a non-blocking, event-driven model, so one thread can handle many connections while waiting on I/O.</details>

3. Name a strength of Go for backend services.
   <details><summary>Answer</summary>Simple language, fast compilation, a single static binary, and lightweight concurrency with goroutines and channels.</details>

---

## 4. Version Control Systems — ☆☆☆☆☆

> Version Control Systems (VCS) manage and track code changes over time, enabling efficient collaboration. Record file changes, allow reverting to previous versions, and maintain modification history. Can be centralized (Subversion) or distributed (Git, Mercurial) for collaboration and code integrity.

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

### 🧠 Quiz

1. Why use version control?
   <details><summary>Answer</summary>To track history, collaborate safely, review changes, and roll back mistakes.</details>

2. What is a branch in Git?
   <details><summary>Answer</summary>A movable pointer to a commit that lets you develop features in isolation.</details>

3. What is a merge conflict and how do you resolve it?
   <details><summary>Answer</summary>When two branches change the same lines differently; you edit the file to choose the correct result, then add and commit.</details>

---

## 5. Repo Hosting Services — ☆☆☆☆☆

> Repo hosting services provide storage, management, and collaboration tools for version-controlled code repositories. Support Git, Mercurial, Subversion with features like branching, pull requests, issue tracking, code review, and CI/CD integration. Popular services: GitHub, GitLab, Bitbucket.

**📚 Learn:**

- 🏛️ Official: [GitHub](https://github.com)
- 🏛️ Official: [GitLab](https://about.gitlab.com/)
- 🏛️ Official: [BitBucket](https://bitbucket.org/product/guides/getting-started/overview)

**✅ Checklist:**

- [ ] GitHub — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated Git & GitHub Roadmap](https://roadmap.sh/git-github)
  - 🏛️ Official: [GitHub Documentation](https://docs.github.com)
  - 🎥 Video: [What is GitHub?](https://www.youtube.com/watch?v=w3jLJU7DT5E)
  - 🎥 Video: [Git and GitHub for Beginners](https://www.youtube.com/watch?v=RGOj5yH7evk)
- [ ] GitLab — ☆☆☆☆☆
  - 🏛️ Official: [GitLab](https://gitlab.com/)
  - 🏛️ Official: [GitLab Documentation](https://docs.gitlab.com/)
  - 🎥 Video: [What is GitLab and Why Use It?](https://www.youtube.com/watch?v=bnF7f1zGpo4)

### 🧠 Quiz

1. What is a pull/merge request?
   <details><summary>Answer</summary>A proposal to merge a branch, with code review, discussion and CI checks.</details>

2. What is the difference between a fork and a branch?
   <details><summary>Answer</summary>A fork is a separate copy of the whole repository under another account; a branch is a line of development inside one repository.</details>

3. What are branch protection rules used for?
   <details><summary>Answer</summary>To require reviews and passing CI before merging, and to prevent force-pushes to important branches like main.</details>

---

## 6. Relational Databases — ☆☆☆☆☆

> Relational databases organize data into structured tables with rows and columns, using SQL for querying. Enforce data integrity through keys and constraints, handle complex queries and transactions efficiently. Examples: MySQL, PostgreSQL, Oracle. Used for structured data storage and strong consistency.

**📚 Learn:**

- 🎓 Course: [Databases and SQL](https://www.edx.org/course/databases-5-sql)
- 📄 Article: [Relational Databases](https://www.ibm.com/cloud/learn/relational-databases)
- 📄 Article: [Intro To Relational Databases](https://www.udacity.com/course/intro-to-relational-databases--ud197)
- 🎥 Video: [What is Relational Database](https://youtu.be/OqjJjpjDRLc)

**✅ Checklist:**

- [ ] PostgreSQL — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated PostgreSQL DBA Roadmap](https://roadmap.sh/postgresql-dba)
  - 🎓 Course: [PostgreSQL Full Course for Beginners – freeCodeCamp](https://www.youtube.com/watch?v=qw--VYLpxG4)
  - 🏛️ Official: [Official Website](https://www.postgresql.org/)
  - 📄 Article: [Learn PostgreSQL - Full Tutorial for Beginners](https://www.postgresqltutorial.com/)
- [ ] MySQL — ☆☆☆☆☆
  - 🏛️ Official: [MySQL Docs](https://dev.mysql.com/doc/)
  - 📄 Article: [MySQL for Developers](https://planetscale.com/courses/mysql-for-developers/introduction/course-introduction)
  - 📄 Article: [MySQL Tutorial](https://www.mysqltutorial.org/)
  - 🎥 Video: [MySQL Complete Course](https://www.youtube.com/watch?v=5OdVJbNCSso)
- [ ] MariaDB — ☆☆☆☆☆
  - 🏛️ Official: [MariaDB](https://mariadb.org/)
  - 📄 Article: [MariaDB vs MySQL](https://www.guru99.com/mariadb-vs-mysql.html)
  - 🎥 Video: [MariaDB Tutorial For Beginners in One Hour](https://www.youtube.com/watch?v=_AMj02sANpI)
- [ ] MS SQL — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated SQL Roadmap](https://roadmap.sh/sql)
  - 🏛️ Official: [MS SQL](https://www.microsoft.com/en-ca/sql-server/)
  - 📄 Article: [Tutorials for SQL Server](https://docs.microsoft.com/en-us/sql/sql-server/tutorials-for-sql-server-2016?view=sql-server-ver15)
  - 🎥 Video: [SQL Server tutorial for beginners](https://www.youtube.com/watch?v=-EPMOaV7h_Q)
- [ ] Oracle — ☆☆☆☆☆
  - 🏛️ Official: [Oracle Website](https://www.oracle.com/database/)
  - 🏛️ Official: [Oracle Docs](https://docs.oracle.com/en/database/index.html)
  - 🎥 Video: [Oracle SQL Tutorial for Beginners](https://www.youtube.com/watch?v=ObbNGhcxXJA)
- [ ] SQLite — ☆☆☆☆☆
  - 🏛️ Official: [SQLite](https://www.sqlite.org/index.html)
  - 📄 Article: [SQLite Tutorial](https://www.sqlitetutorial.net/)
  - 🎥 Video: [SQLite Introduction](https://www.youtube.com/watch?v=8Xyn8R9eKB8)

### 🧠 Quiz

1. What is a primary key and a foreign key?
   <details><summary>Answer</summary>A primary key uniquely identifies a row; a foreign key references a primary key in another table to link rows.</details>

2. What is the difference between INNER JOIN and LEFT JOIN?
   <details><summary>Answer</summary>INNER JOIN returns only matching rows from both tables; LEFT JOIN returns all rows from the left table plus matches (NULLs where none).</details>

3. How do you prevent SQL injection?
   <details><summary>Answer</summary>Use parameterized queries / prepared statements (or an ORM), never concatenate user input into SQL.</details>

---

## 7. Learn about APIs — ☆☆☆☆☆

> API (Application Programming Interface) defines rules and protocols for software applications to communicate. Provides standardized access to functionalities without understanding internal workings. Includes endpoints, request methods (GET, POST, PUT), and data formats (JSON, XML).

**📚 Learn:**

- 🗺️ Roadmap: [Visit the Dedicated API Design Roadmap](https://roadmap.sh/api-design)
- 🗺️ Roadmap: [Visit the Dedicated API Security Best Practices](https://roadmap.sh/api-security-best-practices)
- 📄 Article: [What is an API?](https://aws.amazon.com/what-is/api/)
- 🎥 Video: [What is an API (in 5 minutes)](https://www.youtube.com/watch?v=ByGJQzlzxQg)

**✅ Checklist:**

- [ ] REST — ☆☆☆☆☆
  - 📄 Article: [What is a REST API?](https://www.redhat.com/en/topics/api/what-is-a-rest-api)
  - 📄 Article: [Best practices for RESTful web API design](https://learn.microsoft.com/en-us/azure/architecture/best-practices/api-design)
  - 📄 Article: [Learn REST: A RESTful Tutorial](https://restapitutorial.com/)
  - 🎥 Video: [REST API Best Practices – REST Endpoint Design](https://www.youtube.com/watch?v=1Wl-rtew1_E)
- [ ] JSON APIs — ☆☆☆☆☆
  - 🎓 Course: [Full Stack Open - Node.js and Express (Part 3)](https://fullstackopen.com/en/part3)
  - 🏛️ Official: [JSON.org - Introducing JSON](https://www.json.org/json-en.html)
  - 📄 Article: [JSON API Recommendations and Best Practices](https://jsonapi.org/recommendations/)
  - 🎥 Video: [REST API vs JSON API - Which Should You Use?](https://www.youtube.com/watch?v=0oXYLzuucwE)
- [ ] SOAP — ☆☆☆☆☆
  - 📄 Article: [SOAP Web Services Tutorial for Beginners](https://www.guru99.com/soap-simple-object-access-protocol.html)
  - 🎥 Video: [REST vs SOAP](https://www.youtube.com/watch?v=_fq8Ye8kodA)
  - 🎥 Video: [SOAP vs REST vs GraphQL vs gRPC](https://www.youtube.com/watch?v=4vLxWqE94l4)
- [ ] gRPC — ☆☆☆☆☆
  - 🏛️ Official: [gRPC Website](https://grpc.io/)
  - 📄 Article: [What Is GRPC?](https://www.wallarm.com/what/the-concept-of-grpc)
  - 🎥 Video: [What Is GRPC?](https://www.youtube.com/watch?v=hVrwuMnCtok)
- [ ] GraphQL — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated GraphQL Roadmap](https://roadmap.sh/graphql)
  - 🏛️ Official: [GraphQL](https://graphql.org/)
  - 🎥 Video: [Tutorial - GraphQL Explained in 100 Seconds](https://www.youtube.com/watch?v=eIQh02xuVw4)
- [ ] Open API Specs — ☆☆☆☆☆
  - 🏛️ Official: [OpenAPI Specification Website](https://swagger.io/specification/)
  - 🏛️ Official: [Open API Live Editor](https://swagger.io/tools/swagger-editor/)
  - 🎥 Video: [OpenAPI 3.0: How to Design and Document APIs with the Latest OpenAPI Specification 3.0](https://www.youtube.com/watch?v=6kwmW_p_Tig)
  - 🎥 Video: [REST API and OpenAPI: It’s Not an Either/Or Question](https://www.youtube.com/watch?v=pRS9LRBgjYg)

### 🧠 Quiz

1. What are the main principles of REST?
   <details><summary>Answer</summary>Resources identified by URLs, standard HTTP methods, stateless requests, and representations such as JSON.</details>

2. When might you choose gRPC over REST?
   <details><summary>Answer</summary>For fast internal service-to-service communication with strict contracts (Protocol Buffers) and streaming.</details>

3. What is the OpenAPI specification used for?
   <details><summary>Answer</summary>Describing an HTTP API in a machine-readable format to generate docs, clients, mocks and validation.</details>

---

## 8. Authentication — ☆☆☆☆☆

> API authentication verifies client identity to ensure only authorized access to resources. Common methods include API keys, OAuth 2.0, JWT, and basic auth. It protects data, prevents unauthorized access, enables usage tracking, and provides granular control over API resources.

**📚 Learn:**

- 📄 Article: [Basic Authentication](https://roadmap.sh/guides/basic-authentication)
- 📄 Article: [Session Based Authentication](https://roadmap.sh/guides/session-based-authentication)
- 📄 Article: [Token Based Authentication](https://roadmap.sh/guides/token-authentication)
- 📄 Article: [JWT Authentication](https://roadmap.sh/guides/jwt-authentication)
- 📄 Article: [OAuth - Open Authorization](https://roadmap.sh/guides/oauth)
- 📄 Article: [SSO - Single Sign On](https://roadmap.sh/guides/sso)
- 🎓 Course: [Broken Authentication: Hands-on Exercise](https://ransomleak.com/exercises/broken-user-authentication/)

**✅ Checklist:**

- [ ] JWT — ☆☆☆☆☆
  - 🏛️ Official: [jwt.io Website](https://jwt.io/)
  - 📄 Article: [What is JWT?](https://www.akana.com/blog/what-is-jwt)
  - 📄 Article: [JWT Security Best Practices](https://curity.io/resources/learn/jwt-best-practices/)
  - 🎥 Video: [Node.js JWT Authentication Tutorial](https://www.youtube.com/watch?v=mbsmsi7l3r4)
- [ ] OAuth — ☆☆☆☆☆
  - 📄 Article: [Okta - What the Heck is OAuth](https://developer.okta.com/blog/2017/06/21/what-the-heck-is-oauth)
  - 📄 Article: [DigitalOcean - An Introduction to OAuth 2](https://www.digitalocean.com/community/tutorials/an-introduction-to-oauth-2)
  - 🎥 Video: [OAuth 2 Explained In Simple Terms](https://www.youtube.com/watch?v=ZV5yTm4pT8g)
- [ ] Basic Authentication — ☆☆☆☆☆
  - 📄 Article: [HTTP Basic Authentication](https://roadmap.sh/guides/http-basic-authentication)
  - 🎥 Video: [Basic Authentication in 5 minutes](https://www.youtube.com/watch?v=rhi1eIjSbvk)
  - 🎥 Video: [Illustrated HTTP Basic Authentication](https://www.youtube.com/watch?v=mwccHwUn7Gc)
- [ ] Token Authentication — ☆☆☆☆☆
  - 📄 Article: [Token Based Authentication](https://roadmap.sh/guides/token-authentication)
  - 📄 Article: [What Is Token-Based Authentication?](https://www.okta.com/identity-101/what-is-token-based-authentication/)
  - 🎥 Video: [Why is JWT popular?](https://www.youtube.com/watch?v=P2CPd9ynFLg)
- [ ] Cookie Based Auth — ☆☆☆☆☆
  - 🏛️ Official: [HTTP Cookies - MDN Web Docs](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
  - 📄 Article: [Session vs Token Authentication](https://www.section.io/engineering-education/token-based-vs-session-based-authentication/)
  - 🎥 Video: [Session vs Token Authentication in 100 Seconds](https://www.youtube.com/watch?v=UBUNrFtufWo)
  - 🎥 Video: [How do cookies work?](https://www.youtube.com/watch?v=rdVPflECed8)
- [ ] OpenID — ☆☆☆☆☆
  - 🏛️ Official: [OpenID Website](https://openid.net/)
  - 📄 Article: [OpenID Connect Protocol](https://auth0.com/docs/authenticate/protocols/openid-connect-protocol)
  - 🎥 Video: [An Illustrated Guide to OAuth and OpenID Connect](https://www.youtube.com/watch?v=t18YB3xDfXI)
  - 🎥 Video: [OAuth 2.0 and OpenID Connect (in plain English)](https://www.youtube.com/watch?v=996OiexHze0)
- [ ] SAML — ☆☆☆☆☆
  - 📄 Article: [SAML Explained in Plain English](https://www.onelogin.com/learn/saml)
  - 🎥 Video: [How SAML Authentication Works](https://www.youtube.com/watch?v=VzRnb9u8T1A)

### 🧠 Quiz

1. What is the difference between authentication and authorization?
   <details><summary>Answer</summary>Authentication verifies who you are; authorization decides what you are allowed to do.</details>

2. What are the three parts of a JWT?
   <details><summary>Answer</summary>Header, payload and signature, base64url-encoded and separated by dots.</details>

3. What is OAuth 2.0 and how is OpenID Connect related?
   <details><summary>Answer</summary>OAuth 2.0 delegates access to resources; OpenID Connect adds an identity layer on top of it for login.</details>

---

## 9. Caching — ☆☆☆☆☆

> Caching is a technique used to store copies of data in a temporary storage location so that future requests for that data can be served faster. This temporary storage, known as a cache, can be located closer to the request source than the original data source, reducing latency and improving application performance. By retrieving data from the cache instead of the original source, applications can respond more quickly and efficiently.

**📚 Learn:**

- 📄 Article: [What is caching?](https://www.cloudflare.com/en-gb/learning/cdn/what-is-caching/)
- 📄 Article: [Top Caching Strategies Explained](https://blog.bytebytego.com/p/top-caching-strategies)
- 🎥 Video: [Caching Complete Tutorial for Beginners](https://www.youtube.com/watch?v=1XJG34mewts)

**✅ Checklist:**

- [ ] Redis — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated Redis Roadmap](https://roadmap.sh/redis)
  - 🎓 Course: [Redis Crash Course](https://www.youtube.com/watch?v=XCsS_NVAa1g)
  - 🏛️ Official: [Redis Documentation](https://redis.io/docs/latest/)
  - 🎥 Video: [Redis Tutorial for Beginners](https://www.youtube.com/watch?v=jgpVdJB2sKQ)
- [ ] Memcached — ☆☆☆☆☆
  - 💻 Open source: [memcached/memcached](https://github.com/memcached/memcached#readme)
  - 📄 Article: [Memcached Tutorial](https://www.tutorialspoint.com/memcached/index.htm)
  - 🎥 Video: [Redis vs Memcached](https://www.youtube.com/watch?v=Gyy1SiE8avE)
- [ ] HTTP Caching — ☆☆☆☆☆
  - 📄 Article: [Client Side Caching](https://redis.io/docs/latest/develop/use/client-side-caching/)
  - 🎥 Video: [Everything you need to know about HTTP Caching](https://www.youtube.com/watch?v=HiBDZgTNpXY)

### 🧠 Quiz

1. What is cache invalidation and why is it hard?
   <details><summary>Answer</summary>Removing or updating stale cached data when the source changes; it's hard to know exactly when and what to invalidate without serving stale data.</details>

2. What is the cache-aside pattern?
   <details><summary>Answer</summary>The app checks the cache first; on a miss it reads from the database and writes the result into the cache.</details>

3. What is the difference between Redis and Memcached?
   <details><summary>Answer</summary>Both are in-memory key-value stores; Redis also has rich data types, persistence, pub/sub and replication, while Memcached is simpler and purely a cache.</details>

---

## 10. Web Security — ☆☆☆☆☆

> Web security protects applications from threats through strong authentication, encryption (SSL/TLS), input validation preventing SQL injection and XSS attacks, secure coding practices, session management, regular updates, and ongoing security testing including penetration testing.

**📚 Learn:**

- 🗺️ Roadmap: [Visit the Dedicated Cybersecurity Roadmap](https://roadmap.sh/cyber-security)
- 💻 Open source: [OWASP Web Application Security Testing Checklist](https://github.com/0xRadi/OWASP-Web-Checklist)
- 📄 Article: [Why HTTPS Matters](https://developers.google.com/web/fundamentals/security/encrypt-in-transit/why-https)
- 🎥 Video: [7 Security Risks and Hacking Stories for Web Developers](https://www.youtube.com/watch?v=4YOpILi9Oxs)

**✅ Checklist:**

- [ ] Hashing algorithms — ☆☆☆☆☆
  - [ ] MD5 — ☆☆☆☆☆
    - 📄 Article: [Wikipedia - MD5](https://en.wikipedia.org/wiki/MD5)
    - 📄 Article: [What is MD5?](https://www.techtarget.com/searchsecurity/definition/MD5)
    - 📄 Article: [Why is MD5 not safe?](https://infosecscout.com/why-md5-is-not-safe/)
    - 🎥 Video: [How the MD5 hash function works](https://www.youtube.com/watch?v=5MiMK45gkTY)
  - [ ] SHA — ☆☆☆☆☆
    - 📄 Article: [What is SHA?](https://www.encryptionconsulting.com/education-center/what-is-sha/)
    - 🎥 Video: [SHA: Secure Hashing Algorithm](https://www.youtube.com/watch?v=DMtFhACPnTY)
  - [ ] scrypt — ☆☆☆☆☆
    - 🏛️ Official: [sCrypt Website](https://www.tarsnap.com/scrypt.html)
    - 📄 Article: [Wikipedia - scrypt](https://en.wikipedia.org/wiki/Scrypt)
  - [ ] bcrypt — ☆☆☆☆☆
    - 💻 Open source: [bcrypt for Node.js](https://github.com/kelektiv/node.bcrypt.js)
    - 📄 Article: [Understanding bcrypt](https://auth0.com/blog/hashing-in-action-understanding-bcrypt/)
    - 🎥 Video: [bcrypt explained](https://www.youtube.com/watch?v=AzA_LTDoFqY)
- [ ] HTTPS — ☆☆☆☆☆
  - 📄 Article: [What is HTTPS?](https://www.cloudflare.com/en-gb/learning/ssl/what-is-https/)
  - 📄 Article: [How HTTPS works (comic)](https://howhttps.works/)
  - 📄 Article: [HTTPS explained with carrier pigeons](https://baida.dev/articles/https-explained-with-carrier-pigeons)
  - 🎥 Video: [HTTP vs HTTPS](https://www.youtube.com/watch?v=nOmT_5hqgPk)
- [ ] SSL/TLS — ☆☆☆☆☆
  - 📄 Article: [Wikipedia - SSL/TLS](https://en.wikipedia.org/wiki/Transport_Layer_Security)
  - 📄 Article: [Cloudflare - What is SSL?](https://www.cloudflare.com/learning/ssl/what-is-ssl/)
  - 🎥 Video: [SSL, TLS, HTTPS Explained](https://www.youtube.com/watch?v=j9QmMEWmcfo)
- [ ] OWASP Risks — ☆☆☆☆☆
  - 🏛️ Official: [OWASP Website](https://owasp.org/)
  - 💻 Open source: [OWASP Application Security Verification Standard](https://github.com/OWASP/ASVS)
  - 📄 Article: [OWASP Top 10 Security Risks](https://cheatsheetseries.owasp.org/IndexTopTen.html)
  - 📄 Article: [OWASP Cheatsheets](https://cheatsheetseries.owasp.org/cheatsheets/AJAX_Security_Cheat_Sheet.html)
  - 🎓 Course: [OWASP Top 10: Exploit-then-Fix Labs](https://ransomleak.com/catalogue/application-security/)
- [ ] CORS — ☆☆☆☆☆
  - 📄 Article: [Cross-Origin Resource Sharing (CORS)](https://developer.mozilla.org/en-US/docs/Web/HTTP/CORS)
  - 📄 Article: [Understanding CORS](https://rbika.com/blog/understanding-cors)
  - 🎥 Video: [CORS in 100 Seconds](https://www.youtube.com/watch?v=4KHiSt0oLJ0)
  - 🎥 Video: [CORS in 6 minutes](https://www.youtube.com/watch?v=PNtFSVU-YTI)
- [ ] CSP — ☆☆☆☆☆
  - 📄 Article: [MDN — Content Security Policy (CSP)](https://developer.mozilla.org/en-US/docs/Web/HTTP/CSP)
  - 📄 Article: [Google Devs — Content Security Policy (CSP)](https://developers.google.com/web/fundamentals/security/csp)
  - 🎥 Video: [Content Security Policy Explained](https://www.youtube.com/watch?v=-LjPRzFR5f0)
- [ ] Server Security — ☆☆☆☆☆
  - 📄 Article: [What is a hardened server?](https://www.sophos.com/en-us/cybersecurity-explained/what-is-server-hardening)
  - 🎥 Video: [10 Tips for Hardening your Linux Servers](https://www.youtube.com/watch?v=Jnxx_IAC0G4)

### 🧠 Quiz

1. Why should passwords be hashed with bcrypt/scrypt instead of MD5 or SHA?
   <details><summary>Answer</summary>bcrypt and scrypt are deliberately slow and salted, making brute-force attacks expensive; MD5/SHA are fast and unsuitable for passwords.</details>

2. What does TLS provide?
   <details><summary>Answer</summary>Encryption, integrity and server authentication for data in transit.</details>

3. Name three OWASP Top 10 risks.
   <details><summary>Answer</summary>E.g. broken access control, injection, cryptographic failures, security misconfiguration, vulnerable components.</details>

---

## 11. Learn about Web Servers — ☆☆☆☆☆

> Web servers handle client requests and serve web content like HTML pages and images. Process HTTP/HTTPS requests, interact with databases, and send responses. Popular servers include Apache, Nginx, and IIS. Essential for hosting websites, managing traffic, and providing SSL/TLS security.

**📚 Learn:**

- 📄 Article: [What is a Web Server? - Mozilla](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_is_a_web_server)
- 📄 Article: [What is a Web Server?](https://www.hostinger.co.uk/tutorials/what-is-a-web-server)
- 🎥 Video: [Web Server Concepts and Examples](https://youtu.be/9J1nJOivdyw)

**✅ Checklist:**

- [ ] Nginx — ☆☆☆☆☆
  - 🏛️ Official: [Nginx Website](https://nginx.org/)
  - 🎥 Video: [NGINX Explained in 100 Seconds](https://www.youtube.com/watch?v=JKxlsvZXG7c)
  - 🎥 Video: [NGINX Tutorial for Beginners](https://www.youtube.com/watch?v=9t9Mp0BGnyI)
- [ ] Apache — ☆☆☆☆☆
  - 🏛️ Official: [Apache Server](https://httpd.apache.org/)
  - 🏛️ Official: [Apache Server Documentation](https://httpd.apache.org/docs/2.4/)
  - 🎥 Video: [What is Apache Web Server?](https://www.youtube.com/watch?v=kaaenHXO4t4)
  - 🎥 Video: [Apache vs NGINX](https://www.youtube.com/watch?v=9nyiY-psbMs)
- [ ] Caddy — ☆☆☆☆☆
  - 🏛️ Official: [Caddy Server](https://caddyserver.com/)
  - 💻 Open source: [caddyserver/caddy - Caddy on GitHub](https://github.com/caddyserver/caddy)
  - 🎥 Video: [How to Make a Simple Caddy 2 Website](https://www.youtube.com/watch?v=WgUV_BlHvj0)
- [ ] MS IIS — ☆☆☆☆☆
  - 🏛️ Official: [Microsoft -IIS](https://www.iis.net/)
  - 🎥 Video: [Learn Windows Web Server IIS](https://www.youtube.com/watch?v=1VdxPWwtISA)
  - 🎥 Video: [What is IIS?](https://www.youtube.com/watch?v=hPWSqEXOjQY)

### 🧠 Quiz

1. What is a reverse proxy?
   <details><summary>Answer</summary>A server (e.g. Nginx) that sits in front of app servers and forwards client requests to them, often adding TLS, caching and load balancing.</details>

2. What is the difference between a web server and an application server?
   <details><summary>Answer</summary>A web server serves static files and handles HTTP; an application server runs your application code to produce dynamic responses.</details>

3. Name a feature Caddy is known for.
   <details><summary>Answer</summary>Automatic HTTPS with certificates from Let's Encrypt, configured by default.</details>

---

## 12. Learn the Basics — ☆☆☆☆☆

> (Generative) AI can help backend developers automate tasks and write code more efficiently. It uses machine learning models to generate things like code snippets, documentation, and even test cases. By providing these tools with relevant information about your backend system, you can speed up the development process and reduce errors.

**📚 Learn:**

- 📄 Article: [AI in software development - IBM](https://www.ibm.com/think/topics/ai-in-software-development)
- 📄 Article: [AI in Software Development - GitHub](https://github.com/resources/articles/ai-in-software-development)
- 📄 Article: [AI in Software Development: Revolutionizing the Coding Landscape](https://www.coursera.org/articles/ai-in-software-development)

**✅ Checklist:**

- [ ] How LLMs work — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated AI Engineer Roadmap](https://roadmap.sh/ai-engineer)
  - 📄 Article: [What is a large language model (LLM)?](https://www.cloudflare.com/en-gb/learning/ai/what-is-large-language-model/)
  - 📄 Article: [New to LLMs? Start Here](https://towardsdatascience.com/new-to-llms-start-here/)
  - 🎥 Video: [How Large Language Models Work](https://www.youtube.com/watch?v=5sLYAQS9sWQ)
- [ ] AI vs Traditional Coding — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated Vibe Coding Roamdap](https://roadmap.sh/vibe-coding)
  - 📄 Article: [What is vibe coding?](https://www.ibm.com/think/topics/vibe-coding)
  - 📄 Article: [How AI is transforming work at Anthropic](https://www.anthropic.com/research/how-ai-is-transforming-work-at-anthropic)
  - 🎥 Video: [AI Systems vs Traditional Coding](https://www.youtube.com/watch?v=P7lryCIvxgA)
- [ ] Embeddings — ☆☆☆☆☆
  - 📄 Article: [What are Embeddings in Machine Learning?](https://www.cloudflare.com/en-gb/learning/ai/what-are-embeddings/)
  - 📄 Article: [What is Embedding?](https://www.ibm.com/topics/embedding)
  - 📄 Article: [Getting Started With Embeddings](https://huggingface.co/blog/getting-started-with-embeddings)
  - 🎥 Video: [What are Word Embeddings?](https://www.youtube.com/watch?v=wgfSDrqYMJ4)
- [ ] Vectors — ☆☆☆☆☆
  - 📄 Article: [What is vector embedding?](https://www.ibm.com/think/topics/vector-embedding)
  - 📄 Article: [A Gentle Introduction to Vectors for Machine Learning](https://machinelearningmastery.com/gentle-introduction-vectors-machine-learning/)
  - 📄 Article: [Vector Databases](https://developers.cloudflare.com/vectorize/reference/what-is-a-vector-database/)
  - 🎥 Video: [AI Foundations - What are Vectors?](https://www.youtube.com/watch?v=dvDmXTKFtgQ)
- [ ] RAGs — ☆☆☆☆☆
  - 📄 Article: [What is Retrieval-Augmented Generation? - Google](https://cloud.google.com/use-cases/retrieval-augmented-generation)
  - 📄 Article: [The Ultimate Guide to RAGs – Each Component Dissected](https://towardsdatascience.com/the-ultimate-guide-to-rags-each-component-dissected-3cd51c4c0212/)
  - 🎥 Video: [What is Retrieval-Augmented Generation? - IBM](https://www.youtube.com/watch?v=T-D1OfcDW1M)

### 🧠 Quiz

1. What is an embedding?
   <details><summary>Answer</summary>A vector of numbers representing the meaning of text (or other data), so similar items are close together.</details>

2. What is RAG (Retrieval-Augmented Generation)?
   <details><summary>Answer</summary>Retrieving relevant documents (often via vector search) and adding them to the prompt so the LLM answers using that data.</details>

3. What is a vector database used for?
   <details><summary>Answer</summary>Storing embeddings and finding the most similar ones quickly (similarity search).</details>

---

## 13. Applications — ☆☆☆☆☆

> AI is increasingly utilized to enhance various software development tasks, like automatically creating code snippets based on specifications. It also improves existing code by suggesting better ways to rewrite it and by generating helpful documentation from the code itself. These AI tools promise to increase efficiency and reduce errors.

**📚 Learn:**

- 📄 Article: [AI in software development](https://www.ibm.com/think/topics/ai-in-software-development)
- 📄 Article: [AI in software development: How to use it, benefits, and key trends](https://appfire.com/resources/blog/ai-in-software-development)
- 📄 Article: [AI-Assisted Software Development: A Comprehensive Guide with Practical Prompts (Part 1/3)](https://aalapdavjekar.medium.com/ai-assisted-software-development-a-comprehensive-guide-with-practical-prompts-part-1-3-989a529908e0)

**✅ Checklist:**

- [ ] Code Reviews — ☆☆☆☆☆
  - 📄 Article: [AI Code Reviews](https://github.com/resources/articles/ai-code-reviews)
  - 📄 Article: [AI Code Review: How to Make it Work for You](https://www.startearly.ai/post/ai-code-review-how-to-make-it-work-for-you)
  - 🎥 Video: [You've Been Using AI the Hard Way (Use This Instead)](https://www.youtube.com/watch?v=MsQACpcuTkU)
  - 🎥 Video: [Automatic code reviews with OpenAI Codex](https://www.youtube.com/watch?v=HwbSWVg5Ln4&t=83s)
- [ ] Refactoring — ☆☆☆☆☆
  - 📄 Article: [What is AI code refactoring? - IBM](https://www.ibm.com/think/topics/ai-code-refactoring)
  - 📄 Article: [What is AI code refactoring?](https://graphite.com/guides/what-is-ai-code-refactoring)
  - 🎥 Video: [Using AI to Refactor Legacy Code: A Practical Guide with Scott Wierschem](https://www.youtube.com/watch?v=B7Yt-WmlW2I)
  - 🎥 Video: [AI-Driven Code Refactoring: Improving Legacy Codebases Automatically - Jorrik Klijnsma](https://www.youtube.com/watch?v=u8tvVxUOwvY)
- [ ] Documentation Generation — ☆☆☆☆☆
  - 📄 Article: [AI code documentation: Benefits and top tips](https://www.ibm.com/think/insights/ai-code-documentation-benefits-top-tips)
  - 📄 Article: [AI Code Documentation Generators: A Guide](https://overcast.blog/ai-code-documentation-generators-a-guide-b6cd72cd0ec4)
  - 🎥 Video: [How I Built a Tool to Auto-Generate GitHub Documentation with LLMs](https://www.youtube.com/watch?v=QYchuz6nBR8)
  - 🎥 Video: [How to Generate API Documentation Using AI](https://www.youtube.com/watch?v=1529XqH50Xs)

### 🧠 Quiz

1. How can AI help with code reviews?
   <details><summary>Answer</summary>By spotting bugs, style issues and missing tests, and summarizing changes — as an assistant to human reviewers.</details>

2. What should you do before accepting an AI refactor?
   <details><summary>Answer</summary>Make sure tests pass and review the diff, since behavior may change subtly.</details>

3. What is a risk of AI-generated documentation?
   <details><summary>Answer</summary>It can be confidently wrong or drift from the actual code, so it must be checked.</details>

---

## 14. AI Assisted Coding — ☆☆☆☆☆

> AI-assisted coding involves using artificial intelligence tools to help developers write code more efficiently and effectively. These tools can provide real-time suggestions, automate repetitive tasks, identify potential errors, and even generate code snippets based on natural language descriptions, ultimately speeding up development and improving code quality.

**📚 Learn:**

- 🗺️ Roadmap: [Visit the Dedicated Vibe Coding Roadmap](https://roadmap.sh/vibe-coding)
- 📄 Article: [How to Become an Expert in AI-Assisted Coding – A Handbook for Developers](https://www.freecodecamp.org/news/how-to-become-an-expert-in-ai-assisted-coding-a-handbook-for-developers/)
- 📄 Article: [The 10 Best Vibe Coding Tools in 2026: Our Choices](https://roadmap.sh/vibe-coding/best-tools)
- 🎥 Video: [Everything You Need to Know About Coding with AI // NOT vibe coding](https://www.youtube.com/watch?v=5fhcklZe-qE)

**✅ Checklist:**

- [ ] Claude Code — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated Claude Code Roadmap](https://roadmap.sh/claude-code)
  - 🏛️ Official: [Claude Code Overview](https://code.claude.com/docs/en/overview)
  - 📄 Article: [Vibe coding tutorial: Build your first app with Claude Code](https://roadmap.sh/vibe-coding/tutorial)
  - 🎥 Video: [Claude Code Tutorial for Beginners](https://www.youtube.com/watch?v=eMZmDH3T2bY)
- [ ] Cursor — ☆☆☆☆☆
  - 🎓 Course: [Cursor Learn](https://cursor.com/learn)
  - 🏛️ Official: [Cursor Docs](https://cursor.com/docs)
  - 📄 Article: [Claude Code vs Cursor: Which AI Coding Tool To Choose](https://roadmap.sh/claude-code/vs-cursor)
  - 🎥 Video: [Cursor Tutorial for Beginners (AI Code Editor)](https://www.youtube.com/watch?v=ocMOZpuAMw4)
- [ ] Copilot — ☆☆☆☆☆
  - 🏛️ Official: [Quickstart for GitHub Copilot](https://docs.github.com/en/copilot/quickstart)
  - 📄 Article: [What is GitHub Copilot?](https://www.codecademy.com/article/what-is-github-copilot)
  - 🎥 Video: [Getting started with GitHub Copilot | Tutorial](https://www.youtube.com/watch?v=n0NlxUyA7FI)
- [ ] Antigravity — ☆☆☆☆☆
  - 🏛️ Official: [Google Antigravity](https://antigravity.google/)
  - 🏛️ Official: [Getting Started with Google Antigravity](https://codelabs.developers.google.com/getting-started-google-antigravity#0)
  - 📄 Article: [Hands-On With Antigravity: Google’s Newest AI Coding Experiment](https://thenewstack.io/hands-on-with-antigravity-googles-newest-ai-coding-experiment/)
  - 🎥 Video: [Antigravity + Stitch MCP: AI Agents That Build Complete Websites](https://www.youtube.com/watch?v=7wa4Ey_tCCE)
- [ ] Prompting Techniques — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated Prompt Engineering Roadmap](https://roadmap.sh/prompt-engineering)
  - 🎓 Course: [Introduction to Prompt Engineering](https://learnprompting.org/courses/intro-to-prompt-engineering)
  - 📄 Article: [Prompt engineering techniques](https://www.ibm.com/think/topics/prompt-engineering-techniques)
  - 🎥 Video: [What is Prompt Engineering?](https://www.youtube.com/watch?v=nf1e-55KKbg)
- [ ] Agents — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated AI Agents Roadmap](https://roadmap.sh/ai-agents)
  - 📄 Article: [What are AI Agents? - IBM](https://www.ibm.com/think/topics/ai-agents)
  - 🎥 Video: [What are AI Agents?](https://www.youtube.com/watch?v=F8NKVhkZZWI)
  - 🎥 Video: [From Zero to Your First AI Agent in 25 Minutes (No Coding)](https://www.youtube.com/watch?v=EH5jx5qPabU)
- [ ] MCP — ☆☆☆☆☆
  - 🎓 Course: [MCP: Build Rich-Context AI Apps with Anthropic](https://www.deeplearning.ai/short-courses/mcp-build-rich-context-ai-apps-with-anthropic/)
  - 🏛️ Official: [Model Context Protocol](https://modelcontextprotocol.io/introduction)
  - 💻 Open source: [modelcontexprotocol](https://github.com/modelcontextprotocol/modelcontextprotocol)
  - 📄 Article: [A Clear Intro to MCP (Model Context Protocol) with Code Examples](https://towardsdatascience.com/clear-intro-to-mcp/)
- [ ] Skills — ☆☆☆☆☆
  - 🎓 Course: [Agent Skills with Anthropic](https://www.deeplearning.ai/short-courses/agent-skills-with-anthropic/)
  - 📄 Article: [AI Agents or Skills? Why the Answer Is ‘Both’](https://thenewstack.io/ai-agents-or-skills-why-the-answer-is-both/)
  - 📄 Article: [Agent Skills vs Tools: What Actually Matters](https://blog.arcade.dev/what-are-agent-skills-and-tools)
  - 🎥 Video: [The complete guide to Agent Skills](https://www.youtube.com/watch?v=fabAI1OKKww)

### 🧠 Quiz

1. What is an AI coding agent?
   <details><summary>Answer</summary>A tool like Claude Code that can read the codebase, edit files and run commands in a loop to complete a task.</details>

2. What is MCP?
   <details><summary>Answer</summary>Model Context Protocol: a standard for connecting AI tools to external tools and data sources.</details>

3. Why give an AI tool project instructions (e.g. a CLAUDE.md)?
   <details><summary>Answer</summary>So it follows your conventions, commands and architecture, producing code that fits the project.</details>

---

## 15. Integration Patterns — ☆☆☆☆☆

> Integration patterns are reusable solutions to commonly occurring problems when connecting different software systems or applications. They provide a structured approach for ensuring data is correctly exchanged, services are seamlessly accessed, and overall system behavior is predictable and reliable when integrating AI-powered functionalities. This allows developers to handle complexities like data transformations, error handling, security, and message routing in a standardized way.

**📚 Learn:**

- 📄 Article: [Emerging Patterns in Building GenAI Products](https://martinfowler.com/articles/gen-ai-patterns/)
- 📄 Article: [5 Patterns for Scalable LLM Service Integration](https://latitude.so/blog/5-patterns-for-scalable-llm-service-integration/)
- 🎥 Video: [AI Design Patterns - LLM Integration: Choosing Between Direct Calls, Agents, RAG, MCP & Workflows](https://www.youtube.com/watch?v=_amJOKrM0XU)

**✅ Checklist:**

- [ ] OpenAI — ☆☆☆☆☆
  - 🏛️ Official: [OpenAI Platform](https://platform.openai.com/docs/overview)
  - 🏛️ Official: [OpenAI Models](https://platform.openai.com/docs/models)
  - 🏛️ Official: [OpenAI Academy](https://academy.openai.com/)
- [ ] Anthropic — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated Claude Code Roamdap](https://roadmap.sh/claude-code)
  - 🏛️ Official: [Anthropic](https://www.anthropic.com/)
  - 🏛️ Official: [Claude Tutorials](https://claude.com/resources/tutorials)
  - 📄 Article: [Anthropic: What We Know About the Company Behind Claude AI](https://builtin.com/articles/anthropic)
- [ ] Gemini — ☆☆☆☆☆
  - 🏛️ Official: [Google Gemini](https://gemini.google.com/)
  - 🏛️ Official: [Google's Gemini Documentation](https://workspace.google.com/solutions/ai/)
  - 🎥 Video: [Welcome to the Gemini era](https://www.youtube.com/watch?v=_fuimO6ErKI)
- [ ] Streaming — ☆☆☆☆☆
  - 📄 Article: [Streaming Responses in AI: How AI Outputs Are Generated in Real Time](https://dev.to/pranshu_kabra_fe98a73547a/streaming-responses-in-ai-how-ai-outputs-are-generated-in-real-time-18kb)
  - 📄 Article: [AI for Web Devs: Faster Responses with HTTP Streaming](https://austingil.com/ai-for-web-devs-streaming/)
  - 📄 Article: [Master the OpenAI API: Stream Responses](https://www.toolify.ai/gpts/master-the-openai-api-stream-responses-139447)
- [ ] Structured Outputs — ☆☆☆☆☆
  - 📄 Article: [Diving Deeper with Structured Outputs](https://medium.com/data-science/diving-deeper-with-structured-outputs-b4a5d280c208)
  - 📄 Article: [Structured model outputs - OpenAI](https://platform.openai.com/docs/guides/structured-outputs)
  - 📄 Article: [Structured outputs - Claude](https://platform.claude.com/docs/en/build-with-claude/structured-outputs)
  - 🎥 Video: [How to Measure LLM Confidence: Logprobs & Structured Output](https://www.youtube.com/watch?v=THsGizLHrTs)
- [ ] Function Calling — ☆☆☆☆☆
  - 📄 Article: [A Comprehensive Guide to Function Calling in LLMs](https://thenewstack.io/a-comprehensive-guide-to-function-calling-in-llms/)
  - 📄 Article: [Function Calling with LLMs | Prompt Engineering Guide](https://www.promptingguide.ai/applications/function_calling)
  - 📄 Article: [Function Calling with Open-Source LLMs](https://medium.com/@rushing_andrei/function-calling-with-open-source-llms-594aa5b3a304)
  - 🎥 Video: [LLM Function Calling - AI Tools Deep Dive](https://www.youtube.com/watch?v=gMeTK6zzaO4)

### 🧠 Quiz

1. Why stream LLM responses?
   <details><summary>Answer</summary>To show output as it is generated, reducing perceived latency.</details>

2. What is function calling (tool use)?
   <details><summary>Answer</summary>Letting the model request calls to functions you define, with structured arguments; your code runs them and returns results.</details>

3. How do you get reliable structured output from an LLM?
   <details><summary>Answer</summary>Use structured output/JSON schema features or tool calls, and validate the result in your code.</details>

---

## 16. Testing — ☆☆☆☆☆

> Testing systematically evaluates software functionality, performance, and quality against requirements. Includes unit, integration, system, and acceptance testing levels. Can be manual or automated to identify defects, validate features, and ensure reliable performance before deployment.

**📚 Learn:**

- 📄 Article: [What is Software Testing?](https://www.guru99.com/software-testing-introduction-importance.html)
- 📄 Article: [Testing Pyramid](https://www.browserstack.com/guide/testing-pyramid-for-test-automation)

**✅ Checklist:**

- [ ] Unit Testing — ☆☆☆☆☆
  - 🏛️ Official: [Jest - JavaScript Testing Framework](https://jestjs.io/docs/getting-started)
  - 💻 Open source: [JavaScript Testing Best Practices](https://github.com/goldbergyoni/javascript-testing-best-practices)
  - 📄 Article: [What is Unit Testing?](https://www.guru99.com/unit-testing-guide.html)
  - 🎥 Video: [What is Unit Testing?](https://youtu.be/x95ez7_V7rA?si=JhCVhcEN7zZOkxdp)
- [ ] Integration Testing — ☆☆☆☆☆
  - 💻 Open source: [Supertest - HTTP Integration Testing for Node.js](https://github.com/ladjs/supertest)
  - 📄 Article: [Integration Testing](https://www.guru99.com/integration-testing.html)
  - 📄 Article: [How to Integrate and Test Your Tech Stack](https://thenewstack.io/how-to-integrate-and-test-your-tech-stack/)
  - 🎥 Video: [Integration Testing in Node.js](https://www.youtube.com/watch?v=r9HdJ8P6GQI)
- [ ] Functional Testing — ☆☆☆☆☆
  - 🏛️ Official: [Playwright - End-to-End Testing Documentation](https://playwright.dev/docs/intro)
  - 📄 Article: [What is Functional Testing?](https://www.guru99.com/functional-testing.html)
  - 📄 Article: [Functional Testing: What It Is and How to Do It Right](https://www.atlassian.com/continuous-delivery/software-testing/functional-testing)
  - 🎥 Video: [Functional Testing vs Non-Functional Testing](https://www.youtube.com/watch?v=NgQT7miTP9M)

### 🧠 Quiz

1. What is the difference between unit and integration tests?
   <details><summary>Answer</summary>Unit tests check one piece in isolation; integration tests check several components (e.g. app + database) working together.</details>

2. What is the testing pyramid?
   <details><summary>Answer</summary>Many fast unit tests, fewer integration tests, and few slow end-to-end tests.</details>

3. What is a test double (mock/stub)?
   <details><summary>Answer</summary>A fake replacement for a real dependency used to isolate the code under test.</details>

---

## 17. CI / CD — ☆☆☆☆☆

> CI/CD automates building, testing, and deploying code changes. Continuous Integration merges code frequently with automated builds/tests. Continuous Delivery/Deployment extends this to staging/production. Improves software quality and development efficiency through early issue detection.

**📚 Learn:**

- 📄 Article: [What is CI/CD?](https://about.gitlab.com/topics/ci-cd/)
- 📄 Article: [A Primer: Continuous Integration and Continuous Delivery (CI/CD)](https://thenewstack.io/a-primer-continuous-integration-and-continuous-delivery-ci-cd/)
- 🎥 Video: [DevOps CI/CD Explained in 100 Seconds](https://www.youtube.com/watch?v=scEDHsr3APg)
- 🎥 Video: [Automate your Workflows with GitHub Actions](https://www.youtube.com/watch?v=nyKZTKQS_EQ)

**✅ Checklist:**

- [ ] CI / CD — ☆☆☆☆☆

### 🧠 Quiz

1. What is the difference between continuous integration and continuous delivery/deployment?
   <details><summary>Answer</summary>CI automatically builds and tests every change; CD automatically prepares (delivery) or releases (deployment) passing changes to production.</details>

2. Name some typical steps in a CI pipeline.
   <details><summary>Answer</summary>Install dependencies, lint, run tests, build, scan for vulnerabilities, publish artifacts.</details>

3. What is a blue-green deployment?
   <details><summary>Answer</summary>Running two identical environments and switching traffic from the old (blue) to the new (green) one, allowing instant rollback.</details>

---

## 18. More about Databases — ☆☆☆☆☆

> A database is a structured collection of useful data that serves as an organizational asset. A database management system (DBMS) is software designed to maintain and extract large data collections efficiently and timely.

**📚 Learn:**

- 📄 Article: [Oracle: What is a Database?](https://www.oracle.com/database/what-is-database/)
- 📄 Article: [Prisma.io: What are Databases?](https://www.prisma.io/dataguide/intro/what-are-databases)

**✅ Checklist:**

- [ ] ORMs — ☆☆☆☆☆
  - 📄 Article: [What is an ORM, how does it work, and how should I use one?](https://stackoverflow.com/a/1279678)
  - 📄 Article: [What is an ORM](https://www.freecodecamp.org/news/what-is-an-orm-the-meaning-of-object-relational-mapping-database-tools/)
  - 🎥 Video: [Why Use an ORM?](https://www.youtube.com/watch?v=vHt2LC1EM3Q)
- [ ] Migrations — ☆☆☆☆☆
  - 📄 Article: [Schema migration](https://en.wikipedia.org/wiki/Schema_migration)
  - 📄 Article: [What is Database Migration?](https://www.mongodb.com/resources/basics/databases/database-migration)
  - 📄 Article: [Introduction to Database Migration: A Beginner's Guide](https://www.dbvis.com/thetable/introduction-to-database-migration-a-beginners-guide/)
  - 🎥 Video: [Database Migrations Explained](https://www.youtube.com/watch?v=mMsZPZKNc4g)
- [ ] ACID — ☆☆☆☆☆
  - 🏛️ Official: [PostgreSQL Tutorial on Transactions](https://www.postgresql.org/docs/current/tutorial-transactions.html)
  - 🏛️ Official: [MySQL InnoDB and the ACID Model](https://dev.mysql.com/doc/refman/8.0/en/mysql-acid.html)
  - 📄 Article: [What is an ACID Compliant Database?](https://retool.com/blog/whats-an-acid-compliant-database/)
  - 📚 Book: [Database System Concepts - Silberschatz, Korth, Sudarshan](https://db-book.com/)
  - 🎥 Video: [ACID Explained: Atomic, Consistent, Isolated & Durable](https://www.youtube.com/watch?v=yaQ5YMWkxq4)
- [ ] Transactions — ☆☆☆☆☆
  - 📄 Article: [SQL Transactions Tutorial](https://www.sqlservertutorial.net/sql-server-basics/sql-server-transaction/)
  - 🎥 Video: [What is a Database transaction?](https://www.youtube.com/watch?v=wHUOeXbZCYA)
  - 🎥 Video: [ACID Properties in Databases With Examples](https://www.youtube.com/watch?v=GAe5oB742dw)
- [ ] N+1 Problem — ☆☆☆☆☆
  - 📄 Article: [In Detail Explanation of N+1 Problem](https://medium.com/doctolib/understanding-and-fixing-n-1-query-30623109fe89)
  - 📄 Article: [What is the N+1 Problem](https://planetscale.com/blog/what-is-n-1-query-problem-and-how-to-solve-it)
  - 🎥 Video: [SQLite and the N+1 (no) problem](https://www.youtube.com/watch?v=qPfAQY_RahA)
- [ ] Normalization — ☆☆☆☆☆
  - 📄 Article: [What is Normalization in DBMS (SQL)? 1NF, 2NF, 3NF, BCNF Database with Example](https://www.guru99.com/database-normalization.html)
  - 🎥 Video: [Complete guide to Database Normalization in SQL](https://www.youtube.com/watch?v=rBPQ5fg_kiY)
- [ ] Failure Modes — ☆☆☆☆☆
  - 🎓 Course: [Database Failure Modes](https://roadmap.sh/ai/course/database-failure-modes-prevention-and-recovery)
- [ ] Profiling Performance — ☆☆☆☆☆
  - 📄 Article: [How to Profile SQL Queries for Better Performance](https://servebolt.com/articles/profiling-sql-queries/)
  - 🎥 Video: [Performance Profiling](https://www.youtube.com/watch?v=MaauQTeGg2k)

### 🧠 Quiz

1. What does ACID stand for?
   <details><summary>Answer</summary>Atomicity, Consistency, Isolation, Durability.</details>

2. What is the N+1 query problem?
   <details><summary>Answer</summary>Fetching a list with one query, then running one extra query per item; fix it with joins or eager loading.</details>

3. What is database normalization?
   <details><summary>Answer</summary>Organizing tables to reduce duplication and update anomalies (1NF, 2NF, 3NF...).</details>

---

## 19. Scaling Databases — ☆☆☆☆☆

> Scaling databases adapts them to handle more data and users efficiently through vertical scaling (upgrading hardware) or horizontal scaling (adding servers). Key techniques include sharding and replication to maintain robustness as databases grow.

**📚 Learn:**

- 📄 Article: [Strategies for Scaling Databases: A Comprehensive Guide](https://medium.com/@anil.goyal0057/strategies-for-scaling-databases-a-comprehensive-guide-b69cda7df1d3)
- 📄 Article: [Horizontal vs. Vertical Scaling - How to Scale a Database](https://www.freecodecamp.org/news/horizontal-vs-vertical-scaling-in-database/)
- 🎥 Video: [Database Scaling Strategies for Beginners](https://www.youtube.com/watch?v=dkhOZOmV7Fo)

**✅ Checklist:**

- [ ] Database Indexes — ☆☆☆☆☆
  - 🏛️ Official: [PostgreSQL - Indexes](https://www.postgresql.org/docs/current/indexes.html)
  - 📄 Article: [What is a Database Index?](https://www.codecademy.com/article/sql-indexes)
  - 📄 Article: [Use the Index, Luke! - A Guide to Database Performance for Developers](https://use-the-index-luke.com/)
  - 🎥 Video: [Database Indexing Explained](https://www.youtube.com/watch?v=-qNSXK7s7_w)
- [ ] Data Replication — ☆☆☆☆☆
  - 📄 Article: [Data Replication? - IBM](https://www.ibm.com/topics/data-replication)
  - 🎥 Video: [What is Data Replication?](https://www.youtube.com/watch?v=iO8a1nMbL1o)
- [ ] Sharding Strategies — ☆☆☆☆☆
  - 📄 Article: [Wikipedia - Sharding in Database Architectures](https://en.wikipedia.org/wiki/Shard_%28database_architecture%29)
  - 📄 Article: [How sharding a database can make it faster](https://stackoverflow.blog/2022/03/14/how-sharding-a-database-can-make-it-faster/)
  - 🎥 Video: [What is Database Sharding?](https://www.youtube.com/watch?v=XP98YCr-iXQ)
- [ ] CAP Theorem — ☆☆☆☆☆
  - 📄 Article: [What is CAP Theorem?](https://www.bmc.com/blogs/cap-theorem/)
  - 📄 Article: [An Illustrated Proof of the CAP Theorem](https://mwhittaker.github.io/blog/an_illustrated_proof_of_the_cap_theorem/)
  - 📄 Article: [CAP Theorem and its applications in NoSQL Databases](https://www.ibm.com/uk-en/cloud/learn/cap-theorem)
  - 🎥 Video: [What is CAP Theorem?](https://www.youtube.com/watch?v=_RbsFXWRZ10)

### 🧠 Quiz

1. What does an index do and what does it cost?
   <details><summary>Answer</summary>It speeds up reads/lookups on a column, but uses storage and slows down writes.</details>

2. What is the difference between replication and sharding?
   <details><summary>Answer</summary>Replication copies the same data to multiple servers (read scaling, availability); sharding splits data across servers (write and storage scaling).</details>

3. What does the CAP theorem say?
   <details><summary>Answer</summary>During a network partition, a distributed system must choose between consistency and availability.</details>

---

## 20. Architectural Patterns — ☆☆☆☆☆

> Architectural patterns are reusable solutions to common software architecture problems. They address issues like performance limitations, high availability, and business risk minimization, providing proven templates for system design and structure.

**📚 Learn:**

- 📄 Article: [14 Architectural Patterns to know - Red Hat](https://www.redhat.com/architect/14-software-architecture-patterns)
- 📄 Article: [10 Common Software Architectural Patterns in a nutshell](https://towardsdatascience.com/10-common-software-architectural-patterns-in-a-nutshell-a0b47a1e9013)
- 📄 Article: [Software Architecture Patterns - O'Reilly](https://www.oreilly.com/library/view/software-architecture-patterns/9781491971437/)
- 🎥 Video: [10 Architecture Patterns Used In Enterprise Software Development Today](https://www.youtube.com/watch?v=BrT3AO8bVQY)

**✅ Checklist:**

- [ ] Monolith — ☆☆☆☆☆
  - 📄 Article: [Pattern: Monolithic Architecture](https://microservices.io/patterns/monolithic.html)
  - 📄 Article: [Monolithic Architecture - Advantages & Disadvantages](https://datamify.medium.com/monolithic-architecture-advantages-and-disadvantages-e71a603eec89)
  - 🎥 Video: [Monolithic vs Microservice Architecture](https://www.youtube.com/watch?v=NdeTGlZ__Do)
- [ ] Microservices — ☆☆☆☆☆
  - 📄 Article: [Pattern: Microservice Architecture](https://microservices.io/patterns/microservices.html)
  - 📄 Article: [Microservices 101](https://thenewstack.io/microservices-101/)
  - 🎥 Video: [Microservices explained in 5 minutes](https://www.youtube.com/watch?v=lL_j7ilk7rc)
- [ ] SOA — ☆☆☆☆☆
  - 📄 Article: [What is SOA?](https://aws.amazon.com/what-is/service-oriented-architecture/)
  - 📄 Article: [Reference Architecture Foundation for Service Oriented Architecture](http://docs.oasis-open.org/soa-rm/soa-ra/v1.0/soa-ra.html)
  - 🎥 Video: [Service Oriented Architecture (SOA) Simplified](https://www.youtube.com/watch?v=PA9RjHI463g)
- [ ] Serverless — ☆☆☆☆☆
  - 📄 Article: [Serverless](https://www.ibm.com/cloud/learn/serverless)
  - 📄 Article: [AWS Services](https://aws.amazon.com/serverless/)
  - 🎥 Video: [Serverless Computing in 100 Seconds](https://www.youtube.com/watch?v=W_VV2Fx32_Y&ab_channel=Fireship)
- [ ] Service Mesh — ☆☆☆☆☆
  - 📄 Article: [What is a Service Mesh (AWS blog)?](https://aws.amazon.com/what-is/service-mesh/)
  - 📄 Article: [What is a Service Mesh (RedHat blog)?](https://www.redhat.com/en/topics/microservices/what-is-a-service-mesh)
  - 🎥 Video: [What is a Service Mesh?](https://www.youtube.com/watch?v=vh1YtWjfcyk)
- [ ] Twelve Factor Apps — ☆☆☆☆☆
  - 📄 Article: [The Twelve-Factor App](https://12factor.net/)
  - 📄 Article: [An illustrated guide to 12 Factor Apps](https://www.redhat.com/architect/12-factor-app)
  - 🎥 Video: [Every Developer NEEDS To Know 12-Factor App Principles](https://www.youtube.com/watch?v=FryJt0Tbt9Q)
- [ ] LXC — ☆☆☆☆☆
  - 🏛️ Official: [LXC Documentation](https://linuxcontainers.org/lxc/documentation/)
  - 📄 Article: [What is LXC?](https://linuxcontainers.org/lxc/introduction/)
  - 🎥 Video: [Getting Started with LXD Containerization](https://www.youtube.com/watch?v=aIwgPKkVj8s)
  - 🎥 Video: [Getting Started with LXC containers](https://youtu.be/CWmkSj_B-wo)

### 🧠 Quiz

1. What are the pros and cons of microservices vs a monolith?
   <details><summary>Answer</summary>Microservices allow independent deployment and scaling but add network, operational and data-consistency complexity; monoliths are simpler to build and run.</details>

2. What is serverless?
   <details><summary>Answer</summary>Running code as functions managed by a cloud provider that scales automatically and bills per execution.</details>

3. Name two Twelve-Factor App principles.
   <details><summary>Answer</summary>E.g. store config in the environment, treat backing services as attached resources, keep processes stateless, log to stdout.</details>

---

## 21. Message Brokers — ☆☆☆☆☆

> Message brokers facilitate communication between distributed systems by routing and delivering messages. Enable asynchronous messaging, decoupling producers from consumers. Include features like queuing, load balancing, persistence, and acknowledgment. Popular examples: Kafka, RabbitMQ, ActiveMQ.

**📚 Learn:**

- 📄 Article: [What are Message Brokers?](https://www.ibm.com/topics/message-brokers)
- 🎥 Video: [Introduction to Message Brokers](https://www.youtube.com/watch?v=57Qr9tk6Uxc)
- 🎥 Video: [Kafka vs RabbitMQ](https://www.youtube.com/watch?v=_5mu7lZz5X4)

**✅ Checklist:**

- [ ] RabbitMQ — ☆☆☆☆☆
  - 🏛️ Official: [RabbitMQ Tutorials](https://www.rabbitmq.com/getstarted.html)
  - 🎥 Video: [RabbitMQ Tutorial - Message Queues and Distributed Systems](https://www.youtube.com/watch?v=nFxjaVmFj5E)
  - 🎥 Video: [RabbitMQ in 100 Seconds](https://m.youtube.com/watch?v=NQ3fZtyXji0)
- [ ] Kafka — ☆☆☆☆☆
  - 🏛️ Official: [Apache Kafka](https://kafka.apache.org/quickstart)
  - 🏛️ Official: [Apache Kafka Streams](https://kafka.apache.org/documentation/streams/)
  - 🏛️ Official: [Kafka Streams Confluent](https://docs.confluent.io/platform/current/streams/concepts.html)
  - 🎥 Video: [Apache Kafka Fundamentals](https://www.youtube.com/watch?v=B5j3uNBH8X4)

### 🧠 Quiz

1. Why use a message broker?
   <details><summary>Answer</summary>To decouple services, buffer load, and process work asynchronously and reliably.</details>

2. What is the main difference between Kafka and RabbitMQ?
   <details><summary>Answer</summary>Kafka is a distributed log for high-throughput event streaming with replay; RabbitMQ is a traditional queue broker with flexible routing.</details>

3. What does 'at-least-once delivery' mean for consumers?
   <details><summary>Answer</summary>Messages may be delivered more than once, so consumers should be idempotent.</details>

---

## 22. Search Engines — ☆☆☆☆☆

> Search engines like Elasticsearch are specialized tools for fast, scalable searching and analyzing large data volumes. Built on Apache Lucene, they offer full-text search, real-time indexing, distributed architecture, powerful query DSL, and analytics capabilities for log and event data analysis.

**📚 Learn:**

- 🗺️ Roadmap: [Visit the Dedicated Elasticsearch Roamdap](https://roadmap.sh/elasticsearch)
- 🏛️ Official: [Intro to OpenSearch](https://opensearch.org/docs/latest/getting-started/intro/)
- 📄 Article: [What is Elasticsearch? - Official Docs](https://www.elastic.co/guide/en/elasticsearch/reference/current/elasticsearch-intro.html)
- 🎥 Video: [Elasticsearch Tutorial for Beginners](https://www.youtube.com/watch?v=ZP0NmfyNsuo)

**✅ Checklist:**

- [ ] Elasticsearch — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit the Dedicated Elasticsearch Roadmap](https://roadmap.sh/elasticsearch)
  - 🏛️ Official: [Elasticsearch Website](https://www.elastic.co/elasticsearch/)
  - 🏛️ Official: [Elasticsearch Documentation](https://www.elastic.co/guide/index.html)
  - 🎥 Video: [What is Elasticsearch](https://www.youtube.com/watch?v=ZP0NmfyfsoM)
- [ ] Solr — ☆☆☆☆☆
  - 💻 Open source: [Solr on GitHub](https://github.com/apache/solr)
  - 📄 Article: [Solr Website](https://solr.apache.org/)
  - 📄 Article: [Solr Documentation](https://solr.apache.org/resources.html#documentation)
  - 🎥 Video: [Apache Solr vs Elasticsearch Differences](https://www.youtube.com/watch?v=MMWBdSdbu5k)

### 🧠 Quiz

1. What is an inverted index?
   <details><summary>Answer</summary>A map from each term to the documents that contain it, enabling fast full-text search.</details>

2. Why not just use SQL LIKE '%term%' for search?
   <details><summary>Answer</summary>It's slow on large data, can't use normal indexes, and lacks relevance ranking, stemming and fuzziness.</details>

3. What are Elasticsearch and Solr built on?
   <details><summary>Answer</summary>Apache Lucene.</details>

---

## 23. Real-Time Data — ☆☆☆☆☆

> Real-time data is processed and delivered immediately with minimal delay for prompt system responses. Essential for financial trading, gaming, analytics, and monitoring. Uses stream processing frameworks like Apache Kafka and Flink for high-speed data flows and timely decision-making.

**📚 Learn:**

- 📄 Article: [Real-time Data - Wiki](https://en.wikipedia.org/wiki/Real-time_data)
- 📄 Article: [What is Real-time Data?](https://www.qlik.com/us/streaming-data/real-time-data)

**✅ Checklist:**

- [ ] WebSockets — ☆☆☆☆☆
  - 🏛️ Official: [Socket.io Library Bidirectional and Low-latency Communication for Every Platform](https://socket.io/)
  - 📄 Article: [Introduction to WebSockets](https://www.tutorialspoint.com/websockets/index.htm)
  - 🎥 Video: [A Beginners Guide to WebSockets](https://www.youtube.com/watch?v=8ARodQ4Wlf4)
  - 🎥 Video: [How Web Sockets Work](https://www.youtube.com/watch?v=G0_e02DdH7I)
- [ ] Server Sent Events — ☆☆☆☆☆
  - 📄 Article: [Server Sent Events - MDN](https://developer.mozilla.org/en-US/docs/Web/API/Server-sent_events)
  - 🎥 Video: [Server-Sent Events | Postman Level Up](https://www.youtube.com/watch?v=KrE044J8jEQ&t=1s)
- [ ] Long / Short Polling — ☆☆☆☆☆
  - 📄 Article: [Long Polling](https://javascript.info/long-polling)
  - 🎥 Video: [What is Long Polling?](https://www.youtube.com/watch?v=LD0_-uIsnOE)

### 🧠 Quiz

1. What is the difference between WebSockets and Server-Sent Events?
   <details><summary>Answer</summary>WebSockets are bi-directional; SSE is one-way from server to client over plain HTTP.</details>

2. What is long polling?
   <details><summary>Answer</summary>The client sends a request that the server holds open until data is available, then the client immediately reconnects.</details>

3. Give a use case for WebSockets.
   <details><summary>Answer</summary>Chat, multiplayer games, live collaboration, or real-time dashboards.</details>

---

## 24. NoSQL Databases — ☆☆☆☆☆

> NoSQL databases handle unstructured, semi-structured, or rapidly changing data with flexible schemas. Four types: Document stores (MongoDB, CouchDB), Key-value stores (Redis, Riak), Column-family (Cassandra, HBase), and Graph databases (Neo4j, Neptune). Used for high scalability, flexibility, and performance applications.

**📚 Learn:**

- 📄 Article: [Types of NoSQL Databases: How to Choose the Right One](https://roadmap.sh/backend/types-of-nosql-databases)
- 📄 Article: [NoSQL Explained](https://www.mongodb.com/nosql-explained)
- 🎥 Video: [How do NoSQL Databases work](https://www.youtube.com/watch?v=0buKQHokLK8)
- 🎥 Video: [SQL vs NoSQL Explained](https://www.youtube.com/watch?v=ruz-vK8IesE)

**✅ Checklist:**

- [ ] MongoDB — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated MongoDB Roadmap](https://roadmap.sh/mongodb)
  - 🏛️ Official: [Learning Path for MongoDB Developers](https://learn.mongodb.com/catalog)
  - 📄 Article: [MongoDB Online Sandbox](https://mongoplayground.net/)
- [ ] CouchDB — ☆☆☆☆☆
  - 🏛️ Official: [CouchDB](https://couchdb.apache.org/)
  - 🏛️ Official: [CouchDB Documentation](https://docs.couchdb.org/en/stable/)
  - 🎥 Video: [What is CouchDB?](https://www.youtube.com/watch?v=Mru4sHzIfSA)
- [ ] Firebase — ☆☆☆☆☆
  - 🎓 Course: [The Ultimate Guide to Firebase](https://fireship.io/lessons/the-ultimate-beginners-guide-to-firebase/)
  - 🏛️ Official: [Firebase Documentation](https://firebase.google.com/docs)
  - 🎥 Video: [Firebase in 100 seconds](https://www.youtube.com/watch?v=vAoB4VbhRzM)
- [ ] RethinkDB — ☆☆☆☆☆
  - 🎓 Course: [RethinkDB Crash Course](https://www.youtube.com/watch?v=pW3PFtchHDc)
  - 🏛️ Official: [RethinkDB Website](https://rethinkdb.com/)
  - 🏛️ Official: [Ten-minute Guide with RethinkDB](https://rethinkdb.com/docs/guide/)
- [ ] DynamoDB — ☆☆☆☆☆
  - 🏛️ Official: [AWS DynamoDB](https://aws.amazon.com/dynamodb/)
  - 🎥 Video: [AWS DynamoDB Tutorial For Beginners](https://www.youtube.com/watch?v=2k2GINpO308)
- [ ] Redis — ☆☆☆☆☆
  - 🗺️ Roadmap: [Visit Dedicated Redis Roadmap](https://roadmap.sh/redis)
  - 🎓 Course: [Redis Crash Course](https://www.youtube.com/watch?v=XCsS_NVAa1g)
  - 🏛️ Official: [Redis Documentation](https://redis.io/docs/latest/)
  - 🎥 Video: [Redis Tutorial for Beginners](https://www.youtube.com/watch?v=jgpVdJB2sKQ)
- [ ] Cassandra — ☆☆☆☆☆
  - 🏛️ Official: [Cassandra](https://cassandra.apache.org/_/index.html)
  - 📄 Article: [Cassandra - Quick Guide](https://www.tutorialspoint.com/cassandra/cassandra_quick_guide.htm)
  - 🎥 Video: [Apache Cassandra Database – Full Course for Beginners](https://www.youtube.com/watch?v=J-cSy5MeMOA)
- [ ] ScyllaDB — ☆☆☆☆☆
  - 🏛️ Official: [ScyllaDB](https://www.scylladb.com/)
  - 💻 Open source: [scylladb](https://github.com/scylladb/scylladb)
  - 📄 Article: [Understanding ScyllaDB: A Comprehensive Overview](https://risingwave.com/blog/understanding-scylladb-a-comprehensive-overview/)
  - 🎥 Video: [What Makes ScyllaDB So Fast?](https://www.youtube.com/watch?v=JPkrdWMVpPk)
- [ ] ClickHouse — ☆☆☆☆☆
  - 🏛️ Official: [ClickHouse](https://clickhouse.com/)
  - 🏛️ Official: [What is ClickHouse?](https://clickhouse.com/docs/intro)
  - 💻 Open source: [clickhouse](https://github.com/ClickHouse/ClickHouse)
  - 🎥 Video: [How to Get Started with ClickHouse](https://www.youtube.com/watch?v=6mmQUOmA-T0&list=PL0Z2YDlm0b3gtIdcZI3B_8bMJclDOvY8s)
- [ ] Influx DB — ☆☆☆☆☆
  - 🏛️ Official: [InfluxDB Documentation](https://docs.influxdata.com/influxdb/cloud/)
  - 📄 Article: [Time series database](https://www.influxdata.com/time-series-database/)
  - 📄 Article: [Introduction to InfluxDB - DigitalOcean](https://www.digitalocean.com/community/tutorials/how-to-monitor-system-metrics-with-the-tick-stack-on-centos-7)
  - 🎥 Video: [The Basics of Time Series Data](https://www.youtube.com/watch?v=wBWTj-1XiRU)
- [ ] TimescaleDB — ☆☆☆☆☆
  - 🏛️ Official: [Timescale Website](https://www.timescale.com/)
  - 🎥 Video: [Tutorial - TimeScaleDB Explained in 100 Seconds](https://www.youtube.com/watch?v=69Tzh_0lHJ8)
  - 🎥 Video: [What is Time Series Data?](https://www.youtube.com/watch?v=Se5ipte9DMY)
- [ ] Neo4j — ☆☆☆☆☆
  - 🏛️ Official: [Neo4j Website](https://neo4j.com)
  - 🎥 Video: [Neo4j in 100 Seconds](https://www.youtube.com/watch?v=T6L9EoBy8Zk)
  - 🎥 Video: [Neo4j Course for Beginners](https://www.youtube.com/watch?v=_IgbB24scLI)
- [ ] AWS Neptune — ☆☆☆☆☆
  - 🏛️ Official: [AWS Neptune](https://aws.amazon.com/neptune/)
  - 📄 Article: [Setting Up Amazon Neptune Graph Database](https://cliffordedsouza.medium.com/setting-up-amazon-neptune-graph-database-2b73512a7388)
  - 🎥 Video: [Getting Started with Neptune Serverless](https://www.youtube.com/watch?v=b04-jjM9t4g)
- [ ] DGraph — ☆☆☆☆☆
  - 🏛️ Official: [Dgraph](https://docs.dgraph.io/dgraph-overview)
  - 💻 Open source: [dgraph](https://github.com/dgraph-io/dgraph)
  - 📄 Article: [Dgraph, what is a graph database anyway?](https://medium.com/@JalalOkbi/dgraph-what-is-a-graph-database-anyway-8b6c22fb1eeb)
  - 🎥 Video: [Learn Dgraph in 20 minutes (Graph Database) quick tutorial](https://www.youtube.com/watch?v=roHj5G4vM9Q)

### 🧠 Quiz

1. Name the four main types of NoSQL databases with an example each.
   <details><summary>Answer</summary>Document (MongoDB), key-value (Redis, DynamoDB), wide-column (Cassandra), graph (Neo4j).</details>

2. When might you pick a NoSQL database over a relational one?
   <details><summary>Answer</summary>For flexible schemas, huge scale/high write throughput, or data that fits a specific model (graph, time series).</details>

3. What kind of data is a time-series database like InfluxDB or TimescaleDB built for?
   <details><summary>Answer</summary>Measurements over time, such as metrics, sensor data and events.</details>

---

## 25. Building For Scale — ☆☆☆☆☆

> Scalability is a system's ability to handle growing workload by adding resources. Scalable architecture supports higher workloads without fundamental changes. Two approaches: on-premises (requires planning) or cloud (flexible, easy upgrades). Cloud offers more flexibility than on-premises infrastructure.

**📚 Learn:**

- 📄 Article: [Scalable Architecture: A Definition and How-To Guide](https://www.sentinelone.com/blog/scalable-architecture/)
- 🎥 Video: [Scaling Distributed Systems - Software Architecture Introduction](https://www.youtube.com/watch?v=gxfERVP18-g)

**✅ Checklist:**

- [ ] Observability — ☆☆☆☆☆
  - 📄 Article: [DataDog Docs](https://docs.datadoghq.com/)
  - 📄 Article: [Sentry Docs](https://docs.sentry.io/)
  - 📄 Article: [Observability and Instrumentation: What They Are and Why They Matter](https://newrelic.com/blog/best-practices/observability-instrumentation)
  - 🎥 Video: [What is observability?](https://www.youtube.com/watch?v=--17See0KHs)
- [ ] Instrumentation — ☆☆☆☆☆
  - 📄 Article: [What is Instrumentation?](https://en.wikipedia.org/wiki/Instrumentation_%28computer_programming%29)
  - 📄 Article: [What is Monitoring?](https://www.yottaa.com/performance-monitoring-backend-vs-front-end-solutions/)
  - 📄 Article: [What is Telemetry?](https://www.sumologic.com/insight/what-is-telemetry/)
  - 🎥 Video: [Observability vs. APM vs. Monitoring](https://www.youtube.com/watch?v=CAQ_a2-9UOI)
- [ ] Monitoring — ☆☆☆☆☆
  - 🏛️ Official: [Prometheus Documentation](https://prometheus.io/docs/introduction/overview/)
  - 🏛️ Official: [Grafana Documentation](https://grafana.com/docs/grafana/latest/)
  - 🎥 Video: [Prometheus and Grafana Tutorial for Beginners](https://www.youtube.com/watch?v=9TJx7QTrTyo)
  - 🎥 Video: [Grafana Explained in 5 Minutes](https://www.youtube.com/watch?v=lILY8eSspEo)
- [ ] Telemetry — ☆☆☆☆☆
  - 🎓 Course: [OpenTelemetry Course - Understand Software Performance](https://www.youtube.com/watch?v=r8UvWSX3KA8)
  - 📄 Article: [What is telemetry and how does it work?](https://www.techtarget.com/whatis/definition/telemetry)
- [ ] Graceful Degradation — ☆☆☆☆☆
  - 📄 Article: [What is Graceful Degradation & Why Does it Matter?](https://blog.hubspot.com/website/graceful-degradation)
  - 📄 Article: [Four Considerations When Designing Systems For Graceful Degradation](https://newrelic.com/blog/best-practices/design-software-for-graceful-degradation)
  - 🎥 Video: [Graceful Degradation - Georgia Tech](https://www.youtube.com/watch?v=Tk7e0LMsAlI)
- [ ] Throttling — ☆☆☆☆☆
  - 📄 Article: [Throttling - AWS Well-Architected Framework](https://docs.aws.amazon.com/wellarchitected/2022-03-31/framework/rel_mitigate_interaction_failure_throttle_requests.html)
  - 🎥 Video: [Throttling vs Debouncing](https://www.youtube.com/watch?v=tJhA0DrH5co)
- [ ] Backpressure — ☆☆☆☆☆
  - 📄 Article: [Backpressure explained — the flow of data through software](https://medium.com/@jayphelps/backpressure-explained-the-flow-of-data-through-software-2350b3e77ce7)
  - 📄 Article: [Handling Backpressure in Node.js Streams](https://nodejs.org/learn/modules/backpressuring-in-streams)
  - 🎥 Video: [What is Back Pressure](https://www.youtube.com/watch?v=viTGm_cV7lE)
- [ ] Loadshifting — ☆☆☆☆☆
  - 📄 Article: [Load Shifting](https://en.wikipedia.org/wiki/Load_shifting)
  - 🎥 Video: [Load Shifting 101](https://www.youtube.com/watch?v=DOyMJEdk5aE)
- [ ] Circuit Breaker — ☆☆☆☆☆
  - 🏛️ Official: [Circuit Breaker - Azure Architecture Patterns](https://learn.microsoft.com/en-us/azure/architecture/patterns/circuit-breaker)
  - 💻 Open source: [Resilience4j - Circuit Breaker Library for Java](https://github.com/resilience4j/resilience4j)
  - 📄 Article: [The Circuit Breaker Pattern](https://aerospike.com/blog/circuit-breaker-pattern/)
  - 🎥 Video: [What is the Circuit Breaker Pattern?](https://www.youtube.com/watch?v=ADHcBxEXvFA)

### 🧠 Quiz

1. What are the three pillars of observability?
   <details><summary>Answer</summary>Logs, metrics and traces.</details>

2. What does a circuit breaker do?
   <details><summary>Answer</summary>Stops calling a failing dependency for a while so failures don't cascade, then retries gradually.</details>

3. What is graceful degradation?
   <details><summary>Answer</summary>Keeping core functionality working with reduced features when parts of the system fail.</details>
