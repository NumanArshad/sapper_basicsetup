<script>
import { goto } from '@sapper/app';
 function nav(){
	alert("here")
   goto("/blog")
}



</script>


<svelte:head>
	<title>About</title>
</svelte:head>

<h1>About this site</h1>
<button on:click={nav}>d</button>
<p>This is the 'about' page. There's not much here.</p>