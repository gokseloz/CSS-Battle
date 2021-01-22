# 3 - Push Button

## Objective

![CSS Battle Challenge](https://cssbattle.dev/targets/3.png)

## My Solution

    <div class="rect">
        <div class="lb c">
            <div class="db c">
                <div class="ylw c"></div>
            </div>
        </div>
    </div>

    <style>
    body {
        background: #6592CF;
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
        width: 300px;
        height: 150px;
        background: #243D83;
    }
    .c {
        border-radius: 50%
    }
    .lb {
        background: #6592CF;
        height: 250px;
        width: 250px;
    }
    .db {
        background: #243D83;
        height: 150px;
        width: 150px;
    }
    .ylw {
        background: #EEB850;
        height: 50px;
        width: 50px;
    }
    </style>
