<template>
  <header>
    <img class="logo" alt="Vue logo" src="../assets/logo.png" />
    <div>Homegate
        <Button msg="Coucou"></Button>
    </div>
  </header>
</template>

<script>
export default {
  name: "Header",
};
</script>

<style>
header {
  height: 60px;
  background: green;
  padding: 8px;
  display: grid;
  grid-template-columns: 60px auto;
  justify-items: left;
  align-items: center;
}
.logo {
  width: 50px;
}
</style>