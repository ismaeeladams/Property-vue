<template>
  <div class="card">
    <h2>{{ property.title }}</h2>
    <p><i class="fa-solid fa-ruler"></i>{{ property.size }}</p>
    <p><i class="fa-solid fa-bed"></i>{{ property.bedrooms }}</p>
    <p>{{ property.product }}</p>
    <p>{{ property.location }}</p>
    <p><i class="fa-solid fa-shower"></i>{{ property.bathrooms }}</p>
    <p><i class="fa-solid fa-car"></i>{{ property.parking }}</p>
    <p>{{ property.price }}</p>
  </div>
</template>
<script>
export default {
  props: ["property"],
};
</script>
<style>
.card {
  border: solid;
}
</style>
