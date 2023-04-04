<script>
  import brandColorsSrc from "./brandColors.png";
</script>

<section
  class="h-screen snap-start px-4 py-8 flex flex-col gap-6 overflow-y-hidden"
>
  <h2 class="text-2xl font-semibold">Brand Colors</h2>
  <div class="py-2">
    <hr class="border-b border-[#CCCCCC] border-dashed" />
  </div>
  <div class="">
    <h3 class="text-xl mb-6 font-semibold">Main Color</h3>
    <p>
      These bold colors add energy to our brand, while highlighting the
      simplicity of our designs.
    </p>
  </div>
  <div class="flex gap-2 justify-between flex-wrap">
    <div class="flex justify-center items-center flex-col">
      <div class="rounded-full mb-3 bg-[#231F20] h-[90px] w-[90px] shadow-md" />
      <div class="mb-3">True Black</div>
      <div>#231F20</div>
      <div>35, 31, 32</div>
    </div>
    <div class="flex justify-center items-center flex-col">
      <div class="rounded-full mb-3 bg-[#58595B] h-[90px] w-[90px] shadow-md" />
      <div class="mb-3">True Gray</div>
      <div>#58595B</div>
      <div>88, 89, 91</div>
    </div>
    <div class="flex justify-center items-center flex-col">
      <div class="rounded-full mb-3 bg-[#FED107] h-[90px] w-[90px] shadow-md" />
      <div class="mb-3">Dandelion</div>
      <div>#FED107</div>
      <div>254, 209, 7</div>
    </div>
    <div class="flex justify-center items-center flex-col">
      <div class="rounded-full mb-3 bg-[#EF3F40] h-[90px] w-[90px] shadow-md" />
      <div class="mb-3">Radiant Red</div>
      <div>#EF3F40</div>
      <div>239, 63, 64</div>
    </div>
    <div class="flex justify-center items-center flex-col">
      <div class="rounded-full mb-3 bg-[#FFFFFF] h-[90px] w-[90px] shadow-md" />
      <div class="mb-3">Pure White</div>
      <div>#FFFFFF</div>
      <div>255, 255, 255</div>
    </div>
  </div>
  <figure class="justify-center items-center hidden sm:flex mt-6">
    <img src={brandColorsSrc} alt="Brand Colors" class="h-auto max-w-xl" />
  </figure>
</section>

<section
  class="h-screen snap-start px-4 py-8 flex flex-col gap-6 overflow-y-hidden"
>
  <h2 class="text-2xl font-semibold">Typography</h2>
  <div class="py-2">
    <hr class="border-b border-[#CCCCCC] border-dashed" />
  </div>
  <div class="">
    <h3 class="text-xl mb-6 font-semibold">Brand Fonts</h3>
    <p>
      We use DIN to communicate our message because of the font's similar
      dedication to utility and simplicity. Courier New was selected as our body
      font because of its association with the technological era that inspires
      us.
    </p>
  </div>
  <div>
    <h4 class="text-lg font-semibold mb-6">DIN Alternate Bold</h4>
    <div class="flex gap-6">
      <div class="text-8xl">Aa</div>
      <div>
        <p class="text-xl">ABCDEFGHIJKLMNOPQRSTUVWXYZ</p>
        <p class="text-xl">abcdefghijklmnopqrstuvwxyz</p>
        <p class="text-xl">1234567890(,.;:?!$&*)</p>
      </div>
    </div>
  </div>
</section>
