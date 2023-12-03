<template>
    <!-- <div class="container">
        <h1>{{ page.pageTitle }}</h1>
        <p>{{ page.content }}</p>
    </div> -->

    <div class="container-fluid mt-3">
        <div class="row">
            <div class="col p-6 bg-primary text-white">
                <span class="badge rounded-pill bg-primary" style="font-size: larger;">RAM IT <br /> DevOps
                    Instructor</span>
            </div>
            <div class="col p-3 bg-primary text-white">
                <span class="badge rounded-pill bg-primary  float-end" style="font-size: larger;">WhatsApp
                    +9999988888</span>
            </div>
        </div>
    </div>
    <br />
    <div class="row">
        <div class="col p-3 bg-white text-white"></div>
        <div class="col p-3 bg-success text-white rounded text-center">
            <span class="badge rounded-pill bg-success " style="font-size: larger;">
                DevOps New Batch <br />
                December 9th (Thrusday) <br />
                7:00 PM to 8:30 PM IST
            </span>
        </div>
        <div class="col p-3 bg-white text-white"></div>
    </div>
</template>

<script>
export default {
    props: ['page']
}    
</script>