<template>
  <section class="px-4">
    <div>
      <div class="d-flex justify-content-between align-items-center">
        <button class="btn rounded-5 px-3">الكل</button>
        <h1>برجر</h1>
      </div>
      <div class="product mt-3 d-flex flex-wrap flex-md-nowrap gap-4 justify-content-center">
        <div class="card mx-2" v-for="i in 10" :key="i">
          <img
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRPSeTcovk3SJiHmv81v78chwKW4j1LbGnf9A&s"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title text-end">برجر وسط</h5>
            <p class="card-text">وصف وصف وصف وصف وصف وصف وصف وصف وصف وصف وصف وصف وصف وصف وصف وصف</p>
          </div>
        </div>
      </div>
    </div>
    <div class="mb-5 mt-3">
      <div class="d-flex justify-content-between align-items-center">
        <button class="btn rounded-5 px-3">الكل</button>
        <h1>سلطات</h1>
      </div>
      <div class="product mt-3 d-flex flex-wrap flex-md-nowrap gap-4">
        <div class="card mx-2" v-for="i in 10" :key="i">
          <img
            src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcS7VOyVzUTFqdUjl3TT3B3TarWnx5kw3nAqqdE3MG4GgqxQwnOljhqrot96aEycdKVHfTc&usqp=CAU"
            class="card-img-top"
            alt="..."
          />
          <div class="card-body">
            <h5 class="card-title text-end">سلطه وسط</h5>
            <p class="card-text">وصف وصف وصف وصف وصف وصف وصف وصف وصف وصف وصف وصف وصف وصف وصف وصف</p>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
div.product {
  overflow-x: scroll;
}

div.product .card {
  flex: 0 0 auto;
  width: 18rem !important;
  display: inline-block;
  text-align: center;
  white-space: normal;
}

button {
  color: #50a6df;

  font-weight: bold;
  background-color: #c4e8fa !important;
}
section {
  background-color: #ecf6fb !important;
}
</style>
