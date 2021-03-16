---
title: "Projects"
layout: gridlay
sitemap: false
permalink: /projects/
---

<!-- <style> -->
<!-- iframe { -->
<!--   height: 100%; -->
<!--   width: 175px !important; -->
<!--   display: inline; -->
<!--   vertical-align:middle; -->
<!--   margin:0px !important; -->
<!--   padding:0px !important; -->
<!--   width: 175px; -->
<!--   display: inline; -->
<!--   vertical-align:middle; -->
<!--   border: 1px solid red; -->
<!-- } -->
<!-- .col-md-3 { -->
<!--   margin:0px !important; -->
<!--   padding:0px !important; -->
<!--   overflow:hidden; -->
<!--   display: table-cell; -->
<!--   text-align:center; -->
<!--   background: white; -->
<!--   width: 175px; -->
<!--   border: 0px solid transparent; -->
<!--   border-radius:20px; -->
<!-- } -->
<!-- </style> -->

<style>
img{
  border-radius: 10px;
}
.col-md-3 {
  margin-top:10px;
  margin-bottom:10px;
  padding:0px;
  display:block;
  overflow:hidden;
  text-align:center;
  display: table-cell;
  background: white;
  border-radius: 20px;
  height: auto;
  <!-- border: 1px solid black; -->
}
iframe {
  margin:0;
  padding:0;
  width: 175px;
  display: inline;
  vertical-align: middle;
}
</style>

  <!-- border: 5px solid red; -->
  <!-- margin-bottom:5px; -->
  <!-- margin-left:5px; -->
  <!-- float: none; -->

## Academic

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Two Phase Flow in a Viscously Compacting Matrix</h4>
  
<b>Advisor:</b>
<i> Professor Marc Hesse</i>

Developing a 2D solver to simulate two immiscible fluids inside a viscously compacting porous solid. The solver is based on:
* Conservative finite-difference scheme
* Second order in space and theta method in time
* General framework for implementation in other fields

The applications I am currently studying as a part of my doctoral study are:
* Firn densification due to melt percolation and refreezing in glaciers and investigating the effects of global warming
* Melt percolation during core formation in planetesimals (young planets) to understand the mechanism of planetary core formation
* <a href="https://agu.confex.com/agu/fm20/webprogram/Paper712914.html" target="_blank">Groundwater filling times for large impact basins on early Mars and implications for the onset of post impact hydrothermal systems</a>

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524095933?autoplay=1&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4> Investigating Fluid Drainage using Physics Informed Neural Networks</h4>
  
<b>Collaborators:</b>
<i> DingCheng Luo, Yiran Shen, Eric Hiatt, and Prof. Marc Hesse</i>

Physics Informed Neural Networks (PINNs) is a state-of-the-art tool for finding data-driven solutions to PDEs and discovering parameters in a PDE from
a given data. In the present work, we have studied both, in the context of fluid
drainage from the edge of a porous reservoir.
We are investigating:
* steady-state PDE, called Dupuit-Boussinesq approximation, from both synthetic and experimental data
for a range of given input flow values.
* estimation problem for the transient flow PDE, using numerical solutions from finite-difference simulations as the input data to
infer both the hydraulic conductivity and the outflow boundary condition.
* difficulties in implementing PINNs for studying this problem, for example, when
the data does not perfectly match the PDEs or scaling of the misfit terms.

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524097521?autoplay=1&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4> Suppression of drop breakup in a viscoelastic bath</h4>
  
<b>Advisor:</b>
<i> Professor Irmgard Bischofberger</i>

A drop of a Newtonian liquid falling in a bath of another, less-dense and miscible, Newtonian liquid, deforms into a torus which is either stable or subsequently fragments into smaller structures, depending on the relative contributions of diffusive, viscous and convective forces. 
Here we show that the <a href="https://meetings.aps.org/Meeting/DFD20/Session/S03.3" target="_blank">dynamics of the drop can change significantly when the bath is replaced by a viscoelastic liquid</a>. Wrote a MATLAB code (<a href="https://github.com/mashadab/drop-dynamics" target="_blank">src</a>) to analyse a moving frame video.

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524103920?autoplay=1&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</div>
</div>
</div>

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4> High-Order Finite-Volume Reconstruction in Curvilinear Coordinates</h4>
  
<b>Advisor:</b>
<i> Professor Kun Xu</i>

High-order reconstruction represents the state-of-the-art computational physics. The main ideas in using <a href="https://users.soe.ucsc.edu/~dongwook/wp-content/uploads/2019/ams260/_build/html/_downloads/Shu_wenoConvection_2009.pdf" target="_blank">Weighed Essentially Non-Oscillatory schemes</a> to solve various hyperbolic PDEs and other convection dominated problems, and present a collection of applications in areas including computational fluid dynamics, computational astronomy and astrophysics, semiconductor device simulation, traffic flow models, computational biology and some non-PDE applications.
Research highlights:
* Proposed <a href="{{ site.url }}{{ site.baseurl }}/papers/shadab_fifthWENO_CnF_2019.pdf" target="_blank">fifth order finite volume WENO-C in orthogonally-curvilinear coordinates</a>.
* WENO-Curvilinear reconstruction and averaging weights provided for standard grids (<a href="https://github.com/mashadab/WENO-curvilinear" target="_blank">src</a>).
* Analytical values of weights for Radius → ∞ case conform to conventional WENO-JS.
* Tests performed in <a href="{{ site.url }}{{ site.baseurl }}/papers/shadab_ICOSAHOM_2020.pdf" target="_blank">curvilinear coordinates</a> testify for fifth order & ENO properties.

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524120989?autoplay=1&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4> Investigation and Control of Unstart Phenomenon in
Scramjets</h4>
  
<b>Advisor:</b>
<i> Professor M.F. Baig</i>

Engine unstart refers to the transient disgorging, which is generated with the aid of thermal choking due to impulsive heat addition inside the combustor. The generated pressure disturbance traverses upstream
inside the isolator duct in the form of normal shock, resulting in a loss of thrust and possible flameout of the engine.
Research highlights:
* Designed a Scramjet based on different operating Mach numbers
* A quasi-one-dimensional adaptation of mass, momentum and energy conservation.
* A <a href="{{ site.url }}{{ site.baseurl }}/papers/shadab_Scramjet_2017.pdf" target="_blank">single-input-single-output (SISO) mechanism</a> based on pressure feedback is proposed to avert Engine unstart

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524139367?autoplay=1&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4> Investigation and Control of Unstart Phenomenon in
Scramjets</h4>
  
<b>Advisor:</b>
<i> Professor M.F. Baig</i>

Engine unstart refers to the transient disgorging, which is generated with the aid of thermal choking due to impulsive heat addition inside the combustor. The generated pressure disturbance traverses upstream
inside the isolator duct in the form of normal shock, resulting in a loss of thrust and possible flameout of the engine.
Research highlights:
* Designed a Scramjet based on different operating Mach numbers
* A quasi-one-dimensional adaptation of mass, momentum and energy conservation.
* A <a href="{{ site.url }}{{ site.baseurl }}/papers/shadab_Scramjet_2017.pdf" target="_blank">single-input-single-output (SISO) mechanism</a> based on pressure feedback is proposed to avert Engine unstart

</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/524147082?autoplay=1&loop=1&autopause=0&muted=1&quality=1080p&background=1" height="182px" frameborder="0" allow="autoplay; fullscreen" allowfullscreen></iframe>
</div>
</div>
</div>


## Industrial

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Decomposition of Carbonates</h4>
  
<b>Developer:</b>
<i>  Gianmarco Polotti</i>

Cavitating bubbles can ablate cancer cells, fragment tissues, and deliver drugs, among other functions.
I develop high-fidelity computational methods to simulate these dynamics.
Examples are:
* Euler--Euler and Euler--Lagrange <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-IJMF-19.pdf" target="_blank">sub-grid bubble cloud models</a>
* Accelerated models using a <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-IJMF-20.pdf" target="_blank">statistical paradigm and neural networks</a>
* Implementation in my open-source solver <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-CPC-19.pdf" target="_blank">MFC</a>

These enable realistic simulation of the bubble populations that nucleate during treatment.
This has impacted application-specific treatments, including:
* Improved _burst-wave lithotripsy administration_ in human trials 
* Understanding of <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-JCP-20.pdf" target="_blank">bubble-collapse-rebound</a> dynamics
* Cavitation-induced <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-JFM-19.pdf" target="_blank">erosion potential</a> for rough materials
</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="{{ site.url }}{{ site.baseurl }}/images/research/VID_20200423_120900.mp4" height="182px" frameborder="0" allow="autoplay"></iframe>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4> Bio-polymers for Pharma</h4>
  
<b>Developer:</b>
<i> Mattia Sponchioni</i>

Cavitating bubbles can ablate cancer cells, fragment tissues, and deliver drugs, among other functions.
I develop high-fidelity computational methods to simulate these dynamics.
Examples are:
* Euler--Euler and Euler--Lagrange <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-IJMF-19.pdf" target="_blank">sub-grid bubble cloud models</a>
* Accelerated models using a <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-IJMF-20.pdf" target="_blank">statistical paradigm and neural networks</a>
* Implementation in my open-source solver <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-CPC-19.pdf" target="_blank">MFC</a>

These enable realistic simulation of the bubble populations that nucleate during treatment.
This has impacted application-specific treatments, including:
* Improved _burst-wave lithotripsy administration_ in human trials 
* Understanding of <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-JCP-20.pdf" target="_blank">bubble-collapse-rebound</a> dynamics
* Cavitation-induced <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-JFM-19.pdf" target="_blank">erosion potential</a> for rough materials
</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/455888052?autoplay=1&loop=1&autopause=0&muted=1&quality=240p&background=1" height="182px" frameborder="0" allow="autoplay"></iframe>
</div>
</div>
</div>

## Hobby

<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4>Decomposition of Carbonates</h4>
  
<b>Developer:</b>
<i>  Gianmarco Polotti</i>

Cavitating bubbles can ablate cancer cells, fragment tissues, and deliver drugs, among other functions.
I develop high-fidelity computational methods to simulate these dynamics.
Examples are:
* Euler--Euler and Euler--Lagrange <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-IJMF-19.pdf" target="_blank">sub-grid bubble cloud models</a>
* Accelerated models using a <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-IJMF-20.pdf" target="_blank">statistical paradigm and neural networks</a>
* Implementation in my open-source solver <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-CPC-19.pdf" target="_blank">MFC</a>

These enable realistic simulation of the bubble populations that nucleate during treatment.
This has impacted application-specific treatments, including:
* Improved _burst-wave lithotripsy administration_ in human trials 
* Understanding of <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-JCP-20.pdf" target="_blank">bubble-collapse-rebound</a> dynamics
* Cavitation-induced <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-JFM-19.pdf" target="_blank">erosion potential</a> for rough materials
</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="{{ site.url }}{{ site.baseurl }}/images/research/VID_20200423_120900.mp4" height="182px" frameborder="0" allow="autoplay"></iframe>
</div>
</div>
</div>


<div class="jumbotron">
<div class="row align-items-end">
<div class="col-md-9 col-sm-12">
 <h4> Bio-polymers for Pharma</h4>
  
<b>Developer:</b>
<i> Mattia Sponchioni</i>

Cavitating bubbles can ablate cancer cells, fragment tissues, and deliver drugs, among other functions.
I develop high-fidelity computational methods to simulate these dynamics.
Examples are:
* Euler--Euler and Euler--Lagrange <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-IJMF-19.pdf" target="_blank">sub-grid bubble cloud models</a>
* Accelerated models using a <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-IJMF-20.pdf" target="_blank">statistical paradigm and neural networks</a>
* Implementation in my open-source solver <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-CPC-19.pdf" target="_blank">MFC</a>

These enable realistic simulation of the bubble populations that nucleate during treatment.
This has impacted application-specific treatments, including:
* Improved _burst-wave lithotripsy administration_ in human trials 
* Understanding of <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-JCP-20.pdf" target="_blank">bubble-collapse-rebound</a> dynamics
* Cavitation-induced <a href="{{ site.url }}{{ site.baseurl }}/papers/bryngelson-JFM-19.pdf" target="_blank">erosion potential</a> for rough materials
</div>
<div class="col-md-3 col-sm-12" style="background-color:transparent;">
  <iframe src="https://player.vimeo.com/video/455888052?autoplay=1&loop=1&autopause=0&muted=1&quality=240p&background=1" height="182px" frameborder="0" allow="autoplay"></iframe>
</div>
</div>
</div>



