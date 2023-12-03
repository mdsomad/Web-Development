# Column Layout Properties in CSS

<table>
  <tr>                    
   
   <th>Before View</th>
   <th>Aftert View</th>

</tr>
  
  
<tr>

<td>

<img src=""/>

</td>
<td>

<img src=""  />

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
  padding: 20px 20px;
}
.section-hero h1 {
  font-size: 30px;
  align-items: center;
  margin-left: 40%;
  color: red;
}

div {
  margin-top: 30px;
}

p {
  column-count: 3;
  column-rule: 4px solid blue;
  column-gap: 50px;
  text-align: justify;
}

```
