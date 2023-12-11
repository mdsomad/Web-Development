




```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  height: 100vh;
  width: 100vw;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #ffe4d6;
}

.universe {
  width: 40vw;
  aspect-ratio: 1;
  background-color: #ffbb5c;
  display: flex;
  justify-content: center;
  align-items: center;
  border-radius: 12px;
  animation: skychange 10s ease-in-out infinite;
}

@keyframes skychange {
  0% {
    background-color: #ffbb5c;
  }
  25% {
    background-color: #ffbb5c;
  }
  50% {
    background-color: #000000;
  }
  75% {
    background-color: #ffbb5c;
  }
  100% {
    background-color: #ffbb5c;
  }
}

.sun {
  width: 18vw;
  aspect-ratio: 1;
  background-color: #e25e3e;
  border-radius: 50%;
  position: relative;
  overflow: hidden;

  &::after {
    content: "";
    position: absolute;
    top: 0;
    left: 0;
    width: inherit;
    aspect-ratio: 1;
    border-radius: inherit;
    background-color: #000;
    animation: moonwalk 10s ease-in-out infinite;
  }
}

@keyframes moonwalk {
  0% {
    translate: 100%;
  }
  50% {
    translate: 0%;
    scale: 0.95;
    box-shadow: rgba(255, 255, 255, 0.5) 0px 45px 100px 0px;
  }
  100% {
    translate: -100%;
    scale: 0.95;
  }
}


```


