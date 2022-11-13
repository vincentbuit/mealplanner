# Meal Planner (frond end)

Manage your own recipes, plan your meals for the week and automatically create a groceries list. This is an over-engineered application for learning new technologies and concepts that will make me a better developer overall. See also the back end repo: https://github.com/vincentbuit/mealplanner-back-end.

## Technologies and concepts to master in the front end

### Technologies

- Modern React (framework)
    - React default state management
    - Typescript (type checking js)
        - Advanced type definitions
        - Setting up tsconfig
        - ESLint (lint)
        - Prettier (beautifyer)
- Cypress (testing)
- ReactiveX: RxJS (reactive programming)
- Webpack (bundling)
- Flexbox (responsiveness & layout)
- Husky (git hooks)
- Git (version control)
    - Small and atomic commits
    - Branches which are easy to review and follow an easy to understand narrative
    - Splitting, combining commits and everything else related to interactive rebase    
    - Using git history to your advantage by searching through previous commit messages and code changes using ```git log``` and ```git blame```

### Concepts

- Functional programming: https://github.com/MostlyAdequate/mostly-adequate-guide
    - Pure functions
    - Currying
    - Coding by composing
    - Hindley-Milner type system
    - Functors
    - Monads
- Design, styling, UI/UX
- Standards: Don’t allow bad designs, wrong decisions or poor code. (The Pragmatic Programmer p6)
- Documentation: Restrict non-API commenting to discussing why something is done, its purpose and its goal. (The Pragmatic Programmer p23)
- Easy To Change (ETC): Isolate concerns, single responsibility, good naming and write replaceable code. (The Pragmatic Programmer p28)
- Don’t Repeat Yourself (DRY): No duplication in code, documentation, data and APIs. (The Pragmatic Programmer p30)
- Reusibility: Make code easy to reuse. (The Pragmatic Programmer p37)
- Orthogonality: Eliminate effects between unrelated things. (The Pragmatic Programmer p39)
- Flexibility: There are no final decisions, remain as flexible as you can. (The Pragmatic Programmer p48)
- Tracer bullets: Quickly, visibly and repeatably get from requirements to some aspect of the final system. (The Pragmatic Programmer p50)
- Estimate: Iterate the schedule with the code to better communicate when projects are finished. (The Pragmatic Programmer p65)
- Engineering daybook: Learn from choices, bugs for the future by writing it down. (The Pragmatic Programmer p100)
- Design by Contract (DBC): Think about preconditions, postconditions and repercussions. (The Pragmatic Programmer p104)
- Memory leaks: Prevent them by acting locally. (The Pragmatic Programmer p121)
- Parameterization: Using external configuration to control your app. (The Pragmatic Programmer p166)
- Refactoring: Doing it early and doing it often. (The Pragmatic Programmer p209)
- Test driven development. (The Pragmatic Programmer p214)
- Naming: Name well and rename when needed. (The Pragmatic Programmer p238)

## Plan

### Stage 1: Setup project

- ~~Design a plan including recourses~~
- Setup new react project and decide which toolchain to use (new or existing, next.js?)
    - https://reactjs.org/docs/create-a-new-react-app.html
    - https://reactjs.org/docs/create-a-new-react-app.html#more-flexible-toolchains
    - https://medium.com/@JedaiSaboteur/creating-a-react-app-from-scratch-f3c693b84658
    - https://reactjs.org/docs/optimizing-performance.html#use-the-production-build
- Setup tsconfig and study advanced type definitions and type assertions (DBC)
    - https://www.typescriptlang.org/docs/handbook/tsconfig-json.html
    - https://www.typescriptlang.org/docs/handbook/advanced-types.html
    - https://www.typescriptlang.org/tsconfig#strict
    - https://mariusschulz.com/blog/assertion-functions-in-typescript
- Setup cypress, RxJS, purify and webpack
    - https://webpack.js.org/concepts/
    - https://dev.to/daslaf/using-react-and-rxjs-together-5c5l
    - https://github.com/gigobyte/purify
- Setup ESLint and Prettier using Husky (git hooks)
    - https://kemilbeltre.medium.com/how-to-setup-git-commit-hooks-with-husky-in-a-react-app-24fa05919b7
    - https://www.reactnative.guide/6-conventions-and-code-style/6.2-git-pre-hooks.html
    - ESLint
        - https://eslint.org/docs/latest/user-guide/configuring/
    - Prettier
        - https://dev.to/knowankit/setup-eslint-and-prettier-in-react-app-357b

### Step 2: Design

- Sketch a fully functional FE design which incorperates the concepts defined earlier
    - https://doridori.github.io/Architecture-Application-as-a-Function/#sthash.nULTszXz.dpbs
    - https://reactjs.org/docs/optimizing-performance.html#use-the-production-build
    - https://softwareengineering.stackexchange.com/questions/128717/why-is-there-such-limited-support-for-design-by-contract-in-most-modern-programm
    - https://medium.com/preezma/memory-leaks-in-javascript-and-how-to-avoid-them-63916a02f68
    - Make color a setting
- Create branches roadmap to improve orthogonality
- Write tests using cypress
    - https://docs.cypress.io/guides/end-to-end-testing/writing-your-first-end-to-end-test
    - https://docs.cypress.io/guides/core-concepts/introduction-to-cypress

### Step 3: Write front end

- Define steps to writing front end
    - https://dev.to/azure/modern-javascript-10-things-you-should-be-using-starting-today-1adm
- Design, styling, UI/UX
    - CSS grid (responsiveness)
    - https://thefullstackdev.net/article/create-beautiful-website-while-sucking-at-design/
    - https://developer.apple.com/design/tips/
    - http://amortizedcost.net/ui-desing-for-software-developer-part-1/
