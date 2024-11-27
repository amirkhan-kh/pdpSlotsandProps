<template>
    <div class="container">
    <div class="intro">
            <div class="flex items-center p-[120px] ">
                <div class="left relative">
                    <div class="card absolute bg-[#DBF9D8] w-[480px] h-[450px] rotate-6 rounded-[21px]"></div>
                    <div class="card absolute bg-[#fff] border border-[#f0eded] w-[480px] h-[450px] rounded-[21px] p-9">
                        <h1>PDP Junior – IT kelajakni shu yerdan boshlang!</h1>
                        <div class="items">
                            <div class="circle">1</div>
                            <div class="option">
                                <h3>Sifatli Ta’lim</h3>
                                <p>5 yildan beri katta-yu kichik dasturchilarni yetishtirib chiqarmoqda</p>
                            </div>
                        </div>
                        <div class="items">
                            <div class="circle">2</div>
                            <div class="option">
                                <h3>Bilim va ko’nikma</h3>
                                <p>Yoshlar dasturlash va tanqidiy fikrlash ko'nikmalariga ega bo'lishmoqda</p>
                            </div>
                        </div>
                        <div class="items">
                            <div class="circle">3</div>
                            <div class="option">
                                <h3>Natija</h3>
                                <p>Algoritmlar orqali masalalar yechib, kichik oʻyinlar yasashmoqda</p>
                            </div>
                        </div>
                    </div>
                </div>
                <div class="right"></div>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="css" scoped>
.intro{
    background-image: url("../../../../components/images/Hero BG.png");
    height: 820px;
    background-repeat: no-repeat;
    background-size: cover;
    background-position: center;
}
h1{
    font-size: 31px;
    color: #012A30;
    font-weight: 800;
    line-height: 40.3px;
    margin-bottom: 15px;
}
h3{
    font-size: 20px;
    color: #00B534;
    font-weight: 800;
    line-height: 28px;
    margin-bottom: 7px;
}
p{
    font-size: 16px;
    color: #636363;
    font-weight: 400;
    line-height: 21px;
}
.items{
    display: flex;
    margin-bottom: 23px;
    gap: 20px;
}
.circle{
    width: 50px;
    height: 40px;
    background-color: #d0e9ce;
    border-radius: 50%;
    color: #000000;
    font-size: 27px;
    line-height: 35px;
    display: grid;
    place-items: center;
}
</style>