<template>
  <!-- https://tailwindcomponents.com/component/youtube-home-timeline -->
  <div class="flex justify-center p-8 bg-[#181818]">
    <div class="grid grid-cols-12 gap-6 gap-y-6">

      <!-- Video 1 -->
      <div v-for="video in videos" class="col-span-6 sm:col-span-6 md:col-span-3">
        <div class="flex flex-col w-full">
          <div class="relative">

            <!-- Image Video -->
            <a href="#">
              <img :src="video.url" class="h-[120px] lg:h-[200px] w-96" />
              <div v-if="video.isplayed" class="bg-red-800 h-[3px]" :class="`w-[${ video.playedpercent }%]`"></div>
            </a>

            <p v-if="!video.live" class="absolute px-1 text-xs text-gray-100 bg-gray-900 right-2 bottom-2 py"> {{ video.duration }} </p>
          </div>

          <div class="flex flex-row gap-2 mt-2">

            <!-- Profile Picture -->
            <a class="flex-none" href="#">
              <img :src="video.authorpic" class="rounded-full  w-10" />
            </a>

            <!-- Description -->
            <div clas="flex flex-col">
              <a href="#">
                <p class="text-sm font-semibold text-gray-100"> {{ truncate(video.title, 50) }} </p>
              </a>
              <a class="mt-2 text-xs text-gray-400 hover:text-gray-100" href="#"> {{ video.authorname }} </a>
              <p v-if="!video.live" class="mt-1 text-xs text-gray-400">{{ video.views }} <span style="font-size: 50px">.</span> {{ video.elapsedtime }}</p>
              <p v-if="video.live" class="mt-1 text-xs text-gray-400">{{ video.views }} watching</p>

              <div v-if="video.live">
                <button class="text-red-600 border border-red-600 px-2 font-semibold rounded-[4px] uppercase text-sm my-2">
                  Live now
                </button>
              </div>
            </div>

          </div>
        </div>
      </div>



    </div>
  </div>
</template>


<script setup lang="ts">
import {ref} from "~/.nuxt/imports";

 // interface Video {
//   url: string,
//  duration: string,
//  authorpic: string,
//  title: string,
//  authorname: string,
//  views: string,
//  elapsedtime: string,
//  live: boolean,
//}

  const videos = ref([
    {
      url: 'https://i.ytimg.com/vi/p9gpouZp2QA/hqdefault_live.jpg?sqp=CLSE4JIG-oaymwEcCOADEI4CSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCpRyoglkELGDFn7k6cL-pSavQGzA',
      duration: '1.15',
      authorpic: 'https://yt3.ggpht.com/3RMarDSmUSIexCXWCpMUkqV64uiHDXTidBLwsObHstx5-AbB8h_n8Zy1W9JymURd7ivzlDEGFw=s48-c-k-c0x00ffffff-no-rj',
      title: 'Ibiza Summer Mix 2022 🍓 Best Of Tropical Deep House Music Chill Out Mix 2022 🍓 Chillout Lounge',
      authorname: 'Miracle Music',
      views: '42',
      elapsedtime: '3 years ago',
      live: true
    },
    {
      url: 'https://i.ytimg.com/vi/xYD2SQljwJo/hqdefault.jpg?sqp=-oaymwEXCOADEI4CSFryq4qpAwkIARUAAIhCGAE=&rs=AOn4CLCEA9tz_d6iu6iUBqPpd6oyLnKMlQ',
      duration: '2:52',
      authorpic: 'https://yt3.ggpht.com/ytc/AKedOLRNn6Pxk5RhZLqZIr3mOH4YNVJBUz4Vvutfg_Ff9w=s88-c-k-c0x00ffffff-no-rj',
      title: 'Omah Lay - Lo Lo (Official Video)',
      authorname: 'Omah Lay',
      views: '30 M',
      elapsedtime: '1 year ago',
      isplayed: true,
      playedpercent: 70,
    },
    {
      url: 'https://i.ytimg.com/vi/-FrOfXMzvAQ/hqdefault.jpg?sqp=-oaymwEcCOADEI4CSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDfV1TjF0grVEhuSoJH0OjaOSu0Tw',
      duration: '13:29',
      authorpic: 'https://yt3.ggpht.com/WnyA-RJFsCqsfQbOs5HGCHe_lbGONhO3Q5nrh1IEc24JQsvnwn6Lpqfe56rAQ1uhZGd935N0OQ=s48-c-k-c0x00ffffff-no-rj',
      title: 'Trust In God When You Don\'t Understand | Steve Harvey, Les Brown, Joel Osteen | Best Motivation 2022',
      authorname: 'Motivation 2 Inspire',
      views: '51K',
      elapsedtime: '4 weeks ago'
    },
    {
      url: 'https://i.ytimg.com/vi/O7z_anlApZ0/hqdefault.jpg?sqp=-oaymwEcCOADEI4CSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLC1gv0hFjlafbgv2r3irqbZUVP7lw',
      duration: '1:15',
      authorpic: 'https://yt3.ggpht.com/81B_ZYvPMQ8hsd7_7YyRdngHmI8WcSxoj2dAPZGX57s9V6ypnRzROxDWqqiyZRcFZ55rWygf=s68-c-k-c0x00ffffff-no-rj',
      title: 'Stromae - Multitude [ Full Album | Album complet ]',
      authorname: 'Marshinobi',
      views: '38K',
      elapsedtime: '1 month ago',
      isplayed: true,
      playedpercent: 100
    },
    {
      url: 'https://i.ytimg.com/vi/VPvVD8t02U8/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLAGtsbxbaABA-QwThK17YZarEhJyw',
      duration: '36:29:22',
      authorpic: 'https://yt3.ggpht.com/ytc/AKedOLRyPFojwY3CXV5ks5TwPrt2VifQn-nYNfkgLvVPkw=s68-c-k-c0x00ffffff-no-rj',
      title: 'Flutter Course for Beginners – 37-hour Cross Platform App Development Tutorial',
      authorname: 'freeCodeCamp.org',
      views: '435K',
      elapsedtime: '1 month ago'
    },
    {
      url: 'https://i.ytimg.com/vi/6oAdJjzXQS8/hq720_live.jpg?sqp=COiU4JIG-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDkwm-KhFHtG93Kh4MXDAg1DKRY1Q',
      authorpic: 'https://yt3.ggpht.com/ytc/AKedOLSw37zHOSiciOsXJp0oRTSn0DjaqA5EBvPtU8RUaQ=s48-c-k-c0x00ffffff-no-rj',
      title: 'Relaxing Piano Music & Water Sounds 24/7 - Ideal for Stress Relief and Healing',
      authorname: 'OCB Relax Music',
      views: '877',
      live: true
    },
    {
      url: 'https://i.ytimg.com/vi/yTTCx4-LsLQ/hq720_live.jpg?sqp=CJi04ZIG-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLBodegFG88o1NOxi0KiDLVwE_nuDA',
      authorpic: 'https://yt3.ggpht.com/h7b6wa8_7dFMZRr9qeyD2qPPRbKDryKCI7ks0PKKpoS98IefZd5tl5Xm1pq-uRzDVmklfQKBWEw=s48-c-k-c0x00ffffff-no-nd-rj',
      title: '🔴 Deep Focus Music 24/7 - Beautiful Relaxing Music, Peaceful Soothing Instrumental Music',
      authorname: '4K Video Nature - Focus Music\n',
      views: '447',
      live: true
    },
    {
      url: 'https://i.ytimg.com/vi/WLQDpY7lOLg/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLAXi1Aa9uFE1yAjVUJQSkT1Doywag',
      duration: '5:18:44',
      authorpic: 'https://yt3.ggpht.com/ytc/AKedOLSaQFgUzVlatJkpyAzXZU1Vvy_26MUyYYXg9O3qkg=s68-c-k-c0x00ffffff-no-rj',
      title: 'I Built Full Stack Application with Laravel, Vue 3 and Tailwindcss',
      authorname: 'The Codeholic',
      views: '173K',
      elapsedtime: '2 months ago'
    },
    {
      url: 'https://i.ytimg.com/vi/p9gpouZp2QA/hqdefault_live.jpg?sqp=CLSE4JIG-oaymwEcCOADEI4CSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLCpRyoglkELGDFn7k6cL-pSavQGzA',
      duration: '1.15',
      authorpic: 'https://yt3.ggpht.com/3RMarDSmUSIexCXWCpMUkqV64uiHDXTidBLwsObHstx5-AbB8h_n8Zy1W9JymURd7ivzlDEGFw=s48-c-k-c0x00ffffff-no-rj',
      title: 'Ibiza Summer Mix 2022 🍓 Best Of Tropical Deep House Music Chill Out Mix 2022 🍓 Chillout Lounge',
      authorname: 'Miracle Music',
      views: '42',
      elapsedtime: '3 years ago',
      live: true
    },
    {
      url: 'https://i.ytimg.com/vi/xYD2SQljwJo/hqdefault.jpg?sqp=-oaymwEXCOADEI4CSFryq4qpAwkIARUAAIhCGAE=&rs=AOn4CLCEA9tz_d6iu6iUBqPpd6oyLnKMlQ',
      duration: '2:52',
      authorpic: 'https://yt3.ggpht.com/ytc/AKedOLRNn6Pxk5RhZLqZIr3mOH4YNVJBUz4Vvutfg_Ff9w=s88-c-k-c0x00ffffff-no-rj',
      title: 'Omah Lay - Lo Lo (Official Video)',
      authorname: 'Omah Lay',
      views: '30 M',
      elapsedtime: '1 year ago',
      isplayed: true,
      playedpercent: 70,
    },
    {
      url: 'https://i.ytimg.com/vi/-FrOfXMzvAQ/hqdefault.jpg?sqp=-oaymwEcCOADEI4CSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDfV1TjF0grVEhuSoJH0OjaOSu0Tw',
      duration: '13:29',
      authorpic: 'https://yt3.ggpht.com/WnyA-RJFsCqsfQbOs5HGCHe_lbGONhO3Q5nrh1IEc24JQsvnwn6Lpqfe56rAQ1uhZGd935N0OQ=s48-c-k-c0x00ffffff-no-rj',
      title: 'Trust In God When You Don\'t Understand | Steve Harvey, Les Brown, Joel Osteen | Best Motivation 2022',
      authorname: 'Motivation 2 Inspire',
      views: '51K',
      elapsedtime: '4 weeks ago'
    },
    {
      url: 'https://i.ytimg.com/vi/O7z_anlApZ0/hqdefault.jpg?sqp=-oaymwEcCOADEI4CSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLC1gv0hFjlafbgv2r3irqbZUVP7lw',
      duration: '1:15',
      authorpic: 'https://yt3.ggpht.com/81B_ZYvPMQ8hsd7_7YyRdngHmI8WcSxoj2dAPZGX57s9V6ypnRzROxDWqqiyZRcFZ55rWygf=s68-c-k-c0x00ffffff-no-rj',
      title: 'Stromae - Multitude [ Full Album | Album complet ]',
      authorname: 'Marshinobi',
      views: '38K',
      elapsedtime: '1 month ago',
      isplayed: true,
      playedpercent: 100
    },
    {
      url: 'https://i.ytimg.com/vi/VPvVD8t02U8/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLAGtsbxbaABA-QwThK17YZarEhJyw',
      duration: '36:29:22',
      authorpic: 'https://yt3.ggpht.com/ytc/AKedOLRyPFojwY3CXV5ks5TwPrt2VifQn-nYNfkgLvVPkw=s68-c-k-c0x00ffffff-no-rj',
      title: 'Flutter Course for Beginners – 37-hour Cross Platform App Development Tutorial',
      authorname: 'freeCodeCamp.org',
      views: '435K',
      elapsedtime: '1 month ago'
    },
    {
      url: 'https://i.ytimg.com/vi/6oAdJjzXQS8/hq720_live.jpg?sqp=COiU4JIG-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLDkwm-KhFHtG93Kh4MXDAg1DKRY1Q',
      authorpic: 'https://yt3.ggpht.com/ytc/AKedOLSw37zHOSiciOsXJp0oRTSn0DjaqA5EBvPtU8RUaQ=s48-c-k-c0x00ffffff-no-rj',
      title: 'Relaxing Piano Music & Water Sounds 24/7 - Ideal for Stress Relief and Healing',
      authorname: 'OCB Relax Music',
      views: '877',
      live: true
    },
    {
      url: 'https://i.ytimg.com/vi/yTTCx4-LsLQ/hq720_live.jpg?sqp=CJi04ZIG-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLBodegFG88o1NOxi0KiDLVwE_nuDA',
      authorpic: 'https://yt3.ggpht.com/h7b6wa8_7dFMZRr9qeyD2qPPRbKDryKCI7ks0PKKpoS98IefZd5tl5Xm1pq-uRzDVmklfQKBWEw=s48-c-k-c0x00ffffff-no-nd-rj',
      title: '🔴 Deep Focus Music 24/7 - Beautiful Relaxing Music, Peaceful Soothing Instrumental Music',
      authorname: '4K Video Nature - Focus Music\n',
      views: '447',
      live: true
    },
    {
      url: 'https://i.ytimg.com/vi/WLQDpY7lOLg/hq720.jpg?sqp=-oaymwEcCNAFEJQDSFXyq4qpAw4IARUAAIhCGAFwAcABBg==&rs=AOn4CLAXi1Aa9uFE1yAjVUJQSkT1Doywag',
      duration: '5:18:44',
      authorpic: 'https://yt3.ggpht.com/ytc/AKedOLSaQFgUzVlatJkpyAzXZU1Vvy_26MUyYYXg9O3qkg=s68-c-k-c0x00ffffff-no-rj',
      title: 'I Built Full Stack Application with Laravel, Vue 3 and Tailwindcss',
      authorname: 'The Codeholic',
      views: '173K',
      elapsedtime: '2 months ago'
    },

  ])


  const truncate = (str: string, n: number) => {
    return (str.length > n) ? str.substr(0, n-1) + '...' : str;
  };

</script>
