<template>
    <div>
        <div class="title">
            <h3 class="yun-h3">计数器 Counter</h3>
            <p>YunUI提供统一的计数器，可以使用在计算数值的场景</p>
        </div>
        <div class="content form">
            <div class="row clearContentPadding">
                <y-form>
                    <y-counter label="计数器"></y-counter>
                </y-form>
            </div>
            <div class="row clearContentPadding">
                <y-form>
                    <y-counter label="计数器" supplement= "(极值为3)" :min="0" :max="3"></y-counter>
                </y-form>
            </div>
             <div class="row clearContentPadding">
                <y-form>
                    <y-counter label="计数器" supplement= "(禁选)" disabled></y-counter>
                </y-form>
            </div>
        </div>
    </div>
</template>

<script>
    export default {
        name: 'y-counter-demo',
        props: {},
        created () {
            console.log('counter demo loaded')
        },
        methods: {}
    }

</script>

<style lang="less">

</style>
