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
      <div class="text-neutral-500 mb-0.5">Expected May 2028</div>
    </div>
    <p class="byline">B.S. Computer Science, B.S. Mathematics</p>
  </div>

  <p>Senior standing.</p>

  <h4 class="font-medium mt-4 mb-1">Relevant coursework:</h4>
  <ul>
    <li>Advanced Algorithms</li>
    <li>Honors Linear Algebra</li>
    <li>Real Analysis</li>
    <li>Probability Theory</li>
    <li>Mathematical Statistics</li>
    <li>Programming Languages</li>
    <li>Abstract Algebra</li>
    <li>Field Theory</li>
    <li>Set Theory</li>
  </ul>
</section>

<section class="layout-md py-12">
  <h2 class="heading2">Experience</h2>

  <Workplace
    title="Co-founder"
    company="CallCode"
    url="https://github.com/AregGevorgyan"
    dates="January 2026 - present"
  >
    <li>
      Built parallel AI agent orchestration tool that I am scaling and iterating
      on; tested with 40 users who built real applications including disability
      communication and art gallery applications
    </li>
    <li>
      Cursor DC hackathon 1st place, Startup Shell pitch competition winner
    </li>
  </Workplace>

  <Workplace
    title="Machine Learning Intern"
    company="University of Maryland"
    url="https://cdcl.umd.edu/"
    dates="May 2025 - August 2025"
  >
    <li>
      Worked on the DARPA Triage Challenge with the Collective Dynamics and
      Control Lab
    </li>
    <li>
      Built benchmark for testing vision language models and implemented VLM
      system with 30% higher accuracy and 50% faster on Boston Dynamics Spot
      robot
    </li>
    <li>Utilized Python, HF Transformers, PyTorch, vLLM</li>
  </Workplace>

  <Workplace
    title="Software Engineering Intern"
    company="University of Maryland"
    url="https://cisess.umd.edu/"
    dates="June 2024 – October 2024"
  >
    <li>
      Built VR application to educate about the types of lightning at Earth
      Science Center
    </li>
    <li>
      Presented at AGU 2024 conference and won best presentation award at
      internship
    </li>
  </Workplace>

  <Workplace
    title="Fellow"
    company="Startup Shell"
    url="https://startupshell.org/"
    dates="September 2025 - present"
  >
    <li>Won 6 awards at hackathons and pitch competitions</li>
    <li>Managing GPU server, NAS, and VPN with 30 users</li>
  </Workplace>
</section>

<section class="layout-md py-12">
  <h2 class="heading2">Projects</h2>

  <div class="mb-8">
    <h3 class="text-black text-lg leading-tight mb-1">
      MSG: Multimodal Spatial reasoning Gym
    </h3>
    <p class="font-light mb-2 text-neutral-500">2026</p>
    <ul class="list-disc pl-7 marker:text-neutral-400">
      <li>
        Built reinforcement learning environment for fine tuning vision language
        models on 1 million spatial reasoning tasks extracted from hours of
        construction footage
      </li>
      <li>Used to fine tune Qwen 3.5 on 12 H100 GPUs</li>
    </ul>
  </div>

  <div class="mb-8">
    <h3 class="text-black text-lg leading-tight mb-1">Cortex</h3>
    <p class="font-light mb-2 text-neutral-500">2025</p>
    <ul class="list-disc pl-7 marker:text-neutral-400">
      <li>
        Built a machine learning library from scratch utilizing automatic
        differentiation and implemented neural networks including MLPs and CNNs
        to successfully train image classifier
      </li>
      <li>
        Taught myself optimization algorithms, backpropagation, neural networks,
        CNNs, machine learning systems, and machine learning theory
      </li>
    </ul>
  </div>

  <div class="mb-8">
    <h3 class="text-black text-lg leading-tight mb-1">
      Kubernetes Scaled Inference
    </h3>
    <p class="font-light mb-2 text-neutral-500">2026</p>
    <ul class="list-disc pl-7 marker:text-neutral-400">
      <li>
        Built a system to deploy multiple instances of Qwen3.5-0.8B on a server
        with multiple Nvidia graphics cards
      </li>
      <li>Served on OpenAI comparable API to several users</li>
    </ul>
  </div>

  <div class="mb-8">
    <h3 class="text-black text-lg leading-tight mb-1">
      <a class="link" href="https://tomatocode.xyz">Tomatocode.xyz</a>
    </h3>
    <p class="font-light mb-2 text-neutral-500">2025</p>
    <ul class="list-disc pl-7 marker:text-neutral-400">
      <li>
        Built synchronous coding teaching tool that provides live feedback to
        instructor, currently used in classes
      </li>
    </ul>
  </div>

  <div class="mb-8">
    <h3 class="text-black text-lg leading-tight mb-1">
      <a class="link" href="https://hicruit.us">Hicruit.us</a>
    </h3>
    <p class="font-light mb-2 text-neutral-500">2025</p>
    <ul class="list-disc pl-7 marker:text-neutral-400">
      <li>
        Built backend for a recruiting tool that automatically screens
        candidates with AI phone interviews using Python
      </li>
    </ul>
  </div>

  <div class="mb-8">
    <h3 class="text-black text-lg leading-tight mb-1">
      Linux Shell and Memory Allocator
    </h3>
    <p class="font-light mb-2 text-neutral-500">2025</p>
    <ul class="list-disc pl-7 marker:text-neutral-400">
      <li>
        Built a Linux shell and memory allocator from scratch in C utilizing
        processes, forking, and memory management
      </li>
    </ul>
  </div>
</section>

<section class="layout-md py-12">
  <h2 class="heading2">Skills</h2>

  <div class="mb-4">
    <h3 class="font-medium mb-1">Languages:</h3>
    Python (advanced), C++, Rust, CUDA, LaTeX (advanced), Lean, OCaml, C, Java, JavaScript,
    Assembly
    <h3 class="font-medium mb-1">Frameworks:</h3>
    PyTorch, JAX/Flax, Huggingface Transformers, TRL, verl, vLLM, Node.js, Bun
    <h3 class="font-medium mb-1">Infrastructure:</h3>
    Linux, Bash/Zsh, Git, K8s, SLURM, Vim, Emacs, Docker, GCP, distributed multi-GPU
    training
  </div>
</section>

<style lang="postcss">
  ul {
    @apply list-disc pl-7 marker:text-neutral-400;
  }

  .byline {
    @apply font-serif italic;
  }
</style>
