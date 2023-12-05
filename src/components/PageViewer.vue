<template>
  <div class="container-fluid">
    <div class="row">
      <div class="col p-3 bg-warning text-light">
        <span class="badge rounded-pill bg-warning" style="font-size: larger;">RAM IT <br /> DevOps
          Instructor</span>
      </div>
      <div class="col p-3 bg-warning text-light rounded text-center">
        <span class="badge rounded-pill bg-warning" style="font-size: larger;">
          DevOps New Batch <br />
          December 9th (Thrusday) <br />
          7:00 PM to 8:30 PM IST
        </span>
      </div>
      <div class="col p-3 bg-warning text-light">
        <span class="badge rounded-pill bg-warning float-end" style="font-size: larger;">WhatsApp
          +9999988888</span>
      </div>
    </div>
  </div>


  <div id="demo" class="carousel slide" data-bs-ride="carousel">


    <div class="carousel-indicators">
      <button type="button" data-bs-target="#demo" data-bs-slide-to="0" class="active"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="1"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="2"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="3"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="4"></button>
      <button type="button" data-bs-target="#demo" data-bs-slide-to="5"></button>
    </div>


    <div class="carousel-inner">

      <div class="carousel-item active">
        <img src="kube.jpg" class="d-block" style="width:100%">
        <div class="carousel-caption">
          <h3></h3>
          <p></p>
        </div>
      </div>

      <div class="carousel-item">
        <img src="jenkins.jpg" class="d-block" style="width:100%">
        <div class="carousel-caption">
          <h3></h3>
          <p></p>
        </div>
      </div>

      <div class="carousel-item">
        <img src="ansible.jpg" alt="Chicago" class="d-block" style="width:100%">
        <div class="carousel-caption">
          <h3></h3>
          <p></p>
        </div>
      </div>

      <div class="carousel-item">
        <img src="terraform.jpg" class="d-block" style="width:100%">
        <div class="carousel-caption">
          <h3></h3>
          <p></p>
        </div>
      </div>

      <div class="carousel-item">
        <img src="prometheus.jpg" class="d-block" style="width:100%">
        <div class="carousel-caption">
          <h3></h3>
          <p></p>
        </div>
      </div>

      <div class="carousel-item">
        <img src="grafana.jpg" class="d-block" style="width:100%">
        <div class="carousel-caption">
          <h3></h3>
          <p></p>
        </div>
      </div>
    </div>


    <button class="carousel-control-prev" type="button" data-bs-target="#demo" data-bs-slide="prev">
      <span class="carousel-control-prev-icon"></span>
    </button>
    <button class="carousel-control-next" type="button" data-bs-target="#demo" data-bs-slide="next">
      <span class="carousel-control-next-icon"></span>
    </button>
  </div>

  <div class="m-4 text-center">
    <h4 class="ms-4">DevOps Syllabus</h4>
  </div>
    <div class="container d-flex mt-4 p-4">
      <div class="card mb-3" style="max-width:680px;">
      <div class="row g-0">
        <div class="col-md-2">
          <img src="devops.png" class="img-fluid rounded-start" alt="...">
        </div>
        <div class="col-md-10">
          <div class="card-body">
            <h5 class="card-title">
              INTRODUCTION TO DEVOPS
            </h5>
            <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item p-0">What is Devops?</li>
                  <li class="list-group-item p-0">Why Devops?</li>
                  <li class="list-group-item p-0">Devops Tools</li>
                  <li class="list-group-item p-0">Differences between traditional methodologies and DEVOPS-approach</li>
                  <li class="list-group-item p-0">Big Picture of CI/CD Devops Delivery Pipeline</li>
                </ul>
            </p>            
          </div>
        </div>
      </div>
    </div>
      <div class="card mb-3" style="max-width:680px;">
        <div class="row g-0">
          <div class="col-md-2">
            <img src="linux.png"
              class="img-fluid rounded-start" alt="...">
          </div>
          <div class="col-md-10">
            <div class="card-body">
              <h5 class="card-title">OPERATING SYSTEM & LINUX BASICS</h5>
              <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item p-0">Introduction to Operating Systems</li>
                  <li class="list-group-item p-0">Introduction to Virtual Machines</li>
                  <li class="list-group-item p-0">Linux File Systems</li>
                  <li class="list-group-item p-0">Introduction to Command Line Interface</li>
                  <li class="list-group-item p-0">Basic Linux Commands</li>
                  <li class="list-group-item p-0">Package Manager - Installing Software in Linux</li>
                  <li class="list-group-item p-0">Vim Text Editor</li>
                  <li class="list-group-item p-0">Users and Permissions</li>
                  <li class="list-group-item p-0">Shell Scripting</li>
                  <li class="list-group-item p-0">Environment Variables</li>
                  <li class="list-group-item p-0">SSH -Secure Shell</li>
                </ul>
              </p>              
            </div>
          </div>
        </div>
      </div>
    </div> 

  <div class="container d-flex mt-4 p-4">
      <div class="card mb-3" style="max-width:680px;">
      <div class="row g-0">
        <div class="col-md-2">
          <img src="git.png" class="img-fluid rounded-start" alt="...">
        </div>
        <div class="col-md-10">
          <div class="card-body">
            <h5 class="card-title">
              VERSION CONTROL SYSTEM - GIT
            </h5>
            <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item p-0">Introduction to VCS</li>
                  <li class="list-group-item p-0">Types of VCS</li>
                  <li class="list-group-item p-0">Difference between CVCS and DVCS</li>
                  <li class="list-group-item p-0">What is GIT</li>
                  <li class="list-group-item p-0">GIT Architecture</li>
                  <li class="list-group-item p-0">GIT installation on Windows and Linux</li>
                  <li class="list-group-item p-0">GIT commands</li>
                  <li class="list-group-item p-0">Working with GIT</li>
                  <li class="list-group-item p-0">Creating repository</li>
                  <li class="list-group-item p-0">Cloning repository</li>
                  <li class="list-group-item p-0">Committing the changes</li>
                  <li class="list-group-item p-0">Fetch, pull and remote</li>
                  <li class="list-group-item p-0">Branching Strategy in GIT</li>
                  <li class="list-group-item p-0">Creating the Branches</li>
                  <li class="list-group-item p-0">Switching the branches</li>
                  <li class="list-group-item p-0">Merging the branches</li>
                  <li class="list-group-item p-0">Git reset</li>
                  <li class="list-group-item p-0">Git rebase</li>
                  <li class="list-group-item p-0">Git stash</li>
                  <li class="list-group-item p-0">Working with GitHub</li>
                </ul>
            </p>            
          </div>
        </div>
      </div>
    </div>
      <div class="card mb-3" style="max-width:680px;">
        <div class="row g-0">
          <div class="col-md-2">
            <img src="jenkinslogo.png"
              class="img-fluid rounded-start" alt="...">
          </div>
          <div class="col-md-10">
            <div class="card-body">
              <h5 class="card-title">CONTINUOUS INTEGRATION - JENKINS</h5>
              <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item p-0">What is Jenkins?</li>
                  <li class="list-group-item p-0">Continuous Integration with Jenkins</li>
                  <li class="list-group-item p-0">Java installation and configuration</li>
                  <li class="list-group-item p-0">Exploring Jenkins Dashboard</li>
                  <li class="list-group-item p-0">Creating jobs in Jenkins</li>
                  <li class="list-group-item p-0">Running the Jobs</li>
                  <li class="list-group-item p-0">Setting up the global environment variables for Jobs</li>
                  <li class="list-group-item p-0">Adding and updating Plugins</li>
                  <li class="list-group-item p-0">Disabling and deleting jobs</li>
                  <li class="list-group-item p-0">Different authorization strategies in Jenkins</li>
                  <li class="list-group-item p-0">RBAC strategy in Jenkins</li>
                  <li class="list-group-item p-0">Best Practices for Jenkins</li>
                  <li class="list-group-item p-0">Plugin Management in Jenkins</li>
                  <li class="list-group-item p-0">Triggering email notifications in Jenkins</li>
                  <li class="list-group-item p-0">Scheduling jobs automatically in Jenkins</li>
                  <li class="list-group-item p-0">Poll SCM and web hooks in Jenkins</li>
                  <li class="list-group-item p-0">Compile, test and deploy jobs in Jenkins</li>
                  <li class="list-group-item p-0">Building Delivery Pipeline in Jenkins with java Maven Project</li>
                  <li class="list-group-item p-0">Create complete pipeline in Jenkins</li>
                  <li class="list-group-item p-0">Master Slave Architecture in Jenkins</li>
                  <li class="list-group-item p-0">Credentials in Jenkins</li>
                  <li class="list-group-item p-0">Adding Windows slave and run test job on windows</li>
                  <li class="list-group-item p-0">Adding Linux slave and configuring the job on Linux ec2 instance</li>
                  <li class="list-group-item p-0">Pipeline and Multi branch jobs in Jenkins</li>
                  <li class="list-group-item p-0">Pipeline as code in Jenkins (Jenkins file) using groovy script</li>
                  <li class="list-group-item p-0">Deploy to ec2-instance on AWS using Jenkins Pipeline</li>
                </ul>
              </p>              
            </div>
          </div>
        </div>
      </div>
    </div>
</template>

<script>
export default {
  props: ['page']
}    
</script>
