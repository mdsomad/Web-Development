# flexBox Properties in CSS



```sh
.flex-container {
  width: 60%;
  height: auto;
  padding: 50px;
  margin: 0 auto;
  box-shadow: rgba(0, 0, 0, 16) 0px 1px 4px, rgb(51, 51, 51) 0px 0px 0px 3px;
  background: linear-gradient(to right, #514a9d, #24c6dc);
  color: #fff;
  /*? flexbox container propertu */
  display: flex;
  flex-direction: row;
  gap: 20px;
  flex-wrap: wrap;
  align-content: center;
}

.item {
  min-width: 200px;
  height: 100px;
  /* aspect-ratio: 1; */
  background-image: linear-gradient(to right top, #004d7a, #00bf72, #a8eb12);
  box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px, rgb(51, 51, 51) 0px 0px 0px 3px;
  font-size: 24px;
}
.item-2 {
  flex-grow: 1;
  flex-shrink: 5;
}

```
