<template>
  <div class="page-wrapper">
    <!-- Page Content -->
    <div class="content container-fluid">
      <!-- Page Header -->
      <breadcrumb :title="title" :text="text" path="invoices-list" />
      <!-- /Page Header -->

      <div class="row mt-4">
        <div class="col-xl-3 col-md-4">
          <div class="widget settings-menu setting-list-menu">
            <ul>
              <li class="nav-item">
                <router-link to="invoices-settings" class="nav-link invoice active">
                  <i class="fa fa-cog me-2" aria-hidden="true"></i
                  ><span>General Settings</span>
                </router-link>
              </li>
              <li class="nav-item">
                <router-link to="tax-settings" class="nav-link invoice">
                  <i class="fa fa-bookmark me-2"></i> <span>Tax Settings</span>
                </router-link>
              </li>
              <li class="nav-item">
                <router-link to="bank-settings" class="nav-link invoice">
                  <i class="fas fa-university me-2"></i> <span>Bank Settings</span>
                </router-link>
              </li>
            </ul>
          </div>
        </div>

        <div class="col-xl-9 col-md-8">
          <div class="card invoices-settings-card">
            <div class="card-header px-3">
              <h5 class="card-title">General Settings</h5>
            </div>
            <div class="card-body">
              <!-- Form -->
              <form action="javascript:;" class="invoices-settings-form">
                <div class="row align-items-center input-block">
                  <label for="name" class="col-sm-3 col-form-label input-label"
                    >Invoice Status</label
                  >
                  <div class="col-sm-9">
                    <label class="custom_check">
                      <input type="checkbox" name="invoice" />
                      <span class="checkmark"></span> Change invoice status to paid after
                      an order is complete
                    </label>
                  </div>
                </div>
                <div class="row align-items-center input-block">
                  <label for="email" class="col-sm-3 col-form-label input-label"
                    >Invoice Amount</label
                  >
                  <div class="col-sm-9">
                    <input type="text" class="form-control" />
                  </div>
                </div>
                <div class="row align-items-center input-block">
                  <label for="phone" class="col-sm-3 col-form-label input-label"
                    >Invoice number starts with</label
                  >
                  <div class="col-sm-9">
                    <input type="text" class="form-control" placeholder="$" value="$" />
                  </div>
                </div>
                <div class="row align-items-center input-block">
                  <label for="addressline1" class="col-sm-3 col-form-label input-label"
                    >Prefix</label
                  >
                  <div class="col-sm-9">
                    <input type="text" class="form-control" />
                  </div>
                </div>
                <div class="row align-items-center input-block">
                  <label for="addressline2" class="col-sm-3 col-form-label input-label"
                    >Number Reset</label
                  >
                  <div class="col-sm-9">
                    <input type="text" class="form-control" />
                  </div>
                </div>
                <div class="row align-items-center input-block">
                  <label for="zipcode" class="col-sm-3 col-form-label input-label"
                    >Default Due Time</label
                  >
                  <div class="col-sm-9">
                    <input type="text" class="form-control" />
                  </div>
                </div>
                <div class="row align-items-center input-block">
                  <label for="zipcode" class="col-sm-3 col-form-label input-label"
                    >Default Digital Signatory</label
                  >
                  <div class="col-sm-9">
                    <div class="invoices-upload-btn">
                      <input
                        type="file"
                        accept="image/*"
                        name="image"
                        id="file"
                        onchange="loadFile(event)"
                        class="hide-input"
                      />
                      <label for="file" class="upload"> upload File </label>
                    </div>
                  </div>
                </div>
                <div class="row align-items-center input-block">
                  <label for="zipcode" class="col-sm-3 col-form-label input-label"
                    >Default Digital Name</label
                  >
                  <div class="col-sm-9">
                    <input type="text" class="form-control" />
                  </div>
                </div>
                <div class="invoice-setting-btn text-end">
                  <button type="submit" class="btn cancel-btn me-2">Cancel</button>
                  <button type="submit" class="btn btn-primary">Save Changes</button>
                </div>
              </form>
              <!-- /Form -->
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- /Page Content -->
  </div>
</template>
<script>
export default {
  data() {
    return {
      title: "Invoice",
      text: "Invoice Setting",
    };
  },
};
</script>
