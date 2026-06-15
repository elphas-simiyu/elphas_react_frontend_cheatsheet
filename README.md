# React JS CheatSheet

I have created this cheatsheet to help developers to with somewhere to refer from when they are developing their react applications

# 1. React Fundamentals

## 1.1 What React Is

* Library vs Framework
* Virtual DOM
* Real DOM vs Virtual DOM
* Declarative UI
* Component-Based Architecture
* Reactive Updates
* Unidirectional Data Flow

## 1.2 React Project Structure

* Typical React Project
* Vite Structure
* CRA Structure
* Production Structure
* Organizing Features
* Organizing Components
* Organizing Hooks
* Organizing Services
* Organizing Assets

## 1.3 React Rendering Process

* Initial Render
* Re-render
* Reconciliation
* Diffing Algorithm
* Component Tree
* Render Cycle
* Commit Phase
* Why Components Re-render

---

# 2. JSX Deep Dive

## 2.1 JSX Basics

* JSX Syntax
* Rules of JSX
* Returning JSX
* Parent Element Requirement
* React Fragments

## 2.2 Expressions in JSX

* Variables
* Functions
* Objects
* Arrays
* Template Literals

## 2.3 Conditional Rendering

* if Statements
* Ternary Operators
* &&
* Switch Statements
* Conditional Components

## 2.4 Lists and Rendering

* map()
* filter()
* reduce()
* Rendering Collections
* Nested Lists

## 2.5 Keys

* Why Keys Matter
* Stable Keys
* Bad Keys
* Key Generation

## 2.6 JSX Attributes

* className
* htmlFor
* style
* data-* Attributes
* Custom Attributes

## 2.7 Event Handling

* onClick
* onChange
* onSubmit
* onFocus
* onBlur
* Keyboard Events
* Mouse Events

---

# 3. Components

## 3.1 Function Components

* Creating Components
* Exporting Components
* Importing Components

## 3.2 Component Composition

* Parent Components
* Child Components
* Nested Components
* Layout Components

## 3.3 Component Communication

* Parent to Child
* Child to Parent
* Sibling Communication

## 3.4 Reusable Components

* Design Principles
* Generic Components
* Shared Components

## 3.5 Component Patterns

* Container Components
* Presentational Components
* Compound Components
* Controlled Components
* Uncontrolled Components

---

# 4. Props

## 4.1 Props Fundamentals

* Passing Props
* Receiving Props
* Destructuring Props

## 4.2 Advanced Props

* Default Values
* Optional Props
* Dynamic Props
* Computed Props

## 4.3 Children Prop

* Understanding Children
* Wrappers
* Layout Components

## 4.4 Prop Drilling

* Definition
* Problems
* Solutions

---

# 5. State Management

## 5.1 State Fundamentals

* What State Is
* State vs Variables
* State Updates

## 5.2 useState

* Syntax
* Updating State
* Functional Updates
* Lazy Initialization

## 5.3 Complex State

* Objects
* Arrays
* Nested Objects
* Immutable Updates

## 5.4 State Design

* Local State
* Shared State
* Global State
* Derived State

## 5.5 Common State Mistakes

* Mutating State
* Stale Closures
* Incorrect Updates

---

# 6. React Hooks

## 6.1 Hooks Rules

* Rules of Hooks
* Why Rules Exist

## 6.2 useState

## 6.3 useEffect

* Syntax
* Dependencies
* Cleanup Functions
* Lifecycle Replacement
* API Calls

## 6.4 useContext

## 6.5 useRef

* DOM References
* Persistent Values

## 6.6 useMemo

* Memoization
* Expensive Calculations

## 6.7 useCallback

* Function Memoization
* Preventing Re-renders

## 6.8 useReducer

* Reducers
* Actions
* Complex State

## 6.9 useLayoutEffect

## 6.10 useImperativeHandle

## 6.11 useTransition

## 6.12 useDeferredValue

## 6.13 useId

## 6.14 useSyncExternalStore

## 6.15 Custom Hooks

* Creating Hooks
* Reusable Logic
* Hook Patterns

---

# 7. Forms

## 7.1 Controlled Forms

## 7.2 Uncontrolled Forms

## 7.3 Input Types

* Text
* Number
* Email
* Password
* Checkbox
* Radio
* Select
* File Upload

## 7.4 Validation

* Client Validation
* Custom Validation
* Error Messages

## 7.5 Form Libraries

* React Hook Form
* Formik

---

# 8. Effects and Side Effects

## 8.1 Understanding Effects

## 8.2 Data Fetching

## 8.3 API Calls

## 8.4 Cleanup Functions

## 8.5 Common useEffect Mistakes

## 8.6 Dependency Arrays

## 8.7 Infinite Loops

---

# 9. React Routing

## 9.1 React Router Overview

## 9.2 Installation

## 9.3 BrowserRouter

## 9.4 Routes

## 9.5 Route Parameters

## 9.6 Nested Routes

## 9.7 Layout Routes

## 9.8 Navigation

* Link
* NavLink
* useNavigate

## 9.9 Protected Routes

## 9.10 404 Pages

## 9.11 Route Loaders

## 9.12 Search Parameters

---

# 10. API Integration

## 10.1 Fetch API

## 10.2 Axios

## 10.3 CRUD Operations

* GET
* POST
* PUT
* PATCH
* DELETE

## 10.4 Error Handling

## 10.5 Authentication APIs

## 10.6 Token Management

## 10.7 API Service Layer

## 10.8 Interceptors

---

# 11. Context API

## 11.1 What Context Solves

## 11.2 Creating Context

## 11.3 Provider Pattern

## 11.4 Consuming Context

## 11.5 Multiple Contexts

## 11.6 Context Best Practices

## 11.7 Performance Considerations

---

# 12. Global State Management

## 12.1 Context vs Redux

## 12.2 Redux Fundamentals

## 12.3 Redux Toolkit

## 12.4 Store

## 12.5 Reducers

## 12.6 Actions

## 12.7 Selectors

## 12.8 Async Thunks

## 12.9 Zustand

## 12.10 Recoil

## 12.11 Jotai

---

# 13. Styling React Applications

## 13.1 CSS Modules

## 13.2 Tailwind CSS

## 13.3 Styled Components

## 13.4 Emotion

## 13.5 Sass

## 13.6 Inline Styles

## 13.7 Dynamic Styling

## 13.8 Theme Systems

## 13.9 Dark Mode

---

# 14. Performance Optimization

## 14.1 React.memo

## 14.2 useMemo

## 14.3 useCallback

## 14.4 Code Splitting

## 14.5 Lazy Loading

## 14.6 Suspense

## 14.7 Virtualization

## 14.8 Preventing Unnecessary Re-renders

## 14.9 Bundle Optimization

---

# 15. Error Handling

## 15.1 Error Boundaries

## 15.2 Handling API Errors

## 15.3 Fallback UI

## 15.4 Logging Errors

## 15.5 User-Friendly Error Messages

---

# 16. Authentication and Authorization

## 16.1 JWT Authentication

## 16.2 Refresh Tokens

## 16.3 Session Authentication

## 16.4 OAuth

## 16.5 Role-Based Access

## 16.6 Protected Routes

## 16.7 Permissions

---

# 17. React Patterns

## 17.1 Render Props

## 17.2 Higher Order Components

## 17.3 Compound Components

## 17.4 Provider Pattern

## 17.5 Factory Pattern

## 17.6 Custom Hooks Pattern

## 17.7 State Reducer Pattern

---

# 18. Advanced React

## 18.1 Portals

## 18.2 Refs

## 18.3 Forward Ref

## 18.4 Concurrent Features

## 18.5 Suspense for Data Fetching

## 18.6 Server Components

## 18.7 Hydration

## 18.8 Streaming

---

# 19. React Ecosystem

## 19.1 Vite

## 19.2 React Router

## 19.3 Redux Toolkit

## 19.4 React Query / TanStack Query

## 19.5 Zustand

## 19.6 Framer Motion

## 19.7 React Hook Form

## 19.8 Axios

## 19.9 Zod

## 19.10 TanStack Table

---

# 20. React Query (TanStack Query)

## 20.1 Why React Query

## 20.2 Query Client

## 20.3 useQuery

## 20.4 useMutation

## 20.5 Query Keys

## 20.6 Caching

## 20.7 Refetching

## 20.8 Optimistic Updates

## 20.9 Infinite Queries

## 20.10 Pagination

---

# 21. Testing React Applications

## 21.1 Testing Fundamentals

## 21.2 Vitest

## 21.3 Jest

## 21.4 React Testing Library

## 21.5 Component Testing

## 21.6 Hook Testing

## 21.7 Mocking APIs

## 21.8 End-to-End Testing

## 21.9 Cypress

## 21.10 Playwright

---

# 22. React Project Architecture

## 22.1 Feature-Based Structure

## 22.2 Domain-Driven Structure

## 22.3 Scalable Folder Structure

## 22.4 Shared Components

## 22.5 Shared Hooks

## 22.6 Shared Services

## 22.7 Utility Functions

## 22.8 Constants

## 22.9 Environment Variables

---

# 23. React Security

## 23.1 XSS Prevention

## 23.2 Secure Storage

## 23.3 Token Security

## 23.4 CSRF

## 23.5 Sanitization

## 23.6 Environment Variables

## 23.7 Secure API Communication

---

# 24. Deployment

## 24.1 Building for Production

## 24.2 Environment Variables

## 24.3 Vercel

## 24.4 Netlify

## 24.5 AWS

## 24.6 Docker

## 24.7 CI/CD

## 24.8 GitHub Actions

---

# 25. TypeScript with React

## 25.1 TypeScript Fundamentals

## 25.2 Typing Props

## 25.3 Typing State

## 25.4 Typing Events

## 25.5 Typing Hooks

## 25.6 Generic Components

## 25.7 API Types

## 25.8 Utility Types

## 25.9 Advanced Generics

---

# 26. React Interview & Debugging Handbook

## 26.1 React Lifecycle Explained

## 26.2 Common Interview Questions

## 26.3 Debugging Techniques

## 26.4 React DevTools

## 26.5 Performance Profiling

## 26.6 Common Bugs

## 26.7 Common Anti-Patterns

## 26.8 Production Debugging

---

# 27. Production-Ready Features Checklist

## Authentication

## Authorization

## Error Handling

## Loading States

## Toast Notifications

## Pagination

## Infinite Scroll

## Search

## Filters

## Sorting

## Dark Mode

## Internationalization (i18n)

## Accessibility (a11y)

## SEO

## Analytics

## Logging

## Monitoring

## Offline Support

## PWA

## Caching

## Rate Limiting

## Data Validation

---

