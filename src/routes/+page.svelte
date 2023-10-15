<script>
  import Navbar from "../lib/components/+Navbar.svelte";
  import Hero from "../lib/components/+Hero.svelte";
  import About from "../lib/components/+About.svelte"
  // import Gallery from "../lib/components/+Gallery.svelte";
  import Belajar from "../lib/components/+Belajar.svelte";
  import Contrib from "../lib/components/+Contribute.svelte";
  import Footer from "../lib/components/+Footer.svelte";
</script>

<head>
  <title>Senyum Pelangi</title>
</head>

<Navbar />

<main>
  <section id="hero">
    <Hero />
  </section>

  <section id="about">
    <About />
  </section>
<!-- 
  <section id="gallery">
    <Gallery />
  </section> -->

  <section id="belajar">
    <Belajar />
  </section>

  <section id="contribute">
    <Contrib />
  </section>

  <section id="Footer">
    <Footer />
  </section>

 
</main>
