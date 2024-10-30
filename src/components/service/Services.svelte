<script>
  import ServiceItem from "./ServiceItem.svelte";

  //    mock data service
  let dataservices = [
    { imgUrl: "../public/images/security.jpg", title: "CYBER SECURITY", link:"#cs" },
    { imgUrl: "../public/images/handCom.jpg", title: "CYBER SECURITY", link:"#cs" },
    { imgUrl: "../public/images/typing.jpg", title: "CYBER SECURITY", link:"#cs" },
  ];
</script>

<section id="services">
  <div class="container-inner">
    <div class="title">Our services</div>
    <div class="content">
      {#each dataservices as dataservice}
        <ServiceItem imgUrl={dataservice.imgUrl} title={dataservice.title} link={dataservice.link} />
      {/each}
    </div>
  </div>
</section>

<style>
  .container-inner {
    padding-top: 100px;
    padding-bottom: 100px;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    .title {
      font-size: 28px;
      font-weight: bold;
      margin-bottom: 20px;
    }
    .content {
      display: grid;
      grid-template-columns: 340px 340px 340px;
      row-gap: 20p;
      column-gap: 20px;
      padding-left: 15px;
      padding-right: 15px;
    }
  }
</style>
