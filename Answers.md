A: .map(), .forEach(), every(), components can be extended by using extends

A: Actions send payload of info to the store via Reducers. Typically they get this info from the API/server.
   Reducers instruct the store to change 'state' depending on the instructions they receive from the Actions.
   The Store is the central repository of all data in Redux and this is why its known as the single source of truth.

A: Application state is global while component state is local. Component state lives within a particular component and is usually updated only there.
   It is passed onto its children via props. However any component can hook into the central store and access it.

A: Middleware provides third party extensions between dispatching an actions and the action being received by the reducer. E.g Logging.

A: Thunk actionware allows you to write action creators that return a function instead of an action. Thunk is sometimes used to delay an action.