<template>
  <div class="home-container"
    ><app-header rootClassName="header-root-class-name"></app-header
    ><div class="home-hero"
      ><div class="heroContainer home-hero1"
        ><div class="home-container1"
          ><h1 class="home-hero-heading heading1">Minimize Your Tax Liability</h1
          ><div class="home-btn-group"
            ><router-link
              to="/tax-services"
              class="home-hero-button1 buttonFilled"
              >Get Started Now</router-link
            ><router-link to="/about" class="home-hero-button2 buttonFlat"
              >Learn More →</router-link
            ></div
          ></div
        ></div
      ></div
    ><div class="home-features"
      ><div class="featuresContainer"
        ><div class="home-features1"
          ><div class="home-container2"
            ><h2 class="home-features-heading heading2">Our Tax Services</h2></div
          ><div class="home-container3"
            ><feature-card
              heading="Tax Clearance"
              subHeading="Support and assistance for your tax audit and matters."
            ></feature-card
            ><feature-card
              heading="Confidentiality "
              subHeading="Guarantees confidentiality of data and Tax information."
            ></feature-card
            ><feature-card
              heading="Responsibility"
              subHeading="Onus is on us in maximizing your tax savings."
            ></feature-card
            ><feature-card
              heading="Commitment"
              subHeading="for being a partner in fulfilling your tax obligation."
              rootClassName="feature-card-root-class-name"
            ></feature-card></div></div></div></div
    ><div class="home-banner"
      ><div class="bannerContainer home-banner1"
        ><div class="home-container4"
          ><h1 class="home-banner-heading">TYPES OF TAXES</h1
          ><div class="home-container5"
            ><ul class="list"
              ><li class="list-item"
                ><span class="home-tick">✔</span
                ><span>Pay As You Earn (PAYE)</span></li
              ><li class="list-item"
                ><span class="home-tick01">✔</span
                ><span>Value Added Tax (VAT)</span></li
              ><li class="list-item"
                ><span class="home-tick02">✔</span
                ><span>Simplified Value Added Tax (SVAT) Scheme</span></li
              ><li class="list-item"
                ><span class="home-tick03">✔</span
                ><span
                  ><span>Social Security Contribution Levy (SSCL)</span
                  ><br /></span></li
              ><li class="list-item"
                ><span class="home-tick04">✔</span
                ><span><span>Economic Service Charge (ESC)</span><br /></span></li
              ><li class="list-item"
                ><span class="home-tick05">✔</span
                ><span>Construction Industry Guarantee Fund Levy (CIGF)</span></li
              ></ul
            ><ul class="list"
              ><li class="list-item"
                ><span class="home-tick06">✔</span
                ><span>Capital Gain Tax (CGT)</span></li
              ><li class="list-item"
                ><span class="home-tick07">✔</span
                ><span>Stamp Duty (SD)</span></li
              ><li class="list-item"
                ><span class="home-tick08">✔</span
                ><span>Betting and Gaming Levy (B&amp;GL)</span></li
              ><li class="list-item"
                ><span class="home-tick09">✔</span
                ><span><span>Share Transaction Levy (STL)</span><br /></span></li
              ><li class="list-item"
                ><span class="home-tick10">✔</span
                ><span>Tourist VAT Refund Scheme (TVRS)</span></li
              ><li class="list-item"
                ><span class="home-tick11">✔</span
                ><span>Nation Building Tax (NBT) </span></li
              ></ul
            ></div
          ></div
        ></div
      ></div
    ><div class="home-faq"
      ><div class="faqContainer"
        ><div class="home-faq1"
          ><div class="home-container6"
            ><span class="overline"><span>FAQ</span><br /></span
            ><h2 class="home-text21 heading2">Common questions</h2
            ><span class="home-text22 bodyLarge"
              ><span>Here are some of the most common questions that we get.</span
              ><br /></span></div
          ><div class="home-container7"></div></div></div></div
    ><app-footer></app-footer
  ></div>
</template>

<script>
import AppHeader from '../components/header'
import FeatureCard from '../components/feature-card'
import AppFooter from '../components/footer'

export default {
  name: 'Home',
  props: {},
  components: {
    AppHeader,
    FeatureCard,
    AppFooter,
  },
  metaInfo: {
    title: 'taxonus',
    meta: [
      {
        property: 'og:title',
        content: 'taxonus',
      },
    ],
  },
}
</script>

<style scoped>
.home-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.home-hero {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  margin-top: 96px;
  align-items: flex-start;
  justify-content: center;
}
.home-container1 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.home-hero-heading {
  max-width: 800px;
  text-align: center;
}
.home-btn-group {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: center;
  flex-direction: row;
}
.home-hero-button1 {
  text-decoration: none;
}
.home-hero-button2 {
  text-decoration: none;
}
.home-features {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-features1 {
  gap: var(--dl-space-space-threeunits);
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: column;
  padding-bottom: var(--dl-space-space-fourunits);
  justify-content: flex-start;
}
.home-container2 {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.home-features-heading {
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-container3 {
  width: 100%;
  display: grid;
  grid-gap: var(--dl-space-space-oneandhalfunits);
  position: relative;
  grid-template-columns: 1fr 1fr;
}
.home-banner {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-container4 {
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: center;
}
.home-banner-heading {
  text-align: center;
}
.home-container5 {
  display: flex;
  align-items: flex-start;
  flex-direction: row;
  justify-content: center;
}
.home-tick {
  line-height: 150%;
}
.home-tick01 {
  line-height: 150%;
}
.home-tick02 {
  line-height: 150%;
}
.home-tick03 {
  line-height: 150%;
}
.home-tick04 {
  line-height: 150%;
}
.home-tick05 {
  line-height: 150%;
}
.home-tick06 {
  line-height: 150%;
}
.home-tick07 {
  line-height: 150%;
}
.home-tick08 {
  line-height: 150%;
}
.home-tick09 {
  line-height: 150%;
}
.home-tick10 {
  line-height: 150%;
}
.home-tick11 {
  line-height: 150%;
}
.home-faq {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.home-faq1 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: flex-start;
  padding-top: var(--dl-space-space-fourunits);
  padding-left: var(--dl-space-space-threeunits);
  padding-right: var(--dl-space-space-threeunits);
  flex-direction: row;
  padding-bottom: var(--dl-space-space-fourunits);
}
.home-container6 {
  display: flex;
  max-width: 35%;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.home-text21 {
  margin-bottom: var(--dl-space-space-oneandhalfunits);
}
.home-text22 {
  text-align: left;
}
.home-container7 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
@media(max-width: 991px) {
  .home-hero1 {
    flex-direction: column;
  }
  .home-container1 {
    align-items: center;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
    padding-right: 0px;
  }
  .home-hero-heading {
    text-align: center;
  }
  .home-text22 {
    text-align: center;
    padding-left: var(--dl-space-space-threeunits);
    padding-right: var(--dl-space-space-threeunits);
  }
}
@media(max-width: 767px) {
  .home-hero1 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-features1 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-container3 {
    grid-template-columns: 1fr;
  }
  .home-banner1 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .home-faq1 {
    flex-direction: column;
  }
  .home-container6 {
    max-width: 100%;
    align-self: center;
    align-items: center;
    justify-content: center;
  }
  .home-text22 {
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
  }
}
@media(max-width: 479px) {
  .home-hero1 {
    height: 408px;
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-container1 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .home-btn-group {
    flex-direction: column;
  }
  .home-features1 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .home-banner1 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
}
</style>
