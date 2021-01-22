# 4 - Ups n Downs

## Objective

![CSS Battle Challenge](https://cssbattle.dev/targets/4.png)

## My Solution

    <p></p>
    <p></p>
    <p></p>

    <style>
        body {
            display:flex;
            align-items:center;
            justify-content:center;
            background:#62306D
        }
        p {
            width:100;
            height:200;
            background:linear-gradient(#62306D 50%,0,#F7EC7D);
            border-radius:50px
        }
        p:nth-child(2) {
            transform:scaleY(-1)
        }
    </style>
