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
16.
17.
18.
19.
20.