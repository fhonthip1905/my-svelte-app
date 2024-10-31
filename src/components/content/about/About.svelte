<script>
  import ContentItem from "../ContentItem.svelte";
  import { AboutMockData } from "../ContentMockData";
</script>

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
  .content-detail{
    width: 1100px;
  }
  .detail-text p {
    margin: 0;
    color: #5b5b5b;
  }

  @media only screen and (max-width: 700px) {
    .content-detail{
    width: 350px;
    margin-bottom: 80px;
  }
  }
</style>

