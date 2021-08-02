# useCounter Hook

Example

```
    const {state, increment , decrement, reset} = useCounter(10);

    default value = 10
 
```

Component

```
    <div>
            <h1> Counter with Hook: { state } </h1>
            <hr />

            <button onClick={ increment }  className="btn btn-primary" > + 1 </button>
            <button onClick={ reset }  className="btn btn-primary" > Reset </button>
            <button onClick={ decrement }  className="btn btn-primary" > - 1 </button>

    </div>
```