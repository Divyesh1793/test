
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

</div>

<!-- 
<div id="root" class="container">

  <tabs>
    <tab name="Services" :selected="true">
      <h1>What we do</h1>
    </tab>
    <tab name="Pricing">
      <h1>How much we do it for</h1>
    </tab>
    <tab name="About Us">
      <h1>Why we do it</h1>
    </tab>
  </tabs>

</div> -->



</template>


// <script>


//     Vue.component('tabs', {
//     template: `
//         <div>
//             <div class="tabs">
//               <ul>
//                 <li v-for="tab in tabs" :class="{ 'is-active': tab.isActive }">
//                     <a :href="tab.href" @click="selectTab(tab)">{{ tab.name }}</a>
//                 </li>
//               </ul>
//             </div>

//             <div class="tabs-details">
//                 <slot></slot>
//             </div>
//         </div>
//     `,
    
//     data() {
//         return {tabs: [] };
//     },
    
//     created() {
        
//         this.tabs = this.$children;
        
//     },
//     methods: {
//         selectTab(selectedTab) {
//             this.tabs.forEach(tab => {
//                 tab.isActive = (tab.name == selectedTab.name);
//             });
//         }
//     }
// });

// Vue.component('tab', {
    
//     template: `

//         <div v-show="isActive"><slot></slot></div>

//     `,
    
//     props: {
//         name: { required: true },
//         selected: { default: false}
//     },
    
//     data() {
        
//         return {
//             isActive: false
//         };
        
//     },
    
//     computed: {
        
//         href() {
//             return '#' + this.name.toLowerCase().replace(/ /g, '-');
//         }
//     },
    
//     mounted() {
        
//         this.isActive = this.selected;
        
//     }
// });

// new Vue({
//     el: '#root'
// });
// </script>