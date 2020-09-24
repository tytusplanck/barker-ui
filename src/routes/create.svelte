<script lang="ts">
	let dogName;
	let dogBreed;

	function create() {
		console.log({'dogName': this.dogName, 'dogBreed': this.dogBreed});
	}
</script>

<svelte:head>
	<title>Create</title>
</svelte:head>

<h1>Let's create a new Dog for You!</h1>

<form>
    <div>
      <input bind:value={dogName} type="text" name="dogname" placeholder="Dog's Name" />
    </div>
    <div>
      <input bind:value={dogBreed} type="text" name="breed" placeholder="Dog Breed" />
    </div>
    <div>
      <button on:click={create}>Create Dog</button>
    </div>
  </form>