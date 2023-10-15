<script>
  import { Carousel, Thumbnails } from 'flowbite-svelte';
  import { images } from './static';

  let index = 0;
  let forward = true; // sync animation direction between Thumbnails and Carousel
</script>

<div class="max-w-4xl space-y-4">
  <Carousel {images} {forward} let:Indicators let:Controls bind:index>
    <Controls />
    <Indicators />
  </Carousel>
  <Thumbnails {images} {forward} bind:index />
</div>