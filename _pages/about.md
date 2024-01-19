---
layout: about
title: About
permalink: /
subtitle: # <a href='#'>Affiliations</a>. Address. Contacts. Moto. Etc.

social: true  # includes social icons at the bottom of the page

toc:
  sidebar: false
---

<!-- <div class="abstract"> -->

<p>Robotic technology has proven to be an excellent solution for aiding humans in an ever-increasing number of scenarios: from domestic and urban routines to industrial tasks, robots reduce the workload burden on humans and their exposure to hazards. Despite the capabilities demonstrated in recent years, many obstacles remain to be overcome. New challenges arise from the increasing capabilities of advanced robotic platforms. The more complex and unstructured the environment, the more robots should be versatile and reliable to overcome obstacles, plan optimal motions, and reliably accomplish the designed tasks.</p>

<p>This workshop continues to explore state-of-the-art advancements in control strategies that are behind the abilities of such robots, namely, planning and control of dynamic, whole-body motions. Pursuing the thread initiated with the <a href="https://events.pal-robotics.com/humanoids22-workshop">first edition</a> of this workshop, we will focus on trajectory optimization and optimal control: successful approaches that exploit the robotic systems' dynamics, particularly under-actuated ones. This second edition will also address links and synergies with machine learning approaches, e.g. reinforcement learning or deep learning, which are undeniably increasing their relevance and popularity for planning and control applications. Both strategies boil down to a minimization (or maximization) of a desired metric, resulting in a sequence of the most effective actions to take. However, they are fundamentally different approaches that exhibit inherent advantages and drawbacks. How do robotic systems benefit from these methods? Which are the properties shared by the two? How to combine these strategies? These questions will be addressed, soliciting a discussion to compare ideas and solutions from the invited speakers.</p>

<!-- </div> -->

<h2 id="speakers" class="fancy-heading">SPEAKERS</h2>
<div class="card-container">
  <div class="card hoverable" style="width: 250px; height: 430px">
    <a href="https://www.cs.washington.edu/people/postdocs/tassa">
    <img src="assets/img/yuval_tassa.jpg" alt="Yuval Tassa Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Yuval Tassa</h2>
      <h3 class="card-subtitle">Google DeepMing</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Trajectory optimization with MuJoCo</p>          
    </div>
    {%- include pop-up.html
      id = "yuval_tassa_modal" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#yuval_tassa_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 430px">
    <a href="https://www.dlr.de/rm/en/desktopdefault.aspx/tabid-3858/16537_read-29897/sortby-lastname/">
    <img src="assets/img/johannes_englsberger.jpg" alt="Johannes Englsberger Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 16px">Johannes Englsberger</h2>
      <h3 class="card-subtitle">DLR</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Why I decided NOT to use MPC – a denier’s perspective</p>
    </div>
    {%- include pop-up.html
      id = "yuval_tassa_modal" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#yuval_tassa_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 430px">
    <a href="https://sites.nd.edu/pwensing/">
    <img  src="assets/img/patrick_wensing.jpeg" alt="Patrick Wensing Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Patrick Wensing</h2>
      <h3 class="card-subtitle">University of Notre Dame</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Accelerating MPC for dynamic locomotion: Exploiting structure, and letting learning guide the way</p>  
    </div>
    {%- include pop-up.html
      id = "yuval_tassa_modal" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#yuval_tassa_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 430px">
    <a href="https://mavt.ethz.ch/people/person-detail.MjI1NTcx.TGlzdC81NTksLTE3MDY5NzgwMTc=.html">
    <img src="assets/img/jean_pierre_sleiman.jpg" alt="Jean Pierre Sleiman Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Jean Pierre Sleiman</h2>
      <h3 class="card-subtitle">ETH</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Whole-Body Motion Planning and Control for Multi-Contact Locomanipulation</p>
    </div>
    {%- include pop-up.html
      id = "yuval_tassa_modal" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#yuval_tassa_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 430px">
    <a href="https://members.loria.fr/SIvaldi/">
    <img src="assets/img/serena_ivaldi.jpg" alt="Serena Ivaldi Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Serena Ivaldi</h2>
      <h3 class="card-subtitle">Inria</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Teleoperating humanoid robots: optimised controllers, contacts and human-like motions </p>
    </div>
    {%- include pop-up.html
      id = "yuval_tassa_modal" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#yuval_tassa_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 430px">
    <a href = "https://cmastalli.github.io/">
    <img src="assets/img/carlos_mastalli.jpeg" alt="Carlos Mastalli Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Carlos Mastalli</h2>
      <h3 class="card-subtitle">Heriot-Watt University</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Accelerating Algorithms for Numerical Optimization in Full-Dynamics MPC</p>
    </div>
    {%- include pop-up.html
      id = "yuval_tassa_modal" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#yuval_tassa_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 430px">
    <a href = "https://webapps.unitn.it/du/it/Persona/PER0197808/Didattica">
    <img src="assets/img/andrea_del_prete.jpeg" alt="Andrea Del Prete Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Andrea Del Prete</h2>
      <h3 class="card-subtitle">Università di Trento</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Integrating learning and trajectory optimization to achieve safe and efficient robot control</p>
    </div>
    {%- include pop-up.html
      id = "yuval_tassa_modal" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#yuval_tassa_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 430px">
    <a href = "https://gepettoweb.laas.fr/index.php/Members/NicolasMansard">
    <img src="assets/img/nicolas_mansard.jpg" alt="Nicolas Mansard Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Nicolas Mansard</h2>
      <h3 class="card-subtitle">LAAS-CNRS</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> Whole-body MPC on real robots, by combining advanced solver and machine learning</p>
    </div>
    {%- include pop-up.html
      id = "yuval_tassa_modal" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#yuval_tassa_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>

  <div class="card hoverable" style="width: 250px; height: 430px">
    <a href = "#">
    <img src="assets/img/wang_xingxing.jpg" alt="Wang Xingxing Picture"/> 
    </a>
    <div class="card-body">
      <h2 class="card-title" style="font-size: 17px">Wang Xingxing</h2>
      <h3 class="card-subtitle">Founder & CEO of Unitree</h3>
      <p class="card-text" style="text-align: left; margin-top: 5px"><b>Title:</b> AI-powered humanoid robot</p>
    </div>
    {%- include pop-up.html
      id = "wang_xingxing_modal" -%}
    <button type="button" class="circular-button" data-toggle="modal" data-target="#yuval_tassa_modal">
      <span class="material-symbols-outlined">play_circle</span> 
    </button>
  </div>
</div>

<h2 id="organizers" class="fancy-heading">WORKSHOP ORGANIZERS</h2>


<div class="image-container">
<a href="https://www.iit.it/it/people-details/-/people/luca-rossini"> 
  <img class="hoverable" style="border-radius: 50%" src="assets/img/luca_rossini.png" alt="Prof. Luis Sentis Picture" width="200" /> 
  <figcaption class="image-caption">Luca Rossini</figcaption>
  <p>IIT</p>
</a>
<a href="https://www.iit.it/it/people-details/-/people/francesco-ruscelli"> 
  <img class="hoverable" style="border-radius: 50%" src="assets/img/francesco_ruscelli.png" alt="Francesco Ruscelli Picture" width="200" /> 
  <figcaption class="image-caption">Francesco Ruscelli</figcaption>
  <p>IIT</p>
</a>
<a href="https://members.loria.fr/EMingoHoffman/"> 
  <img class="hoverable" style="border-radius: 50%"  src="assets/img/enrico_mingo1.jpeg" alt="Enrico Mingo Hoffman Picture" width="200" /> 
  <figcaption class="image-caption">Enrico Mingo Hoffman</figcaption>
  <p>Inria</p>
</a>
<a href="https://www.ae.utexas.edu/people/faculty/faculty-directory/sentis"> 
  <img class="hoverable" style="border-radius: 50%"  src="assets/img/luis_sentis.jpg" alt="Luis Sentis Picture" width="200" />   
  <figcaption class="image-caption">Luis Sentis</figcaption>
  <p>University of Texas at Austin</p>         
</a>
<a href = "https://cmastalli.github.io/"> 
  <img class="hoverable" style="border-radius: 50%" src = "assets/img/carlos_mastalli.jpeg" alt = "Carlos Mastalli Picture" width ="200"/> 
  <figcaption class="image-caption">Carlos Mastalli</figcaption>
  <p>Heriot-Watt University</p>
</a>

