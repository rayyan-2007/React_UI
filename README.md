# React Card UI

A simple React application built to understand and practice React Props and Props Drilling concepts.

## Features

* Reusable Card Component
* Reusable Button Component
* Data passed using Props
* Props Drilling from Parent Component to Child Component
* Simple and Clean User Interface

## Technologies Used

* React.js
* Vite
* JavaScript
* CSS

## Concepts Practiced

### Props

Props are used to pass data from a parent component to a child component.

Example:

```jsx
<Card name="Joe Root" email="joe@gmail.com" btnname="Click" />
```

### Props Drilling

Props Drilling occurs when data is passed through multiple components before reaching the component that actually uses it.

Example Flow:

App → Card → Button

The `btnname` prop is passed from the App component to the Card component and then forwarded to the Button component.

## Project Structure

```text
src
├── component
│   ├── card
│   │   └── Card.jsx
│   └── button
│       └── Button.jsx
├── App.jsx
├── App.css
├── index.css
└── main.jsx
```

## What I Learned

* Creating React Components
* Passing Data with Props
* Understanding Parent and Child Components
* Implementing Props Drilling
* Component Reusability
* Basic React Project Structure

## Run the Project

```bash
npm install
npm run dev
```
