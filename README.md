context API react:

useContext is a hook that let's us read and subscribe to context in our component.
const value = useContext(SomeContext)

when we create a context by createContext it gives us a provider, we implement it using a wrapper. 
call it in the child components that needs to call the context that will utilise the context variable where it needs to be.