<script setup>

</script>

<template>
  <div class="container">
    <header>
      <h1 class="p-5 bg-light text-center mt-4 rounded">Calculadora Aritmética</h1>
    </header>
    <form>
      <div class="row pt-4">
        <div class="col">
          <input type="number" placeholder="Digite um número" class="p-2 rounded-3 form-control">
        </div>
        <div class="col-md-1">
          <select class="form-control text-center">
            <option value="soma">+</option>
            <option value="subtracao">-</option>
            <option value="divisao">*</option>
            <option value="multiplicacao">/</option>
          </select>
        </div>
        <div class="col">
          <input type="number" placeholder="Digite um número" class="p-2 rounded-3 form-control">
        </div>
      </div>
    </form>
    <div class="row pt-4 justify-content-center">
      <p class="text-center fs-3">Solução</p>
      <div class="col-4 text-center border p-3 rounded">
        19 + 20 = 39
      </div>
    </div>
  </div>
</template>

<style scoped>

</style>
