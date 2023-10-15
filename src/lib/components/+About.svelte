<script>
  import { Heading} from 'flowbite-svelte';
  let AboutUs="Dipelopori oleh seorang siswa Sekolah Menengah Atas, William Max Kusumo bersama rekan – rekannya yang membentuk sebuah komunitas relawan pendidikan di Surabaya, Indonesia. Tujuan terbentuknya SENYUM PELANGI adalah untuk memberikan tempat belajar alternatif bagi anak jalanan dan adik-adik yang mendapat perhatian minim. William berharap apa yang dilakukan komunitas ini bisa bermanfaat untuk masyarakat sekitar yang membutuhkan. Untuk saat ini tersedia kelas matematika, Bahasa Indonesia, Bahasa Inggris, Bahasa mandarin, dan memasak. Semoga kedepannya akan ada kelas tambahan yang mengajar bidang – bidang lainnya.";
</script>

<!-- <div class="">
  <div class = "pt-20 pb-20">
    <div class="flex flex-col w-full align-center justify-center items-center pl-10 pr-10 sm:pl-18 sm:pr-18 md:pl-28 md:pr-28 lg:pl-40 lg:pr-40 md:w-160 lg:w-200">
      <Heading tag="h2" class="mb-4" customSize="text-center text-xl font-extrabold  md:text-2xl lg:text-3xl">Apa itu SENYUM PELANGI?</Heading>
      <p class="text-center leading-loose text-md lg:text-lg dark:text-gray-400">{AboutUs}</p>
    </div>
  </div>
</div> -->


<div>
  <Heading tag="h2" class="mb-4 md:mb-16" customSize="text-center text-3xl font-extrabold  md:text-4xl lg:text-5xl">Siapakah Kami?</Heading>
  <div class="mt-10 mb-8 ml-20 mr-20 lg:ml-32">
    <ol class="items-center sm:flex">
      <li class="relative content-center mb-6 sm:mb-0">
          <div class="flex items-center ">
              <div class="z-10 flex items-center justify-center w-6 h-6 bg-blue-100 rounded-full ring-0 ring-white dark:bg-blue-900 sm:ring-8 dark:ring-gray-900 shrink-0">
                  <svg class="w-2.5 h-2.5 text-blue-800 dark:text-blue-300" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                      <path d="M20 4a2 2 0 0 0-2-2h-2V1a1 1 0 0 0-2 0v1h-3V1a1 1 0 0 0-2 0v1H6V1a1 1 0 0 0-2 0v1H2a2 2 0 0 0-2 2v2h20V4ZM0 18a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V8H0v10Zm5-8h10a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Z"/>
                  </svg>
              </div>
          </div>
          <div class="mt-3 sm:pr-8">
              <h3 class="text-lg font-semibold text-gray-900 dark:text-white">Senyum Pelangi Dibentuk</h3>
              <time class="block mb-2 text-sm font-normal leading-none text-gray-400 dark:text-gray-500">[Bulan, Tahun]</time>
              <p class="text-base font-normal text-gray-500 dark:text-gray-400">William Max Kusumo membentuk sebuah komunitas relawan pendidikan di Surabaya, Indonesia.</p>
          </div>
      </li>
      <li class="relative content-center mb-6 sm:mb-0">
          <div class="flex items-center ">
              <div class="z-10 flex items-center justify-center w-6 h-6 bg-blue-100 rounded-full ring-0 ring-white dark:bg-blue-900 sm:ring-8 dark:ring-gray-900 shrink-0">
                  <svg class="w-2.5 h-2.5 text-blue-800 dark:text-blue-300" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                      <path d="M20 4a2 2 0 0 0-2-2h-2V1a1 1 0 0 0-2 0v1h-3V1a1 1 0 0 0-2 0v1H6V1a1 1 0 0 0-2 0v1H2a2 2 0 0 0-2 2v2h20V4ZM0 18a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V8H0v10Zm5-8h10a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Z"/>
                  </svg>
              </div>
          </div>
          <div class="mt-3 sm:pr-8">
              <h3 class="text-lg font-semibold text-gray-900 dark:text-white">Mengajar Anak Jalanan</h3>
              <time class="block mb-2 text-sm font-normal leading-none text-gray-400 dark:text-gray-500">Sejak [Bulan, Tahun]</time>
              <p class="text-base font-normal text-gray-500 dark:text-gray-400">Memberikan tempat alternatif untuk belajar matematika, Bahasa Indonesia, Bahasa Inggris, Bahasa mandarin, dan memasak.</p>
          </div>
      </li>
      <li class="relative content-center mb-6 sm:mb-0">
          <div class="flex items-center ">
              <div class="z-10 flex items-center justify-center w-6 h-6 bg-blue-100 rounded-full ring-0 ring-white dark:bg-blue-900 sm:ring-8 dark:ring-gray-900 shrink-0">
                  <svg class="w-2.5 h-2.5 text-blue-800 dark:text-blue-300" aria-hidden="true" xmlns="http://www.w3.org/2000/svg" fill="currentColor" viewBox="0 0 20 20">
                      <path d="M20 4a2 2 0 0 0-2-2h-2V1a1 1 0 0 0-2 0v1h-3V1a1 1 0 0 0-2 0v1H6V1a1 1 0 0 0-2 0v1H2a2 2 0 0 0-2 2v2h20V4ZM0 18a2 2 0 0 0 2 2h16a2 2 0 0 0 2-2V8H0v10Zm5-8h10a1 1 0 0 1 0 2H5a1 1 0 0 1 0-2Z"/>
                  </svg>
              </div>
          </div>
          <div class="mt-3 sm:pr-8">
              <h3 class="text-lg font-semibold text-gray-900 dark:text-white">Kita bantu lebih banyak anak bersama yuk</h3>
              <time class="block mb-2 text-sm font-normal leading-none text-gray-400 dark:text-gray-500">Mulailah HARI INI!</time>
              <p class="text-base font-normal text-gray-500 dark:text-gray-400">Semoga kedepannya akan ada kelas tambahan yang mengajar bidang – bidang lainnya.</p>
          </div>
      </li>
    </ol>
  </div>
</div>




