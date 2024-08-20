<template>
  <section>
    <nav class="navbar navbar-expand-lg ">
      <div class="container-fluid">
        <button
          class="navbar-toggler"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#navbarNavAltMarkup"
          aria-controls="navbarNavAltMarkup"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="navbarNavAltMarkup">
          <div class="navbar-nav">
            <div class="color d-flex gap-5 rounded text-light px-2 py-2">
              <p class="m-0">20$</p>
              <p class="m-0">
                الطلبيات
                <span class="bg-light num rounded-circle text-center">5</span>
              </p>
            </div>
            <p class="px-2 m-0 py-2 fw-bold text-center">
              اعدادات <i class="fa-solid fa-gear bg-dark text-light rounded-circle p-2"></i>
            </p>
          </div>
        </div>
        <a class="navbar-brand fw-bold" href="#">زاتشي</a>
      </div>
    </nav>
    <hr class="text-muted">
  </section>
</template>

<script>
export default {}
</script>

<style scoped>
span {
  display: inline-block;
}
.color {
  background-color: #50a6df;
}

.num {
  color: #50a6df;
  width: 25px;
  height: 25px;
}
</style>
