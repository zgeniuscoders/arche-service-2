<template>
    <section class="md:my-12">
        <div class="grid mb-8 border border-gray-200 rounded-lg shadow-sm  md:grid-cols-2">
            <figure v-for="tt in 4" :key="tt"
                class="flex flex-col items-center justify-center p-8 text-center bg-white border-b border-gray-200 rounded-t-lg md:rounded-t-none md:rounded-tl-lg md:border-r ">
                <blockquote class="max-w-2xl mx-auto mb-4 text-gray-500 lg:mb-8 ">
                    <h3 class="text-lg font-semibold text-gray-900 ">Very easy this was to integrate</h3>
                    <p class="my-4">If you care for your time, I hands down would go with this."</p>
                </blockquote>
                <figcaption class="flex items-center justify-center space-x-3">
                    <img class="rounded-full w-9 h-9"
                        src="https://flowbite.s3.amazonaws.com/blocks/marketing-ui/avatars/karen-nelson.png"
                        alt="profile picture">
                    <div class="space-y-0.5 font-medium text-left">
                        <div>Bonnie Green</div>
                        <div class="text-sm text-gray-500 ">Developer at Open AI</div>
                    </div>
                </figcaption>
            </figure>
        </div>
    </section>
</template>

<script setup lang="ts"></script>