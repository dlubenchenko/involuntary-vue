<template>
  <div>
    <div class="text-center">
      <h2 class="mt-4">Переклади причин</h2>
      <hr />
    </div>
    <div class="row">
      <div class="col-lg-6 col-md mt-2">
        <v-select :options="options"></v-select>
      </div>
      <div class="col-lg-6 col-md mt-2">
        <v-select :options="options"></v-select>
      </div>
    </div>
    <div class="row mt-2">
      <div class="col">
        <hr />
        <p class="output text-center">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Alias,
          distinctio?
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data: () => ({
    options: ["foo", "bar", "baz", "led", "lwo"],
  }),
};
</script>

<style>
</style>