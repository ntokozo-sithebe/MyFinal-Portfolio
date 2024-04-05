<template>
    <div class="container">
        <div class="row">
            <h2 class="display-4 text-black mb-5 mt-2"> Contact </h2>
                <div class="col-md-6 justify-content-center mb-3 p-2" id="contact">
                    <form action="https://formspree.io/f/mnqenpjw" method="post">
                        <div class="input m-2">
                            <textarea input type="text" class="form-control" placeholder="Name" required rows="2"></textarea>
                        </div>
                        <div class="input m-2">
                            <textarea input type="text" class="form-control" placeholder="Surname" required rows="2"></textarea>
                        </div>
                        <div class="input m-2">
                            <textarea input type="text" class="form-control" placeholder="Email" required rows="2"></textarea>
                        </div>
                        <div class="input m-2">
                            <textarea input type="text" class="form-control" placeholder="Message" required rows="4"></textarea>
                        </div>
                        <button class="btn m-3 bg-white text-black">Submit</button>
                    </form>
                </div>
                <div class="col">
                    <div>
                    <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="lightBlue" class="bi bi-pin" viewBox="0 0 16 16">
  <path d="M4.146.146A.5.5 0 0 1 4.5 0h7a.5.5 0 0 1 .5.5c0 .68-.342 1.174-.646 1.479-.126.125-.25.224-.354.298v4.431l.078.048c.203.127.476.314.751.555C12.36 7.775 13 8.527 13 9.5a.5.5 0 0 1-.5.5h-4v4.5c0 .276-.224 1.5-.5 1.5s-.5-1.224-.5-1.5V10h-4a.5.5 0 0 1-.5-.5c0-.973.64-1.725 1.17-2.189A6 6 0 0 1 5 6.708V2.277a3 3 0 0 1-.354-.298C4.342 1.674 4 1.179 4 .5a.5.5 0 0 1 .146-.354m1.58 1.408-.002-.001zm-.002-.001.002.001A.5.5 0 0 1 6 2v5a.5.5 0 0 1-.276.447h-.002l-.012.007-.054.03a5 5 0 0 0-.827.58c-.318.278-.585.596-.725.936h7.792c-.14-.34-.407-.658-.725-.936a5 5 0 0 0-.881-.61l-.012-.006h-.002A.5.5 0 0 1 10 7V2a.5.5 0 0 1 .295-.458 1.8 1.8 0 0 0 .351-.271c.08-.08.155-.17.214-.271H5.14q.091.15.214.271a1.8 1.8 0 0 0 .37.282"/>
</svg> 
<h5 class="mt-3"> Based </h5>
<p class="mb-3"> Milnerton, Cape Town </p>
</div>
<div>



<svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="lightblue" class="bi bi-telephone" viewBox="0 0 16 16">
  <path d="M3.654 1.328a.678.678 0 0 0-1.015-.063L1.605 2.3c-.483.484-.661 1.169-.45 1.77a17.6 17.6 0 0 0 4.168 6.608 17.6 17.6 0 0 0 6.608 4.168c.601.211 1.286.033 1.77-.45l1.034-1.034a.678.678 0 0 0-.063-1.015l-2.307-1.794a.68.68 0 0 0-.58-.122l-2.19.547a1.75 1.75 0 0 1-1.657-.459L5.482 8.062a1.75 1.75 0 0 1-.46-1.657l.548-2.19a.68.68 0 0 0-.122-.58zM1.884.511a1.745 1.745 0 0 1 2.612.163L6.29 2.98c.329.423.445.974.315 1.494l-.547 2.19a.68.68 0 0 0 .178.643l2.457 2.457a.68.68 0 0 0 .644.178l2.189-.547a1.75 1.75 0 0 1 1.494.315l2.306 1.794c.829.645.905 1.87.163 2.611l-1.034 1.034c-.74.74-1.846 1.065-2.877.702a18.6 18.6 0 0 1-7.01-4.42 18.6 18.6 0 0 1-4.42-7.009c-.362-1.03-.037-2.137.703-2.877z"/>
</svg>
<h5 class="mt-3"> Contact </h5>
<p class="mb-3"> +27 76 518 2960 </p>
</div>

<div>
    <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" fill="lightblue" class="bi bi-envelope" viewBox="0 0 16 16">
  <path d="M0 4a2 2 0 0 1 2-2h12a2 2 0 0 1 2 2v8a2 2 0 0 1-2 2H2a2 2 0 0 1-2-2zm2-1a1 1 0 0 0-1 1v.217l7 4.2 7-4.2V4a1 1 0 0 0-1-1zm13 2.383-4.708 2.825L15 11.105zm-.034 6.876-5.64-3.471L8 9.583l-1.326-.795-5.64 3.47A1 1 0 0 0 2 13h12a1 1 0 0 0 .966-.741M1 11.105l4.708-2.897L1 5.383z"/>
</svg>
<h5 class="mt-3"> Email</h5>
<p class="mb-3">ntoky28@gmail.com</p>

</div>

                </div>
                
                
                
            </div>
               
       


    </div>
</template>

<script>
    export default {
        
    }
</script>

<style scoped>
*,
*, ::before
*, ::after{
    margin: 0px;
    padding: 0px;
    box-sizing: border-box;
}
.container{
    font-family: Georgia, 'Times New Roman', Times, serif;
    height: auto;
    align-items: center;
    justify-content: center;
}

#contact{
   background-color: rgb(182, 218, 230)
}

.form-control{
    border-bottom: 1px black;
}



</style>