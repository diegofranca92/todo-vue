<template>
  <div id="app">
   <div class="container grid-xs py-2 text-center">
      <img alt="Vue logo" src="@/assets/logo.png">
      <form>
        <div class="input-group">
          <input type="text" class="form-input" placeholder="Nova tarefa">
          <button class="btn btn-primary input-group-btn">Adicionar</button>
        </div>
      </form>
   </div>
  </div>
</template>

<script>

export default {
  name: 'App',
  components: {
  }
}
</script>

<style>
img {
  max-width: 150px;
  margin: 0 auto;
}
</style>
