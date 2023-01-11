<nav class="px-2 sm:px-4 py-2.5 dark:bg-gray-900  w-full    dark:border-gray-600">
    <div class="container  navbg px-3  lg:px-10 flex flex-row lg:flex-wrap items-center justify-between">
    <a href="/" class="flex items-center m-2 p-0 lg:p-">
        <img src="logo.svg" class=" h-8 m-2 sm:h-10 " alt="Shubhchintak Logo">
    </a>
    <div class="flex justify-end md:order-2 md:hidden navside">
        
        <button data-collapse-toggle="navbar-sticky" type="button" class="inline-flex items-center p-2  text-gray-500  md:hidden hover:bg-gray-100  focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600 font-urban text-white navbtn focus:ring-4 focus:outline-none text-white focus:ring-blue-300 font-medium rounded-lg text-base px-5 py-2.5 text-center mr-3 md:mr-0 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800" aria-controls="navbar-sticky" aria-expanded="false">
          <span class="sr-only">Open main menu</span>
          Menu
      </button>
    </div>
    <div class="items-center justify-center navside hidden w-full md:flex md:w-auto md:order-1" id="navbar-sticky">
      <ul class="flex flex-col  items-center p-0 lg:px-5 mt-0 border border-gray-100 rounded-lg  md:flex-row md:space-x-8 md:mt-0 md:text-sm md:font-medium md:border-0  dark:bg-gray-800 md:dark:bg-gray-900 dark:border-gray-700">
        <li>
          <a href="#" class=" font-urban block py-2 pl-3 pr-4 text-textp bg-blue-700 rounded md:bg-transparent md:text-blue-700 md:p-0 dark:text-white" aria-current="page">Home</a>
        </li>
        <li>
          <a href="#" class="font-urban block py-2 pl-3 pr-4 text-textp rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">About</a>
        </li>
        <li>
          <a href="#" class="font-urban block py-2 pl-3 pr-4 text-textp rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Services</a>
        </li>
        <li>
          <a href="#" class="font-urban block py-2 pl-3 pr-4 text-textp rounded hover:bg-gray-100 md:hover:bg-transparent md:hover:text-blue-700 md:p-0 md:dark:hover:text-white dark:text-gray-400 dark:hover:bg-gray-700 dark:hover:text-white md:dark:hover:bg-transparent dark:border-gray-700">Contact</a>
        </li>
        <li class="xsm:hidden">
            <button type="button" class="font-urban text-white navbtn focus:ring-4 focus:outline-none text-white focus:ring-blue-300 font-medium rounded-lg text-base px-5 py-2.5 text-center mr-3 md:mr-0 dark:bg-blue-600 dark:hover:bg-blue-700 dark:focus:ring-blue-800">Get started</button>
        <button data-collapse-toggle="navbar-sticky" type="button" class="inline-flex items-center p-2 text-sm text-gray-500 rounded-lg md:hidden hover:bg-gray-100 focus:outline-none focus:ring-2 focus:ring-gray-200 dark:text-gray-400 dark:hover:bg-gray-700 dark:focus:ring-gray-600" aria-controls="navbar-sticky" aria-expanded="false">
          <span class="sr-only">Open main menu</span>
          <svg class="w-6 h-6" aria-hidden="true" fill="currentColor" viewBox="0 0 20 20" xmlns="http://www.w3.org/2000/svg"><path fill-rule="evenodd" d="M3 5a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 10a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1zM3 15a1 1 0 011-1h12a1 1 0 110 2H4a1 1 0 01-1-1z" clip-rule="evenodd"></path></svg>
      </button>
        </li>
        
      </ul>
    </div>
    </div>
  </nav>
  


  <style>
    .navbtn
    {
        background: linear-gradient(180deg, #0F89FF 0%, #2F608F 100%);
        border-radius: 30px;
        color: white;
        font-family: 'Urbanist';
font-style: normal;
font-weight: 600;
    }
    .navbg
    {
      width:100%;
      height:70px;   
      background: linear-gradient(90.38deg, #DFF2FF 0%, #E8E8E1 97.05%);
      box-shadow: 0px 33px 227px rgba(0, 0, 0, 0.07), 0px 4.13211px 28.4239px rgba(0, 0, 0, 0.035);
      border-radius: 210px;
      margin:auto;
      
      animation-name: center-animate;
      animation-duration: 8s;
    }
    @keyframes center-animate {
  0%
  {
  width:100px;
  height:70px;
  margin:auto;  }
  100%
  {
  width:100%;
  height:70px;
 
  }
    
}    

.navside {
  width: 100%;
  overflow: hidden;
  margin-left: 0px;
  max-width: 500px;
}

.navside ul {
  animation: 2s slide-right 4s forwards;
    transform:translatex(100%);
}

@keyframes slide-right {
  to {
    transform:translateX(0);
  }
}
  </style>