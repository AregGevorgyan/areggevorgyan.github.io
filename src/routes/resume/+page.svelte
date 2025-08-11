<script lang="ts">
  import Seo from "$lib/components/Seo.svelte";
  import Workplace from "./Workplace.svelte";
</script>

<Seo
  title="Areg Gevorgyan – Resume"
  description="Researcher, Builder, and Computer Science and Mathematics student."
/>

<section class="layout-md py-12">
  <h2 class="heading2">Education</h2>

  <div class="mb-4">
    <div class="flex justify-between items-end">
      <h3 class="text-black text-lg">University of Maryland, College Park</h3>
      <div class="text-neutral-500 mb-0.5">2024 — 2028</div>
    </div>
    <p class="byline">B.S. Mathematics, B.S. Computer Science</p>
  </div>

  <p>University Honors student with junior standing.</p>

  <h4 class="font-medium mt-4 mb-1">Selected coursework:</h4>
  <ul>
    <li>
      Honors Linear Algebra, Multivariable Calculus, and Differential Equations
    </li>
    <li>Discreate Structures</li>
    <li>Computer Systems</li>
    <li>Object Oritented Programming</li>
    <li>Probability Theory</li>
    <li>Mathematical Statistics</li>
  </ul>
</section>

<section class="layout-md py-12">
  <h2 class="heading2">Experience</h2>

  <Workplace
    title="Machine Learning Intern"
    company="University of Maryland"
    url="https://cdcl.umd.edu/"
    dates="June 2025 - Present"
  >
    <li>
      Building framework for testing vision language models for the DARPA Triage
      Challenge with the Collective Dynamics and Control Lab
    </li>
    <li>Utilized Python, HF Transformers, HF Accelerate, PyTorch</li>
    <li>Models will be deployed on Boston Dynamics Spot robot</li>
  </Workplace>

  <Workplace
    title="Quantitative Analyist"
    company="Apex Fund"
    url="https://www.linkedin.com/company/apexfund-md"
    dates="December 2024 - Present"
  >
    <li>
      Developing financial model backtesting framework using JAX at student run
      quantitative fund
    </li>
  </Workplace>

  <Workplace
    title="Software Engineering Intern"
    company="University of Maryland"
    url="https://cisess.umd.edu/"
    dates="June 2024 – October 2024"
  >
    <li>
      Built VR application to educate about the types of lightning at Each
      Science Center
    </li>
    <li>
      Project presented at AGU 2024 conference and won best presentation award
      at internship
    </li>
    <li>Used C#, Unity, Git, and Blender</li>
  </Workplace>
</section>

<section class="layout-md py-12">
  <h2 class="heading2">Skills</h2>

  <div class="mb-4">
    <h3 class="font-medium mb-1">Programming:</h3>
    Python, C/C++, Java, MATLAB, C#, JavaScript LaTeX, GAS Assembly
    <h3 class="font-medium mb-1">Frameworks:</h3>
    PyTorch, Pandas, NumPy, SciPy, JAX, Huggingface packages
    <h3 class="font-medium mb-1">Developer Tools:</h3>
    Linux, Bash/Zsh/Tmux, Git, SLURM, Vim, Emacs, Docker
  </div>
</section>

<style lang="postcss">
  b {
    @apply font-medium;
  }

  ul {
    @apply list-disc pl-7 marker:text-neutral-400;
  }

  .byline {
    @apply font-serif italic;
  }
</style>
