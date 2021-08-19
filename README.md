This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).


## About this boilerplate:

### app
The app directory is where our application actually lives. I like the approach of having the application files, which are not dedicated to the framework bundled in a specific directory.


### api
This folder contains all code we need to access the APIs of our application. Personally, I like to have one folder for each REST API controller. Each folder then contains the functions for the API calls as well as the tests.

### components
The components directory contains all your elements, modules, templates, and layouts. I will explain each of these under a separate title. Some of you may prefer the Atomic Design by Brad Frost which is fine as well. In my opinion, the Atomic Design Pattern is sometimes a little bit confusing whether a component is a molecule or organism.

### elements
This directory contains all the basic building blocks for your app. For example a button or a headline component.


### modules
Create all your components here which are more than a basic building block. This could be a header or a footer component. Most likely those modules are built out of multiple elements.


### templates
In the templates directory, you should place all your page templates which are then called from your Next.js specific pages. You can find an example of this pattern in the Repository.


### layouts
Layouts are used to wrap your Templates and provide them with the components which will be displayed by default in a specific layout. For example, you would include the Footer and the Header in a default layout.


### hooks
Your custom hooks may find their place here.
Introducing Hooks — React
Hooks are a new addition in React 16.8. They let you use state and other React features without writing a class. This…
reactjs.org

### styles
The styles directory is an addition to the scss files you have in each component directory. I like to place all my global styles like variables or utilities in this directory.
You may use a different approach for your application styling, so feel free to customize or remove this directory.

### utils
Most likely you will have some JS functions which you will use over and over again. I would recommend you to outsource them into separate files.






## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.js`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.js`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
