# 6 - Missing Slice

## Objective

![CSS Battle Challenge](https://cssbattle.dev/targets/6.png)

## My Solution

    <div></div>

    <style>
        body {
            background: #E3516E;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        div {
            width: 200px;
            height: 200px;
            background: linear-gradient(45deg, #51B5A9, #51B5A9 100%), linear-gradient(135deg, #F7F3D7, #F7F3D7), 				linear-gradient(225deg, #FADE8B, #FADE8B) , linear-gradient(225deg, #E3516E, #E3516E);
            background-size: 50% 50%;
            background-position: 0% 0%, 0% 100%, 100% 0%, 100% 100%;
            background-repeat: no-repeat;
            border-radius: 50%
        }

    </style>
