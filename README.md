<h1 align="center">Giuseppe Messina </h1>
<h3 align="center">Front-End Engineer based in London</h3>

### 🧑‍💻 About Me

I’m **Giuseppe**, a **Senior Front-End Engineer** with 8+ years of experience building performant, maintainable React applications. I care about clean architecture, thoughtful UI, and working closely with teams to ship great products.

I focus on TypeScript, React, and responsive design. I structure components and hooks with clear intent, using self-documenting names, well-scoped props, and precise TypeScript interfaces. I back them up with unit and integration tests using Jest and React Testing Library. I also automate linting, formatting, and type-checking in CI pipelines to ensure every merge is safe and predictable.

I also hold an MSc in Computer Science with a focus on Software Engineering, which sharpened both my theoretical foundation and practical approach to problem-solving.

### 🚀 What you'll find here

I’ve organized my work into two main areas on my GitHub:

1. **[React Lab Mono](#react-lab-mono)** – a comprehensive showcase of my React expertise split into a [Design System](#design-system) and [Examples & Micro-demos](#examples-demos).
2. **[Other Repositories](#other-repos)** – standalone projects like my [portfolio page](https://github.com/giuseppe-messi/portfolio), various Python algorithm implementations, and a personal full-stack COVID-19 info hub website, among others.

Feel free to jump to any section using the links above!

---

<a id="react-lab-mono"></a>

### 🛠️ [React Lab Mono](https://github.com/giuseppe-messi/react-lab-mono)

I built one **monorepo** to **showcase my core React skills** in action by creating a full-featured **Design System** and a set of **Examples & Micro-demos**, each targeting specific areas from my checklist (Core TypeScript/JavaScript & Web Fundamentals, React Fundamentals, State Management, Routing & Navigation, Styling & Theming, Type Safety, Data Fetching & API Integration, Forms & Validation, Testing, Build Tools & Workflow, Accessibility, Performance Optimization, Documentation & Design Systems, Deployment & CI/CD, and more).

> ⚠️ **Note:** This is an evolving project that I update when time allows, because, well, life happens. Some sections may be in progress or marked with notes if they haven’t been started or fully completed yet. It's more like a living portfolio than a static snapshot.

<a id="design-system"></a>

### 🎨 [Design System](https://github.com/giuseppe-messi/react-lab-mono/tree/main/packages/ui)

Inside [packages/ui](https://github.com/giuseppe-messi/react-lab-mono/tree/main/packages/ui) you'll find a self-contained, production-ready React component library, [published on npm](https://www.npmjs.com/package/@react-lab-mono/ui) demonstrating:

- **Core TypeScript/JavaScript & Web Fundamentals**  
  ES6+ syntax (arrow functions, destructuring, spread/rest, template literals), modules (`import`/`export`), event handling & DOM APIs, asynchronous patterns (Promises, async/await, Fetch), Browser APIs (LocalStorage, SessionStorage, WebSockets), error handling, and debounce/throttle utilities.

- **React Fundamentals**  
  JSX & its transforms, function components, props & state, lifecycle phases (mount/update/unmount), built-in hooks (`useState`, `useEffect`, `useRef`, `useLayoutEffect`, `useMemo`, `useCallback`, `useContext`, `useReducer`), custom hooks, Context API, error boundaries, and advanced patterns (render-props, compound components).

- **Styling & Theming**  
  Design tokens (centralized variables for colors, typography, spacing), CSS Modules for scoped styles, responsive design techniques, and a theme­provider architecture for light/dark modes.

- **Type Safety**  
  Full **TypeScript** setup with strict `tsconfig` rules, typed React props & state, utility & mapped types.

- **Accessibility (a11y)**  
  Semantic HTML, ARIA roles & attributes, keyboard navigation & focus management, high-contrast themes, screen-reader testing, and automated audits with **jest-axe** and **Lighthouse**.

- **Performance Optimization**  
  Code-splitting with `React.lazy` & `Suspense`, route-based chunking, memoization (`React.memo`, `useMemo`, `useCallback`), list virtualization (react-window), image lazy-loading, bundle-size budgets enforced via plugins (e.g. `rollup-plugin-visualizer`, `vite-bundle-analyzer`, `vite-plugin-inspect`), and profiling with React DevTools & Lighthouse CI.

- **Testing**  
  Unit tests (Jest + React Testing Library), end-to-end smoke tests for critical flows, and a focus on testable, accessible components through Storybook.

- **Documentation & Design Systems**  
  Interactive component catalog with **Storybook**, MDX (Markdown + JSX) for rich examples & documentation.

- **Build Tools & Workflow**  
  Library bundling with **Vite**, Turborepo pipelines for caching & parallel builds, semantic-release for automated versioning & npm publishing, and CI/CD pipelines on **GitHub Actions** (lint, type-check, test, build, publish).

↳ [react-lab-mono/tree/main/packages/ui](https://github.com/giuseppe-messi/react-lab-mono/tree/main/packages/ui)

<a id="examples-demos"></a>

### 🧩 [Examples & Micro-demos](https://github.com/giuseppe-messi/react-lab-mono/tree/main/apps)

Inside [apps/](https://github.com/giuseppe-messi/react-lab-mono/tree/main/apps) you'll find:

- A `docs/` directory containing the Storybook project showcasing the design system ([packages/ui](https://github.com/giuseppe-messi/react-lab-mono/tree/main/packages/ui) ) components.
- A set of focused example apps, each highlighting specific core skills.

Every project is backed by unit and integration tests using Jest and React Testing Library. I also automate linting, formatting, and type-checking using ESLint and TypeScript configuration files.

1. **[Storybook](https://github.com/giuseppe-messi/react-lab-mono/tree/main/apps/docs)** ( 🧪 Work In Progress )

   - **Checkout the repo**: [apps/docs](https://github.com/giuseppe-messi/react-lab-mono/tree/main/apps/docs)
   - **Live demo**: [Packages UI Storybook](https://tiny-ganache-0201ee.netlify.app/?path=/docs/button--docs/)

2. **[Optimistic UI Sandbox](https://github.com/giuseppe-messi/react-lab-mono/tree/main/apps/optimistic-ui-sandbox)** ( ✅ Done )

   - **State Management**: Zustand
   - **Mocked Data Fetching & API Integration**: mocking + optimistic UI
   - **Testing**: Jest & React Testing Library
   - **Core JavaScript & Web Fundamentals**: async/await, Promises, modules
   - **Test coverage**: 100%
   - **Checkout the repo**: [apps/optimistic-ui-sandbox](https://github.com/giuseppe-messi/react-lab-mono/tree/main/apps/optimistic-ui-sandbox)
   - **Live demo**: [Optimistic UI Sandbox](https://startling-shortbread-4b5781.netlify.app/)

3. **Auth-Guarded Docs & SSR** ( ❌ Coming Soon )
   - **Routing & Navigation**: nested MDX routes, JWT-based admin guards
   - **Data Fetching & API Integration**: SSG for public docs, SSR for protected pages
   - **Type Safety** & **React Fundamentals**: functional components, hooks, strict TS
   - **Build Tools & Workflow**: Next.js configuration, SSR/SSG pipeline
4. **PWA Cache Demo** ( ❌ Coming Soon )
   - **Core JS/Web Fundamentals**: Service Workers, IndexedDB via localForage, Web APIs
   - **Data Fetching & API Integration**: fetch + runtime caching (Workbox)
   - **Accessibility**: offline state banner, progressive enhancement
   - **Build Tools & Workflow**: Vite PWA template, manifest.json
5. **Cross-Platform UI** ( ❌ Coming Soon )
   - **React Fundamentals** & **Type Safety**: JSX, props & state, TypeScript
   - **Styling & Theming**: shared design-system tokens across web & native
   - **Component Architecture**: code-sharing via React Native Web
   - **Build Tools & Workflow**: Metro/RNW bundling, platform-agnostic styling

---

<a id="other-repos"></a>

### 🗃️ Other Repositories

I also maintain several other projects, feel free to explore:

- **[portfolio-page](https://github.com/giuseppe-messi/portfolio)**: my personal portfolio site
- **shop-order-system**: an online shop ordering system built with Python
- **linked-list-sort**: a Python implementation of a linked-list sorting algorithm
- **huffman-coding**: a Python implementation of the Huffman compression algorithm
- **covid19-info-hub**: a full-stack COVID-19 info hub built with PHP & JavaScript

_(See each repo’s topics for more details.)_

---

### 📫 Let’s connect

- 📧 **Email:** [giuseppe91messina@gmail.com](mailto:giuseppe91messina@gmail.com)

- 🔗 **LinkedIn:** [linkedin.com/in/giuseppe-messina](https://www.linkedin.com/in/giuseppe-messina/)

- 🚀 **My website:** [giuseppemessina.dev](https://giuseppemessina.dev/)

I’m always open to discussing new projects, collaborations, or roles where I can bring my React expertise to help deliver exceptional digital experiences for your users.
