<script>
  function greet() {
    alert('Welcome to Svelte!');
  }
</script>

<div class="min-h-screen place-content-center bg-gray-900">
  <div class="flex w-full flex-col">
    <div class="card rounded-box grid">
      <form
        x-on:submit.prevent
        class="pitems-center justify-center gap-x-3 gap-y-4 sm:flex"
      >
        <div class="mx-auto max-w-4xl flex-col space-y-10 gap-y-4 text-center">
          <label
            for="upload"
            class="d-flex mx-auto my-10 mb-4 pb-4 text-3xl font-extrabold text-white md:text-4xl"
          >
            Upload your CV
          </label>
          <input
            id="upload"
            type="file"
            class="file-input file-input-bordered file-input-info mt-4 w-full max-w-xs"
          />
        </div>
      </form>
    </div>
    <div class="divider m-10 text-white">OR</div>
    <div class="card rounded-box grid">
      <a
        href="/fill-out-the-form/"
        class="btn btn-outline btn-info px-9 py-4 text-3xl font-medium text-white duration-150 hover:bg-sky-400 active:bg-sky-600 md:inline-flex md:text-4xl"
      >
        Fill out the Form
      </a>
    </div>
  </div>
</div>

<style>
  button {
    font-size: 2em;
  }
</style>
