<script>
	import TodoCard from "./TodoCard.svelte";
</script>

<div class="container is-fluid">
	<h1 class="is-size-3">Todp App</h1>
	<div class="columns">
		<div class="column is-4">
			<div class="card has-background-light">
				<div class="card-header">
					<p class="card-header-title">Tasks</p>
				</div>
				<div class="card-content">
					<TodoCard content={"Belajar HTML"} >
					<TodoCard content={"Belajar CSS"} >
					<TodoCard content={"Belajar JavaScript"} >
				</div>
			</div>
		</div>
	</div>
</div>

<svelte:head>
	<link rel="stylesheet" href="/bulma.min.css" />
</svelte:head>
