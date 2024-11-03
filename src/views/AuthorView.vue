<script setup lang="ts">
import MainLayout from '@/layouts/MainLayout.vue'
</script>

<template>
  <MainLayout>
    <header data-layername="authorHeader" class="flex flex-col pt-20">
      <div data-layername="background" class="flex flex-col items-center px-20 pt-32 w-full bg-gray-100 max-md:px-5 max-md:pt-24 max-md:max-w-full">
        <div class="flex flex-col w-full max-w-screen-lg max-md:max-w-full">
          <div class="max-w-full w-[952px]">
            <div class="flex gap-5 max-md:flex-col">
              <div data-layername="column" class="flex flex-col w-[27%] max-md:ml-0 max-md:w-full">
                <img src="@/assets/images/misc/man-wearing-sunglasses.png" alt="Author's portrait" class="object-contain grow w-full aspect-[0.85] max-md:mt-8" />
              </div>
              <div data-layername="column" class="flex flex-col ml-5 w-[73%] max-md:ml-0 max-md:w-full">
                <div class="flex flex-col max-md:mt-9 max-md:max-w-full">
                  <h1 data-layername="heyThereImAndrewJonhsonAndWelcomeToMyBlog" class="text-5xl font-bold tracking-tighter text-gray-800 leading-[64px] max-md:max-w-full max-md:text-4xl max-md:leading-[60px]">
                    Hey there, I'm Andrew Jonhson and welcome to my Blog
                  </h1>
                  <p data-layername="loremIpsumDolorSitAmetConsecteturAdipiscingElitSedDoEiusmodTemporIncididuntUtLaboreEtDoloreMagnaAliquaNonBlanditMassaEnimNecScelerisqueViverraMaurisInAliquamSemAtRisusViverraAdipiscingAtInTellus" class="mt-6 mr-5 text-base leading-7 text-zinc-500 max-md:mr-2.5 max-md:max-w-full">
                    Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Non blandit massa enim nec. Scelerisque viverra mauris in aliquam sem. At risus viverra adipiscing at in tellus.
                  </p>
                </div>
                <ul class="flex items-center gap-6 mt-2.5">
                  <li><a href="#"><img src="@/assets/images/logo/facebook.png" alt="Facebook" class="hover:opacity-75 transition duration-150 ease-in-out"></a></li>
                  <li><a href="#"><img src="@/assets/images/logo/twitter.png" alt="Twitter" class="hover:opacity-75 transition duration-150 ease-in-out"></a></li>
                  <li><a href="#"><img src="@/assets/images/logo/instagram.png" alt="Instagram" class="hover:opacity-75 transition duration-150 ease-in-out"></a></li>
                  <li><a href="#"><img src="@/assets/images/logo/linkedin.png" alt="LinkedIn" class="hover:opacity-75 transition duration-150 ease-in-out"></a></li>
                </ul>
              </div>
            </div>
          </div>
          <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/5c6adf65d2b2182cdb25b4a072861eb1ed209bb0f828b6136c6697d20e482490?placeholderIfAbsent=true&apiKey=0e885ef60c3640e6aa6ee17a0c7492e4" alt="" class="object-contain mt-28 w-full aspect-[43.48] max-md:mt-10 max-md:max-w-full" />
        </div>
      </div>
    </header>
    <section class = "flex flex-col gap-8 bg-white px-[80px] py-[40px]">
    <div class="flex gap-5 max-md:flex-col">
      <section class="flex flex-col w-[42%] max-md:ml-0 max-md:w-full">
        <h1 class="self-start text-5xl font-bold tracking-tighter leading-none text-gray-800 max-md:mt-8 max-md:text-4xl">
          My Posts
        </h1>
        <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/7a0cfd0b5f4bac1070110b31f5611e8edaf3d046aecde01dc829c8565e0f4e88?placeholderIfAbsent=true&apiKey=0e885ef60c3640e6aa6ee17a0c7492e4" alt="Blog post image 1" class="object-contain mt-16 w-full aspect-[1.29] max-md:mt-10" />
        <img loading="lazy" src="https://cdn.builder.io/api/v1/image/assets/TEMP/ca902affa6ca9d3191f1c419b95251b420de6faa3e6ebeeb56b702de796f1699?placeholderIfAbsent=true&apiKey=0e885ef60c3640e6aa6ee17a0c7492e4" alt="Blog post image 2" class="object-contain mt-16 w-full aspect-[1.29] max-md:mt-10" />
      </section>
      <section class="flex flex-col ml-5 w-[58%] max-md:ml-0 max-md:w-full">
        <article class="flex z-10 flex-col mt-48 mr-0 text-base font-semibold leading-none text-amber-300 max-md:mt-10 max-md:max-w-full">
          <span class="self-start uppercase tracking-[3px]">BUSINESS</span>
          <h2 class="self-start mt-5 text-4xl font-bold tracking-tighter leading-10 text-gray-800 max-md:max-w-full">
            Font sizes in UI design: The complete guide to follow
          </h2>
          <p class="mt-4 leading-7 text-zinc-500 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
        </article>
        <article class="flex z-10 flex-col mt-44 mr-0 text-base font-semibold leading-none text-amber-300 max-md:mt-10 max-md:max-w-full">
          <span class="self-start uppercase tracking-[3px]">ECONOMY</span>
          <h2 class="mt-5 mr-5 text-4xl font-bold tracking-tighter leading-10 text-gray-800 max-md:mr-2.5 max-md:max-w-full">
            How to build rapport with your web design clients
          </h2>
          <p class="mt-4 leading-7 text-zinc-500 max-md:max-w-full">
            Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
          </p>
        </article>
      </section>
    </div>
    </section>


  </MainLayout>
</template>
