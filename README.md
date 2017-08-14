# Bookings
### Introduction to building a fully functional applications using REACT.
* Introduction
* Environment setup
- Our development environment should be able to handle.
   > Automated testing.
   > Linting.
   > Minification.
   > Bundling
   > JSX compilation
   > ES6 transpilation.
   > One command.
* React component approaches
* Initial App Structure
* Redux Introduction
* Action stores and reducers
* Connecting react to Redux
* Redux flow
* Async in redux
* Async Writes in Redux.

### Redux
It's a library. Popular data management library. It builds on fluxes' unidirectional data flow pattern.

| Flux | Redux | 
| -------- | ------------- |
| `ES6` | `ES6 with  babel(transpiling ES6 with babel)`  | 
|  `React Router` | `React Router(used for routing purposes.)` | 
| `Browserify` | `Webpack( It's powerful and is the most common bundler(module bundler))` | 
| `Gulp` | `npm scripts( Creates automatted builds.)` | 
| `ESLINT` | `ESLINT( Most powerful way to lint javascript.)` | 
| `No testing` | `Mocha, React Test Utils and Enzyme` | 

#### Why redux?
It's popular(has more stars on github than flux).
Facebook have embraced redux as compared to initially flux.Redux creator Dan joined the facebook team.
* It centralizes all your application statesin one store.
* Reduced boilerplate code compared to facebooks' flux.
* isomorphic/ universal friendly(Architecture is easy to render react components.)
* Immutable store
* Hot Reloading(Using babel-preset-react-mre). It doesn't work with functional components. Doesn't reload container functions like MapStateToProps.
* Time-travel debugging
* Small
* Requires lesser boilerplate code than flux.
