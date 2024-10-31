<script>
  import Cybersecurity from "./components/content/cybersecurity/Cybersecurity.svelte";
  import Header from "./components/Header.svelte";
  import OnePage from "./components/OnePage.svelte";
  import Services from "./components/content/service/Services.svelte";
  import Automation from "./components/content/Automation.svelte";
  import Turnkey from "./components/content/turnkey/Turnkey.svelte";
  import About from "./components/content/about/About.svelte";
</script>

<div class="homepage">
  <Header />
  <OnePage />
</div>
<Services />
<Cybersecurity />
<Automation/>
<Turnkey/>
<About />
<style>
  .homepage {
    height: 100vh;
    background-image: url(../../public/images/onepage-01.jpg);
    background-size: cover;
    opacity: 1;
    color: white;
    top: 0;
  }
</style>
