<script>
  // import Header from "./Header.svelte";
</script>

<div class="title">
  <div class="title-header">
    <a href="rpa">Robotic Process Automation (RPA)</a>
  </div>
  <div class="title-detail">
    <p>Automate your business using robotic solution</p>
  </div>
</div>

<style>
  .title {
    color: white;
    height: 100%;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    text-align: center;

    .title-header {
      a {
        color: white;
        text-decoration: none;
        font-size: 56px;
        font-weight: 700;
      }
      a:hover {
        color: #70aed2;
      }
    }

    .title-detail {
      font-size: 28px;
      font-weight: 300;
    }
  }

  @media only screen and (max-width: 700px) {
    .title {
      .title-header a {
        font-size: 36px;
      }
      .title-detail {
        font-size: 18px;
      }
     
    }
  }
</style>
