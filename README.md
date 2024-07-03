# Reac Crash Course 2024

- React is a Javascript library/framework for building user interfaces.

Types:
* Single Page App (SPA)
* Server-Side Rendered (SSR)
* Static Site Generation (SSG)

## Hooks

* useState
* useEffect
* useRef
* useReducer

Phasing out in React 19
* useContext
* useMemo
* useCallback

## React Project

### Create Project

`$ npm create vite@latest {react-crash-2024|src}`
or
`$ npm create vite@latest {react-crash-2024|src} -- --template react`

### Start

`$ cd {react-crash-2024|src}`
`$ npm install`
`$ npm run dev`

### Install Tailwind CSS

`$ npm install -D tailwindcss postcss autoprefixer`
`$ npx tailwindcss init -p`

* Instructions at https://tailwindcss.com/docs/guides/vite

### Set in 'src/vite.config.js'

`...`
`export default defineConfig({`
`   ...`
`   server: {`
`       host: '0.0.0.0',`
`       port: 3000,`
`   },`
`   ...`
`})`

### Use Icons

`$ npm i react-icons`

## YouTube

By `Traversy Media`

1. Intro
2. What Is React? (Slide)
3. Why React? (Slide)
4. What Are Components? (Slide)
5. What Is State? (Slide)
6. What Are Hooks? (Slide)
7. What Is JSX? (Slide)
8. SPA, SSR, SSG (Slide)
9. Vite (Slide)
10. Project Demo
11. Setup React With Vite
12. File Explanation
13. Boilerplate Cleanup
14. Tailwind CSS Setup
15. JSX Crash Course
16. Start Homepage 
17. Navbar Component
18. Image Import
19. Hero Component
20. Props
21. Default Props
22. Wrapper Components
23. JobListings Component
24. Create Lists With map()
25. Single JobListing Component
26. Limit Jobs to 3
27. useState() Hook & Desc Toggle
28. Creating an Event
29. Updating Component State
30. React Icons Package
31.
32.
33.
34.
35.
36.
37.
38.
39.
40.
