<template>
  <div class="row">
    <div class="col-lg-4">
      <div class="doctor-personals-grp">
        <div class="card">
          <div class="card-body">
            <div class="heading-detail">
              <h4 class="mb-3">About me</h4>
              <p>
                Hello I am Smith Bruklin a Gynaecologist in Sanjivni Hospital Surat. I
                love to work with all my hospital staff and seniour doctors.
              </p>
            </div>
            <div class="about-me-list">
              <ul class="list-space">
                <li>
                  <h4>Gender</h4>
                  <span>Male</span>
                </li>
                <li>
                  <h4>Operation Done</h4>
                  <span>30+</span>
                </li>
                <li>
                  <h4>Designation</h4>
                  <span>Engineer</span>
                </li>
              </ul>
            </div>
          </div>
        </div>
      </div>
      <div class="doctor-personals-grp">
        <div class="card">
          <div class="card-body">
            <div class="heading-detail">
              <h4>Skills:</h4>
            </div>
            <div class="skill-blk">
              <div class="skill-statistics">
                <div class="skills-head">
                  <h5>Heart Beat</h5>
                  <p>45%</p>
                </div>
                <div class="progress mb-0">
                  <div
                    class="progress-bar bg-operations"
                    role="progressbar"
                    style="width: 45%"
                    aria-valuenow="45"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
              <div class="skill-statistics">
                <div class="skills-head">
                  <h5>Haemoglobin</h5>
                  <p>85%</p>
                </div>
                <div class="progress mb-0">
                  <div
                    class="progress-bar bg-haemoglobin"
                    role="progressbar"
                    style="width: 85%"
                    aria-valuenow="85"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
              <div class="skill-statistics">
                <div class="skills-head">
                  <h5>Blood Pressure</h5>
                  <p>65%</p>
                </div>
                <div class="progress mb-0">
                  <div
                    class="progress-bar bg-statistics"
                    role="progressbar"
                    style="width: 65%"
                    aria-valuenow="65"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
              <div class="skill-statistics">
                <div class="skills-head">
                  <h5>Sugar</h5>
                  <p>90%</p>
                </div>
                <div class="progress mb-0">
                  <div
                    class="progress-bar bg-visit"
                    role="progressbar"
                    style="width: 90%"
                    aria-valuenow="90"
                    aria-valuemin="0"
                    aria-valuemax="100"
                  ></div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="col-lg-8">
      <div class="doctor-personals-grp">
        <div class="card">
          <div class="card-body">
            <div class="tab-content-set">
              <ul class="nav">
                <li>
                  <router-link to="patient-profile"
                    ><span class="set-about-icon me-2"
                      ><img src="@/assets/img/icons/menu-icon-02.svg" alt="" /></span
                    >About me</router-link
                  >
                </li>
                <li>
                  <router-link to="patient-setting" class="active"
                    ><span class="set-about-icon me-2"
                      ><img src="@/assets/img/icons/menu-icon-16.svg" alt="" /></span
                    >Settings</router-link
                  >
                </li>
              </ul>
            </div>
            <div class="setting-form-blk">
              <form>
                <div class="row">
                  <div class="col-12">
                    <div class="form-heading">
                      <h4>Account Setting</h4>
                    </div>
                  </div>
                  <div class="col-12 col-sm-12">
                    <div class="input-block local-forms">
                      <label>Username </label>
                      <input class="form-control" type="text" value="smith@29" />
                    </div>
                  </div>
                  <div class="col-12 col-sm-12">
                    <div class="input-block local-forms">
                      <label>Mobile </label>
                      <input class="form-control" type="text" value="+1 43 456890" />
                    </div>
                  </div>
                  <div class="col-12 col-sm-12">
                    <div class="input-block local-forms">
                      <label>Email </label>
                      <input
                        class="form-control"
                        type="email"
                        value="smithbruklin@info.com"
                      />
                    </div>
                  </div>
                  <div class="col-12 col-sm-12">
                    <div class="input-block local-forms">
                      <label>Address <span class="login-danger">*</span></label>
                      <textarea class="form-control" rows="3" cols="30">
101, Elanxa Apartments, 340 N Madison Avenue</textarea
                      >
                    </div>
                  </div>
                </div>
                <div class="col-12">
                  <div class="form-heading">
                    <h4>Security Setting</h4>
                  </div>
                </div>
                <div class="col-12 col-sm-12">
                  <div class="input-block local-forms">
                    <label>Current Password </label>
                    <input class="form-control" type="password" value="12345" />
                  </div>
                </div>
                <div class="col-12 col-sm-12">
                  <div class="input-block local-forms">
                    <label>New Password </label>
                    <input class="form-control" type="password" placeholder="" />
                  </div>
                </div>
                <div class="col-12 col-sm-12">
                  <div class="input-block local-forms">
                    <label>Confirm Password </label>
                    <input class="form-control" type="password" placeholder="" />
                  </div>
                </div>
                <div class="col-12 col-sm-12">
                  <div class="profile-check-blk input-block">
                    <div class="remember-me">
                      <label class="custom_check mr-2 mb-0 d-inline-flex remember-me">
                        Profile Visibility For Everyone
                        <input type="checkbox" name="radio" checked />
                        <span class="checkmark"></span>
                      </label>
                    </div>
                    <div class="remember-me">
                      <label class="custom_check mr-2 mb-0 d-inline-flex remember-me">
                        New task notifications
                        <input type="checkbox" name="radio" checked />
                        <span class="checkmark"></span>
                      </label>
                    </div>
                    <div class="remember-me">
                      <label class="custom_check mr-2 mb-0 d-inline-flex remember-me">
                        New friend request notifications
                        <input type="checkbox" name="radio" />
                        <span class="checkmark"></span>
                      </label>
                    </div>
                  </div>
                </div>
                <div class="col-12">
                  <div class="doctor-submit">
                    <button type="submit" class="btn btn-primary submit-form me-2">
                      Submit
                    </button>
                    <button type="submit" class="btn btn-primary cancel-form">
                      Cancel
                    </button>
                  </div>
                </div>
              </form>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
