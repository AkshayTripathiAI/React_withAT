# React_withAT

My personal React learning notes: concept docs, a cheat sheet, interview-style revision notes, hook snippets and two small practice projects.

## Contents

### Docs

| File | What's inside |
| --- | --- |
| [docs/ReactConcept.md](docs/ReactConcept.md) | 20 core topics with examples: components, JSX, state and props, lifecycle methods, hooks, React Router, Redux, forms, Context API, HOCs, error boundaries, portals, Suspense/lazy loading, testing, Next.js SSR, render props, WebSockets, GraphQL with Apollo |
| [docs/ReactHooks.md](docs/ReactHooks.md) | Built-in hooks with examples (`useContext`, `useState`, `useEffect`, `useReducer`, `useMemo`, `useCallback`, `useImperativeHandle`, `useDebugValue`, `useRef`, `useLayoutEffect`) and custom hooks |

### Cheat sheets

| File | What's inside |
| --- | --- |
| [cheat-sheet/ReactCheatSheet.md](cheat-sheet/ReactCheatSheet.md) | Long-form cheat sheet: components, state and events, forms and validation, `useRef`, lists and conditional rendering, styling (inline, styled-components, CSS Modules), fragments/portals/refs, `useEffect`, `useReducer`, Context API, and more |
| [cheat-sheet/React_Revision.md](cheat-sheet/React_Revision.md) | Q&A revision notes: what React is and its key features; class vs. functional components |

### Code examples

Standalone component snippets (not a runnable app):

- [code-examples/useState.js](code-examples/useState.js) – counter
- [code-examples/useEffect.js](code-examples/useEffect.js) – data fetching with loading and error states
- [code-examples/useContext.js](code-examples/useContext.js) – theme toggle with Context

### Mini projects

| Project | Stack | Run |
| --- | --- | --- |
| [react-projects/reduxTodo-project2](react-projects/reduxTodo-project2) | Vite, React 18, Redux Toolkit (`createSlice`), Tailwind CSS. Add and remove todos. | `npm install && npm run dev` |
| [react-projects/usememo-optimization-project1](react-projects/usememo-optimization-project1) | Create React App. Memoization experiments (a hand-written memoized function plus small components). | `npm install && npm start` |

Run the commands inside each project folder.

## Getting started

```bash
git clone https://github.com/AkshayTripathiAI/React_withAT.git
cd React_withAT
```

The notes are plain Markdown and read fine on GitHub; only the projects under `react-projects/` need Node.js and npm.
