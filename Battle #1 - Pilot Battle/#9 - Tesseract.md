# 9 - Tesseract

## Objective

![CSS Battle Challenge](https://cssbattle.dev/targets/9.png)

## My Solution

    <div class="rect">
        <div class="db">
            <div class="lb">
                <div class="crl"></div>
            </div>
        </div>
    </div>

    <style>
        body {
            background: #222730;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
        }
        div {
            display: flex;
            justify-content: center;
            align-items: center;
        }
        .rect {
            background: #4CAAB3;
            height: 150px;
            width: 400px;
        }
        .db {
            background: #222730;
            width: 250px;
            height: 250px;
            transform: rotate(45deg);
        }
        .lb {
            background: #4CAAB3;
            width: 150px;
            height: 150px;
            transform: rotate(90deg);
        }
        .crl {
            background: #393E46;
            width: 50px;
            height: 50px;
            border-radius: 50%;
        }
    </style>
