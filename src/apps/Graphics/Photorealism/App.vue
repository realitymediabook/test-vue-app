<template>
  <div> 
  <div id="room" class="darkwall">
  <div class="squareoff">
  <Title msg="Photorealism in Computer graphics" />
  <br/>
  The first step in achieving photorealism in computer graphics lies in reproducing the perspective in which we see the world. When we look at the world, objects that are far away appear smaller than ones that are close, and straight lines converge in a particular way. Renaissance painters beginning with Brunelleschi in the fifteenth century developed systematic manual techniques for drawing in <span class="emphasis"> linear perspective</span> to create the illusion of three dimensions on flat canvases. A computer graphics program calculates <span class="emphasis">perspective projection</span> using linear algebra. CG programers use the remediating term camera, but a CG camera is a mathematical construct rather than a physical mechanism. It is simply the point that represents the viewer’s eye, at a location in front of the projection plane. The computer draws the objects on the projection plane so that they look “right” for a viewer at that point.  In this room you see how a 3D model is projected onto a 2D plane.
  
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