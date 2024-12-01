<script>
  function greet() {
    alert('Welcome to Svelte!');
  }
</script>

<form x-on:submit.prevent class="items-center justify-center gap-x-3 sm:flex">
  <a
    href="/upload/"
    class="flex items-center justify-center gap-x-1 rounded-2xl bg-sky-500 px-9 py-4 text-3xl font-medium text-white duration-150 hover:bg-sky-400 active:bg-sky-600 md:inline-flex md:text-4xl"
  >
    Upload CV
    <svg
      xmlns="http://www.w3.org/2000/svg"
      viewBox="0 0 20 20"
      fill="currentColor"
      class="h-5 w-5"
    >
      <path
        fill-rule="evenodd"
        d="M7.21 14.77a.75.75 0 01.02-1.06L11.168 10 7.23 6.29a.75.75 0 111.04-1.08l4.5 4.25a.75.75 0 010 1.08l-4.5 4.25a.75.75 0 01-1.06-.02z"
        clip-rule="evenodd"
      />
    </svg>
  </a>
</form>
<p>or</p>
<h2>Fill the form</h2>

<style>
  button {
    font-size: 2em;
  }
</style>
