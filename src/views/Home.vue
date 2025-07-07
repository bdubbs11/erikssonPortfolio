
<template>
  <div class="flex flex-col items-center justify-center">
    <div class="container grid grid-cols-16 mx-auto min-h-screen">
      <div class="text-center col-span-16 p-2 m-2 ">

        <div class="grid grid-cols-1 md:grid-cols-16 p-2 mt-2">
          <!-- sm:col-span-8 lg:col-span-10 -->
          <div class="order-2 md:order-1 md:col-span-8 flex flex-col justify-center md:text-left">
            <h1 class="text-3xl md:text-5xl mb-4">Hello, I'm William.</h1>
            <h1 class="text-xl md:text-3xl mb-4">Project Coordinator (Strategy and Hospitality Development) specializing in data-driven dashboards and analytics.</h1>


            <p class="text-sm md:text-lg mb-2 md:mb-4" >Turning raw data into powerful insights with tools like Power BI, Tableau, SQL, and Excel.</p>
            <a href="/projects" class="text-xs md:text-sm underline opacity-75 mb-2 md:mb-4">check out my projects</a>

            <div class="flex justify-center md:justify-start">
              <a class="inline-block rounded-xs px-6 py-2 mt-10 md:mt-20 bg-accent transition-transform hover:bg-accent/80 hover:text-white/80 duration-300 text-xs md:text-md" href="/images/files/William_Eriksson_resume.docx" download>
                Download Resume
              </a>
            </div> 
          </div>

          <div class="md:col-span-8 items-center justify-center md:justify-end h-[30rem] md:h-[44rem] flex relative order-1 md:order-2">
            <div class="relative h-3/4 w-auto">
              <img class="h-full w-auto object-cover relative transform -translate-x-2 -translate-y-2 " src="/images/headshot.jpeg" alt="william eriksson headshot">
              <div class="absolute top-0 left-0 h-full w-full bg-accent transform translate-x-2 translate-y-2 -z-10"></div>
            </div>
          </div>
        </div>


      </div>


    </div>

  </div>
</template>
