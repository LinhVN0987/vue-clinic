<template>
  <div class="page-wrapper">
    <div class="content">
      <!-- Page Header -->
      <breadcrumb :title="title" :text="text" path="chat" />
      <!-- /Page Header -->
      <div class="row">
        <div class="col-xl-4 d-flex">
          <div class="card chat-box-clinic">
            <div class="chat-widgets">
              <div class="chat-user-group-head d-flex align-items-center">
                <div class="img-users call-user">
                  <router-link to="/profile"
                    ><img src="@/assets/img/profiles/avatar-01.jpg" alt="img"
                  /></router-link>
                  <span class="active-users"></span>
                </div>
                <div class="chat-users user-main">
                  <div class="user-titles">
                    <h5>William Stephin</h5>
                    <div class="chat-user-time">
                      <p>Doctor</p>
                    </div>
                  </div>
                  <div class="drop-item chat-menu user-dot-list">
                    <a href="javascript:;" data-bs-toggle="dropdown" aria-expanded="false" class="">
                      <i class="feather-more-vertical"></i>
                    </a>
                    <div class="dropdown-menu" style="">
                      <a class="dropdown-item" href="javascript:;"
                        ><i class="feather-user me-2 text-primary"></i> Profile</a
                      >
                      <a class="dropdown-item" href="javascript:;"
                        ><i class="feather-plus-circle me-2 text-success"></i> Archive</a
                      >
                      <a class="dropdown-item" href="javascript:;"
                        ><i class="feather-trash-2 me-2 text-danger"></i> Delete</a
                      >
                      <a class="dropdown-item" href="javascript:;"
                        ><i class="feather-slash me-2 text-secondary"></i> Block</a
                      >
                    </div>
                  </div>
                </div>
              </div>
              <div class="top-liv-search top-chat-search">
                <form>
                  <div class="chat-search">
                    <div class="input-block me-2 mb-0">
                      <input type="text" class="form-control" placeholder="Search here" />
                      <a class="btn"
                        ><img src="@/assets/img/icons/search-normal.svg" alt=""
                      /></a>
                    </div>
                    <div class="add-search">
                      <a href="javascript:;"><i class="feather-plus"></i></a>
                    </div>
                  </div>
                </form>
              </div>
              <div class="chat-user-group d-flex align-items-center">
                <div class="img-users call-user">
                  <router-link to="/profile"
                    ><img src="@/assets/img/profiles/avatar-05.jpg" alt="img"
                  /></router-link>
                  <span class="active-users bg-info"></span>
                </div>
                <div class="chat-users">
                  <div class="user-titles d-flex">
                    <h5>William Stephin</h5>
                    <div class="chat-user-time">
                      <p>10:22 AM</p>
                    </div>
                  </div>
                  <div class="user-text d-flex">
                    <p>Lorem ipsum dolor sit amet...</p>
                    <div class="chat-user-count">
                      <span>3</span>
                    </div>
                  </div>
                </div>
              </div>
              <div class="chat-user-group d-flex align-items-center">
                <div class="img-users call-user">
                  <router-link to="/profile"
                    ><img src="@/assets/img/profiles/avatar-02.jpg" alt="img"
                  /></router-link>
                  <span class="active-users"></span>
                </div>
                <div class="chat-users">
                  <div class="user-titles d-flex">
                    <h5>Mark Hay Smith</h5>
                    <div class="chat-user-time">
                      <p>2hrs ago</p>
                    </div>
                  </div>
                  <div class="user-text d-flex">
                    <p>Lorem ipsum dolor sit amet...</p>
                  </div>
                </div>
              </div>
              <div class="chat-user-group d-flex align-items-center">
                <div class="img-users call-user">
                  <router-link to="/profile"
                    ><img src="@/assets/img/profiles/avatar-03.jpg" alt="img"
                  /></router-link>
                  <span class="active-users"></span>
                </div>
                <div class="chat-users">
                  <div class="user-titles d-flex">
                    <h5>William Stephin</h5>
                    <div class="chat-user-time">
                      <p>11:35 AM</p>
                    </div>
                  </div>
                  <div class="user-text d-flex">
                    <p>Lorem ipsum dolor sit amet...</p>
                    <div class="chat-user-count">
                      <span>4</span>
                    </div>
                  </div>
                </div>
              </div>
              <div class="chat-user-group d-flex align-items-center">
                <div class="img-users call-user">
                  <router-link to="/profile"
                    ><img src="@/assets/img/profiles/avatar-04.jpg" alt="img"
                  /></router-link>
                  <span class="active-users bg-info"></span>
                </div>
                <div class="chat-users">
                  <div class="user-titles d-flex">
                    <h5>Bernardo James</h5>
                    <div class="chat-user-time">
                      <p>11:35 AM</p>
                    </div>
                  </div>
                  <div class="user-text d-flex">
                    <p>Lorem ipsum dolor sit amet...</p>
                  </div>
                </div>
              </div>
              <div class="chat-user-group d-flex align-items-center">
                <div class="img-users call-user">
                  <router-link to="/profile"
                    ><img src="@/assets/img/profiles/avatar-05.jpg" alt="img"
                  /></router-link>
                  <span class="active-users"></span>
                </div>
                <div class="chat-users">
                  <div class="user-titles d-flex">
                    <h5>Harald Kowalski</h5>
                    <div class="chat-user-time">
                      <p>11:35 AM</p>
                    </div>
                  </div>
                  <div class="user-text d-flex">
                    <p>Lorem ipsum dolor sit amet...</p>
                    <div class="chat-user-count">
                      <span>5</span>
                    </div>
                  </div>
                </div>
              </div>
              <div class="chat-user-group d-flex align-items-center">
                <div class="img-users call-user">
                  <router-link to="/profile"
                    ><img src="@/assets/img/profiles/avatar-06.jpg" alt="img"
                  /></router-link>
                  <span class="active-users bg-info"></span>
                </div>
                <div class="chat-users">
                  <div class="user-titles d-flex">
                    <h5>Alexandr Donnelly</h5>
                    <div class="chat-user-time">
                      <p>11:35 AM</p>
                    </div>
                  </div>
                  <div class="user-text d-flex">
                    <p>Lorem ipsum dolor sit amet...</p>
                    <div class="chat-user-count">
                      <span>3</span>
                    </div>
                  </div>
                </div>
              </div>
              <div class="chat-user-group d-flex align-items-center">
                <div class="img-users call-user">
                  <router-link to="/profile"
                    ><img src="@/assets/img/profiles/avatar-07.jpg" alt="img"
                  /></router-link>
                  <span class="active-users"></span>
                </div>
                <div class="chat-users">
                  <div class="user-titles d-flex">
                    <h5>Regina Dickerson</h5>
                    <div class="chat-user-time">
                      <p>11:35 AM</p>
                    </div>
                  </div>
                  <div class="user-text d-flex">
                    <p>Lorem ipsum dolor sit amet...</p>
                  </div>
                </div>
              </div>
              <div class="chat-user-group mb-0 d-flex align-items-center">
                <div class="img-users call-user">
                  <router-link to="/profile"
                    ><img src="@/assets/img/profiles/avatar-08.jpg" alt="img"
                  /></router-link>
                  <span class="active-users bg-info"></span>
                </div>
                <div class="chat-users">
                  <div class="user-titles d-flex">
                    <h5>Forest Kroch</h5>
                    <div class="chat-user-time">
                      <p>11:35 AM</p>
                    </div>
                  </div>
                  <div class="user-text d-flex">
                    <p>Lorem ipsum dolor sit amet...</p>
                    <div class="chat-user-count">
                      <span>3</span>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
        <div class="col-xl-8">
          <div class="card chat-box">
            <div class="chat-search-group">
              <div class="chat-user-group mb-0 d-flex align-items-center">
                <div class="img-users call-user">
                  <router-link to="/profile"
                    ><img src="@/assets/img/profiles/avatar-05.jpg" alt="img"
                  /></router-link>
                  <span class="active-users bg-info"></span>
                </div>
                <div class="chat-users">
                  <div class="user-titles">
                    <h5>Forest Kroch</h5>
                  </div>
                  <div class="user-text">
                    <p>Lorem ipsum dolor sit amet...</p>
                  </div>
                </div>
              </div>
              <div class="chat-search-list">
                <ul>
                  <li>
                    <router-link to="/call/video-call"
                      ><img src="@/assets/img/icons/chat-icon-01.svg" alt="img"
                    /></router-link>
                  </li>
                  <li>
                    <router-link to="/call/voice-call"
                      ><img src="@/assets/img/icons/chat-icon-02.svg" alt="img"
                    /></router-link>
                  </li>
                  <li>
                    <a href="javascript:;"
                      ><img src="@/assets/img/icons/chat-icon-03.svg" alt="img"
                    /></a>
                  </li>
                </ul>
              </div>
            </div>
          </div>
          <!-- Chat -->
          <div class="card chat-message-box">
            <div class="card-body p-0">
              <div class="chat-body">
                <ul class="list-unstyled chat-message">
                  <li class="media d-flex received">
                    <div class="avatar flex-shrink-0">
                      <img
                        src="@/assets/img/profiles/avatar-01.jpg"
                        alt="User Image"
                        class="avatar-img rounded-circle"
                      />
                    </div>
                    <div class="media-body flex-grow-1">
                      <div class="msg-box">
                        <div class="message-sub-box">
                          <h4>Williams Bruk</h4>
                          <p>
                            How likely are you to recommend our company to your friends
                            and family ?
                          </p>
                          <span>06:00 PM, 30 Sep 2022</span>
                        </div>
                      </div>
                    </div>
                  </li>
                  <li class="media d-flex sent">
                    <div class="media-body flex-grow-1">
                      <div class="msg-box">
                        <div class="message-sub-box">
                          <p>
                            How likely are you to recommend our company to your friends
                            and family ?
                          </p>
                          <span>06:00 PM, 30 Sep 2022</span>
                        </div>
                      </div>
                    </div>
                  </li>
                  <li class="media d-flex received">
                    <div class="avatar flex-shrink-0">
                      <img
                        src="@/assets/img/profiles/avatar-03.jpg"
                        alt="User Image"
                        class="avatar-img rounded-circle"
                      />
                    </div>
                    <div class="media-body flex-grow-1">
                      <div class="msg-box">
                        <div class="message-sub-box">
                          <h4>Galaviz Lalema</h4>
                          <p>non tellus dignissim</p>
                          <ul class="msg-sub-list">
                            <li>
                              <img
                                src="@/assets/img/icons/chat-icon-04.svg"
                                alt=""
                                class="me-1"
                              />Explainer Video.avi<span class="ms-1">30.0 MB</span
                              ><img
                                src="@/assets/img/icons/chat-icon-07.svg"
                                alt=""
                                class="ms-1 ms-auto"
                              />
                            </li>
                            <li>
                              <img
                                src="@/assets/img/icons/chat-icon-05.svg"
                                alt=""
                                class="me-1"
                              />Ayush Therapy.mp3<span class="ms-1">4.0 MB</span
                              ><img
                                src="@/assets/img/icons/chat-icon-08.svg"
                                alt=""
                                class="ms-1 ms-auto"
                              />
                            </li>
                            <li>
                              <img
                                src="@/assets/img/icons/chat-icon-06.svg"
                                alt=""
                                class="me-1"
                              />The liver.img<span class="ms-1">520KB</span>
                            </li>
                          </ul>
                          <span>06:32 PM Yesterday</span>
                        </div>
                      </div>
                    </div>
                  </li>
                  <li class="media d-flex sent">
                    <div class="media-body flex-grow-1">
                      <div class="msg-box">
                        <div class="message-sub-box">
                          <p>Vivamus sed dictum dictum ligula, cursus blandit risus</p>
                          <p class="mb-0">Vivamus sed dictum</p>
                          <span>06:50PM Today</span>
                        </div>
                      </div>
                    </div>
                  </li>
                  <li class="media d-flex received">
                    <div class="avatar flex-shrink-0">
                      <img
                        src="@/assets/img/profiles/avatar-01.jpg"
                        alt="User Image"
                        class="avatar-img rounded-circle"
                      />
                    </div>
                    <div class="media-body flex-grow-1">
                      <div class="msg-box">
                        <div class="message-sub-box">
                          <h4>William Stephin</h4>
                          <p>aliquam ut a ex</p>
                          <span>5min Ago</span>
                        </div>
                      </div>
                    </div>
                  </li>
                </ul>
              </div>
              <div class="chat-footer-box">
                <div class="discussion-sent">
                  <div class="row gx-2">
                    <div class="col-lg-12">
                      <div class="footer-discussion">
                        <div class="inputgroups">
                          <input type="text" placeholder="Type your Message here..." />
                          <div class="micro-text position-icon">
                            <img src="@/assets/img/icons/chat-foot-icon-04.svg" alt="" />
                          </div>
                          <div class="send-chat position-icon comman-flex">
                            <a href="javascript:;"
                              ><img src="@/assets/img/icons/chat-foot-icon-03.svg" alt=""
                            /></a>
                          </div>
                          <div class="symple-text position-icon">
                            <ul>
                              <li>
                                <a href="javascript:;"
                                  ><img
                                    src="@/assets/img/icons/chat-foot-icon-01.svg"
                                    class="me-2"
                                    alt=""
                                /></a>
                              </li>
                              <li>
                                <a href="javascript:;"
                                  ><img
                                    src="@/assets/img/icons/chat-foot-icon-02.svg"
                                    alt=""
                                /></a>
                              </li>
                            </ul>
                          </div>
                        </div>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- /Chat -->
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      title: "App",
      text: "Chat",
    };
  },
};
</script>
