<template>
  <!-- Page Wrapper -->
  <div class="page-wrapper">
    <div class="content container-fluid">
      <breadcrumb :title="title" :text="text" path="/dashboard" />
      <div class="row">
        <div class="col-sm-12">
          <div class="card">
            <div class="card-body card-buttons">
              <div class="row">
                <div class="col-xl-6">
                  <h4 class="header-title">Images shapes</h4>
                  <p>
                    Add classes to an <code>&lt;img&gt;</code> element to easily style
                    images in any project.
                  </p>

                  <div class="row">
                    <div class="col-sm-4">
                      <img
                        src="@/assets/img/img-4.jpg"
                        alt="image"
                        class="img-fluid rounded"
                        width="200"
                      />
                      <p class="mb-0">
                        <code>.rounded</code>
                      </p>
                    </div>

                    <div class="col-sm-4 text-center">
                      <img
                        src="@/assets/img/user-6.jpg"
                        alt="image"
                        class="img-fluid rounded-circle"
                        width="120"
                      />
                      <p class="mb-0">
                        <code>.rounded-circle</code>
                      </p>
                    </div>

                    <div class="col-sm-4">
                      <img
                        src="@/assets/img/img-1.jpg"
                        alt="image"
                        class="img-fluid img-thumbnail"
                        width="200"
                      />
                      <p class="mb-0">
                        <code>.img-thumbnail</code>
                      </p>
                    </div>
                  </div>
                </div>
                <!-- end col-->
              </div>
            </div>
          </div>
        </div>
      </div>

      <div class="row">
        <div class="col-sm-12">
          <div class="card">
            <div class="card-body card-buttons">
              <div class="row">
                <div class="col-xl-6 mt-3 mt-xl-0">
                  <h4 class="header-title">Image sizes</h4>
                  <p>
                    Add classes to an <code>&lt;img&gt;</code> element to easily style
                    images in any project.
                  </p>

                  <div class="row">
                    <div class="col-sm-3">
                      <img
                        src="@/assets/img/user-5.jpg"
                        alt="image"
                        class="img-fluid avatar-xs rounded"
                      />
                      <p class="mb-0">
                        <code>.avatar-xs</code>
                      </p>
                      <img
                        src="@/assets/img/user-5.jpg"
                        alt="image"
                        class="img-fluid avatar-sm rounded mt-2"
                      />
                      <p class="mb-0">
                        <code>.avatar-sm</code>
                      </p>
                    </div>

                    <div class="col-sm-3">
                      <img
                        src="@/assets/img/user-5.jpg"
                        alt="image"
                        class="img-fluid avatar-md rounded"
                      />
                      <p class="mb-0">
                        <code>.avatar-md</code>
                      </p>
                    </div>

                    <div class="col-sm-3">
                      <img
                        src="@/assets/img/user-5.jpg"
                        alt="image"
                        class="img-fluid avatar-lg rounded"
                      />
                      <p class="mb-0">
                        <code>.avatar-lg</code>
                      </p>
                    </div>

                    <div class="col-sm-3">
                      <img
                        src="@/assets/img/user-5.jpg"
                        alt="image"
                        class="img-fluid avatar-xl rounded"
                      />
                      <p class="mb-0">
                        <code>.avatar-xl</code>
                      </p>
                    </div>
                  </div>
                </div>
                <!-- end col -->
              </div>
              <!-- end row -->
            </div>
          </div>
          <!-- end card -->
        </div>
        <!-- end col -->
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
      text: "Images",
    };
  },
};
</script>
