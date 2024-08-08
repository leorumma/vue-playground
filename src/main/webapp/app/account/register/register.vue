<template>
  <div class="container mt-5">
    <div class="row">
      <div class="col-12 mb-4">
        <h1 class="text-center">Minha Aplicação Vue</h1>
      </div>
      <div class="col-12 mb-4">
        <h2 class="text-center">Componente Hello World</h2>
        <div class="d-flex justify-content-center">
          <hello-world />
        </div>
      </div>
      <div class="col-12 mb-4">
        <h2 class="text-center">Componente Hello World 2</h2>
        <div class="d-flex justify-content-center">
          <hello-world2 />
        </div>
      </div>
      <div class="col-12 mb-4">
        <h2 class="text-center">Componente Counter</h2>
        <div class="d-flex justify-content-center">
          <Counter />
        </div>
      </div>
      <div class="col-12 mb-4">
        <h2 class="text-center">Componente Form</h2>
        <div class="d-flex justify-content-center">
          <Form />
        </div>
      </div>
    </div>
  </div>
</template>

<script lang="ts" src="./register.component.ts"></script>
