<script>
  import Dropdown from "./dropdown.svelte";



</script>
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

  <div class="menu-icon">
    <button>
      <img src="../public/icons/burger-menu.png" alt="icon-menu" />
    </button>
    <div id="active">
      <Dropdown />
    </div>
 
  </div>
</nav>

<style>
  nav.navbar {
    display: flex;
    justify-content: space-around;
    align-items: center;
    padding: 0 40px;
    /* border: 1px dashed red; */
    background: transparent;
    position: fixed;
    z-index: 999;
    width: 100%;
  }
  .navbar-logo a {
    display: flex;
    justify-content: center;
    align-items: center;
    text-decoration: none;
    color: white;
    /* border: 1px dashed red; */
    column-gap: 10px;
  }
  .navbar-logo img {
    height: 36px;
    width: 36px;
  }
  .logo-text {
    color: white;
    font-size: 42px;
    font-weight: 700;
  }

  ul.menu-list {
    display: flex;
    justify-content: center;
    align-items: center;
    list-style-type: none;
    visibility: visible;
  }
  ul a {
    text-decoration: none;
    color: white;
    padding: 0 20px;
  }
  a:hover {
    color: #70aed2;
  }

  button {
    visibility: hidden;
    background: transparent;
    border: none;
    img {
      height: 36px;
      width: 36px;
    }
  }

  @media only screen and (max-width: 700px) {
    nav.navbar {
      height: 68px;
      padding: 0;
      display: flex;
      justify-content: space-between;
    }
    .navbar-logo img {
      padding: 10px;
      text-align: center;
      justify-content: center;
      display: flex;
    }
    .logo-text {
      display: none;
    }
    
    ul.menu-list {
      display: none;
    }
    button {
      visibility: visible;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 0;
      img {
        padding: 10px;
      }
    }
  }
  #active{
    /* display: block; */
    display: none;
  }

</style>
