<template>
  <div class="container">
    <div class="row">
      <div class="col ">
        <img class="img-fluid w-100 p-3 mt-5" src="https://i.postimg.cc/8zhrFqSb/Screenshot-2023-10-29-162640.png" alt="image" loading="lazy">
      </div>  <!-- eslint-disable   -->
	  			 
	  <div class="col text-align-center text-black p-5 m-3">
		<p class="text-align-center"> 
			<h2 class="fs-2 "> About </h2>

		<p> As an aspiring full stack developer, <br>
I love creating anything from its raw form and coming out with a final product that serves an actual purpose and can help another person. I now see that every job/ learnership that has been a part of my journey resembled how something can be taken from its raw form, processed into something better and useful and be used to transform another persons life whether it be creating a website, skincare, which is why l enjoy software development particulally the framework of JavaScript, the incorporation of different languages makes if fun to create - you can make something out of nothing
<br>
<br>
In my spare time I run my own business,<br>
 I  read, enjoy running at the beach and l occasionally hike. l love activities that make me reflect and do self-introspection - always come out with the best solutions to my own trials and tribulation. And as it is like hiking the higher you go, the harder it gets the deeper you go - the resilience and belief you have within yourself is what will take you to the top and l believe this concept works with software development as well as in life.
</p>
<button class="bg-tertiary p-2 rounded-2">
  <a href="https://drive.google.com/file/d/18YlOdM0OLPD5F6MsyZLPrnwkfQcKYjr6/view?usp=sharing" target="_blank">Download CV</a>
</button>
			
		</p>
	  </div>
    </div>
    
   
  </div>
</template>
<script>

export default{
  name: 'AboutView',
  

}

</script>
<style scoped>
@import url('https://fonts.googleapis.com/css2?family=Crimson+Text:ital,wght@0,400;0,600;0,700;1,400;1,600;1,700&family=Playfair+Display:ital,wght@0,400..900;1,400..900&display=swap');

body{
	font-family:"Playfair Display", serif;
	background-color: white;
}

.container{
	background-color: white;
	scroll-behavior: none;
}

img [alt="image"]:hover{
  padding:2rem

}
@media (min-width < 762px){
	.col{
		flex: 0 0 50%
	}
	.container{
		justify-content: center;
		position: relative;
		display: block;
		margin: 0px;
		text-align: center;
	}
	.navbar-toggler-icon{
		justify-content: center;
		align-items: center;
	}
}

@media  (min-width <  992px){
	.col{
		flex: 0 0 33.333%
	}
	
}

@media (min-width < 1500px  ){
	.col{
		flex: 0 0 25%
	}
	.navbar-toggler-icon{
		justify-content: center;
		align-items: center;
	}
}

</style>