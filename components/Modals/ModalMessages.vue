<template>
    <div class="modal_messages">
        <div class="modal_messages_i">
            <div class="modal_messages_inner">
                <MessageDialogs style="display: ;" />
                <div class="messanger" style="display: ;">
                    <div class="messanger_empty" style="display: none;">
                        <img src="../../assets/images/mess/big_msg.svg" alt="">
                        <div class="messanger_empty_title">Выберите, кому хотели бы написать</div>
                    </div>
                    <div class="messages" style="display: ;">
                        <div class="msg_people">
                            <img src="../../assets/images/mess/Аватар.svg" alt="">
                            <div class="msg_people_info">
                                <div class="name">Владислав S.</div>
                                <div class="date">Был 01.02.22</div>
                            </div>
                            <img class="muted" src="../../assets/images/mess/muted.svg" alt="">
                        </div>
                        <div class="msg_messanger">
                            <div class="name_date_guy">
                                <div class="name">Владислав Support Y.</div>
                                <div class="date">02.02.23, 08:04</div>
                            </div>
                            <div class="message_guy">
                                <div>Здравствуйте!</div><br>
                                Ваше задание "75576" удалено.<br>
                                К сожалению, мы не совсем поняли, что все-таки должен сделать<br>
                                исполнитель :( Пожалуйста, уточните вашу задачу и опубликуйте<br>
                                ее вновь.<br><br>
                                Если что, мы всегда рядом - пишите <span>https://youdo.com/supportchat</span> Служба<br>
                                поддержки работает каждый день с 9.00 до 21.00 по<br>
                                московскому времени.
                            </div>
                            <div class="name_date_guy">
                                <div class="name">Александр</div>
                                <div class="date">4:01</div>
                            </div>
                            <div class="message_guy">
                                Здравствуйте! Ок.
                            </div>
                        </div>
                        <div class="msg_input_send">
                            <img src="../../assets/images/mess/camera.svg" alt="">
                            <div class="msg_input_send_inp">
                                <input type="text" placeholder="Введите сообщения">
                            </div>
                        </div>
                    </div>

                </div>
            </div>
        </div>
    </div>
</template>

<script>
import MessageDialogs from './MessageDialogs.vue';

export default {
    name: "ModalMessages",
    components: { MessageDialogs }
}
</script>

<style scoped lang="scss">
.modal_messages_inner {
    display: flex;
}

.modal_messages {
    display: flex;
    justify-content: center;
    align-items: center;
    padding-top: 2rem;

    .modal_messages_i {
        width: 100%;
        height: 724px;
        background: #FFFFFF;
        border-radius: 20px 20px 0 0;
    }
}



.messanger_empty {
    width: 750px;
    height: 665px;
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;

    .messanger_empty_title {
        margin-top: 2rem;
        font-size: 16px;
        font-weight: 700;
        color: #828282;
    }
}

.messanger {
    width: 810px;
    height: 665px;
}



.msg_messanger {
    height: 560px;
    width: 100%;
    padding-left: 4.5rem;
    overflow: auto;

    .name_date_guy {
        display: flex;
        justify-content: space-between;
        align-items: center;
        width: 70%;
        margin-top: 2rem;

        .name {
            color: #2D9CDB;
            font-size: 14px;
            font-weight: 700;
        }

        .date {
            color: #828282;
            font-size: 14px;
        }
    }
}

.msg_people {
    height: 80px;
    width: 100%;
    padding-left: 4.5rem;
    padding-top: 1rem;
    display: flex;
    align-items: center;
    justify-content: flex-start;

    .muted {
        margin-left: 1rem;
    }

    .name {
        color: #000;
        font-size: 16px;
        font-weight: 700;
    }

    .date {
        color: #828282;
        font-size: 14px;
    }

    img {
        margin-right: 1rem;
    }

}

.msg_input_send {
    height: 92px;
    width: 100%;
    border-top: 1px solid #D9D9D9;
    display: flex;
    justify-content: flex-start;
    align-items: center;
    padding-left: 2rem;

    img {
        margin-right: 1rem;
    }

    .msg_input_send_inp {
        width: 590px;
        height: 40px;
        border: 1px solid #D9D9D9;
        border-radius: 5px;

        input {
            width: 100%;
            height: 100%;
            outline: 0;
            border: 0;
            padding-left: 1rem;
        }
    }
}

.message_guy {
    margin-top: 2rem;
    font-size: 14px;
    color: #22305F;

    span {
        color: #2D9CDB;
    }
}
</style>
