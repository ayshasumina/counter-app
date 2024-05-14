REDUX - STATE MANAGEMENT TOOL
------------------------------
1. To avoid props drilling and its manage state in a react app

2. Libraries needs to implement redux
  - React-Redux : official React bindings for Redux 
  - Redux Toolkit : toolset for efficient Redux development
  - install libraries : npm install @reduxjs/toolkit react-redux
3. Redux Features
     - Store : Using 'configureStore()' to create redux store, use 'Provider' component to make the store available for the react app
     - createSlice() - used to combine action and reducer together
     - Action : degine logic to update state
     - Reducer : used to hold updated state to store
     - createSlice() - used to combine action and reducer together, it returns actions and reducer, to create slice we have to pass configuration with following data : name, initial state, reducers where will define action to update the state with argument when action function will get from its 'payload'
     - when component dispatch action with argument to update the state
     - Redux DevTools Extension : used for debugging application's state changes.\
     - useSelector hook : use state from store to component, syntax: useSelector(state=>state.reducer-name)
     - useDispatch hook : used to execute the  action from component