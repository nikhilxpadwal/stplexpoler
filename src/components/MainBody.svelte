<script>
 import { Swiper, SwiperSlide } from "swiper/svelte";
 import "swiper/css";
 import Time from "svelte-time";
 import { Mousewheel, Pagination } from "swiper";
 function replace()
 {

 }
 
</script>
<div class="container mx-auto maindesktop  mt-38">
    <nav class="px-2 sm:px-4 py-0 dark:bg-gray-900   w-full dark:border-gray-600">
        <div class="container px-3 flex flex-wrap items-center justify-between mx-auto">
        <a href="/" class="flex items-center py-4">
            <img src="Controls.svg" class="mobicon h-6 mr-3 sm:h-3 " alt="Shubhchintak">
            <img src="desicon.svg" class="mobicon h-6 mr-3 sm:h-4 " alt="Shubhchintak Logo">
            <img src="arrow.svg" class="mobicon h-6 mr-3 sm:h-4 " alt="Shubhchintak Logo">
            
        </a>
        <div>
            <img src="Field.svg" class="mobicon h-6 mr-3 sm:h-8" />
        </div>
        <div class="items-center justify-center hidden w-full md:flex md:w-auto md:order-1" id="navbar-sticky">
            <img src="addnew.svg"  class=" h-6 mr-3 sm:h-4 "/>
        </div>
        </div>
      </nav>
      <div class="maincontent mx-1 my-1 rounded lg:h-[80vh] ">

        <Swiper
        direction={"vertical"}
        slidesPerView={1}
        spaceBetween={30}
        mousewheel={true}
        pagination={{
          clickable: true,
        }}
        modules={[Mousewheel, Pagination]}
        class="mySwiper"
      >
      <SwiperSlide>
            <div class="container mx-auto px-5 lg:px-20 flex flex-col lg:flex-row gap-5 text-center items-center  justify-center">
                <div class="flex flex-col justify-center gap-5 w-[100%] lg:w-[50%]">
                    <img src="mobile.svg" class=" h-[0px] lg:h-[500px]" />
                    <img src="mobmob.svg" class=" h-[400px] lg:h-[0px]" />
                </div>
                <div class="flex flex-col gap-5 w-[100%] lg:w-[50%] text-center lg:text-left justify-center">
                    <h1 class="text-3xl lg:text-5xl font-bold  leading-tight">Headline  <span class="text-accent"> of  Modern  and Digital</span> Lending Platform Seconds</h1>
                    <p  class=" text-textp ">Nowadays, it isn’t uncommon to see lenders rapidly adopting a digital lending strategy to streamline the lending process</p>
                    <div class="space-x-3 py-3">
                        <button class="bg-accent text-secondary px-5 py-2.5  rounded-full">Get Started</button>
                        <button class="bg-accent text-secondary px-5 py-2.5  rounded-full">Learn More</button>
                    </div>
                </div>
            </div>  
       </SwiperSlide>  
       <SwiperSlide>
        <div class="container mx-auto flex flex-col lg:flex-row gap-5 text-center items-center  justify-center">
            
            <div class="flex flex-col pl-10 gap-5 w-[100%] lg:w-[50%] text-center lg:text-left justify-center">
                <div class="space-x-3 ">
                    <button class="flex gap-2 bg-secondary text-accent text-sm  px-5 py-2 rounded-full"><img src="Star.svg" />ABOUT US </button>
                </div>
                <h1 class="text-3xl lg:text-5xl font-bold  leading-tight">Headline  <span class="text-accent"> of  Modern  and Digital</span> Lending Platform Seconds</h1>
                <p  class=" text-textp ">Nowadays, it isn’t uncommon to see lenders rapidly adopting a digital lending strategy to streamline the lending process</p>
                <div class="space-x-3 py-3">    
                  <button class="flex gap-3 bg-accent text-secondary  px-5 py-2.5 rounded-full">Explore All <img src="Arrow_Forward.svg" /></button>    
                </div>
            </div>
            <div class="flex flex-col pl-10  justify-center gap-5 w-[100%] lg:w-[50%]">
                <img src="desktop.svg" class="pt-10 h-[0px] lg:h-[520px]" />
                <img src="mobmob.svg" class=" h-[400px] lg:h-[0px]" />
            </div>
        </div>  
   </SwiperSlide>  
    <SwiperSlide> 
        <div class="container mx-auto flex flex-col lg:flex-row gap-5 text-center lg:h-[80vh] items-center justify-center">
            <div id="div1" class="flex  lg:flex-col justify-center w-[100%] lg:w-[10%]">
                <img src="image3.svg" class="h-20" />
                <img src="image4.svg" class="h-20" />
                <img src="image5.svg" class="h-20" />
                <img src="image6.svg" class="h-20" />
            </div>
            <div id="div2" class="flex hidden lg:flex-col justify-center w-[100%] lg:w-[10%]">
                <img src="image3.svg" class="h-20" />
                <img src="image4.svg" class="h-20" />
                
            </div>

            <div class="flex flex-col justify-center w-[100%] lg:w-[30%]">
                <img src="desktop.svg"  />
            </div>
            <div class="flex flex-col p-5  gap-2 w-[100%] lg:w-[60%] text-left justify-center">
                <div class="flex flex-col lg:flex-row gap-2">
                <div on:click={replace()} class="bgcard cursor-pointer p-5 opacity-20 hover:opacity-100   space-y-3 w-[100%] lg:w-[50%]">
                    <h1 class="text-xl font-bold  leading-tight">UI/UX </h1>
                    <p  class=" text-textp ">Nowadays, it isn’t uncommon to see lenders rapidly adopting a digital lending strategy</p>
                    <div class="space-x-1 flex">
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">Headline</button>
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">Text</button>
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">lable</button>
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">post</button>
                    </div>
                </div>

                <div  class="bgcard cursor-pointer p-5 opacity-20 hover:opacity-100   space-y-3 w-[100%] lg:w-[50%]">
                    <h1 class="text-xl font-bold  leading-tight">UI/UX </h1>
                    <p  class=" text-textp ">Nowadays, it isn’t uncommon to see lenders rapidly adopting a digital lending strategy</p>
                    <div class="space-x-1 flex">
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">Headline</button>
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">Text</button>
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">lable</button>
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">post</button>
                    </div>
                </div>
            </div>
            <div class="flex flex-col lg:flex-row gap-2 ">
                <div  class="bgcard cursor-pointer p-5 opacity-20 hover:opacity-100   space-y-3 w-[100%] lg:w-[50%]">
                    <h1 class="text-xl font-bold  leading-tight">UI/UX </h1>
                    <p  class=" text-textp ">Nowadays, it isn’t uncommon to see lenders rapidly adopting a digital lending strategy</p>
                    <div class="space-x-1 flex">
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">Headline</button>
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">Text</button>
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">lable</button>
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">post</button>
                    </div>
                </div>

                <div  class="bgcard cursor-pointer p-5 opacity-20 hover:opacity-100  space-y-3 w-[100%] lg:w-[50%]">
                    <h1 class="text-xl font-bold  leading-tight">UI/UX </h1>
                    <p  class=" text-textp ">Nowadays, it isn’t uncommon to see lenders rapidly adopting a digital lending strategy</p>
                    <div class="space-x-1 flex">
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">Headline</button>
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">Text</button>
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">lable</button>
                        <button class="flex gap-3 bg-accent text-xs text-secondary  px-5 py-2.5 rounded-full uppercase">post</button>
                    </div>
                </div>
            </div>    
            </div>
            
        </div>  
    </SwiperSlide>

    <SwiperSlide>
        <div class="container mx-auto  flex flex-col lg:items-center lg:flex-row gap-5 text-center lg:min-h-fit justify-center">
            <div class="flex flex-col  p-10 lg:pl-20 gap-5 w-[100%] lg:w-[50%]  text-left justify-center">
                <h1 class="text-2xl font-urban font-semibold leading-tight">About </h1>
                <p  class="text-primary ">Nowadays, it isn’t uncommon to see lenders rapidly adopting a digital lending strategy to streamline the lending process Gorgeous, high-quality design system for mobile, tablet & desktop devices a few reasons digital</p>
                <div class="flex flex-col  lg:flex-row space-y-3 lg:space-x-3 ">
                   <div class="w-[70%]  lg:w-[40%] ">
                        <h1 class="text-5xl font-urban font-bold">18 k</h1>
                        <p class="text-textp ">Gorgeous, high-quality design system for mobile, tablet & desktop devices</p>
                   </div>
                   <div style="margin: 0px;" class=" w-[70%] lg:w-[40%] ">
                    <h1 class="text-5xl font-urban font-bold">92 %</h1>
                    <p class="text-textp ">Gorgeous, high-quality design system for mobile, tablet & desktop devices</p>
               </div>
                </div>
            </div>
            <div class="flex flex-col p-0 justify-center w-[100%] lg:w-[50%]">
                <img src="about.svg" class="h-[0px] lg:h-[530px]" />
            </div>
        </div>  
    </SwiperSlide>
    <SwiperSlide>
        <div class="container mx-auto p-10 lg:p-10 flex flex-col lg:flex-row gap-5 text-center mt-0 mb-0 lg:mt-20 lg:mb-20 justify-center">
            <div class="flex flex-col w-[100%] lg:w-[30%] text-center p-5 lg:p-10 bgcards  ">
                <img src="mission.svg" class="h-[100px]" />
                <h1 class="text-2xl font-urban font-semibold">Mission</h1>
                <p>Nowadays, it isn’t uncommon to see lenders rapidly adopting a digital lending strategy to streamline the lending process</p>
            </div>
            <div class="flex flex-col w-[100%] lg:w-[30%] text-center p-5 lg:p-10 bgcard  opacity-20 hover:opacity-100">
                <img src="vision.svg" class="h-[100px]" />
                <h1 class="text-2xl font-urban font-semibold">Vision</h1>
                <p>Nowadays, it isn’t uncommon to see lenders rapidly adopting a digital lending strategy to streamline the lending process</p>
            </div>
        </div>
    </SwiperSlide>
    <SwiperSlide>
        <div class="flex flex-col items-center" >
            <div class="space-x-3 py-5">
            <label class="flex gap-2 font-urban bg-secondary text-accent text-sm  px-5 py-2 rounded-full"><img src="Star.svg" />Methodology</label>
            </div>
            <img src="map.svg"  class="h-[0px] lg:h-[400px]" />
        </div>
    </SwiperSlide>
    <SwiperSlide>
        <div class="container mx-auto flex flex-col gap-5 items-center  lg:mt-5 lg:mb-20  justify-center">
            <div class="text-center p-2 lg:px-10 space-y-2 ">
                <h1 class="text-3xl lg:text-5xl font-semibold">The Headline for UI/UX Design</h1>
                <p>Nowadays, it isn’t uncommon to see lenders rapidly adopting a digital lending strategy to <br>streamline the lending process nowadays, it isn’t uncommon to see lenders rapidly</p>
                <button class=" gap-3 bg-accent text-sm text-secondary  px-5 py-2.5 rounded-full ">Get Started</button>
            </div>
            <div class="text-center p-2 lg:px-10 ">
                <img src="pro.svg" class="h-[500px] lg:h-[0px]" />
                <img src="object.svg" class="h-[0px] lg:h-[250px]" />
            </div>
        </div>
    </SwiperSlide>

    <SwiperSlide>
        <div class="container mx-auto flex flex-col lg:flex-row gap-5 text-center lg:h-[80vh] justify-center">
            <div class="flex flex-col p-5 lg:pl-20 gap-5 w-[100%] lg:w-[50%] lg:text-left items-center lg:items-start justify-center">
                
                <h1 class="text-3xl lg:text-5xl font-semibold ">The Headline for Mobile App Development</h1>
                <p  class=" text-textp ">Nowadays, it isn’t uncommon to see lenders rapidly adopting a digital lending strategy to streamline the lending process</p>
                <div class="space-x-3 ">
                    <button class="flex gap-3 bg-accent text-secondary  px-5 py-2.5 rounded-full">Get Started</button>
                </div>
            </div>
            <div class="flex flex-col justify-center  w-[100%] lg:w-[50%]">
                <img src="service.svg" class="h-[400px] lg:h-[500px]" />
            </div>
        </div>  
    </SwiperSlide>

    <SwiperSlide>
        <h1 class="text-3xl lg:text-5xl text-center font-semibold py-5">The Headline for Mobile App Development</h1>
        <div class="container mx-auto flex flex-col lg:flex-row gap-0 lg:gap-2 text-center py-5 lg:py-10 lg:h-[80vh] justify-center">
            <div class="flex flex-col lg:pl-20 gap-5 w-[100%] lg:w-[25%] lg:text-left items-center lg:items-start justify-center">
                <p  class=" text-textp ">Nowadays, it isn’t uncommon to see lenders rapidly adopting a digital lending strategy to streamline the lending process</p>
                <div class="space-x-3 ">
                    <button class="flex gap-3 bg-accent text-secondary  px-5 py-2.5 rounded-full">Get Started</button>
                </div>
            </div>
            <div class="flex flex-col  w-[100%] lg:w-[50%]">
                <img src="services.svg" class="h-[500px] " />
                
            </div>
            <div class="flex flex-col  w-[100%] lg:w-[25%] lg:text-left justify-center">
                <p  class=" text-textp ">Nowadays, it isn’t uncommon to see lenders rapidly adopting a digital lending strategy to streamline the lending process</p>
            </div>
        </div>  
    </SwiperSlide>
       </Swiper>
       </div>
</div>

<style>
    .maindesktop{
        background:linear-gradient(90deg, #E0E1F5 0%, #F2F1E3 100.31%);;
border: 0.73875px solid rgba(0, 0, 0, 0.1);
box-shadow: 0px 37.6763px 79.0462px rgba(45, 48, 57, 0.09), 0px 15.7402px 33.0236px rgba(45, 48, 57, 0.0646969), 0px 8.41548px 17.656px rgba(45, 48, 57, 0.0536497), 0px 4.71765px 9.89782px rgba(45, 48, 57, 0.045), 0px 2.50551px 5.25666px rgba(45, 48, 57, 0.0363503), 0px 1.0426px 2.18741px rgba(45, 48, 57, 0.0253031);
border-radius: 8.865px;
    }
    .maincontent
    {
        background: linear-gradient(97.36deg, #18A0FB 4.4%, rgba(255, 255, 255, 0) 107.69%);
        animation: gradient 15s ease infinite;
        background-size: 400% 400%;
    }

    @keyframes gradient {
	0% {
		background-position: 0% 50%;
	}
	50% {
		background-position: 100% 50%;
	}
	100% {
		background-position: 0% 50%;
	}
}

    .bgcard:hover
    {
        background: rgba(255, 255, 255, 0.2);
border: 2px solid #E3E3E3;
backdrop-filter: blur(2px);

/* Note: backdrop-filter has minimal browser support */
border-radius: 15px;
    }
    .bgcards
    {
        background: rgba(255, 255, 255, 0.2);
border: 2px solid #E3E3E3;
backdrop-filter: blur(2px);

/* Note: backdrop-filter has minimal browser support */
border-radius: 15px;
    }

    @media(max-width:480px)
    {
        .mobicon
        {
            display:none;
        }
    }
</style>
