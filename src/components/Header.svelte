
<nav class="navbar">
  <div class="navbar-logo">
    <a href="#home">
      <div class="logo-img">
        <img src="../public/icons/logo-white.png" alt="" />
      </div>
      <div class="logo-text">FFnT</div>
    </a>
  </div>
  <div class="navbar-menu">
    <ul class="menu-list">
      <li class="current-page">
        <a href="#home">HOME</a>
      </li>
      <li class="dropdown">
        <a href="#services">SERVICES</a>
        <!-- <ul class="dropdown-menu">
            <li><a href="#cybersecurity">Cybersecurity</a></li>
            <li>
              <a href="#app-protection" class="sub-menu"
                >- Mobile Application Protection</a
              >
            </li>
            <li>
              <a href="#multi-factor-authentication" class="sub-menu"
                >- Multi-factor Authentication</a
              >
            </li>
            <li>
              <a href="#single-sign-on" class="sub-menu">- Single Sign On</a>
            </li>
            <li><a href="#automation">Automation</a></li>
            <li><a href="#rpa" class="sub-menu">- RPA</a></li>
            <li><a href="#turnkey-solution">Turnkey Solution</a></li>
            <li>
              <a href="#mobile-app-development" class="sub-menu"
                >- Mobile Application Development</a
              >
            </li>
            <li>
              <a href="#cloud-solution" class="sub-menu">- Cloud Solution</a>
            </li>
          </ul> -->
      </li>
      <li>
        <a href="#about">ABOUT</a>
      </li>
      <li>
        <a href="#contact">CONTACT</a>
      </li>
    </ul>
  </div>
</nav>

<style>
  nav.navbar {
    display: flex;
    align-items: center;
    color: white;
    padding: 0 40px;
    background-color:#011e54b9;
    position: fixed;
    width: 100%;
    top: 0;
    z-index: 999;
    .navbar-logo {
      display: flex;
      justify-content: center;
      align-items: center;
      text-decoration: none;
      height: 80px;
      a {
        display: flex;
        align-items: center;
        text-decoration: none;
      }
      .logo-img img {
        width: 36px;
        height: 36px;
        padding: 4px;
      }
      .logo-text {
        color: white;
        font-size: 42px;
        font-weight: 700;
      }
    }
    .navbar-menu {
      display: flex;
      justify-content: center;
      align-items: center;
      width: auto;
      height: 80px;
      margin: 0 auto;

      ul.menu-list {
        display: flex;
        li {
          padding: 0 20px;
          list-style-type: none;
        }
        a {
          color: white;
          font-size: 12px;
          font-family: "Montserrat", sans-serif;
          text-decoration: none;
          letter-spacing: 2px;
          font-weight: 700;
        }
        a:hover {
          color: #70aed2;
        }
      }
    }
  }
</style>
