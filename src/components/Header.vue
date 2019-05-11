<template>
    <header>
        <div class="container">
            <div class="slide">
                <!-- <img src="../assets/img/1 copy.png" alt=""> -->
                
            </div>
            <div class="focus">
                <span></span>
                <span></span>
                <span></span>
            </div>
        </div>
    </header>
</template>

<style lang="scss" scoped>
    header{
        height: 420px;
        position: relative;
        .slide{
            height: 420px;
            background-color: #049DB4;
            img{
                display: block;
                width: 100%;
                height: 420px;
            }
        }
        .focus{
            position: absolute;
            left:50%;
            transform: translate(-50%);
            bottom:20px;
            span{
                display: inline-block;
                width: 40px;
                height: 6px;
                background-color: #fff;
                border-radius: 3px;
                margin-right:15px;

                &.active{
                    background:rgba(255,255,255,1);
                    opacity: 0.5;
                }
            }
        }
    }
</style>

<script>
export default {
    name:"top"
}
</script>
