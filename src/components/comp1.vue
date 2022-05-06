<template>
    <div>
        <input  v-model="task"  >
        <button v-on:click="addtask(task)" v-show="isadd">add task</button>
        <button  v-show="isedit" @click="touch(indexToUpdate)" >update</button>
    </div>
</template>

<script>
    export default {
        name:comp1
    }
</script>

<style lang="scss" scoped>

</style>