<script setup>
import HeaderSection from '../../components/HeaderSection.vue';

</script>

<template>
    <section class="powers mb-10 sm:mb-20" data-aos="fade-up" data-aos-duration="1000">
        <HeaderSection :title="'My Superpowers'" />
        <div class="techs flex flex-wrap gap-10">
            <img title="Grafana" src="/images/stacks/grafana.png" alt="" class="tech mb-10 w-[18%] sm:w-24 object-contain">
            <img title="Pytorch" src="/images/stacks/torch.jpeg" alt="" class="tech mb-10 w-[18%] sm:w-24 object-contain">
            <img title="Scikit-Learn" src="/images/stacks/sklearn.png" alt="" class="tech mb-10 w-[18%] sm:w-24 object-contain">
            <img title="Numpy" src="/images/stacks/numpy.png" alt="" class="tech mb-10 w-[18%] sm:w-24 object-contain">
            <img title="Pandas" src="/images/stacks/pandas.jpeg" alt="" class="tech mb-10 w-[18%] sm:w-24 object-contain">
            <img title="SQL" src="/images/stacks/sql.png" alt="" class="tech mb-10 w-[18%] sm:w-20 object-contain">
            <img title="Python" src="/images/stacks/python.png" alt="" class="tech mb-10 w-[18%] sm:w-24 object-contain">
            <img title="Tableau" src="/images/stacks/mytableau.png" alt="" class="tech mb-10 w-[18%] sm:w-24 object-contain">
            <img title="Visual Studio Code" src="/images/stacks/vscode.png" alt="" class="tech mb-10 w-[18%] sm:w-24 object-contain">
            <img title="Git" src="/images/stacks/git.png" alt="" class="tech mb-10 w-[18%] sm:w-24 object-contain">
            <img title="Deep Learning" src="/images/stacks/deep_learning.png" alt="" class="tech mb-10 w-[18%] sm:w-24 object-contain">
            <img title="Postgres" src="/images/stacks/postgres.png" alt="" class="tech mb-10 w-[18%] sm:w-24 object-contain">
            <img title="Predictive Analysis" src="/images/stacks/predictive.jpg" alt="" class="tech mb-10 w-[18%] sm:w-20 object-contain">
            <img title="Excel" src="/images/stacks/excel.png" alt="" class="tech mb-10 w-[18%] sm:w-20 object-contain">
            <img title="Web Scrapping" src="/images/stacks/scraped.png" alt="" class="tech mb-10 w-[18%] sm:w-24 object-contain">
        </div>
    </section>
</template>