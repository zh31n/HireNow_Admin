<template>
    <div class="header" style="width: calc(100vw - 250px);">
        <div class="container">
            <div class="header_i">
                <div class="search_inp">
                    <input type="text" name="" id="" placeholder="Напишите что хотите найти">
                    <img src="../assets/images/search_ic.svg" alt="">
                </div>
                <div class="info_btn">
                    <div class="balance">
                        Баланс:<span>55 274 $</span>
                    </div>
                    <img src="../assets/images/profile icon.svg" alt="">
                </div>
            </div>
        </div>
    </div>
</template>
<script>
export default {
    name: 'TheHeader'
}
</script>

<style scoped lang="scss">
.header {
    width: 100%;
    height: 85px;
    display: flex;
    justify-content: center;
    align-items: center;

    .header_i {
        display: flex;
        justify-content: space-between;
        align-items: center;

        .search_inp {
            width: 330px;
            height: 46px;
            background: #FFFFFF;
            border: 1px solid #DDE2E8;
            border-radius: 30px;
            display: flex;
            align-items: center;
            justify-content: flex-start;
            gap: 5px;
            font-family: 'Lato', sans-serif;

            input {
                width: 90%;
                padding-left: 1rem;
            }

            input::placeholder {
                color: black;
                font-size: 14px;
            }
        }

        .info_btn {
            display: flex;
            justify-content: flex-start;
            gap: 40px;
            align-items: center;
            .balance {
                color: black;
                font-weight: 500;
                font-size: 18px;
                span{
                    color: #FFA200;
                    margin-left: 1rem;
                }
            }

        }

    }
}</style>