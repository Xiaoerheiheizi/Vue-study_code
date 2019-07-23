<template>
    <div class="hello">
        <label>
            <input type="text" v-model="msg">
        </label>
        <p>{{msg}}</p>
    </div>
</template>

<script>
export default {
    name: 'HelloWorld',
    data () {
        return {
            msg: 'Welcome to Your Vue.js App'
        }
    }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>

</style>
