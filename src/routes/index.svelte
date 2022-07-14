<script>
  import TodoItem from "../lib/todo-item.svelte";

  const pageTitle = "Todos";
</script>

<svelte:head>
  <title>{pageTitle}</title>
</svelte:head>

<h1>{pageTitle}</h1>

<form action="" method="">
  <input
    type="text"
    name="text"
    id=""
    aria-label="Add a Todo"
    placeholder="+ type to add a Todo"
  />
</form>

<TodoItem />
