<section id="services">
  <div class="container-inner">
    <div class="title">Our services</div>
    <div class="content">
      <div class="card-item">
        <img class="card-img" src="../public/images/security.jpg" alt="" />
        <div class="card-title">CYBER SECURITY</div>
      </div>
      <div class="card-item">
        <img class="card-img" src="../public/images/security.jpg" alt="" />
        <div class="card-title">CYBER SECURITY </div>
      </div>
      <div class="card-item">
        <img class="card-img" src="../public/images/security.jpg" alt="" />
        <div class="card-title">CYBER SECURITY</div>
      </div>
    </div>
  </div>
</section>

<style>
  .container-inner {
    padding-top: 100px;
    padding-bottom: 100px;
    text-align: center;
    
    .title {
      font-size: 28px;
      font-weight: bold;
      margin-bottom: 20px;
    }
  }
  .content {
    display: grid;
    grid-template-columns: auto auto auto;
    row-gap: 20p;
    padding-left: 15px;
    padding-right: 15px;
  }
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
      left: 232px;
      z-index: 9;
      color: white;
      background-color: #0000003c;
    }
  }
</style>
