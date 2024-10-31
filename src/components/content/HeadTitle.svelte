<script>
    export let headTitle, id;
</script>

<section id={id}>
    <div class="container-bg">
      <img src="./public/images/title5.jpg" alt="" />
      <div class="title">{headTitle}</div>
    </div>
  </section>

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

  </style>