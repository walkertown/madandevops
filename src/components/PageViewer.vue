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

    <div class="container d-flex mt-4 p-4">
      <div class="card mb-3" style="max-width:540px;">
      <div class="row g-0">
        <div class="col-md-6">
          <img src="devops.png" class="img-fluid rounded-start" alt="...">
        </div>
        <div class="col-md-6">
          <div class="card-body">
            <h5 class="card-title">
              INTRODUCTION TO DEVOPS
            </h5>
            <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item">What is Devops?</li>
                  <li class="list-group-item">Why Devops?</li>
                  <li class="list-group-item">Devops Tools</li>
                  <li class="list-group-item">Differences between traditional methodologies and DEVOPS-approach</li>
                  <li class="list-group-item">Big Picture of CI/CD Devops Delivery Pipeline</li>
                </ul>
            </p>            
          </div>
        </div>
      </div>
    </div>
      <div class="card mb-3" style="max-width:540px;">
        <div class="row g-0">
          <div class="col-md-6">
            <img src="linux.png"
              class="img-fluid rounded-start" alt="...">
          </div>
          <div class="col-md-6">
            <div class="card-body">
              <h5 class="card-title">OPERATING SYSTEM & LINUX BASICS</h5>
              <p class="card-text">
                <ul class="list-group list-group-flush">
                  <li class="list-group-item">Introduction to Operating Systems</li>
                  <li class="list-group-item">Introduction to Virtual Machines</li>
                  <li class="list-group-item">Linux File Systems</li>
                  <li class="list-group-item">Introduction to Command Line Interface</li>
                  <li class="list-group-item">Basic Linux Commands</li>
                  <li class="list-group-item">Package Manager - Installing Software in Linux</li>
                  <li class="list-group-item">Vim Text Editor</li>
                  <li class="list-group-item">Users and Permissions</li>
                  <li class="list-group-item">Shell Scripting</li>
                  <li class="list-group-item">Environment Variables</li>
                  <li class="list-group-item">SSH -Secure Shell</li>
                </ul>
              </p>              
            </div>
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
