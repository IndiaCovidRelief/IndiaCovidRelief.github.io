---
layout: default
---

<!-- Google Tag Manager -->
<script>(function(w,d,s,l,i){w[l]=w[l]||[];w[l].push({'gtm.start':
new Date().getTime(),event:'gtm.js'});var f=d.getElementsByTagName(s)[0],
j=d.createElement(s),dl=l!='dataLayer'?'&l='+l:'';j.async=true;j.src=
'https://www.googletagmanager.com/gtm.js?id='+i+dl;f.parentNode.insertBefore(j,f);
})(window,document,'script','dataLayer','GTM-NNJLRQW');</script>
<!-- End Google Tag Manager -->
<!-- Google Tag Manager (noscript) -->
<noscript><iframe src="https://www.googletagmanager.com/ns.html?id=GTM-NNJLRQW"
height="0" width="0" style="display:none;visibility:hidden"></iframe></noscript>
<!-- End Google Tag Manager (noscript) -->
<script>
/**
* Function that captures a click on an outbound link in Analytics.
* This function takes a valid URL string as an argument, and uses that URL string
* as the event label. Setting the transport method to 'beacon' lets the hit be sent
* using 'navigator.sendBeacon' in browser that support it.
*/
var captureOutboundLink = function(url) {
   ga('send', 'event', 'outbound', 'click', url, {
     'transport': 'beacon',
     'hitCallback': function(){document.location = url;}
   });
}
</script>

<style>
table th:first-of-type {
    width: 40%;
}
table th:nth-of-type(2) {
    width: 20%;
}
table th:nth-of-type(3) {
    width: 20%;
}
table th:nth-of-type(4) {
    width: 20%;
}

.btn.abtn {
    background-color:rgba(255,255,255,0.15);
    border-color:rgba(255,255,255,0.2)
}

.btn.ibtn {
    background-color:rgba(255,255,255,0.1);
    border-color:rgba(255,255,255,0.2)
}

.form-group {
  margin-bottom: 5%;
}

.dropdown {
  padding: 1%;
  margin: 1.5%;
  display: inline;
  width: 40%;
  font-size: 1rem;
  line-height: 1.5;
  color: rgba(255, 255, 255, 0.7);
  background-clip: padding-box;
  border: 1px solid #ced4da;
  border-radius: .25rem;
  transition: border-color .15s ease-in-out,box-shadow .15s ease-in-out;
  background-color: rgba(255,255,255,0.15);
}

.dropdown option {
  background-color: rgba(255,255,255,0.15);
  color: #606c71;
}

._reset_filter {
  margin-top: 3%;
  margin-bottom: 0%;
  cursor: pointer;
  padding: 0.4rem 0.8rem;
  font-size: 0.9rem;
  width: 40%;
}

.page-em {
	color: #fff;
	text-align: center;
	background-color: #159957;
	background-image: linear-gradient(120deg, #155799, #159957)
}

.share-links {
  margin: 0px;
  background: none;
  margin-top: 2%;
}

@media screen and (min-width: 64em) {
	.page-em {
		padding: 3rem 4rem
	}
}

@media screen and (min-width: 42em) and (max-width: 64em) {
	.page-em {
		padding: 2rem 1rem
	}
}

@media screen and (max-width: 42em) {
	.page-em {
		padding: 1rem 0.5rem
	}
}

@media screen and (max-width: 480px) {
     .dropdown {
        display: block;
        width: 95%;
        margin-bottom: 10%;
     }

     .form-group {
      margin-left: 5%;
     }
}

.resp-sharing-button__link,
.resp-sharing-button__icon {
  display: inline-block
}

.resp-sharing-button__link {
  text-decoration: none;
  color: #fff;
  margin: 0.5em
}

.resp-sharing-button {
  border-radius: 5px;
  transition: 25ms ease-out;
  padding: 0.5em 0.75em;
  font-family: Helvetica Neue,Helvetica,Arial,sans-serif
}

.resp-sharing-button__icon svg {
  width: 1em;
  height: 1em;
  margin-right: 0.4em;
  vertical-align: top
}

.resp-sharing-button--small svg {
  margin: 0;
  vertical-align: middle
}

/* Non solid icons get a stroke */
.resp-sharing-button__icon {
  stroke: #fff;
  fill: none
}

/* Solid icons get a fill */
.resp-sharing-button__icon--solid,
.resp-sharing-button__icon--solidcircle {
  fill: #fff;
  stroke: none
}

.resp-sharing-button--twitter {
  background-color: #55acee
}

.resp-sharing-button--twitter:hover {
  background-color: #2795e9
}

.resp-sharing-button--pinterest {
  background-color: #bd081c
}

.resp-sharing-button--pinterest:hover {
  background-color: #8c0615
}

.resp-sharing-button--facebook {
  background-color: #3b5998
}

.resp-sharing-button--facebook:hover {
  background-color: #2d4373
}

.resp-sharing-button--tumblr {
  background-color: #35465C
}

.resp-sharing-button--tumblr:hover {
  background-color: #222d3c
}

.resp-sharing-button--reddit {
  background-color: #5f99cf
}

.resp-sharing-button--reddit:hover {
  background-color: #3a80c1
}

.resp-sharing-button--google {
  background-color: #dd4b39
}

.resp-sharing-button--google:hover {
  background-color: #c23321
}

.resp-sharing-button--linkedin {
  background-color: #0077b5
}

.resp-sharing-button--linkedin:hover {
  background-color: #046293
}

.resp-sharing-button--email {
  background-color: #777
}

.resp-sharing-button--email:hover {
  background-color: #5e5e5e
}

.resp-sharing-button--xing {
  background-color: #1a7576
}

.resp-sharing-button--xing:hover {
  background-color: #114c4c
}

.resp-sharing-button--whatsapp {
  background-color: #25D366
}

.resp-sharing-button--whatsapp:hover {
  background-color: #1da851
}

.resp-sharing-button--hackernews {
background-color: #FF6600
}
.resp-sharing-button--hackernews:hover, .resp-sharing-button--hackernews:focus {   background-color: #FB6200 }

.resp-sharing-button--vk {
  background-color: #507299
}

.resp-sharing-button--vk:hover {
  background-color: #43648c
}

.resp-sharing-button--facebook {
  background-color: #3b5998;
  border-color: #3b5998;
}

.resp-sharing-button--facebook:hover,
.resp-sharing-button--facebook:active {
  background-color: #2d4373;
  border-color: #2d4373;
}

.resp-sharing-button--twitter {
  background-color: #55acee;
  border-color: #55acee;
}

.resp-sharing-button--twitter:hover,
.resp-sharing-button--twitter:active {
  background-color: #2795e9;
  border-color: #2795e9;
}

.resp-sharing-button--linkedin {
  background-color: #0077b5;
  border-color: #0077b5;
}

.resp-sharing-button--linkedin:hover,
.resp-sharing-button--linkedin:active {
  background-color: #046293;
  border-color: #046293;
}

.resp-sharing-button--whatsapp {
  background-color: #25D366;
  border-color: #25D366;
}

.resp-sharing-button--whatsapp:hover,
.resp-sharing-button--whatsapp:active {
  background-color: #1DA851;
  border-color: #1DA851;
}



</style>

<section  id="table-filter" class="page-em">
<div class="form-group">
  <select class="form-control dropdown" id="_location_filter" filter="location">
      <option selected value="all">-- All Locations --</option>
      <option value="india">Pan India</option>
      <option value="mumbai">Mumbai</option>
      <option value="delhi">Delhi</option>
      <option value="bangalore">Bangalore</option>
      <option value="other-loc">Other Locations</option>
  </select>
  <br>
  <select class="form-control dropdown" id="_people_filter" filter="people">
      <option selected value="all">-- All Beneficiaries --</option>
      <option value="wage-workers">Daily Wager</option>
      <option value="homeless">Homeless</option>
      <option value="trash-pickers">Trash Pickers</option>
      <option value="migrant-workers">Migrant Workers</option>
      <option value="domestic-workers">Domestic Workers</option>
      <option value="other-ben">Other Beneficiaries</option>
  </select>
  <br>
  <select class="form-control dropdown" id="_helptype_filter" filter="helptype">
      <option selected value="all">-- All Types --</option>
      <option value="cash">Cash</option>
      <option value="food">Food</option>
      <option value="homeless">Ration</option>
      <option value="sanitation">Sanitation</option>
      <option value="ppe">PPE</option>
      <option value="other-sup">Other Suppplies</option>
  </select>
</div>

<hr>
<a class="btn _reset_filter ibtn" filter="all-campaigns" style="display:inline-block;text-align:center;text-decoration:none" id="_reset_filter">Reset Filters</a>
</section>

<br>
<table id="main-table">
  <thead>
    <tr>
      <th>Organization</th>
      <th>Beneficiaries</th>
      <th>Support Provided</th>
      <th>City/States</th>
    </tr>
  </thead>
  <tbody>
        <tr class="no-rows-found" id="no-rows-found">
            <td colspan="4" style="text-align: center;">No campaigns found! Please reset the filters.</td>
        </tr>
        <tr class="india wage-workers cash">
         <td>Give India - Support Families <br /><span style="font-size:0.8em"> [<a href="https://indiafightscorona.giveindia.org/support-families/">Go To Page</a>] [<a href="#give-india---support-families">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Cash</td>
         <td>Pan India</td>
        </tr>
        <tr class="india wage-workers ration">
         <td>Zomato India <br /><span style="font-size:0.8em"> [<a href="https://www.zomato.com/blog/feed-daily-wager">Go To Page</a>] [<a href="#zomato-india">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Ration kits</td>
         <td>Pan India</td>
        </tr>
        <tr class="other-loc other-ben ration">
         <td>Kanaga (Personal Campaign) <br /><span style="font-size:0.8em"> [<a href="https://milaap.org/fundraisers/support-kanaga">Go To Page</a>] [<a href="#kanaga-personal-campaign">Details</a>]</span></td>
         <td>Trans persons</td>
         <td>Ration kits</td>
         <td>Chennai</td>
        </tr>
        <tr class="delhi trash-pickers cash">
         <td>Paigam <br /><span style="font-size:0.8em"> [<a href="https://pages.razorpay.com/pl_EW6B2AlIPZz41X/view">Go To Page</a>] [<a href="#paigam">Details</a>]</span></td>
         <td>Waste pickers</td>
         <td>Cash, safety kits</td>
         <td>Delhi</td>
        </tr>
        <tr class="india wage-workers ration">
         <td>Goonj - Rahat COVID-19 <br /><span style="font-size:0.8em"> [<a href="https://goonj.org/support-covid-19-affected/">Go To Page</a>] [<a href="#goonj---rahat-covid-19">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Ration kits</td>
         <td>Pan India</td>
        </tr>
        <tr class="other-loc wage-workers ration">
         <td>Elixir Foundation <br /><span style="font-size:0.8em"> [<a href="https://pages.razorpay.com/pl_EW357Eyk0tOlaa/view">Go To Page</a>] [<a href="#elixir-foundation">Details</a>]</span></td>
         <td>Daily wage workers, old age homes, shelters</td>
         <td>Ration kits</td>
         <td>Ahmedabad</td>
        </tr>
        <tr class="bangalore wage-workers homeless migrant-workers ration sanitation">
         <td>SAFA Society <br /><span style="font-size:0.8em"> [<a href="https://pages.razorpay.com/Covid19Relief">Go To Page</a>] [<a href="#safa-society">Details</a>]</span></td>
         <td>Daily wage workers, migrant workers, street children, single parents, beggars</td>
         <td>Ration kits, hygeine kits</td>
         <td>Hyderabad, North Karnataka, Bangalore, Chennai</td>
        </tr>
        <tr class="mumbai delhi bangalore wage-workers domestic-workers food">
         <td>Venkat Iyer (Personal Campaign) <br /><span style="font-size:0.8em"> [<a href="https://milaap.org/fundraisers/support-venkat-iyer">Go To Page</a>] [<a href="#venkat-iyer-personal-campaign">Details</a>]</span></td>
         <td>Daily wagers, domestic workers</td>
         <td>Food, medicines</td>
         <td>Delhi, Agra, Lucknow, Kanpur, Varanasi, Bangalore, Mumbai, Surat, Malegaon</td>
        </tr>
        <tr class="india homeless food sanitation">
         <td>Uday Foundation <br /><span style="font-size:0.8em"> [<a href="https://www.udayfoundation.org/coronavirus-disease-covid-19/?fbclid=IwAR05051YKouzPYii14L2CNPnS-I80PLgvAj_tw4NUuFxcDIlGl8AS6ft7FA">Go To Page</a>] [<a href="#uday-foundation">Details</a>]</span></td>
         <td>Homeless persons</td>
         <td>Food, soap</td>
         <td>Pan India</td>
        </tr>
        <tr class="delhi wage-workers cash">
         <td>Delhi Youth Welfare Association <br /><span style="font-size:0.8em"> [<a href="https://www.ourdemocracy.in/Campaign/covid19Delhi">Go To Page</a>] [<a href="#delhi-youth-welfare-association">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Cash</td>
         <td>Delhi</td>
        </tr>
        <tr class="mumbai wage-workers ration">
         <td>YUVA <br /><span style="font-size:0.8em"> [<a href="https://milaap.org/fundraisers/support-youth-for-unity-and-voluntary-action">Go To Page</a>] [<a href="#yuva">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Ration kits</td>
         <td>Mumbai</td>
        </tr>
        <tr class="mumbai other-ben ration">
         <td>Making The Difference <br /><span style="font-size:0.8em"> [<a href="https://pages.razorpay.com/pl_EUwNKcGMyXoosk/view">Go To Page</a>] [<a href="#making-the-difference">Details</a>]</span></td>
         <td>Underprivileged</td>
         <td>Ration kits</td>
         <td>Mumbai</td>
        </tr>
        <tr class="mumbai other-ben ration">
         <td>Help for Sex Workers (Personal Campaign) <br /><span style="font-size:0.8em"> [<a href="https://www.ketto.org/fundraiser/covid-19-relief-fund-for-sex-workers-in-kamathipura?payment=form">Go To Page</a>] [<a href="#help-for-sex-workers-personal-campaign">Details</a>]</span></td>
         <td>Sex workers</td>
         <td>Ration kits</td>
         <td>Mumbai</td>
        </tr>
        <tr class="bangalore trash-pickers ration">
         <td>Hasiru Dala <br /><span style="font-size:0.8em"> [<a href="http://hasirudala.in/news/wastepickers-and-covid19/">Go To Page</a>] [<a href="#hasiru-dala">Details</a>]</span></td>
         <td>Waste pickers</td>
         <td>Ration kits</td>
         <td>Bangalore, Mysuru, Tumakuru, Davanagere, Hubli, Dharawad</td>
        </tr>
        <tr class="other-loc other-ben cash ration">
         <td>Sangama <br /><span style="font-size:0.8em"> [<a href="https://www.ourdemocracy.in/Campaign/supportsangama">Go To Page</a>] [<a href="#sangama">Details</a>]</span></td>
         <td>Sex workers, trans persons</td>
         <td>Ration kits, cash</td>
         <td>Karnataka</td>
        </tr>
        <tr class="other-loc wage-workers cash">
         <td>Chhoti Si Aasha <br /><span style="font-size:0.8em"> [<a href="https://www.ourdemocracy.in/Campaign/Covid19reliefCHD">Go To Page</a>] [<a href="#chhoti-si-aasha">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Cash</td>
         <td>Chandigarh, Mohali, Panchkula</td>
        </tr>
        <tr class="delhi wage-workers domestic-workers ration">
         <td>Meraj Foundation <br /><span style="font-size:0.8em"> [<a href="https://www.ourdemocracy.in/Campaign/MerajFoundation">Go To Page</a>] [<a href="#meraj-foundation">Details</a>]</span></td>
         <td>Differently abled, daily wage workers, domestic workers, gig workers</td>
         <td>Essential items</td>
         <td>Delhi</td>
        </tr>
        <tr class="other-loc trash-pickers ration ppe">
         <td>Kashtakari Panchayat <br /><span style="font-size:0.8em"> [<a href="https://www.ourdemocracy.in/Campaign/Covid19Pune">Go To Page</a>] [<a href="#kashtakari-panchayat">Details</a>]</span></td>
         <td>Waste pickers</td>
         <td>Ration kits, Personal Protective Equipment (PPE)</td>
         <td>Pune</td>
        </tr>
        <tr class="india homeless ration food">
         <td>Upay <br /><span style="font-size:0.8em"> [<a href="https://www.upay.org.in/crowd-fund/Help-us-fight-corona-and-feed-the-homeless">Go To Page</a>] [<a href="#upay">Details</a>]</span></td>
         <td>Homeless persons</td>
         <td>Ration kits, food</td>
         <td>Pan India</td>
        </tr>
        <tr class="mumbai homeless food">
         <td>Mumbai Roti Bank <br /><span style="font-size:0.8em"> [<a href="https://rotibankfoundation.org/">Go To Page</a>] [<a href="#mumbai-roti-bank">Details</a>]</span></td>
         <td>Homeless persons</td>
         <td>Food</td>
         <td>Mumbai</td>
        </tr>
        <tr class="mumbai delhi wage-workers migrant-workers cash">
         <td>Cash Relief <br /><span style="font-size:0.8em"> [<a href="http://www.cashrelief.org/covid-relief/">Go To Page</a>] [<a href="#cash-relief">Details</a>]</span></td>
         <td>Daily wage workers, migrant workers, slum dwellers</td>
         <td>Cash</td>
         <td>Mumbai, Jaipur, Delhi, Kanpur, Madhya Pradesh</td>
        </tr>
        <tr class="other-loc wage-workers food">
         <td>Maruti Veer Jawan Trust <br /><span style="font-size:0.8em"> [<a href="https://www.instagram.com/marutiveerjawantrust/">Go To Page</a>] [<a href="#maruti-veer-jawan-trust">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Food</td>
         <td>Surat</td>
        </tr>
        <tr class="other-loc other-ben ration">
         <td>Grace Banu <br /><span style="font-size:0.8em"> [<a href="https://milaap.org/fundraisers/trnsgndrrelieftoothukudi">Go To Page</a>] [<a href="#grace-banu">Details</a>]</span></td>
         <td>Trans persons</td>
         <td>Ration kits</td>
         <td>Tuticorin</td>
        </tr>
        <tr class="other-loc wage-workers cash ration">
         <td>Gurgaon Nagrik Ekta Manch <br /><span style="font-size:0.8em"> [<a href="https://www.ourdemocracy.in/Campaign/GurgaonDailyWageWorkers">Go To Page</a>] [<a href="#gurgaon-nagrik-ekta-manch">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Ration kits, cash</td>
         <td>Gurgaon</td>
        </tr>
        <tr class="delhi wage-workers migrant-workers ration food">
         <td>KMC-Ramjas Collective <br /><span style="font-size:0.8em"> [<a href="https://pages.razorpay.com/pl_EXfaOUPkVTIPla/view">Go To Page</a>] [<a href="#kmc-ramjas-collective">Details</a>]</span></td>
         <td>Daily wage workers, migrant workers</td>
         <td>Ration kits, food, safety kits</td>
         <td>Delhi</td>
        </tr>
        <tr class="india other-ben other-sup">
         <td>Urban Company <br /><span style="font-size:0.8em"> [<a href="https://www.urbancompany.com/uc-relief-fund">Go To Page</a>] [<a href="#urban-company">Details</a>]</span></td>
         <td>Gig workers</td>
         <td>Health insurance</td>
         <td>Pan India</td>
        </tr>
        <tr class="india other-ben cash">
         <td>CanKids KidsCan <br /><span style="font-size:0.8em"> [<a href="https://milaap.org/fundraisers/support-cankids-kidscan-1?community=10177">Go To Page</a>] [<a href="#cankids-kidscan">Details</a>]</span></td>
         <td>Children suffering from cancer</td>
         <td>Cash, safety kits</td>
         <td>Pan India</td>
        </tr>
        <tr class="india wage-workers cash">
         <td>India Care Covid <br /><span style="font-size:0.8em"> [<a href="https://docs.google.com/forms/d/1g0bfQT9YLH7RMsyG0zqof3amAlE9PzPk5kaRcTZLUgE">Go To Page</a>] [<a href="#india-care-covid">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Cash</td>
         <td>Pan India</td>
        </tr>
        <tr class="other-loc wage-workers ration">
         <td>Giweaway Foundation <br /><span style="font-size:0.8em"> [<a href="https://pages.razorpay.com/pl_EXJCTralOep9xu/view">Go To Page</a>] [<a href="#giweaway-foundation">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Ration kits</td>
         <td>Tamil Nadu, Karnataka, UP</td>
        </tr>
        <tr class="delhi wage-workers ration">
         <td>Young India Fellows <br /><span style="font-size:0.8em"> [<a href="https://milaap.org/fundraisers/support-saloni-6?">Go To Page</a>] [<a href="#young-india-fellows">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Ration kits</td>
         <td>Delhi</td>
        </tr>
        <tr class="other-loc trash-pickers ration sanitation">
         <td>Centre For Applied Research and Peoples Engagement <br /><span style="font-size:0.8em"> [<a href="https://www.ketto.org/fundraiser/support-our-kachra-vechaks-in-the-covid-times?payment=form">Go To Page</a>] [<a href="#centre-for-applied-research-and-peoples-engagement">Details</a>]</span></td>
         <td>Sanitation workers, waste pickers</td>
         <td>Ration kits, soap</td>
         <td>Aurangabad</td>
        </tr>
        <tr class="other-loc wage-workers trash-pickers ration sanitation">
         <td>Sarvahitey <br /><span style="font-size:0.8em"> [<a href="https://www.sarvahitey.org/donate">Go To Page</a>] [<a href="#sarvahitey">Details</a>]</span></td>
         <td>Waste pickers, daily wage workers</td>
         <td>Ration kits, soap, medicines</td>
         <td>Gurgaon</td>
        </tr>
        <tr class="india wage-workers ration sanitation">
         <td>Samarpann <br /><span style="font-size:0.8em"> [<a href="https://samarpann.org.in/donation/">Go To Page</a>] [<a href="#samarpann">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Ration kits, sanitation kits</td>
         <td>Pan India</td>
        </tr>
        <tr class="mumbai wage-workers homeless domestic-workers ration ppe">
         <td>Drona Foundation <br /><span style="font-size:0.8em"> [<a href="https://www.facebook.com/pg/dronafoundation/posts/">Go To Page</a>] [<a href="#drona-foundation">Details</a>]</span></td>
         <td>Daily wage workers, domestic workers, gig workers, homeless persons</td>
         <td>Ration kits, Personal Protective Equipment (PPE)</td>
         <td>Mumbai, Pune</td>
        </tr>
        <tr class="other-loc wage-workers ration">
         <td>CARD <br /><span style="font-size:0.8em"> [<a href="https://pages.razorpay.com/pl_CTMN9rvsgOwage/view">Go To Page</a>] [<a href="#card">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Ration kits</td>
         <td>Nagpur</td>
        </tr>
        <tr class="other-loc wage-workers ration sanitation">
         <td>Richa Malik (Personal Campaign) <br /><span style="font-size:0.8em"> [<a href="https://www.ketto.org/fundraiser/daily-wage-workers-and-artisans-in-up-need-food-and-basic-essentials?payment=form">Go To Page</a>] [<a href="#richa-malik-personal-campaign">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Ration kits, soap</td>
         <td>Uttar Pradesh</td>
        </tr>
        <tr class="bangalore wage-workers food">
         <td>Feed My Bangalore <br /><span style="font-size:0.8em"> [<a href="https://pages.razorpay.com/feedmybangalore">Go To Page</a>] [<a href="#feed-my-bangalore">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Food</td>
         <td>Bangalore</td>
        </tr>
        <tr class="other-loc wage-workers ration">
         <td>Sphoorti Foundation <br /><span style="font-size:0.8em"> [<a href="https://donatekart.com/Sphoorti/Sphoorti-corona-relief">Go To Page</a>] [<a href="#sphoorti-foundation">Details</a>]</span></td>
         <td>Daily wage workers</td>
         <td>Ration kits</td>
         <td>Hyderabad</td>
        </tr>
        <tr class="other-loc wage-workers cash">
         <td>Milaan Foundation <br /><span style="font-size:0.8em"> [<a href="https://milaap.org/fundraisers/support-milaan-foundation">Go To Page</a>] [<a href="#milaan-foundation">Details</a>]</span></td>
         <td>Daily wage workers (women)</td>
         <td>Cash</td>
         <td>Uttar Pradesh</td>
        </tr>
  </tbody>
</table>

<section class='page-em' style="padding:0.5em;margin-top:5%;padding:5%">
<a class="btn _reset_filter ibtn" style="display:inline-block;text-align:center;text-decoration:none" id="_view_filter">View Filters</a>
</section>

<section class='page-em share-links' style="padding-top:2.5%">

  <!-- Sharingbutton Facebook -->
  <a class="resp-sharing-button__link" href="https://facebook.com/sharer/sharer.php?u=https%3A%2F%2Findiacovidrelief.github.io%2F" target="_blank" rel="noopener" aria-label="">
    <div class="resp-sharing-button resp-sharing-button--facebook resp-sharing-button--small"><div aria-hidden="true" class="resp-sharing-button__icon resp-sharing-button__icon--solid">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M18.77 7.46H14.5v-1.9c0-.9.6-1.1 1-1.1h3V.5h-4.33C10.24.5 9.5 3.44 9.5 5.32v2.15h-3v4h3v12h5v-12h3.85l.42-4z"/></svg>
      </div>
    </div>
  </a>

  <!-- Sharingbutton Twitter -->
  <a class="resp-sharing-button__link" href="https://twitter.com/intent/tweet/?text=COVID-19%20Relief%20Efforts%20in%20India.%20A%20list%20of%20initiatives%20to%20support%20vulnerable%20groups%20during%20the%20COVID-19%20pandemic%20and%20national%20lockdown.&amp;url=https%3A%2F%2Findiacovidrelief.github.io%2F" target="_blank" rel="noopener" aria-label="">
    <div class="resp-sharing-button resp-sharing-button--twitter resp-sharing-button--small"><div aria-hidden="true" class="resp-sharing-button__icon resp-sharing-button__icon--solid">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M23.44 4.83c-.8.37-1.5.38-2.22.02.93-.56.98-.96 1.32-2.02-.88.52-1.86.9-2.9 1.1-.82-.88-2-1.43-3.3-1.43-2.5 0-4.55 2.04-4.55 4.54 0 .36.03.7.1 1.04-3.77-.2-7.12-2-9.36-4.75-.4.67-.6 1.45-.6 2.3 0 1.56.8 2.95 2 3.77-.74-.03-1.44-.23-2.05-.57v.06c0 2.2 1.56 4.03 3.64 4.44-.67.2-1.37.2-2.06.08.58 1.8 2.26 3.12 4.25 3.16C5.78 18.1 3.37 18.74 1 18.46c2 1.3 4.4 2.04 6.97 2.04 8.35 0 12.92-6.92 12.92-12.93 0-.2 0-.4-.02-.6.9-.63 1.96-1.22 2.56-2.14z"/></svg>
      </div>
    </div>
  </a>

  <!-- Sharingbutton E-Mail -->
  <a class="resp-sharing-button__link" href="mailto:?subject=COVID-19%20Relief%20Efforts%20in%20India.%20A%20list%20of%20initiatives%20to%20support%20vulnerable%20groups%20during%20the%20COVID-19%20pandemic%20and%20national%20lockdown.&amp;body=https%3A%2F%2Findiacovidrelief.github.io%2F" target="_self" rel="noopener" aria-label="">
    <div class="resp-sharing-button resp-sharing-button--email resp-sharing-button--small"><div aria-hidden="true" class="resp-sharing-button__icon resp-sharing-button__icon--solid">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M22 4H2C.9 4 0 4.9 0 6v12c0 1.1.9 2 2 2h20c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zM7.25 14.43l-3.5 2c-.08.05-.17.07-.25.07-.17 0-.34-.1-.43-.25-.14-.24-.06-.55.18-.68l3.5-2c.24-.14.55-.06.68.18.14.24.06.55-.18.68zm4.75.07c-.1 0-.2-.03-.27-.08l-8.5-5.5c-.23-.15-.3-.46-.15-.7.15-.22.46-.3.7-.14L12 13.4l8.23-5.32c.23-.15.54-.08.7.15.14.23.07.54-.16.7l-8.5 5.5c-.08.04-.17.07-.27.07zm8.93 1.75c-.1.16-.26.25-.43.25-.08 0-.17-.02-.25-.07l-3.5-2c-.24-.13-.32-.44-.18-.68s.44-.32.68-.18l3.5 2c.24.13.32.44.18.68z"/></svg>
      </div>
    </div>
  </a>

  <!-- Sharingbutton LinkedIn -->
  <a class="resp-sharing-button__link" href="https://www.linkedin.com/shareArticle?mini=true&amp;url=https%3A%2F%2Findiacovidrelief.github.io%2F&amp;title=COVID-19%20Relief%20Efforts%20in%20India.%20A%20list%20of%20initiatives%20to%20support%20vulnerable%20groups%20during%20the%20COVID-19%20pandemic%20and%20national%20lockdown.&amp;summary=COVID-19%20Relief%20Efforts%20in%20India.%20A%20list%20of%20initiatives%20to%20support%20vulnerable%20groups%20during%20the%20COVID-19%20pandemic%20and%20national%20lockdown.&amp;source=https%3A%2F%2Findiacovidrelief.github.io%2F" target="_blank" rel="noopener" aria-label="">
    <div class="resp-sharing-button resp-sharing-button--linkedin resp-sharing-button--small"><div aria-hidden="true" class="resp-sharing-button__icon resp-sharing-button__icon--solid">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M6.5 21.5h-5v-13h5v13zM4 6.5C2.5 6.5 1.5 5.3 1.5 4s1-2.4 2.5-2.4c1.6 0 2.5 1 2.6 2.5 0 1.4-1 2.5-2.6 2.5zm11.5 6c-1 0-2 1-2 2v7h-5v-13h5V10s1.6-1.5 4-1.5c3 0 5 2.2 5 6.3v6.7h-5v-7c0-1-1-2-2-2z"/></svg>
      </div>
    </div>
  </a>

  <!-- Sharingbutton WhatsApp -->
  <a class="resp-sharing-button__link" href="whatsapp://send?text=COVID-19%20Relief%20Efforts%20in%20India.%20A%20list%20of%20initiatives%20to%20support%20vulnerable%20groups%20during%20the%20COVID-19%20pandemic%20and%20national%20lockdown.%20https%3A%2F%2Findiacovidrelief.github.io%2F" target="_blank" rel="noopener" aria-label="">
    <div class="resp-sharing-button resp-sharing-button--whatsapp resp-sharing-button--small"><div aria-hidden="true" class="resp-sharing-button__icon resp-sharing-button__icon--solid">
      <svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 24 24"><path d="M20.1 3.9C17.9 1.7 15 .5 12 .5 5.8.5.7 5.6.7 11.9c0 2 .5 3.9 1.5 5.6L.6 23.4l6-1.6c1.6.9 3.5 1.3 5.4 1.3 6.3 0 11.4-5.1 11.4-11.4-.1-2.8-1.2-5.7-3.3-7.8zM12 21.4c-1.7 0-3.3-.5-4.8-1.3l-.4-.2-3.5 1 1-3.4L4 17c-1-1.5-1.4-3.2-1.4-5.1 0-5.2 4.2-9.4 9.4-9.4 2.5 0 4.9 1 6.7 2.8 1.8 1.8 2.8 4.2 2.8 6.7-.1 5.2-4.3 9.4-9.5 9.4zm5.1-7.1c-.3-.1-1.7-.9-1.9-1-.3-.1-.5-.1-.7.1-.2.3-.8 1-.9 1.1-.2.2-.3.2-.6.1s-1.2-.5-2.3-1.4c-.9-.8-1.4-1.7-1.6-2-.2-.3 0-.5.1-.6s.3-.3.4-.5c.2-.1.3-.3.4-.5.1-.2 0-.4 0-.5C10 9 9.3 7.6 9 7c-.1-.4-.4-.3-.5-.3h-.6s-.4.1-.7.3c-.3.3-1 1-1 2.4s1 2.8 1.1 3c.1.2 2 3.1 4.9 4.3.7.3 1.2.5 1.6.6.7.2 1.3.2 1.8.1.6-.1 1.7-.7 1.9-1.3.2-.7.2-1.2.2-1.3-.1-.3-.3-.4-.6-.5z"/></svg>
      </div>
    </div>
  </a>

</section>

**Note**:
- This is not an exhaustive list of initiatives in India. If you know or are organising such an initiative, please submit your details on *[this form](https://forms.gle/6uLcxdyhKToDQoc68)*.
- While the citizen-led campaigns need your financial support and encouragement to continue their noble efforts, the central and state governments are also accepting donations for their respective relief funds. A list of all such funds can be found on [this link](https://www.investindia.gov.in/bip/resources/state-and-national-relief-funds-accepting-donations-covid-19).


<section class='page-em share-links' style="margin:0px">

</section>


<br>

## Brief details

### [Give India - Support Families](https://indiafightscorona.giveindia.org/support-families/)
Beneficiaries are daily wage workers' families, whose profiles are sourced from trusted non-profit partners, including Aadhar & Ration card details. Funds are disbursed through non-profit partners, adhering to GiveIndia's governance mechanisms.

- Cities/States Covered: Pan India
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: Yes

### [Zomato India](https://www.zomato.com/blog/feed-daily-wager)
This initiative, called "Feed the Daily Wager", is a joint endeavor of Zomato and Grofers. It aims to deliver ration kits to families of daily wage workers via local NGOs across 26 cities. Each ration kit, costing Rs. 500, is sufficient to sustain a family of 5 for a week.

- Cities/States Covered: Pan India
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: Yes

### [Kanaga (Personal Campaign)](https://milaap.org/fundraisers/support-kanaga)
The trans community is one of the worst affected by the ongoing crisis, with most of them relying on the unorganized sector to earn their daily wages. This initiative aims to help a group of 100 people in Chennai, by providing them the basic provisions like food, salt, masks, drinking water, soap and medical supplies, to get through these testing times.

- Cities/States Covered: Chennai
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: No

### [Paigam](https://pages.razorpay.com/pl_EW6B2AlIPZz41X/view)
In times of unprecedented crisis, vulnerable communities like the waste pickers are the first to be forgotten. Paigam, in partnership with Basti Suraksha Manch is trying to provide safety kits (mask + hand sanitizer) and minimum income support for the waste pickers.

- Cities/States Covered: Delhi
- Payment Modes Available: Cards, Net Banking, UPI
- 80G Eligible: No

### [Goonj - Rahat COVID-19](https://goonj.org/support-covid-19-affected/)
The initiative wants to bring comprehensive family kits of essentials – largely dry ration, personal care material to over a million people (200k families) in areas well known for migration and in geographies they are already working in.

- Cities/States Covered: Pan India
- Payment Modes Available: Cards, Net Banking, UPI
- 80G Eligible: No

### [Elixir Foundation](https://pages.razorpay.com/pl_EW357Eyk0tOlaa/view)
Elixir Foundation along with other organisations is raising funds to provide groceries to daily wage workers, old age home residents and those in shelters in Ahmedabad and the rest of Gujarat.

- Cities/States Covered: Ahmedabad
- Payment Modes Available: Cards, Net Banking, UPI
- 80G Eligible: Yes

### [SAFA Society](https://pages.razorpay.com/Covid19Relief)
The initiative is providing basic ration and hygiene supply kits to those in dire need. Daily wagers, migrant workers, street children, single parents and beggars are worst hit due to the lockdown.

- Cities/States Covered: Hyderabad, North Karnataka, Bangalore, Chennai
- Payment Modes Available: Cards, Net Banking, UPI
- 80G Eligible: Yes

### [Venkat Iyer (Personal Campaign)](https://milaap.org/fundraisers/support-venkat-iyer)
As the crisis grows, the people most affected by it will be those living in India’s unorganised sector of the Indian economy. It is here that we can all extend our help to such affected persons in turn help their families by providing food and medicine., starting with a pilot in Delhi

- Cities/States Covered: Delhi, Agra, Lucknow, Kanpur, Varanasi, Bangalore, Mumbai, Surat, Malegaon
- Payment Modes Available: Cards, Net Banking, UPI
- 80G Eligible: No

### [Uday Foundation](https://www.udayfoundation.org/coronavirus-disease-covid-19/?fbclid=IwAR05051YKouzPYii14L2CNPnS-I80PLgvAj_tw4NUuFxcDIlGl8AS6ft7FA)
Uday foundation is collecting donations to sponsor distribution of sanitization and food kits to homeless individuals and families. The kits will cover one month worth of supplies for individuals

- Cities/States Covered: Pan India
- Payment Modes Available: Cards, Net Banking, Wallets
- 80G Eligible: Yes

### [Delhi Youth Welfare Association](https://www.ourdemocracy.in/Campaign/covid19Delhi)
This campaign aims to raise funds for daily wagers who don't have the luxury of working from home and are struggling to survive during the Covid 19 pandemic.

- Cities/States Covered: Delhi
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: No

### [YUVA](https://milaap.org/fundraisers/support-youth-for-unity-and-voluntary-action)
The campaign named ‘Together We Can’ aims raise funds as well as support in kind (non-persihable food items) to offer emergency relief food supplies to the urban poor, starting with the most marginalised families first. Covering approximately 1500 families currently, and adding more areas under their coverage regularly, they are distributing ration packages worth Rs. 600 to support weekly requirements of a family.

- Cities/States Covered: Mumbai
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: Yes

### [Making The Difference](https://pages.razorpay.com/pl_EUwNKcGMyXoosk/view)
Making The Difference, a Mumbai based NGO, is collecting funds to disburse basic ration and support food requirements of the under privileged.

- Cities/States Covered: Mumbai
- Payment Modes Available: Cards, Net Banking, UPI
- 80G Eligible: No

### [Help for Sex Workers (Personal Campaign)](https://www.ketto.org/fundraiser/covid-19-relief-fund-for-sex-workers-in-kamathipura?payment=form)
In times like these, it is vital for us as a community to come together and help the marginalized sections of society. While there are many who are being deprived of basic necessities owing to the pandemic that has become a common enemy for the global population, there are huge red-light areas in Mumbai that are home to almost 5000 sex workers. This initiative aims to provide basic necessities to these workers.

- Cities/States Covered: Mumbai
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: No

### [Hasiru Dala](http://hasirudala.in/news/wastepickers-and-covid19/)
Hasiru Dala has identified ~1000 vulnerable wastepickers’ families (no BPL/ration card, no public housing, no predictable income) in 6 cities/towns in Karnataka (Bengaluru, Mysuru, Tumakuru, Davanagere, Hubli/Dharawad) who need immediate support.

- Cities/States Covered: Bangalore, Mysuru, Tumakuru, Davanagere, Hubli, Dharawad
- Payment Modes Available: Direct Bank Transfer
- 80G Eligible: Yes

### [Sangama](https://www.ourdemocracy.in/Campaign/supportsangama)
Sangama plans to provide 350 family units of sexworkers and 150 transpeople whose livelihoods also depend on begging, with a monthly pakage of Rs 2000,  for the months of April and May 2020. While half of this will be given in cash, the other half will be given as essential food rations for the home

- Cities/States Covered: Karnataka
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: Yes

### [Chhoti Si Aasha](https://www.ourdemocracy.in/Campaign/Covid19reliefCHD)
This campaign aims at providing relief to daily-wage workers in Chandigarh, Mohali and Panchkula who are affected by the lockdown.

- Cities/States Covered: Chandigarh, Mohali, Panchkula
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: No

### [Meraj Foundation](https://www.ourdemocracy.in/Campaign/MerajFoundation)
In regard to the recent COVID-19 LOCKDOWN in Delhi, many people are left stranded without money who are dependent on daily wages.

For these people we at *Meraj Foundation* is planning to distribute Essential Items Pack till 31st March 2020.


- Cities/States Covered: Delhi
- Payment Modes Available: UPI, Wallets
- 80G Eligible: No

### [Kashtakari Panchayat](https://www.ourdemocracy.in/Campaign/Covid19Pune)
While the entire nation is at home during this lockdown due to COVID-19, the waste-pickers of Pune and Pimpri-Chinchwad are still providing waste collection services and maintaining the city's health and hygiene.

Waste-pickers cannot work from home. They collect the city's waste and protect our health. Please help them protect theirs. Contribute now.

- Cities/States Covered: Pune
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: No

### [Upay](https://www.upay.org.in/crowd-fund/Help-us-fight-corona-and-feed-the-homeless)
We are targeting to support at least 200 meals per day to the homeless people and 15 days ration support to at least 500 families.

Ration support will cost us Rs. 900 per family and each meal would cost Rs. 15.

- Cities/States Covered: Pan India
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: Yes

### [Mumbai Roti Bank](https://rotibankfoundation.org/)
As pavement dwellers and the homeless in the city struggle to arrange food in the present lockdown, Mumbai Police has tied up with Mumbai Roti Bank for providing meals to homeless people in Mumbai.

- Cities/States Covered: Mumbai
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: Yes

### [Cash Relief](http://www.cashrelief.org/covid-relief/)
We identify people in need and enrol them into the Cashrelief program. We then transfer money into the bank account of oldest working women in the family. Research is conducted to find out what works, what doesn’t and improve our offerings.

- Cities/States Covered: Mumbai, Jaipur, Delhi, Kanpur, Madhya Pradesh
- Payment Modes Available: Direct Bank Transfer
- 80G Eligible: Yes

### [Maruti Veer Jawan Trust](https://www.instagram.com/marutiveerjawantrust/)
The trust runs a community kitchen that has been providing meals to 2500 daily wage workers in Surat. But with the lockdown the number of people struggling for food has been increasing steadily, and they need monetary support to keep feeding the less privileged.

- Cities/States Covered: Surat
- Payment Modes Available: Direct Bank Transfer
- 80G Eligible: No

### [Grace Banu](https://milaap.org/fundraisers/trnsgndrrelieftoothukudi)
Rural transgender persons in Thoothukudi (Tuticorin), Tamil Nadu are heavily dependent on begging as their only source of livelihood.
We are a collective of transgender people in Thoothukudi (Tuticorin), Tamil Nadu, and are trying to raise funds for at least 150 transgender persons for their basic provisions like food, oil, salt & drinking water so that they can also stay at home this month, and stay safe.

- Cities/States Covered: Tuticorin
- Payment Modes Available: Direct Bank Transfer, UPI, Wallets
- 80G Eligible: No

### [Gurgaon Nagrik Ekta Manch](https://www.ourdemocracy.in/Campaign/GurgaonDailyWageWorkers)
Gurgaon Nagrik Ekta Manch appeals to you to donate generously and help us provide rations to daily wage workers and their families in Gurgaon.

- Cities/States Covered: Gurgaon
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: No

### [KMC-Ramjas Collective](https://pages.razorpay.com/pl_EXfaOUPkVTIPla/view)
We are working with a network of local community organizers who have been engaged in providing relief materials in these localities since the outbreak of violence in North East Delhi in February, 2020 and the impending lock-down due to COVID-19.

- Cities/States Covered: Delhi
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: No

### [Urban Company](https://www.urbancompany.com/uc-relief-fund)
Urban Company (formerly UrbanCIap) is partnering with Srinidhi Foundation (an established charitable trust) to set up a relief fund to provide sustenance support to deserving gig workers and their families over the next few months, till the COVID-19 situation comes back to normalcy.

- Cities/States Covered: Pan India
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: Yes

### [CanKids KidsCan](https://milaap.org/fundraisers/support-cankids-kidscan-1?community=10177)
CanKids KidsCan, an NGO working in the space of childhood cancer care is looking to raise funds for sourcing and purchase of higher quality N95 masks, gloves, other protection equipment and sanitizers for children, hospital staff and support teams in hospitals; Providing accommodation alternatives and food supplies; Providing reimbursement for diagnostic tests undertaken locally by patient families

- Cities/States Covered: Pan India
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: Yes

### [India Care Covid](https://docs.google.com/forms/d/1g0bfQT9YLH7RMsyG0zqof3amAlE9PzPk5kaRcTZLUgE)
India Care Collective, a COVID-19 relief effort, is a group of citizens with a proven background of social service, who are working together to help families impacted because of wage loss situations arising due to the coronavirus pandemic.

- Cities/States Covered: Pan India
- Payment Modes Available: Net Banking, UPI, Wallets
- 80G Eligible: No

### [Giweaway Foundation](https://pages.razorpay.com/pl_EXJCTralOep9xu/view)
We would be procuring groceries and essential items for the families of the daily wage workers who have lost their daily livelihood during the nation wide lockdown of Corona Virus. Your contribution will go in fulfilling their daily ration required for their survival.

- Cities/States Covered: Tamil Nadu, Karnataka, UP
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: No

### [Young India Fellows](https://milaap.org/fundraisers/support-saloni-6?)
We are collecting funds that are being used to supply food (wheat, rice, daal, and oil) and soap to families facing the worst backlash in this 21-day lockdown. We are targeting a community of at least 1000 families. We will expand as and when we get to know more communities in need.

- Cities/States Covered: Delhi
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: No

### [Centre For Applied Research and Peoples Engagement](https://www.ketto.org/fundraiser/support-our-kachra-vechaks-in-the-covid-times?payment=form)
In this time of crisis, while most of us can be indoors and work from home, we have a force of over 200 waste pickers from the informal sector who step out every day to earn a livelihood, Support our Kachra Vechaks in Aurangabad by providing essential household supplies.

- Cities/States Covered: Aurangabad
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: Yes

### [Sarvahitey](https://www.sarvahitey.org/donate)
The slum at Wazirabad is one of poorest of the poor. They have supplies that can barely last a week. After that they have no recourse. Therefore we have started a campaign to support the 100 families residing in that slum. For more info, kindly see https://milaap.org/fundraisers/support-aman-52

- Cities/States Covered: Gurgaon
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: Yes

### [Samarpann](https://samarpann.org.in/donation/)
Mumbai-based Samarpannorg run by doctors & IRS officers, is providing food and sanitation kits to daily wagers & the most vulnerable who are the worst hit by COVID-19 during #21daylockdown ‬ In their endless battle of daily survival, let hunger be one less thing they fight

- Cities/States Covered: Pan India
- Payment Modes Available: Net Banking
- 80G Eligible: No

### [Drona Foundation](https://www.facebook.com/pg/dronafoundation/posts/)
Drona Foundation is one of the grass-root level organisations working towards the welfare of children, youth and women. We have seen long queues for ration and many who go hungry as a result. We have taken this initiative to help the needy in Dharavi.

- Cities/States Covered: Mumbai, Pune
- Payment Modes Available: Net Banking
- 80G Eligible: No

### [CARD](https://pages.razorpay.com/pl_CTMN9rvsgOwage/view)
During this COVID-19 crisis, we are all facing an issue to get groceries during this lockdown. But the poor wage workers who have no daily wage anymore are not even able to afford the staple groceries needed as they are laid off. CARD will be ensuring smooth distribution with all hygienic measures in place and ultimately ensure that no one falls short on their basic pantry needs - especially the poor in the Nagpur region where we are servicing currently.

- Cities/States Covered: Nagpur
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: Yes

### [Richa Malik (Personal Campaign)](https://www.ketto.org/fundraiser/daily-wage-workers-and-artisans-in-up-need-food-and-basic-essentials?payment=form)
We are getting food packets (10 kilo flour, 3 kilo rice, sugar, dal, salt, cooking oil and soap) made for as many people there as we can and handing them out from the workshop. Each food packet costs around INR 1100, one food packet would last 10-12 days (15 on a stretch) for these families.

- Cities/States Covered: Uttar Pradesh
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: Yes

### [Feed My Bangalore](https://pages.razorpay.com/feedmybangalore)
An initiative to feed the countless families of daily wage earners.

- Cities/States Covered: Bangalore
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: No

### [Sphoorti Foundation](https://donatekart.com/Sphoorti/Sphoorti-corona-relief)
Sphoorti Foundation is a children’s home. With a mission to change children’s’ lives, they work for underprivileged children - orphaned, abandoned, destitute and other vulnerable groups.

- Cities/States Covered: Hyderabad
- Payment Modes Available: Cards, Net Banking, UPI, Wallets
- 80G Eligible: No

### [Milaan Foundation](https://milaap.org/fundraisers/support-milaan-foundation)
Milaan Foundation along with its 12 grassroots partners are starting the "COVID 19 - Emergency Support Program" to support people and the field level health workers cope it its adverse impact. Our major geographical focus for the intervention is Uttar Pradesh.

- Cities/States Covered: Uttar Pradesh
- Payment Modes Available: Cards, Direct Bank Transfer, Net Banking, UPI, Wallets
- 80G Eligible: Yes




<br>
<hr>
**Disclaimer**: We are not associated with any of the initiatives mentioned on this page. Our objective is to aggregate various support programs and campaigns to hopefully provide them additional visibility, and to provide potential donors with concise information.

<script>

var location_filter = undefined, helptype_filter = undefined, people_filter = undefined;

function runLocationFilter(e) {
  var select = e.target;

  var value = select.value;
  if (location_filter === value || value === "all") {
    location_filter = undefined;
  } else {
    location_filter = value;
  }

  applyFilter();
}

function runPeopleFilter(e) {
  var select = e.target;

  var value = select.value;
  if (people_filter === value || value === "all") {
    people_filter = undefined;
  } else {
    people_filter = value;
  }

  applyFilter();
}

function runHelptypeFilter(e) {
  var select = e.target;

  var value = select.value;
  if (helptype_filter === value || value === "all") {
    helptype_filter = undefined;
  } else {
    helptype_filter = value;
  }

  applyFilter();
}

function runAllFilter(e) {
  e.preventDefault();
  var btn = e.target;

  helptype_filter = undefined;
  location_filter = undefined;
  people_filter = undefined;

  var peopleFilter = document.getElementById('_people_filter');
  peopleFilter.selectedIndex = 0;

  var locationFilter = document.getElementById('_location_filter');
  locationFilter.selectedIndex = 0;

  var helptypeFilter = document.getElementById('_helptype_filter');
  helptypeFilter.selectedIndex = 0;

  applyFilter();
}

function scrollToTable(){
  var ui_elem = document.getElementById("main-table");
  ui_elem.scrollIntoView({"behavior": "smooth"});
}

function scrollToFilter(){
  var ui_elem = document.getElementById("table-filter");
  ui_elem.scrollIntoView({"behavior": "smooth"});
}

function applyFilter() {
  var main_table = document.getElementById("main-table");
  var table_body = main_table.getElementsByTagName("tbody")[0];
  var rows = table_body.getElementsByTagName("tr");
  document.getElementById("no-rows-found").style.display = "none";

  var row_found = false;
  for (let row of rows) {
    if (row.classList.contains("no-rows-found")) {
      continue;
    };
    row.style.display = "table-row";

    if (people_filter && !row.classList.contains(people_filter)) {
      row.style.display = "none";
    }

    if (helptype_filter && !row.classList.contains(helptype_filter)) {
      row.style.display = "none";
    }

    if (location_filter && !row.classList.contains(location_filter)) {
      row.style.display = "none";
    }

    if (row.style.display == "table-row") {
      row_found = true;
    }
  }

  if (!row_found) {
    document.getElementById("no-rows-found").style.display = "table-row";
  }

}

var locationFilter = document.getElementById('_location_filter');
locationFilter.onchange = runLocationFilter;

var helptypeFilter = document.getElementById('_helptype_filter');
helptypeFilter.onchange = runHelptypeFilter;

var peopleFilter = document.getElementById('_people_filter');
peopleFilter.onchange = runPeopleFilter;


resetFilterButton = document.getElementById('_reset_filter');
resetFilterButton.onclick = runAllFilter;

viewFilterButton = document.getElementById('_view_filter');
viewFilterButton.onclick=scrollToFilter;

function domain(url) {
    return url.replace('http://','').replace('https://','').split('/')[0];
}

function isExternalLink (url) {
  return domain(location.href) !== domain(url);
}

var links = document.getElementsByTagName('a');
for (link of links) {
  var href = link.getAttribute('href');
  if (href && isExternalLink(href) && href.indexOf('#') !== 0) {
    link.setAttribute('onclick', "captureOutboundLink('" + href + "'); return false;");
  }
}

document.getElementById("no-rows-found").style.display = "none";

</script>
