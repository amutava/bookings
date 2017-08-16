# Bookings
### Introduction to building a fully functional applications using REACT.
* Introduction
* Environment setup
- Our development environment should be able to handle:
   - Automated testing.
   - Linting.
   - Minification.
   - Bundling
   - JSX compilation
   - ES6 transpilation.
   - One command.
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
| `Browserify` | `Webpack( It's powerful and is the most common bundler(module bundler)bundles the app for the browser.)` | 
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
<br/>
Create a root project folder. Add a package.json file, add all the packages that you need to be used. Run the command `npm install`. This package installs all the packages that you will need in your project. A folder for the node modules will be added in the project structure.

#### Why npm scripts?
* They are easy to learn.
* Simple
* No extra layer of abstraction.
* No dependence on extra plugin.
* Simpler debugging.
* Better documentation.

We create a configuration for webpack in the application. We used dev because we developing in production we will create a configuration for that.
Express is easy to work with. It is also easy to configure.

#### React in ES6
* No autobind
* PropTypes declared separately.
* Default props declared separately.
* Set initial state in constructor.
#### Stateless functional components: 9 benefits.
* No class needed.
* Avoid 'this' keyword.
* Enforced best practises.
* High signal to noise ratio.
* Enhanced code completion/ Intellisense.
* Bloated components are obvious.
* Easy to understand.
* Easy to test.
* Offers improved performance.
#### When should I use each?
|Class component | Stateless Components |
|----------------|----------------------|
|State | Everywhere else |
|Refs | Everywhere else |
|Lifecycle methods | Everywhere else |
|Child functions for perfomance | Everywhere else |

#### other ways to create components.
* Object.create
* Mixins
* Parasitic components.
* StampIt
more info on this : bit.ly/react-define-component

|Container component|Presentation component|
|------------------- | ----------------------|
|Little to no markup. | Nearly all markup|
|They pass data and ations down to presentation component | Receive data and actions via props|
|Know about redux.(They have redux code) | Doesn't know anything about redux. Doesn't specify how data is loaded or muted.|
|Often stateful. | Typically functional components.|

#### Create app foundation.
* Create our first pages.
* Create layout.
* Configure routing.
* Setup navigation.
