<template>
  <div id="app" class="small-container">
    <h1>Employees</h1>

    <employee-table/>
    <a href="https://www.taniarascia.com/getting-started-with-vue/">Tutorial link</a>
  </div>
</template>

<script>
import EmployeeTable from './components/EmployeeTable.vue'

export default {
  name: 'app',
  components: {
    EmployeeTable
  }
}
</script>

<style>
  button {
    background: #009435;
    border: 1px solid #009435;
  }

  .small-container {
    max-width: 680px;
  }
</style>
