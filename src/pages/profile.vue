<template>
  <div
    class="
      bg-white
      my-12
      pb-6
      w-full
      justify-center
      items-center
      overflow-hidden
      md:max-w-sm
      rounded-lg
      shadow-sm
      mx-auto
    "
  >
    <div class="relative h-40">
      <img
        class="absolute h-full w-full object-cover"
        src="https://i.pinimg.com/originals/2c/a0/0a/2ca00aaad8aca7111f8830daa256a410.jpg"
      />
    </div>
    <div
      class="
        relative
        shadow
        mx-auto
        h-24
        w-24
        -my-12
        border-white
        rounded-full
        overflow-hidden
        border-4
      "
    >
      <img
        class="object-cover w-full h-full"
        src="https://scontent.fbkk8-2.fna.fbcdn.net/v/t1.6435-9/144942121_2090652397732791_1306252839337408179_n.jpg?_nc_cat=105&amp;ccb=1-5&amp;_nc_sid=09cbfe&amp;_nc_eui2=AeFMY6Qnt6b2vpzEQF_145I589u29u70HE3z27b27vQcTY6FrUoR6L2KNC6G95Fe1ay8sQs3R4MgKpv6H-0m7FYT&amp;_nc_ohc=GERy21kcEMoAX8aJwtB&amp;_nc_ht=scontent.fbkk8-2.fna&amp;oh=00_AT9uaEkzod1udd3u-6xhXliPb_3s40aBBJAlt5xBP6314w&amp;oe=621294F5"
      />
    </div>
    <div class="mt-16">
      <h1 class="text-lg text-center font-semibold">Nippit Chotigo</h1>
      <p class="text-sm text-gray-600 text-center">Nickname : Kin , Age : 20</p>
      <p class="text-sm text-gray-600 text-center">
        Education : Bachelor's degree year 3 of SIT KMUTT
      </p>
      <p class="text-sm text-black-600 text-center">
        <router-link :to="{ name: 'contact' }"><b>My Contact</b></router-link>
      </p>
    </div>
    <div class="mt-6 pt-3 flex flex-wrap mx-6 border-t">
      <div
        class="
          text-xs
          mr-2
          my-1
          uppercase
          tracking-wider
          border
          px-2
          text-blue-600
          border-blue-600
          hover:bg-blue-600 hover:text-blue-100
          cursor-default
        "
      >
        Database
      </div>
      <div
        class="
          text-xs
          mr-2
          my-1
          uppercase
          tracking-wider
          border
          px-2
          text-blue-600
          border-blue-600
          hover:bg-blue-600 hover:text-blue-100
          cursor-default
        "
      >
        VueJS
      </div>
      <div
        class="
          text-xs
          mr-2
          my-1
          uppercase
          tracking-wider
          border
          px-2
          text-blue-600
          border-blue-600
          hover:bg-blue-600 hover:text-blue-100
          cursor-default
        "
      >
        Photoshop
      </div>
      <div
        class="
          text-xs
          mr-2
          my-1
          uppercase
          tracking-wider
          border
          px-2
          text-blue-600
          border-blue-600
          hover:bg-blue-600 hover:text-blue-100
          cursor-default
        "
      >
        Premier pro
      </div>
      <div
        class="
          text-xs
          mr-2
          my-1
          uppercase
          tracking-wider
          border
          px-2
          text-blue-600
          border-blue-600
          hover:bg-blue-600 hover:text-blue-100
          cursor-default
        "
      >
        Git command
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'profile',
};
</script>
