<template>
    <div class="modal_moder">
        <div class="modal_i">
            <div class="close">
                <img src="../../assets/images/close.svg" alt="">
            </div>
            <div class="modal_title">Добавить подкатегорию</div>
            <div class="add_inputs">
                <input type="text" placeholder="Название категории (Например строительство)">
                <input type="text" placeholder="Стоимость отклика">
                <input type="text" placeholder="Стоимость отклика за обмен контактами">
                <input type="text" placeholder="Родительская категория">
            </div>
            <div class="moder_btns">
                <div class="moder_btn">Добавить</div>
            </div>
        </div>
    </div>
</template>

<script>
export default {
    name: 'AddPodcategory'
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
    background-color: rgba(0, 0, 0, .4);
    z-index: 20;
    transition: .3s all;
    font-family: 'Lato', sans-serif;
}

.modal_i {
    width: 800px;
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
    font-weight: 400;
    margin-bottom: 2rem;
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
        cursor: pointer;
    }
}

.add_inputs {
    margin-top: 3rem;
    margin-bottom: 3rem;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    gap: 50px;

    input {
        width: 670px;
        height: 50px;
        background: #FFFFFF;
        border: 1px solid #828282;
        border-radius: 40px;
        padding-left: 1.5rem;
        margin-right: auto;
        margin-left: auto;
        font-size: 16px;
        color: black;
        font-family: 'Lato', sans-serif;
    }
    input::placeholder{
        color: #828282;
    }

}
</style>