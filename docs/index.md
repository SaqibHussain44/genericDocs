# Generic Login System
___
###login

**http POST:**  `http://172.25.33.42:8080/login `  
**JSON**  
```json
{    
	"record":    "gander",  
	"email":     "youremail@gmail.com",  
	"password":  "Abc123@!"  
}    
```
**Considerations**  

1. `record` would be the name of the system you're loging in e.g. _(gander, tokenlab, mistwallet)_
2. `password` must be minimum 8 character, with one Upper one lower character and a digit 
3. `email` and `password` format is validated on the server as well


---
<br>
###Signup

**http POST:**  `http://172.25.33.42:8079/signup`  
**JSON**  
```json
{    
	"record":    "gander",
	"username":  "test user",  
	"email":     "youremail@gmail.com",  
	"password":  "Abc123@!"  
}    
```
**Considerations**  

1. `record` would be the name of the system you're loging in e.g. _(gander, tokenlab, mistwallet)_
2. `password` must be minimum 8 character, with one Upper one lower character and a digit 
3.  whole document format is validated on the server


---
