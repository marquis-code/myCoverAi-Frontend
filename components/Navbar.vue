<template>
  <div class="">
    <header aria-label="Site Header" class="bg-gray-100 py-2">
      <div class="mx-auto container">
        <div class="flex h-16 items-center justify-between">
          <div class="md:flex md:items-center md:gap-12">
            <a class="block text-teal-600" href="/">
              <span class="sr-only">Home</span>

              <img src="@/static/img/logo.svg" />
            </a>
          </div>

          <div class="hidden md:block">
            <nav aria-label="Site Nav">
              <ul class="flex items-center gap-6 space-x-52">
                <div class="flex items-center space-x-5">
                  <li>
                    <a
                      class="text-gray-500 transition font-light hover:text-gray-500/75"
                      href="/"
                    >
                     For Individuals
                    </a>
                  </li>

                  <li>
                    <a
                      class="text-gray-500 transition font-light hover:text-gray-500/75"
                      href="/"
                    >
                      Plans
                    </a>
                  </li>
                </div>

                <div class="flex items-center space-x-5">
                  <li>
                    <a
                      class="text-gray-500 transition font-light hover:text-gray-500/75"
                      href="/"
                    >
                     Claims
                    </a>
                  </li>

                  <li>
                    <a
                      class="text-gray-500 transition font-light hover:text-gray-500/75"
                      href="/"
                    >
                     API
                    </a>
                  </li>

                  <li>
                    <a
                      class="text-gray-500 transition font-light hover:text-gray-500/75"
                      href="/"
                    >
                     Company
                    </a>
                  </li>
                </div>
              </ul>
            </nav>
          </div>

          <div class="flex items-center gap-4">
            <div class="sm:flex sm:gap-4">
              <a
                class="
                  rounded-md
                  py-2
                  text-sm
                  text-gray-500
                  bg-gray-200
                    px-4
                  font-light
                "
                href="/"
              >
                Login
              </a>

              <div class="hidden sm:flex">
                <a
                  class="
                    rounded-md
                    bg-gray-10
                    py-2
                    px-4
                    text-sm
                    text-white
                    bg-teal-600
                    font-light
                  "
                  href="/"
                >
                 Get Covered
                </a>
              </div>
            </div>

            <div class="block md:hidden">
              <button
                class="
                  rounded
                  bg-gray-100
                  p-2
                  text-gray-600
                  transition
                  hover:text-gray-600/75
                "
              >
                <svg
                  xmlns="http://www.w3.org/2000/svg"
                  class="h-5 w-5"
                  fill="none"
                  viewBox="0 0 24 24"
                  stroke="currentColor"
                  stroke-width="2"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    d="M4 6h16M4 12h16M4 18h16"
                  />
                </svg>
              </button>
            </div>
          </div>
        </div>
      </div>
    </header>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
button {
  background-color: #439687;
  border: none;
  outline: none;
}
</style>
