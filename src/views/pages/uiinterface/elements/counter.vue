<template>
  <!-- Page Wrapper -->
  <div class="page-wrapper">
    <div class="content container-fluid">
      <breadcrumb :title="title" :text="text" path="/dashboard" />
      <div class="row">
        <!-- Counter -->
        <div class="col-md-4">
          <div class="card">
            <div class="card-body card-buttons">
              <h5 class="card-title">Clients</h5>
              <vue3-autocounter
                class="counter"
                ref="counter"
                :startAmount="1000"
                :delay="3"
                :endAmount="3000"
                :duration="5"
                separator=","
                :autoinit="true"
              />
            </div>
          </div>
        </div>
        <!-- /Counter -->

        <!-- Counter -->
        <div class="col-md-4">
          <div class="card">
            <div class="card-body card-buttons">
              <h5 class="card-title">Total Sales</h5>
              <vue3-autocounter
                class="counter"
                ref="counter"
                :startAmount="3000"
                :delay="3"
                :endAmount="10000"
                :duration="5"
                separator=","
                :autoinit="true"
              />
            </div>
          </div>
        </div>
        <!-- /Counter -->

        <!-- Counter -->
        <div class="col-md-4">
          <div class="card">
            <div class="card-body card-buttons">
              <h5 class="card-title">Total Projects</h5>
              <vue3-autocounter
                class="counter"
                ref="counter"
                :startAmount="5000"
                :delay="3"
                :endAmount="15000"
                :duration="5"
                separator=","
                :autoinit="true"
              />
            </div>
          </div>
        </div>
        <!-- /Counter -->

        <!-- Counter -->
        <div class="col-md-4">
          <div class="card">
            <div class="card-header">
              <h5 class="card-title">Count Down</h5>
            </div>
            <div class="card-body card-buttons">
              <h6 class="card-text">Time Count from 3</h6>
              <vue3-autocounter
                ref="counter"
                :startAmount="1"
                :endAmount="3"
                :duration="50"
                prefix="00 Days 00 : "
                decimalSeparator=" : "
                :decimals="2"
                :autoinit="true"
              />
            </div>
          </div>
        </div>
        <!-- /Counter -->

        <!-- Counter -->
        <div class="col-md-4">
          <div class="card">
            <div class="card-header">
              <h5 class="card-title">Count Up</h5>
            </div>
            <div class="card-body card-buttons">
              <h6 class="card-text">Time Counting From 0</h6>
              <vue3-autocounter
                ref="counter"
                :startAmount="0"
                :endAmount="3"
                :duration="100"
                prefix="00 Days 00 : "
                decimalSeparator=" : "
                :decimals="2"
                :autoinit="true"
              />
            </div>
          </div>
        </div>
        <!-- /Counter -->

        <!-- Counter -->
        <div class="col-md-4">
          <div class="card">
            <div class="card-header">
              <h5 class="card-title">Count Inbetween</h5>
            </div>
            <div class="card-body card-buttons">
              <h6 class="card-text">Time counting from 30 to 20</h6>
              <vue3-autocounter
                ref="counter"
                :startAmount="30"
                :endAmount="20"
                :duration="1000"
                prefix="00 Days 00 : "
                decimalSeparator=" : "
                :decimals="2"
                :autoinit="true"
              />
            </div>
          </div>
        </div>
        <!-- /Counter -->

        <!-- Counter -->
        <div class="col-md-4">
          <div class="card">
            <div class="card-header">
              <h5 class="card-title">Count Callback</h5>
            </div>
            <div class="card-body card-buttons">
              <h6 class="card-text">Count from 10 to 0 and calls timer end callback</h6>
              <vue3-autocounter
                ref="counter"
                :startAmount="0"
                :endAmount="3"
                :duration="100"
                prefix="00 Days 00 : "
                decimalSeparator=" : "
                :decimals="2"
                :autoinit="true"
              />
            </div>
          </div>
        </div>
        <!-- /Counter -->

        <!-- Counter -->
        <div class="col-md-4">
          <div class="card">
            <div class="card-header">
              <h5 class="card-title">Custom Output</h5>
            </div>
            <div class="card-body card-buttons">
              <h6 class="card-text">Changed output pattern</h6>
              <vue3-autocounter
                ref="counter"
                :startAmount="10"
                :endAmount="60"
                :duration="2000"
                prefix="02 Days 23 Hour : "
                decimalSeparator=" : "
                :decimals="2"
                :autoinit="true"
              />
            </div>
          </div>
        </div>
        <!-- /Counter -->
      </div>
    </div>
  </div>
  <!-- /Page Wrapper -->
</template>
<script>
export default {
  data() {
    return {
      title: "Dashboard",
      text: "Counter",
    };
  },
  components: {},
  methods: {},
  mounted() {},
  name: "counter",
};
</script>
