<template>
<div>
    <div class="md:px-12">
                <h1 class="text-center text-3xl pt-12"><b>Account Form</b></h1>
        <div class="pt-16  2xl:px-12 xl:px-12 lg:px-12 md:px-12 sm:px-12 ">
            <div class=" 2xl:pb-16 xl:pb-16 lg:pb-16 md:pb-16 sm:pb-16 pb-4">
                     <p class=" md:w-1/2 bg-blueGray-200 font-bold p-3" ><b>USER INFORMATION</b></p>
    </div>
    <div class="grid 2xl:grid-cols-2 xl:grid-cols-2 lg:grid-cols-2 md:grid-cols-2 sm:grid-cols-2 gap-6">

        <div>
            <label class="block uppercase text-blueGray-600 text-xs font-bold mb-2" > Username</label>
            <input type="text" class=" px-3 py-3 placeholder-blueGray-300 text-blueGray-600 bg-white rounded text-sm shadow focus:outline-none focus:ring w-10/12 ease-linear transition-all duration-150" />
        </div>

        <div>
        <label class="block uppercase text-blueGray-600 text-xs font-bold mb-2" >EMAIL ADDRESS</label>
        <input type="text" class=" px-3 py-3 placeholder-blueGray-300 text-blueGray-600 bg-white rounded text-sm shadow focus:outline-none focus:ring w-10/12 ease-linear transition-all duration-150" />
        </div>

        <div>
            <label class="block uppercase text-blueGray-600 text-xs font-bold mb-2" > FIRST NAME</label>
            <input type="text" class=" px-3 py-3 placeholder-blueGray-300 text-blueGray-600 bg-white rounded text-sm shadow focus:outline-none focus:ring w-10/12 ease-linear transition-all duration-150" />
        </div>

        <div>
            <label class="block uppercase text-blueGray-600 text-xs font-bold mb-2" > LAST NAME</label>
            <input type="text" class=" px-3 py-3 placeholder-blueGray-300 text-blueGray-600 bg-white rounded text-sm shadow focus:outline-none focus:ring w-10/12 ease-linear transition-all duration-150" />
        </div> 

        <div>
            <hr class="text-3xl">
        </div>

    </div>

        <div class="pb-16">
                <p class="  bg-blueGray-200 font-bold p-3" ><b>CONTACT INFORMATION</b></p>
        </div> 
 
    <div class="grid 2xl:grid-cols-2 xl:grid-cols-2 lg:grid-cols-2 md:grid-cols-2 sm:grid-cols-2 gap-6">
            <div>
            <label class="block uppercase text-blueGray-600 text-xs font-bold mb-2" >ADDRESS</label>
            <input type="text" class=" p-8 placeholder-blueGray-300 text-blueGray-600 bg-white rounded text-sm shadow focus:outline-none focus:ring  w-full  ease-linear transition-all duration-150" />
        </div>

        <div>
            <label class="block uppercase text-blueGray-600 text-xs font-bold mb-2" > ABOUT ME</label>
            <input type="text" class="p-8 placeholder-blueGray-300 text-blueGray-600 bg-white rounded text-sm shadow focus:outline-none focus:ring w-full  ease-linear transition-all duration-150" />
        </div>
 
    </div>
        
    <div class="grid 2xl:grid-cols-2 xl:grid-cols-2 lg:grid-cols-2 md:grid-cols-2 sm:grid-cols-2 gap-6">
            <div class="pt-12">
            <label class="block uppercase text-blueGray-600 text-xs font-bold mb-2" >MOBILE NO</label>
            <input type="text" class=" px-3 py-3 placeholder-blueGray-300 text-blueGray-600 bg-white rounded text-sm shadow focus:outline-none focus:ring  w-full  ease-linear transition-all duration-150" />
        </div>

        <div class="pt-12">
            <label class="block uppercase text-blueGray-600 text-xs font-bold mb-2" > COUNTRY</label>
            <input type="text" class=" px-3 py-3 placeholder-blueGray-300 text-blueGray-600 bg-white rounded text-sm shadow focus:outline-none focus:ring w-full  ease-linear transition-all duration-150" />
        </div>
    </div>

    </div>
</div>

<div class=" text-right pt-10 pr-24">
<button class="bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 border border-blue-700 rounded">
  Submit
</button>
</div>

<br>
<br><br>

<br><br>
</div>
</template>