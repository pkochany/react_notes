## Installation

```
npx create-react-app app-name
```

## Start development server

```
npm start
```

## Bundle the app into static files for production

```
npm run build
```

## Start the test runner

```
npm test
```

## Create Element

```javascript
// this is not actual element
// this is an object representation of an element
const title = React.createElement(
  'h1',
  { id: 'main-title', title: 'This is a title.'},// can be null
  'My First React Element!'//can be null, there can be more elements after this and all will be children of this h1 element
)

// result will be:
// <h1 id="main-title" title="This is a title.">My first React Element!</h1>
```

## Rendering Element

```javascript
// first argument is the element to render
// second argument is target where it will be rendered
ReactDOM.render(
  title,
  document.getElementById('root')
)
```

