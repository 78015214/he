<template>
    <div class="shortcut">
        <div class="Stripe">
            <ul class="City">
                <li class="ho_ver base-li">
                    <a class="ditu" href="#">
                        <i class="tu_biao iconfont iconditu-dibiao"></i>
                        <span class="ui-areamini-text">广东</span>
                    </a>
                    <div class="dd">
                        <div class="region box2">
                            <div class="reg_ion"><a href="">北京</a></div>
                            <div class="reg_ion"><a href="">上海</a></div>
                            <div class="reg_ion"><a href="">天津</a></div>
                            <div class="reg_ion"><a href="">重庆</a></div>
                            <div class="reg_ion"><a href="">河北</a></div>
                            <div class="reg_ion"><a href="">山西</a></div>
                            <div class="reg_ion"><a href="">辽宁</a></div>
                            <div class="reg_ion"><a href="">吉林</a></div>
                            <div class="reg_ion"><a href="">黑龙江</a></div>
                            <div class="reg_ion"><a href="">河南</a></div>

                        </div>
                        <div class="areamini_inter">
                            <p class="areamini_inter_desc">地区专享版本</p>
                            <a class="aa">
                                <div class="areamini_inter_name">中國港澳</div>
                            </a>
                        </div>
                        <div></div>
                    </div>
                </li>
            </ul>
            <ul class="fr">
                <li>
                    <a class="dl" target="_blank">你好, 请登录</a>
                    <a class="link-recgit color cover" target="_blank">免费注册</a>
                </li>
                <li class="Vertical"></li>
                <li>
                    <div class="dt">
                        <a target="_blank">我的订单</a>
                    </div>
                </li>
                <li class="Vertical"></li>
                <li class="base-li hd">
                    <div class="re_f">
                        <a hretarget="_blank">我的京东</a>
                        <i class="size iconfont iconxiala1"></i>
                    </div>
                    <div class="jd">
                        <div class="wd"><a href="">待处理订单</a></div>
                        <div class="wd"><a href="">消息</a></div>
                        <div class="wd"><a href="">返回退换货</a></div>
                        <div class="wd"><a href="">我的问答</a></div>
                        <div class="wd"><a href="">商品降价</a></div>
                        <div class="wd"><a href="">我的关注</a></div>
                    </div>
                </li>
                <li class="Vertical hy"></li>
                <li>
                    <div>
                        <a target="_blank">京东会员</a>
                        <i class="size iconfont iconxiala1"></i>
                    </div>
                </li>
                <li class="Vertical hy"></li>
                <li>
                    <div>
                        <a class="cg" target="_blank">企业采购</a>
                        <i class="size iconfont iconxiala1"></i>
                    </div>
                </li>
                <li class="Vertical hy"></li>
                <li>
                    <div>
                        <a target="_blank">客户服务</a>
                        <i class="size iconfont iconxiala1"></i>
                    </div>
                </li>
                <li class="Vertical hy"></li>
                <li>
                    <div>
                        <a target="_blank">网站导航</a>
                        <i class="size iconfont iconxiala1"></i>
                    </div>
                </li>
                <li class="Vertical hy"></li>
                <li>
                    <div>
                        <a target="_blank">手机京东</a>

                    </div>
                </li>
            </ul>
        </div>
    </div>
</template>

<script>
    export default {
        name: "index"
    }
</script>

<style scoped>
    /*导航条*/
    .Stripe {
        width: 1190px;
        height: 31px;
        margin: 0 auto;
    }
    .base-li{
        z-index: 22;
        position: relative;
    }

    .ho_ver:hover .dd {
        display: block;
    }

    .ditu {
        display: block;
        height: 31px;
        padding: 0px 8px;
        border-left: 1px solid rgba(204, 204, 204, 0);
        border-right: 1px solid rgba(204, 204, 204, 0);
        position: relative;
        z-index: 22;
        text-decoration: none;
    }

    .ho_ver:hover .ditu {
        display: block;
        border-color: rgba(204, 204, 204, 1);
        background-color: #fff;
    }

    .dd {
        width: 300px;
        padding: 10px;
        background-color: #fff;
        position: absolute;
        top: 30px;
        border: 1px solid #ccc;
        display: none;
        /*clear: both;*/
    }

    .shortcut {
        background: #e3e4e5;
        height: 31px;
    }

    .City {

        line-height: 31px;
        float: left;
        margin-left: 8px;
    }

    .ui-areamini-text {
        padding-left: 4px;
        font-size: 12px;
        color: #999;
    }

    .tu_biao {
        font-size: 15px;
        color: #f10215;
        position: relative;
        top: 0px;
    }

    .dl:hover{
        color: #f10215;
        cursor: pointer;
    }

    .link-recgit {
        padding-left: 8px;
    }

    .color {
        color: #f10215;
    }

    .cover:hover {
        color: #e33333;
        cursor: pointer;

    }

    .fr {
        float: right;
        /*display: inline-block;*/
        line-height: 31px;
        margin-right: 8px;
    }

    .size {
        font-size: 16px;
        margin-left: 4px;
        position: relative;
        top: 0px;
    }

    .fr li {
        display: inline-block;
        margin-left: 12px;
        color: #7c7676;
    }

    .Vertical {
        width: 1px;
        height: 10px;
        background-color: #999999;
        /*margin-top: 20px;*/
        position: relative;
        top: 1px;
    }

    .fr .hy {
        margin-left: 0px
    }

    /*hover值*/
    .reg_ion {
        float: left;
        width: 60px;
        text-align: center;
    }

    .reg_ion a {
        text-decoration: none;
        color: #7c7676;

    }

    .reg_ion a:hover {
        color: #f10215;
        cursor: pointer;
    }

    .areamini_inter {
        color: #7c7676;
        /*width: 60px;*/
        margin-left: 18px;
    }

    .areamini_inter_name:hover {
        color: #f10215;
        cursor: pointer;
    }

    .jd{
        float: left;
        width: 282px;
        border: 1px solid #ccc;
        position: absolute;
        top: 31px;
        left: -5px;
        display: none;
    }

    .wd{
        float: left;
        /*width: 126px;*/
        box-sizing: border-box;
        width:50%;
        text-align: left;
        padding-left:20px;
        /*margin-left: 30px;*/
    }

    .wd a{
        text-decoration: none;
        color: #7c7676;
        display: block;
    }
    .re_f{
        height: 32px;
        border-left: 1px solid rgba(204, 204, 204, 0);
        border-right: 1px solid rgba(204, 204, 204, 0);
        position: relative;
        left: -5px;
        /*background-color: #fff;*/
        z-index: 22;
    }
    .re_f a {
        padding-left: 5px;
    }
    .hd:hover .re_f {
        border-color: rgba(204, 204, 204, 1);
        /*padding: 0 8px;*/
        background-color: #fff;
        cursor: pointer;
    }
    .hd:hover .jd{
        display: block;
    }
</style>