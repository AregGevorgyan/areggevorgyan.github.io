<script lang="ts">
  import Seo from "$lib/components/Seo.svelte";
  import WritingList from "./WritingList.svelte";
  import writing from "./writing.yaml";
</script>

<Seo
  title="Areg Gevorgyan – Writing"
  description="Past writing: academic papers, presentations, notes, tutorials, and blog posts."
/>

<section class="layout-md py-12">
  <h2 class="heading2">Blog</h2>
  <WritingList data={writing.blog ?? []} />
</section>

<section class="layout-md py-12">
  <h2 class="heading2">Notes</h2>
  <WritingList data={writing.notes ?? []} />
</section>

<section class="layout-md py-12">
  <h2 class="heading2">Academic Writing</h2>
  <WritingList data={writing.papers ?? []} />
</section>
