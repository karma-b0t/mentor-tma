<script>
  let open = false;

  function toggleMenu() {
    open = !open;
  }
</script>

<div class="min-h-screen place-content-center bg-gray-900">
  <section class="relative">
    <div class="relative z-10 mx-auto max-w-screen-xl px-4 py-28 md:px-8">
      <div class="mx-auto max-w-4xl space-y-10 text-center">
        <h2 class="mx-auto text-3xl font-extrabold text-white md:text-4xl">
          This bot helps you find an IT mentor
        </h2>
        <h2 class="mx-auto text-3xl font-extrabold text-white md:text-4xl">
          Upload your CV or fill out a form, and <span
            class="underline decoration-indigo-500 decoration-4">AI</span
          > will select the perfect mentor for you
        </h2>

        <form
          x-on:submit.prevent
          class="items-center justify-center gap-x-3 sm:flex"
        >
          <a
            href="/upload/"
            class="flex items-center justify-center gap-x-1 rounded-2xl bg-sky-500 px-9 py-4 text-3xl font-medium text-white duration-150 hover:bg-sky-400 active:bg-sky-600 md:inline-flex md:text-4xl"
          >
            START
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
        <div
          class="flex items-center justify-center gap-x-4 text-sm text-gray-400"
        >
          <div class="flex">
            <svg
              class="h-5 w-5"
              xmlns="http://www.w3.org/2000/svg"
              fill="currentColor"
              viewBox="0 0 20 20"
            >
              <path
                d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z"
              />
            </svg>
            <svg
              class="h-5 w-5"
              xmlns="http://www.w3.org/2000/svg"
              fill="currentColor"
              viewBox="0 0 20 20"
            >
              <path
                d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z"
              />
            </svg>
            <svg
              class="h-5 w-5"
              xmlns="http://www.w3.org/2000/svg"
              fill="currentColor"
              viewBox="0 0 20 20"
            >
              <path
                d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z"
              />
            </svg>
            <svg
              class="h-5 w-5"
              xmlns="http://www.w3.org/2000/svg"
              fill="currentColor"
              viewBox="0 0 20 20"
            >
              <path
                d="M10.868 2.884c-.321-.772-1.415-.772-1.736 0l-1.83 4.401-4.753.381c-.833.067-1.171 1.107-.536 1.651l3.62 3.102-1.106 4.637c-.194.813.691 1.456 1.405 1.02L10 15.591l4.069 2.485c.713.436 1.598-.207 1.404-1.02l-1.106-4.637 3.62-3.102c.635-.544.297-1.584-.536-1.65l-4.752-.382-1.831-4.401z"
              />
            </svg>
          </div>
          <p><span class="text-gray-100">5.0</span> by over 200 users</p>
        </div>
      </div>
    </div>
    <div
      class="absolute inset-0 m-auto h-[357px] max-w-xs blur-[118px] sm:max-w-md md:max-w-lg"
      style="
          background: linear-gradient(
            106.89deg,
            rgba(192, 132, 252, 0.11) 15.73%,
            rgba(14, 165, 233, 0.41) 15.74%,
            rgba(232, 121, 249, 0.26) 56.49%,
            rgba(79, 70, 229, 0.4) 115.91%
          );
        "
    ></div>
  </section>
</div>
