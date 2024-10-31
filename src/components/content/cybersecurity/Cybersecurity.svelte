<script>
  import ContentItem from "../ContentItem.svelte";
  import HeadTitle from "../HeadTitle.svelte";
  import { CyberTitleMockData,CyberMockData } from "../ContentMockData";

 
</script>

<HeadTitle headTitle={CyberTitleMockData.title} id={CyberTitleMockData.id} />

{#each CyberMockData as data}
<ContentItem contentTitle={data.title} contentImage={data.image} contentDetail={data.detail} />
{/each}

