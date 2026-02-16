---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
/* Skills Section - Integrated with AcademicPages */
.skills-showcase {
  margin: 2em 0;
  padding: 1.5em;
  background: rgba(255, 255, 255, 0.02);
  border-radius: 4px;
  border: 1px solid rgba(255, 255, 255, 0.1);
}

.skills-showcase h2 {
  font-size: 1.4em;
  margin-bottom: 1.2em;
  font-weight: 600;
  border-bottom: 1px solid rgba(255, 255, 255, 0.1);
  padding-bottom: 0.5em;
}

.skills-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
  gap: 1.5em;
  margin-bottom: 1em;
}

.skill-category h3 {
  font-size: 0.75em;
  text-transform: uppercase;
  letter-spacing: 0.05em;
  //color: rgba(255, 255, 255, 0.5);
  margin-bottom: 0.8em;
  font-weight: 600;
}

.skill-bubbles {
  display: flex;
  flex-wrap: wrap;
  gap: 0.5em;
}

.skill-bubble {
  padding: 0.35em 0.9em;
  background: rgba(255, 255, 255, 0.06);
  border: 1px solid rgba(255, 255, 255, 0.12);
  border-radius: 1em;
  font-size: 0.8em;
  transition: all 0.25s ease;
  font-family: Monaco, Consolas, monospace;
}

.skill-bubble:hover {
  background: rgba(82, 113, 255, 0.25);
  border-color: rgba(82, 113, 255, 0.5);
  transform: translateY(-2px);
}

/* Featured Projects - Matching AcademicPages archive style */
.featured-projects {
  margin: 2.5em 0;
}

.featured-projects h2 {
  font-size: 1.563em;
  margin-bottom: 1em;
  font-weight: 600;
  border-bottom: 1px solid rgba(255, 255, 255, 0.1);
  padding-bottom: 0.5em;
}

.project-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
  gap: 1.5em;
  margin-bottom: 1.5em;
}

.project-highlight {
  background: rgba(255, 255, 255, 0.02);
  border: 1px solid rgba(255, 255, 255, 0.1);
  border-radius: 4px;
  overflow: hidden;
  transition: all 0.3s ease;
}

.project-highlight:hover {
  border-color: rgba(82, 113, 255, 0.5);
  transform: translateY(-3px);
  box-shadow: 0 4px 12px rgba(0, 0, 0, 0.3);
}

.project-image {
  width: 100%;
  height: 180px;
  background: rgba(0, 0, 0, 0.2);
  position: relative;
  overflow: hidden;
}

.project-image img {
  width: 100%;
  height: 100%;
  object-fit: cover;
  transition: transform 0.3s ease;
}

.project-highlight:hover .project-image img {
  transform: scale(1.05);
}

.project-badge {
  position: absolute;
  top: 0.6em;
  right: 0.6em;
  background: #5271ff;
  color: white;
  padding: 0.25em 0.7em;
  border-radius: 0.6em;
  font-size: 0.65em;
  font-weight: 600;
  text-transform: uppercase;
  letter-spacing: 0.03em;
}

.project-content {
  padding: 1.2em;
}

.project-content h3 {
  font-size: 1.1em;
  margin-bottom: 0.4em;
  font-weight: 600;
}

.project-meta {
  color: #5271ff;
  font-size: 0.75em;
  margin-bottom: 0.6em;
  font-family: Monaco, Consolas, monospace;
}

.project-description {
  font-size: 0.875em;
  line-height: 1.5;
  //color: rgba(255, 255, 255, 0.65);
  margin-bottom: 0.9em;
}

.project-tags {
  display: flex;
  flex-wrap: wrap;
  gap: 0.4em;
}

.project-tag {
  padding: 0.25em 0.6em;
  background: rgba(255, 255, 255, 0.06);
  border: 1px solid rgba(255, 255, 255, 0.12);
  border-radius: 0.6em;
  font-size: 0.7em;
  //color: rgba(255, 255, 255, 0.7);
  font-family: Monaco, Consolas, monospace;
}

.view-all-link {
  display: inline-block;
  padding: 0.7em 1.5em;
  background: transparent;
  border: 2px solid #5271ff;
  color: #5271ff;
  text-decoration: none;
  border-radius: 4px;
  font-weight: 600;
  font-size: 0.9em;
  transition: all 0.25s ease;
  margin-top: 0.5em;
}

.view-all-link:hover {
  background: #5271ff;
  color: white;
  transform: translateY(-2px);
  text-decoration: none;
}

/* Quick Highlight Box */
.highlight-box {
  margin: 2em 0;
  padding: 1.2em 1.5em;
  background: rgba(82, 113, 255, 0.08);
  border-left: 3px solid #5271ff;
  border-radius: 4px;
}

.highlight-box p {
  margin: 0;
  font-size: 0.95em;
  line-height: 1.6;
}

.highlight-box strong {
  font-weight: 600;
}

/* Achievement Badges */
.achievement-list {
  margin: 1.5em 0;
}

.achievement-list li {
  margin-bottom: 0.5em;
  font-size: 0.95em;
}

@media (max-width: 768px) {
  .project-grid {
    grid-template-columns: 1fr;
  }
  
  .skills-grid {
    grid-template-columns: 1fr;
  }
}
</style>

I'm a roboticist who builds autonomous systems for the real world - from tensegrity robots that can 
navigate unstructured terrain, to edge-deployed computer vision for autonomous tracking. My work sits at the 
intersection of robotics, deep learning, and systems integration. I'm particularly interested in understanding how we 
make increasingly capable autonomous systems safe, interpretable, and robust when they interact with the physical 
world. **I'm actively seeking industry R&D opportunities** where I can apply my expertise to build next-generation 
robotic systems. 

I'm currently a Visiting Assistant Professor in the Electrical and Computer Engineering Department at Florida 
International University in Miami, Florida.  Since [joining the department](https://ece.fiu.edu/people/faculty/profiles/lauren-ervin/index1.html) in August 2025, I have been designing new robotics and 
computer vision courses, mentoring students, and leading research on embodied AI systems.  Recent 
projects I'm excited about include dynamic modeling of a tensegrity continuum manipulator with data-driven 
approaches, and reinforcement learning for challenging multi-agent tasks like cooperative lifting with miniature 
biped robots.

## Featured Projects

<div class="featured-projects">
  <div class="project-grid">
    
    <div class="project-highlight">
      <div class="project-image">
        <span class="project-badge">Featured</span>
        <img src="../images/texplor_quasi/TeXploR2ImpactSideView.gif" alt="TeXploR2">
      </div>
      <div class="project-content">
        <h3>TeXploR2 Robot</h3>
        <p class="project-meta">IEEE ICRA 2026</p>
        <p class="project-description">
          System design of an improved curved-link tensegrity robot with non-intuitive locomotion.
        Expanded upon geometric modeling framework to include quasistatic simulations.
        </p>
        <div class="project-tags">
          <span class="project-tag">MATLAB</span>
          <span class="project-tag">Vicon</span>
          <span class="project-tag">Raspberry Pi</span>
          <span class="project-tag">3D Printing</span>
        </div>
      </div>
    </div>
    
    <div class="project-highlight">
      <div class="project-image">
        <span class="project-badge">In Progress</span>
        <img src="../images/manipulator/manipulator4x.gif" alt="Tensegrity Manipulator">
      </div>
      <div class="project-content">
        <h3>Tensegrity Manipulator</h3>
        <p class="project-meta">Current Research</p>
        <p class="project-description">
          System integration of tensegrity manipulator with motor-tendon actuators, in-line load cells, 
        and Vicon motion capture. Developing dynamic modeling using a modified RNEA algorithm with a data-driven 
        approach coming soon.
        </p>
        <div class="project-tags">
          <span class="project-tag">MATLAB</span>
          <span class="project-tag">Jetson</span>
          <span class="project-tag">Load Cells</span>
          <span class="project-tag">Vicon</span>
        </div>
      </div>
    </div>

    <div class="project-highlight">
      <div class="project-image">
        <span class="project-badge">Best Paper</span>
        <img src="../images/microspines/microspines.gif" alt="Microspines">
      </div>
      <div class="project-content">
        <h3>Compliant Microspines</h3>
        <p class="project-meta">IEEE ICRA 2025 | Patent Pending</p>
        <p class="project-description">
          Novel mechanism design improving grip stability for soft robots on unstructured terrain. Won Best Paper Award at ICRA Space Robotics Workshop.
        </p>
        <div class="project-tags">
          <span class="project-tag">Mechanism Design</span>
          <span class="project-tag">OpenCV</span>
          <span class="project-tag">Patent</span>
        </div>
      </div>
    </div>

    <div class="project-highlight">
      <div class="project-image">
        <span class="project-badge">Simulation</span>
        <img src="../images/cam_lidar_projection/serc2048_odometry.gif" alt="Jackal Gazebo Odometry">
      </div>
      <div class="project-content">
        <h3>Jackal Gazebo Odometry</h3>
        <p class="project-meta">Clearpath Jackal</p>
        <p class="project-description">
          Generated custom Gazebo worlds both inside labs and real-world outside environments.  Simulated Clearpath 
          Jackal robot in Gazebo and performed various navigation algorithms.
        </p>
        <div class="project-tags">
          <span class="project-tag">ROS</span>
          <span class="project-tag">Gazebo</span>
          <span class="project-tag">Simulation</span>
        </div>
      </div>
    </div>
    
  </div>
  
  <a href="/portfolio/" class="view-all-link">View All Projects →</a>
</div>

## Skills

<div class="skills-showcase">
  <div class="skills-grid">
    <div class="skill-category">
      <h3>Programming</h3>
      <div class="skill-bubbles">
        <span class="skill-bubble">Python</span>
        <span class="skill-bubble">MATLAB</span>
        <span class="skill-bubble">ROS</span>
        <span class="skill-bubble">C++</span>
      </div>
    </div>
  </div>

  <div class="skills-grid">
    <div class="skill-category">
      <h3>DL/AI/CV</h3>
      <div class="skill-bubbles">
        <span class="skill-bubble">TensorFlow</span>
        <span class="skill-bubble">Keras</span>
        <span class="skill-bubble">CNNs</span>
        <span class="skill-bubble">OpenCV</span>
        <span class="skill-bubble">RL</span>
      </div>
    </div>
  </div>
    
  <div class="skills-grid">
    <div class="skill-category">
      <h3>Simulation</h3>
      <div class="skill-bubbles">
        <span class="skill-bubble">Gazebo/RViz</span>
        <span class="skill-bubble">Isaac Sim/Lab</span>
        <span class="skill-bubble">MuJoCo</span>
      </div>
    </div>
  </div>

  <div class="skills-grid">
    <div class="skill-category">
      <h3>Robotics Hardware</h3>
      <div class="skill-bubbles">
        <span class="skill-bubble">NVIDIA Jetson</span>
        <span class="skill-bubble">Arduino</span>
        <span class="skill-bubble">RPi</span>
        <span class="skill-bubble">ESP32</span>
        <span class="skill-bubble">Clearpath Jackal</span>
      </div>
    </div>
  </div>
    
  <div class="skills-grid">
    <div class="skill-category">
      <h3>Sensors</h3>
      <div class="skill-bubbles">
        <span class="skill-bubble">LiDAR</span>
        <span class="skill-bubble">RGB/Stereo Camera</span>
        <span class="skill-bubble">IMU</span>
        <span class="skill-bubble">Vicon</span>
        <span class="skill-bubble">RTK GPS</span>
        <span class="skill-bubble">Load Cell</span>
      </div>
    </div>
  </div>

  <div class="skills-grid">
    <div class="skill-category">
      <h3>Prototyping</h3>
      <div class="skill-bubbles">
        <span class="skill-bubble">KiCAD</span>
        <span class="skill-bubble">OtherMill</span>
        <span class="skill-bubble">Soldering</span>
        <span class="skill-bubble">Fusion 360/SolidWorks</span>
        <span class="skill-bubble">FDM/SLA/Voxel8 Printers</span>
        <span class="skill-bubble">Injection Molding/Casting</span>
        <span class="skill-bubble">Water Jetting/Laser Cutting</span>
      </div>
    </div>
  </div>
    
  <div class="skills-grid">
    <div class="skill-category">
      <h3>Tools</h3>
      <div class="skill-bubbles">
        <span class="skill-bubble">Git</span>
        <span class="skill-bubble">Docker</span>
        <span class="skill-bubble">Linux</span>
      </div>
    </div>
  </div>
</div>

<!--
<div class="highlight-box">
  <p><strong>Looking for an industry robotics engineer?</strong> I bring end-to-end capabilities from hardware design to ML deployment, with a track record of building working systems. Previously held TS/SCI clearance at NSA (2017-2019).</p>
</div>
-->

## Background

I completed my Ph.D. from the Electrical and Computer Engineering Department at the University of 
Alabama in August 2025.  During my time there, I worked across two labs: the [Agile Robotics Lab](https://sites.ua.edu/arl/), building and modeling tensegrity robots with non-intuitive behaviors, and the [Embedded and Robotic 
Systems Lab](https://ece.eng.ua.edu/laboratories/ersyl-embedded-and-robotic-systems-laboratory/), developing 
semantic segmentation pipelines for autonomous tracking on the edge and co-developing an open-source, multimodal 
dataset targeting vehicles.  My work has been recognized with awards including the Best 
Paper Award at the IEEE ICRA 2025 Soft Robotics for Space Applications Workshop, ECOB Electrical Engineering 
Graduate Student of the Year (2024), and three rounds of the NASA ASGC Fellowship (2022, 2023, and 2024).  I also 
held a TS/SCI clearance during my time as a co-op at the Department of Defense (2017-2019), where I worked on robotics 
and hardware design projects.

**Key Achievements:**
- **Best Paper Award** - IEEE ICRA 2025 Soft Robotics for Space Workshop
- **Featured in IEEE Spectrum** - "Coolest Robots at ICRA" (2025)
- **NASA ASGC Fellowship** - 3 independent rounds (2022-2025)
- **ECOB EE Graduate Student of the Year** (2024)
- **NSF iREDEFINE Award** (2024)
- **2nd Place Best Poster Award** - UA ECE Grad Poster Competition (2024)
- **NSF BPart Fellowship** (2023)
- **1st Place Best Poster Award** - UA ECE Grad Poster Competition (2023)
- **NSF LIA Scholarship** 2018-2020
- **UA Engineering Scholarship** (2016-2020)
- **TS/SCI Clearance** - DoD (2017-2019)

## Recent Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> </div><img src='images/ICRA 2025 Microspines Graphical Abstract.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Improving Grip Stability Using Passive Compliant Microspine Arrays for Soft Robots in Unstructured Terrain](https://ieeexplore.ieee.org/document/11128855) 
**Lauren Ervin<sup>✉</sup>**, Harish Bezawada, Vishesh Vikas. *<b>2025 IEEE International Conference on Robotics and Automation (ICRA), Atlanta, GA, USA, 2025</b>*, pp. 7872-7878, doi: 10.1109/ICRA55743.2025.11128855.<br>
<img src="https://raw.githubusercontent.com/mingsun-tse/mingsun-tse.github.io/master/images/pdf_icon.png" width="20" height="20" hspace="5">
<span><a href="https://ieeexplore.ieee.org/document/11128855">IEEE ICRA 2025 </a></span>
<img src="https://raw.githubusercontent.com/mingsun-tse/mingsun-tse.github.io/master/images/github_icon.png" width="20" height="20" hspace="5">
<span> <a href="https://github.com/lefaris/microspines">Code</a></span><br>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> </div><img src='images/TeXploR_ICRA_graphical_abstract.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Geometric Static Modeling Framework for Piecewise-Continuous Curved-Link Multi Point-of-Contact Tensegrity Robots](https://ieeexplore.ieee.org/abstract/document/10734217) 
**Lauren Ervin<sup>✉</sup>**,Vishesh Vikas. *<b>IEEE Robotics and Automation Letters</b>*, vol. 9, no. 12, pp. 11066-11073, Dec. 2024, doi: 10.1109/LRA.2024.3486199.<br>
<img src="https://raw.githubusercontent.com/mingsun-tse/mingsun-tse.github.io/master/images/pdf_icon.png" width="20" height="20" hspace="5">
<span><a href="https://ieeexplore.ieee.org/abstract/document/10734217">IEEE RA-L </a></span>
<img src="https://raw.githubusercontent.com/mingsun-tse/mingsun-tse.github.io/master/images/github_icon.png" width="20" height="20" hspace="5">
<span> <a href="https://github.com/lefaris/TeXploR-geometric">Code</a></span><br>
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge"> </div><img src='images/semantic_graphical_abstract.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Evaluation of Semantic Segmentation Performance for a Multimodal Roadside Vehicle Detection System on the Edge](https://www.mdpi.com/1424-8220/25/2/370) 
**Lauren Ervin<sup>✉</sup>**, Max Eastepp, Mason McVicker, Kenneth Ricks. *<b>Sensors</b>*, 2025, 25, 370, doi: 10.3390/s25020370.<br>
<img src="https://raw.githubusercontent.com/mingsun-tse/mingsun-tse.github.io/master/images/pdf_icon.png" width="20" height="20" hspace="5">
<span><a href="https://www.mdpi.com/1424-8220/25/2/370">Sensors </a></span>
<img src="https://raw.githubusercontent.com/mingsun-tse/mingsun-tse.github.io/master/images/github_icon.png" width="20" height="20" hspace="5">
<span> <a href="https://github.com/UA-Roadside-Semantic-Segmentation/Multimodal-Roadside-Detection">Code</a>, <a href="https://doi.org/10.25452/figshare.plus.19311938.v1">Dataset</a></span><br>
</div>
</div>

<a href="/publications/" class="view-all-link">View All Publications →</a>