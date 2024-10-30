<script>
  import Header from "./Header.svelte";
</script>

<div class="onepage">
  <Header />
  <div class="title">
    <div class="title-header">
      <a href="rpa">Robotic Process Automation (RPA)</a>
    </div>
    <div class="title-detail">
      <p>Automate your business using robotic solution</p>
    </div>
  </div>
</div>

<style>
  .onepage {
    height: 100vh;
    background-image: url(../../public/images/onepage-01.jpg);
    background-size: cover;
    opacity: 1;
    background-repeat: no-repeat;
    visibility: inherit;
  }
  .title {
    color: white;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;

    .title-header{
      a{
        color: white;
        text-decoration: none;
        font-size: 56px;
        font-weight: 700;
      }
      a:hover {
          color: #70aed2;
        }
    }

    .title-detail{
        font-size: 28px;
        font-weight: 300;
    }
  }
</style>
