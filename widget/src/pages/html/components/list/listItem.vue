<template>
    <div style="background:#fff;">
        <div class="list-item">
            <p class="item-title">发现发现</p>
            <p class="item-address">
                <svg class="icon" aria-hidden="true">
                    <use xlink:href="#icon-dizhi"></use>
                </svg>
                <span>广州市</span></p>
            <p class="item-date">
                <svg class="icon" aria-hidden="true">
                    <use xlink:href="#icon-rili"></use>
                </svg>
                <span>2018-12-25</span></p>
        </div>
    </div>
</template>

<script>
    export default {
        props: {
            item: {
                type: Object,
                default: {}
            },
            lastChild: {
                type: Boolean,
                default: false
            }
        },
        data() {
            return {
            }
        },
        created() {
        },
        methods: {
        }
    }
</script>
<style>
.list-item{
    /* height:60px; */
    padding:5px 0;
    margin: 0 15px;
    border-bottom:1px solid #eee;
}
.list-item .item-title{
    font-size:14px;
    display:block;
    padding-bottom:3px;
}
.list-item .item-address, .list-item .item-date{
    font-size:12px;
    color:#8a8a8a;
    display:block;
    display:flex;
    align-items: center;
    /* justify-content: center; */
}
.list-item .icon{
    font-size:16px !important;
    margin-right:5px;
}
.item-date .icon{
    font-size:12px !important;
}
</style>