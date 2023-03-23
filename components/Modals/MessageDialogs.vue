<template>
    <div class="dialogs">
        <div class="input_d">
            <input type="text" name="" id="" placeholder="Введите имя для общения">
        </div>
        <div class="msg_items">
            <div class="msg_item active">
                <img src="../../assets/images/mess/Аватар.svg" alt="">
                <div class="msg_item_txt">
                    <span class="name">Владислав S.</span><br>
                    <span>Был 01.02.22</span>
                </div>
                <img class="trash" style="display: none;" src="../../assets/images/mess/trash.svg" alt="">
                <div class="bl_o" style="display: none;">2</div>
            </div>
            <div class="msg_item">
                <img src="../../assets/images/mess/Аватар.svg" alt="">
                <div class="msg_item_txt">
                    <span class="name">Владислав S.</span><br>
                    <span>Был 01.02.22</span>
                </div>
                <img class="trash" src="../../assets/images/mess/trash.svg" alt="">
                <div class="bl_o">2</div>
            </div>
            <div class="msg_item">
                <img src="../../assets/images/mess/Аватар.svg" alt="">
                <div class="msg_item_txt">
                    <span class="name">Владислав S.</span><br>
                    <span>Был 01.02.22</span>
                </div>
                <img class="trash" style="display: block;" src="../../assets/images/mess/trash.svg" alt="">
                <div class="bl_o" style="display: none;">2</div>
            </div> 
            <div class="msg_item">
                <img src="../../assets/images/mess/Аватар.svg" alt="">
                <div class="msg_item_txt">
                    <span class="name">Владислав S.</span><br>
                    <span>Был 01.02.22</span>
                </div>
                <img class="trash" src="../../assets/images/mess/trash.svg" alt="">
                <div class="bl_o" style="display: none;">2</div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'MessageDialogs'
}
</script>

<style scoped lang="scss">
.dialogs {
    width: 350px;
    height: 724px;
    border-right: 1px solid #D9D9D9;
    padding-top: 2rem;
    transition: all .3s;
    // position: relative;
    // bottom: 10px;

    .input_d {
        width: 90%;
        height: 40px;
        background: #FFFFFF;
        border: 1px solid #D9D9D9;
        border-radius: 5px;
        margin-right: auto;
        margin-left: auto;
        margin-bottom: 1rem;

        input {
            width: 100%;
            height: 100%;
            border: 0;
            outline: 0;
            padding-left: 1rem;
        }

        input::placeholder {
            color: #828282;
            font-weight: 400;
            font-size: 14px;
        }
    }
}

.bl_o {
    margin-left: 40%;
    background-color: #6FC727;
    display: flex;
    justify-content: center;
    align-items: center;
    border-radius: 50px;
    color: white;
    width: 30px;
    height: 30px;
    font-size: 16px;
    font-weight: 700;
}

.msg_item.active {
    background-color: #D9D9D9;

    .trash {
        margin-left: 42%;
        display: block;
        cursor: pointer;
    }
}

.msg_item:hover {
    // background-color: #D9D9D9;
    transition: all .3s;

    .trash {
        margin-left: 42%;
        display: block;
    }

    .bl_o {
        display: none;
    }
}

.msg_item {
    display: flex;
    justify-content: flex-start;
    align-items: center;
    padding-top: 1rem;
    padding-bottom: 1rem;
    border-bottom: 1px solid #D9D9D9;
    // cursor: pointer;
    transition: all .3s;
    position: relative;
    z-index: 100;

    img {
        margin-left: 1rem;
    }

    .trash {
        margin-left: 42%;
        display: none;
    }

    .msg_item_txt {
        margin-left: 1rem;

        .name {
            font-size: 14px;
            font-weight: 700;
            color: black;
        }

        span {
            font-size: 12px;
            color: #828282;
        }
    }
}

@media (max-width: 1281px) {
    .bl_o{
        margin-left: 25%;
    }
    .msg_item{
        .trash{
            margin-left: 26% !important;
        }
    }
}
</style>