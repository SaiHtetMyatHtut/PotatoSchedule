<script>
	import PotatoButton from '../components/PotatoButton.svelte';
</script>

<div
	class="flex h-screen w-screen justify-center items-center bg-[url('images/demo2.jpg')] bg-cover"
>
	<div class="flex flex-col w-[400px]  bg-white rounded-md shadow-md p-5 space-y-4">
		<div class="flex-grow-0 text-[#0c1d34] space-y-5">
			<p class="text-center font-bold text-2xl">Potato Community</p>
			<div class="flex flex-col space-y-3 text-[#0c1d34]">
				<input
					class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-indigo-900 focus:border-indigo-900 block w-full p-2.5"
					type="text"
					placeholder="Username"
				/>
				<input
					class="bg-gray-50 border border-gray-300 text-gray-900 text-sm rounded-lg focus:ring-indigo-900 focus:border-indigo-900 block w-full p-2.5"
					type="password"
					placeholder="Password"
				/>
			</div>
		</div>
		<div class="flex flex-row justify-end">
            <p class="text-[#0c1d34] text-xs w-[250px] px-3">Wanna be a Potato? <a class="text-blue-600 underline" href="#">here</a></p>
            <PotatoButton />
        </div>
	</div>
</div>
