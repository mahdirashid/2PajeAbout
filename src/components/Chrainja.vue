<template>
    <div>
        <div class="background">
            <span></span>
            <span></span>
            <span></span>
            <span></span>
            <p class="p-head">چرا اینجاییم؟؟</p>
            <p style="margin-top:90px ;width:95%">
                "تا نگردى آشنا زين پرده رمزى نشنوى"<br>
              من سيد مهدى حسينى كار آفرين و فعال حوزه هاى مالى و مدير شركت گاما همراه تيمم براى ساده و راحت تر كردن معاملات در بازارهاى فاركس و ارزهاى ديجيتال سيگنال هاى مطمئنى را كاربران قرار ميدهيم.
            </p>
            <p style="margin-top:0; width:95% ">
                هدف اصلى اين مجموعه بالا بردن اطلاعات كاربران در مورد بازارهاى مالى ميباشد و نتيجه اى كه قراره ما هر روز از اين بازارا بگيريم:      
                <br>
                ١- حفظ سرمايه اوليه
                <br>
                ٢- دريافت سودهاى پلّه اى
            </p>
            <p style="margin-top:-4px; width:95%">
                شما فقط با ثبت نام كردن داخل سايت ما هر روز يك سيگنال رايگان با سود مطمئن ٥٠+ پيپ دريافت ميكنيد.
                <br>
                راستى !! حتى بعد از تهيه اشتراك از ما ، به هر دليلى از زمان خريد تا يك هفته فرصت داريد ٨٠٪؜ از مبلغ پرادختى خود دريافت كرده و اشتراك خود را لغو كنيد.
                
            </p>
            <p style="width:95%; ">
                " شما اومديد اينجا پول در بياريد ، ما هم اومديم اينجا پول در بياريم ؛ به خدا از اينا واسه خونه خودمونم ميبرم "
            </p>
        </div>
    </div>
</template>
<script>
export default {
    
}
</script>
<style scoped>
.p-head{
    float: right;
    color:#1779ff;
    font-size: 25px;
    text-indent: -5px;
    font-weight: 800;
    margin-right: 15px;
}
.background{
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    color: #1779ff;
    font-weight: 600;
    width: 60%;
    letter-spacing: 1px;
    height: 450px;
    position: absolute;
    top: 50%;
    left: 50%;
    background-color: #190255;
    transform: translate(-50% , -50%);
    box-shadow: 0 20px 50px rgba(0, 0, 0, .5);
    overflow: hidden;
    text-align: right;
    padding: 20px;
    direction: rtl;
}

.background span:nth-child(1){
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 4px;
    background: linear-gradient(to right,#0c002b,#1779ff);
    animation: animate1 4s linear infinite;
    animation-delay: 2s;
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

.background span:nth-child(2){
    position: absolute;
    top: 0;
    right: 0;
    width: 4px;
    height: 100%;
    background: linear-gradient(to bottom,#0c002b,#1779ff);
    animation: animate2 4s linear infinite;
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

.background span:nth-child(3){
    position: absolute;
    bottom: 0;
    right: 0;
    width: 100%;
    height: 4px;
    background: linear-gradient(to left,#0c002b,#1779ff);
    animation: animate3 4s linear infinite;
    animation-delay: 2s;
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
.background span:nth-child(4){
    position: absolute;
    top: 0;
    left:  0;
    width: 4px;
    height: 100%;
    background: linear-gradient(to top,#0c002b,#1779ff);
    animation: animate4 4s linear infinite;
    
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
</style>