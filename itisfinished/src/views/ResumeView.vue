<template>
    <div class="container">
        <div class="row d-block justify-content-space-between text-align-center" id="id-1">
            <h3 class="educate display-3"> Education</h3>
    <div class="card col">
  <div class="card-body">
    <h5 class="card-title">Software Development</h5>
    <p class="card-text">Life Choices Academy & studio</p>
    <h3>2023 - Present</h3>
    <p> • HTML, • CSS, • Javascript, • Vue, • MySql, • Node </p>
  </div>
</div>


<div class="card col">
  <div class="card-body">
    <h5 class="card-title">Chemical Operations</h5>
    <p class="card-text"> Astron Energy & BAB Developers</p>
    <h3> 2020 - 2022 & 2023</h3>
    <p> • Sampling
• Processing emergencies
• Work permits
• Gas testing
• Housekeeping
• Hazardous Chemical substances
• Instrumentation
• Standard operating instructions
• LOTO Procedure
• Plant monitoring
• Importance on PPE  </p>
   
  </div>
</div>

<div class="card col">
  <div class="card-body">
    <h5 class="card-title">Matric</h5>
    <p class="card-text">Bloubergrant High School</p>
    <h3>2019</h3>
    <p> • English Home language
• Afrikaans First additional Language
• Mathematics
• Life Orientation
• Consumer Studies
• Life Sciences
• Physical Sciences 
</p>
    
  </div>
</div>
</div>
       


<div class="row">
    <div>
        <h3>Experience</h3>
    </div>
    
    <div class="card">
  <div class="card-header">
    Sales Assistant
  </div>
  <div class="card-body">
    <h5 class="card-title">The Body Shop</h5>
    <h6 class="card-title"> Dec 2019 - Feb 2020</h6>
    <p class="card-text">
        • Flexi-time
• Sales advisor
• Till operator
• Beauty consultant
• Cashing up
• Product advisor
• Mini Makeovers
• Housekeeping
    </p>
    <h6>Contract Ended</h6>
  </div>
</div>

<div class="card">
  <div class="card-header">
    Intern
  </div>
  <div class="card-body">
    <h5 class="card-title">Life Choices Studio</h5>
    <h6 class="card-title"> Oct 2023 - Present</h6>
    <p class="card-text">
         design, develop, test, and maintain software solutions. This involves writing code in various programming languages and using different technologies and frameworks.
    </p>
    <h6> </h6>
  </div>
</div>


</div>











        
    </div>
</template>

<script>
    export default {
        // name: 'ResumeView',
        // computed:{
        //     education(){
        //         return this.$store.state.education
        //     },
        //     work(){
        //         return this.$store.state.work
        //     },
        //     skills(){
        //         return this.$store.state.skills
        //     }
        // },
        // mounted(){
        //     this.$store.dispatch('fetchEducation');
        //     this.$store.dispatch('fetchWork');
        //     this.$store.dispatch('fetchSkills')
        // },
       
        
        

            
         }

        


    
</script>

<style scoped>
.container{
   /* height: 100vh; */
   justify-content: center;
   text-align: center;
   overflow: hidden;
   scroll-behavior: none;
   margin: 0px;
   padding: 0px;
   min-height: 120rem;
}
.card{
    box-shadow: 5px 5px;
    margin: 2px;
    padding: 2px;
}

.card :hover{
background-color: rgb(196, 236, 241);

}


img[alt="imgSkills"] {
    width: 250px;
}

#id-1{
animation: slide 3s;
}

@keyframes slide{
from{
    transform: translateX(-100)
   } 
   to{
    transform: translateX(0);
   }

}



/* #work{
    animation: slide;
}
#work{
  animation-name: slide;
  animation-duration: 3s;
  animation-timing-function: ease-in;
  animation-delay: 1s;
  animation-iteration-count: 1;
  animation-direction: normal;
  animation-fill-mode: none;
  scroll-behavior: none;
  


}

@keyframes slide{
   from{
    transform: translateX(-100)
   } 
   to{
    transform: translateX(0);
   }
} */
</style>