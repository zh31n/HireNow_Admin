<template>
    <div class="modal_moder">
        <div class="modal_i">
            <div class="close">
                <img src="../../assets/images/close.svg" alt="">
            </div>
            <div class="modal_title">Модерация фотографии</div>
            <div class="img_guy">
                <img src="../../assets/images/img_big.svg" alt="">
            </div>
            <div class="u_id">id: <span>23</span></div>
            <div class="moder_btns">
                <div class="moder_btn">Принять</div>
                <div class="moder_btn">Отклонить</div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'ModerPhoto'
}
</script>

<style scoped lang="scss">
.modal_moder {
    display: flex;
    justify-content: center;
    align-items: center;
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-color: rgba(0, 0, 0, .5);
    z-index: 20;
    transition: .3s all;
    font-family: 'Lato', sans-serif;
}

.modal_i {
    width: 610px;
    height: 610px;
    background: #FFFFFF;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.25);
    border-radius: 20px;
}

.close {
    display: flex;
    justify-content: flex-end;
    padding-right: 1rem;
    padding-top: 1rem;
}

.modal_title {
    text-align: center;
    font-size: 22px;
    font-weight: 700;
    margin-bottom: 2rem;
}

.img_guy {
    margin-right: auto;
    margin-left: auto;
    height: 325px;
    width: 325px;
    border-radius: 50%;
    display: flex;
    justify-content: center;
    align-items: center;
    margin-top: 1rem;
}

.u_id {
    text-align: center;
    font-size: 22px;
    font-weight: 700;
    margin-top: 1rem;
}

.moder_btns {
    margin-right: auto;
    margin-left: auto;
    margin-top: 2rem;
    display: flex;
    justify-content: center;
    align-items: center;

    .moder_btn {
        width: 227px;
        height: 49px;
        font-size: 22px;
        font-weight: 700;
        color: white;
        display: flex;
        justify-content: center;
        align-items: center;
        background: #6FC727;
        border-radius: 20px;
        margin-left: 25px;
    }
    .moder_btn:last-child{
        background-color: #EB5757;
    }
}
</style>