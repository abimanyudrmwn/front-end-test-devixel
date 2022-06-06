<template>
  <div>
     <p class="text-center font-sm text-xl mt-0 mb-2 text-blue-600">Button</p>
    <MyComponents/>
    <MyForm/>
  </div>
</template>

<script>
import MyComponents from '~/components/MyComponents.vue';
import MyForm from '~/components/MyForm.vue';
export default {
    name: "IndexPage",
    components: { MyComponents, MyForm }
}
</script>
