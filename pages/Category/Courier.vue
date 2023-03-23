<template>
    <div class="courier_page">
        <AddPodcategory style="display: none;"/>
        <div class="container">
            <div class="info_stats">
                <div class="info_page">
                    Курьерские услуги
                </div>
                <div class="btn_back">
                    <img src="../../assets/images/Arrow_back.svg" alt="">
                    Назад к статистике
                </div>
            </div>
            <div class="c_table">
                <div class="cards_info">
                    <div class="card_info">
                        <div class="card_info_i">
                            <div class="count">
                                <div class="c_icon">
                                    <img src="../../assets/images/plus.svg" alt="">
                                </div>
                            </div>
                            <div class="c_title">Добавить специализацию</div>
                            <div class="line"></div>
                        </div>
                    </div>
                    <div class="card_info">
                        <div class="card_info_i">
                            <div class="count">
                                <div class="c_icon">
                                    <img src="../../assets/images/plus.svg" alt="">
                                </div>
                            </div>
                            <div class="c_title">Добавить подкатегорию</div>
                            <div class="line"></div>
                        </div>
                    </div>
                </div>
                <div class="c_table_i">
                    <div class="podcat_block">
                        <div class="podcat_block_t">Подкатегории</div>
                        <div class="podcat_line">Уборка и помощь по хозяйству</div>
                        <div class="podcat_line">Разработка ПО</div>
                    </div>
                    <div class="podcat_block">
                        <div class="podcat_block_t">Специализации</div>
                        <div class="podcat_line">Красота и здоровье</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                        <div class="podcat_line">Репетиторы и обучение</div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>
import AddSpecial from '../../components/Modals/AddSpecial.vue';
import AddPodcategory from '../../components/Modals/AddPodcategory.vue';



export default {
    name: '',
    components: { AddSpecial, AddPodcategory }
}
</script>

<style scoped lang="scss">

.courier_page {
    font-family: 'Lato', sans-serif;
    padding-top: 2rem;
    width: calc(100vw - 250px);
    overflow: auto;
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

.c_table {
    height: auto;
    background: #FFFFFF;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.25);
    border-radius: 20px 20px 0 0;
    margin-top: 2rem;
    padding-bottom: 1rem;

    .c_table_i {
        height: auto;
        // overflow: auto;
        margin-top: 5rem;

        .podcat_block {
            width: 1100px;
            margin-right: auto;
            margin-left: auto;
            margin-bottom: 2rem;

            .podcat_block_t {
                font-weight: 400;
                font-size: 22px;
                color: #FFA200;
                padding-left: 2rem;
                margin-bottom: 1rem;
            }

            .podcat_line {
                width: 100%;
                background-color: #FFFFFF;
                height: 61px;
                box-shadow: 0px 0px 4px rgba(0, 0, 0, 0.25);
                border-radius: 20px;
                display: flex;
                justify-content: flex-start;
                align-items: center;
                font-size: 16px;
                color: black;
                font-weight: 400;
                padding-left: 2rem;
                margin-bottom: 1rem;
            }
        }
    }

    .cards_info {
        padding-top: 3rem;
        display: flex;
        justify-content: flex-start;
        gap: 40px;
        margin-left: 2rem;
    }

    .card_info {
        width: 260px;
        height: 151px;
        background: #FFFFFF;
        border-radius: 20px;
        display: flex;
        justify-content: center;
        align-items: center;
        box-shadow: 0px 0px 4px rgba(0, 0, 0, 0.25);

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
}
</style>