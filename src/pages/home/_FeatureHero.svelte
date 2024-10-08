<script>
  import { Section, HeroHeader } from "flowbite-svelte-blocks";
  import { Button } from "flowbite-svelte";
  import { ArrowRightOutline } from "flowbite-svelte-icons";
  // import ParallaxDevices from "./_ParallaxDevices.svelte";
</script>

<Section name="heroVisual">
  <div class="mx-auto place-self-center lg:col-span-12">
    <HeroHeader
      h1Class="max-w-5xl mb-4 text-4xl font-extrabold tracking-tight !leading-[1.05] md:text-5xl xl:text-6xl dark:text-white"
      h2Class="max-w-5xl mb-4 text-2xl font-bold tracking-tight !leading-[1.05] md:text-3xl xl:text-4xl dark:text-white"
      pClass="max-w-5xl mb-6 font-light text-gray-500 lg:mb-8 md:text-lg lg:text-xl dark:text-gray-200"
    >
      <svelte:fragment slot="h1">
        Hi, I'm Gregg Coppen
      </svelte:fragment>
      <svelte:fragment slot="h2">
        Transforming ideas into powerful, scalable digital solutions by blending creativity with technical expertise.
      </svelte:fragment>
      <svelte:fragment slot="paragraph">
        <div class="block sm:hidden">
          A creative professional with over two decades of experience in web development, design, and animation. I specialize in crafting powerful, scalable platforms that not only meet technical demands but also captivate users through intuitive design and engaging experiences. From e-commerce and AI platforms to community-focused websites, my passion lies in turning complex challenges into elegant solutions.
        </div>
        <div class="hidden sm:block">
          A creative professional with over two decades of experience in web development, design, and animation. I specialize in crafting powerful, scalable platforms that not only meet technical demands but also captivate users through intuitive design and engaging experiences. From e-commerce and AI platforms to community-focused websites, my passion lies in turning complex challenges into elegant solutions.
        </div>
      </svelte:fragment>
  
    </HeroHeader>

    <div
      class="md:text-md lg:text-md max-w-2xl font-light text-gray-500 dark:text-gray-200"
    >
      <div class="mt-8 flex flex-col gap-2 sm:flex-row sm:gap-0">
        <a
          href="https://tidycal.com/growagent/30-minute-meeting"
          target="_blank"
          ><Button
            size="xl"
            color="blue"
            class="mr-3 inline-flex items-center justify-center"
            >Book a 30 minute call<ArrowRightOutline
              size="md"
              class="-mr-1 ml-2"
            /></Button
          >
        </a>
      </div>
    </div>
  </div>

</Section>
