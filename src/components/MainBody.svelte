<script>
 import { Swiper, SwiperSlide } from "swiper/svelte";
 import "swiper/css";
 import Time from "svelte-time";
 import { Mousewheel, Pagination } from "swiper";

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
      <div class="maincontent mx-1 my-1 rounded max-h-[80vh] overflow-scroll">

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
            <div class="container mx-auto px-10 lg:px-20 flex flex-col lg:flex-row gap-5 text-center items-center lg:h-[80vh] justify-center">
                <div class="flex flex-col gap-5 w-[100%] lg:w-[50%]">
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

    @media(max-width:480px)
    {
        .mobicon
        {
            display:none;
        }
    }
</style>