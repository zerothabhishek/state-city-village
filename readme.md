

## A minimialist introduction to React

### The problem: the city state problem

![The-problem](/images/prob.png)

- State, City, Village as dropdowns
- State changes => City list must change
- City changes => Villages list much change
- Villages fetched from server side (State/city hardcoded)
- Approaches before React:
  - DOM manipulation (innerHTML)
  - Templates
  - Page reloads

### Step-0: Hello world
- npm i serve (or any simple web server)
- Load React, React-Dom and Babel from unpkg
- Write the hello-world component
- ReactDOM.render
- serve .
- Notable: JSX, ReactDOM.render, unpkg

### Step-1: Event handling
- Add states dropdown
- Notable: function component, component-in-component

### Step-2: Districts
- State-district hashmap
- Add onChange event handler
- Add district dropdown
- Change state dropdown
- Notable: map function for iteration, event handling


### Step-3: setState
- Automatic rendering - setState
- class component and data as internal state
- React plugin for Chrome
- Notable: setState, bind in constructor, initial state

### Step-4: Adding Villages
- Add village dropdown
- fetch, and then setState
- Add districtSelected event handler, call loadData everytime
- Notable: fetch, setState being async, the conditional

### Step-5: Bug fixes
- Fix the options
- Set initial state on villages
- Notable: loadVillages in stateSelected, option selected ===

### Step-6: Form submission
- Add button and submitForm
- Notable: Sending state data. No accessing fields
- Controlled components

### Step-7: Refactor
- Separate components for Village, district, state
- Passing data and event-handlers as props
- Move to separate files
- Redux ??
- CSS in JS ?

### Conclusion
- Didn't do: build, tests (HMR)
- Next: Create React App
- Next: React docs: Introducing JSX, Lifecycle methods, Thinking in React


