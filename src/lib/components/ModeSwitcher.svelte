<script lang="ts">
import { toggleMode } from "mode-watcher";
import { Button } from "$lib/components/ui/button/index.js";
</script>

<Button on:click={toggleMode} variant="outline" size="icon">
  <span
    class="h-[1.2rem] w-[1.2rem] rotate-0 scale-100 transition-all dark:-rotate-90 dark:scale-0"
  >
    🌞
  </span>
  <span
    class="absolute h-[1.2rem] w-[1.2rem] rotate-90 scale-0 transition-all dark:rotate-0 dark:scale-100"
    >🌙</span
  >
  <span class="sr-only">Toggle theme</span>
</Button>
