<template>
    <div class="main">


        <div class="left">left part</div>
        <div class="right">right part</div>
    </div>
</template>

<script>
export default {
  name: 'View',
  props: {
    msg: String
  }
}
</script>

<style scoped>

    .main {
        display: flex;
        justify-content: space-between;
        background: red;
        align-items: center;
        height: 250px;
    }
</style>