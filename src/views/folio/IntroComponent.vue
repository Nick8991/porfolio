<script setup></script>

<template>
  <section class="intro flex flex-col items-start justify-center space-y-2">
    <div class="relative">
      <span
        class="text-2xl font-bold"
        v-motion
        :initial="{ opacity: 0 }"
        :enter="{ opacity: 1 }"
        :delay="1700"
        >Hello 👋, my name is</span
      >
      <h2
        class="text-5xl md:text-7xl font-bold text-important"
        v-motion
        :initial="{ opacity: 0 }"
        :enter="{ opacity: 1 }"
        :delay="1700 * 1.05"
      >
        Yannick Tiba Fomujang,
      </h2>
      <h3
        class="text-3xl md:text-5xl font-bold"
        v-motion
        :initial="{ opacity: 0 }"
        :enter="{ opacity: 1 }"
        :delay="1700 * 1.1"
      >
        a Data Scientist.
      </h3>
      <span
        class="text-lg block text-appgray mt-5 w-full sm:w-2/3"
        v-motion
        :initial="{ opacity: 0 }"
        :enter="{ opacity: 1 }"
        :delay="1700 * 1.15"
      >
      I'm a skilled data scientist with over three years of expertise in diverse data tasks. My skills span web scraping,
       data cleaning, and API integration, ensuring comprehensive data preparation. 
       I specialize in building strong classification models using scikit-learn and PyTorch, 
       and I'm equally adept in harnessing Microsoft Excel for detailed analysis and visualization.

      Moreover, I bring proficiency in SQL and PostgreSQL database management, enabling seamless data manipulation and extraction. Additionally, 
      I'm well-versed in Grafana, leveraging its capabilities to create insightful visualizations and monitor data trends effectively.
       This comprehensive skill set, coupled with my expertise in Seaborn, Matplotlib, and Tableau, 
       empowers me to transform complex data into compelling narratives, driving informed decisions and business success.</span
      >
      <a href="https://docs.google.com/document/d/16l0ngG4r6SQvhKJN8l5zso1cjNYwiSUs/edit?usp=sharing&ouid=107210240055740785384&rtpof=true&sd=true" target="_blank">
        <button
          class="btn bg-transparent hover:bg-important border-2 border-important text-important hover:text-black px-5 py-3 flex justify-between items-center space-x-3 mt-7"
          v-motion
          :initial="{ opacity: 0 }"
          :enter="{ opacity: 1 }"
          :delay="1700 * 1.1"
        >
          <span class="font-bold">Pull my CV</span>
          <font-awesome-icon icon="fa-regular fa-file" class="" />
        </button>
      </a>
    </div>
  </section>
</template>

<style scoped>
button {
  stroke: #64ffda;
  transition: all 0.3s ease-in-out;
}

button:hover {
  stroke: black;
}
</style>
