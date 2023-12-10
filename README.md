





https://github.com/mdsomad/Web-Development/assets/103892160/8f77cc38-25a4-49ac-b57e-589cd516410e




```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Urbanist";
}

html {
  font-size: 62.5%;
}

body {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #191825;
}

button{
  padding:  12px 36px;
  border: 2px solid #865dff;
  text-align: center;
  color: #865dff;
  font-weight: bold;
  font-size: 20px;
  text-transform: capitalize;
  background-color: transparent;
   
  &:hover{
    border: 2px solid #d80032;
    color: #d80032;
    animation: shaking 0.2s linear;
  } 
}

@keyframes shaking {
  0% {
    rotate: 20deg;
  }
  50% {
    rotate: -20deg;
  }
  100% {
    rotate: 20deg;
  }
}
```


