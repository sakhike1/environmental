<template>
  <div class="bg-white py-6 sm:py-8 lg:py-40">
    <div class="max-w-screen-2xl px-4 md:px-8 mx-auto">
      <h2
        class="text-green-700 text-2xl lg:text-3xl font-bold text-center mb-4 md:mb-6"
      >
        About Mpiloenviroservices
      </h2>

      <p
        class="max-w-screen-md text-base text-gray-500 md:text-lg text-center mx-auto"
      >
        Mpiloenviroservices is responsible for protecting and improving the
        environment as a valuable asset for the people of South africa. We are
        committed to protecting people and the environment from the harmful
        effects of radiation and pollution. We play key roles in environmental
        regulation, provision of knowledge and advocacy for the environment. we
        provide assessments and evidence to inform decision making and
        implements effective regulation and environmental compliance systems –
        while working with others to advocate for a clean, healthy and well
        protected environment and sustainable environmental behaviour
      </p>
    </div>
  </div>

  <div class="bg-white py-6 sm:py-8 lg:py-12">
    <div class="max-w-screen-2xl px-4 md:px-8 mx-auto">
      <div
        class="md:h-80 flex flex-col sm:flex-row bg-gray-200 rounded-lg overflow-hidden"
      >
        <!-- image - start -->
        <div
          class="w-full sm:w-1/2 lg:w-2/5 h-48 sm:h-auto order-first sm:order-none bg-gray-300"
        >
          <img
            src="https://images.unsplash.com/photo-1607925482346-9c01848c2946?auto=format&q=75&fit=crop&w=1000"
            loading="lazy"
            alt="Photo by Andras Vas"
            class="w-full h-full object-cover object-center"
          />
        </div>
        <!-- image - end -->

        <!-- content - start -->
        <div
          class="w-full sm:w-1/2 bg-gradient-to-r from-green-500 to-green-700 lg:w-3/5 flex flex-col p-4 sm:p-8"
        >
          <h2 class="text-white text-xl md:text-2xl lg:text-4xl font-bold mb-4">
            Speak to an environmental spealist
          </h2>

          <p class="max-w-md font-light font-sans text-sm text-white mb-8">
            We take big and small project, we are always ready to get the job
            done we have the right skill and the capacity to complete any task
            on time.
          </p>

          <div class="mt-auto">
            <a
              href="/contact"
              class="inline-block transition duration-500 ease-in-out transform hover:-translate-y-1 bg-white hover:bg-gray-100 active:bg-green-200 focus-visible:ring ring-indigo-300 text-gray-800 text-sm md:text-base font-semibold text-center rounded-lg outline-none transition duration-100 px-8 py-3"
              >Contact us</a
            >
          </div>
        </div>
        <!-- content - end -->
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "about",
  components: {},
};
</script>
