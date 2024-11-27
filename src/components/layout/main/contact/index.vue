<template>
    <div>
        <h1>Bog’lanish uchun</h1>
        <div class="container">
            <div class="wrapper">
                <button>Robototexnika kursiga qabul boshlangan !</button>
            <h2>Hoziroq ro'yxatdan o'ting</h2>
            <p>va farzandingiz kelajagi uchun muhim qadamni tashlang</p>
            <form action="#">
                <input type="text" placeholder="Ismingiz">
                <input type="number" placeholder="+998-- --- -- --">
            </form>
            <button>Yuborish</button>
            </div>
        </div>
    </div>
</template>

<script setup>

</script>

<style lang="css" scoped>
h1{
    background: #00B534;
    padding: 20px 0px;
    font-weight: 800;
    font-size: 33px;
    line-height: 42px;
    text-align: center;
    color: #fff;
}
h2{
    font-size: 32px;
    font-weight: 800;
    line-height: 41px;
}
p{
    font-size: 18px;
    font-weight: 300;
    color:#00000090;

}
.wrapper{
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding: 20px;
}
button{
    padding: 15px 25px;
    background: #00B534;
    border-radius: 16px;
    margin: 40px 0px;
    color: #fff;
    border: none;
    cursor: pointer;
}
form{
    display: flex;
    gap: 30px;
}
input{
    padding: 20px 10px;
    border-radius: 16px;
    border: none;
    width: 410px;
    background: #DBF9D8;
    appearance: none;
    color: #000000;
}
</style>