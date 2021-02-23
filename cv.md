# **Rostyslav Lohvynov**
![logo](me.JPG)
## Contact Info: 

- phone: +48788249945
- e-mail: rostyslavlogvinov@gmail.com
- LinkedIn:[LinkedIn](https://www.linkedin.com/in/rostyslav-l-815b271b0/)

## About Me :

* **Education**:
> Politechnika Gdańska
> *Degree NameMaster's degreeField Of StudyTeleinformation Networks And Systems*
> Dates attended or expected graduation : *2017 – 2019*

* **Skills**:
1. **HTML**
2. **CSS**
3. **JavaScript** 
+ *React.js (basic)*
4. **Git**


## Code examples :
A Button Component from smaller project
```javascript
import React from 'react'
import classes from './Button.module.css'

const Button = props => {
const cls = [
    classes.Button,
    classes[props.type],
    ]

    return (
        <button 
            onClick={props.onClick}
            className={cls.join(' ')}
            disabled={props.disabled}
        >
            {props.children}
        </button> 
    )
    }

export default Button
```