<template>
  <div class="header-header" v-bind:class="rootClassName"
    ><header
      data-thq="thq-navbar"
      class="navbarContainer header-navbar-interactive"
      ><router-link to="/" class="header-logo TaxOnUs">{{ logo }}</router-link
      ><div data-thq="thq-navbar-nav" class="header-desktop-menu"
        ><nav class="header-links"
          ><router-link to="/" class="header-nav12 bodySmall"
            >{{ nav12 }}</router-link
          ><router-link to="/about" class="header-nav22 bodySmall"
            >{{ nav22 }}</router-link
          ><router-link to="/tax-services" class="header-nav32"
            >{{ nav32 }}</router-link
          ><router-link to="/accounting-services" class="header-nav42 bodySmall"
            >{{ nav42 }}</router-link
          ><router-link to="/contact" class="header-nav52 bodySmall"
            >{{ nav52 }}</router-link
          ></nav
        ><div class="header-buttons"
          ><button class="header-login buttonFlat">{{ login }}</button
          ><button class="buttonFilled">{{ register }}</button></div
        ></div
      ><div data-thq="thq-burger-menu" class="header-burger-menu"
        ><animate-on-reveal
          ><svg
            viewBox="0 0 1024 1024"
            data-thq-animate-on-reveal="true"
            class="socialIcons header-icon"
          >
            <path
              d="M128 554.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 298.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667zM128 810.667h768c23.552 0 42.667-19.115 42.667-42.667s-19.115-42.667-42.667-42.667h-768c-23.552 0-42.667 19.115-42.667 42.667s19.115 42.667 42.667 42.667z"
            ></path></svg></animate-on-reveal></div
      ><div data-thq="thq-mobile-menu" class="header-mobile-menu1 mobileMenu"
        ><div class="header-nav"
          ><div class="header-top"
            ><span class="TaxOnUs">{{ logo1 }}</span
            ><div data-thq="thq-close-menu" class="header-close-menu"
              ><svg viewBox="0 0 1024 1024" class="header-icon02 socialIcons">
                <path
                  d="M810 274l-238 238 238 238-60 60-238-238-238 238-60-60 238-238-238-238 60-60 238 238 238-238z"
                ></path></svg></div></div
          ><nav class="header-links1"
            ><router-link to="/" class="header-nav121 bodySmall"
              >{{ nav121 }}</router-link
            ><router-link to="/about" class="header-nav221 bodySmall"
              >{{ nav221 }}</router-link
            ><router-link to="/tax-services" class="header-nav321 bodySmall"
              >{{ nav321 }}</router-link
            ><router-link
              to="/accounting-services"
              class="header-nav421 bodySmall"
              >{{ nav421 }}</router-link
            ><router-link to="/contact" class="header-nav521 bodySmall"
              >{{ nav521 }}</router-link
            ></nav
          ><div class="header-buttons1"
            ><button class="buttonFlat">{{ login1 }}</button
            ><button class="buttonFilled">{{ register1 }}</button></div
          ></div
        ><div
          ><svg
            viewBox="0 0 950.8571428571428 1024"
            class="header-icon04 socialIcons"
          >
            <path
              d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
            ></path></svg
          ><svg
            viewBox="0 0 877.7142857142857 1024"
            class="header-icon06 socialIcons"
          >
            <path
              d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
            ></path></svg
          ><svg
            viewBox="0 0 602.2582857142856 1024"
            class="header-icon08 socialIcons"
          >
            <path
              d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
            ></path></svg></div></div></header
  ></div>
</template>

<script>
export default {
  name: 'Header',
  props: {
    rootClassName: String,
    register1: {
      type: String,
      default: 'Register',
    },
    login1: {
      type: String,
      default: 'Login',
    },
    nav521: {
      type: String,
      default: 'Contact Us',
    },
    nav421: {
      type: String,
      default: 'Accounting Services',
    },
    nav321: {
      type: String,
      default: 'Tax Services',
    },
    nav221: {
      type: String,
      default: 'About Us',
    },
    nav121: {
      type: String,
      default: 'Home',
    },
    logo1: {
      type: String,
      default: 'TAXONUS',
    },
    register: {
      type: String,
      default: 'Register',
    },
    login: {
      type: String,
      default: 'Login',
    },
    nav52: {
      type: String,
      default: 'Contact Us',
    },
    nav42: {
      type: String,
      default: 'Accounting Services',
    },
    nav32: {
      type: String,
      default: 'Tax Services',
    },
    nav22: {
      type: String,
      default: 'About Us',
    },
    nav12: {
      type: String,
      default: 'Home',
    },
    logo: {
      type: String,
      default: 'Taxonus',
    },
  },
}
</script>

<style scoped>
.header-header {
  width: 100%;
  display: flex;
  z-index: 100;
  position: fixed;
  align-items: center;
  flex-direction: column;
  background-color: var(--dl-color-gray-white);
}
.header-logo {
  text-decoration: none;
}
.header-desktop-menu {
  flex: 1;
  display: flex;
  justify-content: space-between;
}
.header-links {
  flex: 1;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: center;
}
.header-nav12 {
  margin-left: 0px;
  border-color: var(--dl-color-gray-white);
  border-width: 1px;
  padding-left: 2%;
  padding-right: 2%;
  text-decoration: none;
  border-top-width: 0px;
  border-left-width: 0px;
  border-bottom-width: 0px;
}
.header-nav22 {
  margin-left: 0px;
  border-color: var(--dl-color-gray-white);
  padding-left: 2%;
  padding-right: 2%;
  text-decoration: none;
  border-top-width: 0px;
  border-left-width: 0px;
  border-right-width: 1px;
  border-bottom-width: 0px;
}
.header-nav32 {
  margin-left: 0px;
  border-color: var(--dl-color-gray-white);
  padding-left: 2%;
  padding-right: 2%;
  text-decoration: none;
  border-top-width: 0px;
  border-left-width: 0px;
  border-right-width: 1px;
  border-bottom-width: 0px;
}
.header-nav42 {
  margin-left: 0px;
  border-color: var(--dl-color-gray-white);
  padding-left: 2%;
  padding-right: 2%;
  text-decoration: none;
  border-top-width: 0px;
  border-left-width: 0px;
  border-right-width: 1px;
  border-bottom-width: 0px;
}
.header-nav52 {
  margin-left: 0px;
  padding-left: 2%;
  padding-right: 2%;
  text-decoration: none;
}
.header-buttons {
  display: none;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.header-login {
  margin-right: 32px;
}
.header-burger-menu {
  display: none;
}
.header-mobile-menu1 {
  top: 0px;
  left: 0px;
  width: 100%;
  height: 100vh;
  display: flex;
  padding: 32px;
  z-index: 100;
  position: absolute;
  transform: translateX(-100%);
  transition: 0.5s;
  flex-direction: column;
  justify-content: space-between;
}
.header-nav {
  display: flex;
  align-items: flex-start;
  flex-direction: column;
}
.header-top {
  width: 100%;
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-threeunits);
  justify-content: space-between;
}
.header-close-menu {
  display: flex;
  align-items: center;
  justify-content: center;
}
.header-icon02 {
  width: var(--dl-size-size-xsmall);
  cursor: pointer;
  height: var(--dl-size-size-xsmall);
}
.header-links1 {
  flex: 0 0 auto;
  display: flex;
  align-self: flex-start;
  align-items: flex-start;
  flex-direction: column;
}
.header-nav121 {
  transition: 0.3s;
  margin-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.header-nav121:hover {
  cursor: pointer;
}
.header-nav221 {
  margin-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.header-nav221:hover {
  cursor: pointer;
}
.header-nav321 {
  margin-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.header-nav321:hover {
  cursor: pointer;
}
.header-nav421 {
  margin-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.header-nav421:hover {
  cursor: pointer;
}
.header-nav521 {
  margin-bottom: var(--dl-space-space-unit);
  text-decoration: none;
}
.header-nav521:hover {
  cursor: pointer;
}
.header-buttons1 {
  display: none;
  margin-top: var(--dl-space-space-unit);
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.header-icon04 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.header-icon06 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
  margin-right: var(--dl-space-space-twounits);
}
.header-icon08 {
  width: var(--dl-size-size-xsmall);
  height: var(--dl-size-size-xsmall);
}




@media(max-width: 767px) {
  .header-navbar-interactive {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .header-burger-menu {
    align-items: center;
    justify-content: center;
  }
  .header-nav121 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .header-nav221 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .header-nav321 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .header-nav421 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .header-nav521 {
    margin-bottom: var(--dl-space-space-unit);
  }
}
@media(max-width: 479px) {
  .header-navbar-interactive {
    height: 99px;
    padding: var(--dl-space-space-unit);
    z-index: auto;
    border-color: var(--dl-color-gray-black);
    border-width: 1px;
    margin-bottom: 0px;
    padding-right: 16px;
  }
  .header-desktop-menu {
    display: none;
  }
  .header-burger-menu {
    display: flex;
    flex-direction: column;
  }
  .header-icon {
    z-index: inherit;
  }
  .header-mobile-menu1 {
    padding: 16px;
  }
  .header-buttons1 {
    display: none;
  }
  .header-root-class-name {
    fill: var(--dl-color-gray-black);
    color: var(--dl-color-gray-black);
  }
}
</style>
