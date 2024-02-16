  <script>
     const image1 = "images/image1.png"
     const image2 = "images/image2.png"
     const image3 =  "images/image3.png"   
  </script>
  
  <div class="mt-20 mb-10">
    <div class="bg-gray-100 text-gray-800">
        <div class="relative container mx-auto px-6 flex flex-col space-y-8">
            <div
                class="absolute z-0 w-2 h-full bg-indigo-900 shadow-md inset-0 left-11 md:mx-auto md:right-0 md:left-0" id="animatedDiv"
            ></div>
            <div class="relative z-1">
                <img 
                    src={image1}
                    alt="error"
                    class="h-12 w-12 object-cover rounded-full shadow-md border-4 border-white xs:absolute md:mx-auto md:left-0 md:right-0"
                />
                <div class="relative pt-2 xs:pl-28 xs:pt-0 md:w-1/2 md:ml-auto md:pl-16">
                    <!-- <div class="absolute inset-0 left-10 h-4 w-4 transform rotate-45 bg-white xs:top-11 xs:left-26 md:left-14 timeline-pointer" aria-hidden="true"></div> -->
                    <div class="bg-white p-6 rounded-md shadow-md">
                        <span class="font-bold text-indigo-600 text-sm tracking-wide">Jan 2021</span>
                        <h1 class="text-2xl font-bold pt-1">Lorem, ipsum dolor.</h1>
                        <p class="pt-1">
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ex iste suscipit reiciendis, perferendis vel consequuntur cupiditate ad commodi provident, sapiente veniam sed autem.
                        </p>
                    </div>
                </div>
            </div>

            <div class="relative z-1">
                <img
                    src={image2}
                    alt=""
                    class="h-12 w-12 object-cover rounded-full shadow-md border-4 border-white xs:absolute md:mx-auto md:left-0 md:right-0"
                />
                <div class="relative mt-2 md:w-1/2 md:ml-0 md:mr-auto md:pl-0 md:pr-16">
                    <!-- <div class="absolute inset-0 left-10 h-4 w-4 transform rotate-45 bg-white xs:top-11 xs:left-26 md:left-14 timeline-pointer timeline-pointer-left" aria-hidden="true"></div> -->
                    <div class="bg-white p-6 rounded-md shadow-md">
                        <span class="font-bold text-indigo-600 text-sm tracking-wide">Aug 2020</span>
                        <h1 class="text-2xl font-bold pt-1">Lorem ipsum dolor sit amet.</h1>
                        <p class="pt-1">
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ex iste suscipit reiciendis, perferendis vel consequuntur cupiditate ad commodi provident, sapiente veniam sed
                        </p>
                    </div>
                </div>
            </div>

            <div class="relative z-1">
                <img
                    src={image3}
                    alt=""
                    class="h-12 w-12 object-cover rounded-full shadow-md border-4 border-white xs:absolute md:mx-auto md:left-0 md:right-0"
                />
                <div class="relative pt-2 xs:pl-28 xs:pt-0 md:w-1/2 md:ml-auto md:pl-16 timeline-container">
                    <!-- <div class="absolute inset-0 left-10 h-4 w-4 transform rotate-45 bg-white xs:top-11 xs:left-26 md:left-14 timeline-pointer" aria-hidden="true"></div> -->
                    <div class="bg-white p-6 rounded-md shadow-md">
                        <span class="font-bold text-indigo-600 text-sm tracking-wide">March 2020</span>
                        <h1 class="text-2xl font-bold pt-1">Lorem, ipsum dolor.
                        </h1>
                        <p class="pt-1">
                            Lorem ipsum dolor, sit amet consectetur adipisicing elit. Ex iste suscipit reiciendis, perferendis vel consequuntur cupiditate ad commodi provident, sapiente veniam sed autem, perspiciatis
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </div>
  </div>


 