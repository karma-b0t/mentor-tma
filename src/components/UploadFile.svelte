<script>
  function greet() {
    alert('Welcome to Svelte!');
  }
</script>

<div class="min-h-screen place-content-center bg-gray-900">
  <form
    x-on:submit.prevent
    class="pitems-center justify-center gap-x-3 gap-y-4 sm:flex"
  >
    <div class="mx-auto max-w-4xl space-y-10 text-center">
      <label
        for="upload"
        class="mx-auto my-10 text-3xl font-extrabold text-white md:text-4xl"
      >
        Upload your CV
      </label>
      <input
        id="upload"
        type="file"
        class="file-input file-input-bordered file-input-info w-full max-w-xs"
      />
    </div>
  </form>
  <a
    href="/fill-out-the-form/"
    class=" flex items-center justify-center gap-x-1 rounded-2xl bg-sky-500 px-9 py-4 text-3xl font-medium text-white duration-150 hover:bg-sky-400 active:bg-sky-600 md:inline-flex md:text-4xl"
  >
    Fill out the Form
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

  <p>or</p>
  <h2>Fill the form</h2>
</div>

<style>
  button {
    font-size: 2em;
  }
</style>
