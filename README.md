# Column Layout Properties in CSS

<table>

  <tr>                    
   
   <th>Before View</th>
   <th>Aftert View</th>

</tr>
  
  
<tr>

<td>

<img src="https://github.com/mdsomad/Web-Development/assets/103892160/24637761-9838-4ce4-8451-b83717e1cd02"/>

</td>
<td>

<img src="https://github.com/mdsomad/Web-Development/assets/103892160/df9f21fe-5089-4235-9b3f-f3bae6d934fe"  />

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
