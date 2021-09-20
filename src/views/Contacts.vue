<template>
  <div>
    <div class="text-center">
      <h2 class="mt-4">Котакти</h2>
      <hr />
    </div>
    <div>
      <v-select :options="options"></v-select>
    </div>
    <div class="mt-4">
      <my-collapse :options="options"/>
    </div>
  </div>
</template>

<script>
import MyCollapse from '../components/UI/MyCollapse.vue'

export default {
  components: { MyCollapse },
  data: () => ({
    options: ["foo", "bar", "baz", 'led', 'lwo'],
  }),
}
</script>

<style>
</style>