<script setup>
import HeaderSection from '../../components/HeaderSection.vue'
</script>

<template>
  <section
    class="about min-h-[70vh]"
    id="about"
    data-aos="fade-up"
    data-aos-duration="1000"
    data-oas-offset="5000px"
  >
    <HeaderSection :title="'About me'" />
    <div class="flex justify-center items-center m-auto">
      <div
        class="flex-row sm:flex sm:justify-between items-center sm:space-x-3 space-y-7 sm:space-y-0"
      >
        <div class="text sm:w-[60%] space-y-2 text-sm md:text-base text-appgray font-medium">
          <p class="leading-relaxed">
            Hello there! I'm Yannick Tiba, a passionate data scientist who thrives on unlocking insights from complex datasets.
            My journey into the world of data science began a few years back, sparked by my fascination with uncovering meaningful patterns from raw information. 
            Since then, I've immersed myself in various technologies and methodologies to harness the power of data effectively.
          </p>
          <p class="leading-relaxed">
            My expertise encompasses a range of tools and frameworks essential in the realm of data science, 
            including Python, SQL, and machine learning libraries such as scikit-learn and PyTorch. 
            I'm well-versed in implementing statistical models, and I have hands-on experience with deep learning models and 
            visualization tools like Tableau and Matplotlib, 
            transforming intricate data into compelling visual stories.
          </p>
          <p class="leading-relaxed">
            Throughout my career, I've contributed to diverse projects, from predictive analytics models to data-driven business solutions. 
            Collaborating with multidisciplinary teams has provided me with a profound understanding of project dynamics,
             effective communication, and the art of translating technical findings into actionable insights.
          </p>
          <p class="leading-relaxed">
            Beyond the data world, I nurture various interests that enrich both my personal and professional growth. 
            I'm an avid reader, continually exploring new research and methodologies in the data science field.
             Additionally, I find solace in outdoor activities, providing a refreshing balance to my analytical pursuits.

             I'm driven by the pursuit of unlocking the potential within data and transforming it into actionable intelligence that drives informed decision-making.
          </p>
        </div>
        <div :class="'h-[390px] bg-orange-390 sm:w-[40%]'">
          <img src="/images/tiba.jpeg" alt="Tiba's Picture">
        </div>
      </div>
    </div>
  </section>
</template>

<style scoped></style>
