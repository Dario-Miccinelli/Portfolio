<template>
  <div>




    <div class="bg-black">

<div>
    <nav class="social">
        <ul>
            <li><a href="https://github.com/Dario-Miccinelli">GitHub <i class="fab fa-github"></i></a></li>
            <li><a href="https://www.linkedin.com/in/dariomiccinelli/">Linkedin <i class="fab fa-linkedin"></i></a></li>
        </ul>
    </nav>


    <nav class="navbar navbar-expand-lg justify-between w-75 m-auto">


        <div class="container-fluid text-white"><img class="w-25 p-3 logo" src="BlackModernBusinessLogo.png"
                alt=""></div>
        <div class="container-fluid d-flex">




            <div class="collapse navbar-collapse d-flex justify-content-end">
                <ul class="navbar-nav">
                    <li class="nav-item text-white">
                        <a class="nav-link  text-white"  href="#skills">my skills</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white" href="#work">my work</a>
                    </li>
                    <li class="nav-item">
                        <a class="nav-link text-white" href="#about">about me</a>
                    </li>
                </ul>

            </div>
        </div>
    </nav>
</div>

<div>

    <div class="container text-white">

        <h1 class="text-center text-white fw-bold text0 text">hi, I'm Dario</h1>

        <h3 class="text-center fw-bold align-center pt-1 text">I'm a full stack web developer</h3>

    </div>

    <div class="container text-white d-flex align-items-center mt-5" id="mobile-head">

        <img src="Avatar.svg" alt="" class="w-50 ms-4 avatar">
        <p class="w-40">Passionate about programming and
            everything around it, enthusiastic about
            learning new things every day in this
            industry that has no limits, I am a person
            attentive to details and always try to do my job to the best of my ability.</p>

    </div>






    <div class="container text-center mt-5 pt-5 text-white align-items-center" id="skills">
        <h2 class="fw-bold text-white mb-5 skills">my skills</h2>

        <div class="row d-flex justify-content-center">
            <div class="col-3 ms-4 frontend text-center">
                <h2 class="mt-3 skills">front-end</h2>
                <hr class="pt-1">
                
                <h3 class="fs-5 text-white my-3">languages I speak:</h3>
                <h4 class="fs-5">HTML, CSS, Javascript, Vue.Js</h4>

                <hr>

                <p class="fs-6 mt-4   ms-2 mr-2  text-start">I am particularly fond of front-end development because it allows me to combine my passion for design and user experience with my technical skills in coding. <br> <br> Additionally, I find it gratifying to be able to see the immediate results of my work, as the changes I make are immediately reflected on the user's end. Overall, front-end development is a fulfilling <br> and challenging field that allows me to utilize my creative and technical abilities in a meaningful way.</p>
                


            </div>
            <div class="col-3 graphics ms-4 ">
                <h2 class="mt-3 skills">graphics</h2>
                <hr>
                <h3 class="fs-5 my-3 ">things I enjoy designing:</h3>
                <h4 class="fs-5">UX, UI, Webpages</h4>
                <hr>

                <p class="fs-6 mt-3 ms-2 mr-2 text-start">I have a strong interest in graphics, user experience (UX), and user interface (UI) design utilizing CSS because it allows for the creation of visually appealing and intuitive interfaces that effectively communicate and navigate information to users. </p>
                <br>
            </div>
            <div class="col-3 ms-4 backend">
                <h2 class="mt-3 skills">back-end</h2>
                <hr>
                <h3 class="fs-5 my-3">languages I speak:</h3>
                <h4 class="fs-5 ">PHP, MySQL, Laravel</h4>

                <hr>

                <p class="mt-3 ms-2 mr-2  fs-6 text-start">I am quite fond of backend development due to the intricate and challenging nature of the work.
                The process of designing and implementing <br> server-side logic requires a strong understanding of programming concepts and an ability <br> to think logically and critically. <br><br> Additionally, the satisfaction of seeing <br> a project come to fruition through the successful integration of a backend system is quite rewarding.</p>
            </div>
        </div>
    </div>


    </div>





</div>



</div>

   
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

