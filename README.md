# Pseudo Elements Properties in CSS
<table>
  <tr>                    
   
   <th>Before View</th>
   <th>Aftert View</th>

</tr>
  
  
<tr>

<td>

<img src="https://github.com/mdsomad/Web-Development/assets/103892160/09b1670a-d4ed-4bdb-943f-204ff66a708d"/>

</td>
<td>

<img src="https://github.com/mdsomad/Web-Development/assets/103892160/c419442d-060f-4b2a-ad88-2d24661f85e4"  />

</td>


</tr>

</table>

### Filter-function values
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
.section-hero h1 {
  font-size: 30px;
  position: relative;
  display: inline-block;
}

/*? Before Pseudo elements */
.section-hero h1::before{
  content: "Somad";
  position: absolute;
  top: -25px;
  font-size: 14px;
  letter-spacing: 4px;
  color:#ffcc70;
}

/*? After Pseudo elements */
.section-hero h1::after{
  content: "";
  position: absolute;
  right: 0;
  bottom: 0;
  border: 2px solid red;
  width: 70%;
}

div{
  margin-top: 10px;
}

p::selection{
  background-color: teal;
}

```

