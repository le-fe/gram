<template>
	<div class="container m-auto pt-5">
		<h1 class="font-semibold lg:mb-6 mb-3 text-2xl">Messages</h1>

		<div
			class="lg:flex lg:shadow lg:bg-white lg:space-y-0 space-y-8 rounded-md lg:-mx-0 -mx-5 overflow-hidden lg:dark:bg-gray-800"
		>
			<!-- left message-->
			<div class="lg:w-4/12 bg-white border-r overflow-hidden dark:bg-gray-800 dark:border-gray-600">
				<!-- search-->
				<div class="border-b px-4 py-4 dark:border-gray-600">
					<div class="bg-gray-100 input-with-icon rounded-md dark:bg-gray-700">
						<input id="autocomplete-input" type="text" placeholder="Search" class="bg-transparent max-h-10 shadow-none" />
						<i class="icon-material-outline-search"></i>
					</div>
				</div>

				<!-- user list-->
				<div class="pb-16 w-full">
					<ul class="dark:text-gray-100">
						<li>
							<a href="#" class="block flex items-center py-3 px-4 space-x-3 hover:bg-gray-100 dark:hover:bg-gray-700">
								<div class="w-12 h-12 rounded-full relative flex-shrink-0">
									<img src="/img/avatar-2.jpeg" alt="" class="absolute h-full rounded-full w-full" />
									<span
										class="absolute bg-green-500 border-2 border-white bottom-0 h-3 m-0.5 right-0 rounded-full shadow-md w-3"
									></span>
								</div>
								<div class="flex-1 min-w-0 relative text-gray-500">
									<h4 class="text-black font-semibold dark:text-white">David Peterson</h4>
									<span class="absolute right-0 top-1 text-xs">Sun</span>
									<p class="truncate">Esmod tincidunt ut laoreet</p>
								</div>
							</a>
						</li>
						<li>
							<a href="#" class="block flex items-center py-3 px-4 space-x-3 bg-gray-100 dark:bg-gray-700">
								<div class="w-12 h-12 rounded-full relative flex-shrink-0">
									<img src="/img/avatar-1.jpeg" alt="" class="absolute h-full rounded-full w-full" />
									<span
										class="absolute bg-green-500 border-2 border-white bottom-0 h-3 m-0.5 right-0 rounded-full shadow-md w-3"
									></span>
								</div>
								<div class="flex-1 min-w-0 relative text-gray-500">
									<h4 class="text-black font-semibold dark:text-white">Sindy Forest</h4>
									<span class="absolute right-0 top-1 text-xs"> Mon</span>
									<p class="truncate">Seddiam nonummy nibh euismod laoreet</p>
								</div>
							</a>
						</li>
						<li>
							<a href="#" class="block flex items-center py-3 px-4 space-x-3 hover:bg-gray-100 dark:hover:bg-gray-700">
								<div class="w-12 h-12 rounded-full relative flex-shrink-0">
									<img src="/img/avatar-5.jpeg" alt="" class="absolute h-full rounded-full w-full" />
									<span
										class="absolute bg-gray-300 border-2 border-white bottom-0 h-3 m-0.5 right-0 rounded-full shadow-md w-3"
									></span>
								</div>
								<div class="flex-1 min-w-0 relative text-gray-500">
									<h4 class="text-black font-semibold dark:text-white">Zara Ali</h4>
									<span class="absolute right-0 top-1 text-xs">4 hours ago</span>
									<p class="truncate">Consectetuer adiscing elit</p>
								</div>
							</a>
						</li>
						<li>
							<a href="#" class="block flex items-center py-3 px-4 space-x-3 hover:bg-gray-100 dark:hover:bg-gray-700">
								<div class="w-12 h-12 rounded-full relative flex-shrink-0">
									<img src="/img/avatar-4.jpeg" alt="" class="absolute h-full rounded-full w-full" />
									<span
										class="absolute bg-green-500 border-2 border-white bottom-0 h-3 m-0.5 right-0 rounded-full shadow-md w-3"
									></span>
								</div>
								<div class="flex-1 min-w-0 relative text-gray-500">
									<h4 class="text-black font-semibold dark:text-white">David Peterson</h4>
									<span class="absolute right-0 top-1 text-xs">Week ago</span>
									<p class="truncate">Nam liber tempor <i class="uil-grin-tongue-wink"></i></p>
								</div>
							</a>
						</li>
						<li>
							<a href="#" class="block flex items-center py-3 px-4 space-x-3 hover:bg-gray-100 dark:hover:bg-gray-700">
								<div class="w-12 h-12 rounded-full relative flex-shrink-0">
									<img src="/img/avatar-2.jpeg" alt="" class="absolute h-full rounded-full w-full" />
									<span
										class="absolute bg-green-500 border-2 border-white bottom-0 h-3 m-0.5 right-0 rounded-full shadow-md w-3"
									></span>
								</div>
								<div class="flex-1 min-w-0 relative text-gray-500">
									<h4 class="text-black font-semibold dark:text-white">David Peterson</h4>
									<span class="absolute right-0 top-1 text-xs">Week ago</span>
									<p class="truncate">Esmod tincidunt ut laoreet</p>
								</div>
							</a>
						</li>
					</ul>
				</div>
			</div>

			<!--  message-->
			<div class="lg:w-8/12 bg-white dark:bg-gray-800">
				<div class="px-5 py-4 flex uk-flex-between">
					<a href="#" class="flex items-center space-x-3">
						<div class="w-10 h-10 rounded-full relative flex-shrink-0">
							<img src="/img/avatar-1.jpeg" alt="" class="h-full rounded-full w-full" />
							<span
								class="absolute bg-green-500 border-2 border-white bottom-0 h-3 m-0.5 right-0 rounded-full shadow-md w-3"
							></span>
						</div>
						<div class="flex-1 min-w-0 relative text-gray-500">
							<h4 class="font-semibold text-black text-lg">Sindy Forest</h4>

							<p class="font-semibold leading-3 text-green-500 text-sm">is online</p>
						</div>
					</a>

					<a href="#" class="flex hover:text-red-400 items-center leading-8 space-x-2 text-red-500 font-medium">
						<i class="uil-trash-alt"></i> <span class="lg:block hidden"> Delete Conversation </span>
					</a>
				</div>

				<div class="border-t dark:border-gray-600">
					<div class="lg:p-8 p-4 space-y-5">
						<h3 class="lg:w-60 mx-auto text-sm uk-heading-line uk-text-center lg:pt-2"><span> 28 June, 2018 </span></h3>

						<!-- my message-->
						<div class="flex lg:items-center flex-row-reverse">
							<div class="w-14 h-14 rounded-full relative flex-shrink-0">
								<img src="/img/avatar-2.jpeg" alt="" class="absolute h-full rounded-full w-full" />
							</div>
							<div class="text-white py-2 px-3 rounded bg-blue-600 relative h-full lg:mr-5 mr-2 lg:ml-20">
								<p class="leading-6">
									consectetuer adipiscing elit, sed diam nonummy nibh euismod laoreet dolore magna
									<i class="uil-grin-tongue-wink"></i>
								</p>
								<div class="absolute w-3 h-3 top-3 -right-1 bg-blue-600 transform rotate-45"></div>
							</div>
						</div>

						<h3 class="lg:w-60 mx-auto text-sm uk-heading-line uk-text-center lg:pt-2"><span> 28 June, 2018 </span></h3>

						<div class="flex lg:items-center">
							<div class="w-14 h-14 rounded-full relative flex-shrink-0">
								<img src="/img/avatar-1.jpeg" alt="" class="absolute h-full rounded-full w-full" />
							</div>
							<div
								class="text-gray-700 py-2 px-3 rounded bg-gray-100 h-full relative lg:ml-5 ml-2 lg:mr-20 dark:bg-gray-700 dark:text-white"
							>
								<p class="leading-6">
									In ut odio libero vulputate <urna class="i uil-heart"></urna> <i class="uil-grin-tongue-wink"> </i>
								</p>
								<div class="absolute w-3 h-3 top-3 -left-1 bg-gray-100 transform rotate-45 dark:bg-gray-700"></div>
							</div>
						</div>

						<!-- my message-->
						<div class="flex lg:items-center flex-row-reverse">
							<div class="w-14 h-14 rounded-full relative flex-shrink-0">
								<img src="/img/avatar-2.jpeg" alt="" class="absolute h-full rounded-full w-full" />
							</div>
							<div class="text-white py-2 px-3 rounded bg-blue-600 relative h-full lg:mr-5 mr-2 lg:ml-20">
								<p class="leading-6">
									Nam liber tempor cum soluta nobis eleifend option <i class="uil-grin-tongue-wink-alt"></i>
								</p>
								<div class="absolute w-3 h-3 top-3 -right-1 bg-blue-600 transform rotate-45"></div>
							</div>
						</div>

						<h3 class="lg:w-60 mx-auto text-sm uk-heading-line uk-text-center lg:pt-2"><span> 28 June, 2018 </span></h3>
						<div class="flex lg:items-center flex-row-reverse">
							<div class="w-14 h-14 rounded-full relative flex-shrink-0">
								<img src="/img/avatar-2.jpeg" alt="" class="absolute h-full rounded-full w-full" />
							</div>
							<div class="text-white py-2 px-3 rounded bg-blue-600 relative h-full lg:mr-5 mr-2 lg:ml-20">
								<p class="leading-6">consectetuer adipiscing elit, sed diam nonummy nibh euismod laoreet dolore magna.</p>
								<div class="absolute w-3 h-3 top-3 -right-1 bg-blue-600 transform rotate-45"></div>
							</div>
						</div>

						<h3 class="lg:w-60 mx-auto text-sm uk-heading-line uk-text-center lg:pt-2"><span> 28 June, 2018 </span></h3>

						<div class="flex lg:items-center">
							<div class="w-14 h-14 rounded-full relative flex-shrink-0">
								<img src="/img/avatar-1.jpeg" alt="" class="absolute h-full rounded-full w-full" />
							</div>
							<div
								class="text-gray-700 py-2 px-3 rounded bg-gray-100 relative h-full lg:ml-5 ml-2 lg:mr-20 dark:bg-gray-700 dark:text-white"
							>
								<p class="leading-6">Nam liber tempor cum soluta nobis eleifend option congue nihil imperdiet doming</p>
								<div class="absolute w-3 h-3 top-3 -left-1 bg-gray-100 transform rotate-45 dark:bg-gray-700"></div>
							</div>
						</div>

						<!-- my message-->

						<div class="flex lg:items-center flex-row-reverse">
							<div class="w-14 h-14 rounded-full relative flex-shrink-0">
								<img src="/img/avatar-2.jpeg" alt="" class="absolute h-full rounded-full w-full" />
							</div>
							<div class="text-white py-2 px-3 rounded bg-blue-600 relative h-full lg:mr-5 mr-2 lg:ml-20">
								<p class="leading-6">quis nostrud exerci tation ullamcorper suscipit .</p>
								<div class="absolute w-3 h-3 top-3 -right-1 bg-blue-600 transform rotate-45"></div>
							</div>
						</div>

						<div class="flex lg:items-center">
							<div class="w-14 h-14 rounded-full relative flex-shrink-0">
								<img src="/img/avatar-1.jpeg" alt="" class="absolute h-full rounded-full w-full" />
							</div>
							<div
								class="text-gray-700 py-2 px-3 rounded bg-gray-100 relative h-full lg:ml-5 ml-2 lg:mr-20 dark:bg-gray-700 dark:text-white"
							>
								<div class="flex space-x-0.5 my-2 animate-pulse">
									<div class="w-2 h-2 rounded-full bg-gray-400"></div>
									<div class="w-2 h-2 rounded-full bg-gray-300"></div>
									<div class="w-2 h-2 rounded-full bg-gray-300"></div>
								</div>
								<div class="absolute w-3 h-3 top-3 -left-1 bg-gray-100 transform rotate-45 dark:bg-gray-700"></div>
							</div>
						</div>
					</div>

					<div class="border-t flex p-6 dark:border-gray-700">
						<textarea
							cols="1"
							rows="1"
							placeholder="Your Message.."
							class="border-0 flex-1 h-10 min-h-0 resize-none min-w-0 shadow-none dark:bg-transparent"
						></textarea>
						<div class="flex h-full space-x-2">
							<button type="submit" class="bg-blue-600 font-semibold px-6 py-2 rounded-md text-white">Send</button>
						</div>
					</div>
				</div>
			</div>
		</div>
	</div>
</template>
