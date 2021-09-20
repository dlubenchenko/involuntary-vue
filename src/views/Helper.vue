<template>
  <div>
    <div class="text-center">
      <h2 class="mt-4">Helper</h2>
      <hr />
    </div>
    <div>
      <my-table :items="commands"/>
    </div>
  </div>
</template>

<script>
import MyTable from '../components/UI/MyTable.vue';
export default {
  components: { MyTable },
  data: () => ({
    commands: [
      {'': 'Список очередей', 'AMADEUS': 'QT', 'SABRE': 'QC /', 'SIRENA': 'ОЧР', 'B2': 'QC/', 'GABRIEL': 'QT                 QTA', 'GALILEO': 'QCA'},
      {'': 'Список очередей', 'AMADEUS': 'QT', 'SABRE': 'QC /', 'SIRENA': 'ОЧР', 'B2': 'QC/', 'GABRIEL': 'QT                 QTA', 'GALILEO': 'QCA'},
      {'': 'Список очередей', 'AMADEUS': 'QT', 'SABRE': 'QC /', 'SIRENA': 'ОЧР', 'B2': 'QC/', 'GABRIEL': 'QT                 QTA', 'GALILEO': 'QCA'},
      {'': 'Список очередей', 'AMADEUS': 'QT', 'SABRE': 'QC /', 'SIRENA': 'ОЧР', 'B2': 'QC/', 'GABRIEL': 'QT                 QTA', 'GALILEO': 'QCA'},
      {'': 'Список очередей', 'AMADEUS': 'QT', 'SABRE': 'QC /', 'SIRENA': 'ОЧР', 'B2': 'QC/', 'GABRIEL': 'QT                 QTA', 'GALILEO': 'QCA'},
      {'': 'Список очередей', 'AMADEUS': 'QT', 'SABRE': 'QC /', 'SIRENA': 'ОЧР', 'B2': 'QC/', 'GABRIEL': 'QT                 QTA', 'GALILEO': 'QCA'},
      {'': 'Список очередей', 'AMADEUS': 'QT', 'SABRE': 'QC /', 'SIRENA': 'ОЧР', 'B2': 'QC/', 'GABRIEL': 'QT                 QTA', 'GALILEO': 'QCA'},
      {'': 'Список очередей', 'AMADEUS': 'QT', 'SABRE': 'QC /', 'SIRENA': 'ОЧР', 'B2': 'QC/', 'GABRIEL': 'QT                 QTA', 'GALILEO': 'QCA'},
    ]
  })
  }
</script>

<style>
</style>