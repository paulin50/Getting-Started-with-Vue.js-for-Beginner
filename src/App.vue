<template>
  <div class="container mt-3">
    <div class="grid">
      <div class="row">
        <div class="col">
          <p class="h3 text-success fw-bold">App Component</p>
          <p class="fw-bold">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Saepe dolor commodi eligendi! Labore laborum, molestiae eaque odio in accusantium atque impedit tempora distinctio esse blanditiis eligendi numquam repellat, dignissimos nemo.</p>
        </div>
      </div>
    </div>

    <Customer name="Paulin" age="35" designation="Software Engineer"/>
    <Employee/>

  </div>
</template>

<script>
  import Customer from "@/components/Customer";
  import Employee from "@/components/Employee.vue"
  export default {
    components: { Customer, Employee }
  };
</script>

<style scoped>
  @import "./styles.css";
</style>