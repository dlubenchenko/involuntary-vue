<template>
  <div>
    <div class="text-center">
      <h2 class="mt-4">Повернення</h2>
      <hr />
    </div>
    <div class="container">
      <div class="row">
        <div class="col-md-3">
          <div class="text-center pt-5">
            <div
              class="btn-group-vertical"
              role="group"
              aria-label="Basic example"
            >
              <my-button
                v-for="(item, i) of refundButtons"
                :key="i"
                :item="item"
                @buttonValue="refundHandler"
              />
            </div>
          </div>
        </div>
        <div class="col-md mt-3">
          <my-text-area />
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import MyTextArea from "../components/UI/MyTextArea.vue";
import MyButton from "../components/UI/MyButton.vue";
export default {
  components: { MyTextArea, MyButton },
  data: () => ({
    refundButtons: ["Full refund", "Partial refund"],
  }),
  methods: {
    refundHandler(e) {
      console.log(e);
    },
  },
};
</script>

<style>
</style>