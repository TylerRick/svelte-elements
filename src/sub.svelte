<script>
  import { subscribe } from './utils';

  export let el = undefined;
  export let listen = undefined;
</script>

<sub bind:this={el} on:focus on:blur on:keypress on:click use:subscribe={listen} {...$$restProps}><slot /></sub>
