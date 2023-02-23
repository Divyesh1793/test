
<template>

<div class=" p-8   ">
    <div class="flex space-x-14 ">
  <div>   <img src="http://localhost/ci/assets/123.jpg" class=""></div>
</div>


</div>

<div class="flex space-x-12 justify-center ">
  <div class="cursor-pointer" ><a href="#">Timeline</a></div>
  <div class="cursor-pointer" >About</div>
  <div class="cursor-pointer" >Friends</div>
  <div class="cursor-pointer" >Photos</div>
</div>

<div class="grid gap-4  pt-20 2xl:grid-cols-2 xl:grid-cols-3 lg:grid-cols-5 md:grid-cols-2 sm:grid-cols-6 grid-cols-2 ">
  <div>  <div>   <img src="http://localhost/ci/assets/123.jpg" class="">
</div>
</div>

  <div>
    
    <p class="py-12">
        Timothy Carlson updated his sattus<br>
16 hours ago<br><br>

Lorem ipsum dolor sit amet consectetur adipisicing elit. Modi dicta beatae illo illum iusto iste mollitia explicabo quam officia. Quas ullam, quisquam architecto aspernatur enim iure debitis dignissimos suscipit ipsa.<br><br>

LikeComment
    </p>
  </div>
  
</div>


<div class="pt-20" ><span class=" pb-10 text-2xl"><b>Personal Information</b></span><br>
<p class="pt-10">
Lorem ipsum dolor sit amet consectetur adipisicing elit. Eveniet, commodi quam! Provident quis voluptate asperiores ullam, quidem odio pariatur. Lorem ipsum, dolor sit amet consectetur adipisicing elit. Voluptatem, nulla eos? Cum non ex voluptate corporis id asperiores doloribus dignissimos blanditiis iusto qui repellendus deleniti aliquam, vel quae eligendi explicabo.</p></div>

<hr>

<!-- <div class="grid gap-4 pt-20  2xl:grid-cols-4 xl:grid-cols-3 lg:grid-cols-5 md:grid-cols-2 sm:grid-cols-6 grid-cols-2 "> -->
<div class="grid gap-4 pt-20 grid-cols-3  ">

  <div>
<p>
 Birth Date<br>
1, Jan 1994
</p>
<p class="pt-10">
Lives In<br>
8 Years
    </p>
  </div>
  <div>
    <p>
Gender<br>
1, Jan 1994
</p>
<p class="pt-10">
Email<br>
example@ui-lib.com
    </p>
  </div>
  <div>
    <p>
 Profession<br>
Digital Marketer
</p>
<p class="pt-10">
 Experience
<br>
8 Years
    </p>
    
    </div>  

  </div>

<div class="pt-10">
   <p class="text-2xl"> Timothy Carlson</p>
   <p>Digital Marketer</p>

<div class="flex pt-10 space-x-40 justify-left">
  <div class="text-xl">Travelling</div>
  <div class="text-xl">Photography</div>
  <div class="text-xl">Driving</div>
  <div class="text-xl">Gaming</div>
  <div class="text-xl">Music</div>
  <div class="text-xl">Shopping
</div>


</div>



  <div>
    <h2 class="font-bold text-blue-900 text-1xl">Vue Js Simple Tabs</h2>
    <div class="container mx-auto">
      <ul class="flex justify-center space-x-2 text-white">
        <li>
          <button
            @click="activeTabOne"
            class="inline-block px-4 py-2 bg-purple-500"
          >
            Tab 1
          </button>
        </li>
        <li>
          <button
            @click="activeTabTwo"
            class="inline-block px-4 py-2 bg-purple-500"
          >
            Tab 2
          </button>
        </li>
        <li>
          <button
            @click="activeTabThree"
            class="inline-block px-4 py-2 bg-purple-500"
          >
            Tab 3
          </button>
        </li>
      </ul>
      <div class="p-3 mt-6 bg-white border">
        <div v-show="tab === 1">
          Tab 1 Content show Lorem ipsum dolor sit amet consectetur adipisicing
          elit.
        </div>
        <div v-show="tab === 2">
          Tab 2 Content show Lorem ipsum dolor sit amet consectetur, adipisicing
          elit.
        </div>
        <div v-show="tab === 3">
          Tab 3 Content show Lorem ipsum dolor sit amet consectetur adipisicing
          elit. Amet,
        </div>
      </div>
    </div>
  </div>

</div>

</template>

<script>
export default {
  data() {
    return {
      tab: 1,
    };
  },
  methods: {
    activeTabOne() {
      this.tab = 1;
    },
    activeTabTwo() {
      this.tab = 2;
    },
    activeTabThree() {
      this.tab = 3;
    },
  },
};
</script>












