<template>
  <div class="container">
	<div class="row">
    <div class="image">
      <!-- <img  src="https://i.ibb.co/2gcpTnX/White-Noise-01.jpg" alt="white-noise"> -->

    </div>
		<!-- <div class="col justify-content-center">  -->
      <!-- <img class="img-fluid w-75 m-5 rounded-3" src="https://i.postimg.cc/8zhrFqSb/Screenshot-2023-10-29-162640.png" alt="ntokozo" loading="lazy"> -->
		<!-- </div> -->
      <div class="col justify-content-center text-sm-center" id="HomeText">
            <p class="homeText text-dark "></p>
          </div>
	</div>
  </div>
</template>

<script>

export default {
  
  mounted(){
    this.typeWriter('name', 'I am Ntokozo Sithebe');
  },
methods:{
    typeWriter(targetId, text, speed = 100){
      const typer = document.getElementById('HomeText');
  if (typer) {
    let i = 0;
    const typeWriterInterval = setInterval(() => {
      if (i < text.length) {
        typer.innerHTML += text.charAt(i);
        i++;
      } else {
        clearInterval(typeWriterInterval);
      }
    }, speed);
  }
},
},
}


</script>
<style scoped>
#HomeText{
	height: 70%;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  padding: 12px 30px; 
  color: black; 
  border: none;
  background-color: white;
  border-radius: 10px;
  cursor: pointer;

}


/* white noise 

https://i.ibb.co/gjmw9P8/white-noise.jpg */

/* .overlay_image:hover{
   background-color: black; 
  color: white;
} */


 .container{
	overflow: hidden;
  scroll-behavior: none;
  align-items: center;
  text-align: center;
  font-family: Georgia, 'Times New Roman', Times, serif;
  font-size: larger;
  background-color: rgb(215, 235, 242);
  
}

#HomeText{
  text-align: center;
  justify-content: center;
  font-size: xx-large;
  
}

/* .image{
  height: 70vh;
  width: 100%;
  background-image: url(https://i.ibb.co/2gcpTnX/White-Noise-01.jpg);
  /* background-repeat:none ; 
  background-size: cover;
  background-position: 0% 100%;
  background-attachment: fixed;
  backdrop-filter: blur(10rem);
} */


/* height: 50vh;
    width: 100%;
    background-image: url(https://i.postimg.cc/13V4vn5j/no4-Ecomm.jpg);
    background-repeat: no-repeat;
    background-size: cover;
    background-position: 0% 37%;
    background-attachment: fixed;
    backdrop-filter: blur(10rem);
    opacity: 90%;
    color: black;
    margin: auto; */



</style>
