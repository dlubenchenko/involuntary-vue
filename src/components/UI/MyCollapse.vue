<template>
  <div>
    <div v-for="(opt, i) of options" :key="i" class="accordion" id="accordionExample">
      <div class="card">
        <div class="card-header" :id="'heading' + i">
          <h2 class="mb-0">
            <button
              class="btn btn-link btn-block text-left"
              type="button"
              data-toggle="collapse"
              :data-target="'#' + opt"
              :aria-expanded="i === 0 ? true : false"
              :aria-controls="opt"
              active-class="collapsed"
              exact
            >
              Collapsible Group Item #{{ i + 1 }}
            </button>
          </h2>
        </div>

        <div
          :id="opt"
          :class="i === 0 ? 'collapse show' : 'collapse'"
          :aria-labelledby="'heading' + i"
          data-parent="#accordionExample"
          exact
        >
          <div class="card-body">
            {{opt}}
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
    props: ['options']
};
</script>

<style scoped>
</style>