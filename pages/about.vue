<template>
  <div id="about-page" class="page-wrapper about-page content-page">
    <site-hero
      title="About Us"
      subtitle="Example About Page"
      image="/uploads/about-hero.jpg"
    ></site-hero>
    <main-section theme="sidebar-right">
      <template v-slot:default>
        <div class="content">
							<h1> Mission: Possible </h1>
							<p> People tend to think of countries and borders as immutable things that have been settled long ago.  <a href = "https://aeon.co/essays/the-end-of-a-world-of-nation-states-may-be-upon-us">But is that so?</a> Are individuals truly helpless agents in the tide of history and humankind dynamics? The Sovereignty Club aims to promote the understanding of how sovereignty and governance work in the context of global politics - so that you can actually make a difference. </p>
              <center>
              <h4> To join our mailing list just email Eduardo at edaveiga@caltech.edu and ask to be added. </h4>
              <h4> We meet every Wednesday at 6PM PST (and occasionally also at other times). </h4>
              <h4> Join us! It's fun. </h4>
              </center>

						<h2>Success(?) stories</h2>
						<p>Nowadays, starting a country doesn't have to (necessarily) involve a bloody, protracted civil war. Just look at these testimonials from world leaders just like you! </p>

						<h3>Liberland</h3>
							<p><span class="image left"><img src="images/liberland.png" alt="" width=300em/></span>
							In 2014, in an unclaimed patch of land between Serbia and Croatia, a savvy Czech politician created<a href=https://www.nytimes.com/2015/08/16/magazine/the-making-of-a-president.html> The World's Newest Country (maybe)</a>. But honestly he seems to be doing everything right and following proper international law, and both Serbia and Croatia said the land is not theirs, so there is an actual chance something interesting will happen.
							</p>


							<h3>Principality of Sealand</h3>
								<p><span class="image right"><a href="https://en.wikipedia.org/wiki/Principality_of_Sealand"><img src="images/sealand.jpg" alt="" width=300em/></a></span>
								Back in 1967 an astute Brit occupied an abandoned fortress built in international waters during World War 2 - and it remains in continuous occupation since then, unchallenged in it's claim to be a <a href="https://www.sealandgov.org/"> sovereign state.</a>
								</p>


							<h3>South Sudan</h3>
								<p><span class="image left"><a href="https://en.wikipedia.org/wiki/South_Sudan"><img src="images/south_sudan.png" alt="" width=300em/></a></span>
								In 2011, following a referendum, half of Sudan became a real, independent state, with UN membership and all. However, <a href="https://www.npr.org/sections/goatsandsoda/2017/07/08/535620121/unhappy-anniversary-south-sudan"> they are not doing any better than before they broke off from Sudan. </a> </span>
								</p>

							<h3>Catalonia</h3>
								<p><span class="image right"><a href="https://en.wikipedia.org/wiki/Catalan_independence_movement"><img src="images/catalonia.jpg" alt="" width=300em/></a></span>
								On 27 October 2017, following a referendum, the Government of Catalonia (until then an autonomous province of Spain on the border of France) unilaterally declared independence, and really pissed off the Spanish parliament. <a href="https://jacobinmag.com/2017/10/catalonia-independence-franco-spain-nationalism/"> It's basically a left wing Brexit that has been brewing for 600 years. </a>
								</p>

							<h3>Principality of Hutt River</h3>
								<p><span class="image left"><a href="https://en.wikipedia.org/wiki/Principality_of_Hutt_River"><img src="images/hutt_river.png" alt="" width=300em/></a></span>
								In 1970 a smart Aussie farmer pissed off at the government for enacting wheat production quotas seceded from the Commonwealth of Australia, <a href="http://www.principality-hutt-river.com/"> starting the Principality of Hutt River </a>. On 2 December 1977 the Principality declared war on Australia, notifying authorities of the cessation of hostilities several days later, and wrote to the Governor-General and asserted that "Sovereignty is automatic to a country undefeated in a state of war...and if the state of war is not recognized by the other party, once the notice is given then these conventions apply to their relations."</a>

								Despite solid legal grounding, <a href="http://www.abc.net.au/news/2017-06-16/hutt-river-province-decision-on-ato-fight/8624450"> friction with the Australian government continues to this day. </a> </p>

            <h2>By the way, we have a <a href="https://docs.google.com/document/d/1_2KZgRUbrxrfKcA5IiHkxdEK2Oe729vmSVcqMzSMovs/edit?usp=sharing"> constitution</a>, if you care.</h2>          
          
          
        </div>
      </template>

      <template v-slot:sidebar>
        <h3 class="subtitle is-4">
          Latest Posts
        </h3>
        <posts-grid :per-row="1" :number="2" />
      </template>
    </main-section>
  </div>
</template>
<script>
import QuoteCard from '~/components/cards/QuoteCard'
export default {
  head() {
    return {
      title: `About | ${this.$siteConfig.siteName}`
    }
  },
  components: { QuoteCard }
}
</script>
