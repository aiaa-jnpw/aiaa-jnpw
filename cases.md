---
layout: default
title: Test Cases
permalink: /cases/
---

## **Overview of Test Cases**

The Jet Noise Prediction Workshop (JNPW) will release a series of three test cases in successive phases, each aligned with the AIAA Aviation and SciTech conference cycles (approximately every six months). These cases are designed to progressively increase in physical and geometric complexity, enabling a thorough benchmarking of predictive CFD capabilities across the community.

**The test cases for JNPW are defined in the following document:**  
[**JNPW_Test_Cases_v1.0.pdf**](downloads/JNPW_Test_Cases_v1.0.pdf) *(last updated: 07/11/2025)*



---
<br>

## **JNPW1 - Part I: Canonical Jet Noise Test Cases**
**Description:** Single-stream, isolated round jet based on the SMC000 configuration  
**Purpose:** Establish a baseline using a well-documented canonical jet flow for initial solver comparisons

### **Selected Flow Conditions**
The following table summarizes the selected operating points for Case I, chosen to span a range of subsonic jet conditions. These cases represent the minimum required simulations for workshop participants and are intended to assess baseline solver capability for jet noise prediction.

In addition to covering a range of flow conditions, these set points were intentionally selected to expose known challenges in LES-based jet noise simulations — including sensitivity to turbulence modeling, mesh quality, and numerical dissipation. The goal is to drive deeper understanding and ultimately increase the community’s confidence and consistency in jet noise prediction methodologies.

{% include case1-table2.html %}

<center>
  <img src="{{'/assets/images/SHAR_Rig.png'     | relative_url}}"  width="750"> 
  Figure 1: Depiction of axisymmetric round jet SMC000 in NASA experimental facility
</center>

<br>

---
<br>

## **JNPW1 - Part II: Increased Geometric Complexity (TBD)**  
**Description:** Configurations featuring chevrons, rectangular geometries, and Jet-Surface Interaction (JSI) setups  
**Purpose:** Evaluate predictive performance with added geometric realism and near-field surface interactions

<center>
  <img src="{{'/assets/images/experimental_setup.png'     | relative_url}}"  width="750"> 
  Figure 2: Depiction of SMC000 nozzle configuration with added plate at h/D = 1.0
</center>

<br>

---
<br>

## **JNPW1 - Part III: Multi-Stream Configuration (TBD)**
**Description:** High-speed configurations such as dual-stream nozzles, lobed mixers, twin jets, and JSI at supersonic conditions  
**Purpose:** Extend benchmarking into the supersonic regime with advanced nozzle concepts relevant to future applications


<center>
  <div style="width: 350px; height: 210px; overflow: hidden; display: inline-block;">
    <img src="{{'/assets/images/122Am0pInt.4k.ao.png' | relative_url}}" 
         style="width: 500px; height: 250px; object-fit: cover; object-position: -30px -20px;">
  </div>
  <div style="width: 350px; height: 210px; overflow: hidden; display: inline-block;">
    <img src="{{'/assets/images/122Am5pInt.4k.ao.png' | relative_url}}" 
         style="width: 500px; height: 250px; object-fit: cover; object-position: -30px -20px;">
  </div>
</center>

<center>
  <div style="width: 350px; height: 210px; overflow: hidden; display: inline-block;">
    <img src="{{'/assets/images/122DLm5p2069.4k.ao.png' | relative_url}}" 
         style="width: 500px; height: 250px; object-fit: cover; object-position: -55px -20px;">
  </div>
  <div style="width: 350px; height: 210px; overflow: hidden; display: inline-block;">
    <img src="{{'/assets/images/122DLm5p2069.4k.ao.png' | relative_url}}" 
         style="width: 500px; height: 250px; object-fit: cover; object-position: -55px -10px;">
  </div>
  Figure 3: Depiction of multi-stream plug20 nozzle with internal / external (top / bottom) plug and axisymmetric / lobed (left / right) mixer
</center>



<br>

---
Recent significant updates:

- **July 11, 2025** – Initial draft created

