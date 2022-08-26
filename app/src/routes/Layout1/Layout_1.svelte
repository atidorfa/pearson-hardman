<script>
  import Navbar from '../../Components/Navbar.svelte'
  import HomeSection from './HomeSection.svelte'
  import Service from '../../Components/Service.svelte'
  import Feature from '../../Components/Feature.svelte'
  import Testimonial from '../../Components/Testimonial.svelte'
  import Team from '../../Components/Team.svelte'
  import Faq from '../../Components/Faq.svelte'
  import Pricing from '../../Components/Pricing.svelte'
  import Contact from '../../Components/Contact.svelte'
  import Footer from '../../Components/Footer.svelte'

  import data from '../../Data/data.js'

</script>

<!-- STRAT NAVBAR -->
  <Navbar extraclass="" />
<!-- END NAVBAR -->

<!-- START HOME -->
<HomeSection />
<!-- END HOME -->

<!-- START TEAM-->
<Team teamData={data.TEAM_DATA} />
<!-- END TEAM -->

<!-- START FETURES -->
<Feature featureData={data.FEATURES_DATA} />
<!-- END FEATURES -->

<!-- START SERVICES -->
<Service serviceData={data.SERVICE_DATA} />
<!-- END SERVICES -->

<!-- STRAT TESTIMONIAL -->
<Testimonial testimonialData={data.TESATIMONIAL_DATA} />
<!-- END TESTIMONIAL -->


<!-- START SUPPORT -->
<Faq faqData={data.FAQDATA} ctaData={data.CTA_SECTION} />
<!-- END SUPPORT -->

<!-- START PRICING -->
<Pricing pricingData={data.PRICING_DATA} />
<!-- END PRICING -->

<!-- CONTACT FORM START-->
<Contact contactData={data.CONTACTDATA} />
<!-- CONTACT FORM END-->

<!-- STRT FOOTER -->
<Footer />
<!-- END FOOTER -->