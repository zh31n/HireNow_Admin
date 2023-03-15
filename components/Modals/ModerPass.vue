<template>
    <div class="modal_moder">
        <div class="modal_i">
            <div class="close">
                <img src="../../assets/images/close.svg" alt="">
            </div>
            <img class="pass" src="../../assets/images/pasport.svg" alt="">
        </div>
    </div>
</template>

<script>
export default {
    name: 'ModerPass'
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
    height: 816px;
    margin-bottom: 2rem;
}

.close {
    display: flex;
    justify-content: flex-end;
}

.pass {
    filter: drop-shadow(0px 0px 10px rgba(0, 0, 0, 0.25));
    border-radius: 20px;
    outline: 10px solid #FFA200;
    outline-offset: -15px;
}
</style>