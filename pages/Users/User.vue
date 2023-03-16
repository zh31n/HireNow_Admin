<template>
    <div class="executor_card">
        <div class="container">
            <div class="info_stats">
                <div class="info_page">
                    Пользователь подробнее
                </div>
                <div class="btn_back">
                    <img src="../../assets/images/Arrow_back.svg" alt="">
                    Назад к пользователям
                </div>
            </div>
            <div class="executor_card_i">
                <div class="btns_ban">
                    <div class="btn">Забанить</div>
                    <div class="btn">Удалить</div>
                </div>
                <div class="exr_info">
                    <div class="exr_info_ava">
                        <img class="avatarka_exr" src="../../assets/images/mess/person.svg" alt="">
                    </div>
                    <div class="exr_inform">
                        <div class="exr_name">Никита Белокопытов</div>
                        <div class="exr_since">
                            <div class="exr_age_city mobile">23 года, Москва</div>
                            <span>На HireNow с 3 апреля 2020</span>
                            <span class="status">Сейчас на сайте</span>
                        </div>
                        <div class="exr_age_city">23 года, Москва</div>
                        <div class="exr_veryfication">
                            <div class="exr_veryfication_i">
                                <img src="../../assets/images/mess/veryfied.svg" alt="">
                                <span>Документы подтверждены</span>
                            </div>
                            <div class="exr_veryfication_i">
                                <img src="../../assets/images/mess/iphone.svg" alt="">
                                <span>Контакты и соцсети подтверждены</span>
                            </div>
                        </div>
                        <div class="exr_awards">
                            <div class="">Получил <span>7 наград</span></div>
                            <div class="arounds_awards">
                                <div class="around_award" style="background:#2D9CDB ;"></div>
                                <div class="around_award" style="background:#2F80ED ;"></div>
                                <div class="around_award" style="background:#6FC727 ;"></div>
                                <div class="around_award" style="background:#56CCF2 ;"></div>
                                <div class="around_award" style="background:#2F80ED ;"></div>
                                <div class="around_award" style="background:#FDEAC2 ;"></div>
                                <div class="around_award" style="background:#FFA200 ;"></div>
                            </div>
                        </div>
                        <div class="exr_stats">
                            <div class="exr_stat">
                                <div class="exr_stat_title">
                                    Оценка 4,96
                                    <img src="../../assets/images/mess/Star.svg" alt="">
                                </div>
                                <div class="exr_stat_sup">
                                    на основе
                                    <span>168 отзывов</span>
                                </div>
                            </div>
                            <div class="exr_stat t_l">
                                <div class="exr_stat_title">4 года</div>
                                <div class="exr_stat_sup">опыта</div>
                            </div>
                            <div class="exr_stat">
                                <div class="exr_stat_title ">167 заданий</div>
                                <div class="exr_stat_sup">выполнил</div>
                            </div>
                            <div class="exr_stat t_l">
                                <div class="exr_stat_title">24 задания</div>
                                <div class="exr_stat_sup">создал</div>
                            </div>
                        </div>
                        <div class="exr_about">
                            <p class="exr_about_txt">
                                <span>Здравствуйте!</span>

                                Я-Web-разработчик со стажем более 3-х лет.
                                Работал<br>
                                всегда на фрилансе и знаю, что людям нужно!<br><br>
                                Моя специализация - разработка и поддержка
                                сайтов.<br><br>
                                <!-- Сделаю и простой landing page, и серьезный проект, в портфолио представлены мои выполненные
                                работы! -->
                            </p>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>
</template>

<script>


export default {
    components: {


    }
}


</script>

<style scoped lang="scss">
.executor_card_i {
    width: 100%;
    height:720px;
    background-color: white;
    border-radius: 20px 20px 0 0;
    padding-top: 2rem;
    margin-top: 2rem;
    overflow: hidden;
}
.btns_ban{
    display: flex;
    justify-content: flex-start;
    gap: 20px;
    align-items: center;
    padding-left: 2rem;
    margin-bottom: 4rem;
    .btn{
        width: 153px;
        height: 32px;
        background: #FFA200;
        border-radius: 20px;
        display: flex;
        justify-content: center;
        align-items: center;
        color: white;
        font-size: 16px;
        font-weight: 400;
        cursor: pointer;
    }
    .btn:last-child{
        background: #EB5757;
    }
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

.exr_info {
    margin-left: 3rem;
    margin-top: 2rem;
    font-size: 14px;
    font-weight: 500;
    color: #000;
    display: flex;
    margin-bottom: 2rem;

    .exr_inform {
        margin-left: 2rem;
    }

    .exr_since {
        margin-top: 0.2rem;
        margin-bottom: 0.2rem;
    }

    .exr_name {
        font-size: 28px;
        font-weight: 700;
        color: #000;
    }

    .status {
        margin-left: 2rem;
        color: #6FC727;
    }


    .exr_info_ava {
        height: 185px;
        width: 185px;
        border-radius: 50%;
        display: flex;
        justify-content: center;
        align-items: center;
    }

    .exr_info_ava::after {
        content: url(../../assets/images/mess/online.svg);
        position: relative;
        right: 3rem;
        top: 5rem;

    }

    .exr_veryfication_i {
        display: flex;
        align-items: center;
        color: #6FC727;
        margin-top: 1rem;

        img {
            margin-right: 0.5rem;
        }

        span {
            display: flex;
            align-items: center;
            line-height: normal;
        }
    }

    .avatarka_exr {
        height: 185px;
        width: 185px;
    }

    .exr_awards {
        margin-top: 2rem;
        display: flex;
        justify-content: flex-start;
        align-items: center;

        span {
            color: #2D9CDB;
            margin-left: .5rem;
        }

        .arounds_awards {
            display: flex;
            margin-left: .5rem;

            .around_award {
                width: 22px;
                height: 22px;
                border-radius: 50%;
                margin-right: 0.5rem;
            }
        }
    }
}

.exr_stats {
    margin-top: 4rem;
    display: flex;

    .exr_stat {
        margin-right: 2rem;

        .exr_stat_title {
            font-size: 18px;
            font-weight: 700;
            color: #000;
            display: flex;
            align-items: center;

            img {
                width: 20px;
                height: 20px;
                margin-left: 0.5rem;
            }
        }

        .exr_stat_sup {
            color: #828282;
            font-size: 12px;
            font-weight: 400;

            span {
                color: #2D9CDB;
            }
        }
    }
}

.exr_about {
    margin-top: 2rem;

    .exr_about_txt {
        width: 470px;
        font-size: 20px;
        color: #000;
        margin-bottom: 0;

        span {
            display: block;
            margin-bottom: 1rem;
        }
    }

    .exr_about_txt::after {
        display: inline-flex;
        content: '';
        width: 509px;
        height: 125px;
        background: linear-gradient(0deg, #FFFFFF 49.4%, rgba(255, 255, 255, 0) 261.45%);
        position: relative;
        bottom: 6rem;
    }
}

.exr_about .btn_all_about {
    width: 275px;
    height: 55px;
    background: #FFFFFF;
    border: 1px solid #D9D9D9;
    border-radius: 60px;
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: 700;
    color: #000;
    position: relative;
    bottom: 6rem;
    margin-right: auto;
    margin-left: auto;
    cursor: pointer;
}

.btn_all_about {
    width: 220px;
    height: 50px;
    background: #FFFFFF;
    border: 2px solid #D9D9D9;
    border-radius: 60px;
    color: #000;
    display: flex;
    justify-content: center;
    align-items: center;
    font-weight: 700;
    margin-right: auto;
    margin-left: auto;
    cursor: pointer;
}

.examples_job {
    display: flex;
    align-items: center;
    margin-right: auto;
    margin-left: auto;

    .example {
        font-size: 12px;
        font-weight: 400;
        text-align: center;

        .example_photo {
            width: 170px;
            height: 170px;
            background: #D9D9D9;
            border-radius: 10px;
        }

        .example_title {
            color: #000;
        }

        .example_sup {
            color: #828282;
        }
    }

    .example:nth-child(2) {
        margin-left: 1rem;
        margin-right: 1rem;
    }
}

.types_work_title {
    font-size: 22px;
    font-weight: 700;
    color: #000;
    margin-bottom: 2rem;
    margin-top: 6rem;
}

.type_work {
    display: flex;
    align-items: flex-start;
    margin-top: 1rem;
    margin-bottom: 2rem;
}

.type_work_i {
    margin-left: 1rem;

}

.type_work_i_title {
    line-height: normal;
    font-size: 16px;
    font-weight: 700;
    color: #000;
}

.type_work_i_line {
    font-size: 12px;
    color: #000;
    display: flex;
    justify-content: space-between;
    align-items: baseline;
    margin-top: 1rem;

    span {
        color: #828282;
        margin-left: 0.3rem;
    }

    .line {
        border: 1px dashed #828282;
        width: 180px;
        height: 1px;
        margin-right: 0.3rem;
    }
}

.type_work_i_line.s {
    .line {
        width: 206px;
    }
}

.type_work_i_line.t {
    margin-bottom: 1rem;

    .line {
        width: 224px;
    }
}

.check_more {
    font-size: 12px;
    font-weight: 400;
    color: #2D9CDB;
    cursor: pointer;
}

.types_work {
    margin-bottom: 3rem;
}

.exr_feedback {
    padding-top: 2rem;

    .exr_feedback_up {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 100%;
    }

    .feedbacks {
        font-size: 22px;
        font-weight: 700;
        color: #828282;
    }

    .avg_estimation {
        display: flex;
        font-size: 22px;
        font-weight: 700;
        color: #000;

        .stars {
            display: flex;
            align-items: center;
            margin-left: 1rem;

            img {
                width: 17px;
                height: 17px;
                margin-right: 0.2rem;
            }
        }
    }
}

.feedback_filters {
    display: flex;
    font-size: 14px;
    color: #828282;
    margin-top: 2rem;
    margin-bottom: 1rem;
    gap: 10px;
    align-items: center;

    .conn {
        display: flex;
        justify-content: flex-start;
        align-items: center;
        flex-wrap: wrap;
        gap: 10px;
    }
}

.fb_btn_filter {
    width: 150px;
    height: 30px;
    background-color: white;
    border: 1px solid black;
    color: #000;
    font-size: 12px;
    font-weight: 500;
    display: flex !important;
    justify-content: center !important;
    align-items: center !important;
    border-radius: 20px;
}

.fb_btn_filter.active {
    background-color: #FDEAC2;
    border: 0;
}


.feedback_items {
    margin-top: 4rem;
}

.tire_ {
    display: none;
}

.exr_since {
    .exr_age_city {
        display: none;
    }
}

.exj_titlr {
    font-size: 18px !important;
    font-weight: 700 !important;
    color: #000;
    margin-bottom: 1rem;
}

.exm_job_line {
    margin-top: 10px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    padding-bottom: 10px;
    border-bottom: 1px solid #D9D9D9;

    .ex_job_inf {
        font-size: 12px !important;

        div:first-child {
            color: #000;
        }

        div:last-child {
            color: #828282;
        }
    }

    .exm_job_line_info {
        display: flex;
        justify-content: flex-start;
        align-items: center;
        gap: 10px;

        .exm_job_img {
            width: 33px;
            height: 33px;
            background: #D9D9D9;
            border-radius: 5px;
        }
    }
}

.rotated {
    transform: rotate(270deg);
}

// Media


</style>
