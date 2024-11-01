<script>
  export let contentTitle, contentImage, contentDetail;
</script>

<div class="container-content">
  <div class="content-title">{contentTitle}</div>
  <div class="content-detail">
    <div class="detail-img">
      <img src={contentImage} alt="" />
    </div>
    <div class="detail-text">
      <p>
        {contentDetail}
      </p>
    </div>
  </div>
</div>

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
    display: grid;
    grid-template-columns: 1fr 1fr;
    /* padding: 0 80px; */
    column-gap: 10px;
    row-gap: 10px;
    text-align: start;
  }
  .detail-img {
    text-align: end;
    img {
      width: 460px;
      height: 230px;
    }
  }
  .detail-text {
    width: calc(100% - 41%);
    p {
      margin: 0;
      color: #5b5b5b;
    }
  }

  @media only screen and (max-width: 1024px) {
    .detail-text {
      width: calc(100% - 30px);
    }
  }

  @media only screen and (max-width: 700px) {
    .container-content {
      padding-top: 30px;
      padding-bottom: 30px;
    }
    .content-title {
      text-align: center;
    }
    .content-detail {
      grid-template-columns: none;
      text-align: center;
    }

    .detail-img
    {
      text-align: center;
      img {
      width: 350px;
    }
    } 
    .detail-text p {
      padding: 40px;
      text-align: start;
    }
  }
</style>
