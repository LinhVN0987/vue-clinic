<template>
  <div class="col-lg-4">
    <div class="doctor-personals-grp">
      <div class="card">
        <div class="card-body">
          <div class="heading-detail">
            <h4 class="mb-3">About me</h4>
            <p>
              Hello I am Dr. Bruce Willis a Gynaecologist in Sanjivni Hospital Surat. I
              love to work with all my hospital staff and seniour doctors.
            </p>
          </div>
          <div class="about-me-list">
            <ul class="list-space">
              <li>
                <h4>Gender</h4>
                <span>Female</span>
              </li>
              <li>
                <h4>Operation Done</h4>
                <span>30+</span>
              </li>
              <li>
                <h4>Designation</h4>
                <span>Sr. Doctor</span>
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
                <h5>Operations</h5>
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
                <h5>Patient Care</h5>
                <p>85%</p>
              </div>
              <div class="progress mb-0">
                <div
                  class="progress-bar bg-statistics"
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
                <h5>Endoscopic</h5>
                <p>65%</p>
              </div>
              <div class="progress mb-0">
                <div
                  class="progress-bar bg-endoscopic"
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
                <h5>Patient Visit</h5>
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
    <div class="doctor-personals-grp">
      <div class="card">
        <div class="card-body">
          <div class="heading-detail">
            <h4>Speciality</h4>
          </div>
          <div class="personal-activity">
            <div class="personal-icons status-grey">
              <img src="@/assets/img/icons/medal-01.svg" alt="" />
            </div>
            <div class="views-personal">
              <h4>Proffesionals</h4>
              <h5>Certified Skin Treatment</h5>
            </div>
          </div>
          <div class="personal-activity">
            <div class="personal-icons status-green">
              <img src="@/assets/img/icons/medal-02.svg" alt="" />
            </div>
            <div class="views-personal">
              <h4>Certified</h4>
              <h5>Cold Laser Operation</h5>
            </div>
          </div>
          <div class="personal-activity mb-0">
            <div class="personal-icons status-orange">
              <img src="@/assets/img/icons/medal-03.svg" alt="" />
            </div>
            <div class="views-personal">
              <h4>Medication Laser</h4>
              <h5>Hair Lose Product</h5>
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
                <router-link to="doctor-profile" class="active"
                  ><span class="set-about-icon me-2"
                    ><img src="@/assets/img/icons/menu-icon-02.svg" alt="" /></span
                  >About me</router-link
                >
              </li>
              <li>
                <router-link to="doctor-setting"
                  ><span class="set-about-icon me-2"
                    ><img src="@/assets/img/icons/menu-icon-16.svg" alt="" /></span
                  >Settings</router-link
                >
              </li>
            </ul>
          </div>
          <div class="personal-list-out">
            <div class="row">
              <div class="col-xl-3 col-md-6">
                <div class="detail-personal">
                  <h2>Full Name</h2>
                  <h3>Dr.Bruce Willis</h3>
                </div>
              </div>
              <div class="col-xl-3 col-md-6">
                <div class="detail-personal">
                  <h2>Mobile</h2>
                  <h3>264-625-2583</h3>
                </div>
              </div>
              <div class="col-xl-3 col-md-6">
                <div class="detail-personal">
                  <h2>Email</h2>
                  <h3>bruce@email.com</h3>
                </div>
              </div>
              <div class="col-xl-3 col-md-6">
                <div class="detail-personal">
                  <h2>Location</h2>
                  <h3>Los Angeles</h3>
                </div>
              </div>
            </div>
          </div>
          <div class="hello-park">
            <p>
              Completed my graduation in Gynaecologist Medicine from the well known and
              renowned institution of India – SARDAR PATEL MEDICAL COLLEGE, BARODA in
              2000-01, which was affiliated to M.S. University. I ranker in University
              exams from the same university from 1996-01.
            </p>
            <p>
              Worked as Professor and Head of the department ; Community medicine
              Department at Sterline Hospital, Rajkot, Gujarat from 2003-2015
            </p>
          </div>
          <div class="hello-park mb-2">
            <h5>Education</h5>
            <div class="table-responsive">
              <table class="table mb-0 border-0 custom-table profile-table">
                <thead>
                  <th>Year</th>
                  <th>Degree</th>
                  <th>Institute</th>
                  <th>Result</th>
                </thead>
                <tbody>
                  <tr v-for="item in Doctor_about" :key="item.id">
                    <td>{{ item.Year }}</td>
                    <td>{{ item.Degree }}</td>
                    <td>{{ item.Institute }}</td>
                    <td>
                      <button class="custom-badge status-green">{{ item.Result }}</button>
                    </td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>
          <div class="hello-park mb-2">
            <h5>Experience</h5>
            <div class="table-responsive">
              <table class="table mb-0 border-0 custom-table profile-table">
                <thead>
                  <th>Year</th>
                  <th>Position</th>
                  <th>Hospital</th>
                  <th>Feedback</th>
                </thead>
                <tbody>
                  <tr>
                    <td>2002-2005</td>
                    <td>Senior doctor</td>
                    <td>Midtown Medical Clinic</td>
                    <td>
                      <button class="custom-badge status-orange">Good</button>
                    </td>
                  </tr>
                  <tr>
                    <td>2005-2014</td>
                    <td>Associate Prof.</td>
                    <td>Netherland Medical College</td>
                    <td>
                      <button class="custom-badge status-green">Excellence</button>
                    </td>
                  </tr>
                </tbody>
              </table>
            </div>
          </div>
          <div class="hello-park">
            <h5>Conferences, Cources & Workshop Attended</h5>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod
              tempor incididunt ut labore et dolore magna aliqua.
            </p>
            <p>
              Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia
              deserunt mollit anim id est laborum.
            </p>
            <p>
              Sed ut perspiciatis unde omnis iste natus error sit voluptatem accusantium
              doloremque laudantium, totam rem aperiam
            </p>
            <p class="mb-0">
              Ut enim ad minima veniam, quis nostrum exercitationem ullam corporis
              suscipit laboriosam, nisi ut aliquid ex ea commodi consequatur? Quis autem
              vel eum iure reprehenderit qui in ea voluptate velit esse quam nihil
              molestiae consequatur
            </p>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
import Doctor_about from "@/assets/json/doctor-about.json";
export default {
  data() {
    return {
      Doctor_about,
    };
  },
};
</script>
