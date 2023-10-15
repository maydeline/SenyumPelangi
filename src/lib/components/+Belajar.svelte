<script>
  import { Heading, P, Button } from 'flowbite-svelte';
  import { ArrowRightOutline } from 'flowbite-svelte-icons';
  let Details="Ayo adik – adik  daftarkan dirimu untuk ikut dalam kelas matematika, Bahasa Inggris, Bahasa mandarin atau memasak! Gunakan masa muda kalian untuk hal – hal yang berguna bagi masa depan kalian";
</script>

<div class="">
  <div class = "pt-28 pb-40">
    <div class="flex flex-col items-center space-y-8 md:flex-row mx-auto container md:space-x-20 pl-12 pr-12 lg:pl-20 lg:pr-20 ">
        <!-- Change the image to the one you would like to show -->
      <img src="/Hero.jpeg" alt="Pelangi-Photo" class="h-[10rem] w-[15rem] sm:h-[14rem] sm:w-[21rem] lg:h-[20rem] lg:w-[30rem]"> 

      <div class="flex flex-col w-full align-center justify-center items-center  md:w-160 lg:w-200 md:items-start">
        <Heading tag="h2" class="mb-4" customSize="text-center md:text-left text-3xl font-extrabold  md:text-4xl lg:text-5xl">Learn Together with Us</Heading>
        <p class="mb-6 text-center md:text-left text-md lg:text-lg dark:text-gray-400">{Details}</p>
        <Button href="/" class="w-[15rem]">
          Daftar Sekarang!
          <ArrowRightOutline class="w-3.5 h-3.5 ml-2" />
        </Button>
      </div>
    </div>
  </div>
</div>


