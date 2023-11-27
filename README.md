# Text Properties
### Before UI
![Screenshot 2023-11-27 120336](https://github.com/mdsomad/Web-Development/assets/103892160/9b3f328e-7fb8-4aee-aa18-b0fc9179421c)
### After UI
![Screenshot 2023-11-27 123530](https://github.com/mdsomad/Web-Development/assets/103892160/a360fc60-4f52-4a24-873d-c3301465a9fa)
```sh
body {
  background-color: hsl(0, 0%, 94%);
  display: grid;
  place-items: center;
}

.hero-section {
  width: 50%;
}

h1 {
  font-size: 54px;
  font-weight: 900;
  /*? Text Properties */
  text-align: left;
  text-decoration-line: underline;
  -moz-text-decoration-line: underline;
  text-decoration-color: red;
  text-decoration-thickness: 10px;
  text-decoration-style: solid;
  text-transform: capitalize;
  text-shadow: -2px -2px 5px green ;
}

p {
  font-size: 20px;
  font-weight: 300;
  /*? Text Properties */
  letter-spacing: 1.2px;
  word-spacing: 1px;
  line-height: 1.56;
  /* white-space: nowrap; */
}

/*? :: first-letter pseudo-element in CSS */

p::first-letter{
  text-transform: uppercase;
  font-size: 45px;
  font-weight: 600;
  color: rgb(0, 0, 255);
}


```
