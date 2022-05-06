<template>
    <div>
       <div v-for="(item,id) in currenttask"  class="row">
       <li style="list-style: none">
        <input type="checkbox" @click="strike(item,id)" >{{item}}</li>
       <button @click="changeitem(item,id)">edit</button>
       <button @click="deleteitem(item,id)">delete</button>
       </div>
    </div>
</template>

<script>
    export default {
        name:comp2
    }
</script>

<style lang="scss" scoped>

</style>