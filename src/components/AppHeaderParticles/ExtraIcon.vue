<template>
    <div class="container-extra-icon">
            <div class="extra-icon">
                <div class="white-box">
                    <i class="fa-solid fa-compact-disc fa-xl icon" style="color: #4f4f4f;"></i>
                    <p>Demos</p>
                </div>
            </div>
            <div class="extra-icon">
                <div class="white-box">
                    <div class="text-extra-icon">
                        <h6>$</h6>
                        <h3>39</h3>
                    </div>
                    <p>On Sale</p>
                </div>
            </div>
        </div>
</template>


<script>
export default {
    name: 'ExtraIcon',
}
</script>


<style lang="scss" scoped>
    .container-extra-icon{
        position: absolute;
        right: 1px;
        top: 130px;
        width: 70px;
        height: 120px;
    }

    .extra-icon{
        width: 100%;
        height: 60px;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    .white-box{
        width: 65%;
        height: 75%;
        background-color: white;
        border-radius: 10%;
        display: flex;
        flex-direction: column;
        align-items: center;
        justify-content: center;
    }

    .icon{
        width: 100%;
        height: 70%;
        display: flex;
        align-items: center;
        justify-content: center;
    }

    p{
        font-size: x-small;
        height: 30%;
        width: 100%;
        display: flex;
        justify-content: center;
        align-items: end;
        padding-bottom: .2rem;
    }

    .text-extra-icon{
        display: flex;
        width: 100%;
        height: 100%;
        justify-content: center;
        font-size: 18px;
        color: #65BC7B;
        padding-top: .4rem;
    }
</style>