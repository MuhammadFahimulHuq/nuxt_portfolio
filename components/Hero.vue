<template>

    <div class="bg-blue text-white h-[700px]">
        <div class="w-[80%] pt-[200px] mx-auto">
            <div class="flex justify-center gap-8 mb-[50px]">
                <div v-for="(tag, index) in professionTag" :key="index" class="text-green border-2 text-xs  border-green rounded-3xl py-1 px-4">
          {{ tag }}
        </div>
            </div>
            <div class="text-6xl text-[#FFFFFF] font-semibold text-center">Muhammad Fahimul Huq</div>
            <div class="text-6xl mt-5 text-green font-semibold text-center">Full Stack Dev</div>
            <div class="text-xl mt-5 font-thin text-center  ">Lorem ipsum dolor sit amet consectetur adipisicing elit. Maxime mollitia,<br> amet consectetur adipisicing elit. Maxime mollitia,</div>
        </div>

    </div>
</template>

<script>
export default{
    data(){
        return{
           professionTag: ['Next.js','Nuxt.jsx','Laravel']
        }
    }
}


</script>