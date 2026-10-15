# TypeScript Roadmap — Lessons

**How to use:** tick `[x]` when done, and rate yourself by replacing ☆ with ★ (★☆☆☆☆ = just heard of it · ★★★★★ = can teach it). Quiz answers are hidden — click *Answer* to reveal.

Source: https://roadmap.sh/typescript (lesson order follows the roadmap)

---

## 1. Introduction to TypeScript — ☆☆☆☆☆

> TypeScript is a programming language that builds on JavaScript by adding static types. It essentially acts as a superset of JavaScript, meaning that all valid JavaScript code is also valid TypeScript code. The key addition of static typing allows developers to define the expected data types of variables, function parameters, and return values, which helps catch errors during development and improves code maintainability.

**📚 Learn:**

- 🏛️ Official: [Overview of TypeScript](https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html)
- 🏛️ Official: [TypeScript Official Handbook](https://www.typescriptlang.org/docs/handbook/intro.html)
- 📄 Article: [What Is TypeScript?](https://thenewstack.io/what-is-typescript/)
- 🎥 Video: [Video: Where TypeScript Excels](https://youtu.be/BUo7B6UuoJ4)

**✅ Checklist:**

- [ ] TypeScript vs JavaScript — ☆☆☆☆☆
  - 🏛️ Official: [Learning JavaScript and TypeScript](https://www.typescriptlang.org/docs/handbook/typescript-from-scratch.html#learning-javascript-and-typescript)
  - 📄 Article: [TypeScript vs. JavaScript](https://thenewstack.io/typescript-vs-javascript/)
- [ ] TS and JS Interoperability — ☆☆☆☆☆
  - 🏛️ Official: [Type Checking JavaScript Files](https://www.typescriptlang.org/docs/handbook/type-checking-javascript-files.html)
  - 🎥 Video: [Using JavaScript in TypeScript](https://youtu.be/AZhZlEbBaB4)
- [ ] Installation and Configuration — ☆☆☆☆☆
  - 🏛️ Official: [Install and Configure TypeScript](https://www.typescriptlang.org/download)
  - 📄 Article: [TypeScript Getting Started](https://thenewstack.io/typescript-tutorial-a-guide-to-using-the-programming-language/)
  - [ ] tsconfig.json — ☆☆☆☆☆
    - 🏛️ Official: [What is a tsconfig.json](https://www.typescriptlang.org/docs/handbook/tsconfig-json.html#handbook-content)
  - [ ] Compiler Options — ☆☆☆☆☆
    - 🏛️ Official: [Compiler Options](https://www.typescriptlang.org/docs/handbook/compiler-options.html)
- [ ] Running TypeScript — ☆☆☆☆☆
  - 🏛️ Official: [Running your TypeScript](https://www.typescriptlang.org/docs/handbook/typescript-tooling-in-5-minutes.html)
  - [ ] tsc — ☆☆☆☆☆
    - 🏛️ Official: [tsc CLI Options](https://www.typescriptlang.org/docs/handbook/compiler-options.html#using-the-cli)
  - [ ] ts-node — ☆☆☆☆☆
    - 💻 Open source: [ts-node - GitHub Project](https://github.com/TypeStrong/ts-node)
    - 📄 Article: [How To Run TypeScript Scripts with ts-node](https://www.digitalocean.com/community/tutorials/typescript-running-typescript-ts-node)
  - [ ] TS Playground — ☆☆☆☆☆
    - 🏛️ Official: [TypeScript Official - Playground](https://www.typescriptlang.org/play)

### 🧠 Quiz

1. What is TypeScript?
   <details><summary>Answer</summary>A typed superset of JavaScript that compiles to plain JavaScript.</details>

2. Do TypeScript types exist at runtime?
   <details><summary>Answer</summary>No, they are erased during compilation; they only help at development/compile time.</details>

3. What does tsconfig.json do?
   <details><summary>Answer</summary>Configures the compiler: target, module system, strictness, included files and more.</details>

---

## 2. TypeScript Types — ☆☆☆☆☆

> TypeScript Types define the kind of values a variable can hold. They essentially act as labels that specify the allowed data types, like numbers, strings, or more complex objects. By assigning types, TypeScript can perform static type checking, catching potential errors during development before the code is even run. This helps improve code reliability and makes it easier to understand how data flows through your application.

**📚 Learn:**

- 🏛️ Official: [TypeScript - Everyday Types](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html)

**✅ Checklist:**

- [ ] Primitive types — ☆☆☆☆☆
  - [ ] boolean — ☆☆☆☆☆
    - 📄 Article: [Number, String, Boolean, Symbol and Object](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)
  - [ ] number — ☆☆☆☆☆
    - 🏛️ Official: [Number, String, Boolean, Symbol and Object](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)
  - [ ] string — ☆☆☆☆☆
    - 🏛️ Official: [Number, String, Boolean, Symbol and Object](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#the-primitives-string-number-and-boolean)
  - [ ] void — ☆☆☆☆☆
    - 🏛️ Official: [void - TypeScript Docs](https://www.typescriptlang.org/docs/handbook/2/functions.html#void)
  - [ ] undefined — ☆☆☆☆☆
    - 🏛️ Official: [null and undefined](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#null-and-undefined)
  - [ ] null — ☆☆☆☆☆
    - 🏛️ Official: [null and undefined](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#null-and-undefined)
- [ ] Object types — ☆☆☆☆☆
  - [ ] Object — ☆☆☆☆☆
    - 🏛️ Official: [Object Types in TypeScript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#object-types)
  - [ ] Interface — ☆☆☆☆☆
    - 🏛️ Official: [Object Types - Interfaces](https://www.typescriptlang.org/docs/handbook/2/objects.html)
  - [ ] Class — ☆☆☆☆☆
    - 🏛️ Official: [TypeScript Classes](https://www.typescriptlang.org/docs/handbook/2/classes.html)
  - [ ] Enum — ☆☆☆☆☆
    - 🏛️ Official: [TypeScript - Enums](https://www.typescriptlang.org/docs/handbook/enums.html)
  - [ ] Array — ☆☆☆☆☆
    - 🏛️ Official: [Arrays](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#arrays)
  - [ ] Tuple — ☆☆☆☆☆
    - 🏛️ Official: [Tuple Types](https://www.typescriptlang.org/docs/handbook/2/objects.html#tuple-types)
- [ ] unknown — ☆☆☆☆☆
  - 🏛️ Official: [Unknown Type in TypeScript](https://www.typescriptlang.org/docs/handbook/release-notes/typescript-3-0.html#new-unknown-top-type)
- [ ] any — ☆☆☆☆☆
  - 🏛️ Official: [any type in TypeScript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#any)
- [ ] never — ☆☆☆☆☆
  - 🏛️ Official: [Never Type](https://www.typescriptlang.org/docs/handbook/2/narrowing.html#the-never-type)
- [ ] Type assertions — ☆☆☆☆☆
  - [ ] as const — ☆☆☆☆☆
    - 🏛️ Official: [const assertions](https://www.typescriptlang.org/docs/handbook/release-notes/typescript-3-4.html#const-assertions)
  - [ ] as [type] — ☆☆☆☆☆
    - 🏛️ Official: [Type assertions](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#type-assertions)
  - [ ] as any — ☆☆☆☆☆
    - 🏛️ Official: [any](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#any)
  - [ ] Non-null Assertion — ☆☆☆☆☆
    - 🏛️ Official: [Non-null assertion operator](https://www.typescriptlang.org/docs/handbook/release-notes/typescript-2-0.html#non-null-assertion-operator)
- [ ] satisfies keyword — ☆☆☆☆☆
  - 🏛️ Official: [satisfies Keyword](https://www.typescriptlang.org/docs/handbook/release-notes/typescript-4-9.html#the-satisfies-operator)

### 🧠 Quiz

1. What is the difference between any and unknown?
   <details><summary>Answer</summary>any turns off type checking; unknown requires narrowing before use, so it's type-safe.</details>

2. When is never used?
   <details><summary>Answer</summary>For values that never occur: functions that always throw or loop forever, and exhaustive checks.</details>

3. What does as const do?
   <details><summary>Answer</summary>Makes a value deeply readonly and infers the narrowest literal types.</details>

---

## 3. Type Inference — ☆☆☆☆☆

> Type inference is the automatic deduction of the data type of an expression in a programming language. Instead of explicitly declaring the type of a variable, the compiler or interpreter can infer it based on the value assigned to it or how it's used within the code. This reduces the need for verbose type annotations, making code more concise and readable while still providing the benefits of type safety.

**📚 Learn:**

- 🏛️ Official: [Type Inference](https://www.typescriptlang.org/docs/handbook/type-inference.html#handbook-content)

**✅ Checklist:**

- [ ] Type Inference — ☆☆☆☆☆

### 🧠 Quiz

1. What type does TypeScript infer for let x = 5 and const y = 5?
   <details><summary>Answer</summary>x: number, y: 5 (a literal type because const can't change).</details>

2. When should you add explicit type annotations?
   <details><summary>Answer</summary>On function parameters, public APIs/return types, and when inference is too wide or unclear.</details>

3. What is contextual typing?
   <details><summary>Answer</summary>Inferring types from where a value is used, e.g. the parameter types of a callback passed to arr.map.</details>

---

## 4. Type Compatibility — ☆☆☆☆☆

> Type compatibility is a mechanism in TypeScript that determines whether one type can be assigned to another based on the structure of the types. Unlike languages that use nominal typing where compatibility is based on explicit declarations, TypeScript uses structural typing to compare members. If a target type has all the required members of a source type, the compiler considers them compatible, regardless of their specific names or hierarchies.

**📚 Learn:**

- 🏛️ Official: [Type Compatibility](https://www.typescriptlang.org/docs/handbook/type-compatibility.html)

**✅ Checklist:**

- [ ] Type Compatibility — ☆☆☆☆☆

### 🧠 Quiz

1. What does 'structural typing' mean?
   <details><summary>Answer</summary>Types are compatible if their shapes match, regardless of their names.</details>

2. Can an object with extra properties be assigned to a type with fewer properties?
   <details><summary>Answer</summary>Yes, from a variable; but an object literal assigned directly gets an excess property error.</details>

3. Is { name: string } assignable to { name: string; age: number }?
   <details><summary>Answer</summary>No, it's missing the required age property.</details>

---

## 5. Combining Types — ☆☆☆☆☆

> Combining types in TypeScript allows you to create new, more complex types from existing ones. This is achieved through features like unions and intersections. A union type lets a variable hold values of different types, while an intersection type combines multiple types into a single type that has all the properties of each individual type. These mechanisms provide flexibility and expressiveness when defining the shape of your data.

**📚 Learn:**

- 🏛️ Official: [Union Types in TypeScript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#union-types)
- 📄 Article: [Intersection Types in TypeScript](https://www.typescripttutorial.net/typescript-tutorial/typescript-intersection-types/)
- 📄 Article: [Type Aliases](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#type-aliases)
- 📄 Article: [Keyof Type Operator](https://www.typescriptlang.org/docs/handbook/2/keyof-types.html#handbook-content)

**✅ Checklist:**

- [ ] Union Types — ☆☆☆☆☆
  - 🏛️ Official: [Union Types in TypeScript](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#union-types)
- [ ] Intersection Types — ☆☆☆☆☆
  - 📄 Article: [Intersection Types in TypeScript](https://www.typescripttutorial.net/typescript-tutorial/typescript-intersection-types/)
- [ ] Type Aliases — ☆☆☆☆☆
  - 🏛️ Official: [Type Aliases](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#type-aliases)
- [ ] keyof Operator — ☆☆☆☆☆
  - 🏛️ Official: [keyof Type Operator](https://www.typescriptlang.org/docs/handbook/2/keyof-types.html#handbook-content)

### 🧠 Quiz

1. What is the difference between a union and an intersection type?
   <details><summary>Answer</summary>A | B means either A or B; A &amp; B means both at once (all properties combined).</details>

2. What does keyof do?
   <details><summary>Answer</summary>Produces a union of the property names of a type, e.g. keyof {a: 1; b: 2} is 'a' | 'b'.</details>

3. What is a discriminated union?
   <details><summary>Answer</summary>A union whose members share a literal property (e.g. kind) used to narrow which member you have.</details>

---

## 6. TypeScript Interfaces — ☆☆☆☆☆

> Interfaces in TypeScript are a way to define a contract for the structure of an object. They describe the shape that an object should have, specifying the names, types, and optionality of its properties. Essentially, an interface names a specific combination of fields and their types. These interfaces don't compile into JavaScript; they are purely a TypeScript construct used for type-checking during development.

**📚 Learn:**

- 🏛️ Official: [TypeScript - Interfaces](https://www.typescriptlang.org/docs/handbook/2/objects.html)

**✅ Checklist:**

- [ ] Types vs Interfaces — ☆☆☆☆☆
  - 🏛️ Official: [Interfaces vs. Type Aliases](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#differences-between-type-aliases-and-interfaces)
  - 📄 Article: [Interfaces vs Types in TypeScript](https://stackoverflow.com/questions/37233735/interfaces-vs-types-in-typescript)
- [ ] Interface Declaration — ☆☆☆☆☆
  - 🏛️ Official: [Extending Interfaces](https://www.typescriptlang.org/docs/handbook/2/objects.html)
- [ ] Extending Interfaces — ☆☆☆☆☆
  - 🏛️ Official: [Extending Interfaces](https://www.typescriptlang.org/docs/handbook/2/objects.html)
- [ ] Hybrid Types — ☆☆☆☆☆

### 🧠 Quiz

1. When would you choose interface over type?
   <details><summary>Answer</summary>For object shapes that may be extended or merged (e.g. public APIs); type for unions, tuples and computed types.</details>

2. What is declaration merging?
   <details><summary>Answer</summary>Multiple interface declarations with the same name are merged into one.</details>

3. How do you make a property optional or readonly?
   <details><summary>Answer</summary>name?: string and readonly id: number.</details>

---

## 7. Type Guards / Narrowing — ☆☆☆☆☆

> Type guards and narrowing are techniques in TypeScript used to refine the type of a variable within a specific scope. They allow you to tell the TypeScript compiler that a variable is more specific than its declared type, enabling you to safely perform operations that would otherwise result in type errors. This is particularly useful when dealing with union types or situations where the initial type of a variable is broad.

**📚 Learn:**

- 🏛️ Official: [Type Guards - TypeScript Docs](https://www.typescriptlang.org/docs/handbook/2/narrowing.html#typeof-type-guards)

**✅ Checklist:**

- [ ] typeof — ☆☆☆☆☆
  - 🏛️ Official: [Type Guards and Differentiating Types](https://www.typescriptlang.org/docs/handbook/2/narrowing.html#typeof-type-guards)
- [ ] instanceof — ☆☆☆☆☆
  - 🏛️ Official: [instanceOf Operator](https://www.typescriptlang.org/docs/handbook/2/narrowing.html#instanceof-narrowing)
- [ ] Equality — ☆☆☆☆☆
  - 🏛️ Official: [Equality Narrowing](https://www.typescriptlang.org/docs/handbook/2/narrowing.html#equality-narrowing)
- [ ] Truthiness — ☆☆☆☆☆
  - 🏛️ Official: [Truthiness Narrowing](https://www.typescriptlang.org/docs/handbook/2/narrowing.html#truthiness-narrowing)
- [ ] Type Predicates — ☆☆☆☆☆
  - 🏛️ Official: [Type Guards and Differentiating Types](https://www.typescriptlang.org/docs/handbook/2/narrowing.html#using-type-predicates)

### 🧠 Quiz

1. Name three ways to narrow a type.
   <details><summary>Answer</summary>typeof, instanceof, the in operator, equality checks, truthiness checks, discriminant properties.</details>

2. What is a type predicate?
   <details><summary>Answer</summary>A function return type like value is string that tells TypeScript the type when it returns true.</details>

3. How do you make a switch over a union exhaustive?
   <details><summary>Answer</summary>Assign the value to a never variable in the default case, so a missing case causes a compile error.</details>

---

## 8. TypeScript Functions — ☆☆☆☆☆

> Functions in TypeScript are reusable blocks of code designed to perform specific tasks. They can accept inputs (parameters), process them, and return a result. TypeScript enhances JavaScript functions by adding type annotations to parameters and return values, enabling better code clarity and error checking during development. This helps ensure that functions receive and produce the expected data types, leading to more robust and maintainable code.

**📚 Learn:**

- 🏛️ Official: [Functions in TypeScript](https://www.typescriptlang.org/docs/handbook/2/functions.html)

**✅ Checklist:**

- [ ] Typing Functions — ☆☆☆☆☆
  - 🏛️ Official: [TypeScript Functions](https://www.typescriptlang.org/docs/handbook/2/functions.html)
- [ ] Function Overloading — ☆☆☆☆☆
  - 🏛️ Official: [Function Overloads](https://www.typescriptlang.org/docs/handbook/2/functions.html#function-overloads)

### 🧠 Quiz

1. How do you type a function's parameters and return type?
   <details><summary>Answer</summary>function add(a: number, b: number): number { ... }.</details>

2. What is function overloading in TypeScript?
   <details><summary>Answer</summary>Declaring multiple call signatures for one function implementation.</details>

3. How do you type a callback parameter?
   <details><summary>Answer</summary>With a function type, e.g. (cb: (err: Error | null, data?: string) =&gt; void).</details>

---

## 9. Classes — ☆☆☆☆☆

> Classes are blueprints for creating objects, encapsulating data (properties) and behavior (methods) into a single unit. They provide a structured way to define the characteristics and actions that an object of that class can possess. This allows for creating multiple instances of the same object type with consistent properties and methods.

**📚 Learn:**

- 🏛️ Official: [Tutorial - Classes](https://www.typescriptlang.org/docs/handbook/2/classes.html)

**✅ Checklist:**

- [ ] Constructor Params — ☆☆☆☆☆
  - 🏛️ Official: [TypeScript - Construct](https://www.typescriptlang.org/docs/handbook/2/classes.html#constructors)
- [ ] Constructor Overloading — ☆☆☆☆☆
  - 🏛️ Official: [Constructors - TypeScript](https://www.typescriptlang.org/docs/handbook/2/classes.html#constructors)
- [ ] Access Modifiers — ☆☆☆☆☆
  - 🏛️ Official: [TypeScript Access Modifiers](https://www.typescripttutorial.net/typescript-tutorial/typescript-access-modifiers/)
- [ ] Abstract Classes — ☆☆☆☆☆
  - 🏛️ Official: [Abstract Classes](https://www.typescriptlang.org/docs/handbook/2/classes.html#abstract-classes-and-members)
- [ ] Inheritance vs Polymorphism — ☆☆☆☆☆
  - 📄 Article: [Dev.to - Mastering OOP in TypeScript](https://dev.to/rajrathod/mastering-object-oriented-programming-with-typescript-encapsulation-abstraction-inheritance-and-polymorphism-explained-c6p)
  - 🎥 Video: [Inheritance and Polymorphism In TypeScript](https://www.youtube.com/watch?v=Sn6K57YSuwU)
- [ ] Method Overriding — ☆☆☆☆☆
  - 🏛️ Official: [TypeScript - Overriding Methods](https://www.typescriptlang.org/docs/handbook/2/classes.html#overriding-methods)

### 🧠 Quiz

1. What are the access modifiers in TypeScript?
   <details><summary>Answer</summary>public (default), private (class only), protected (class and subclasses).</details>

2. What is an abstract class?
   <details><summary>Answer</summary>A class that can't be instantiated and may declare abstract methods that subclasses must implement.</details>

3. What are parameter properties?
   <details><summary>Answer</summary>Shorthand like constructor(private name: string) {} that declares and assigns a property.</details>

---

## 10. Generics — ☆☆☆☆☆

> Generics are a way to write code that can work with a variety of types without knowing those types ahead of time. They allow you to define type variables that can be used to represent the specific type that will be used when the code is actually executed. This makes your code more reusable and type-safe by preventing errors that could occur if you were to use `any` or other less specific types.

**📚 Learn:**

- 🏛️ Official: [Hello World of Generics](https://www.typescriptlang.org/docs/handbook/2/generics.html#hello-world-of-generics)

**✅ Checklist:**

- [ ] Generic Types — ☆☆☆☆☆
  - 🏛️ Official: [Hello World of Generics](https://www.typescriptlang.org/docs/handbook/2/generics.html#hello-world-of-generics)
- [ ] Generic Constraints — ☆☆☆☆☆
  - 🏛️ Official: [Generic Constraints - TypeScript](https://www.typescriptlang.org/docs/handbook/2/generics.html#generic-constraints)

### 🧠 Quiz

1. Why use generics?
   <details><summary>Answer</summary>To write reusable code that works with many types while preserving type information.</details>

2. How do you constrain a generic?
   <details><summary>Answer</summary>With extends, e.g. function getLen&lt;T extends { length: number }&gt;(x: T).</details>

3. What does function identity&lt;T&gt;(x: T): T return when called with 'hi'?
   <details><summary>Answer</summary>The type 'hi' (or string), whatever T was inferred as.</details>

---

## 11. Utility Types — ☆☆☆☆☆

> Utility Types in TypeScript are built-in generic types that perform common type transformations. They allow you to create new types based on existing ones by applying operations like making properties optional, required, readonly, or picking specific properties. These utilities enhance type safety and code reusability by enabling you to express complex type manipulations in a concise and declarative way.

**📚 Learn:**

- 🏛️ Official: [TypeScript - Utility Types](https://www.typescriptlang.org/docs/handbook/utility-types.html)
- 📄 Article: [TypeScript Utility Types Guide](https://camchenry.com/blog/typescript-utility-types)

**✅ Checklist:**

- [ ] Partial — ☆☆☆☆☆
- [ ] Pick — ☆☆☆☆☆
  - 🏛️ Official: [Pick\<Type, Keys\>](https://www.typescriptlang.org/docs/handbook/utility-types.html#picktype-keys)
- [ ] Omit — ☆☆☆☆☆
  - 🏛️ Official: [Omit\<Type, Keys\>](https://www.typescriptlang.org/docs/handbook/utility-types.html#omittype-keys)
- [ ] Readonly — ☆☆☆☆☆
- [ ] Record — ☆☆☆☆☆
  - 🏛️ Official: [Record\<Keys, Type\>](https://www.typescriptlang.org/docs/handbook/utility-types.html#recordkeys-type)
- [ ] Exclude — ☆☆☆☆☆
  - 🏛️ Official: [Exclude\<UnionType, ExcludedMembers\>](https://www.typescriptlang.org/docs/handbook/utility-types.html#excludeuniontype-excludedmembers)
- [ ] Extract — ☆☆☆☆☆
  - 🏛️ Official: [Extract\<Type, Union\>](https://www.typescriptlang.org/docs/handbook/utility-types.html#extracttype-union)
- [ ] NonNullable — ☆☆☆☆☆
- [ ] Parameters — ☆☆☆☆☆
- [ ] ReturnType — ☆☆☆☆☆
- [ ] InstanceType — ☆☆☆☆☆
- [ ] Awaited — ☆☆☆☆☆

### 🧠 Quiz

1. What do Partial, Required and Readonly do?
   <details><summary>Answer</summary>Make all properties optional, required, or readonly.</details>

2. What is the difference between Pick and Omit?
   <details><summary>Answer</summary>Pick keeps only the listed properties; Omit removes them.</details>

3. How do you get the return type of a function type?
   <details><summary>Answer</summary>ReturnType&lt;typeof fn&gt;.</details>

---

## 12. Decorators — ☆☆☆☆☆

> Decorators are a special kind of declaration that can be attached to a class declaration, method, accessor, property, or parameter. They use the form `@expression`, where `expression` must evaluate to a function that will be called at runtime with information about the decorated declaration. Decorators provide a way to add both annotations and a meta-programming syntax for class declarations and members. They essentially modify the behavior or functionality of the decorated code in a declarative way.

**📚 Learn:**

- 🏛️ Official: [Decorators](https://www.typescriptlang.org/docs/handbook/decorators.html#handbook-content)

**✅ Checklist:**

- [ ] Decorators — ☆☆☆☆☆

### 🧠 Quiz

1. What is a decorator?
   <details><summary>Answer</summary>A special function applied with @ to classes, methods, accessors or fields to add or modify behavior.</details>

2. Name a framework that heavily uses decorators.
   <details><summary>Answer</summary>Angular or NestJS (also TypeORM).</details>

3. Are TC39 standard decorators the same as the old experimentalDecorators?
   <details><summary>Answer</summary>No, TypeScript 5+ supports the standard version, which has a different API from legacy experimentalDecorators.</details>

---

## 13. Advanced Types — ☆☆☆☆☆

> Advanced types are sophisticated features in TypeScript that allow developers to create flexible and reusable code by composing existing types in complex ways. These tools include features like union types, intersection types, mapped types, and conditional types, which enable the creation of highly expressive type definitions. By leveraging these patterns, you can define precise constraints for your data structures and ensure type safety even in scenarios where the structure of an object is dynamic or dependent on other values.

**📚 Learn:**

- 🏛️ Official: [Advanced Topics](https://www.typescriptlang.org/docs/handbook/type-compatibility.html#advanced-topics)
- 🎥 Video: [Tutorial of Typescript - Advanced Types](https://www.youtube.com/playlist?list=PLw5h0DiJ-9PBIgIyd2ZA1CVnJf0BLFJg2)

**✅ Checklist:**

- [ ] Literal Types — ☆☆☆☆☆
  - 🏛️ Official: [Literal Types](https://www.typescriptlang.org/docs/handbook/2/everyday-types.html#literal-types)
- [ ] Template Literal Types — ☆☆☆☆☆
  - 🏛️ Official: [Template Literal Types](https://www.typescriptlang.org/docs/handbook/2/template-literal-types.html#handbook-content)
- [ ] Mapped Types — ☆☆☆☆☆
  - 🏛️ Official: [Mapped Types](https://www.typescriptlang.org/docs/handbook/2/mapped-types.html#handbook-content)
- [ ] Conditional Types — ☆☆☆☆☆
  - 🏛️ Official: [Conditional Types](https://www.typescriptlang.org/docs/handbook/2/conditional-types.html#handbook-content)
  - 🎥 Video: [Conditional Types - Advanced TypeScript](https://www.youtube.com/watch?v=QFWrbNehKk0)
- [ ] Recursive Types — ☆☆☆☆☆
  - 🏛️ Official: [Recursive Types in TypeScript](https://www.typescriptlang.org/play/3-7/types-and-code-flow/recursive-type-references.ts.html)

### 🧠 Quiz

1. What is a conditional type?
   <details><summary>Answer</summary>A type of the form T extends U ? X : Y, chosen based on a type relationship.</details>

2. What is a mapped type?
   <details><summary>Answer</summary>A type that transforms each property of another type, e.g. { [K in keyof T]: T[K] | null }.</details>

3. What is a template literal type?
   <details><summary>Answer</summary>A string type built from others, e.g. type EventName = `on${Capitalize&lt;string&gt;}`.</details>

---

## 14. TypeScript Modules — ☆☆☆☆☆

> Modules in TypeScript (and JavaScript) are a way to organize code into reusable and manageable blocks. Each module encapsulates its own variables, functions, classes, and interfaces, preventing naming collisions and promoting code modularity. Modules explicitly export parts that other code can use and import modules to gain access to their exported functionalities.

**📚 Learn:**

- 🏛️ Official: [Modules](https://www.typescriptlang.org/docs/handbook/modules.html#handbook-content)
- 🎥 Video: [TypeScript - Modules](https://www.youtube.com/watch?v=EpOPR03z4Vw)

**✅ Checklist:**

- [ ] External Modules — ☆☆☆☆☆
  - 📄 Article: [TypeScript - External Module](https://learncodeweb.com/typescript/modules-in-typescript-explain-with-an-example/)
- [ ] Namespaces — ☆☆☆☆☆
  - 🏛️ Official: [Overview of Namespaces](https://www.typescriptlang.org/docs/handbook/namespaces.html)
  - 🏛️ Official: [Namespaces and Modules](https://www.typescriptlang.org/docs/handbook/namespaces-and-modules.html)
  - 🏛️ Official: [TypeScript - Using Namespaces](https://typescriptlang.org/docs/handbook/namespaces-and-modules.html#using-namespaces)
- [ ] Ambient Modules — ☆☆☆☆☆
  - 🏛️ Official: [Ambient Modules](https://www.typescriptlang.org/docs/handbook/modules/reference.html#ambient-modules)
- [ ] Namespace Augmentation — ☆☆☆☆☆
  - 🏛️ Official: [Module Augmentation](https://www.typescriptlang.org/docs/handbook/declaration-merging.html#module-augmentation)
- [ ] Global Augmentation — ☆☆☆☆☆
  - 🏛️ Official: [Global augmentation](https://www.typescriptlang.org/docs/handbook/declaration-merging.html#global-augmentation)

### 🧠 Quiz

1. What makes a file a module in TypeScript?
   <details><summary>Answer</summary>Having a top-level import or export.</details>

2. What is a .d.ts file?
   <details><summary>Answer</summary>A declaration file that describes types for JavaScript code, without implementation.</details>

3. What is module augmentation used for?
   <details><summary>Answer</summary>Adding types to an existing module or global scope, e.g. extending a library's interface.</details>

---

## 15. Ecosystem — ☆☆☆☆☆

> The TypeScript ecosystem refers to the collection of tools, libraries, frameworks, and resources that support and enhance TypeScript development. It includes everything from build tools and linters to UI libraries and server-side frameworks that have TypeScript definitions available or are specifically designed to work well with TypeScript. The ecosystem also incorporates community resources like documentation, tutorials, and open-source projects that help developers learn and use TypeScript effectively.

**✅ Checklist:**

- [ ] Formatting — ☆☆☆☆☆
  - 📄 Article: [Prettier Website](https://prettier.io)
  - 📄 Article: [Why Prettier](https://prettier.io/docs/en/why-prettier.html)
  - 📄 Article: [BiomeJS Website](https://biomejs.dev)
- [ ] Linting — ☆☆☆☆☆
  - 📄 Article: [ESLint Official Website](https://eslint.org/)
  - 📄 Article: [Introduction to ESLint](https://dev.to/shivambmgupta/eslint-what-why-when-how-5f1d)
  - 🎥 Video: [ESLint Quickstart - find errors automatically](https://www.youtube.com/watch?v=qhuFviJn-es)
- [ ] Build Tools — ☆☆☆☆☆
  - 🏛️ Official: [webpack is a static module bundler for modern JavaScript applications](https://webpack.js.org/)
  - 🏛️ Official: [Vite Next Generation Frontend Tooling](https://vitejs.dev)
  - 🏛️ Official: [Parcel is a zero configuration build tool for the web](https://parceljs.org/)
  - 🏛️ Official: [esbuild is an extremely fast JavaScript bundler and minifier](https://esbuild.github.io/)
- [ ] Useful Packages — ☆☆☆☆☆
  - 🏛️ Official: [zod](https://zod.dev/)
  - 🏛️ Official: [valibot](https://valibot.dev/)
  - 🏛️ Official: [ts-node](https://typestrong.org/ts-node)
  - 💻 Open source: [ts-morph](https://github.com/dsherret/ts-morph)
  - 💻 Open source: [ts-jest](https://github.com/kulshekhar/ts-jest)
  - 💻 Open source: [typesync](https://github.com/jeffijoe/typesync)

### 🧠 Quiz

1. What is typescript-eslint?
   <details><summary>Answer</summary>Tooling that lets ESLint parse TypeScript and adds type-aware lint rules.</details>

2. Name two tools that can compile/run TypeScript quickly.
   <details><summary>Answer</summary>esbuild, SWC, tsx, Vite, Bun or Deno.</details>

3. What does Zod add on top of TypeScript?
   <details><summary>Answer</summary>Runtime validation with schemas, from which static types can be inferred.</details>
