<template>
  <footer class="text-gray-700 text-sm leading-normal flex flex-wrap justify-between mx-auto px-6 sm:px-12 bg-blue-900">
    <div class="w-full sm:w-1/2 mb-4 sm:mb-0 text-white">
      <p>
        <a href="https://github.com/cossssmin/gridsome-starter-bleda" class="border-b border-transparent hover:border-gray-400 transition-border-color">Fixathon.io </a> by <a href="https://twitter.com/fixathon" class="border-b border-transparent hover:border-gray-400 transition-border-color">@fixathon</a> & ImpactMakers <a href="https://twitter.com/_impactMakers" class="border-b border-transparent hover:border-gray-400 transition-border-color">@_impactMakers</a>
      </p>
    </div>
    <div class="w-full sm:w-1/2 text-white">
      <nav>
        <ul class="flex sm:justify-end -mx-2">
          <li class="px-2">
            <g-link to="/" class="border-b border-transparent hover:border-gray-400 transition-border-color">Home</g-link>
          </li>
          <li class="px-2">
            <g-link to="/about/" class="border-b border-transparent hover:border-gray-400 transition-border-color">About</g-link>
          </li>
          <li class="px-2">
            <g-link to="https://fixathon.io" class="border-b border-transparent hover:border-gray-400 transition-border-color">The Fixathon</g-link>
          </li>
          <li class="px-2">
            <a href="/feed.xml" class="border-b border-transparent hover:border-gray-400 transition-border-color">RSS Feed</a>
          </li>
        </ul>
      </nav>
    </div>
  </footer>
</template>

<script>

export default {
  name: 'Footer',
}
</script>
