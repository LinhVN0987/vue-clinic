<template>
  <!-- Page Wrapper -->
  <div class="page-wrapper">
    <div class="content container-fluid">
      <breadcrumb :title="title" :text="text" path="/dashboard" />
      <!-- Dropdowns -->
      <div class="card bg-white">
        <div class="card-body card-buttons">
          <h5 class="card-title">Dropdowns within Text</h5>
          <div class="dropdown">
            <a
              class="dropdown-toggle"
              href="javascript:;"
              role="button"
              data-bs-toggle="dropdown"
              aria-expanded="false"
            >
              Dropdown
            </a>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="javascript:;">Action</a>
              <a class="dropdown-item" href="javascript:;">Another action</a>
            </div>
          </div>
          <hr />
          <h5 class="card-title">Dropdowns within Buttons</h5>
          <div class="btn-group">
            <button
              type="button"
              class="btn btn-primary dropdown-toggle me-1"
              data-bs-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Action
            </button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="javascript:;">Action</a>
              <a class="dropdown-item" href="javascript:;">Another action</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="javascript:;">Separated link</a>
            </div>
          </div>
          <div class="btn-group">
            <button
              type="button"
              class="btn btn-secondary dropdown-toggle me-1"
              data-bs-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Action
            </button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="javascript:;">Action</a>
              <a class="dropdown-item" href="javascript:;">Another action</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="javascript:;">Separated link</a>
            </div>
          </div>
          <div class="btn-group">
            <button
              type="button"
              class="btn btn-info dropdown-toggle me-1"
              data-bs-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Action
            </button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="javascript:;">Action</a>
              <a class="dropdown-item" href="javascript:;">Another action</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="javascript:;">Separated link</a>
            </div>
          </div>
          <div class="btn-group">
            <button
              type="button"
              class="btn btn-success dropdown-toggle me-1"
              data-bs-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Action
            </button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="javascript:;">Action</a>
              <a class="dropdown-item" href="javascript:;">Another action</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="javascript:;">Separated link</a>
            </div>
          </div>
          <div class="btn-group">
            <button
              type="button"
              class="btn btn-warning dropdown-toggle me-1"
              data-bs-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Action
            </button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="javascript:;">Action</a>
              <a class="dropdown-item" href="javascript:;">Another action</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="javascript:;">Separated link</a>
            </div>
          </div>
          <div class="btn-group">
            <button
              type="button"
              class="btn btn-danger dropdown-toggle"
              data-bs-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Action
            </button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="javascript:;">Action</a>
              <a class="dropdown-item" href="javascript:;">Another action</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="javascript:;">Separated link</a>
            </div>
          </div>
          <hr />
          <h5 class="card-title">Split button dropdowns</h5>
          <div class="btn-group">
            <button type="button" class="btn btn-primary">Action</button>
            <button
              type="button"
              class="btn btn-primary dropdown-toggle dropdown-toggle-split me-1"
              data-bs-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              <span class="sr-only">Toggle Dropdown</span>
            </button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="javascript:;">Action</a>
              <a class="dropdown-item" href="javascript:;">Another action</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="javascript:;">Separated link</a>
            </div>
          </div>
          <div class="btn-group">
            <button type="button" class="btn btn-secondary">Action</button>
            <button
              type="button"
              class="btn btn-secondary dropdown-toggle dropdown-toggle-split me-1"
              data-bs-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              <span class="sr-only">Toggle Dropdown</span>
            </button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="javascript:;">Action</a>
              <a class="dropdown-item" href="javascript:;">Another action</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="javascript:;">Separated link</a>
            </div>
          </div>
          <div class="btn-group">
            <button type="button" class="btn btn-info">Action</button>
            <button
              type="button"
              class="btn btn-info dropdown-toggle dropdown-toggle-split me-1"
              data-bs-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              <span class="sr-only">Toggle Dropdown</span>
            </button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="javascript:;">Action</a>
              <a class="dropdown-item" href="javascript:;">Another action</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="javascript:;">Separated link</a>
            </div>
          </div>
          <div class="btn-group">
            <button type="button" class="btn btn-success">Action</button>
            <button
              type="button"
              class="btn btn-success dropdown-toggle dropdown-toggle-split me-1"
              data-bs-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              <span class="sr-only">Toggle Dropdown</span>
            </button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="javascript:;">Action</a>
              <a class="dropdown-item" href="javascript:;">Another action</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="javascript:;">Separated link</a>
            </div>
          </div>
          <div class="btn-group">
            <button type="button" class="btn btn-warning">Action</button>
            <button
              type="button"
              class="btn btn-warning dropdown-toggle dropdown-toggle-split me-1"
              data-bs-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              <span class="sr-only">Toggle Dropdown</span>
            </button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="javascript:;">Action</a>
              <a class="dropdown-item" href="javascript:;">Another action</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="javascript:;">Separated link</a>
            </div>
          </div>
          <div class="btn-group">
            <button type="button" class="btn btn-danger">Action</button>
            <button
              type="button"
              class="btn btn-danger dropdown-toggle dropdown-toggle-split"
              data-bs-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              <span class="sr-only">Toggle Dropdown</span>
            </button>
            <div class="dropdown-menu">
              <a class="dropdown-item" href="javascript:;">Action</a>
              <a class="dropdown-item" href="javascript:;">Another action</a>
              <div class="dropdown-divider"></div>
              <a class="dropdown-item" href="javascript:;">Separated link</a>
            </div>
          </div>
        </div>
      </div>
      <!-- /Dropdowns -->
    </div>
  </div>
  <!-- /Page Wrapper -->
</template>
<script>
export default {
  data() {
    return {
      title: "Dashboard",
      text: "Dropdowns",
    };
  },
};
</script>
