<script>
  export let imgUrl, title;
</script>

<div class="card-item">
  <img class="card-img" src={imgUrl} alt="" />
  <div class="card-title">{title}</div>
</div>

<style>
  .card-item {
    position: relative;
    height: fit-content;
    img.card-img {
      width: 340px;
      height: 280px;
    }
    .card-title {
      width: fit-content;
      padding: 0 16px;
      font-size: 16px;
      position: absolute;
      top: 220px;
      right: 0;
      z-index: 9;
      color: white;
      background-color: #0000003c;
    }
  }
</style>
