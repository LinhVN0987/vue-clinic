<template>
  <div class="page-wrapper">
    <div class="content">
      <div class="row">
        <div class="col-sm-7 col-6">
          <ul class="breadcrumb">
            <li class="breadcrumb-item">
              <router-link to="dashboard">Dashboard </router-link>
            </li>
            <li class="breadcrumb-item"><i class="feather-chevron-right"></i></li>
            <li class="breadcrumb-item active">My Profile</li>
          </ul>
        </div>

        <div class="col-sm-5 col-6 text-end m-b-30">
          <router-link to="edit-profile" class="btn btn-primary btn-rounded"
            ><i class="fa fa-plus"></i> Edit Profile</router-link
          >
        </div>
      </div>
      <div class="card-box profile-header">
        <div class="row">
          <div class="col-md-12">
            <div class="profile-view">
              <div class="profile-img-wrap">
                <div class="profile-img">
                  <a href="javascript:;"
                    ><img class="avatar" src="@/assets/img/doctor-03.jpg" alt=""
                  /></a>
                </div>
              </div>
              <div class="profile-basic">
                <div class="row">
                  <div class="col-md-5">
                    <div class="profile-info-left">
                      <h3 class="user-name m-t-0 mb-0">Cristina Groves</h3>
                      <small class="text-muted">Gynecologist</small>
                      <div class="staff-id">Employee ID : DR-0001</div>
                      <div class="staff-msg">
                        <router-link to="/chat" class="btn btn-primary"
                          >Send Message</router-link
                        >
                      </div>
                    </div>
                  </div>
                  <div class="col-md-7">
                    <ul class="personal-info">
                      <li>
                        <span class="title">Phone:</span>
                        <span class="text"><a href="">770-889-6484</a></span>
                      </li>
                      <li>
                        <span class="title">Email:</span>
                        <span class="text"
                          ><a href="">cristinagroves@example.com</a></span
                        >
                      </li>
                      <li>
                        <span class="title">Birthday:</span>
                        <span class="text">3rd March</span>
                      </li>
                      <li>
                        <span class="title">Address:</span>
                        <span class="text"
                          >714 Burwell Heights Road, Bridge City, TX, 77611</span
                        >
                      </li>
                      <li>
                        <span class="title">Gender:</span>
                        <span class="text">Female</span>
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      <div class="profile-tabs">
        <ul class="nav nav-tabs nav-tabs-bottom">
          <li class="nav-item">
            <a class="nav-link active" href="#about-cont" data-bs-toggle="tab">About</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#bottom-tab2" data-bs-toggle="tab">Profile</a>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#bottom-tab3" data-bs-toggle="tab">Messages</a>
          </li>
        </ul>

        <div class="tab-content">
          <div class="tab-pane show active" id="about-cont">
            <div class="row">
              <div class="col-md-12">
                <div class="card-box">
                  <h3 class="card-title">Education Informations</h3>
                  <div class="experience-box">
                    <ul class="experience-list">
                      <li>
                        <div class="experience-user">
                          <div class="before-circle"></div>
                        </div>
                        <div class="experience-content">
                          <div class="timeline-content">
                            <a href="#/" class="name"
                              >International College of Medical Science (UG)</a
                            >
                            <div>MBBS</div>
                            <span class="time">2001 - 2003</span>
                          </div>
                        </div>
                      </li>
                      <li>
                        <div class="experience-user">
                          <div class="before-circle"></div>
                        </div>
                        <div class="experience-content">
                          <div class="timeline-content">
                            <a href="#/" class="name"
                              >International College of Medical Science (PG)</a
                            >
                            <div>MD - Obstetrics & Gynaecology</div>
                            <span class="time">1997 - 2001</span>
                          </div>
                        </div>
                      </li>
                    </ul>
                  </div>
                </div>
                <div class="card-box">
                  <h3 class="card-title">Experience</h3>
                  <div class="experience-box">
                    <ul class="experience-list">
                      <li>
                        <div class="experience-user">
                          <div class="before-circle"></div>
                        </div>
                        <div class="experience-content">
                          <div class="timeline-content">
                            <a href="#/" class="name">Consultant Gynecologist</a>
                            <span class="time"
                              >Jan 2014 - Present (4 years 8 months)</span
                            >
                          </div>
                        </div>
                      </li>
                      <li>
                        <div class="experience-user">
                          <div class="before-circle"></div>
                        </div>
                        <div class="experience-content">
                          <div class="timeline-content">
                            <a href="#/" class="name">Consultant Gynecologist</a>
                            <span class="time">Jan 2009 - Present (6 years 1 month)</span>
                          </div>
                        </div>
                      </li>
                      <li>
                        <div class="experience-user">
                          <div class="before-circle"></div>
                        </div>
                        <div class="experience-content">
                          <div class="timeline-content">
                            <a href="#/" class="name">Consultant Gynecologist</a>
                            <span class="time"
                              >Jan 2004 - Present (5 years 2 months)</span
                            >
                          </div>
                        </div>
                      </li>
                    </ul>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <div class="tab-pane" id="bottom-tab2">Tab content 2</div>
          <div class="tab-pane" id="bottom-tab3">Tab content 3</div>
        </div>
      </div>
    </div>
  </div>
</template>
