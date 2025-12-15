<script lang="ts">
  import Navbar from '$lib/Navbar.svelte';
  import Footer from '$lib/Footer.svelte';
  import Button from '$lib/Button.svelte';
</script>

<div class="min-h-screen font-sans text-dark bg-white overflow-x-hidden">
  <Navbar />

  <!-- Hero Section -->
  <section class="pt-32 pb-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto text-center">
    <div class="mb-6">
      <span class="text-xs font-bold tracking-widest text-gray-500 uppercase">Coming Soon</span>
    </div>
    <h1 class="text-5xl md:text-7xl font-serif mb-6 leading-tight">
      Stop scrolling.<br class="hidden md:block" /> Start living.
    </h1>
    <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10 leading-relaxed">
      Transform scattered social plans into coordinated experiences. 
      Discover the best of your city with your crew—all in one place.
    </p>
    <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-20">
      <Button href="#waitlist" type="primary">Join Waitlist</Button>
      <Button href="mailto:hey@aaa.inc" type="outline">Get in Touch</Button>
    </div>

    <!-- Hero Image -->
    <div class="relative w-full max-w-5xl mx-auto rounded-2xl overflow-hidden shadow-2xl border border-gray-200 bg-gray-900 aspect-[16/9] mb-16">
      <img src="/generated/image-mixed-group-of-friends-walking-together--1765810733664-2.webp" alt="Friends exploring the city at night" class="w-full h-full object-cover" />
      <div class="absolute inset-0 bg-gradient-to-t from-black/60 via-transparent to-transparent"></div>
    </div>

    <!-- Social Proof -->
    <div class="text-center">
      <p class="text-sm text-gray-500 mb-6">Join thousands on the waitlist discovering their city differently</p>
    </div>
  </section>

  <!-- Problem Section -->
  <section class="py-20 bg-gray-50">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-3xl mx-auto">
        Your social life shouldn't feel like work
      </h2>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-16">
        <div class="bg-white p-8 rounded-2xl text-center border border-gray-200">
          <div class="text-5xl mb-4">📱</div>
          <div class="text-xl font-serif font-medium mb-2">Too many apps</div>
          <div class="text-sm text-gray-600">Scrolling through 5+ apps to find something worth doing</div>
        </div>
        <div class="bg-white p-8 rounded-2xl text-center border border-gray-200">
          <div class="text-5xl mb-4">💬</div>
          <div class="text-xl font-serif font-medium mb-2">Scattered plans</div>
          <div class="text-sm text-gray-600">Group chats that go nowhere, plans that never happen</div>
        </div>
        <div class="bg-white p-8 rounded-2xl text-center border border-gray-200">
          <div class="text-5xl mb-4">😴</div>
          <div class="text-xl font-serif font-medium mb-2">Event fatigue</div>
          <div class="text-sm text-gray-600">Overwhelmed by options, end up doing nothing</div>
        </div>
      </div>
    </div>
  </section>

  <!-- Solution Section -->
  <section class="bg-dark text-white py-24 overflow-hidden">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4">One app. Your crew.<br /> Endless possibilities.</h2>
      <p class="text-center text-gray-400 mb-16">Access transforms how you discover and coordinate social experiences.</p>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Feature 1 -->
        <div class="bg-gray-900 rounded-2xl p-8 border border-gray-800">
          <div class="w-12 h-12 bg-primary/20 rounded-full flex items-center justify-center mb-6">
            <svg class="w-6 h-6 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M21 21l-6-6m2-5a7 7 0 11-14 0 7 7 0 0114 0z"></path></svg>
          </div>
          <h3 class="text-xl font-serif mb-3">Curated Discovery</h3>
          <p class="text-gray-400 text-sm leading-relaxed">
            No more endless scrolling. We surface the best pop-ups, shows, and scenes happening in your city—handpicked, not algorithmic.
          </p>
        </div>

        <!-- Feature 2 -->
        <div class="bg-gray-900 rounded-2xl p-8 border border-gray-800">
          <div class="w-12 h-12 bg-primary/20 rounded-full flex items-center justify-center mb-6">
            <svg class="w-6 h-6 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M17 20h5v-2a3 3 0 00-5.356-1.857M17 20H7m10 0v-2c0-.656-.126-1.283-.356-1.857M7 20H2v-2a3 3 0 015.356-1.857M7 20v-2c0-.656.126-1.283.356-1.857m0 0a5.002 5.002 0 019.288 0M15 7a3 3 0 11-6 0 3 3 0 016 0zm6 3a2 2 0 11-4 0 2 2 0 014 0zM7 10a2 2 0 11-4 0 2 2 0 014 0z"></path></svg>
          </div>
          <h3 class="text-xl font-serif mb-3">Crew Coordination</h3>
          <p class="text-gray-400 text-sm leading-relaxed">
            Built for friend groups. See what your crew is into, coordinate plans effortlessly, and actually make things happen.
          </p>
        </div>

        <!-- Feature 3 -->
        <div class="bg-gray-900 rounded-2xl p-8 border border-gray-800">
          <div class="w-12 h-12 bg-primary/20 rounded-full flex items-center justify-center mb-6">
            <svg class="w-6 h-6 text-primary" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="2" d="M8 7V3m8 4V3m-9 8h10M5 21h14a2 2 0 002-2V7a2 2 0 00-2-2H5a2 2 0 00-2 2v12a2 2 0 002 2z"></path></svg>
          </div>
          <h3 class="text-xl font-serif mb-3">Unified Calendar</h3>
          <p class="text-gray-400 text-sm leading-relaxed">
            All your plans in one place. From underground shows to weekend markets—see what's happening and who's going.
          </p>
        </div>
      </div>
    </div>
  </section>

  <!-- How It Works Section -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4 max-w-2xl mx-auto">
        Designed for how you actually socialize
      </h2>
      <p class="text-center text-gray-600 mb-16 max-w-xl mx-auto">
        Access brings together everything you need to discover, coordinate, and experience your city with your crew.
      </p>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Card 1 -->
        <div class="bg-gray-50 rounded-3xl p-8 border border-gray-200 overflow-hidden relative group">
            <div class="mb-8">
                <h3 class="text-2xl font-serif mb-3">Offline-First Curation</h3>
                <p class="text-gray-600 text-sm leading-relaxed">Forget algorithms. Our team handpicks the best pop-ups, underground shows, art openings, and food scenes. Real experiences, not sponsored content.</p>
            </div>
            <div class="bg-white rounded-xl p-6 h-64 relative border border-gray-200 flex items-center justify-center">
                <div class="text-center space-y-4">
                    <div class="text-6xl">🎭</div>
                    <div class="text-sm font-medium text-gray-900">Curated by locals,<br />not algorithms</div>
                </div>
            </div>
        </div>

        <!-- Card 2 -->
        <div class="bg-gray-50 rounded-3xl p-8 border border-gray-200 overflow-hidden">
            <div class="mb-8">
                <h3 class="text-2xl font-serif mb-3">Crew-Based Planning</h3>
                <p class="text-gray-600 text-sm leading-relaxed">Create crews with your different friend groups. See what everyone's interested in, vote on plans, and coordinate without the endless back-and-forth.</p>
            </div>
            <div class="bg-white rounded-xl h-64 relative overflow-hidden flex items-center justify-center border border-gray-200">
                <div class="text-center space-y-4">
                    <div class="flex justify-center gap-2">
                        <div class="w-12 h-12 rounded-full bg-primary"></div>
                        <div class="w-12 h-12 rounded-full bg-gray-800"></div>
                        <div class="w-12 h-12 rounded-full bg-gray-400"></div>
                    </div>
                    <div class="text-sm font-medium text-gray-900">Your crews, unified</div>
                </div>
            </div>
        </div>

        <!-- Card 3 -->
        <div class="bg-gray-50 rounded-3xl p-8 border border-gray-200 overflow-hidden">
             <div class="mb-8">
                 <h3 class="text-2xl font-serif mb-3">City-Specific Discovery</h3>
                 <p class="text-gray-600 text-sm leading-relaxed">Every city has its own vibe. Access adapts to where you are, surfacing the scenes and experiences that matter in your location.</p>
             </div>
             <div class="h-64 bg-white rounded-xl p-6 relative border border-gray-200 flex items-center justify-center">
                <div class="text-center space-y-4">
                    <div class="text-6xl">📍</div>
                    <div class="text-sm font-medium text-gray-900">Wherever you are,<br />discover your city</div>
                </div>
             </div>
        </div>

        <!-- Card 4 -->
        <div class="bg-gray-50 rounded-3xl p-8 border border-gray-200 overflow-hidden">
             <div class="mb-8">
                 <h3 class="text-2xl font-serif mb-3">Anti-Scroll Philosophy</h3>
                 <p class="text-gray-600 text-sm leading-relaxed">We're not here to keep you on your phone. Get in, find something amazing, coordinate with your crew, and get out into the real world.</p>
             </div>
             <div class="h-64 bg-white rounded-xl p-6 flex items-center justify-center relative border border-gray-200">
                 <div class="text-center space-y-4">
                    <div class="text-6xl">🌆</div>
                    <div class="text-sm font-medium text-gray-900">Less screen time,<br />more real life</div>
                 </div>
             </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonial -->
  <section class="py-16 bg-gray-50">
    <div class="max-w-4xl mx-auto px-4 text-center">
        <div class="relative w-full max-w-md mx-auto mb-8">
            <img src="/generated/image-young-professional-in-late-20s-sitting-a-1765810742989-4.webp" alt="Access user" class="w-32 h-32 rounded-full mx-auto object-cover border-4 border-white shadow-lg" />
        </div>
        <blockquote class="text-2xl md:text-3xl font-serif leading-relaxed mb-8">
            "Tired of scrolling through five different apps just to find something to do. Access actually gets my crew together and doing things."
        </blockquote>
        <div class="text-center">
            <div class="font-bold text-sm">Maya, 27</div>
            <div class="text-xs text-gray-500">Early Access User, Brooklyn</div>
        </div>
    </div>
  </section>

  <!-- Visual Feature Section -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center mb-24">
        <div>
          <h2 class="text-3xl md:text-5xl font-serif mb-6">
            The city is your playground
          </h2>
          <p class="text-lg text-gray-600 mb-8 leading-relaxed">
            From underground music venues to weekend food markets, art gallery openings to secret pop-ups—Access surfaces the experiences that make your city worth exploring.
          </p>
          <ul class="space-y-4">
            <li class="flex items-start gap-3">
              <div class="w-6 h-6 bg-primary/20 rounded-full flex items-center justify-center flex-shrink-0 mt-0.5">
                <svg class="w-3 h-3 text-primary" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
              </div>
              <span class="text-gray-700">Handpicked events and experiences</span>
            </li>
            <li class="flex items-start gap-3">
              <div class="w-6 h-6 bg-primary/20 rounded-full flex items-center justify-center flex-shrink-0 mt-0.5">
                <svg class="w-3 h-3 text-primary" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
              </div>
              <span class="text-gray-700">Real-time updates on what's happening now</span>
            </li>
            <li class="flex items-start gap-3">
              <div class="w-6 h-6 bg-primary/20 rounded-full flex items-center justify-center flex-shrink-0 mt-0.5">
                <svg class="w-3 h-3 text-primary" fill="currentColor" viewBox="0 0 20 20"><path fill-rule="evenodd" d="M16.707 5.293a1 1 0 010 1.414l-8 8a1 1 0 01-1.414 0l-4-4a1 1 0 011.414-1.414L8 12.586l7.293-7.293a1 1 0 011.414 0z" clip-rule="evenodd"></path></svg>
              </div>
              <span class="text-gray-700">No sponsored content, just authentic experiences</span>
            </li>
          </ul>
        </div>
        <div class="relative">
          <img src="/generated/image-diverse-friend-group-of-4-5-people-at-un-1765810737156-3.webp" alt="Friends at live music venue" class="rounded-2xl shadow-2xl border border-gray-200" />
        </div>
      </div>
    </div>
  </section>

  <!-- Waitlist CTA -->
  <section id="waitlist" class="py-24 bg-gray-50 relative overflow-hidden">
    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <div class="inline-block bg-primary/10 text-primary px-4 py-1 rounded-full text-xs font-bold mb-6">
            Launching Soon
        </div>
        <h2 class="text-4xl md:text-6xl font-serif mb-4">Be the first to experience <br /> coordinated social discovery</h2>
        <p class="text-gray-600 mb-10">Join the waitlist and get early access when we launch in your city.</p>
        
        <div class="flex flex-col sm:flex-row justify-center gap-4 max-w-md mx-auto">
            <input type="email" placeholder="Enter your email" class="flex-1 px-6 py-3 rounded-full border-2 border-gray-300 focus:border-primary focus:outline-none" />
            <Button type="primary">Join Waitlist</Button>
        </div>
        <p class="text-xs text-gray-500 mt-4">No spam. Just updates on our launch.</p>
    </div>
  </section>

  <!-- Philosophy Section -->
  <section class="py-24 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        Built on a simple belief
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <!-- Card 1 -->
        <div class="bg-gray-50 rounded-3xl p-8 border border-gray-200 text-center">
            <div class="text-5xl mb-6">🌃</div>
            <h3 class="text-xl font-serif mb-3">IRL > URL</h3>
            <p class="text-gray-600 text-sm leading-relaxed">
              Real experiences beat endless scrolling. We're building for the world outside your screen.
            </p>
        </div>

        <!-- Card 2 -->
        <div class="bg-gray-50 rounded-3xl p-8 border border-gray-200 text-center">
            <div class="text-5xl mb-6">👥</div>
            <h3 class="text-xl font-serif mb-3">Crews over crowds</h3>
            <p class="text-gray-600 text-sm leading-relaxed">
              Your close friends matter more than follower counts. Built for tight-knit groups, not social media clout.
            </p>
        </div>

        <!-- Card 3 -->
        <div class="bg-gray-50 rounded-3xl p-8 border border-gray-200 text-center">
            <div class="text-5xl mb-6">✨</div>
            <h3 class="text-xl font-serif mb-3">Quality over quantity</h3>
            <p class="text-gray-600 text-sm leading-relaxed">
              Curated experiences you'll actually remember, not an endless feed of mediocre options.
            </p>
        </div>
      </div>
    </div>
  </section>

  <!-- Final CTA Section -->
  <section class="bg-primary py-24 relative overflow-hidden">
    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <h2 class="text-4xl md:text-6xl font-serif mb-8 text-white">Your city is waiting.<br />Your crew is ready.</h2>
        
        <p class="text-lg text-white/90 mb-10 max-w-2xl mx-auto">
          Stop wasting time scrolling through apps that don't get it. Join the waitlist and be first to experience social discovery that actually works.
        </p>

        <div class="flex justify-center gap-4">
            <Button href="#waitlist" type="secondary">Join Waitlist</Button>
            <Button href="mailto:hey@aaa.inc" type="white">Get in Touch</Button>
        </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-24 bg-gray-50">
    <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
      <h2 class="text-3xl md:text-5xl font-serif mb-8">About Access</h2>
      <div class="prose prose-lg mx-auto text-gray-600">
        <p class="text-lg leading-relaxed mb-6">
          We're building Access because we're tired of the endless scroll. Tired of group chats that go nowhere. 
          Tired of missing out on the best experiences in our cities because we can't coordinate with our friends.
        </p>
        <p class="text-lg leading-relaxed mb-6">
          Access transforms scattered social plans into coordinated experiences. We handpick the best pop-ups, shows, 
          and scenes happening in your city, then make it effortless for your crew to discover and coordinate around them.
        </p>
        <p class="text-lg leading-relaxed">
          Starting with urban friend groups, we're capturing the $50B social discovery market by solving what 
          matters most: getting people off their phones and into real experiences that actually matter.
        </p>
      </div>
    </div>
  </section>

  <!-- Contact Section -->
  <section id="contact" class="py-24 bg-white">
    <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
      <h2 class="text-3xl md:text-5xl font-serif mb-8">Get in Touch</h2>
      <p class="text-lg text-gray-600 mb-8 max-w-2xl mx-auto">
        Want to learn more? Have feedback? Just want to say hi? Hit us up.
      </p>
      <div class="flex flex-col sm:flex-row justify-center gap-6 items-center">
        <a href="mailto:hey@aaa.inc" class="text-lg font-medium text-primary hover:underline">hey@aaa.inc</a>
        <span class="text-gray-400">•</span>
        <a href="https://instagram.com/accessdotapp" target="_blank" rel="noopener noreferrer" class="text-lg font-medium text-primary hover:underline">@accessdotapp</a>
      </div>
    </div>
  </section>

  <Footer />
</div>

<style>
  /* Custom Scroll Animation */
  @keyframes scroll {
    0% { transform: translateX(0); }
    100% { transform: translateX(-50%); }
  }
  .animate-scroll {
    animation: scroll 20s linear infinite;
  }
  
  @keyframes spin-slow {
    from { transform: rotate(0deg); }
    to { transform: rotate(360deg); }
  }
  .animate-spin-slow {
    animation: spin-slow 20s linear infinite;
  }
</style>

