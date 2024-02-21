# Skeleton Loader using React + Vite

### Demo

<video width="320" height="240" controls>
  <source src="./src/assets/media/skeleton_loader.mov" type="video/mp4">
  Your browser does not support the video tag.
</video>


To view the component in action please click -> [Demo](https://skeleton-loader-react.vercel.app/)

I created a skeleton loader using React + Vite.

## Vite

Vite is a build tool that aims to provide a fast development experience for modern web projects. It focuses on near-instantaneous cold server start, fast hot module replacement (HMR), and lightning-fast bundling. Vite achieves this speed by leveraging native ES module imports in the browser, which eliminates the need for bundling during development.

### Why Vite?

#### Speed:

Vite offers blazing-fast build times, allowing developers to see changes reflected in the browser almost instantly.

#### Modern Development:

It embraces modern JavaScript features, such as ES modules, which leads to a more efficient development process.

#### Optimized for Vue and React:

Vite is optimized for frameworks like Vue.js and React, providing tailored features and optimizations for these frameworks.

#### Developer Experience:

With its built-in development server and support for features like HMR, Vite enhances the developer experience, making development smoother and more enjoyable.

By choosing Vite for your project, you've opted for a tool that prioritizes speed and developer experience, helping you build modern web applications more efficiently.

## App Component

This is the main functional React component named App. It represents the root component of the application.

### State and Effect:

It initializes a state variable loading using the useState hook and sets its initial value to true.
The useEffect hook is used to simulate a loading delay. It changes the loading state to false after a timeout of 1000 milliseconds.

### Rendering:

The component returns JSX that consists of a div element with classnames defining its styling attributes. This div is a flex container that centers its children both horizontally and vertically within the viewport.

Within this container, there's a ternary expression: if loading is true, it renders the Skeleton component; otherwise, it renders the Card component.

Export The App component is exported as the default export of this module, making it available for use elsewhere in the application.

## I created 2 components:

- Card.jsx
- Skeleton.jsx

## Card Component

This is a functional React component named Card. It represents a card element containing information about Apple headphones.

### Structure:

The outer div element has a set of classnames defining its styling attributes.

Inside this div, there is another div with classnames defining its styling attributes. This inner div contains an img element displaying the Headphones image.

Below the image, there is a div containing text information about the headphones, including the product name, price, and a description.

## Skeleton Component

This is a functional React component named Skeleton. It represents a skeleton loading effect often used to indicate to users that content is being loaded.

### Structure:

The outer div element has a set of classnames defining its styling attributes.

Inside this div, there is another div with classnames defining its styling attributes. This inner div represents the container for the skeleton loading effect.
Within the skeleton container, there is an svg element depicting a placeholder icon.

Following the icon, there are several div elements with classnames defining their styling attributes. These div elements represent placeholder lines used to simulate content loading. Each div has a background color of gray and rounded corners, mimicking the appearance of content while it's loading.
