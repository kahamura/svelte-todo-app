<script>
  import ToDoInputForm from "./ToDoInputForm.svelte";

  let lastName = "田中";
  let firstName = "花子";

  $: fullName = lastName + " " + firstName;
</script>

<main>
  <ToDoInputForm userName={fullName} />
</main>

<style>
  main {
    text-align: center;
    padding: 1em;
    max-width: 450px;
    margin: 0 auto;
  }
</style>
