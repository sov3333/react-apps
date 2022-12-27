# React

Code-along to [Build and Deploy 4 Modern React Apps and Get Hired as a Frontend Developer | Full 10-Hour Course](https://youtu.be/F627pKNUCVQ)

## Setup Guide

### Setup Project 1

Install dependencies:
```
npm install react-icons
```

Gradient generator for background: https://angrytools.com/gradient/

CSS animations: https://animista.net/play/basic/scale-up

### Setup Project 2

Install dependencies:
```
npm install react-icons
```

### Setup Project 3

Setup:
```
npm create vite@latest
```

Install dependencies:
```
npm install
```

Install [TailwindCSS using PostCSS](https://tailwindcss.com/docs/installation/using-postcss):
```
npm install -D tailwindcss postcss autoprefixer
npx tailwindcss init -p
```

Run:
```
npm run dev
```


## Tips & Tricks


1. Shortcut to Create React Functional Component export:

- On a blank `.jsx` file, type `rafce` then press `Tab`.
- Note: This requires the `ES7+ React/Redux/React-Native snippets` (dsznajder.es7-react-js-snippets) extension.

2. Instant return

```
const WithCurlyBrackets = () => {
    return (
        <p>Hello</p>
    )
}
```

is the same as:
```
const NoCurlyBrackets = () => (
    <p>Hello</p>
)
```