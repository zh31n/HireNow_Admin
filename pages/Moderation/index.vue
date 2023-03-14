<template>
    <div class="stat">
        <div class="container">
            <div class="stat_i">
                <div class="page_title">Выберете категорию</div>
                <div class="cards_info">
                    <NuxtLink to="/Moderation/Photo" class="card_info">
                        <div class="card_info_i">
                            <div class="count">
                                <div class="c_icon">
                                    <img src="../../assets/images/mod_1.svg" alt="">
                                </div>
                            </div>
                            <div class="c_title">Модерация Фотографий</div>
                            <div class="line"></div>
                        </div>
                    </NuxtLink>
                    <NuxtLink to="/Moderation/Documents" class="card_info">
                        <div class="card_info_i">
                            <div class="count">
                                <div class="c_icon">
                                    <img src="../../assets/images/mod_2.svg" alt="">
                                </div>
                            </div>
                            <div class="c_title">Модерация паспартов</div>
                            <div class="line"></div>
                        </div>
                    </NuxtLink>
                </div>
            </div>
        </div>
    </div>
</template>


<style scoped lang="scss">

.page_title{
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
</style>