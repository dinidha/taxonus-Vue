<template>
  <div class="accounting-services-container"
    ><app-header rootClassName="header-root-class-name1"></app-header
    ><div class="accounting-services-hero"
      ><div class="heroContainer accounting-services-hero1"
        ><div class="accounting-services-container01"
          ><h1 class="accounting-services-hero-heading heading1"
            >Choose the right plan for you </h1
          ></div
        ></div
      ></div
    ><div class="accounting-services-pricing"
      ><div class="accounting-services-pricing1"
        ><div class="pricingContainer"
          ><div class="accounting-services-container02"
            ><div class="freePricingCard accounting-services-pricing-card"
              ><div class="accounting-services-container03"
                ><span class="accounting-services-text heading3"
                  >Small business</span
                ><span
                  ><span class="bodySmall">(up to 120 transactions/month)</span
                  ><br /><br /></span></div
              ><div class="accounting-services-container04"
                ><span class="accounting-services-text004">LKR</span
                ><span class="accounting-services-free-plan-price">28,500</span
                ><span class="accounting-services-text005">/ month</span></div
              ><div class="accounting-services-feature-container"
                ><div class="accounting-services-feature"
                  ><h1 class="accounting-services-text006"
                    >Account reconciliation</h1
                  ><div class="accounting-services-sub-feature"
                    ><span class="accounting-services-text007">✔</span
                    ><span>Bank accounts up to 3 </span></div
                  ><div class="accounting-services-sub-feature01"
                    ><span class="accounting-services-text008">✔</span
                    ><span
                      >Credit card accounts up to 3
                      <span v-html="rawzeud"></span></span></div
                  ><div class="accounting-services-sub-feature02"
                    ><span class="accounting-services-text009">✔</span
                    ><span
                      >Reconcile electronic transactions into an Accounting
                      Package <span v-html="rawefv3"></span></span></div
                  ><span class="accounting-services-text010">LKR 9000</span></div
                ><div class="accounting-services-feature01"
                  ><h1 class="accounting-services-text011">Monthly financials</h1
                  ><div class="accounting-services-sub-feature03"
                    ><span class="accounting-services-text012">✔</span
                    ><span>Balance Sheet</span></div
                  ><div class="accounting-services-sub-feature04"
                    ><span class="accounting-services-text013">✔</span
                    ><span
                      ><span
                        >Profit &amp; Loss <span v-html="rawh3q4"></span></span
                      ><br /><span>
                        <span v-html="rawhk38"></span></span></span></div
                  ><div class="accounting-services-sub-feature05"
                    ><span class="accounting-services-text017">✔</span
                    ><span
                      ><span>General Ledger <span v-html="raw4fo2"></span></span
                      ><br /><span>
                        <span v-html="raw96si"></span></span></span></div
                  ><div class="accounting-services-sub-feature06"
                    ><span class="accounting-services-text021">✔</span
                    ><span
                      ><span>Statement of Cash Flows</span><br /><span>
                        <span v-html="raw8s28"></span></span></span></div
                  ><span class="accounting-services-text025"
                    ><span>LKR 8000</span><br /></span></div
                ><div class="accounting-services-feature02"
                  ><h1 class="accounting-services-text028"
                    >Stock Records <span v-html="rawtbk6"></span></h1
                  ><div class="accounting-services-sub-feature07"
                    ><span class="accounting-services-text029">✔</span
                    ><span>Stock report up to 20 items</span></div
                  ><span class="accounting-services-text030">LKR 2500</span></div
                ><div class="accounting-services-feature03"
                  ><h1 class="accounting-services-text031"
                    >Employee Funds <span v-html="rawj9r0"></span></h1
                  ><div class="accounting-services-sub-feature08"
                    ><span class="accounting-services-text032">✔</span
                    ><span>EPF &amp; ETF returns up to 5 Emps</span></div
                  ><div class="accounting-services-sub-feature09"
                    ><span class="accounting-services-text033">✔</span
                    ><span
                      >Annual return <span v-html="rawzqj1"></span></span></div
                  ><span class="accounting-services-text034">LKR 2500</span></div
                ><div class="accounting-services-feature04"
                  ><h1 class="accounting-services-text035"
                    >Advice <span v-html="raw9mnm"></span></h1
                  ><div class="accounting-services-sub-feature10"
                    ><span class="accounting-services-text036">✔</span
                    ><span
                      >Accountant and business service meeting up to an hour</span
                    ></div
                  ><span class="accounting-services-text037">LKR 2000</span></div
                ><div class="accounting-services-feature05"
                  ><h1 class="accounting-services-text038"
                    >Software and portals</h1
                  ><div class="accounting-services-sub-feature11"
                    ><span class="accounting-services-text039">✔</span
                    ><span
                      >Essential document storage
                      <span v-html="rawzzq3"></span></span></div
                  ><div class="accounting-services-sub-feature12"
                    ><span class="accounting-services-text040">✔</span
                    ><span
                      >Accounting software setup &amp; maintenance
                      <span v-html="raw6h2q"></span></span></div
                  ><div class="accounting-services-sub-feature13"
                    ><span class="accounting-services-text041">✔</span
                    ><span
                      ><span
                        >Expense management with one criterion
                        <span v-html="raw0wdw"></span></span
                      ><br /><br /><span>
                        <span v-html="raw0r4w"></span></span></span></div
                  ><span class="accounting-services-text046">LKR 4500</span></div
                ></div
              ><button class="accounting-services-button buttonOutline"
                >Continue with Free</button
              ></div
            ><div class="freePricingCard accounting-services-pricing-card1"
              ><div class="accounting-services-container05"
                ><span class="accounting-services-text047 heading3"
                  >Small business plus</span
                ><span
                  ><span class="bodySmall"
                    >(up to 125-240 transactions/month)</span
                  ><br /><br /></span></div
              ><div class="accounting-services-container06"
                ><span class="accounting-services-text051">LKR</span
                ><span class="accounting-services-free-plan-price1">28,500</span
                ><span class="accounting-services-text052">/ month</span></div
              ><div class="accounting-services-feature-container1"
                ><div class="accounting-services-feature06"
                  ><h1 class="accounting-services-text053"
                    >Account reconciliation</h1
                  ><div class="accounting-services-sub-feature14"
                    ><span class="accounting-services-text054">✔</span
                    ><span>Bank accounts up to 5</span></div
                  ><div class="accounting-services-sub-feature15"
                    ><span class="accounting-services-text055">✔</span
                    ><span
                      >Credit card accounts up to 5
                      <span v-html="rawmy0b"></span></span></div
                  ><div class="accounting-services-sub-feature16"
                    ><span class="accounting-services-text056">✔</span
                    ><span
                      >Reconcile electronic transactions into an Accounting
                      Package <span v-html="rawlnm8"></span></span></div
                  ><span class="accounting-services-text057">LKR 12000</span></div
                ><div class="accounting-services-feature07"
                  ><h1 class="accounting-services-text058">Monthly financials</h1
                  ><div class="accounting-services-sub-feature17"
                    ><span class="accounting-services-text059">✔</span
                    ><span>Balance Sheet</span></div
                  ><div class="accounting-services-sub-feature18"
                    ><span class="accounting-services-text060">✔</span
                    ><span
                      ><span
                        >Profit &amp; Loss <span v-html="rawvqcv"></span></span
                      ><br /><span>
                        <span v-html="raw3d02"></span></span></span></div
                  ><div class="accounting-services-sub-feature19"
                    ><span class="accounting-services-text064">✔</span
                    ><span
                      ><span>General Ledger <span v-html="rawtcez"></span></span
                      ><br /><span>
                        <span v-html="rawky0m"></span></span></span></div
                  ><div class="accounting-services-sub-feature20"
                    ><span class="accounting-services-text068">✔</span
                    ><span
                      ><span>Statement of Cash Flows</span><br /><span>
                        <span v-html="rawvp9s"></span></span></span></div
                  ><span class="accounting-services-text072"
                    ><span>LKR 10000</span><br /></span></div
                ><div class="accounting-services-feature08"
                  ><h1 class="accounting-services-text075"
                    >Stock Records <span v-html="rawf5cc"></span></h1
                  ><div class="accounting-services-sub-feature21"
                    ><span class="accounting-services-text076">✔</span
                    ><span>Stock report up to 20 items</span></div
                  ><span class="accounting-services-text077">LKR 4000</span></div
                ><div class="accounting-services-feature09"
                  ><h1 class="accounting-services-text078"
                    >Employee Funds <span v-html="raw9vls"></span></h1
                  ><div class="accounting-services-sub-feature22"
                    ><span class="accounting-services-text079">✔</span
                    ><span>EPF &amp; ETF returns up to 5 Emps</span></div
                  ><div class="accounting-services-sub-feature23"
                    ><span class="accounting-services-text080">✔</span
                    ><span
                      >Annual return <span v-html="rawqs9m"></span></span></div
                  ><span class="accounting-services-text081">LKR 4000</span></div
                ><div class="accounting-services-feature10"
                  ><h1 class="accounting-services-text082"
                    >Advice <span v-html="rawetqt"></span></h1
                  ><div class="accounting-services-sub-feature24"
                    ><span class="accounting-services-text083">✔</span
                    ><span
                      >CFO and business service meeting up to an hour</span
                    ></div
                  ><span class="accounting-services-text084">LKR 5000</span></div
                ><div class="accounting-services-feature11"
                  ><h1 class="accounting-services-text085"
                    >Training <span v-html="rawzpvd"></span></h1
                  ><div class="accounting-services-sub-feature25"
                    ><span class="accounting-services-text086">✔</span
                    ><span
                      >Necessary software training
                      <span v-html="rawuuu6"></span></span></div
                  ><span class="accounting-services-text087">LKR 5000</span></div
                ><div class="accounting-services-feature12"
                  ><h1 class="accounting-services-text088"
                    >Software and portals</h1
                  ><div class="accounting-services-sub-feature26"
                    ><span class="accounting-services-text089">✔</span
                    ><span
                      >Essential document storage
                      <span v-html="raw7isr"></span></span></div
                  ><div class="accounting-services-sub-feature27"
                    ><span class="accounting-services-text090">✔</span
                    ><span
                      >Accounting software setup &amp; maintenance
                      <span v-html="rawf6f0"></span></span></div
                  ><div class="accounting-services-sub-feature28"
                    ><span class="accounting-services-text091">✔</span
                    ><span>Expense management with two criteria</span></div
                  ><div class="accounting-services-sub-feature29"
                    ><span class="accounting-services-text092">✔</span
                    ><span
                      >Optional monthly <span v-html="rawp7gh"></span></span></div
                  ><div class="accounting-services-sub-feature30"
                    ><span class="accounting-services-text093">✔</span
                    ><span
                      >Optional monthly performance report with key performance
                      indicators (KPIs) <span v-html="rawgzx9"></span></span></div
                  ><div class="accounting-services-sub-feature31"
                    ><span class="accounting-services-text094">✔</span
                    ><span
                      >Class tracking <span v-html="rawjhju"></span></span></div
                  ><span class="accounting-services-text095">LKR 7500</span></div
                ></div
              ><button class="accounting-services-button1 buttonOutline"
                >Continue with Free</button
              ></div
            ><div class="freePricingCard accounting-services-pricing-card2"
              ><div class="accounting-services-container07"
                ><span class="accounting-services-text096 heading3"
                  >Small business Advanced</span
                ><span
                  ><span class="bodySmall">(250+ transactions/month)</span
                  ><br /><br /></span></div
              ><div class="accounting-services-container08"
                ><span class="accounting-services-free-plan-price2"
                  >Custom Pricing</span
                ><span class="accounting-services-text100"></span></div
              ><div class="accounting-services-feature-container2"
                ><div class="accounting-services-feature13"
                  ><h1 class="accounting-services-text101"
                    >Account reconciliation</h1
                  ><div class="accounting-services-sub-feature32"
                    ><span class="accounting-services-text102">✔</span
                    ><span>Bank accounts up to 5</span></div
                  ><div class="accounting-services-sub-feature33"
                    ><span class="accounting-services-text103">✔</span
                    ><span
                      >Credit card accounts up to 5
                      <span v-html="rawi2u3"></span></span></div
                  ><div class="accounting-services-sub-feature34"
                    ><span class="accounting-services-text104">✔</span
                    ><span
                      >Reconcile electronic transactions into an Accounting
                      Package <span v-html="rawo6d6"></span></span></div></div
                ><div class="accounting-services-feature14"
                  ><h1 class="accounting-services-text105">Monthly financials</h1
                  ><div class="accounting-services-sub-feature35"
                    ><span class="accounting-services-text106">✔</span
                    ><span>Balance Sheet</span></div
                  ><div class="accounting-services-sub-feature36"
                    ><span class="accounting-services-text107">✔</span
                    ><span
                      ><span
                        >Profit &amp; Loss <span v-html="rawynrr"></span></span
                      ><br /><span>
                        <span v-html="rawsq5z"></span></span></span></div
                  ><div class="accounting-services-sub-feature37"
                    ><span class="accounting-services-text111">✔</span
                    ><span
                      ><span>General Ledger <span v-html="rawq2jb"></span></span
                      ><br /><span>
                        <span v-html="raw6g6h"></span></span></span></div
                  ><div class="accounting-services-sub-feature38"
                    ><span class="accounting-services-text115">✔</span
                    ><span
                      ><span>Statement of Cash Flows</span><br /><span>
                        <span v-html="rawp949"></span></span></span></div></div
                ><div class="accounting-services-feature15"
                  ><h1 class="accounting-services-text119"
                    >Stock Records <span v-html="raw8oza"></span></h1
                  ><div class="accounting-services-sub-feature39"
                    ><span class="accounting-services-text120">✔</span
                    ><span>Stock system</span></div
                  ></div
                ><div class="accounting-services-feature16"
                  ><h1 class="accounting-services-text121"
                    >Employee Funds <span v-html="rawa67r"></span></h1
                  ><div class="accounting-services-sub-feature40"
                    ><span class="accounting-services-text122">✔</span
                    ><span>EPF &amp; ETF returns up to 5 Emps</span></div
                  ><div class="accounting-services-sub-feature41"
                    ><span class="accounting-services-text123">✔</span
                    ><span
                      >Annual return <span v-html="rawfqxc"></span></span></div
                  ><div class="accounting-services-sub-feature42"
                    ><span class="accounting-services-text124">✔</span
                    ><span>PAYE <span v-html="rawguk5"></span></span></div></div
                ><div class="accounting-services-feature17"
                  ><h1 class="accounting-services-text125"
                    >Advice &amp; Training</h1
                  ><div class="accounting-services-sub-feature43"
                    ><span class="accounting-services-text126">✔</span
                    ><span>General business consulting</span></div
                  ><div class="accounting-services-sub-feature44"
                    ><span class="accounting-services-text127">✔</span
                    ><span>Strategic planning</span></div
                  ><div class="accounting-services-sub-feature45"
                    ><span class="accounting-services-text128">✔</span
                    ><span>Tax planning <span v-html="rawzjot"></span></span></div
                  ><div class="accounting-services-sub-feature46"
                    ><span class="accounting-services-text129">✔</span
                    ><span>Necessary software training</span></div
                  ><div class="accounting-services-sub-feature47"
                    ><span class="accounting-services-text130">✔</span
                    ><span>Business advisory service</span></div
                  ></div
                ><div class="accounting-services-feature18"
                  ><h1 class="accounting-services-text131"
                    >Software and portals</h1
                  ><div class="accounting-services-sub-feature48"
                    ><span class="accounting-services-text132">✔</span
                    ><span
                      >Essential document storage
                      <span v-html="rawsm2q"></span></span></div
                  ><div class="accounting-services-sub-feature49"
                    ><span class="accounting-services-text133">✔</span
                    ><span
                      >Accounting software setup &amp; maintenance
                      <span v-html="raw1qrn"></span></span></div
                  ><div class="accounting-services-sub-feature50"
                    ><span class="accounting-services-text134">✔</span
                    ><span>Expense management</span></div
                  ><div class="accounting-services-sub-feature51"
                    ><span class="accounting-services-text135">✔</span
                    ><span
                      >Optional monthly performance report with key performance
                      indicators (KPIs) <span v-html="rawdf8e"></span></span></div
                  ><div class="accounting-services-sub-feature52"
                    ><span class="accounting-services-text136">✔</span
                    ><span
                      >Class and location tracking
                      <span v-html="raw2zq5"></span></span></div></div></div
              ><button class="accounting-services-button2 buttonOutline"
                >Continue with Free</button
              ></div
            ></div
          ></div
        ></div
      ></div
    ><div class="accounting-services-footer"
      ><footer class="footerContainer accounting-services-footer1"
        ><div class="accounting-services-container09"
          ><span class="TaxOnUs">TAXPROS</span
          ><nav class="accounting-services-nav"
            ><span class="bodySmall">Services</span
            ><span class="accounting-services-nav22 bodySmall">About Us</span
            ><span class="accounting-services-nav32 bodySmall">Resources</span
            ><span class="accounting-services-nav42 bodySmall"
              >Contact Us</span
            ></nav
          ></div
        ><div class="accounting-services-separator"></div
        ><div class="accounting-services-container10"
          ><span class="bodySmall accounting-services-text137"
            >© 2023 myCompany, All Rights Reserved.</span
          ><div class="accounting-services-icon-group"
            ><svg
              viewBox="0 0 950.8571428571428 1024"
              class="accounting-services-icon socialIcons"
            >
              <path
                d="M925.714 233.143c-25.143 36.571-56.571 69.143-92.571 95.429 0.571 8 0.571 16 0.571 24 0 244-185.714 525.143-525.143 525.143-104.571 0-201.714-30.286-283.429-82.857 14.857 1.714 29.143 2.286 44.571 2.286 86.286 0 165.714-29.143 229.143-78.857-81.143-1.714-149.143-54.857-172.571-128 11.429 1.714 22.857 2.857 34.857 2.857 16.571 0 33.143-2.286 48.571-6.286-84.571-17.143-148-91.429-148-181.143v-2.286c24.571 13.714 53.143 22.286 83.429 23.429-49.714-33.143-82.286-89.714-82.286-153.714 0-34.286 9.143-65.714 25.143-93.143 90.857 112 227.429 185.143 380.571 193.143-2.857-13.714-4.571-28-4.571-42.286 0-101.714 82.286-184.571 184.571-184.571 53.143 0 101.143 22.286 134.857 58.286 41.714-8 81.714-23.429 117.143-44.571-13.714 42.857-42.857 78.857-81.143 101.714 37.143-4 73.143-14.286 106.286-28.571z"
              ></path></svg
            ><svg
              viewBox="0 0 877.7142857142857 1024"
              class="accounting-services-icon2 socialIcons"
            >
              <path
                d="M585.143 512c0-80.571-65.714-146.286-146.286-146.286s-146.286 65.714-146.286 146.286 65.714 146.286 146.286 146.286 146.286-65.714 146.286-146.286zM664 512c0 124.571-100.571 225.143-225.143 225.143s-225.143-100.571-225.143-225.143 100.571-225.143 225.143-225.143 225.143 100.571 225.143 225.143zM725.714 277.714c0 29.143-23.429 52.571-52.571 52.571s-52.571-23.429-52.571-52.571 23.429-52.571 52.571-52.571 52.571 23.429 52.571 52.571zM438.857 152c-64 0-201.143-5.143-258.857 17.714-20 8-34.857 17.714-50.286 33.143s-25.143 30.286-33.143 50.286c-22.857 57.714-17.714 194.857-17.714 258.857s-5.143 201.143 17.714 258.857c8 20 17.714 34.857 33.143 50.286s30.286 25.143 50.286 33.143c57.714 22.857 194.857 17.714 258.857 17.714s201.143 5.143 258.857-17.714c20-8 34.857-17.714 50.286-33.143s25.143-30.286 33.143-50.286c22.857-57.714 17.714-194.857 17.714-258.857s5.143-201.143-17.714-258.857c-8-20-17.714-34.857-33.143-50.286s-30.286-25.143-50.286-33.143c-57.714-22.857-194.857-17.714-258.857-17.714zM877.714 512c0 60.571 0.571 120.571-2.857 181.143-3.429 70.286-19.429 132.571-70.857 184s-113.714 67.429-184 70.857c-60.571 3.429-120.571 2.857-181.143 2.857s-120.571 0.571-181.143-2.857c-70.286-3.429-132.571-19.429-184-70.857s-67.429-113.714-70.857-184c-3.429-60.571-2.857-120.571-2.857-181.143s-0.571-120.571 2.857-181.143c3.429-70.286 19.429-132.571 70.857-184s113.714-67.429 184-70.857c60.571-3.429 120.571-2.857 181.143-2.857s120.571-0.571 181.143 2.857c70.286 3.429 132.571 19.429 184 70.857s67.429 113.714 70.857 184c3.429 60.571 2.857 120.571 2.857 181.143z"
              ></path></svg
            ><svg
              viewBox="0 0 602.2582857142856 1024"
              class="accounting-services-icon4 socialIcons"
            >
              <path
                d="M548 6.857v150.857h-89.714c-70.286 0-83.429 33.714-83.429 82.286v108h167.429l-22.286 169.143h-145.143v433.714h-174.857v-433.714h-145.714v-169.143h145.714v-124.571c0-144.571 88.571-223.429 217.714-223.429 61.714 0 114.857 4.571 130.286 6.857z"
              ></path></svg></div></div></footer></div
  ></div>
</template>

<script>
import AppHeader from '../components/header'

export default {
  name: 'AccountingServices',
  props: {},
  components: {
    AppHeader,
  },
  data() {
    return {
      rawzeud: ' ',
      rawefv3: ' ',
      rawh3q4: ' ',
      rawhk38: ' ',
      raw4fo2: ' ',
      raw96si: ' ',
      raw8s28: ' ',
      rawtbk6: ' ',
      rawj9r0: ' ',
      rawzqj1: ' ',
      raw9mnm: ' ',
      rawzzq3: ' ',
      raw6h2q: ' ',
      raw0wdw: ' ',
      raw0r4w: ' ',
      rawmy0b: ' ',
      rawlnm8: ' ',
      rawvqcv: ' ',
      raw3d02: ' ',
      rawtcez: ' ',
      rawky0m: ' ',
      rawvp9s: ' ',
      rawf5cc: ' ',
      raw9vls: ' ',
      rawqs9m: ' ',
      rawetqt: ' ',
      rawzpvd: ' ',
      rawuuu6: ' ',
      raw7isr: ' ',
      rawf6f0: ' ',
      rawp7gh: ' ',
      rawgzx9: ' ',
      rawjhju: ' ',
      rawi2u3: ' ',
      rawo6d6: ' ',
      rawynrr: ' ',
      rawsq5z: ' ',
      rawq2jb: ' ',
      raw6g6h: ' ',
      rawp949: ' ',
      raw8oza: ' ',
      rawa67r: ' ',
      rawfqxc: ' ',
      rawguk5: ' ',
      rawzjot: ' ',
      rawsm2q: ' ',
      raw1qrn: ' ',
      rawdf8e: ' ',
      raw2zq5: ' ',
    }
  },
  metaInfo: {
    title: 'Accounting-Services - taxonus',
    meta: [
      {
        property: 'og:title',
        content: 'Accounting-Services - taxonus',
      },
    ],
  },
}
</script>

<style scoped>
.accounting-services-container {
  width: 100%;
  display: flex;
  overflow: auto;
  min-height: 100vh;
  align-items: center;
  flex-direction: column;
}
.accounting-services-hero {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  margin-top: 96px;
  align-items: flex-start;
  justify-content: center;
}
.accounting-services-container01 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.accounting-services-hero-heading {
  max-width: 800px;
  text-align: center;
}
.accounting-services-pricing {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.accounting-services-pricing1 {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.accounting-services-container02 {
  gap: var(--dl-space-space-twounits);
  width: 100%;
  display: flex;
  align-items: flex-start;
  justify-content: center;
}
.accounting-services-container03 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.accounting-services-text {
  text-transform: uppercase;
}
.accounting-services-container04 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
}
.accounting-services-text004 {
  font-size: 1.15rem;
  margin-top: var(--dl-space-space-twounits);
  font-weight: 300;
}
.accounting-services-free-plan-price {
  font-size: 4rem;
  font-weight: 700;
}
.accounting-services-text005 {
  font-size: 1.15rem;
  font-style: normal;
  margin-top: var(--dl-space-space-twounits);
  font-weight: 300;
}
.accounting-services-feature-container {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: column;
}
.accounting-services-feature {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text006 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text007 {
  line-height: 150%;
}
.accounting-services-sub-feature01 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text008 {
  line-height: 150%;
}
.accounting-services-sub-feature02 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text009 {
  line-height: 150%;
}
.accounting-services-text010 {
  align-self: flex-end;
  margin-top: var(--dl-space-space-unit);
}
.accounting-services-feature01 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text011 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature03 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text012 {
  line-height: 150%;
}
.accounting-services-sub-feature04 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text013 {
  line-height: 150%;
}
.accounting-services-sub-feature05 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text017 {
  line-height: 150%;
}
.accounting-services-sub-feature06 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text021 {
  line-height: 150%;
}
.accounting-services-text025 {
  align-self: flex-end;
  margin-top: var(--dl-space-space-unit);
}
.accounting-services-feature02 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text028 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature07 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text029 {
  line-height: 150%;
}
.accounting-services-text030 {
  align-self: flex-end;
  margin-top: var(--dl-space-space-unit);
}
.accounting-services-feature03 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text031 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature08 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text032 {
  line-height: 150%;
}
.accounting-services-sub-feature09 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text033 {
  line-height: 150%;
}
.accounting-services-text034 {
  align-self: flex-end;
  margin-top: var(--dl-space-space-unit);
}
.accounting-services-feature04 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text035 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature10 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text036 {
  line-height: 150%;
}
.accounting-services-text037 {
  align-self: flex-end;
  margin-top: var(--dl-space-space-unit);
}
.accounting-services-feature05 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text038 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature11 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text039 {
  line-height: 150%;
}
.accounting-services-sub-feature12 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text040 {
  line-height: 150%;
}
.accounting-services-sub-feature13 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text041 {
  line-height: 150%;
}
.accounting-services-text046 {
  align-self: flex-end;
  margin-top: var(--dl-space-space-unit);
}
.accounting-services-button {
  width: 100%;
  display: none;
}
.accounting-services-container05 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.accounting-services-text047 {
  text-transform: uppercase;
}
.accounting-services-container06 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
}
.accounting-services-text051 {
  font-size: 1.15rem;
  margin-top: var(--dl-space-space-twounits);
  font-weight: 300;
}
.accounting-services-free-plan-price1 {
  font-size: 4rem;
  font-weight: 700;
}
.accounting-services-text052 {
  font-size: 1.15rem;
  font-style: normal;
  margin-top: var(--dl-space-space-twounits);
  font-weight: 300;
}
.accounting-services-feature-container1 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: column;
}
.accounting-services-feature06 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text053 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature14 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text054 {
  line-height: 150%;
}
.accounting-services-sub-feature15 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text055 {
  line-height: 150%;
}
.accounting-services-sub-feature16 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text056 {
  line-height: 150%;
}
.accounting-services-text057 {
  align-self: flex-end;
  margin-top: var(--dl-space-space-unit);
}
.accounting-services-feature07 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text058 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature17 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text059 {
  line-height: 150%;
}
.accounting-services-sub-feature18 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text060 {
  line-height: 150%;
}
.accounting-services-sub-feature19 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text064 {
  line-height: 150%;
}
.accounting-services-sub-feature20 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text068 {
  line-height: 150%;
}
.accounting-services-text072 {
  align-self: flex-end;
  margin-top: var(--dl-space-space-unit);
}
.accounting-services-feature08 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text075 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature21 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text076 {
  line-height: 150%;
}
.accounting-services-text077 {
  align-self: flex-end;
  margin-top: var(--dl-space-space-unit);
}
.accounting-services-feature09 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text078 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature22 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text079 {
  line-height: 150%;
}
.accounting-services-sub-feature23 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text080 {
  line-height: 150%;
}
.accounting-services-text081 {
  align-self: flex-end;
  margin-top: var(--dl-space-space-unit);
}
.accounting-services-feature10 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text082 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature24 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text083 {
  line-height: 150%;
}
.accounting-services-text084 {
  align-self: flex-end;
  margin-top: var(--dl-space-space-unit);
}
.accounting-services-feature11 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text085 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature25 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text086 {
  line-height: 150%;
}
.accounting-services-text087 {
  align-self: flex-end;
  margin-top: var(--dl-space-space-unit);
}
.accounting-services-feature12 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text088 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature26 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text089 {
  line-height: 150%;
}
.accounting-services-sub-feature27 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text090 {
  line-height: 150%;
}
.accounting-services-sub-feature28 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text091 {
  line-height: 150%;
}
.accounting-services-sub-feature29 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text092 {
  line-height: 150%;
}
.accounting-services-sub-feature30 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text093 {
  line-height: 150%;
}
.accounting-services-sub-feature31 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text094 {
  line-height: 150%;
}
.accounting-services-text095 {
  align-self: flex-end;
  margin-top: var(--dl-space-space-unit);
}
.accounting-services-button1 {
  width: 100%;
  display: none;
}
.accounting-services-container07 {
  gap: var(--dl-space-space-oneandhalfunits);
  display: flex;
  align-items: flex-start;
  flex-direction: column;
  justify-content: flex-start;
}
.accounting-services-text096 {
  text-transform: uppercase;
}
.accounting-services-container08 {
  display: flex;
  align-items: center;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
}
.accounting-services-free-plan-price2 {
  font-size: 4rem;
  font-style: italic;
  font-weight: 600;
}
.accounting-services-text100 {
  font-size: 1.15rem;
  font-style: normal;
  margin-top: var(--dl-space-space-twounits);
  font-weight: 300;
}
.accounting-services-feature-container2 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: var(--dl-space-space-unit);
  flex-direction: column;
}
.accounting-services-feature13 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text101 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature32 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text102 {
  line-height: 150%;
}
.accounting-services-sub-feature33 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text103 {
  line-height: 150%;
}
.accounting-services-sub-feature34 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text104 {
  line-height: 150%;
}
.accounting-services-feature14 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text105 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature35 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text106 {
  line-height: 150%;
}
.accounting-services-sub-feature36 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text107 {
  line-height: 150%;
}
.accounting-services-sub-feature37 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text111 {
  line-height: 150%;
}
.accounting-services-sub-feature38 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text115 {
  line-height: 150%;
}
.accounting-services-feature15 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text119 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature39 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text120 {
  line-height: 150%;
}
.accounting-services-feature16 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text121 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature40 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text122 {
  line-height: 150%;
}
.accounting-services-sub-feature41 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text123 {
  line-height: 150%;
}
.accounting-services-sub-feature42 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text124 {
  line-height: 150%;
}
.accounting-services-feature17 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text125 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature43 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text126 {
  line-height: 150%;
}
.accounting-services-sub-feature44 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text127 {
  line-height: 150%;
}
.accounting-services-sub-feature45 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text128 {
  line-height: 150%;
}
.accounting-services-sub-feature46 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text129 {
  line-height: 150%;
}
.accounting-services-sub-feature47 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text130 {
  line-height: 150%;
}
.accounting-services-feature18 {
  width: 100%;
  display: flex;
  align-items: flex-start;
  margin-bottom: 0px;
  flex-direction: column;
  padding-bottom: 5%;
}
.accounting-services-text131 {
  font-size: 1.5em;
  margin-bottom: var(--dl-space-space-halfunit);
}
.accounting-services-sub-feature48 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text132 {
  line-height: 150%;
}
.accounting-services-sub-feature49 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text133 {
  line-height: 150%;
}
.accounting-services-sub-feature50 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text134 {
  line-height: 150%;
}
.accounting-services-sub-feature51 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text135 {
  line-height: 150%;
}
.accounting-services-sub-feature52 {
  gap: 4px;
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  position: relative;
  margin-bottom: 0px;
  flex-direction: row;
}
.accounting-services-text136 {
  line-height: 150%;
}
.accounting-services-button2 {
  width: 100%;
  display: none;
}
.accounting-services-footer {
  flex: 0 0 auto;
  width: 100%;
  height: auto;
  display: flex;
  align-items: center;
  justify-content: center;
}
.accounting-services-container09 {
  gap: var(--dl-space-space-unit);
  display: flex;
  max-width: var(--dl-size-size-maxwidth);
  align-items: center;
  flex-direction: column;
  justify-content: flex-start;
}
.accounting-services-nav {
  flex: 0 0 auto;
  display: flex;
  margin-top: 0px;
  align-items: center;
  flex-direction: row;
}
.accounting-services-nav22 {
  margin-left: var(--dl-space-space-unit);
}
.accounting-services-nav32 {
  margin-left: var(--dl-space-space-unit);
}
.accounting-services-nav42 {
  margin-left: var(--dl-space-space-unit);
}
.accounting-services-separator {
  flex: 0 0 auto;
  width: 100%;
  height: 0px;
  display: flex;
  margin-top: var(--dl-space-space-twounits);
  align-items: flex-start;
  margin-left: 0px;
  border-color: var(--dl-color-gray-900);
  border-style: solid;
  border-width: 1px;
  margin-right: 0px;
  margin-bottom: var(--dl-space-space-twounits);
  flex-direction: row;
  border-top-width: 0px;
  border-left-width: 0px;
  border-right-width: 0px;
}
.accounting-services-container10 {
  flex: 0 0 auto;
  width: 100%;
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.accounting-services-icon-group {
  display: flex;
  align-items: center;
  flex-direction: row;
  justify-content: space-between;
}
.accounting-services-icon {
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-twounits);
}
.accounting-services-icon2 {
  width: 24px;
  height: 24px;
  margin-right: var(--dl-space-space-twounits);
}
.accounting-services-icon4 {
  width: 24px;
  height: 24px;
}
@media(max-width: 991px) {
  .accounting-services-hero1 {
    flex-direction: column;
  }
  .accounting-services-container01 {
    align-items: center;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
    padding-right: 0px;
  }
  .accounting-services-hero-heading {
    text-align: center;
  }
  .accounting-services-container02 {
    align-items: center;
    flex-direction: column;
  }
  .accounting-services-pricing-card {
    width: 100%;
    padding: var(--dl-space-space-twounits);
    max-width: 450px;
  }
  .accounting-services-pricing-card1 {
    width: 100%;
    padding: var(--dl-space-space-twounits);
    max-width: 450px;
  }
  .accounting-services-pricing-card2 {
    width: 100%;
    padding: var(--dl-space-space-twounits);
    max-width: 450px;
  }
}
@media(max-width: 767px) {
  .accounting-services-hero1 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .accounting-services-container02 {
    align-items: center;
    flex-direction: column;
  }
  .accounting-services-pricing-card {
    width: 100%;
    max-width: 450px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
  }
  .accounting-services-pricing-card1 {
    width: 100%;
    max-width: 450px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
  }
  .accounting-services-pricing-card2 {
    width: 100%;
    max-width: 450px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-twounits);
  }
  .accounting-services-footer1 {
    padding-left: var(--dl-space-space-twounits);
    padding-right: var(--dl-space-space-twounits);
  }
  .accounting-services-separator {
    margin-top: var(--dl-space-space-oneandhalfunits);
    margin-left: 0px;
    margin-right: 0px;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .accounting-services-container10 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .accounting-services-text137 {
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
@media(max-width: 479px) {
  .accounting-services-hero1 {
    padding-top: var(--dl-space-space-twounits);
    padding-left: var(--dl-space-space-unit);
    padding-right: var(--dl-space-space-unit);
    padding-bottom: var(--dl-space-space-twounits);
  }
  .accounting-services-container01 {
    margin-bottom: var(--dl-space-space-unit);
  }
  .accounting-services-footer1 {
    padding: var(--dl-space-space-unit);
  }
  .accounting-services-separator {
    margin-top: var(--dl-space-space-oneandhalfunits);
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
  .accounting-services-container10 {
    align-items: center;
    flex-direction: column;
    justify-content: space-between;
  }
  .accounting-services-text137 {
    text-align: center;
    margin-bottom: var(--dl-space-space-oneandhalfunits);
  }
}
</style>
