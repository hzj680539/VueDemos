##VueJs 基本指令
###1.v-model
    <h2>{{message}}</h2>
    <input type="text" v-model="message">
###2.v-if,v-show,v-else
    <h1 v-if="yes">show yes</h1>
    <h1 v-else>show no</h1>
    <h1 v-show="name.indexOf('ace') > 0">included</h1>
    <h1 v-else>Not included</h1>
    Note:v-if 不再渲染该元素，v-show 渲染该元素并置display:none;
###3.v-for
    <li v-for="item in object">{{item}}</li>
    Note:object 可以是整数，数据，json数据
####4.v-bind
    <div bind:class="active">Item</div>
    Note: bind可以省略，可以写成<div :class="active">Item</div>
###5.v-on
    <div on:click="saySth">Click Me!</div>
    Note: on可以用@代替，可以写成<div @click="saySth">Click Me!</div>












