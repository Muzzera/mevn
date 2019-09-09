<template>
    <div class="jumbotron custom-bg-dark">
        <h1 class="display-4">MEVN Stack Task Manager</h1>
        <p class="lead">This is a simple TASK MANAGER built with MEVN</p>
        <hr class="my-4">
        <p>Click bellow to begin managing task for users</p>
        <router-link to="/tasks" class="btn btn-success btn-lg"> View Tasks</router-link>
        
    </div>
</template>

<script>
export default {
    name: 'HelloWorld'
}
</script>