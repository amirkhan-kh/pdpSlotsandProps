<template>
    <div>
        <h1>PDP Junior  kurslari</h1>
        <div class="container">
            <div class="wrapper">
                    <div class="box ">
                    <div class="card"></div>
                    <div class="card1">
                        <img src="../../../images/Screenshot 2023-04-06 at 02.49 Background Removed 1.png" alt="">
                        <div class="bio">
                            <h4> Robototexnika<span>Yangi</span></h4>
                            <p>-  Robot elektronikasini yig’ishni-  Robotlarga erkin dastur yozish C++ tilida	-  Motorlar va Sensorlarni ishlata olish		-  Korpuslarni 3D ko’rinishda yaratish</p>
                            <div class="flex items-center gap-[50px]">
                                <h5> Davomiligi<br><p>8 oy</p></h5>
                                <h5> Yosh chegarasi<br><p>10 - 17</p></h5>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="box ">
                    <div class="card"></div>
                    <div class="card1">
                        <img src="../../../images/dev.png" alt="">
                        <div class="bio">
                            <h4> Frontend</h4>
                            <p>Frontend development kursi pdp kids loyihasining yosh jihatidan uchinchi kursi hisoblanadi. Bu kursda o’quvchilar  web sahifalarning bizga ko'rinadigan vizual qismini yaratishadi. </p>
                            <div class="flex items-center gap-[50px]">
                                <h5> Davomiligi<br><p>10 oy</p></h5>
                                <h5> Yosh chegarasi<br><p>10 - 14</p></h5>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="box ">
                    <div class="card"></div>
                    <div class="card1">
                        <img src="../../../images/py.png" alt="">
                        <div class="bio">
                            <h4> Python</h4>
                            <p>Bolalar Python dasturlash tili misolida boshlang'ich dasturlash asoslarini mukammal o'rganishib bilim va ko'nikmalar hosil qiladi. Dasturlash sohasining asosiy tushunchalarini mustahkamlagan holda farzandingizda yangi bilim va ko'nikmalarni hosil qiladi.</p>
                            <div class="flex items-center gap-[50px]">
                                <h5> Davomiligi<br><p>11 oy</p></h5>
                                <h5> Yosh chegarasi<br><p> 8 - 14</p></h5>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="box ">
                    <div class="card"></div>
                    <div class="card1">
                        <img src="../../../images/scratch.png" alt="">
                        <div class="bio">
                            <h4> Scratch development </h4>
                            <p>Scratch development kursi pdp kids loyihasining yosh jihatidan ikkinchi kursi hisoblanadi. Kompyuter savodxonligiga ega bo'lgan jajji dasturchilar uchun kirish kursi hisoblandi. Oddiy dasturlash kurslaridan farqli o'laroq qiziqarli rang-barang bloklar bilan o'rgatiladi.</p>
                            <div class="flex items-center gap-[50px]">
                                <h5> Davomiligi<br><p>9 oy</p></h5>
                                <h5> Yosh chegarasi<br><p>8 - 12</p></h5>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="css" scoped>
img{
    width: 180px;
    height: 190px;
}
.card{
    width: 990px;
    height:315px;
    background-color: #DBF9D8;
    border-radius: 20px;
    transform: rotate(2deg);

    position: absolute;
}
.card1{
    width: 990px;
    height:315px;
    background-color: #ffffff;
    display: flex;
    align-items: center;
    border-radius: 20px;
    padding: 55px;
    gap: 90px;
    transform: rotate(0deg);
    box-shadow: rgba(0, 0, 0, 0.16) 0px 1px 4px;

}
.wrapper{
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 70px 0px;
    gap: 60px;
    flex-wrap: wrap;
}
h1{
    background: #00B534;
    padding: 20px 0px;
    font-weight: 800;
    font-size: 33px;
    line-height: 42px;
    text-align: center;
    color: #fff;
}
h4{
    font-size: 33px;
    line-height: 42px;
    color: #000;
    margin-bottom: 11px;
}
h5>p{
    font-size: 26px;
    line-height: 33px;
    font-weight: 800;
    color: #00B534;
}
span{
    background: #00B534; 
    color: #fff;
    border-radius: 30px;
    font-size: 17px;
    padding: 10px;
    margin-left: 10px;
}
p{
    font-size: 18.5px;
    line-height: 23px;
    color: #000;
    margin-bottom: 30px;
    font-weight: 400;
}
</style>