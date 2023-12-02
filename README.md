# Anchor Properties in CSS

![Screenshot 2023-12-02 161956](https://github.com/mdsomad/Web-Development/assets/103892160/da8d3094-3808-4e44-bc4e-cbaa3f8b8f80)
![Screenshot 2023-12-02 162325](https://github.com/mdsomad/Web-Development/assets/103892160/a46620da-ebae-4a21-ae7b-f7a94356ada6)


```sh
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}
body {
  display: flex;
  background-color: #080a0c;
  color: azure;
  height: 100vh;
  align-items: center;
  justify-content: center;
}
.section-hero a {
  color: #080a0c;
}

.section-hero a:link {
  background-color: #fff;
  display: inline-block;
  padding: 10px 32px;
  text-transform: capitalize;
  text-decoration: none;
  border-radius: 5px;
  font-size: 24px;
  font-weight: bold;
}


.section-hero a:visited{
  color: #d67e03;
}

.section-hero a:hover{
  color: #0062ff;
}

.section-hero a:active{
  color: #f31559;
}

```

