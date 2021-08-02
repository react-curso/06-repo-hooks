# useFetch Hook

````
    const { loading, data } = useFetch(`you_url`);
    
    loading = 'while charging'

    data = data in array

```

Component

```
    <div>
        {data.map( data => {
            return ( <li> {data} </li> )
        } )}
    </div>

```