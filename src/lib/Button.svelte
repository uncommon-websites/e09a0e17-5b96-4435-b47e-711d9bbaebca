<script lang="ts">
  export let type: 'primary' | 'secondary' | 'outline' | 'white' = 'primary';
  export let href: string | undefined = undefined;
  export let className = '';
</script>

{#if href}
  <a
    {href}
    class="inline-flex items-center justify-center px-6 py-3 rounded-full font-medium transition-transform active:scale-95 {className}
    {type === 'primary' ? 'bg-primary text-white hover:bg-primary-dark' : ''}
    {type === 'secondary' ? 'bg-dark text-white hover:bg-gray-800' : ''}
    {type === 'outline' ? 'border-2 border-dark bg-transparent hover:bg-gray-100' : ''}
    {type === 'white' ? 'bg-white text-dark hover:bg-gray-50 border border-gray-200' : ''}"
  >
    <slot />
  </a>
{:else}
  <button
    class="inline-flex items-center justify-center px-6 py-3 rounded-full font-medium transition-transform active:scale-95 {className}
    {type === 'primary' ? 'bg-primary text-white hover:bg-primary-dark' : ''}
    {type === 'secondary' ? 'bg-dark text-white hover:bg-gray-800' : ''}
    {type === 'outline' ? 'border-2 border-dark bg-transparent hover:bg-gray-100' : ''}
    {type === 'white' ? 'bg-white text-dark hover:bg-gray-50 border border-gray-200' : ''}"
  >
    <slot />
  </button>
{/if}
