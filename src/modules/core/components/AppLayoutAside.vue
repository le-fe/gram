<template>
	<div class="sidebar">
		<div class="sidebar_header border-b border-gray-200 from-gray-100 to-gray-50 bg-gradient-to-t  uk-visible@s">
			<a href="#">
				<img src="/img/logo.png" />
				<img src="/img/logo-light.png" class="logo_inverse" />
			</a>
			<!-- btn night mode -->
			<a
				href="#"
				id="night-mode"
				class="btn-night-mode"
				data-tippy-placement="left"
				data-tippy=""
				data-original-title="Switch to dark mode"
			></a>
		</div>
		<div class="border-b border-gray-20 flex justify-between items-center p-3 pl-5 relative uk-hidden@s">
			<h3 class="text-xl">Navigation</h3>
			<span class="btn-mobile" uk-toggle="target: #wrapper ; cls: sidebar-active"></span>
		</div>
		<div class="sidebar_inner" data-simplebar="init">
			<div class="simplebar-wrapper" style="margin: -5px -13px;">
				<div class="simplebar-height-auto-observer-wrapper"><div class="simplebar-height-auto-observer"></div></div>
				<div class="simplebar-mask">
					<div class="simplebar-offset" style="right: 0px; bottom: -17px;">
						<div class="simplebar-content" style="padding: 5px 13px; height: 100%; overflow: scroll hidden;">
							<div class="flex flex-col items-center my-6 uk-visible@s">
								<div class="bg-gradient-to-tr from-yellow-600 to-pink-600 p-1 rounded-full transition m-0.5 mr-2  w-24 h-24">
									<img
										src="/img/avatar-2.jpeg"
										class="bg-gray-200 border-4 border-white rounded-full w-full h-full"
									/>
								</div>
								<a href="profile.html" class="text-xl font-medium capitalize mt-4 uk-link-reset"> Stella Johnson </a>
								<div class="flex justify-around w-full items-center text-center uk-link-reset text-gray-800 mt-6">
									<div>
										<a href="#">
											<strong>Post</strong>
											<div>130</div>
										</a>
									</div>
									<div>
										<a href="#">
											<strong>Following</strong>
											<div>1,230</div>
										</a>
									</div>
									<div>
										<a href="#">
											<strong>Followers</strong>
											<div>2,430</div>
										</a>
									</div>
								</div>
							</div>
							<hr class="-mx-4 -mt-1 uk-visible@s" />
							<ul>
								<li class="active">
									<router-link :to="{ name: 'FeedView' }">
										<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
											<path
												stroke-linecap="round"
												stroke-linejoin="round"
												stroke-width="2"
												d="M4 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2V6zM14 6a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2V6zM4 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2H6a2 2 0 01-2-2v-2zM14 16a2 2 0 012-2h2a2 2 0 012 2v2a2 2 0 01-2 2h-2a2 2 0 01-2-2v-2z"
											></path>
										</svg>
										<span> Feed </span>
									</router-link>
								</li>
								<li>
									<router-link :to="{ name: 'ExploreView' }">
										<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
											<path
												stroke-linecap="round"
												stroke-linejoin="round"
												stroke-width="2"
												d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"
											></path>
										</svg>
										<span> Explore </span>
									</router-link>
								</li>
								<li>
									<router-link :to="{ name: 'ChatView' }">
										<i class="uil-location-arrow"></i>
										<span> Messages </span> <span class="nav-tag"> 3</span>
									</router-link>
								</li>
								<li>
									<router-link :to="{ name: 'TrendingView' }">
										<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
											<path
												stroke-linecap="round"
												stroke-linejoin="round"
												stroke-width="2"
												d="M17.657 18.657A8 8 0 016.343 7.343S7 9 9 10c0-2 .5-5 2.986-7C14 5 16.09 5.777 17.656 7.343A7.975 7.975 0 0120 13a7.975 7.975 0 01-2.343 5.657z"
											></path>
											<path
												stroke-linecap="round"
												stroke-linejoin="round"
												stroke-width="2"
												d="M9.879 16.121A3 3 0 1012.015 11L11 14H9c0 .768.293 1.536.879 2.121z"
											></path>
										</svg>
										<span> Trending </span>
									</router-link>
								</li>
								<li>
									<router-link :to="{ name: 'MarketplaceView' }">
										<i class="uil-store"></i>
										<span> Marketplace </span>
									</router-link>
								</li>
								<li>
									<router-link :to="{ name: 'AccountSettingView' }">
										<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
											<path
												stroke-linecap="round"
												stroke-linejoin="round"
												stroke-width="2"
												d="M10.325 4.317c.426-1.756 2.924-1.756 3.35 0a1.724 1.724 0 002.573 1.066c1.543-.94 3.31.826 2.37 2.37a1.724 1.724 0 001.065 2.572c1.756.426 1.756 2.924 0 3.35a1.724 1.724 0 00-1.066 2.573c.94 1.543-.826 3.31-2.37 2.37a1.724 1.724 0 00-2.572 1.065c-.426 1.756-2.924 1.756-3.35 0a1.724 1.724 0 00-2.573-1.066c-1.543.94-3.31-.826-2.37-2.37a1.724 1.724 0 00-1.065-2.572c-1.756-.426-1.756-2.924 0-3.35a1.724 1.724 0 001.066-2.573c-.94-1.543.826-3.31 2.37-2.37.996.608 2.296.07 2.572-1.065z"
											></path>
											<path
												stroke-linecap="round"
												stroke-linejoin="round"
												stroke-width="2"
												d="M15 12a3 3 0 11-6 0 3 3 0 016 0z"
											></path>
										</svg>
										<span> Settings </span>
									</router-link>
									<ul>
										<li><a href="setting.html">General </a></li>
										<li><a href="setting.html"> Account setting </a></li>
										<li>
											<a href="setting.html">Billing <span class="nav-tag">3</span> </a>
										</li>
									</ul>
								</li>
								<li>
									<router-link :to="{ name: 'ProfileView' }">
										<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
											<path
												stroke-linecap="round"
												stroke-linejoin="round"
												stroke-width="2"
												d="M16 7a4 4 0 11-8 0 4 4 0 018 0zM12 14a7 7 0 00-7 7h14a7 7 0 00-7-7z"
											></path>
										</svg>
										<span> My Profile </span>
									</router-link>
								</li>
								<li>
									<hr class="my-2" />
								</li>
								<li>
									<router-link :to="{ name: 'LoginView' }">
										<svg xmlns="http://www.w3.org/2000/svg" fill="none" viewBox="0 0 24 24" stroke="currentColor">
											<path
												stroke-linecap="round"
												stroke-linejoin="round"
												stroke-width="2"
												d="M17 16l4-4m0 0l-4-4m4 4H7m6 4v1a3 3 0 01-3 3H6a3 3 0 01-3-3V7a3 3 0 013-3h4a3 3 0 013 3v1"
											></path>
										</svg>
										<span> Logout </span>
									</router-link>
								</li>
							</ul>
						</div>
					</div>
				</div>
				<div class="simplebar-placeholder" style="width: 303px; height: 877px;"></div>
			</div>
			<div class="simplebar-track simplebar-horizontal" style="visibility: visible;">
				<div class="simplebar-scrollbar" style="transform: translate3d(0px, 0px, 0px); visibility: visible; width: 297px;"></div>
			</div>
			<div class="simplebar-track simplebar-vertical" style="visibility: hidden;">
				<div class="simplebar-scrollbar" style="transform: translate3d(0px, 0px, 0px); visibility: hidden;"></div>
			</div>
		</div>
	</div>
</template>
