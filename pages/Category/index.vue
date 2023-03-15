<template>
    <div class="stat">
        <AddCategory />
        <div class="container">
            <div class="stat_i">
                <div class="page_title">Категории/Специализации</div>
                <div class="cards_info">
                    <div class="card_info">
                        <div class="card_info_i">
                            <div class="count">
                                <div class="c_icon">
                                    <img src="../../assets/images/plus.svg" alt="">
                                </div>
                            </div>
                            <div class="c_title">Добавить категорию</div>
                            <div class="line"></div>
                        </div>
                    </div>
                </div>
                <div class="page_i">
                    <div class="cat_line">Курьерские услуги</div>
                    <div class="cat_line">Уборка и помощь по хозяйству</div>
                    <div class="cat_line">Разработка ПО</div>
                    <div class="cat_line">Дизайн</div>
                    <div class="cat_line">Красота и здоровье</div>
                    <div class="cat_line">Репетиторы и обучение</div>
                    <div class="cat_line">Ремонт и строительство</div>
                    <div class="cat_line">Курьерские услуги</div>
                    <div class="cat_line">Курьерские услуги</div>
                    <div class="cat_line">Курьерские услуги</div>
                </div>
            </div>
        </div>
    </div>
</template>
<script>
import AddCategory from '../../components/Modals/AddCategory.vue';

export default{
    components:{
    AddCategory
}
}
</script>

<style scoped lang="scss">
.page_title {
    font-size: 22px;
    font-weight: 500;
    color: black;
    margin: 1rem 0;
}

.cards_info {
    margin-top: 2rem;
    display: flex;
    justify-content: flex-start;
    gap: 40px;
}

.card_info {
    width: 260px;
    height: 151px;
    background: #FFFFFF;
    border-radius: 20px;
    display: flex;
    justify-content: center;
    align-items: center;

    .card_info_i {
        width: 208px;
        height: 107px;
        font-family: 'Lato', sans-serif;

        .count {
            display: flex;
            justify-content: space-between;
            align-items: center;
            font-size: 24px;
            font-weight: 700;
            color: black;

            .c_icon {
                width: 60px;
                height: 60px;
                background: #FFA200;
                border-radius: 7px;
                display: flex;
                justify-content: center;
                align-items: center;
            }
        }

        .c_title {
            color: black !important;
            font-size: 16px;
            font-weight: 400;
            margin-top: 10px;
            text-align: justify;
        }

        .line {
            margin-top: 10px;
            width: 100%;
            height: .5px;
            background-color: #FFA200;
        }
    }
}

.page_i {
    width: 100%;
    height: 550px;
    overflow: auto;
    margin-top: 2rem;
    font-family: 'Lato',sans-serif;

    .cat_line {
        margin-bottom: 15px;
        width: 100%;
        height: 61px;
        background: #FFFFFF;
        border-radius: 20px;
        display: flex;
        justify-content: flex-start;
        align-items: center;
        padding-left: 2rem;
        font-size: 16px;
        font-weight: 400;
    }
}
</style>