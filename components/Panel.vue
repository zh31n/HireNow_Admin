<template>
    <div class="Panel">
        <img class="logo_panel" src="../assets/images/LOGO.svg" alt="">
        <div class="panel_btns">
            <NuxtLink to="/" class="p_btn ">
                <img src="../assets/images/banknote.svg" alt="">
                Баланс
            </NuxtLink>
            <NuxtLink to="/Stat" class="p_btn ">
                <img src="../assets/images/stat.svg" alt="">
                Статистика
            </NuxtLink>
            <NuxtLink to="/Moderation" class="p_btn ">
                <img src="../assets/images/protect.svg" alt="">
                Модерация
            </NuxtLink>
            <NuxtLink to="/Category" class="p_btn " >
                <img src="../assets/images/books.svg" alt="">
                Категории
            </NuxtLink>
            <NuxtLink to="/" class="p_btn ">
                <img src="../assets/images/chat.svg" alt="">
                Чат
            </NuxtLink>
            <NuxtLink to="/" class="p_btn ">
                <img src="../assets/images/person.svg" alt="">
                Пользователи
            </NuxtLink>
            <NuxtLink to="/" class="p_btn ">
                <img src="../assets/images/gearshape.svg" alt="">
                Настройки
            </NuxtLink>
            <div class="p_btn ">
                <img src="../assets/images/figure.svg" alt="">
                Выйти из профиля
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'Panel'
}
</script>

<style scoped lang="scss">
.Panel {

    height: 100vh;
    width: 250px;
    background-color: #ffa200;
    padding: 3rem 0;

    .logo_panel {
        margin-right: auto;
        margin-left: auto;
    }

    .panel_btns{
        margin-top: 2rem;
        transition: all .3s;
    }

    .p_btn {
        width: 204px;
        height: 50px;
        display: flex;
        justify-content: flex-start;
        gap: 10px;
        align-items: center;
        font-family: 'Lato', sans-serif;
        font-size: 18px;
        font-weight: 400;
        border-radius: 10px;
        color: white;
        margin-right: auto;
        margin-left: auto;
        margin-top: 1rem;
        padding-left: 1rem;
        cursor: pointer;
        transition: all .3s;
    }

    .p_btn.active {
        background-color: #DF8E00;
    }
    .p_btn:hover{
        background-color: #DF8E00;
        transition: all .3s;
    }

    .p_btn:last-child{
        margin-top: 15rem;
    }
}
</style>