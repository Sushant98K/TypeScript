
# 📘 TypeScript Daily Learning Roadmap (10 Days)

> Ideal for those with basic JavaScript knowledge planning to start **Angular** and **React** development.

---

## 📅 Day 1: Introduction to TypeScript
- ✅ What is TypeScript?
- ✅ Installing TypeScript (`npm install -g typescript`)
- ✅ Using the `tsc` CLI
- ✅ Writing and compiling your first `.ts` file

**Practice:**
```ts
let message: string = "Hello, TypeScript!";
console.log(message);
```

---

## 📅 Day 2: Type Annotations & Basic Types
- ✅ Primitive types: `string`, `number`, `boolean`
- ✅ Special types: `any`, `unknown`, `void`, `never`, `null`, `undefined`
- ✅ Type inference

**Practice:**
- Create a function that takes name and age, and returns a greeting.

---

## 📅 Day 3: Arrays, Tuples, and Enums
- ✅ Typed arrays
- ✅ Tuples
- ✅ Enums (numeric and string enums)

**Practice:**
- Define a tuple for a product: `[id: number, name: string]`
- Create an enum for user roles

---

## 📅 Day 4: Functions in TypeScript
- ✅ Function parameter types & return types
- ✅ Optional, default, and rest parameters
- ✅ Arrow functions

**Practice:**
- Write a function to calculate the average of a list of numbers using rest params.

---

## 📅 Day 5: Type Aliases and Interfaces
- ✅ `type` vs `interface`
- ✅ Optional & readonly properties
- ✅ Extending interfaces

**Practice:**
- Define an interface for a `User` with `name`, `email`, and optional `age`.

---

## 📅 Day 6: Classes and Access Modifiers
- ✅ Class properties and methods
- ✅ Access modifiers: `public`, `private`, `protected`
- ✅ `readonly`, `static`, and inheritance

**Practice:**
- Create a `Person` class and extend it with a `Student` class.

---

## 📅 Day 7: Advanced Types
- ✅ Union and Intersection types
- ✅ Type guards
- ✅ Literal types and type narrowing

**Practice:**
- Write a function that takes either a `string` or `number` and logs its type.

---

## 📅 Day 8: Generics
- ✅ Generic functions and interfaces
- ✅ Constraints and default types

**Practice:**
- Create a generic function `identity<T>(arg: T): T`.

---

## 📅 Day 9: TypeScript with React & Angular Basics
- ✅ Setup `tsconfig.json`
- ✅ React with TypeScript (`.tsx`, props & state types)
- ✅ Angular with TypeScript (decorators, typing services & components)

**Practice:**
- Setup a basic component in both Angular and React using TypeScript.

---

## 📅 Day 10: Utility Types & Real-world Practice
- ✅ TypeScript utility types: `Partial`, `Pick`, `Omit`, `Readonly`, `Record`, `Required`
- ✅ Real-world usage for forms and API data handling

**Practice:**
- Simulate API response types and use type-safe data.

---

## ✅ What’s Next?

### For React:
- Use `props`, `useState`, and `useEffect` with types
- Learn about `React.FC`, `PropsWithChildren`, and `useContext` with TypeScript

### For Angular:
- Explore `@Input`, `@Output`, services, and RxJS observables with typing
- Use strong typing in templates and components

---

**Want this as a Notion template or downloadable PDF? Let me know!**
