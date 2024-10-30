<script>
  import Header from "./components/Header.svelte";
  import OnePage from "./components/OnePage.svelte";
  import Services from "./components/service/Services.svelte";
</script>

<div>
  <OnePage />
  <Services />
  <section id="cs">
    <div class="container-bg">
      <img src="./public/images/title5.jpg" alt="" />
      <div class="title">Cybersecurity</div>
    </div>
  </section>

  <div class="container-content">
    <div class="content-title">Mobile Application Protection</div>
    <div class="content-detail">
      <div class="detail-img">
        <img src="./public/images/mobile.jpg" alt="" />
      </div>
      <div class="detail-text">
        <p>
          Smartphones have seen rapid growth and adoption in less than a decade.
          With the increase in smartphones there has been a rapid increase of
          the variety of applications that run on smartphones as well.
          Protection of these applications is vital and cannot be ignored. Risk
          factors have only increased and that has increased the demand for
          security of these applications as well.
        </p>
      </div>
    </div>
  </div>
</div>

<style>
  .container-bg {
    display: flex;
    justify-content: center;
    align-items: center;
    img {
      width: 100%;
      height: 289px;
      position: relative;
    }
    .title {
      position: absolute;
      font-size: 28px;
      font-weight: bold;
      color: white;
      z-index: 40;
    }
  }

  .container-content {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding-top: 100px;
    padding-bottom: 100px;
  }
  .content-title{
    font-size: 28px;
    font-weight: bold;
    margin-bottom: 20px;
    color: #2f2f2f;
  }
  .content-detail {
    display: grid;
    grid-template-columns: 460px 652px;
    column-gap: 20px;
    text-align: start;
  }
  .detail-img img {
    width: 460px;
    height: 230px;
  }
  .detail-text p {
    margin: 0;
    color: #5b5b5b;
  }
</style>
