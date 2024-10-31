<script>
  import ContentItem from "./ContentItem.svelte";
  import HeadTitle from "./HeadTitle.svelte";
  import { AutoTitleMockData, AutoMockData } from "./ContentMockData";
</script>

<HeadTitle headTitle={AutoTitleMockData.title} id={AutoTitleMockData.id} />

<ContentItem contentTitle={AutoMockData.title} contentImage={AutoMockData.image} contentDetail={AutoMockData.detail} />
