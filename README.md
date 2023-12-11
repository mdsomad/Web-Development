










```
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
  font-family: "Franklin Gothic Medium", "Arial Narrow", Arial, sans-serif;
}

body {
  height: 100vh;
  display: flex;
  justify-content: center;
  align-items: center;
  background-color: #191825;
}

h1 {
  font-size: 96px;
  font-weight: bold;
  text-shadow: -1px 2px 3px rgba(236, 247, 76, 0.2);
  color: #fff;
  text-transform: uppercase;
  position: relative;
}

h1::before {
  content: "NeonWolf...";
  position: absolute;
  top: 0;
  left: 0;
  width: 50%;
  color: #ff1493;
  border-right: 2px solid #ff1493;
  overflow: hidden;
  animation: textreveal 2s linear infinite;
}

@keyframes textreveal {
  0% {
    width: 0;
  }
  50% {
    width: 100%;
  }
  100% {
    width: 0;
  }
}

```


