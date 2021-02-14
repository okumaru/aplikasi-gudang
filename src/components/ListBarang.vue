<template>
	
	<div class="flex flex-col w-3/4 mx-10 my-5 p-5 bg-white text-gray-700 flex-shrink-0 border-4 rounded-lg border-dashed">

    <h2 class="text-2xl font-bold text-gray-900">
      List Barang
    </h2>
		<!-- This example requires Tailwind CSS v2.0+ -->
		<div class="flex flex-col">
  			<div class="-my-2 overflow-x-auto sm:-mx-6 lg:-mx-8">
    			<div class="py-2 align-middle inline-block min-w-full sm:px-6 lg:px-8">
      				<div class="shadow overflow-hidden border-b border-gray-200 sm:rounded-lg">
        				<table class="min-w-full divide-y divide-gray-200">
          					<thead class="bg-gray-50">
            					<tr>

              						<th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Name</th>

                          <th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Code</th>

              						<th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Status</th>

              						<th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Total</th>
              						
              						<th scope="col" class="px-6 py-3 text-left text-xs font-medium text-gray-500 uppercase tracking-wider">Last Update</th>

              						<th scope="col" class="relative px-6 py-3">
              							<span class="sr-only">History</span>
              						</th>

            					</tr>
          					</thead>
          					<tbody class="bg-white divide-y divide-gray-200">

            					<tr>

              						<td class="px-6 py-4 whitespace-nowrap">
                						<div class="flex items-center">
                  							<div class="flex-shrink-0 h-10 w-10">
                    							<img class="h-10 w-10 rounded-full" src="https://images.unsplash.com/photo-1543508282-5c1f427f023f?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1558&q=80" alt="">
                  							</div>
                  							<div class="ml-4">
                    							<div class="text-sm font-medium text-gray-900">Sepatu Nike Air</div>
                    							<div class="text-sm text-gray-500">Sepatu</div>
                  							</div>
                						</div>
              						</td>

                          <td class="px-6 py-4 whitespace-nowrap">
                            <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full text-gray-800">#SP0001</span>
                          </td>

              						<td class="px-6 py-4 whitespace-nowrap">
                						<span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">Available</span>
              						</td>

              						<td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                						10
              						</td>

              						<td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                						2021-02-10 22:23:10
              						</td>

              						<td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium">
              							<a href="#" class="mx-2 text-indigo-600 hover:text-indigo-900">Detail</a>
                						<a href="#" class="mx-2 text-indigo-600 hover:text-indigo-900">Update</a>
              						</td>

            					</tr>

            					<tr>

              						<td class="px-6 py-4 whitespace-nowrap">
                						<div class="flex items-center">
                  							<div class="flex-shrink-0 h-10 w-10">
                    							<img class="h-10 w-10 rounded-full" src="https://images.unsplash.com/photo-1512675828443-4f454c42253a?ixlib=rb-1.2.1&ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&auto=format&fit=crop&w=1534&q=80" alt="">
                  							</div>
                  							<div class="ml-4">
                    							<div class="text-sm font-medium text-gray-900">Sepatu Kulit Pria</div>
                    							<div class="text-sm text-gray-500">Sepatu</div>
                  							</div>
                						</div>
              						</td>

                          <td class="px-6 py-4 whitespace-nowrap">
                            <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full text-gray-800">#SP0002</span>
                          </td>

              						<td class="px-6 py-4 whitespace-nowrap">
                						<span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">Available</span>
              						</td>

              						<td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                						10
              						</td>

              						<td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                						2021-02-10 22:23:10
              						</td>

              						<td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium">
              							<a href="#" class="mx-2 text-indigo-600 hover:text-indigo-900">Detail</a>
                						<a href="#" class="mx-2 text-indigo-600 hover:text-indigo-900">Update</a>
              						</td>

            					</tr>

            					<tr>

              						<td class="px-6 py-4 whitespace-nowrap">
                						<div class="flex items-center">
                  							<div class="flex-shrink-0 h-10 w-10">
                    							<img class="h-10 w-10 rounded-full" src="https://images.unsplash.com/photo-1604001307862-2d953b875079?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1527&q=80" alt="">
                  							</div>
                  							<div class="ml-4">
                    							<div class="text-sm font-medium text-gray-900">Sepatu Chamel Wanita</div>
                    							<div class="text-sm text-gray-500">Sepatu</div>
                  							</div>
                						</div>
              						</td>

                          <td class="px-6 py-4 whitespace-nowrap">
                            <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full text-gray-800">#SP0003</span>
                          </td>

              						<td class="px-6 py-4 whitespace-nowrap">
                						<span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">Available</span>
              						</td>

              						<td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                						10
              						</td>

              						<td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                						2021-02-10 22:23:10
              						</td>

              						<td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium">
              							<a href="#" class="mx-2 text-indigo-600 hover:text-indigo-900">Detail</a>
                						<a href="#" class="mx-2 text-indigo-600 hover:text-indigo-900">Update</a>
              						</td>

            					</tr>

            					<tr>

              						<td class="px-6 py-4 whitespace-nowrap">
                						<div class="flex items-center">
                  							<div class="flex-shrink-0 h-10 w-10">
                    							<img class="h-10 w-10 rounded-full" src="https://images.unsplash.com/photo-1611255680915-114e3414c085?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1504&q=80" alt="">
                  							</div>
                  							<div class="ml-4">
                    							<div class="text-sm font-medium text-gray-900">Blue de Chanel</div>
                    							<div class="text-sm text-gray-500">Parfum</div>
                  							</div>
                						</div>
              						</td>

                          <td class="px-6 py-4 whitespace-nowrap">
                            <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full text-gray-800">#PF0001</span>
                          </td>

              						<td class="px-6 py-4 whitespace-nowrap">
                						<span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">Available</span>
              						</td>

              						<td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                						10
              						</td>

              						<td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                						2021-02-10 22:23:10
              						</td>

              						<td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium">
              							<a href="#" class="mx-2 text-indigo-600 hover:text-indigo-900">Detail</a>
                						<a href="#" class="mx-2 text-indigo-600 hover:text-indigo-900">Update</a>
              						</td>

            					</tr>

            					<tr>

              						<td class="px-6 py-4 whitespace-nowrap">
                						<div class="flex items-center">
                  							<div class="flex-shrink-0 h-10 w-10">
                    							<img class="h-10 w-10 rounded-full" src="https://images.unsplash.com/photo-1598533674391-8b8f5b46497a?ixid=MXwxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHw%3D&ixlib=rb-1.2.1&auto=format&fit=crop&w=1402&q=80" alt="">
                  							</div>
                  							<div class="ml-4">
                    							<div class="text-sm font-medium text-gray-900">Tas Pinggang Kulit</div>
                    							<div class="text-sm text-gray-500">Tas</div>
                  							</div>
                						</div>
              						</td>

                          <td class="px-6 py-4 whitespace-nowrap">
                            <span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full text-grey-800">#TS0001</span>
                          </td>

              						<td class="px-6 py-4 whitespace-nowrap">
                						<span class="px-2 inline-flex text-xs leading-5 font-semibold rounded-full bg-green-100 text-green-800">Available</span>
              						</td>

              						<td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                						10
              						</td>

              						<td class="px-6 py-4 whitespace-nowrap text-sm text-gray-500">
                						2021-02-10 22:23:10
              						</td>

              						<td class="px-6 py-4 whitespace-nowrap text-right text-sm font-medium">
              							<a href="#" class="mx-2 text-indigo-600 hover:text-indigo-900">Detail</a>
                						<a href="#" class="mx-2 text-indigo-600 hover:text-indigo-900">Update</a>
              						</td>

            					</tr>

            				<!-- More items... -->
          					</tbody>
        				</table>
      				</div>
    			</div>
  			</div>
		</div>


	</div>

</template>