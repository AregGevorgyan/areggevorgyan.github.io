<script lang="ts">
  import { ArrowUpRight } from "lucide-svelte";

  import Seo from "$lib/components/Seo.svelte";

  const featuredProjects = [
    {
      name: "Cortex",
      href: "/projects#Cortex",
      desc: "Modern deep learning from scratch",
    },
  ];
</script>

<Seo
  title="Areg Gevorgyan"
  description="Researcher, Builder, and Math + CS student."
/>

<div class="layout-md text-lg space-y-14">
  <div class="space-y-5">
    <p>
      I'm a builder and Math + CS student at UMD interested in the intersection
      of the two fields I study. Particularly areas that blur the lines between
      the two and have implications in both theory and practice, such as machine
      learning and algorithms.
    </p>

    <p>
      I'm currently building
      <a href="https://github.com/alkahest-cas/alkahest">alkahest</a>, a modern
      high performance symbolic math system designed for the era of AI agents.
    </p>

    <p>
      Before this I worked on a voice multi-agent orchestration platform
      CallCode, built deep learning framework from scratch, and deployed AI
      models on the Boston Dynamics Spot robot.
    </p>
  </div>
</div>

<style lang="postcss">
  .g {
    @apply text-neutral-400;
  }

  em {
    @apply font-serif text-[110%] leading-[100%];
  }

  .project-pair {
    @apply grid sm:grid-cols-[1fr,2fr] gap-y-1 -mx-3 px-3 py-2 hover:bg-neutral-100 transition-colors;
  }

  aside {
    @apply mt-0.5 text-base text-neutral-500;
  }

  /* Correction for vertical navigation links on mobile. */
  @media (max-width: 420px) {
    #eric-is {
      @apply -mt-10;
    }
  }
</style>
