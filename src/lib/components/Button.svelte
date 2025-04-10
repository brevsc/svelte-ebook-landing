<script lang="ts">
  let {children, ...props} = $props();
</script>

<button {...props}>{@render children()}</button>

<style>
  button {
    background-color: #000000;
    color: #ffffff;
    padding: 20px 24px;
    font-weight: normal;
    font-size: 22px;
    text-transform: uppercase;
    transition: all 0.3s;
    border: 1px solid #ffffff;
    &:hover {
      background-color: #ffffff;
      color: #000000;
    }
  }
</style>