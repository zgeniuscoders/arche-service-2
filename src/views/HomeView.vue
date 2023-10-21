<script setup lang="ts">
import ServiceSection from "../components/ServiceSection.vue"
import CommentSection from "../components/CommentSection.vue"
import BlogSection from "../components/BlogSection.vue"
import NewsLetterSection from "@/components/NewsLetterSection.vue";
</script>

<template>
  <main class="mx-auto max-w-screen-xl p-4">

    <!-- banner  -->
    <section>
      <div class="grid md:grid-cols-2 gap-6">
        <div class="flex flex-col justify-center">
          <h1 class="text-3xl mb-4">Bienvenu sur arche service</h1>
          <p>Arche Service est votre guichet unique pour des solutions informatiques sur mesure. Notre équipe expérimentée
            est
            prête à donner vie à vos idées, que ce soit la création d'applications mobiles, de sites web, l'hébergement de
            sites, la conception d'affiches percutantes ou le montage vidéo professionnel. Nous mettons notre expertise à
            votre
            service pour répondre à tous vos besoins informatiques. Faites confiance à Arche Service pour concrétiser vos
            projets numériques avec excellence.</p>
        </div>

        <img src="../assets/banner.jpg" alt="">
      </div>
      <button class="bg-blue-700 text-white px-4 py-2 rounded-full">decouvrir</button>

    </section>

    <ServiceSection />

    <CommentSection />

    <BlogSection />

    <NewsLetterSection/>
  </main>
</template>
