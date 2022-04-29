
<template>
<div>
  <ComponentTest/>
  <LifeCycle/>
  </div>
</template>


<script>
import ComponentTest from './components/ComponentTest.vue'
import LifeCycle from './components/LifeCycle.vue'
export default {
  name:'App',
  components: 
  {
    ComponentTest,
    LifeCycle
    
  }
}
</script>