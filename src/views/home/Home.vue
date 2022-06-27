<template>
    <div class="app">
        <div class="header">
            <img class="icon_ml" src="../../assets/images/icon_fanhui.png" alt="">
            <span class="txt">Local screencast</span>
            <div class="header-box"></div>
        </div>
        <div class="main">
            <div class="flex-center">
                <input class="ipt" placeholder="search"  type="text">
                 <img src="../../assets/images/icon_sousuo.png" alt="">
            </div>
            <div class="flex">
                <img src="../../assets/images/icon_waaw.jpg" alt="">
                <div>
                    <div class="font-Size">Mirror guide</div>
                    <div class="font-size">common problem</div>
                </div>
                
                <div></div>
            </div>
            <div class="flex-scoll">
                <div class="item itemcolor1">
                    <img src="../../assets/images/icon_item.png" alt="">
                    <div class="font-bai">Picture</div>
                    <div class="font-hui">Local screencost</div>
                </div>
                <div class="item itemcolor2">
                     <img src="../../assets/images/icon_item.png" alt="">
                    <div class="font-bai">Picture</div>
                    <div class="font-hui">Local screencost</div>
                </div>
                <div class="item itemcolor3">
                     <img src="../../assets/images/icon_item.png" alt="">
                    <div class="font-bai">Picture</div>
                    <div class="font-hui">Local screencost</div>
                </div>
            </div>
        </div>
        <div class="footer">
            <div class="footertop"></div>
            <div class="footerbtn">
                <button class="btn">|| Time out</button>
                <button class="btn">@ End</button>
            </div>
        </div>
    </div>
</template>
<style>
    .app{
        /* height: 100vh; */
        border-radius: 50px;
        background-image:linear-gradient(#d6cff9,#e6e8f5);
        padding: 2.4rem;
    }   
        .icon_ml,.header-box{
            width: 2rem;
        }
        .header{
            display: flex;
            align-items: center;
            justify-content:space-around;
            padding: 45px 0 0 0;
            box-sizing: border-box;
        }
        .header .txt{
            font-size: 1.6rem;
        }
        .main .ipt{
            outline: none;
            border-radius: 12px;
            height: 5.8rem;
            border: none;
            width: 100%;
            margin-top: 2.5rem;
            text-indent: 2rem;
        }
        .flex-center{
            display: flex;
            align-items: center;
        }
        .flex-center img{
            width: 3rem;
            height: 3rem;
            margin-top: 3rem;
            margin-left: -5rem;
        }
        .flex{
            margin-top: 2rem;
            display: flex;
            align-items: center;
            justify-content: space-around;
            height: 10rem;
            background-color: #eceaff;
            border-radius: 45px;
        }
        .flex img{
            height: 10rem;
            margin-left: 1rem;
            border-radius: 5px;
        }
        .font-Size{
            font-size: 2rem;
            font-weight: 600;
        }
        .font-size{
            font-size: 1.5rem;
        }
        .flex-scoll{
            display: flex;
            overflow-x: scroll;
            margin-top: 3.5rem;
        }
        .item{
            min-width: 13.5rem;
            height: 16.5rem;
            display: flex;
            border-radius: 15px;
            margin-left: 1.5rem;
        }
        .item img{
            width: 6rem;
            height: 6rem;
            border-radius: 20px;
        }
        ::-webkit-scrollbar{
            display: none;
        }
        .itemcolor1{
            background-color: #7367fb;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-evenly;
        }
        .font-bai{
            font-size: 1.8rem;
            color: #fafbff;
        }
        .font-hui{
            font-size: 1.4rem;
            color: #9389fb;
        }
        .itemcolor2{
            background-color: #ffffff;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-evenly;
        }
        .itemcolor3{
            background-color: #eceaff;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: space-evenly;
        }
        .footer{
            height: 25rem;
            margin-top: 3.5rem;
            background-color: #e5e2ff;
            border-radius: 20px;
        }
        .footertop{
            background-color: #ffffff;
            height: 12.5rem;
            border-radius: 20px;
        }
        .footerbtn{
            display: flex;
            justify-content: space-around;
            margin-top: 3rem;
        }
        .btn{
            border: none;
            background-color: #ffffff;
            padding: 2rem;
        }
</style>