# useForm

Ejemplo
```
    const initialForm = {
        name:"",
        age:0,
        email:""
    };
    
    const [ formValue, handleInputChange, reset ] = useForm( initialForm );
```