<script setup>
import logo from './assets/sjie-logo.jpg'

</script>
<template>
  <div>
    <header class="bg-white shadow">
      <div class="mx-auto max-w-7xl px-4 py-6 sm:px-6 lg:px-8 flex place-content-between">
        <div><img :src="logo" class="w-24" /></div>
        <h1 class="text-3xl font-bold leading-tight text-gray-900 text-right place-self-end">
          Shravani Jhajharia Institute of Education, Singhana
        </h1>
      </div>
    </header>
    
				
				<!--Nav-->
          <nav class="mt-0 w-full bg-orange-200">
            <div class="container w-full mx-auto flex items-center">
              
              <div class="flex pl-4 text-md">
                <ul class="list-reset flex justify-between flex-1 md:flex-none place-items-end">
                  <li class="mr-2">
                  <a class="inline-block text-gray-600 no-underline hover:text-gray-200 hover:underline py-2 px-2" href="#">LINK</a>
                  </li>
                  <li class="mr-2">
                  <a class="inline-block text-gray-600 no-underline hover:text-gray-200 hover:underline py-2 px-2" href="#">LINK</a>
                  </li>
                  <li class="mr-2">
                  <a class="inline-block text-gray-600 no-underline hover:text-gray-200 hover:underline py-2 px-2" href="post_vue.html">POST_VUE</a>
                  </li>
                  <li class="mr-2">
                  <a class="inline-block text-gray-600 no-underline hover:text-gray-200 hover:underline py-2 px-2" href="#">LINK</a>
                  </li>
                  <li class="mr-2">
                  <a class="inline-block text-gray-600 no-underline hover:text-gray-200 hover:underline py-2 px-2" href="#">LINK</a>
                  </li>
                  <li class="mr-2">
                  <a class="inline-block text-gray-600 no-underline hover:text-gray-200 hover:underline py-2 px-2" href="post_vue.html">POST_VUE</a>
                  </li>
                </ul>
              </div>
            </div>
          </nav>
       
    <main>
      <router-view />
    </main>
    <footer class="bg-gray-900">	
		<div class="container max-w-6xl mx-auto flex items-center px-2 py-8">

			<div class="w-full mx-auto flex flex-wrap items-center">
				<div class="flex w-full md:w-1/2 justify-center md:justify-start text-white font-extrabold">
					<a class="text-gray-900 no-underline hover:text-gray-900 hover:no-underline" href="#">
						 <span class="text-base text-gray-200">&copy; Shravani Jhajharia Institute of Education</span>
					</a>
				</div>
				<div class="flex w-full pt-2 content-center justify-between md:w-1/2 md:justify-end">
					<ul class="list-reset flex justify-center flex-1 md:flex-none items-center">
					  <li>
						<a class="inline-block py-2 px-3 text-white no-underline" href="#">Active</a>
					  </li>
					  <li>
						<a class="inline-block text-gray-600 no-underline hover:text-gray-200 hover:underline py-2 px-3" href="#">link</a>
					  </li>
					  <li>
						<a class="inline-block text-gray-600 no-underline hover:text-gray-200 hover:underline py-2 px-3" href="#">link</a>
					  </li>
						<li>
						<a class="inline-block text-gray-600 no-underline hover:text-gray-200 hover:underline py-2 px-3" href="#">link</a>
					  </li>
					</ul>
				</div>
			</div>
        

		
		</div>
	</footer>
  </div>
</template>
