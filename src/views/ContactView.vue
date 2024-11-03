<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
</script>

<template>
  <MainLayout>
    <!-- Header Section -->
    <section class="flex flex-col items-center text-center text-gray-800 max-w-[749px] mx-auto my-8">
      <h2 class="font-black uppercase tracking-[3px] text-gray-700">Contact Us</h2>
      <h3 class="mt-3 text-5xl font-bold text-gray-900">Let's Start a Conversation</h3>
      <p class="mt-6 text-zinc-500 text-lg">
        Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim.
      </p>
    </section>

    <!-- Contact Information Section -->
    <section class="bg-yellow-400 px-16 py-12 mx-auto max-w-screen-md rounded-md mt-8">
      <div class="flex gap-10">
        <!-- Working Hours -->
        <div class="w-1/2">
          <h2 class="text-sm opacity-60">Working hours</h2>
          <hr class="my-4 border-t border-gray-600 opacity-10" />
          <p class="text-xl font-bold">Monday To Friday</p>
          <p class="text-xl font-bold">9:00 AM to 8:00 PM</p>
          <p class="text-base text-neutral-600 opacity-60">Our Support Team is available 24/7</p>
        </div>
        
        <!-- Contact Us -->
        <div class="w-1/2">
          <h2 class="text-sm opacity-60">Contact Us</h2>
          <hr class="my-4 border-t border-gray-600 opacity-10" />
          <p class="text-xl font-bold">020 7993 2905</p>
          <p class="text-base text-neutral-600 opacity-60">hello@finsweet.com</p>
        </div>
      </div>
    </section>

    <!-- Contact Form Section -->
    <section class="flex flex-col items-center mx-auto max-w-screen-md mt-8 space-y-4 mb-16"> 
      <input type="text" placeholder="Full Name" class="w-full p-4 border border-gray-300 rounded-md" />
      <input type="email" placeholder="Your Email" class="w-full p-4 border border-gray-300 rounded-md" />
      
      <!-- Dropdowns for Province and City -->
      <div class="flex gap-4 w-full">
        <select class="w-1/2 p-4 border border-gray-300 rounded-md">
          <option>Province</option>
        </select>
        <select class="w-1/2 p-4 border border-gray-300 rounded-md">
          <option>City</option>
        </select>
      </div>
      
      <!-- Message Textarea -->
      <textarea placeholder="Message" class="w-full p-4 border border-gray-300 rounded-md h-32"></textarea>
      
      <!-- Submit Button -->
      <button class="w-full py-4 mt-4 text-white bg-blue-600 rounded-md">Send Message</button>
    </section>
  </MainLayout>
</template>
