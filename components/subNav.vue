<template>
     <div class="home-view">
        <ul class="quick-nav">
            <li>
                <router-link :to="{name: 'MovieView'}">影院热映</router-link>
            </li>
            <li>
                <router-link :to="{name: 'StatusView'}">欧美新碟榜</router-link>
            </li>
            <li>
                <router-link :to="{name: 'RegisterView'}">注册帐号</router-link>
            </li>
            <li>
                <router-link :to="{name: ''}">退出登录</router-link>
            </li>
        </ul>
    </div>    
</template>
<script>
    
</script>
<style lang="scss" scoped>
    .home-view {
        margin-top: 4.8rem;
        padding: 0 1.8rem;

        .quick-nav {
            overflow: hidden;
            padding-top: 1.8rem;

             li {
                width: 50%;
                float: left;
                box-sizing: border-box;
                font-size: 1.6rem;
                border-radius: 5px;
                padding: .3rem;
            }

            a {
                display: block;
                background: #f6f6f6;
                padding: 1.2rem 0;
                text-align: center;
                color: #494949;
                border-radius: 5px;
            }
        }
    }

</style>
