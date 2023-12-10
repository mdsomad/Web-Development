
```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
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

.loader{
  width: 20rem;
  aspect-ratio: 1;
  border-radius: 50%;
  background-color: #865dff;
  position: relative;
  animation: circleloader 2s linear infinite reverse;
}

@keyframes circleloader {
  100% {
    rotate: 360deg;
  }
}

.loader::before{
  content: "";
  position: absolute;
  top: 0;
  left: 0;
  width: 17rem;
  aspect-ratio: 1;
  border-radius: 50%;
  background-color:#191825;
}
.loader:after{
  content: "";
  position: absolute;
  top: -2.5rem;
  left: 8.5rem;
  width: 5rem;
  aspect-ratio: 1;
  border-radius: 50%;
  background-color:#865dff;
  box-shadow: 0 0 1rem #865dff , 0 0 1.5rem #865dff, 0 0 2rem #865dff,
  0 0 2.5rem #865dff, 0 0 3rem #865dff; 
}
```


