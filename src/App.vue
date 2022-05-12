<template>
 
<div id="app">

 <TitleComp/>
 <JumboComp/>

</div>
</template>

<script>
import TitleComp from './components/TitleComp.vue';
import JumboComp from './components/JumboComp.vue';

export default {
  name: 'App',
  components: {
    TitleComp,
    JumboComp,
  }
}
</script>
