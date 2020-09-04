# Next JS Boilerplate

This is a Next.JS Boilerplate created to start quickly your next React project.

For instances, I kept the boilerplate as simple as possible to quickly start adding modules.

It is recommended the usage of **Yarn**.

The boilerplate contains this basic features:

- Next.JS for bundling optimization
- Basic _package.json_ file to enhance customization
- _Material UI_ using **Server Side Rendering** for style optimization
- A _Layout Component_ made as a general wrapper
- Different folders using the Next.JS naming conventions: _utils_ , _public_ , _views_ , _theme_ , _components_
- _Babel_, _Prettier_ and _Code Workspace_ for coding comfort

## Installation

To start using this boilerplate remember changing the `<title>` tag in the _app.tsx_ file.
First install all using _yarn_:

```bash
yarn
```

## Development

Use the `dev` command to start developing your project. If the _tsconfig.json_ file is not present, then Next will create it for you.

```bash
yarn dev
```

## Deployment

Build your project using

```bash
yarn build
```

To watch your build in localhost you can type:

```bash
yarn start
```

To generate a Static Site ready for deployment you can type:

```bash
yarn export
```

This will generate a _out_ folder with all the static contents.

## Tutorial

If you're new to NextJS, don't forget to visit the tutorial for [NextJS](https://nextjs.org/learn/basics/create-nextjs-app)
