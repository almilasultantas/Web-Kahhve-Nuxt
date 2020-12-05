<template>
  <div style="width=100%; height=15%">
    <div>
  <b-carousel
    id="carousel-fade"
    style="text-shadow: 0px 0px 2px #000"
    fade
    indicators
    
  >
      <b-carousel-slide
        
        img-src="//st1.myideasoft.com/idea/bs/42/myassets/slider_pictures/pictures_3_7.jpg?revision=1605008358"
      ></b-carousel-slide>
      <b-carousel-slide
        
        img-src="//st1.myideasoft.com/idea/bs/42/myassets/slider_pictures/pictures_3_4.jpg?revision=1605008358"
      ></b-carousel-slide>

      <!-- Slides with custom text -->
      <b-carousel-slide img-src="//st1.myideasoft.com/idea/bs/42/myassets/slider_pictures/pictures_3_10.jpg?revision=1607073239">
        
      </b-carousel-slide>

      <!-- Slides with image only -->
      <b-carousel-slide img-src="//st1.myideasoft.com/idea/bs/42/myassets/slider_pictures/pictures_3_7.jpg?revision=1605008358"></b-carousel-slide>

      <!-- Slides with img slot -->
      <!-- Note the classes .d-block and .img-fluid to prevent browser default image alignment -->
      <b-carousel-slide>
        <template #img>
          <img
            
            src="//st2.myideasoft.com/idea/bs/42/myassets/slider_pictures/pictures_3_5.jpg?revision=1605008358"
            
          >
        </template>
      </b-carousel-slide>

      
      
    </b-carousel>

</div>

    
  </div>
</template>

<script>
export default {
   
   
}
</script>

<style>

</style>