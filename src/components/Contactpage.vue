<template>
  <section class="dark:bg-coolGray-800 dark:text-coolGray-100">
    <div
      class="container mx-auto flex flex-col items-center px-4 py-16 text-center md:py-32 md:px-10 lg:px-32 xl:max-w-3xl"
    >
      <h1 class="text-4xl font-bold leading-none sm:text-5xl"
        >Get in touch for any environmental service you
        <span class="dark:text-violet-400">require from us</span>
      </h1>
      <p class="px-8 mt-8 mb-12 text-lg"
        >In nature’s economy the currency is not money, it is life</p
      >
    </div>
  </section>
  <section class="dark:bg-coolGray-800 dark:text-coolGray-100">
    <div class="container max-w-6xl p-6 mx-auto space-y-6 sm:space-y-12">
      <a
        rel="noopener noreferrer"
        href="#"
        class="block max-w-sm gap-3 mx-auto sm:max-w-full group hover:no-underline focus:no-underline lg:grid lg:grid-cols-12 dark:bg-coolGray-900"
      >
        <img
          src="https://images.pexels.com/photos/3617500/pexels-photo-3617500.jpeg?auto=compress&amp;cs=tinysrgb&amp;dpr=2&amp;w=500"
          alt=""
          class="object-cover transition duration-500 ease-in-out transform hover:-translate-y-1 w-full h-64 rounded sm:h-96 lg:col-span-7 dark:bg-coolGray-500"
        />
        <div class="p-6 space-y-2 lg:col-span-5">
          <p
            >As the increase in temperature is concerning, there is a need to
            keep a watch on the toxic compounds we ingest that pollute the
            atmosphere. We need to adopt environmentally sustainable methods to
            minimise</p
          >
        </div>
      </a>
    </div>
  </section>
  <div class="bg-white py-6 sm:py-8 lg:py-12">
    <div class="max-w-screen-2xl px-4 md:px-8 mx-auto">
      <!-- form - start -->
      <form class="max-w-screen-md grid sm:grid-cols-2 gap-4 mx-auto">
        <div>
          <label
            for="first-name"
            class="inline-block text-gray-800 text-sm sm:text-base mb-2"
            >First name*</label
          >
          <input
            name="first-name"
            class="w-full bg-gray-50 text-gray-800 border focus:ring ring-indigo-300 rounded outline-none transition duration-100 px-3 py-2"
          />
        </div>

        <div>
          <label
            for="last-name"
            class="inline-block text-gray-800 text-sm sm:text-base mb-2"
            >Last name*</label
          >
          <input
            name="last-name"
            class="w-full bg-gray-50 text-gray-800 border focus:ring ring-indigo-300 rounded outline-none transition duration-100 px-3 py-2"
          />
        </div>

        <div class="sm:col-span-2">
          <label
            for="company"
            class="inline-block text-gray-800 text-sm sm:text-base mb-2"
            >Company</label
          >
          <input
            name="company"
            class="w-full bg-gray-50 text-gray-800 border focus:ring ring-indigo-300 rounded outline-none transition duration-100 px-3 py-2"
          />
        </div>

        <div class="sm:col-span-2">
          <label
            for="email"
            class="inline-block text-gray-800 text-sm sm:text-base mb-2"
            >Email*</label
          >
          <input
            name="email"
            class="w-full bg-gray-50 text-gray-800 border focus:ring ring-indigo-300 rounded outline-none transition duration-100 px-3 py-2"
          />
        </div>

        <div class="sm:col-span-2">
          <label
            for="subject"
            class="inline-block text-gray-800 text-sm sm:text-base mb-2"
            >Subject*</label
          >
          <input
            name="subject"
            class="w-full bg-gray-50 text-gray-800 border focus:ring ring-indigo-300 rounded outline-none transition duration-100 px-3 py-2"
          />
        </div>

        <div class="sm:col-span-2">
          <label
            for="message"
            class="inline-block text-gray-800 text-sm sm:text-base mb-2"
            >Message*</label
          >
          <textarea
            name="message"
            class="w-full h-64 bg-gray-50 text-gray-800 border focus:ring ring-indigo-300 rounded outline-none transition duration-100 px-3 py-2"
          ></textarea>
        </div>

        <div class="sm:col-span-2 flex justify-between items-center">
          <button
            class="inline-block transition duration-500 ease-in-out transform hover:-translate-y-1 bg-indigo-500 hover:bg-indigo-600 active:bg-indigo-700 focus-visible:ring ring-indigo-300 text-white text-sm md:text-base font-semibold text-center rounded-lg outline-none transition duration-100 px-8 py-3"
            >Send</button
          >

          <span class="text-gray-500 text-sm">*Required</span>
        </div>
      </form>
      <!-- form - end -->
    </div>
  </div>
</template>
