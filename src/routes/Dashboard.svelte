<!-- Notification Header -->
<div class="flex items-center justify-end space-x-4">
  <span class="n relative mt-5">
    <span class="absolute top-0 right-0 inline-flex items-center justify-center w-10 h-9  bg-blue-500 text-white text-lg rounded-full">
      P
    </span>
    <span class="notification">
      <i class="fa-regular fa-bell mt-2"></i>
    </span>
  </span>
</div>
<!-- Side Navigation -->
<div class="side-nav fixed left-0 top-0 h-full w-52 flex flex-col bg-white">
  <div class="flex items-center justify-between">
    <!-- svelte-ignore a11y-missing-attribute -->
    <img src="./logo.png" class="my-4 mx-2.5">
  </div>
  <div class="p-2.5 mt-2 mx-2.5 flex items-center rounded-md px-4 duration-300 cursor-pointer hover:bg-blue-500">
    <i class="fa-solid fa-house"></i>
    <span class="text-[15px] ml-4 color-black">Dashboard</span>
  </div>
  <div class="p-2.5 mt-2 mx-2.5 flex items-center rounded-md px-4 duration-300 cursor-pointer hover:bg-blue-500">
    <i class="fa-solid fa-users"></i>
    <span class="text-[15px] ml-4 color-black">My surveys</span>
  </div>
  <div class="p-2.5 mt-2 mx-2.5 flex items-center rounded-md px-4 duration-300 cursor-pointer hover:bg-blue-500">
    <i class="fa fa-file"></i>
    <span class="text-[15px] ml-4 color-black">Forms </span>
  </div>
  <div class="p-2.5 mt-2 mx-2.5 flex items-center rounded-md px-4 duration-300 cursor-pointer hover:bg-blue-500">
    <i class="fa fa-pie-chart"></i>
    <span class="text-[15px] ml-4 color-black">Analytics</span>
  </div>
</div>
<!-- Dashboard -->
<div class="container m-20 mt-8 px-4 ml-64 max-w-3xl bg-white rounded-lg ">
  <h1 class="text-left text-2xl md:text-4xl mt-8">Hello, Admin <span class="text-blue-500">Yukio!</span></h1>
  <p class="text-left mt-4">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
  <button class="block mx-auto mt-4 px-4 py-2 ml-0 bg-blue-500 text-white rounded hover:bg-blue-600">Create form</button>
  <br>
</div>
<div class=" m1 container ml-64 m-72 my-1 px-4 space-y-3.5 p-0 bg-white rounded-lg ">
  <span class="text-2xl font-medium">Schools</span><br>
  <div class="flex justify-end">
    <span class="mr-64 text-4xl">0</span><br>
    <div class="icon flex mx-2 flex-col items-end ">
      <span class="hover:text-blue-500 cursor-pointer">
        <i class="fa fa-flag blue-bg mx-2"></i>
        <span>View all</span>
      </span>
    </div>
  </div>
  <span class="font-medium">Registered Schools</span>
</div>
<div class=" m2 container m-72 px-4 my-auto mt-80 space-y-3.5 p-0 bg-white rounded-lg  ">
  <span class="text-2xl font-medium">Forms</span><br>
  <div class="flex justify-end">
    <span class="mr-64 text-4xl">0</span><br>
    <div class="icon flex mx-2 flex-col items-end">
      <span class="hover:text-blue-500 cursor-pointer">
        <i class="fa fa-file blue-bg mx-2"></i>
        <span>View all</span>
      </span>
    </div>
  </div>
  <span class="font-medium">Current Forms</span>
</div>
<div class="panel container  ml-64 mt-9 m-72 my-11 px-4 max-w-3xl  rounded-lg ">
  <span class="text-2xl font-medium">Published forms</span>
  <p>The public forms well be displayed here. These</p>
  <p>are the steps for creating and letting the students</p>
  <p>see it.</p>
  <div class="inside-container mt-3 m-8 max-w-xs rounded-lg p-8">
    <p>Step 1. Create a school in my survey in the side navigation.</p>
    <p>Step 2. Go to forms in the side navigation.</p>
    <p>Step 3. Select create form and edit.</p>
    <p>Step 4. Share the form with a school and publish it.</p>
  </div>
  <div class="container3 container px-0.5 m-7 w-72 rounded-lg">
    <h3 class="text-2xl font-normal my-2 ">Published forms</h3>
    <div class="bg-white h-10 rounded-md flex items-center border-solid border-2 border-slate-300">
      <div class="badge rounded-full bg-blue-500 h-8 w-8 ml-2">
        <p class="text-center font-normal ml-10 text-black text-xs flex">Untitled_form1 <span><div class="badge bg-green-400 h-2 w-2 ml-2 my-1 rounded-full"></div></span> <span class="ml-10">160/436</span></p>
        <div class="w-52 bg-slate-100 h-2 rounded-full ml-10 my-1"> 
          <div class="bg-blue-500 rounded-full h-2" style="width:45%;"></div>
        </div>
      </div>
    </div>
    <div class="bg-white h-10 rounded-md flex items-center my-2 border-solid border-2 border-slate-300">
      <div class="badge rounded-full bg-blue-500 h-8 w-8 ml-2">
        <p class="text-center font-normal ml-10 text-black text-xs flex">Untitled_form2 <span><div class="badge bg-green-400 h-2 w-2 ml-2 my-1 rounded-full"></div></span> <span class="ml-9">587/902</span></p>
        <div class="w-52 bg-slate-100 h-2 rounded-full ml-10 my-1">
          <div class="bg-blue-500 rounded-full h-2" style="width:65%;"></div>
        </div>
      </div>
    </div>
    <div class="bg-white h-10 rounded-md flex items-center my-2 border-solid border-2 border-slate-300">
      <div class="badge rounded-full bg-blue-500 h-8 w-8 ml-2">
        <p class="text-center font-normal ml-10 text-black text-xs flex">Untitled_form3 <span><div class="badge bg-green-400 h-2 w-2 ml-2 my-1 rounded-full"></div></span> <span class="ml-12">0/384</span></p>
        <div class="w-52 bg-slate-100 h-2 rounded-full ml-10 my-1"> 
          <div class="bg-blue-500 rounded-full h-2" style="width:0%;"></div>
        </div>
      </div>
    </div>
    <div class="bg-white h-10 rounded-md flex items-center my-2 border-solid border-2 border-slate-300">
      <div class="badge rounded-full bg-blue-500 h-8 w-8 ml-2">
        <p class="text-center font-normal ml-10 text-black text-xs flex">Untitled_form4 <span><div class="badge bg-green-400 h-2 w-2 ml-2 my-1 rounded-full"></div></span> <span class="ml-12">0/289</span></p>
        <div class="w-52 bg-slate-100 h-2 rounded-full ml-10 my-1"> 
          <div class="bg-blue-500 rounded-full h-2" style="width:0%;"></div>
        </div>
      </div>
    </div>
    <div class="bg-white h-10 rounded-md flex items-center my-2 border-solid border-2 border-slate-300">
      <div class="badge rounded-full bg-blue-500 h-8 w-8 ml-2">
        <p class="text-center font-normal ml-10 text-black text-xs flex">Untitled_form5 <span><div class="badge bg-green-400 h-2 w-2 ml-2 my-1 rounded-full"></div></span> <span class="ml-12">0/652</span></p>
        <div class="w-52 bg-slate-100 h-2 rounded-full ml-10 my-1"> 
          <div class="bg-blue-500 rounded-full h-2" style="width:0%;"></div>
        </div>
      </div>
    </div>
  </div>
  <br>
  <div class="container4 container bg-white px-0.5 m-7 rounded-lg ">
    <span class="text-2xl font-medium">Schools</span>
    <div class="badge rounded-full bg-slate-100 mt-8 h-11 w-11 ml-2">
      <div class="badge w-32 h-6 ml-14 bg-slate-100 rounded-full"></div>
        <div class="badge w-20 h-5 ml-14 mt-1 bg-slate-100 rounded-full">
      </div>
    </div>
    <hr class="mt-3">
      <div class="badge rounded-full bg-slate-100 mt-8 h-11 w-11 ml-2">
        <div class="badge w-32 h-6 ml-14 bg-slate-100 rounded-full"></div>
          <div class="badge w-20 h-5 ml-14 mt-1 bg-slate-100 rounded-full">
        </div>
    </div>
        <hr class="mt-3">
        <div class="badge rounded-full bg-slate-100 mt-8 h-11 w-11 ml-2">
          <div class="badge w-32 h-6 ml-14 bg-slate-100 rounded-full"></div>
            <div class="badge w-20 h-5 ml-14 mt-1 bg-slate-100 rounded-full">
          </div>
        </div>
          <hr class="mt-3">
          <br>
          <div class="row">
            <span class="hover:text-blue-500 cursor-pointer">
              <span class="hover:text-blue-500 cursor-pointer">
                <i class="bi bi-plus-square-dotted flex mt-0  ml-10"> </i>
                <span class="txt flex font-medium">Create school space</span>
              </span>             
            </span>
          </div>
          </div>
      </div>
    <!-- <footer class="bg-slate-500 h-20">
      <p class="text-white text-center ml-52 font-black"> © COPYRIGHT JUVANE ARCENAS 2023 <br>
        <span>WELA-WEbDEV-Intern</span><br>
        <span>email: bunnytv112798@gmail.com</span>
      </p>
    </footer> -->
