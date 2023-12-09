



https://github.com/mdsomad/Web-Development/assets/103892160/c1323bb6-016a-42a0-84e4-d76de4f251e2




```sh
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
  background-color: #2b3033;
}

.container-img {
  width: 60vw;
  height: 50rem;
  border-radius: 1rem;
  box-shadow: rgba(100, 100, 111, 0.2) 0px 7px 29px 0px;
  background-image: url("https://images.pexels.com/photos/534164/pexels-photo-534164.jpeg?auto=compress&cs=tinysrgb&w=600");
  background-size: cover;
  animation: gallery 20s linear infinite;
}

@keyframes gallery {
  0% {
    background-image: url("https://images.pexels.com/photos/612891/pexels-photo-612891.jpeg?auto=compress&cs=tinysrgb&w=600");
  }
  20% {
    background-image: url("https://images.pexels.com/photos/2104152/pexels-photo-2104152.jpeg?auto=compress&cs=tinysrgb&w=600");
  }
  40% {
    background-image: url("https://images.pexels.com/photos/459038/pexels-photo-459038.jpeg?auto=compress&cs=tinysrgb&w=600");
  }
  60% {
    background-image: url("https://images.pexels.com/photos/237321/pexels-photo-237321.jpeg?auto=compress&cs=tinysrgb&w=600");
  }
  80% {
    background-image: url("https://images.pexels.com/photos/1574181/pexels-photo-1574181.jpeg");
  }
  100% {
    background-image: url("https://images.pexels.com/photos/951076/pexels-photo-951076.jpeg?auto=compress&cs=tinysrgb&w=600");
  }
}

```



