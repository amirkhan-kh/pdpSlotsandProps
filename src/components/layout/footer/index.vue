<template>
    <div>
        <footer>
            <div class="container">
                <nav>
                    <img src="../../../assets//icon/logo.svg" alt="">
                    <div class="flex items-center gap-[10px]">
                        <a href="#"><img src="../../images/tm.svg" alt=""></a>
                        <a href="#"><img src="../../images/instagram.svg" alt=""></a>
                        <a href="#"><img src="../../images/youtube.svg" alt=""></a>
                    </div>
                    <a href="#">(78) 777-47-47</a>
                </nav>
                <div class="flex items-center justify-between">
                    <p>©2022 PDP Academy</p>
                    <p>Xizmatlar litsenziyalangan</p>
                </div>
            </div>
        </footer>
    </div>
</template>

<script setup>

</script>

<style lang="css" scoped>
footer{
    background: #012A30;
    width: 100%;
    padding: 39px 100px;
}
nav{
    display: flex;
    justify-content: space-between;
    align-items: center;
    border-bottom: 1px solid silver;
    padding: 18px;
    color: #DBF9D8;
}
p{
    color: #DBF9D8;
    font-size: 12px;
    font-weight: 500;
}
</style>