<template>
    <section id="intro">
        <div class="intro__inner">
            <h2 class="intro__title">port developer</h2>
            <div class="intro__lines" aria-hidden="true">
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
            </div>
            <div class="intro__text">
                <div class="text">
                    <div>talent is</div>
                    <div>found at the end of the</div>
                    <div>effort</div>
                </div>
                <div class="img">
                    <img src="https://images.unsplash.com/photo-1621523379741-0db8b7c11ac2?q=80&w=1887&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D" alt="">
                </div>
            </div>
            <div class="intro__lines" aria-hidden="true">
                <!-- <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span>
                <span class="line"></span> -->
            </div>
        </div>
    </section>
</template>

<style lang="scss" scoped>
#intro {
    height: 100vh;

    .intro__inner {
        width: 100%;
        height: 100%;
        display: flex;
        align-items: flex-start;
        justify-content: flex-end;
        flex-direction: column;
        padding: 16px;
        .intro__title {
            font-size: 10vw;
            line-height: 1;
            font-weight: 800;
            white-space: nowrap;
            text-transform: uppercase;
            letter-spacing: -0.3vw;


        }

        .intro__lines {
            width: 100%;

            .line {
                display: block;
                width: 100%;
                height: 1px;
                background-color: var(--black);
                margin-bottom: 0.5vw;

                &:nth-child(1){
                    height: 1px;
                    background-color: #3f3a38;
                }

                &:nth-child(2){
                    height: 3px;
                    background-color: #3f3a38;
                }
                &:nth-child(3){
                    height: 5px;
                    background-color: #3f3a38;
                }
                &:nth-child(4){
                    height: 10px;
                    background-color: #3f3a38;
                }
                &:nth-child(5){
                    height: 13px;
                    background-color: #3f3a38;
                }
                &:nth-child(6){
                    height: 17px;
                    background-color: #3f3a38;
                }
                &:nth-child(7){
                    height: 26px;
                    background-color: #3f3a38;
                }
            }
        }

        .intro__text {
            width: 100%;
            height: 60vh;
            background-color: #3f3a38;
            color: var(--white);
            align-items: center;
            justify-content: center;
            display: flex;
            position: relative;

            .text {
                font-size: 3vw;
                line-height: 1;
                font-weight: 900;
                text-transform: uppercase;
                text-decoration: underline;
                text-align: center;
                position: relative;
                z-index: 100;
                transition: all 0.3s;
                cursor: all-scroll;
            }

            .img {
                position: absolute;
                left: 50%;
                top: 50%;
                transform: translate(-50%, -50%);
                width: 30vh;
                height: 30vh;
                border-radius: 50%;
                overflow:hidden;

                transition: all 0.3s;
            }
        }
    }
}

</style>