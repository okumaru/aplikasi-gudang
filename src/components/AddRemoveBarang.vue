<template>
	
	<div class="flex flex-col w-3/4 mx-10 my-5 p-5 bg-white text-gray-700 flex-shrink-0 border-4 rounded-lg border-dashed">

		<h2 class="text-2xl font-bold text-gray-900">
            Barang masuk & keluar
        </h2>

        <form action="#" method="POST">
	        <div class="sm:rounded-md sm:overflow-hidden">
	          	<div class="pt-6 px-10 py-16 space-y-6">

	          		<div class="grid grid-cols-12 gap-12">

	          			<div class="col-span-12 sm:col-span-6 p-2 bg-blue-500 shadow-2xl rounded-md bg-opacity-70 hover:bg-opacity-100 transition">
	          				<div class="p-6 rounded-md border-2 border-dashed border-gray-300">
	          					
	          					<h2 class="text-2xl font-bold text-white">
	          						Barang Masuk
	          					</h2>

	          					<div class="mt-2">
	                  				<label for="about" class="block text-sm font-medium text-white">
		                				Kode / Nama barang
		              				</label>
		              				<div class="mt-1">
		                				<input type="text" name="last_name" id="last_name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md" placeholder="#SP0001 | Sepatu Nike Air">
		              				</div>
	                  			</div>

	                  			<div class="mt-2 grid grid-cols-8 gap-8">
	                  				
	                  				<div class="col-span-8 sm:col-span-5">
		                  				<label for="about" class="block text-sm font-medium text-white">
			                				Tanggal
			              				</label>
			              				<div class="mt-1">
			                				<input type="text" name="last_name" id="last_name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
			              				</div>
		                  			</div>

		                  			<div class="col-span-8 sm:col-span-3">
		                  				<label for="about" class="block text-sm font-medium text-white">
			                				Jumlah
			              				</label>
			              				<div class="mt-1">
			                				<input type="text" name="last_name" id="last_name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md" placeholder="1">
			              				</div>
		                  			</div>

	                  			</div>

	                  			<div class="mt-6 p-2 rounded-md bg-white text-grey-900">
	                  				<div class="border-b border-grey-600 py-2">
	                  					<h3 class="text-lg font-bold">
	                  						Detail Informasi
	                  					</h3>
	                  					<p class="max-w-2xl text-sm">
      										Barang yang akan ditambahkan
    									</p>
	                  				</div>
	                  				<div>
	                  					<div class="mt-2">
			                  				<label for="about" class="block text-sm font-medium text-grey-900">
				                				Nama barang
				              				</label>
				              				<div class="mt-1">
				                				<input type="text" name="last_name" id="last_name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md" value="Sepatu Nike Air" disabled="disabled">
				              				</div>
			                  			</div>

			                  			<div class="py-2 grid grid-cols-8 gap-8">
			                  				
			                  				<div class="col-span-8 sm:col-span-5">
				                  				<label for="about" class="block text-sm font-medium text-grey-900">
					                				Kode barang
					              				</label>
					              				<div class="mt-1">
					                				<input type="text" name="last_name" id="last_name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md" value="#SP0001" disabled="disabled">
					              				</div>
				                  			</div>

				                  			<div class="col-span-8 sm:col-span-3">
				                  				<label for="about" class="block text-sm font-medium text-grey-900">
					                				Jumlah
					              				</label>
					              				<div class="mt-1">
					                				<input type="text" name="last_name" id="last_name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md" value="10"  disabled="disabled">
					              				</div>
				                  			</div>

			                  			</div>
	                  				</div>
	                  			</div>

					            <div class="mt-2 px-4 py-3 text-right sm:px-6">
	              					<button type="submit" class="w-full inline-flex justify-center py-2 px-4 border border-transparent shadow-sm text-sm font-medium rounded-md text-white bg-green-600 hover:bg-green-500 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-green-500">
	                					Save
	              					</button>
	            				</div>

	          				</div>
                		</div>

                		<div class="col-span-6 sm:col-span-6 p-2 rounded-md bg-yellow-500 shadow-2xl bg-opacity-70 hover:bg-opacity-100 transition">
                			<div class="p-6 rounded-md border-2 border-dashed border-white">
                				
                				<h2 class="text-2xl font-bold text-white">
	          						Barang Keluar
	          					</h2>

                				<div class="mt-2">
	                  				<label for="about" class="block text-sm font-medium text-white">
		                				Kode / Nama barang
		              				</label>
		              				<div class="mt-1">
		                				<input type="text" name="last_name" id="last_name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md" placeholder="#SP0001 | Sepatu Nike Air">
		              				</div>
	                  			</div>

	                  			<div class="mt-2 grid grid-cols-8 gap-8">
	                  				
	                  				<div class="col-span-8 sm:col-span-5">
		                  				<label for="about" class="block text-sm font-medium text-white">
			                				Tanggal
			              				</label>
			              				<div class="mt-1">
			                				<input type="text" name="last_name" id="last_name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
			              				</div>
		                  			</div>

		                  			<div class="col-span-8 sm:col-span-3">
		                  				<label for="about" class="block text-sm font-medium text-white">
			                				Jumlah
			              				</label>
			              				<div class="mt-1">
			                				<input type="text" name="last_name" id="last_name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md" placeholder="1">
			              				</div>
		                  			</div>

	                  			</div>

	                  			<div class="mt-6 p-2 rounded-md bg-white text-grey-900">
	                  				<div class="border-b border-grey-600 py-2">
	                  					<h3 class="text-lg font-bold">
	                  						Detail Informasi
	                  					</h3>
	                  					<p class="max-w-2xl text-sm">
      										Barang yang akan dikeluarkan
    									</p>
	                  				</div>
	                  				<div>
	                  					<div class="mt-2">
			                  				<label for="about" class="block text-sm font-medium text-grey-900">
				                				Nama barang
				              				</label>
				              				<div class="mt-1">
				                				<input type="text" name="last_name" id="last_name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md" value="Sepatu Nike Air" disabled="disabled">
				              				</div>
			                  			</div>

			                  			<div class="py-2 grid grid-cols-8 gap-8">
			                  				
			                  				<div class="col-span-8 sm:col-span-5">
				                  				<label for="about" class="block text-sm font-medium text-grey-900">
					                				Kode barang
					              				</label>
					              				<div class="mt-1">
					                				<input type="text" name="last_name" id="last_name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md" value="#SP0001" disabled="disabled">
					              				</div>
				                  			</div>

				                  			<div class="col-span-8 sm:col-span-3">
				                  				<label for="about" class="block text-sm font-medium text-grey-900">
					                				Jumlah
					              				</label>
					              				<div class="mt-1">
					                				<input type="text" name="last_name" id="last_name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md" value="10"  disabled="disabled">
					              				</div>
				                  			</div>

			                  			</div>
	                  				</div>
	                  			</div>

					            <div class="mt-2 px-4 py-3 text-right sm:px-6">
	              					<button type="submit" class="w-full inline-flex justify-center py-2 px-4 border border-transparent shadow-sm text-sm font-medium rounded-md text-white bg-green-600 hover:bg-green-500 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-green-500">
	                					Save
	              					</button>
	            				</div>

                			</div>
                		</div>

	          		</div>

	          	</div>
	        </div>
      	</form>

	</div>

</template>

<script>
	// Date.now();
</script>