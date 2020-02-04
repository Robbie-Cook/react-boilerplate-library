---

## Getting started

### Local setup

Clone this repo, and then run

```bash
yarn
yarn build
```

or 

```bash
npm i
yarn run build
```

Now, your files should be built in `dist/`.

You can then use import this repository into another React project.

## Use in anther project

Go to another React project (such as one created by https://github.com/facebook/create-react-app).
Then add this project as a dependency:

```bash
yarn add @robbie-cook/react-library-example
```

or

```bash
npm i @robbie-cook/react-library-example
```

You can then use this library in your project. Test this by going to your App.tsx / App.jsx and adding the line

```js
import { Foo } from '@robbie-cook/react-library-example'
```.

Then, go to your render function and add the line: 
`<Foo />` inside your returned JSX. If this works, you have set up the library correctly

Look up these functions in node-helper.mjs for a detailed description.

## Recognition

This repo was adapted from https://github.com/bdoss/typescript-react-library
