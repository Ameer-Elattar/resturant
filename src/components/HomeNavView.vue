<template>
  <section class="d-flex justify-content-between pb-3 px-3 shadow border-bottom">
    <input
      class="form-control form-control-lg w-25 rounded-5 bg-body-tertiary"
      type="text"
      placeholder="البحث..."
      aria-label=".form-control-lg example"
    />
    <ul class="nav nav-pills justify-content-end">
      <li class="nav-item">
        <a class="nav-link" aria-current="page" href="#">اضافات</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" aria-current="page" href="#">مشروبات</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" aria-current="page" href="#">تورتيا</a>
      </li>
      <li class="nav-item">
        <a class="nav-link" aria-current="page" href="#">سلطات</a>
      </li>
      <li class="nav-item">
        <a class="nav-link active rounded-5" aria-current="page" href="#">برجر</a>
      </li>
    </ul>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
input::placeholder {
  text-align: end;
}
a {
  color: black;
  font-weight: bold;
}
.active {
  color: #2498e6 !important;
  background-color: #ecf6fb !important;
}
</style>
