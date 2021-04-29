<script>
	import Tailwindcss from './Tailwindcss.svelte';

	export let name;
</script>

<Tailwindcss />
<nav class="bg-blue-900 shadow-lg">
  <div class="container mx-auto">
    <div class="sm:flex">
      <a href="#" class="text-white text-3xl font-bold p-3">APP LOGO</a>
      
      <!-- Menus -->
      <div class="ml-55 mt-4">
        <ul class="text-white sm:self-center text-xl">
          <li class="sm:inline-block">
            <a href="#" class="p-3 hover:text-red-900">About</a>
          </li>
          <li class="sm:inline-block">
            <a href="#" class="p-3 hover:text-red-900">Services</a>
          </li>
          <li class="sm:inline-block">
            <a href="#" class="p-3 hover:text-red-900">Blog</a>
          </li>
          <li class="sm:inline-block">
            <a href="#" class="p-3 hover:text-red-900">Contact</a>
          </li>
        </ul>
      </div>

    </div>
  </div>
</nav>

<div class="p-6 max-w-sm mx-auto bg-white rounded-xl shadow-md flex items-center space-x-4">
  <div class="flex-shrink-0">
    <img class="h-12 w-12" src="./favicon.png" alt="ChitChat Logo">
  </div>
  <div>
    <div class="text-xl font-medium text-black">test</div>
    <p class="text-gray-500">Does this work?</p>
  </div>
</div>
