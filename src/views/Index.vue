<template>
  <div class="wrapper">
    <parallax class="page-header header-filter" :style="headerStyle">
      <div class="md-layout">
        <div class="md-layout-item">
          <div class="image-wrapper">
            
            <div class="brand">
              <h1>Exposiciones Equinas</h1>
              <h3>Popayán Cauca</h3>
            </div>
          </div>
        </div>
      </div>
    </parallax>
    <div class="main main-raised md-layout md-gutter" classs="masonry-container" >
<!-- Comment --> 
         <div class="md-layout-item md-size-25 md-xsmall-size-100 md-small-size-50 md-medium-size-25">
                <div class="card text-center" data-background="image"   >
                    <h4 class="title title-modern">Hipster Vacation</h4>
                                        <div class="content">
                        <div class="price">
                            <h6>From</h6>
                            <h4>2.799<b class="currency">$</b></h4>
                        </div>
                        <p class="description">When selling products it's always a good idea to go with commanding fonts that are good at showing authority and security.</p>
                    </div>
                    <div class="filter"></div>
                    <div class="footer btn-center">
                        <button class="btn btn-neutral btn-round btn-fill">Book Now!</button>
                    </div>
                </div> <!-- end card -->
            </div>

<!-- Comment -->
<!-- tarjeta 2 -->
        <div class="md-layout-item md-size-25 md-xsmall-size-100 md-small-size-50 md-medium-size-25">
                <div class="card text-center" data-background="image"  data-src="@/assets/img/examples/studio-1.jpg" >
                    <h4 class="title title-modern">Hipster Vacation</h4>
                                        <div class="content">
                        <div class="price">
                            <h6>From</h6>
                            <h4>2.799<b class="currency">$</b></h4>
                        </div>
                        <p class="description">When selling products it's always a good idea to go with commanding fonts that are good at showing authority and security.</p>
                    </div>
                    <div class="filter"></div>
                    <div class="footer btn-center">
                        <button class="btn btn-neutral btn-round btn-fill">Book Now!</button>
                    </div>
                </div> <!-- end card -->
            </div>

<!-- fin tarjeta 2 --> 

<!-- tarjeta 2 -->
        <div class="md-layout-item md-size-25 md-xsmall-size-100 md-small-size-50 md-medium-size-25">
                <div class="card text-center" data-background="image"  data-src="@/assets/img/examples/studio-1.jpg" style="background-color:red">
                    <h4 class="title title-modern">Hipster Vacation</h4>
                                        <div class="content">
                        <div class="price">
                            <h6>From</h6>
                            <h4>2.799<b class="currency">$</b></h4>
                        </div>
                        <p class="description">When selling products it's always a good idea to go with commanding fonts that are good at showing authority and security.</p>
                    </div>
                    <div class="filter"></div>
                    <div class="footer btn-center">
                        <button class="btn btn-neutral btn-round btn-fill">Book Now!</button>
                    </div>
                </div> <!-- end card -->
            </div>

<!-- fin tarjeta 2 --> 

<!-- tarjeta 2 -->
        <div class="md-layout-item md-size-25 md-xsmall-size-100 md-small-size-50 md-medium-size-25">
                <div class="card text-center" data-background="image"  data-src="@/assets/img/examples/studio-1.jpg" >
                    <h4 class="title title-modern">Hipster Vacation</h4>
                                        <div class="content">
                        <div class="price">
                            <h6>From</h6>
                            <h4>2.799<b class="currency">$</b></h4>
                        </div>
                        <p class="description">When selling products it's always a good idea to go with commanding fonts that are good at showing authority and security.</p>
                    </div>
                    <div class="filter"></div>
                    <div class="footer btn-center">
                        <button class="btn btn-neutral btn-round btn-fill">Book Now!</button>
                    </div>
                </div> <!-- end card -->
            </div>

<!-- fin tarjeta 2 --> 

<!-- tarjeta 2 -->
        <div class="md-layout-item md-size-25 md-xsmall-size-100 md-small-size-50 md-medium-size-25">
                <div class="card text-center" data-background="image"  data-src="@/assets/img/examples/studio-1.jpg" >
                    <h4 class="title title-modern">Hipster Vacation</h4>
                                        <div class="content">
                        <div class="price">
                            <h6>From</h6>
                            <h4>2.799<b class="currency">$</b></h4>
                        </div>
                        <p class="description">When selling products it's always a good idea to go with commanding fonts that are good at showing authority and security.</p>
                    </div>
                    <div class="filter"></div>
                    <div class="footer btn-center">
                        <button class="btn btn-neutral btn-round btn-fill">Book Now!</button>
                    </div>
                </div> <!-- end card -->
            </div>

<!-- fin tarjeta 2 --> 

    </div>
  </div>
</template>

<script>
import BasicElements from "./components/BasicElementsSection";
import Navigation from "./components/NavigationSection";
import SmallNavigation from "./components/SmallNavigationSection";
import Tabs from "./components/TabsSection";
import NavPills from "./components/NavPillsSection";
import Notifications from "./components/NotificationsSection";
import TypographyImages from "./components/TypographyImagesSection";
import JavascriptComponents from "./components/JavascriptComponentsSection";
import { LoginCard } from "@/components";

export default {
  components: {
    BasicElements,
    Navigation,
    SmallNavigation,
    Tabs,
    NavPills,
    Notifications,
    TypographyImages,
    JavascriptComponents,
    LoginCard
  },
  name: "index",
  bodyClass: "index-page",
  props: {
    image: {
      type: String,
      default: require("@/assets/img/bg_horse4.jpg")
    },
    leaf4: {
      type: String,
      default: require("@/assets/img/leaf4.png")
    },
    leaf3: {
      type: String,
      default: require("@/assets/img/leaf3.png")
    },
    leaf2: {
      type: String,
      default: require("@/assets/img/leaf2.png")
    },
    leaf1: {
      type: String,
      default: require("@/assets/img/leaf1.png")
    },
    signup: {
      type: String,
      default: require("@/assets/img/city.jpg")
    },
    landing: {
      type: String,
      default: require("@/assets/img/landing.jpg")
    },
    profile: {
      type: String,
      default: require("@/assets/img/profile.jpg")
    }
  },
  data() {
    return {
      tabPane1: [
        { image: require("@/assets/img/examples/studio-1.jpg") }
      ],
      firstname: null,
      email: null,
      password: null,
      leafShow: false
    };
  },
  methods: {
    leafActive() {
      if (window.innerWidth < 768) {
        this.leafShow = false;
      } else {
        this.leafShow = true;
      }
    }
  },
  computed: {
    headerStyle() {
      return {
        backgroundImage: `url(${this.image})`
      };
    },
    signupImage() {
      return {
        backgroundImage: `url(${this.signup})`
      };
    }
  },
  mounted() {
    this.leafActive();
    window.addEventListener("resize", this.leafActive);
  },
  beforeDestroy() {
    window.removeEventListener("resize", this.leafActive);
  }
};
</script>
<style lang="scss">



.section-download {
  .md-button + .md-button {
    margin-left: 5px;
  }
}

@media all and (min-width: 991px) {
  .btn-container {
    display: flex;
  }
}
</style>




