# Transition Properties in CSS

![Screenshot 2023-12-06 204034](https://github.com/mdsomad/Web-Development/assets/103892160/bf2941b2-0983-4d04-a594-b0d25d07fd69)
![Screenshot 2023-12-06 204123](https://github.com/mdsomad/Web-Development/assets/103892160/edfb9683-60d7-42f9-923e-a37a6b1f49b2)
![Screenshot 2023-12-06 204103](https://github.com/mdsomad/Web-Development/assets/103892160/8b056701-742d-49ef-873b-2cb0b4bc1c87)
```sh


      .container {
        width: 100%;
        height: 100vh;
        display: flex;
        flex-direction: column;
        justify-content: center;
        gap: 40px;
        padding-left: 50px;
      }

      .box {
        width: 100px;
        aspect-ratio: 1;
        background-color: #4861ec;
        box-shadow: 0 0 0 15px #353f6d;
        border-radius: 50%;
        transition: all 5s;
      }

      .box:nth-child(1):hover {
        transition-timing-function: ease;
        translate: 90vw 0;
      }
      /* Second box */
      .box:nth-child(2):hover {
        transform: translateX(90vw);
        transition:  5s ease-in;
      }
      /* Third box */
      .box:nth-child(3):hover {
        background-color: #4bc77d;
        transform: translateX(90vw);
        transition:  5s ease-in-out;
      }
      /* Fourth box */
      .box:nth-child(4):hover {
        background-color: #FF1493;
        transform: translateX(90vw);
        transition:  5s linear;
      }
```
