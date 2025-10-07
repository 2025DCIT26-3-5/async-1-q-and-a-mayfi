# Introduction to React Router

## Question
What is React Router and why is it important in single-page applications?

## Answer
React Router is a declarative library that manages routing and navigation in React apps. It keeps the UI in sync with the URL, allowing users to move between views without full page reloads. This makes SPAs faster and more seamless.


# Core Router Components

## Question
What are the main components of React Router and their purposes?

## Answer
- **BrowserRouter**: Wraps the app to enable routing  
- **Routes & Route**: Define path-to-component mappings  
- **Link & NavLink**: Provide navigation without reloading the page


# Navigation Techniques

## Question
What are the two main navigation methods in React Router?

## Answer
- **Declarative Navigation**: Uses `Link` or `NavLink` for user-triggered navigation  
- **Programmatic Navigation**: Uses the `useNavigate` hook to change routes through code, like after form submission


# Dynamic Routes & Parameters

## Question
How does React Router handle dynamic and optional parameters in routes?

## Answer
React Router captures parameters through URL segments using `useParams`. It can also handle query strings via `useSearchParams`, and supports optional parameters by defining flexible route paths.


# Nested Routes & Layouts

## Question
Why use nested routes in React Router?

## Answer
Nested routes let you share layouts and organize related pages under one parent route. This helps maintain consistent navigation structures, such as dashboards with subpages.