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

# Projects {#featured-projects}

## 1 Event Detection System for Driling

### 1.1 Two Phase Flow Simulator
<div style="display: flex; align-items: center;">
    <img src="https://jiaminx7.github.io/Website/images/DFM.gif" alt="DFM" style="margin-right: 15px; width: 400px;">
    <p>3 nonlinear PDEs with 4 closure equations to simulate the gas bubble propagation inside the wellbore.</p>
</div>
---

### 1.2 Fast Real Time Detection System
<div style="display: flex; align-items: center;">
    <img src="https://jiaminx7.github.io/Website/images/Phase_Portrait.gif" alt="Phase" style="margin-right: 15px; width: 400px;">
    <p>Phase portrait of a hydraulic system. Paper coming soon...</p>
</div>
<div style="clear:both;"></div>
---

## 2 Modeling, Estimation, and Control of Directional Drilling

<div style="text-align: center;">
    <img src="https://jiaminx7.github.io/Website/images/Model.gif" alt="MECC_2023" style="width: 800px;">
</div>
<div style="clear:both;"></div>

### 2.1 Model Validations

<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/Comparison.gif" alt="MECC_2023" style="margin-right: 15px; width: 400px;">
    <p>
        Compared and generalized linear/nonlinear DDE models for borehole propagation using experimental data.
        Check out our paper <a href="https://asmedigitalcollection.asme.org/lettersdynsys/article-abstract/3/2/021007/1166902/Experimentally-Validated-Nonlinear-Delayed?redirectedFrom=fulltext" target="_blank">Here</a>,
        which is the <strong>Best Student Paper Finalist</strong> at Modelling, Estimation, and Control Conference (<a href="https://mecc2023.a2c2.org/" target="_blank">MECC 2023</a>).
    </p>
</div>
---

### 2.2 Model Improvements

#### Machine Learning approach
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/AIM.png" alt="AIM" style="width: 400px; height: auto; margin-right: 15px;">
    <p>
        A data driven approach to approximate the complex nonlinear DDE model by using the Sparse Identification of Nonlinear Dynamics (SINDy) method. 
        Check out our paper <a href="https://ras.papercept.net/images/temp/AIM/files/0221.pdf" target="_blank">Here</a>, published by IEEE/ASME International Conference on Advanced Intelligent Mechatronics (<a href="https://www.aim2024.org/" target="_blank">AIM 2024</a>).
    </p>
</div>
---

#### Physics-based method
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/JPSE.png" alt="JPSE" style="margin-right: 15px; width: 400px;">
    <p>An efficient model that is 80 times faster than the nonlinear DDE model while having high prediction accuracy (maximum error within 2 degrees). 

    Check out our paper <a href="https://www.sciencedirect.com/science/article/pii/S2949891024001994" target="_blank">Here</a>, published by <a href="https://www.sciencedirect.com/journal/geoenergy-science-and-engineering" target="_blank">Geoenergy Science and Engineering</a>.
    </p>
</div>
---

### 2.3 Parameter Estimation
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/Estimation.png" alt="Estimation" style="margin-right: 15px; width: 400px;">
    <p>A Gradient Descent based method equipped with Line Search to estimate the unknown parameter during drilling. 

    Check out our paper <a href="https://www.sciencedirect.com/science/article/pii/S2949891024001994" target="_blank">Here</a>, published by <a href="https://www.sciencedirect.com/journal/geoenergy-science-and-engineering" target="_blank">Geoenergy Science and Engineering</a>.
    </p>
</div>
---

### 2.4 Model Predictive Control
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/MPC.png" alt="MPC" style="margin-right: 15px; width: 400px;">
    <p>A Model Predictive Controller for directional drilling by using the nonlinear DDE model. 

    Paper accepted by Modelling, Estimation, and Control Conference (<a href="https://mecc2024.a2c2.org/" target="_blank">MECC 2024</a>).
    </p>
</div>
---

## 3 Optimization Solver Package
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/optimization.png" alt="Optimization" style="margin-right: 15px; width: 400px;">
    <p>RaghuRobi, named after one of my favorite instructors <a href="https://oden.utexas.edu/people/directory/Raghu-Bollapragada/" target="_blank">Dr. Bollapragada</a>, is a software package for solving unconstrained optimization problems with methods such as Gradient Descent, Newton-CG, and BFGS.
    </p>
</div>
---

## 4 Flow Structure Interaction
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/canopy.png" alt="FSI" style="margin-right: 15px; width: 400px;">
    <p>Experimental investigation of turbulence dynamics and transport modulated by canopies.
    </p>
</div>
---

## 5 Vehicle Engineering
### 5.1 Fuel Cells
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/Fuelcell.png" alt="Fuelcell" style="margin-right: 15px; width: 400px;">
    <p>Optimization of graded catalyst layer to improve fuel cell performance. 

    Check out our paper <a href="https://www.sciencedirect.com/science/article/pii/S0360544222024665" target="_blank">Here</a>, published by <a href="https://www.sciencedirect.com/journal/energy" target="_blank">Energy</a> and is the <strong>Highly Cited Paper</strong> in 2023, Web of Science.
    </p>
</div>
---

### 5.2 Vehicle Thermal Management
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/ITMS.png" alt="ITMS" style="margin-right: 15px; width: 400px;">
    <p>Integrated thermal management of fuel cell vehicles. 

    Check out our <a href="https://www.sciencedirect.com/science/article/pii/S0360544220306022" target="_blank">Paper 1</a> and <a href="https://www.sciencedirect.com/science/article/pii/S1364032121011746" target="_blank">Paper 2</a>, published by <a href="https://www.sciencedirect.com/journal/energy" target="_blank">Energy</a> and <a href="https://www.sciencedirect.com/journal/renewable-and-sustainable-energy-reviews" target="_blank">Renewable and Sustainable Energy Reviews
</a>, respecitively. The second paper is the <strong>Highly Cited Paper</strong> in 2022, 2023, and 2024, <a href="https://www-webofscience-com.ezproxy.lib.utexas.edu/wos/woscc/summary/ced4c522-5b41-43b6-a82c-8015f5c083e1-0103f2b492/relevance/1" target="_blank">Web of Science</a> .
    </p>
</div>
---

### 5.3 Formula Student China
<div style="display: flex; align-items: center; margin-bottom: 20px;">
    <img src="https://jiaminx7.github.io/Website/images/FSAE.jpg" alt="FASE" style="margin-right: 15px; width: 400px;">
    <p>Three year experiences of <a href="http://www.formulastudent.com.cn/" target="_blank">Formula Student China</a> competition. Designed and manufactured one inter combustion engine and one electric formula racers per year.
    </p>
</div>
---

# Publications {#Publications}
## Journal
- **Xu, J.**, Demirer, N., Pho, V., Tian, K., Zhang, H., Bhaidasna, K., Darbe, R. and Chen, D., 2024. Advancing real-time drilling trajectory prediction with an efficient nonlinear DDE model and online parameter estimation. *Geoenergy Science and Engineering, 238, p.212829.*

- **Xu, J**, Keller A, Nazli D, Zhang H, Tian K, Bhaidasna K, Darbe R, Chen D. Experimentally Validated Nonlinear Delayed Differential Approach to Model Borehole Propagation for Directional Drilling. *ASME Letters in Dynamic Systems and Control, ALDSC-23-1030*. (Best Student Paper Finalist, MECC 2023)

- **Xu, J.**, Zhang C, Wan Z, Chen X, Chan SH, Tu Z. Progress and perspectives of integrated thermal management systems in PEM fuel cell vehicles: A review. *Renewable and Sustainable Energy Reviews, 2022;155:111908.* (Highly Cited Paper in 2022 and 2023, Web of Science. 149 citations so far)

- **Xu, J.**, Zhang C, Fan R, Bao H, Wang Y, Huang S, et al. Modelling and control of vehicle integrated thermal management system of PEM fuel cell vehicle. *Energy, 2020;199:117495.* (117 citations so far)

- Fan R, Chang G, **Xu, Y.**, **Xu, J.** Multi-objective optimization of graded catalyst layer to improve performance and current density uniformity of a PEMFC. *Energy, 2023 Jan 1;262:125580.* (Highly Cited Paper in 2023, 40 citations so far)

- Ma R, **Xu, J.**, Li J, Yuan H, Zhang C. A multi-conditions speed predictor based on a DK clustering model. *Journal of Chongqing University.*
---

## Conference
- **Xu, J.**, Demirer, N., Pho, V., Tian, K., Zhang, H., Bhaidasna, K., Darbe, R. and Chen, D., 2024. Nonlinear Model Predictive Control for Directional Drilling Applications. *(Accepted).*

- **Xu, J.**, Demirer, N., Pho, V., Tian, K., Zhang, H., Bhaidasna, K., Darbe, R. and Chen, D., 2024. Data-Driven Modeling of Nonlinear Delay Differential Equations with Gap Effects Using SINDy. *(Accepted).*
---
