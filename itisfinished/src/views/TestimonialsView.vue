<template>
    <div class="container">
        <div class="row">
            <h2 class="display-4">Testimonials</h2>
        </div>
		<div class="Card justify-content-center m-3">
                <div class="row d-block d-flex m-3" id="front">
            <div class="col-md-3 m-3 p-2" v-for="reviews in testimonials" :key="reviews">
                <div class="card">
              <div class="card-body justify-content-center">
				<h5 class="card-title m-5">{{ reviews.name }} {{ reviews.surname }}</h5>
                <p class="card-title m-5"> {{ reviews.title }}</p>
                <img class="img-fluid rounded-5" id="profiles" :src="reviews.profile" alt="theProfiles" loading="lazy">
                
              </div> 
			<div class="back">
				<div class="card-body justify-content-center m-5">
				<p class="card-text text-align-center mt-3">{{ reviews.quotes }}</p>
				</div>
			</div>
			</div>
            </div>
            </div>
         </div> 
      </div> 
</template>

<script>
    export default {
        name: 'TestimonialsView',
        computed:{
            testimonials(){
                return this.$store.state.testimonials
            }
        },
        mounted(){
            return this.$store.dispatch('fetchTestimonials')
        }
        
    }
</script>

<style scoped>

  @import url('https://fonts.googleapis.com/css2?family=Alumni+Sans+Collegiate+One&family=Merriweather:wght@700&family=Nova+Square&family=Playfair+Display:ital@0;1&family=Space+Grotesk:wght@500&display=swap');

*,
* ::before,
* ::after{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}

  .container{
    overflow: hidden;
    scroll-behavior: none;
    margin: 0px;
    padding: 0px;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    overflow: hidden;
    /* animation: bounce 0.9s ; */
}



#profiles{
    width: 25rem;
    height: 50%;
    padding: 2rem;
}

/* .term1{
    margin-left: 10rem;
    margin-right: 10rem;
    align-items: center;
} */


.testimonials{
  font-family: 'Alumni Sans Collegiate One', sans-serif, 'Merriweather', serif, 'Nova Square', sans-serif, 'Playfair Display', serif, 'Space Grotesk', sans-serif;
}

.card{
  width: 20rem;
  height: 30rem;
  position: relative;
  transition: transform 150ms;
  transform-style: preserve-3d;
  perspective: 450px;
  /* margin: 1rem; */
  border-radius: 2px solid;
  box-shadow: 2px 5px 2px;
  margin-right: 3rem;
}
.card img[alt="theProfiles"]{
  width: 70%;
  height: 50%;
  margin-bottom: 1rem;
}

/* body{ */
    /* height: 100vh; 
    overflow: hidden;
    /* background: linear-gradient(rgb(68, 68, 176), rgb(98, 98, 205), rgb(52, 125, 150)); 
    /* font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif; 
    color: white;
    display: flex ;
    justify-content: center;
    align-items: center;
    margin:0px;

}

/* .card{
     height: 100%;
    width: 100%; 
    position: relative;
    transition: transform 150ms; 
    transform-style: preserve-3d; 
} */

.card:hover{
    cursor: pointer;
    transform: rotateY(180deg);
}

 .back{
    height: 100%;
    width: 100%;
    border-radius: 5px;
    position: absolute;
    backface-visibility: hidden;
    margin-left: 1rem;
    margin-right: 1rem

}

#front{
    /* height: 100%; */
    /* width: 100%; */
    /* background-image:url(https://i.postimg.cc/3NbX9pCC/vitamin-c-serum-stylized-2-opt-900x.webp/350x500) ; */
    /* position: absolute; */
    /* backface-visibility: hidden; */
	
}

.back{
    background-color: rgb(179, 218, 242);
    color: black;
    transform: rotateY(180deg) ;
    display: flex;
    flex-direction: column;
    justify-content: center;
    align-items: center;
    
}

/* .container{
    max-width: 100%;
    margin-left:auto;
    margin-right: auto;

} */
.Card{
    margin-left: auto;
    margin-right: auto;
    /* width: 100%; */
}

@media (min-width: 320px){
    .container{
        min-width: 320px;
        justify-content: center;
        
    }
    
}
@media (min-width: 647px){
    .container{
        min-width: 647px;
        margin-left: auto;
        margin-right: auto;
        justify-content: center;
    }
    
}


</style>