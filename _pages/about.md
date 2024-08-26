---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
--- 

<img src="https://jiaminx7.github.io/Website/images/Background.png" alt="Research Illustration" style="float: right; margin-left: 15px; width: 300px;">

Hello. I am a third year Ph.D. student in the [Walker Department of Mechanical Engineering at the University of Texas at Austin](https://www.me.utexas.edu/), where I conducted research in the [Advanced Power Systems and Control Laboratory](https://www.apscl.me.utexas.edu/) under the supervision of Prof. [Dongmei "Maggie" Chen](https://www.me.utexas.edu/people/faculty-directory/chen). My Ph.D. research is founded by [Halliburton](https://www.halliburton.com/) and I finished two summer internships there. Before my Ph.D. career, I was a visiting researcher in the [Renewable Energy & Turbulent Environment Group](https://chamorro.mechse.illinois.edu/) at the University of Illinois at Urbana-Champaign (UIUC).

My research centers on the integration of advanced physics-based and machine learning techniques to address complex challenges in both academia and industry. I specialize in the modeling, estimation, and control of diverse systems, with applications ranging from drilling automation, vehicle engineering, to fluid mechanics. My work aims to bridge the gap between theoretical advancements and practical implementations, driving innovation in different fields.


<h2 id="projects"> 📚 Projects </h2>

<!-- Table of Contents for Projects -->
<p>Jump to: <a href="#event-detection">🔔 Fault Diagnosis</a> | <a href="#directional-drilling">⛽️ Directional Drilling</a> | <a href="#optimization"> 0️⃣ Optimization</a> | <a href="#flow-structure-interaction"> 🌊 Turbulence</a> | <a href="#vehicle-engineering">🚗 Vehicles</a></p>

<!-- Begin Projects Content -->
<h3 id="event-detection">1. 🔔 Event Detection System for Drilling</h3>

<h4 id="two-phase-flow">1.1 Two Phase Flow Simulator</h4>
<div style="display: flex; align-items: center;">
    <img src="https://jiaminx7.github.io/Website/images/DFM.gif" alt="DFM" style="margin-right: 15px; width: 400px;">
    <p>3 nonlinear PDEs with 4 closure equations to simulate the gas bubble propagation inside the wellbore.</p>
</div>
<hr>

<h4 id="real-time-detection">1.2 Fast Real Time Detection System</h4>
<div style="display: flex; align-items: center;">
    <img src="https://jiaminx7.github.io/Website/images/Phase_Portrait.gif" alt="Phase" style="margin-right: 15px; width: 400px;">
    <p>Phase portrait of a hydraulic system. <br>Paper coming soon...</p>
</div>
<hr>

<h3 id="directional-drilling">2. ⛽️ Modeling, Estimation, and Control of Directional Drilling</h3>

<div style="text-align: center;">
    <img src="https://jiaminx7.github.io/Website/images/Model.gif" alt="MECC_2023" style="width: 800px;">
</div>
<div style="clear:both;"></div>

<h4 id="model-validations">2.1 Model Validations</h4>
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/Comparison.gif" alt="MECC_2023" style="margin-right: 15px; width: 400px;">
    <p>
        Compared and generalized linear/nonlinear DDE models for borehole propagation using experimental data.
        <br><br>Check out our paper <a href="https://asmedigitalcollection.asme.org/lettersdynsys/article-abstract/3/2/021007/1166902/Experimentally-Validated-Nonlinear-Delayed?redirectedFrom=fulltext" target="_blank">Here</a>,
        which is the <strong>Best Student Paper Finalist</strong> at Modeling, Estimation, and Control Conference (<a href="https://mecc2023.a2c2.org/" target="_blank">MECC 2023</a>).
    </p>
</div>
<hr>

<h4 id="model-improvements">2.2 Model Improvements</h4>

<h5 id="ml-approach">Machine Learning approach</h5>
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/AIM.png" alt="AIM" style="width: 400px; height: auto; margin-right: 15px;">
    <p>
        A data driven approach to approximate the complex nonlinear DDE model by using the Sparse Identification of Nonlinear Dynamics (SINDy) method. 
        <br><br>Check out our paper <a href="https://ras.papercept.net/images/temp/AIM/files/0221.pdf" target="_blank">Here</a>, published by IEEE/ASME International Conference on Advanced Intelligent Mechatronics (<a href="https://www.aim2024.org/" target="_blank">AIM 2024</a>).
    </p>
</div>
<hr>

<h5 id="physics-based-method">Physics-based method</h5>
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/JPSE.png" alt="JPSE" style="margin-right: 15px; width: 400px;">
    <p>An efficient model that is 80 times faster than the nonlinear DDE model while having high prediction accuracy (maximum error within 2 degrees). 

    <br><br>Check out our paper <a href="https://www.sciencedirect.com/science/article/pii/S2949891024001994" target="_blank">Here</a>, published by <a href="https://www.sciencedirect.com/journal/geoenergy-science-and-engineering" target="_blank">Geoenergy Science and Engineering</a>.
    </p>
</div>
<hr>

<h4 id="parameter-estimation">2.3 Parameter Estimation</h4>
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/Estimation.png" alt="Estimation" style="margin-right: 15px; width: 400px;">
    <p>A Gradient Descent based method equipped with Line Search to estimate the unknown parameter during drilling. 

    <br><br>Check out our paper <a href="https://www.sciencedirect.com/science/article/pii/S2949891024001994" target="_blank">Here</a>, published by <a href="https://www.sciencedirect.com/journal/geoenergy-science-and-engineering" target="_blank">Geoenergy Science and Engineering</a>.
    </p>
</div>
<hr>

<h4 id="model-predictive-control">2.4 Model Predictive Control</h4>
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/MPC.png" alt="MPC" style="margin-right: 15px; width: 400px;">
    <p>A Model Predictive Controller for directional drilling by using the nonlinear DDE model. 

    <br><br>Paper accepted by Modeling, Estimation, and Control Conference (<a href="https://mecc2024.a2c2.org/" target="_blank">MECC 2024</a>).
    </p>
</div>
<hr>

<h3 id="optimization">3. 0️⃣ Optimization Solver Package</h3>
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/optimization.png" alt="Optimization" style="margin-right: 15px; width: 400px;">
    <p>RaghuRobi, named after one of my favorite instructors <a href="https://oden.utexas.edu/people/directory/Raghu-Bollapragada/" target="_blank">Dr. Bollapragada</a>, is a software package for solving unconstrained optimization problems with methods such as Gradient Descent, Newton-CG, and BFGS.
    </p>
</div>
<hr>

<h3 id="flow-structure-interaction">4. 🌊 Flow Structure Interaction</h3>
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/canopy.png" alt="FSI" style="margin-right: 15px; width: 400px;">
    <p>Experimental investigation of turbulence dynamics and transport modulated by canopies.
    </p>
</div>
<hr>

<h3 id="vehicle-engineering">5. 🚗 Vehicle Engineering</h3>

<h4 id="fuel-cells">5.1 Fuel Cells</h4>
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/Fuelcell.png" alt="Fuelcell" style="margin-right: 15px; width: 400px;">
    <p>Optimization of graded catalyst layer to improve fuel cell performance. 

    <br><br>Check out our paper <a href="https://www.sciencedirect.com/science/article/pii/S0360544222024665" target="_blank">Here</a>, published by <a href="https://www.sciencedirect.com/journal/energy" target="_blank">Energy</a> and is the <strong>Highly Cited Paper</strong> in 2023, Web of Science.
    </p>
</div>
<hr>

<h4 id="thermal-management">5.2 Vehicle Thermal Management</h4>
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/ITMS.png" alt="ITMS" style="margin-right: 15px; width: 400px;">
    <p>Integrated thermal management of fuel cell vehicles. 

    <br><br>Check out our <a href="https://www.sciencedirect.com/science/article/pii/S0360544220306022" target="_blank">Paper 1</a> and <a href="https://www.sciencedirect.com/science/article/pii/S1364032121011746" target="_blank">Paper 2</a>, published by <a href="https://www.sciencedirect.com/journal/energy" target="_blank">Energy</a> and <a href="https://www.sciencedirect.com/journal/renewable-and-sustainable-energy-reviews" target="_blank">Renewable and Sustainable Energy Reviews</a>, respectively. The second paper is the <strong>Highly Cited Paper</strong> in 2022, 2023, and 2024, <a href="https://www-webofscience-com.ezproxy.lib.utexas.edu/wos/woscc/summary/ced4c522-5b41-43b6-a82c-8015f5c083e1-0103f2b492/relevance/1" target="_blank">Web of Science</a>.
    </p>
</div>
<hr>

<h4 id="formula-student">5.3 Formula Student China</h4>
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/FSAE.jpg" alt="FASE" style="margin-right: 15px; width: 400px;">
    <p>Three year experiences of <a href="http://www.formulastudent.com.cn/" target="_blank">Formula Student China</a> competition. Designed and manufactured one internal combustion engine and one electric formula racers per year.
    </p>
</div>
<hr>


<h2 id="publications">📑 Publications</h2>
<p>My journal and conference publications are listed below. For a brief summary of each work, please refer to the <a href="#projects">Projects</a> section on this page or click [<a href="#projects">Overview</a>] in front of each publications.</p>

<p>Jump to: <a href="#journal">Journal</a> | <a href="#conference">Conference</a></p>

<h3 id="journal">Journal</h3>
<ul>
  <li>[<a href="#physics-based-method">Overview</a>] | [<a href="https://www.sciencedirect.com/science/article/pii/S2949891024001994">Download</a>] | <strong>Xu J</strong>, Demirer N, Pho V, Tian K, Zhang H, Bhaidasna K, Darbe R and Chen D, 2024. Advancing real-time drilling trajectory prediction with an efficient nonlinear DDE model and online parameter estimation. <em>Geoenergy Science and Engineering, 238, p.212829.</em></li>
  
  <li>[<a href="#model-validations">Overview</a>] | [<a href="https://asmedigitalcollection.asme.org/lettersdynsys/article-abstract/3/2/021007/1166902/Experimentally-Validated-Nonlinear-Delayed?redirectedFrom=fulltext">Download</a>] | <strong>Xu J</strong>, Keller A, Nazli D, Zhang H, Tian K, Bhaidasna K, Darbe R, Chen D. Experimentally Validated Nonlinear Delayed Differential Approach to Model Borehole Propagation for Directional Drilling. <em>ASME Letters in Dynamic Systems and Control, ALDSC-23-1030</em>. (<strong>Best Student Paper Finalist</strong>, MECC 2023)</li>
  
  <li>[<a href="#thermal-management">Overview</a>] | [<a href="https://www.sciencedirect.com/science/article/pii/S1364032121011746">Download</a>] | <strong>Xu J.</strong>, Zhang C, Wan Z, Chen X, Chan SH, Tu Z. Progress and perspectives of integrated thermal management systems in PEM fuel cell vehicles: A review. <em>Renewable and Sustainable Energy Reviews, 2022;155:111908.</em> (<strong>Highly Cited Paper in 2022, 2023 and 2024</strong>, Web of Science).</li>
  
  <li>[<a href="#thermal-management">Overview</a>] | [<a href="https://www.sciencedirect.com/science/article/pii/S0360544220306022">Download</a>] | <strong>Xu J</strong>, Zhang C, Fan R, Bao H, Wang Y, Huang S, et al. Modelling and control of vehicle integrated thermal management system of PEM fuel cell vehicle. <em>Energy, 2020;199:117495.</em> </li>
  
  <li>[<a href="#fuel-cells">Overview</a>] | [<a href="https://www.sciencedirect.com/science/article/pii/S0360544222024665">Download</a>] | Fan R, Chang G, Xu Y, <strong>Xu J.</strong> Multi-objective optimization of graded catalyst layer to improve performance and current density uniformity of a PEMFC. <em>Energy, 2023 Jan 1;262:125580.</em> (<strong>Highly Cited Paper in 2023</strong>)</li>
  
  <li> [<a href="">Overview</a>] | [<a href="http://qks.cqu.edu.cn/cqdxzren/article/abstract/202304001">Download</a>] | Ma R, <strong>Xu J.</strong>, Li J, Yuan H, Zhang C. A multi-conditions speed predictor based on a DK clustering model. <em>Journal of Chongqing University.</em></li>
</ul>

<hr>

<h3 id="conference">Conference</h3>
<ul>
  <li>[<a href="#model-predictive-control">Overview</a>] | [<a href="">Download</a>] | <strong>Xu J</strong>, Demirer N, Pho V, Tian K, Zhang, H, Bhaidasna, K, Darbe R and Chen D, 2024. Nonlinear Model Predictive Control for Directional Drilling Applications. <em>Modeling, Estimation, and Control Conference (MECC 2024).</em></li>
  
  <li>[<a href="#ml-approach">Overview</a>] | [<a href="https://mecc2024.a2c2.org/">Download</a>] | <strong>Xu, J.</strong>, Demirer, N, Pho, V, Tian K, Zhang H, Bhaidasna K, Darbe R, and Chen D, 2024. Data-Driven Modeling of Nonlinear Delay Differential Equations with Gap Effects Using SINDy. <em>IEEE/ASME International Conference on Advanced Intelligent Mechatronics (AIM 2024).</em></li>
</ul>


<h2 id="honors">🏅 Honors and Awards</h2>
<ul>
  <li>Highly Cited Paper four times [<a href="#journal">Papers</a>]</li>
  <li>2023 Best Student Paper Finalist, <a href="https://mecc2023.a2c2.org/" target="_blank">Modelling, Estimation, and Control Conference (MECC)</a>.</li>
  <li>2021 China National Scholarship (Top 0.2% in China).</li>
  <li>2021 Graduate Academic Scholarship for 1st prize.</li>
  <li>2020 Graduate Academic Scholarship for 1st prize.</li>
  <li>2019 Graduate Academic Scholarship for 1st prize.</li>
  <li>2019 Champion of Hydrogen group in Shell Eco-marathon ASIA.</li>
  <li>2019 Undergraduate Academic Scholarship for 3rd prize.</li>
  <li>2018 Undergraduate Academic Scholarship for 3rd prize.</li>
  <li>2018 Formula Student Electric China for 2nd prize.</li>
</ul>

<h2 id="teaching">🧑‍🏫 Teaching</h2>
<ul>
  <li> [<a href="https://jiaminx7.github.io/Website/files/Syllabus.pdf">Syllabus</a>] | ME 140L Mechatronics Lab. 2022 Fall, 2023 Spring</li>
</ul> 

