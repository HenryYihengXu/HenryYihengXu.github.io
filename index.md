---
title:  "About Me"
layout: single
permalink: /
author_profile: true
comments: true
---

<style type="text/css">
.justify {text-align: justify;}

details {
    font-family:Arial, sans-serif;
    font-size:18px;
    border: 1.5px solid #aaa;
    border-radius: 4px;
    padding: .5em .5em 0;
}

summary {
    font-family:Arial, sans-serif;
    font-size:18px;
    font-weight: bold;
    margin: -.5em -.5em 0;
    padding: .5em;
}

details[open] {
    padding: .5em;
}

details[open] summary {
    border-bottom: 1px solid #aaa;
    margin-bottom: .5em;
}
</style>

\\
I'm a CS master's student at the University of Maryland (UMD), graduating in May 2023, with an over 3.9 GPA in coursework. I'm a motivated programmer with considerable experience in real-world projects. I have interned at Lawrence Livermore National Laboratory, where I did software engineering on several performance analysis tools. I have also interned at the Institute of Computing Technology in China, where I contributed to developing a high-performance FFT library. In the internship, I optimized several kernel functions and implemented a new algorithm for a specific type of FFT. Besides, I have worked on web application development for a lab at UW-Madison, where I created an interactive frontend using React and a backend using Node.js and Maven. I'm currently working as a research assistant at UMD on performance modeling and tool development. I'm actively seeking a software engineering full-time position. 
<hr style="border: 1.5px solid black; margin: 3em 0 3em; background-color: black;">

## Education:
- **University of Maryland, College Park** (2020 - present)   
  MS in Computer Science, GPA: 4.0/4.0
- **University of Wisconsin, Madison** (2018 - 2020)   
  BS in Computer Science, GPA: 4.0/4.0
- **Wuhan University** (2016 - 2018)   
  BS in Computer Science, GPA: 3.9/4.0. National Scholarship (Top 0.2 nationwide)
<hr style="border: 1.5px solid black; margin: 3em 0 3em; background-color: black;">

## Skills:
- **Programming:** Java, C/C++, Python, JavaScript, MPI, Cuda, SQL
- **Domain Knowledge:** High-Performance Algorithm and Data Structure, Software Engineering, Parallel Programming, Performance Modeling
<hr style="border: 1.5px solid black; margin: 3em 0 3em; background-color: black;">

## Experience:
<p style="margin: 0 0 0.5em;"><b>University of Maryland</b>, Research Assistant. <br> College Park, MD. 09/2020 - present</p>
<p style="margin: 0 0 0.5em;"> <b>Parallel I/O performance modeling with ML</b> </p>
<details class="justify">
    <summary>Details</summary>
<ul>
<li> Designed an ML model that predicts the best storage system based on an app’s I/O patterns with 97% accuracy. </li>
<li> Developed a python-based performance analysis tool that automates analysis and I/O pattern extractions. </li>
<li> Comparatively evaluated several storage systems and created a dataset of I/O performance w.r.t. I/O patterns. </li>
</ul>
</details>
<hr>

<p style="margin: 0 0 0.5em;"><b>Lawrence Livermore National Laboratory</b>, Software Engineer Intern. <br> Livermore, CA. 05/2020 - 08/2021</p>
<p style="margin: 0 0 0.5em;"> <b>Software development with C++</b> </p>
<details class="justify">
    <summary>Details</summary>
<ul>
<li> Integrated GOTCHA into several performance profiling software so they can be executed at the same time. </li>
<li> Reduced the time spent in getting profiling results by a factor of N, where N is the number of profilers. </li>
<li> Reduced variability of profiling results from 35% to 12%. </li>
</ul>
</details>
<hr>

<p style="margin: 0 0 0.5em;"><b>MadPL Lab at UW-Madison</b>, Web Development Assistant. <br> Madison, WI. 09/2019–01/2020</p>
<p style="margin: 0 0 0.5em;"> <b>Web Development for a Regex Fixing Application</b> </p>
<details class="justify">
    <summary>Details</summary>
<ul>
<li> Designed an interactive frontend using React and JavaScript ES6. </li>
<li> Built a back-end server using Node.js and Maven to talk to the program to fix the regex. </li>
<li> Optimized the application so that it could provide some matching information before running the whole server program. </li>
</ul>
</details>
<hr>

<p style="margin: 0 0 0.5em;"><b>PerfXLab & Institute of Computing Technology</b>, Software Engineer Intern. <br> Beijing, China. 06/2019–09/2019</p>
<p style="margin: 0 0 0.5em;"> <b>Web Development for a Regex Fixing Application</b> </p>
<details class="justify">
    <summary>Details</summary>
<ul>
<li> Optimized kernel functions based on x86 architecture by optimizing memory allocation, cache usage, etc. </li>
<li> Implemented the core “split” function for both single and double-precision floating-point using SIMD, which improved the parallelism by a factor of 4. </li>
<li> Implemented a faster REDFT00 sub-transform algorithm. The new algorithm improved the performance of this transform for large-scale inputs by 35%. </li>
</ul>
</details>
<hr style="border: 2px solid black; margin: 3em 0 3em; background-color: black;">

## Selected Projects:
<p style="margin: 0 0 0.5em;"><b>Marius: High-Performance Software for Large-Scale Graph Embeddings</b></p>
<ul>
<li> A C++ Software for graph embeddings (an ML problem). Implemented a multi-thread pipeline for evaluation and stateful optimizer for gradient descent. Explored smarter sampling and tuning strategies for hyper-parameter tuning. </li>
</ul>

<p style="margin: 0 0 0.5em;"><b>Online Book Store</b></p>
<ul>
<li> A JavaEE web application. Implemented the frontend with HTML and JavaScript. Built the server with Hibernate and Spring framework. Used MYSQL as the database and used JDBC to access it. </li>
</ul>

<p style="margin: 0 0 0.5em;"><b>Qirkat Game AI</b></p>
<ul>
<li> A Java implementation of a board game called Qirkat and its game AI. Implemented the game AI using alpha-beta pruning and several heuristics. </li>
</ul>

<hr style="border: 1.5px solid black; margin: 3em 0 3em; background-color: black;">

## Publications:
- [**Chaining Multiple Tools and Libraries Using Gotcha** (SC '21 Poster)](https://pssg.cs.umd.edu/assets/posters/2021-11-chaining-tools-sc.pdf)
  Yiheng Xu, Kathryn Mohror, Hariharan Devarajan, Cameron Stanavige, Abhinav Bhatele
- [**Marius: Learning Massive Graph Embeddings on a Single Machine** (OSDI '21)](https://arxiv.org/abs/2101.08358)   
  Jason Mohoney, Roger Waleffe, Yiheng Xu, Theodoros Rekatsinas, Shivaram Venkataraman
