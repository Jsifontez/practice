<script>
	import mobileCover from '$lib/assests/illustration-sign-up-mobile.svg';
</script>

<main>
	<img
		src={mobileCover}
		alt="a page with orange background"
		class="w-full max-h-[330px] object-bottom object-cover"
	/>
	<section class="mt-6 px-6 pb-4 max-w-[510px] mx-auto">
		<h1 class="text-4xl font-bold">Stay updated!</h1>
		<p class="text-base my-5">Join 60,000+ product managers receiving monthly updates on:</p>
		<ul class="pl-7">
			<li>Product discovery and building what matters</li>
			<li>Measuring to ensure updates are success</li>
			<li>And much more!</li>
		</ul>

		<form class="mt-9">
			<label
				for="email"
				class="text-sm font-bold text-dark-slate-gray mb-2 block"
			>
				Email address
			</label>
			<input
				type="email"
				placeholder="email@company.com"
				required
				class="w-full py-4 px-6 border border-grey rounded-lg"
			/>
			<button
				class="w-full py-4 mt-5 bg-dark-slate-gray text-white rounded-lg font-bold text-center"
			>
				Suscribe to monthly newsletter
			</button>
		</form>
	</section>
</main>

<style>
	* {
		font-family: 'Roboto', sans-serif;
	}
	ul {
		list-style: url('../lib/assests/icon-list.svg');
	}
</style>
