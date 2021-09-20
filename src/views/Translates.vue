<template>
  <div>
    <div class="text-center">
      <h2 class="mt-4">Переклади причин</h2>
      <hr />
    </div>
    <div>
      <v-select :options="options"></v-select>
      <v-select class="mt-3" :options="options"></v-select>
    </div>
  </div>
</template>

<script>
export default {
    data: () => ({
    options: ["foo", "bar", "baz", 'led', 'lwo'],
  }),
};
</script>

<style>
</style>