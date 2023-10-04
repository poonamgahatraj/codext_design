<template>
<div style="background: #FFF;">
    <div class="headingg">
        <h1 style="width: 46%;
    line-height: 50px;font-size: 45px;">We Provides best Feature for customar</h1>
    </div>
    <div class="content">
        <div class="box">
            <div class="img">
                <img src="public/assets/Group 411.png">
            </div>
            <div class="content1">
                
                <h5>Clean Code</h5>
                <p class="p">Lorem ipsum dolor sit amet ecte adipiscing elitIpsum.</p>
                <img src="public/assets/Group 10.png">
            </div>   
        </div>


        <div class="box">
            <div class="img">
                <img src="public/assets/Group 412.png">
            </div>
            <div class="content1">
                <h5>Data Analytic</h5>
                <p class="p">Lorem ipsum dolor sit amet ecte adipiscing elitIpsum.</p>
                <img src="public/assets/Group 10.png">
            </div>
        </div>
        <div class="box">
            <div class="img">
                <img src="public/assets/Group 413.png">
            </div>
            <div class="content1">
                <h5>Fully Secured</h5>
                <p class="p">Lorem ipsum dolor sit amet ecte adipiscing elitIpsum.</p>
                <img src="public/assets/Group 10.png">
            </div>
        </div>
        <div class="box">
            <div class="img">
                <img src="public/assets/Group 414.png">
            </div>
            <div class="content1">
                <h5>24/7 Support</h5>
                <p class="p">Lorem ipsum dolor sit amet ecte adipiscing elitIpsum.</p>
                <img src="public/assets/Group 10.png">
            </div>
        </div>
    </div>

</div>

</template>

<style scoped>

.content{
    display:flex;
    justify-content: space-between;
}
.box{
width: 250px;

flex-shrink: 0;

border-radius: 10px;
background: #FFF;
box-shadow: 0px 6px 50px 5px rgba(6, 14, 26, 0.05);
}

.content1{
width: 265px;
height: 209px;
flex-shrink: 0;
background-image: linear-gradient 107deg, #5A1FAF -25.47%, #692BC3 136.15%;
stroke-width: 1px;
stroke: #000;



text-align: center;
font-family: Inter;
font-size: 25px;
font-style: normal;
font-weight: 500;
line-height:100% /* 37.5px */
}

.img{
    display: flex;
    justify-content: center;
    margin-top:15%;
}

.headingg{
    color: var(--Black, #051114);
text-align: center;
font-family: Inter;
font-size: 44px;
font-style: normal;
font-weight: 600;
line-height: 130%;
display: flex;
justify-content: center;
}

.p{
    color:grey;
    font-size: 16px;
}
</style>