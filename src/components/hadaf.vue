<template>
    <div>
        <h1 style="float:right; color:#1670f0">اهداف آینده  (2020)</h1>
        <div class="apr">
            
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <p style="position:reletive; font-size:20px; font-weight:800; ">APRIL</p>
            اضافه شدن 1000+ پیپ سود روزانه با-<br>معاملات بلند مدت برای اشتراک الماس
            <br>
            ربات تلگرامی برای راحت تر کردن کار ها-
        </div>
        <div class="may">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <p style="position:reletive; font-size:20px; font-weight:800; ">MAY</p>
                اضافه کردن سیگنال برای-<br>            (Fix-Contraket) باینری آپشن
        </div>
        <div class="jun">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <p style="position:reletive; font-size:20px; font-weight:800; ">JUNE</p>
                اضافه شدن سیگنال های- <br>ارزهای دیجیتال(15لی25 سیگنال روزانه)
        </div>
        <div class="jul">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <p style="position:reletive; font-size:20px; font-weight:800; ">JULY</p>
            افزایش دو برابر قیمت اشتراک ها-<br>
             ios و android اپلیکیشن- 
        </div>
    </div>
</template>
<script>
export default{
    name:"hadaf"
}
</script>
<style scoped>
.apr{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    position: absolute;
    width: 400px;
    height: 150px;
    font-weight: 500;
    right: 5%;
    background-color: #190255;
    top:100px;
    color:#1670f0;
    letter-spacing: 1px;
    text-align: center;
    box-shadow: 0 20px 50px rgba(0, 0, 0, .5);overflow: hidden;
}
.apr span:nth-child(1){
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 2px;
    background: linear-gradient(to right,#0c002b,#1779ff);
    animation: animate1 2s linear infinite;
    animation-delay: 1s;
}
@keyframes animate1
{
    0%{
        transform: translateX(-100%);
    }
    100%{
        transform: translateX(100%);
    }
}

.apr span:nth-child(2){
    position: absolute;
    top: 0;
    right: 0;
    width: 2px;
    height: 100%;
    background: linear-gradient(to bottom,#0c002b,#1779ff);
    animation: animate2 2s linear infinite;
}

@keyframes animate2
{
    0%{
        transform: translateY(-100%);
    }
    100%{
        transform: translateY(100%);
    }
}

.apr span:nth-child(3){
    position: absolute;
    bottom: 0;
    right: 0;
    width: 100%;
    height: 2px;
    background: linear-gradient(to left,#0c002b,#1779ff);
    animation: animate3 2s linear infinite;
    animation-delay: 1s;
}
@keyframes animate3
{
    0%{
        transform: translateX(100%);
    }
    100%{
        transform: translateX(-100%);
    }
}
.apr span:nth-child(4){
    position: absolute;
    top: 0;
    left:  0;
    width: 2px;
    height: 100%;
    background: linear-gradient(to top,#0c002b,#1779ff);
    animation: animate4 2s linear infinite;
    
}
@keyframes animate4
{
    0%{
        transform: translateY(100%);
    }
    100%{
        transform: translateY(-100%);
    }
}
.may{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    position: absolute;
    width: 400px;
    height: 150px;
    font-weight: 500;
    right: 25%;
    background-color: #190255;
    top:300px;
    color:#1670f0;
    letter-spacing: 1px;
    text-align: center;
    box-shadow: 0 20px 50px rgba(0, 0, 0, .5);overflow: hidden;
}
.may span:nth-child(1){
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 2px;
    background: linear-gradient(to right,#0c002b,#1779ff);
    animation: animate1 2s linear infinite;
    animation-delay: 1s;
}
.may span:nth-child(2){
    position: absolute;
    top: 0;
    right: 0;
    width: 2px;
    height: 100%;
    background: linear-gradient(to bottom,#0c002b,#1779ff);
    animation: animate2 2s linear infinite;
}
.may span:nth-child(3){
    position: absolute;
    bottom: 0;
    right: 0;
    width: 100%;
    height: 2px;
    background: linear-gradient(to left,#0c002b,#1779ff);
    animation: animate3 2s linear infinite;
    animation-delay: 1s;
}
.may span:nth-child(4){
    position: absolute;
    top: 0;
    left:  0;
    width: 2px;
    height: 100%;
    background: linear-gradient(to top,#0c002b,#1779ff);
    animation: animate4 2s linear infinite;
    
}
.jun{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    position: absolute;
    width: 400px;
    height: 150px;
    font-weight: 500;
    right: 45%;
    background-color: #190255;
    top:100px;
    color:#1670f0;
    letter-spacing: 1px;
    text-align: center;
    box-shadow: 0 20px 50px rgba(0, 0, 0, .5);overflow: hidden;
}
.jun span:nth-child(1){
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 2px;
    background: linear-gradient(to right,#0c002b,#1779ff);
    animation: animate1 2s linear infinite;
    animation-delay: 1s;
}
.jun span:nth-child(2){
    position: absolute;
    top: 0;
    right: 0;
    width: 2px;
    height: 100%;
    background: linear-gradient(to bottom,#0c002b,#1779ff);
    animation: animate2 2s linear infinite;
}
.jun span:nth-child(3){
    position: absolute;
    bottom: 0;
    right: 0;
    width: 100%;
    height: 2px;
    background: linear-gradient(to left,#0c002b,#1779ff);
    animation: animate3 2s linear infinite;
    animation-delay: 1s;
}
.jun span:nth-child(4){
    position: absolute;
    top: 0;
    left:  0;
    width: 2px;
    height: 100%;
    background: linear-gradient(to top,#0c002b,#1779ff);
    animation: animate4 2s linear infinite;
    
}
.jul{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    position: absolute;
    width: 400px;
    height: 150px;
    font-weight: 500;
    right: 65%;
    background-color: #190255;
    top:300px;
    color:#1670f0;
    letter-spacing: 1px;
    text-align: center;
    box-shadow: 0 20px 50px rgba(0, 0, 0, .5);
    overflow: hidden;
}
.jul span:nth-child(1){
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 2px;
    background: linear-gradient(to right,#0c002b,#1779ff);
    animation: animate1 2s linear infinite;
    animation-delay: 1s;
}
.jul span:nth-child(2){
    position: absolute;
    top: 0;
    right: 0;
    width: 2px;
    height: 100%;
    background: linear-gradient(to bottom,#0c002b,#1779ff);
    animation: animate2 2s linear infinite;
}
.jul span:nth-child(3){
    position: absolute;
    bottom: 0;
    right: 0;
    width: 100%;
    height: 2px;
    background: linear-gradient(to left,#0c002b,#1779ff);
    animation: animate3 2s linear infinite;
    animation-delay: 1s;
}
.jul span:nth-child(4){
    position: absolute;
    top: 0;
    left:  0;
    width: 2px;
    height: 100%;
    background: linear-gradient(to top,#0c002b,#1779ff);
    animation: animate4 2s linear infinite;
    
}

</style>