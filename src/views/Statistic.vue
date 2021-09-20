<template>
  <div>
    <div class="text-center">
      <h2 class="mt-4">Історія запитів</h2>
      <hr />
    </div>
    <div>
      <my-table :items="statistic" :btn="'Open'"/>
    </div>
  </div>
</template>

<script>
import MyTable from '../components/UI/MyTable.vue';
export default {
  components: { MyTable },
  data: ()=> ({
    statistic: [
      {'Name': 'Lubenchenko Dmytro', "System": 'Kiwi', 'Time': '17.09.21, 23:38:46', 'More': 'btn'},
      {'Name': 'Lubenchenko Dmytro', "System": 'Kiwi', 'Time': '17.09.21, 23:38:46', 'More': 'btn'},
      {'Name': 'Lubenchenko Dmytro', "System": 'Kiwi', 'Time': '17.09.21, 23:38:46', 'More': 'btn'},
      {'Name': 'Lubenchenko Dmytro', "System": 'Kiwi', 'Time': '17.09.21, 23:38:46', 'More': 'btn'},
      {'Name': 'Lubenchenko Dmytro', "System": 'Kiwi', 'Time': '17.09.21, 23:38:46', 'More': 'btn'},
      {'Name': 'Lubenchenko Dmytro', "System": 'Kiwi', 'Time': '17.09.21, 23:38:46', 'More': 'btn'},
    ]
  })
  }
</script>

<style>
</style>