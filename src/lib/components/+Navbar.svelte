<script>
  import { Navbar, NavBrand, NavLi, NavUl, NavHamburger, Button, Input } from 'flowbite-svelte';
</script>

<Navbar>
  <NavBrand href="#Hero">
    <img src="/images/flowbite-svelte-icon-logo.svg" class="sm:mr-3 h-6 sm:h-9" alt="Flowbite Logo" />
    <span class="hidden sm:block viself-center whitespace-nowrap text-xl font-semibold dark:text-white">Senyum Pelangi</span>
  </NavBrand>
  <NavHamburger />
  <NavUl class="order-1">
    <NavLi href="#about" active={true}>About</NavLi>
    <NavLi href="#belajar">Belajar</NavLi>
    <NavLi href="#contribute">Berbagi</NavLi>
    <NavLi href="/pricing">Tim Kami</NavLi>
  </NavUl>
</Navbar>