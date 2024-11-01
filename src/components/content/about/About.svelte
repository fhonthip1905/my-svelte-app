<script>
  import { AboutMockData } from "../ContentMockData";
</script>

<section id="about">
  <div class="container-content">
    <div class="content-title">{AboutMockData.title}</div>
    <div class="content-detail">
      <div class="detail-text">
        <p>
          {AboutMockData.detail}
        </p>
      </div>
    </div>
  </div>
</section>

<style>
  .container-content {
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    padding-top: 40px;
    padding-bottom: 40px;
  }
  .content-title {
    font-size: 28px;
    font-weight: bold;
    margin-bottom: 20px;
    color: #2f2f2f;
  }
  .content-detail {
    width: auto;
    padding: 0 40px;
  }

  .detail-text {
    display: flex;
    justify-content: center;
  }

  .detail-text p {
    width: 80%;
    margin: 0;
    color: #5b5b5b;
  }

  @media only screen and (max-width: 1024px) {
    .detail-text p {
      width: 80%;
    }
  }

  @media only screen and (max-width: 700px) {
    .detail-text p {
      width: 100%;
    }
    .content-detail {
      margin-bottom: 80px;
    }
  }
</style>
