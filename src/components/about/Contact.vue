<template>
    <div class="card text-dark bg-light mb-3">
        <div class="card-header">联系我们</div>
        <div class="card-body">
            <div class="card-title">联系我们</div>
            <div class="card-text">1373004321@qq.com</div>

            <router-link :to="{name:'phoneNumber'}">电话</router-link>
            <router-link :to="{name:'personName'}">联系人</router-link>

            <router-view></router-view>
        </div>
    </div>
</template>
