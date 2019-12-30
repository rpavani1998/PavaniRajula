---
layout: post
title: "My Journey with Outreachy+Ceph"
date: 2018-08-14 00:00:00
author: "Rajula Pavani"
image: outreachy-logo.png
tags:  Tech 
---

<p>Officially my Internship kicked off on May 14th 2018. It's already been almost weeks my internship started. </p>

<p> Let me first introduce to the organization and the project I have been working on.</p>

<h2>Organization I am working under..</h2>
<h3> Ceph </h3>
<p>Ceph is an open source storage platform, it provides high performance, reliability, and scalability. It's a free distributed storage system that provides an interface for object, block, and file-level storage and can operate without a single point of failure.</p>
<h2>Project I am working on..</h2>

<h3>Creation of a CephFS Shell and CLI Tool</h3>

<p>The Ceph file system (CephFS) provides for kernel driver and FUSE client access. In testing and trivial system administration, the FUSE interface is commonly used but can be cumbersome. This project aims to provide a shell and CLI tool interface to CephFS using the existing libcephfs client library and python bindings. The shell should allow for a series of commands (like mkdir) against the file system. Additionally, if time permits, the project should adapt existing tests to use the new toolset. In simple words, the project is to create a user interface shell to access ceph file system. In other words, This project aims to provide a shell and CLI tool interface to CephFS using the existing libcephfs client library and python bindings. The shell should allow for a series of commands (like mkdir) against the file system. Additionally, if time permits, the project should adapt existing tests to use the new toolset. In simple words, the project is to create a user interface shell to access ceph file system.</p>

<p>In this project my task was to write a user-friendly shell in Python2/3 which calls out the python bindings around libcephfs. ​Being a tech enthusiast and a linux lover always curious about how the commands work in backend, with this project I got the opportunity to actually create those commands for a file system.</p>

<h2>Initial weeks of my Internship</h2>
<p> The time has flown by. I have spent them through setting up my system to get started, exploring the implementations, modules that I can include in my project and tried to do a basic implementation of the same. The first week was more of reading and understanding stuff. I was even asked by my mentor to write a brief documentation of the commands I would like to implement. </p>

<p> It was really a awesome learning weeks. My mentor is really friendly, very helpful and guiding me not just to complete the project but also to forgo my wrong coding practices and help
me get stronger technically.</p>
<center>
    <a href="#">
        <img src="{{ site.baseurl }}/img/InitalShell.png" alt="accepted" style="height:200px; width:100%">
    </a>
   <span class="caption text-muted">This is how the Shell is by the end of first two weeks</span>
</center>

<h2> Initial Weeks Learnings </h2>
<p> I was been coding in python for about 2 years. But this was another new experience with python exploring different modules in python to create a shell. During the initial weeks I came accross new modules in python for creating a shell like argparse, click, optparse, docopt and so on. I would like to write a blog on Creating a shell in python using these modules very soon.</p>
<p>Making mistakes is always a great learning. Computer science is the stream where you will learn technology only by  experimenting, making mistakes and learning from those mistakes.</p>
<p>Documentation! Whatever you do making a documention, will help you and anyone better understand the work/project.</p>
<p>This work is giving me the opportunity to sharpen my Git skills. </p>

<h2> Completing my Internship Work </h2>
<p>Initally, I faced lot of difficulties in getting started but later I realised that my task was kind of easy because whatever I was working on is from the scratch, I had the freedom to select the tool to work on, additional features to be added. I got to work from designing, coding, documentation and testing too.</p>

<p>Starting with basic complete implementation of each and every command executation and then added additional options to them. This is how I started completing the shell commands. Later comparing the shell I have created with the one we actually use, I got to add features like colors, auto-complete, regression expressions, accessing commands history , few other commands which makes interaction more ease like alias, shortcuts, load and so on.</p>

<center>
    <a href="#">
        <img src="{{ site.baseurl }}/img/EndShell.png" alt="accepted" style="height:400px; width:95%">
    </a>
   <span class="caption text-muted">This is how the Shell is by the end of the intrenship.</span>
</center>

<p>The Shell was completely built using Python compatible for both version 2 and 3 and C++, all the libcephfs plugins are written in C++ which are used python by using cython.</p>
   
<p>Cmd2 ,Colorama, argparse, shutil, shlex are some of the python modules used for creating a shell. Not just creating shell I worked on creating new functionalities in libcephfs and updated python bindings. Ex. umask command..
Following are some of the functionalities the shell has.</p>
<p>
<li> AutoComplete commands</li>
<li> Previous commands</li>
<li> Copy commands to a file</li>
<li> Run a file commands</li>
<li> Color variations for files</li>
<li> Regression expressions</li>
<li> Aliasing commands</li>
<li> Shortcuts</li>
<li> Help</li>
</p>

<p> As part of the Internship I got to work on stages of the sdlc from requirement gathering, designing, coding, testing and documenting. The developed shell till date, unit testing (python) is done and documentation is written for further enhancements.</p>

<p>Though I was asked to work on the ceph teuthology testing tool but I had setup issues and also I came to the end of the internship, I could'nt do that instead I have completed the unit testing of the shell manually. Other than gthat I have completed the rest of the tasks as mentioned as per the internship description.</p>
<p>
<p>Here is the a demo of my work</p>
<iframe src="https://www.youtube.com/embed/tonJmvsZBDc" frameborder="0" allowfullscreen></iframe>
</p>
<p> This was one of the best experiences I ever had and was such a amazing learning expreience my mentor helped me with lot of patience and helped me understand things in a better way. Not just desinging, gathering, coding, testing and documenting I learned to communicating, multi-tasking, stress management and blogging too. I had to stop my contribution as I became busy in my academic work as I was in my 3rd year end, placements, project submissions and so on. Still I looked back into the project whenever possible.</p>

<p>I would like to thank everyone who were part of my internship journey and helped me to complete it successfully!</p>