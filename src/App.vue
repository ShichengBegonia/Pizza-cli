<template>
    <div id="app">
        <div class="container">
          <app-header></app-header>
        </div>
        <div class="container">
            <!--点击哪个组件，哪个组件就会展示到 router-view 面来-->
            <router-view></router-view>
        </div>
    </div>
</template>

<script>
import Header from './components/Header';
export default{
    name: 'app',
    components:{
        //appHeader: Header   --- 两种写法都可以
        "app-header": Header
    }
}
</script>
