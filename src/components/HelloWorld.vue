<template>
  <nav
    class="navbar container-fluid navv navbar-expand-lg navbar-light bg-white pl-5 col-lg-12"
  >
    <button
      class="navbar-toggler"
      type="button"
      data-toggle="collapse"
      data-target="#navbarSupportedContent"
      aria-controls="navbarSupportedContent"
      aria-expanded="false"
      aria-label="Toggle navigation"
    >
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="profile d-flex align-items-center ml-2 text-orange">
      <svg
        xmlns="http://www.w3.org/2000/svg"
        width="16"
        height="16"
        fill="currentColor"
        class="bi bi-person-circle"
        viewBox="0 0 16 16"
      >
        <path d="M11 6a3 3 0 1 1-6 0 3 3 0 0 1 6 0z" />
        <path
          fill-rule="evenodd"
          d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8zm8-7a7 7 0 0 0-5.468 11.37C3.242 11.226 4.805 10 8 10s4.757 1.225 5.468 2.37A7 7 0 0 0 8 1z"
        />
      </svg>
    </div>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul
        class="navbar-nav mr-lg-2 ml-lg-5 home-served d-flex align-items-center"
      >
        <li class="active">
          <a class="nav-link" href="#">Home</a>
        </li>
        <div class="line">
          <svg xmlns="http://www.w3.org/2000/svg" width="1" height="20">
            <line
              x1="0"
              y1="0"
              x2="0"
              y2="100"
              stroke="black"
              stroke-width="2"
            />
          </svg>
        </div>
        <li class="nav-item">
          <a class="nav-link font-weight-bold text-dark mr-0" href="#"
            >Served</a
          >
        </li>
      </ul>
      <div
        class="update-info py-2 bg-light col-md-4 col-sm-12 mr-auto col-sm-auto mr-lg-5"
      >
        Data last updated at 9:15 am 25 June 2023
      </div>
      <form
        class="form-inline my-2 my-lg-0 col-3.5 p-lg-0 d-flex justify-content-start"
      >
        <input
          class="form-control mr-sm-0"
          type="search"
          placeholder="Search"
          aria-label="Search"
        />
        <button
          class="btn search-btn btn-outline-success my-2 my-sm-0"
          type="submit"
        >
          <svg
            xmlns="http://www.w3.org/2000/svg"
            width="16"
            height="16"
            fill="currentColor"
            class="bi bi-search"
            viewBox="0 0 16 16"
          >
            <path
              d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"
            />
          </svg>
        </button>
      </form>
      <ul class="navbar-nav home-served">
        <li class="nav-item">
          <div
            class="help d-flex align-items-center ml-3 m-sm-0 m-md-1 justify-content-between"
          >
            <svg
              xmlns="http://www.w3.org/2000/svg"
              width="16"
              height="16"
              fill="currentColor"
              class="bi bi-question-circle"
              viewBox="0 0 16 16"
            >
              <path
                d="M8 15A7 7 0 1 1 8 1a7 7 0 0 1 0 14zm0 1A8 8 0 1 0 8 0a8 8 0 0 0 0 16z"
              />
              <path
                d="M5.255 5.786a.237.237 0 0 0 .241.247h.825c.138 0 .248-.113.266-.25.09-.656.54-1.134 1.342-1.134.686 0 1.314.343 1.314 1.168 0 .635-.374.927-.965 1.371-.673.489-1.206 1.06-1.168 1.987l.003.217a.25.25 0 0 0 .25.246h.811a.25.25 0 0 0 .25-.25v-.105c0-.718.273-.927 1.01-1.486.609-.463 1.244-.977 1.244-2.056 0-1.511-1.276-2.241-2.673-2.241-1.267 0-2.655.59-2.75 2.286zm1.557 5.763c0 .533.425.927 1.01.927.609 0 1.028-.394 1.028-.927 0-.552-.42-.94-1.029-.94-.584 0-1.009.388-1.009.94z"
              />
            </svg>
            <a class="nav-link font-weight-bold text-dark" href="#">Help</a>

            <div class="line">
              <svg xmlns="http://www.w3.org/2000/svg" width="1" height="20">
                <line
                  x1="0"
                  y1="0"
                  x2="0"
                  y2="100"
                  stroke="black"
                  stroke-width="1"
                />
              </svg>
            </div>

            <a class="nav-link" href="#"
              ><svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-bell"
                viewBox="0 0 16 16"
              >
                <path
                  d="M8 16a2 2 0 0 0 2-2H6a2 2 0 0 0 2 2zM8 1.918l-.797.161A4.002 4.002 0 0 0 4 6c0 .628-.134 2.197-.459 3.742-.16.767-.376 1.566-.663 2.258h10.244c-.287-.692-.502-1.49-.663-2.258C12.134 8.197 12 6.628 12 6a4.002 4.002 0 0 0-3.203-3.92L8 1.917zM14.22 12c.223.447.481.801.78 1H1c.299-.199.557-.553.78-1C2.68 10.2 3 6.88 3 6c0-2.42 1.72-4.44 4.005-4.901a1 1 0 1 1 1.99 0A5.002 5.002 0 0 1 13 6c0 .88.32 4.2 1.22 6z"
                />
              </svg>
            </a>

            <div class="line">
              <svg xmlns="http://www.w3.org/2000/svg" width="1" height="20">
                <line
                  x1="0"
                  y1="0"
                  x2="0"
                  y2="100"
                  stroke="black"
                  stroke-width="1"
                />
              </svg>
            </div>
            <div class="profile d-flex align-items-center ml-2">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                width="16"
                height="16"
                fill="currentColor"
                class="bi bi-person-circle"
                viewBox="0 0 16 16"
              >
                <path d="M11 6a3 3 0 1 1-6 0 3 3 0 0 1 6 0z" />
                <path
                  fill-rule="evenodd"
                  d="M0 8a8 8 0 1 1 16 0A8 8 0 0 1 0 8zm8-7a7 7 0 0 0-5.468 11.37C3.242 11.226 4.805 10 8 10s4.757 1.225 5.468 2.37A7 7 0 0 0 8 1z"
                />
              </svg>

              <a class="nav-link font-weight-bold text-dark" href="#"
                >Front Desk</a
              >
            </div>
          </div>
        </li>
      </ul>
    </div>
  </nav>
  <!-- side Bar -->
  <div class="container-fluid">
    <div class="main-container d-flex">
      <div class="side-nav-bar">
        <nav class="bg-white my-0 sidebar p-0">
          <!-- Left sidebar content here -->
          <ul class="nav flex-column">
            <li class="nav-item">
              <a
                class="nav-link d-flex align-items-center flex-column text-orange"
                href="#"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="16"
                  fill="currentColor"
                  class="bi bi-house-door-fill"
                  viewBox="0 0 16 16"
                >
                  <path
                    d="M6.5 14.5v-3.505c0-.245.25-.495.5-.495h2c.25 0 .5.25.5.5v3.5a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5v-7a.5.5 0 0 0-.146-.354L13 5.793V2.5a.5.5 0 0 0-.5-.5h-1a.5.5 0 0 0-.5.5v1.293L8.354 1.146a.5.5 0 0 0-.708 0l-6 6A.5.5 0 0 0 1.5 7.5v7a.5.5 0 0 0 .5.5h4a.5.5 0 0 0 .5-.5Z"
                  />
                </svg>
                <p class="text-orange">Home</p>
              </a>
            </li>
            <li class="nav-item">
              <a
                class="nav-link d-flex align-items-center flex-column text-gray"
                href="#"
              >
                <img src="../assets/icons8-dashboard-layout-24.png" alt="" />
                <p class="text-gray">Dashboard</p>
              </a>
            </li>
            <div class="hor-line">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                style="width: 7rem; height: 1rem"
              >
                <line
                  x1="0"
                  y1="0"
                  x2="100%"
                  y2="0"
                  stroke="black"
                  stroke-width="1"
                />
              </svg>
            </div>
            <li class="nav-item">
              <a
                class="nav-link d-flex align-items-center flex-column text-gray"
                href="#"
              >
                <img src="../assets/icons8-chat-message-32.png" alt="" />
                <p class="text-gray">Chat</p>
              </a>
            </li>
            <li class="nav-item">
              <a
                class="nav-link d-flex align-items-center flex-column text-gray"
                href="#"
              >
                <img src="../assets/icons8-group-50.png" alt="" />
                <p class="text-gray">Clients</p>
              </a>
            </li>
            <div class="hor-line">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                style="width: 7rem; height: 1rem"
              >
                <line
                  x1="0"
                  y1="0"
                  x2="100%"
                  y2="0"
                  stroke="black"
                  stroke-width="1"
                />
              </svg>
            </div>
            <li class="nav-item">
              <a
                class="nav-link d-flex align-items-center flex-column text-gray"
                href="#"
              >
                <img src="../assets/icons8-user-80.png" alt="" />
                <p class="text-gray">Staff</p>
              </a>
            </li>
            <li class="nav-item">
              <a
                class="nav-link d-flex align-items-center flex-column text-gray"
                href="#"
              >
                <img src="../assets/icons8-power-off-button-64.png" alt="" />
                <p class="text-gray">On/Off</p>
              </a>
            </li>
            <div class="hor-line">
              <svg
                xmlns="http://www.w3.org/2000/svg"
                style="width: 7rem; height: 1rem"
              >
                <line
                  x1="0"
                  y1="0"
                  x2="100%"
                  y2="0"
                  stroke="black"
                  stroke-width="1"
                />
              </svg>
            </div>
            <li class="nav-item">
              <a
                class="nav-link d-flex align-items-center flex-column text-gray"
                href="#"
              >
                <img src="../assets/icons8-combo-chart-24.png" alt="" />
                <p class="text-gray">Analytics</p>
              </a>
            </li>
            <li class="nav-item">
              <a
                class="nav-link d-flex align-items-center flex-column text-gray"
                href="#"
              >
                <img src="../assets/icons8-gear-32.png" alt="" />
                <p class="text-gray">Settings</p>
              </a>
            </li>
          </ul>
        </nav>
      </div>

      <div class="content-area pt-5 d-flex flex-column align-items-center">
        <div class="filters bg-white d-flex justify-content-between">
          <div class="left-side-filters">
            <nav
              class="navbar navbar-light bg-white mx-lg-5 filter-bar border-1 rounded-1"
            >
              <form class="form-inline">
                <button
                  class="btn btn-outline-success text-bg-dark-gray mr-2"
                  type="button"
                >
                  All
                </button>
                <button
                  class="btn btn-outline-secondary text-bg-dark-gray mr-2"
                  type="button"
                >
                  Live Queue (74)
                </button>
                <button
                  class="btn btn-outline-success text-bg-dark-gray mr-2"
                  type="button"
                >
                  Walk-In (13)
                </button>
                <button
                  class="btn btn-outline-secondary text-bg-dark-gray mr-2"
                  type="button"
                >
                  appointments (25)
                </button>
                <button
                  class="btn btn-outline-success text-bg-dark-gray mr-2"
                  type="button"
                >
                  Serving (8)
                </button>
                <button
                  class="btn btn-outline-secondary bg-success text-white font-weight-bold mr-2"
                  type="button"
                >
                  Served (15)
                </button>
              </form>
            </nav>
          </div>
          <div class="right-side-filter">
            <nav
              class="navbar navbar-light bg-white mx-lg-5 filter-bar border-1 rounded-1"
            >
              <form class="form-inline">
                <button
                  class="btn btn-outline-success bg-white text-dark font-weight-bold mr-2"
                  type="button"
                >
                  Filters (8)
                </button>
                <button
                  class="btn btn-outline-secondary bg-white text-dark font-weight-bold"
                  type="button"
                >
                  Export (15)
                </button>
              </form>
            </nav>
          </div>
        </div>
        <div class="content-inner d-flex flex-column mt-3">
          <div
            class="header d-flex flex-end justify-content-between align-items-center pt-3"
          >
            <div class="main-t font-weight-bold text-dark">Served(15)</div>
            <div class="searchfor">
              <button
                class="btn search-btn btn-outline-success my-2 my-sm-0"
                type="submit"
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  width="16"
                  height="16"
                  fill="currentColor"
                  class="bi bi-search"
                  viewBox="0 0 16 16"
                >
                  <path
                    d="M11.742 10.344a6.5 6.5 0 1 0-1.397 1.398h-.001c.03.04.062.078.098.115l3.85 3.85a1 1 0 0 0 1.415-1.414l-3.85-3.85a1.007 1.007 0 0 0-.115-.1zM12 6.5a5.5 5.5 0 1 1-11 0 5.5 5.5 0 0 1 11 0z"
                  />
                </svg>
              </button>
            </div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
.navv {
  margin-left: auto;
}
.home-served {
}
.hor-line {
  width: 90%;
}
.update-info {
  margin: 0;
  border: 1px transparent;
  border-radius: 1.5rem;
}
.form-control {
  border: 3px solid rgb(219, 216, 216);
  border-right: none;
  border-top-right-radius: 0%;
  border-bottom-right-radius: 0%;
}
.search-btn {
  border-top-left-radius: 0%;
  border-bottom-left-radius: 0%;
  border-left: none;
  background-color: rgb(219, 216, 216);
  border: 1px solid rgb(219, 216, 216);
  height: 2.5rem;
  width: 2.5rem;
}
.help {
}
.profile {
}
.text-gray {
  color: #8c8e95;
}
.text-orange {
  color: #ed6726;
}

.nav-item {
  width: 7rem;
}
.sidebar {
  width: 10%;
}
.content-area {
  background-color: #edeef2;
  width: 100%;
}
.filters {
  width: 98%;
  border-radius: 0.5rem;
  flex-wrap: wrap;
}
.left-side-filters {
  max-width: 70%;
}
.right-side-filter {
  max-width: 30%;
}
.border-gray {
  border: 2px solid #dedede;
  border-radius: 0.2rem;
}
.filter-bar {
  border: 5px;
  border-radius: 0.5rem;
}
.text-bg-dark-gray {
  color: #71747c;
  font-weight: bold;
}
.content-inner {
  background-color: #f9f9f9;
  width: 98%;
  border-top-right-radius: 0.5rem;
  border-top-left-radius: 0.5rem;
  height: 5rem;
}
.header {
  display: flex;
  flex-direction: row;
  justify-content: space-between;
}
</style>
