# useForm Hook

```
     const { handleInputChange, values: { description }, reset } = useForm({
        description: ''
    })

   Default Value: initialState = {}

```

Component

```
     <input
        type="text"
        onChange={handleInputChange}
        value={description}
    />

    

```
