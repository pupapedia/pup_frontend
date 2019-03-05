<template>
    <div>

        <div class="position-relative">
            <!-- shape Hero -->
            <section class="section-shaped my-0">
                <div class="shape shape-style-1 shape-default shape-skew">
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                    <span></span>
                </div>
                <div class="container shape-container d-flex">
                    <div class="col px-0">
                        <div class="row text-center">
                            <div class="col-lg-12">
                                <h1 class="display-3  text-gray">Find your Furry Friend!
                                </h1>
                                <div>
                                    <base-input alternative placeholder="Start typing to search..."></base-input>
                                    <base-button tag="a"
                                                 href="https://demos.creative-tim.com/argon-design-system/docs/components/alerts.html"
                                                 class="mb-6 mb-sm-0"
                                                 type="info"
                                                 icon="fa fa-search">
                                        Search
                                    </base-button>
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </section>
            <!-- 1st Hero Variation -->
        </div>
        <section class="section section-lg pt-lg-0 mt--200">
            <div class="container">
                <div class="row justify-content-center">
                    <div class="col-lg-12">
                        <div class="row row-grid">
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <h6 class="text-primary text-uppercase text-center">Post your Puppy</h6>
                                    <p class="description mt-3">
                                        Post and share your puppy and help find a new loving home
                                        
                                    </p>
                                    <small>
<ul class="list-unstyled">
    <li>
      <ul>
        <li>Share to Facebook, Twitter, etc</li>
        <li>Tracking and Analytics</li>
      </ul>
    </li>

</ul>
</small>
                                    <base-button tag="a" href="#" type="primary" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <h6 class="text-success text-uppercase">Registered Breeder</h6>
                                    <p class="description mt-3">Submit Health Certifications to be processed as a Registered Breeder so buyers know the Puppy is being raised in a happy and healthy environment</p>
                                    <base-button tag="a" href="#" type="success" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                            <div class="col-lg-4">
                                <card class="border-0" hover shadow body-classes="py-5">
                                    <h6 class="text-warning text-uppercase">Service 3</h6>
                                    <p class="description mt-3">another service with its description here dfasdf</p>
                                    <base-button tag="a" href="#" type="warning" class="mt-4">
                                        Learn more
                                    </base-button>
                                </card>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg">
            <div class="container">
                <div class="row row-grid align-items-center">
                    <div class="col-md-6 order-md-2">
                        <img src="img/theme/promo-1.png" class="img-fluid floating">
                    </div>
                    <div class="col-md-6 order-md-1">
                        <div class="pr-md-5">
                            <icon name="ni ni-settings-gear-65" class="mb-5" size="lg" type="success" shadow
                                  rounded></icon>
                            <h3>Pupapedia's Mission</h3>
                            <p>Here at Pupapedia; We aim to mitigate fraud and immature breeding habits through supporting known, reputable breeders and to help find introduce a new furry friend into your home and hearts!</p>
                            <ul class="list-unstyled mt-5">
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-settings-gear-65"></badge>
                                        <h6 class="mb-0">Carefully crafted components</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-html5"></badge>
                                        <h6 class="mb-0">Amazing page examples</h6>
                                    </div>
                                </li>
                                <li class="py-2">
                                    <div class="d-flex align-items-center">
                                        <badge type="success" circle class="mr-3" icon="ni ni-satisfied"></badge>
                                        <h6 class="mb-0">Super friendly support team</h6>
                                    </div>
                                </li>
                            </ul>
                        </div>
                    </div>
                </div>
            </div>
        </section>
        <section class="section section-lg pt-0">
            <div class="container">
                <card gradient="primary"
                      no-body
                      shadow-size="lg"
                      class="border-0">
                    <div class="p-5">
                        <div class="row align-items-center">
                            <div class="col-lg-8">
                                <h3 class="text-white">Want to post a puppy up for adoption?</h3>
                                <p class="lead text-white mt-3">We'll help guide you through the process, and aim to pair your puppy to the most lovable family possible!</p>
                            </div>
                            <div class="col-lg-3 ml-lg-auto">
                                <base-button tag="a" href="https://www.creative-tim.com/product/vue-argon-design-system"
                                             type="white" block size="lg">
                                    Get Started!
                                </base-button>
                            </div>
                        </div>
                    </div>
                </card>
            </div>
        </section>


    </div>
</template>

<script>
import BaseDropdown from "../components/BaseDropdown";

export default {
  name: "home",
  components: {
    BaseDropdown
  }
};
</script>
