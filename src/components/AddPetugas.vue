<template>
	
	<div class="flex flex-col w-3/4 mx-10 my-5 p-5 bg-white text-gray-700 flex-shrink-0 border-4 rounded-lg border-dashed">

		<h2 class="text-2xl font-bold text-gray-900">
            Add Petugas
        </h2>

        <form action="#" method="POST">
	        <div class="shadow overflow-hidden sm:rounded-md">
            <div class="px-4 py-5 bg-white sm:p-6">
              <div class="grid grid-cols-6 gap-6">
                <div class="col-span-6 sm:col-span-2">
                  <label for="first_name" class="block text-sm font-medium text-gray-700">Nama deplan</label>
                  <input type="text" name="first_name" id="first_name" autocomplete="given-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
                </div>

                <div class="col-span-6 sm:col-span-2">
                  <label for="last_name" class="block text-sm font-medium text-gray-700">Nama belakang</label>
                  <input type="text" name="last_name" id="last_name" autocomplete="family-name" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
                </div>

                <div class="col-span-6 sm:col-span-2">
                  <label for="email_address" class="block text-sm font-medium text-gray-700">Role</label>
                  <input type="text" name="email_address" id="email_address" autocomplete="email" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
                </div>

                <div class="col-span-6">
                  <label for="street_address" class="block text-sm font-medium text-gray-700">Alamat</label>
                  <input type="text" name="street_address" id="street_address" autocomplete="street-address" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
                </div>

                <div class="col-span-6 sm:col-span-6 lg:col-span-3">
                  <label for="city" class="block text-sm font-medium text-gray-700">Kota</label>
                  <input type="text" name="city" id="city" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
                </div>

                <div class="col-span-6 sm:col-span-3 lg:col-span-3">
                  <label for="state" class="block text-sm font-medium text-gray-700">Provinsi</label>
                  <input type="text" name="state" id="state" class="mt-1 focus:ring-indigo-500 focus:border-indigo-500 block w-full shadow-sm sm:text-sm border-gray-300 rounded-md">
                </div>

                <div class="col-span-6">
	              	<label class="block text-sm font-medium text-gray-700">
	                	photo
	              	</label>
	              	<div class="mt-2 flex justify-center px-6 pt-5 pb-6 border-2 border-gray-300 border-dashed rounded-md">
	                	<div class="space-y-1 text-center">
	                  		<svg class="mx-auto h-12 w-12 text-gray-400" stroke="currentColor" fill="none" viewBox="0 0 48 48" aria-hidden="true">
	                    		<path d="M28 8H12a4 4 0 00-4 4v20m32-12v8m0 0v8a4 4 0 01-4 4H12a4 4 0 01-4-4v-4m32-4l-3.172-3.172a4 4 0 00-5.656 0L28 28M8 32l9.172-9.172a4 4 0 015.656 0L28 28m0 0l4 4m4-24h8m-4-4v8m-12 4h.02" stroke-width="2" stroke-linecap="round" stroke-linejoin="round" />
	                  		</svg>
	                  		<div class="flex text-sm text-gray-600">
	                    		<label for="file-upload" class="relative cursor-pointer bg-white rounded-md font-medium text-indigo-600 hover:text-indigo-500 focus-within:outline-none focus-within:ring-2 focus-within:ring-offset-2 focus-within:ring-indigo-500">
	                      			<span>Upload a file</span>
	                      			<input id="file-upload" name="file-upload" type="file" class="sr-only">
	                    		</label>
	                    		<p class="pl-1">or drag and drop</p>
	                  		</div>
	                  		<p class="text-xs text-gray-500">
	                    		PNG, JPG, GIF up to 10MB
	                  		</p>
	                	</div>
	              	</div>
	            </div>

              </div>
            </div>
            <div class="px-4 py-3 bg-gray-50 text-right sm:px-6">
              <button type="submit" class="inline-flex justify-center py-2 px-4 border border-transparent shadow-sm text-sm font-medium rounded-md text-white bg-indigo-600 hover:bg-indigo-700 focus:outline-none focus:ring-2 focus:ring-offset-2 focus:ring-indigo-500">
                Save
              </button>
            </div>
          </div>
      	</form>

	</div>

</template>