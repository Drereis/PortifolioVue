<template>
  <nav class="bg-zinc-800">
    <div class="mx-auto max-w-7xl px-2 sm:px-6 lg:px-8">
      <div class="relative flex h-16 items-center justify-between">
        <div class="absolute inset-y-0 left-0 flex items-center sm:hidden">
        </div>
        <div
          class="flex flex-1 items-center justify-center sm:items-stretch sm:justify-start"
        >
          <div class="flex shrink-0 items-center">
            <img
              class="h-8 w-auto"
              src="https://tailwindcss.com/plus-assets/img/logos/mark.svg?color=indigo&shade=500"
              alt="Your Company"
            />
          </div>
          <div class="hidden sm:ml-6 sm:block">
            <div class="flex space-x-4">
              <ul class="flex gap-6">
                <li>
                  <router-link
                    to="/"
                    class="rounded-md px-3 py-2 text-sm font-medium text-purple-700 hover:bg-purple-700 hover:text-black"
                    >Tela inicial</router-link
                  >
                </li>
                <li>
                  <router-link
                    to="/about"
                    id=""class="rounded-md px-3 py-2 text-sm font-medium text-purple-700 hover:bg-purple-700 hover:text-black"
                    >Sobre</router-link
                  >
                </li>
                <li>
                  <router-link
                    to="/contact"
                    class="rounded-md px-3 py-2 text-sm font-medium text-purple-700 hover:bg-purple-700 hover:text-black"
                    >Contato</router-link
                  >
                </li>
              </ul>
            </div>
          </div>
        </div>
        <div
          class="absolute inset-y-0 right-0 flex items-center pr-2 sm:static sm:inset-auto sm:ml-6 sm:pr-0"
        >
          <button
            type="button"
            class="relative rounded-full bg-black p-1 text-gray-700 hover:text-purple-700 focus:ring-2 focus:ring-purple-700 focus:ring-offset-2 focus:ring-offset-purple-700 focus:outline-hidden"
          >
            <span class="absolute -inset-1.5"></span>
            <span class="sr-only">View notifications</span>
            <svg
              class="size-6"
              fill="none"
              viewBox="0 0 24 24"
              stroke-width="1.5"
              stroke="currentColor"
              aria-hidden="true"
              data-slot="icon"
            >
              <path
                stroke-linecap="round"
                stroke-linejoin="round"
                d="M14.857 17.082a23.848 23.848 0 0 0 5.454-1.31A8.967 8.967 0 0 1 18 9.75V9A6 6 0 0 0 6 9v.75a8.967 8.967 0 0 1-2.312 6.022c1.733.64 3.56 1.085 5.455 1.31m5.714 0a24.255 24.255 0 0 1-5.714 0m5.714 0a3 3 0 1 1-5.714 0"
              />
            </svg>
          </button>

         
          <div class="relative ml-3">
            <div>
              <button
                type="button"
                 class="relative rounded-full bg-black p-1 text-gray-700 hover:text-purple-700 focus:ring-2 focus:ring-purple-700 focus:ring-offset-2 focus:ring-offset-purple-700 focus:outline-hidden"
                id="user-menu-button"
                aria-expanded="false"
                aria-haspopup="true"
              >
                <span class="absolute -inset-1.5"></span>
                <span class="sr-only">Open user menu</span>
                <img
                  class="size-8 rounded-full"
                  src="https://imagesash.cot-1472099645785-5658abf4ff4e?ixlib=rb-1.2.1&ixid=eyJhcHBfaWQiOjEyMDd9&auto=format&fit=facearea&facepad=2&w=256&h=256&q=80"
                  alt=""
                />
              </button>
            </div>
        </div>
      </div>
    </div>
    </div>
  </nav>
</template>
