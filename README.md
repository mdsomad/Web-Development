# Grid Properties in CSS
![Screenshot 2023-12-05 201022](https://github.com/mdsomad/Web-Development/assets/103892160/ebf982cf-5d20-4d4e-b802-e5f328f33827)
![Screenshot 2023-12-05 212429](https://github.com/mdsomad/Web-Development/assets/103892160/c94a96cf-6d25-422a-98d3-03bef8d5311f)
![Screenshot 2023-12-05 203956](https://github.com/mdsomad/Web-Development/assets/103892160/9b33eaed-e411-4126-930e-2c17bc0729f3)
![Screenshot 2023-12-05 204052](https://github.com/mdsomad/Web-Development/assets/103892160/65e7c7d7-556a-41d3-abef-10b64489ee8f)
### changing item position code
```sh

.item-1 {
  background-color: #662549;
  /* grid-row-start: 2;
  grid-row-end: 3; */
  /** short method */
  /* grid-row: 2/3; */
/*   
  grid-column-start: 2;
  grid-column-end: 3; */
  /** short method */
  /* grid-column: 2/3;   */
   
  /** Single line short method */
   grid-area: 2 / 2 / 3 / 3;
}
```

![Screenshot 2023-12-05 205419](https://github.com/mdsomad/Web-Development/assets/103892160/84dc1f34-7047-4bb5-bbc0-25d9b6e3b030)

```sh
.item-3 {
  background-color: #102c57;
  grid-row: 1/2;
  grid-column: 2/4;
}

```
###  Responsive grid View

![Screenshot 2023-12-05 212429](https://github.com/mdsomad/Web-Development/assets/103892160/354b1c04-c136-49c1-aea6-8958d915a8d6)
![Screenshot 2023-12-05 213034](https://github.com/mdsomad/Web-Development/assets/103892160/abc53f66-ef48-4a4b-8ec6-508e58f6128d)

```sh
.grid-container {
  width: 80%;
  margin: 100pz auto;
  padding: 50px;
  margin: 0 auto;
  box-shadow: rgba(0, 0, 0, 0.25) 0px 54px 55px,
    rgba(0, 0, 0, 0.12) 0px -12px 30px, rgba(0, 0, 0, 0.12) 0px 4px 6px,
    rgba(0, 0, 0, 0.17) 0px -12px 13px, rgba(0, 0, 0, 0.09) 0px -3px 5px;
  color: #fff;
  /*? Grid properts */
  display: grid;
  /* grid-template-rows: 250px 250px; */
  grid-template-rows: repeat(2,250px);
  /** yah hone wala extra raws ke liye hai */
  grid-auto-rows: 250px;
  /* grid-template-columns: 250px 250px 250px; */
  /* grid-template-columns: 250px 250px 1fr; */
  /* grid-template-columns: 1fr 1fr 1fr; */
  /* grid-template-columns: repeat(3, 1fr); */
  /* grid-template-columns: repeat(auto-fill,minmax(250px,1fr)); */
  /* grid-template-columns: repeat(auto-fit,minmax(250px,1fr)); */
  grid-template-columns: repeat(3,minmax(250px,1fr));


  /*? gaps */
  /* grid-row-gap: 50px; */
  /* grid-column-gap: 50px; */
  /* grid-gap: 50px; */

  /* row-gap: 50px;
  column-gap: 50px; */
  gap: 50px;

  /* ? Aling */
  /* align-items: center; */
  /* align-items: self-start; */
  /* align-items: flex-end; */
  /* align-items: stretch; */

  /*? justify horizontally */
  /* justify-items: self-start; */
  /* justify-items: center; */
  justify-items: stretch;


  
  
}

@media (width < 1200px) {
  .grid-container{
    grid-template-columns: repeat(auto-fit,minmax(250px,1fr));
  }
}
```
