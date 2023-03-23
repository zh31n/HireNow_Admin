<template>
    <div class="chat_page">
        <div class="container">
            <div class="info_stats">
                <div class="info_page">
                    Чаты
                </div>
                <div class="btn_back">
                    <img src="../../assets/images/Arrow_back.svg" alt="">
                    Назад к чатам
                </div>
            </div>
            <ModalMessages />
        </div>
    </div>
</template>

<script>
import ModalMessages from '../../components/Modals/ModalMessages.vue';

export default {
    components: {
        ModalMessages
    }
}
</script>


<style scoped lang="scss">

.chat_page {
    padding-top: 2rem;
    width: calc(100vw - 250px);
}
.info_stats {
    display: flex;
    justify-content: space-between;
    align-items: center;
    margin-top: 2rem;
}

.info_page {
    font-size: 22px;
    font-weight: 500;
    color: black;
    font-family: 'DM Sans', sans-serif;

    span {
        color: #FFA200;
    }
}

.btn_back {
    font-family: 'Lato', sans-serif;
    display: flex;
    justify-content: flex-start;
    gap: 10px;
    align-items: center;
    color: #FFA200;
    font-size: 14px;
    font-weight: 400;
}
</style>