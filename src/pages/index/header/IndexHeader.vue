<template>
    <div class="header">
        <router-link to="/search" tag="div" class="search-wrapper">
            <div class="icon-search">
                <i class="iconfont icon-16"></i>输入您需要的商品名称
            </div>
        </router-link>
    </div>
</template>

<script type="text/ecmascript-6">
export default {
    name: 'IndexHeader',
    data () {
        return {

        }
    },
    components: {

    }
}
</script>

<style scoped lang="stylus">
@import '~styles/common.styl'
    .header
        height: .9rem
        gradient()
        .search-wrapper
            padding: .15rem
            .icon-search
                height: .6rem
                line-height: .6rem
                font-size: .28rem
                color: #ccc
                text-align: left
                text-indent: .6rem
                background: #f7f7f7
                border-radius: .6rem
                .iconfont
                    margin-right: .2rem
</style>
