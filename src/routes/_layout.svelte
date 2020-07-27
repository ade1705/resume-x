<script>
	import Nav from '../components/Nav.svelte';

	export let segment;
</script>

<Nav {segment}/>

<div class="bg-blue-100">
    <div class="container mx-auto">
      <main>
        <slot></slot>
      </main>
    </div>
</div>
