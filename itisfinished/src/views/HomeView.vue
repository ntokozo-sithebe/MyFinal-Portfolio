<template>
  <div class="container">
	<div class="row">
		<div class="col justify-content-center"> 
      <img class="img-fluid w-75 m-5" src="https://i.postimg.cc/8zhrFqSb/Screenshot-2023-10-29-162640.png" alt="ntokozo" loading="lazy">
		</div>
    <div class="col">
      <div class="row justify-content-center m-3 mb-2" id="HomeText">
            <p class="homeText text-dark text-sm-center"></p>
          </div>
    </div>
		
		
	</div>
  </div>
</template>

<script>

export default {
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
/* .overlay_image{
	height: 70%;
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  /* padding: 12px 30px; */
  /* color: black; 
  border: none;
  background-color: white;
  border-radius: 10px;
  cursor: pointer;

} */


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
}

/*
@keyframes slide{
  from{
    transform: translateX(-300px);
  }
  to{
    transform: translateX(300px)
  }
}
.myName{
  animation-name: slide;
  animation-duration: 3s;
  animation-timing-function: ease-out;
  animation-delay: 1s;
  animation-iteration-count: 3;
  animation-direction: reverse;
  animation-fill-mode: none;
}
@keyframes sliding{
  from{
    transform: translateX(0);

  }
  to{
    transform:translateX(-300px)

  }
}

.developer{
  animation-name: slide;
  animation-duration: 3s;
  animation-timing-function: ease-in;
  animation-delay: 1s;
  animation-iteration-count: 3;
  animation-direction: normal;
  animation-fill-mode: none;
  scroll-behavior: none;

}
.Homeimg{
  border: 5px white;
  border-radius: 35%;
  margin: 5px;
  justify-content: center
} */
</style>
