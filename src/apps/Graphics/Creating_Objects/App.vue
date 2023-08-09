<template>
  <div> 
  <div id="room" class="lightwall">
  <div class="squareoff">
  <Title msg="Creating Objects in 3D" />
  <br/>
  Each computer graphic object is composed of geometric shapes, usually triangles, that are fitted together into more complex shapes called polygons. The objects may end up looking complicated and irregular, but they are ultimately geometric and simple. All the irregular or organic forms you might see in a graphic scene—for example, the human beings, animals, or mountains in a 3D animated film— are composed of a large number of small, discrete triangles. This teapot, the so-called Utah teapot, was a classic test model for computer graphics research in the 1970s. You can see how increasing the number of polygons in the <span class="emphasis">geometry</span> creates a smoother 3D result. The model can also illustrate how <span class="emphasis">texture mapping</span> and <span class="emphasis">shading</span> improve the photorealism of the object.
  </div> 
  </div>
  </div> 
</template>

<script setup>
import Title from '../../../components/CenterTitle.vue'

import "../../../assets/top.css"
import "../../../assets/room.css"
</script>

<style scoped>

</style>