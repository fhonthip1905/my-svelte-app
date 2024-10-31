<script>
  import ContentItem from "../ContentItem.svelte";
  import HeadTitle from "../HeadTitle.svelte";
  import { TurnkeyTitleMockData, TurnkeyMockData } from "../ContentMockData";
</script>

<HeadTitle
  headTitle={TurnkeyTitleMockData.title}
  id={TurnkeyTitleMockData.id}
/>

{#each TurnkeyMockData as data}
  <ContentItem contentTitle={data.title} contentImage={data.image} contentDetail={data.detail} />
{/each}
