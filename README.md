# Perseus UI Kit
A collection of reusable UI components built with TypeScript.

## What is it?
Perseus UI Kit is a set of pre-built UI components designed to help you speed up your development process. It includes components like buttons, forms, navigation menus, and more.

## Getting Started
To get started with Perseus UI Kit, simply install it via npm or yarn:
```bash
npm install perseus_ui_kit
```
or
```bash
yarn add perseus_ui_kit
```
Then, import the components you need in your TypeScript project:
```typescript
import { Button } from 'perseus_ui_kit';
```
## Example Usage
Here's a quick example of using the Button component:
```typescript
import React from 'react';
import { Button } from 'perseus_ui_kit';

const App = () => {
  return [
    <Button key="button-1" onClick={() => console.log('Button clicked!')}>Click me!</Button>
  ];
};
```
## Running the Demo
To run the demo, clone this repository and navigate to the demo directory:
```bash
git clone https://github.com/[your-username]/perseus_ui_kit.git
cd perseus_ui_kit/demo
npm install
npm start
```
This will start a development server, and you can view the demo in your browser at [http://localhost:3000](http://localhost:3000).