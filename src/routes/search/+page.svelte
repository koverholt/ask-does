<script lang="ts">
  import { Heading, Button } from 'flowbite-svelte';
  import { Navbar, NavBrand, NavLi, NavUl, NavHamburger } from 'flowbite-svelte';
</script>

<div>
  <script src="https://cloud.google.com/ai/gen-app-builder/client"></script>
  <gen-search-widget
    configId="acbfa948-3f08-4275-a651-609ce9be02b1"
    triggerId="searchWidgetTrigger">
  </gen-search-widget>

  <style>
    .grecaptcha-badge { visibility: hidden; }
  </style>

  <Button color="yellow" id="searchWidgetTrigger" hidden>Open Search Widget</Button>
  <script>
    document.getElementById("searchWidgetTrigger").click();
  </script>
</div>
