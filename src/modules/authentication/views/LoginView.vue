<template>
	<div class="lg:p-12 max-w-md max-w-xl lg:my-0 my-12 mx-auto p-6 space-y-">
		<h1 class="lg:text-3xl text-xl font-semibold  mb-6">Log in</h1>
		<p class="mb-2 text-black text-lg">Email or Username</p>
		<form action="">
			<input
				type="text"
				placeholder="example@mydomain.com"
				class="bg-gray-200 mb-2 shadow-none dark:bg-gray-800"
				style="border: 1px solid #d3d5d8 !important;"
			/>
			<input
				type="text"
				placeholder="***********"
				class="bg-gray-200 mb-2 shadow-none dark:bg-gray-800"
				style="border: 1px solid #d3d5d8 !important;"
			/>
			<div class="flex justify-between my-4">
				<div class="checkbox">
					<input type="checkbox" id="chekcbox1" checked="" />
					<label for="chekcbox1"><span class="checkbox-icon"></span>Remember Me</label>
				</div>
				<a href="#"> Forgot Your Password? </a>
			</div>
			<button type="submit" class="bg-gradient-to-br from-pink-500 py-3 rounded-md text-white text-xl to-red-400 w-full">
				Login
			</button>
			<div class="text-center mt-5 space-x-2">
				<p class="text-base">Not registered? <router-link :to="{ name: 'SignupView' }" class=""> Create a account </router-link></p>
			</div>
		</form>
	</div>
</template>
