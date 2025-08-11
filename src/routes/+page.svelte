<script lang="ts">
  import { ArrowUpRight } from "lucide-svelte";

  import Seo from "$lib/components/Seo.svelte";

  const featuredProjects = [
    {
      name: "Cortex",
      href: "/projects#Cortex",
      desc: "Modern machine learning from scratch",
    },
  ];
</script>

<Seo
  title="Areg Gevorgyan"
  description="Researcher, Builder, and Computer Science and Mathematics student."
/>

<div class="layout-md text-lg space-y-14">
  <div class="space-y-5">
    <p>
      Hi, I’m an undergraduate student at University of Maryland studying
      Mathematics and Computer Science. I am currently interning at the
      Collective Dynamics and Control Lab at UMD, as well as working on personal
      projects such as building machine learning algorithms from scratch and
      formalizing math in lean. I previously worked as a VR developer for the
      Earth Sciences department and led the Math Team at my high school.
    </p>

    <p>
      I’m interested in everything related to mathematics and computer science,
      particularly areas that blur the lines between the two and have
      implications in both theory and practice, such as machine learning and
      algorithms.
    </p>
  </div>

  <div class="space-y-5">
    <!-- <p>This is what I look like:</p> -->
    <img alt="Picture of Areg" src="/assets/images/portrait.jpg" />
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
