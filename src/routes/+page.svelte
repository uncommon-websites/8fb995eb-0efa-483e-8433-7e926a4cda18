<script lang="ts">
  import Navbar from '$lib/Navbar.svelte';
  import Footer from '$lib/Footer.svelte';
  import Button from '$lib/Button.svelte';
</script>

<div class="min-h-screen font-sans text-dark bg-cream overflow-x-hidden">
  <Navbar />

  <!-- Hero Section -->
  <section class="pt-32 pb-16 px-4 sm:px-6 lg:px-8 max-w-7xl mx-auto text-center">
    <div class="mb-6">
      <span class="text-xs font-bold tracking-widest text-gray-500 uppercase">Team Recognition Made Simple</span>
    </div>
    <h1 class="text-5xl md:text-7xl font-serif mb-6 leading-tight">
      Turn gratitude into action <br class="hidden md:block" /> with digital thank-you cards
    </h1>
    <p class="text-lg md:text-xl text-gray-600 max-w-2xl mx-auto mb-10 leading-relaxed">
      Kudobox helps remote teams recognize contributions instantly with shareable digital cards. 
      Make appreciation visual, meaningful, and effortless.
    </p>
    <div class="flex flex-col sm:flex-row items-center justify-center gap-4 mb-20">
      <Button href="#" type="primary">Start Free Trial &rarr;</Button>
      <Button href="#" type="outline">See Demo</Button>
    </div>

    <!-- Hero Image Placeholder -->
    <div class="relative w-full max-w-5xl mx-auto rounded-2xl overflow-hidden shadow-2xl border border-gray-200 bg-white aspect-[16/9] mb-16 group">
      <!-- Mock UI - Kudobox Interface -->
      <div class="absolute inset-0 bg-gray-50 p-4">
        <div class="h-full w-full bg-white rounded-xl border border-gray-200 shadow-sm p-6 flex flex-col">
            <!-- Header of Mock UI -->
            <div class="flex items-center justify-between mb-6 border-b border-gray-100 pb-4">
                <div class="flex items-center gap-3">
                    <svg width="24" height="24" viewBox="0 0 24 24" fill="none" xmlns="http://www.w3.org/2000/svg" class="text-orange-brand">
                      <path fill-rule="evenodd" clip-rule="evenodd" d="M6.99251 12.196C6.85314 12.5757 6.62925 12.9208 6.33682 13.2067H6.33835C6.00191 13.5351 5.58566 13.7756 5.12816 13.9059C4.67065 14.0362 4.18671 14.0522 3.72118 13.9523C3.25564 13.8524 2.82357 13.64 2.46501 13.3345C2.10645 13.0291 1.83299 12.6406 1.66998 12.2051C1.50697 11.7696 1.45969 11.3012 1.5325 10.8432C1.60532 10.3852 1.79587 9.95244 2.08653 9.58516C2.37718 9.21781 2.75852 8.9277 3.1952 8.74177C3.63188 8.55585 4.10979 8.48002 4.58462 8.52142L4.57074 8.50792C5.0567 8.54782 5.54575 8.48407 6.00378 8.32124C6.4618 8.15846 6.87776 7.90043 7.2226 7.56521C7.56746 7.22998 7.83285 6.82564 8.00036 6.38041C8.16786 5.93517 8.23344 5.45976 8.1924 4.98737L8.20628 5.00087C8.15181 4.43594 8.27796 3.86844 8.56753 3.37575C8.85701 2.88307 9.29579 2.48919 9.82407 2.24782C10.3523 2.00645 10.9443 1.92933 11.5192 2.02701C12.0942 2.12467 12.6243 2.39237 13.037 2.79358C13.4497 3.19479 13.7251 3.70999 13.8256 4.26892C13.926 4.82785 13.8467 5.4033 13.5984 5.9168C13.3501 6.4303 12.9449 6.85685 12.4381 7.13828C11.9313 7.41971 11.3474 7.54233 10.7663 7.4894L10.781 7.5029C10.2949 7.46279 9.80563 7.52632 9.34741 7.68904C8.88919 7.85176 8.47309 8.10975 8.12805 8.44499C7.78301 8.78025 7.51742 9.18466 7.34983 9.63001C7.18224 10.0754 7.11669 10.551 7.15774 11.0235L7.14309 11.01C7.1833 11.4112 7.13189 11.8162 6.99251 12.196Z" fill="currentColor"/>
                    </svg>
                    <div class="h-4 w-24 bg-gray-800 rounded font-bold text-xs flex items-center px-2 text-white">Kudobox</div>
                </div>
                <div class="flex gap-2">
                    <div class="h-8 w-24 bg-orange-brand rounded text-white text-xs flex items-center justify-center font-bold">+ New Card</div>
                </div>
            </div>
            <!-- Content of Mock UI - Thank You Cards Grid -->
            <div class="flex-1 bg-gray-50 rounded-lg p-4 grid grid-cols-3 gap-4">
                 <!-- Card 1 - Orange -->
                 <div class="bg-gradient-to-br from-orange-100 to-orange-200 p-4 rounded-lg shadow-sm flex flex-col justify-between">
                    <div class="text-2xl">🎉</div>
                    <div class="text-xs font-bold mt-2">Great Job!</div>
                    <div class="text-[8px] text-gray-600 mt-1">From Sarah</div>
                 </div>
                 <!-- Card 2 - Blue -->
                 <div class="bg-gradient-to-br from-blue-100 to-blue-200 p-4 rounded-lg shadow-sm flex flex-col justify-between">
                    <div class="text-2xl">⭐</div>
                    <div class="text-xs font-bold mt-2">Thank You!</div>
                    <div class="text-[8px] text-gray-600 mt-1">From Mike</div>
                 </div>
                 <!-- Card 3 - Purple -->
                 <div class="bg-gradient-to-br from-purple-100 to-purple-200 p-4 rounded-lg shadow-sm flex flex-col justify-between">
                    <div class="text-2xl">💪</div>
                    <div class="text-xs font-bold mt-2">Amazing Work</div>
                    <div class="text-[8px] text-gray-600 mt-1">From Team</div>
                 </div>
                 <!-- Card 4 - Green -->
                 <div class="bg-gradient-to-br from-green-100 to-green-200 p-4 rounded-lg shadow-sm flex flex-col justify-between">
                    <div class="text-2xl">🙌</div>
                    <div class="text-xs font-bold mt-2">Well Done!</div>
                    <div class="text-[8px] text-gray-600 mt-1">From Alex</div>
                 </div>
                 <!-- Card 5 - Pink -->
                 <div class="bg-gradient-to-br from-pink-100 to-pink-200 p-4 rounded-lg shadow-sm flex flex-col justify-between">
                    <div class="text-2xl">🚀</div>
                    <div class="text-xs font-bold mt-2">You Rock!</div>
                    <div class="text-[8px] text-gray-600 mt-1">From Lisa</div>
                 </div>
                 <!-- Card 6 - Yellow -->
                 <div class="bg-gradient-to-br from-yellow-100 to-yellow-200 p-4 rounded-lg shadow-sm flex flex-col justify-between">
                    <div class="text-2xl">✨</div>
                    <div class="text-xs font-bold mt-2">Kudos!</div>
                    <div class="text-[8px] text-gray-600 mt-1">From Chris</div>
                 </div>
            </div>
        </div>
      </div>
      
      <!-- Decorative Elements -->
      <div class="absolute -left-12 bottom-12 w-24 h-24 bg-orange-brand rounded-full blur-2xl opacity-20"></div>
      <div class="absolute -right-12 top-12 w-32 h-32 bg-primary-300 rounded-full blur-2xl opacity-20"></div>
    </div>

    <!-- Logos -->
    <div class="text-center">
      <p class="text-sm text-gray-500 mb-6">Trusted by remote teams at innovative companies</p>
      <div class="flex flex-wrap justify-center items-center gap-8 md:gap-12 opacity-60 grayscale hover:grayscale-0 transition-all duration-500">
        <!-- GitLab -->
        <span class="font-bold text-xl flex items-center gap-2"><div class="w-5 h-5 bg-orange-600 rounded-full"></div> GitLab</span>
        <!-- Zapier -->
        <span class="font-bold text-xl flex items-center gap-2"><div class="w-5 h-5 bg-orange-500 rounded"></div> Zapier</span>
        <!-- Notion -->
        <span class="font-bold text-xl flex items-center gap-2"><div class="w-5 h-5 bg-black rounded"></div> Notion</span>
        <!-- Automattic -->
        <span class="font-bold text-xl flex items-center gap-2"><div class="w-5 h-5 bg-blue-600 rounded-full"></div> Automattic</span>
        <!-- Buffer -->
        <span class="font-bold text-xl flex items-center gap-2"><div class="w-5 h-5 bg-blue-500 rounded"></div> Buffer</span>
        <!-- Doist -->
        <span class="font-bold text-xl flex items-center gap-2"><div class="w-5 h-5 bg-red-500 rounded-full"></div> Doist</span>
      </div>
    </div>
  </section>

  <!-- Stats Section -->
  <section class="py-20 bg-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-3xl mx-auto">
        Recognition that strengthens remote teams and builds culture
      </h2>
      
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 mb-16">
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">500K+</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Cards Sent</div>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">10 Seconds</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Average Time to Create</div>
        </div>
        <div class="bg-gray-50 p-8 rounded-2xl text-center">
          <div class="text-4xl font-serif font-medium mb-2">85%</div>
          <div class="text-xs font-bold text-gray-400 tracking-widest uppercase">Team Engagement Increase</div>
        </div>
      </div>

      <!-- Card Templates Carousel -->
      <div class="flex gap-4 overflow-hidden relative">
        <div class="absolute inset-y-0 left-0 w-20 bg-gradient-to-r from-white to-transparent z-10"></div>
        <div class="absolute inset-y-0 right-0 w-20 bg-gradient-to-l from-white to-transparent z-10"></div>
        
        <div class="flex gap-4 animate-scroll">
            <!-- Card 1 - Celebration -->
            <div class="w-64 h-80 bg-gradient-to-br from-orange-200 to-orange-300 rounded-2xl flex-shrink-0 relative overflow-hidden group p-8 flex flex-col justify-between shadow-lg">
                <div class="text-6xl">🎉</div>
                <div>
                    <div class="text-2xl font-serif font-bold mb-2">Great Job!</div>
                    <div class="text-sm opacity-80">Your presentation was amazing</div>
                </div>
                <div class="text-xs opacity-60">Celebration Template</div>
            </div>
            <!-- Card 2 - Thank You -->
            <div class="w-64 h-80 bg-gradient-to-br from-blue-200 to-blue-300 rounded-2xl flex-shrink-0 relative overflow-hidden group p-8 flex flex-col justify-between shadow-lg">
                <div class="text-6xl">🙏</div>
                <div>
                    <div class="text-2xl font-serif font-bold mb-2">Thank You</div>
                    <div class="text-sm opacity-80">For always being there</div>
                </div>
                <div class="text-xs opacity-60">Gratitude Template</div>
            </div>
            <!-- Card 3 - Achievement -->
            <div class="w-64 h-80 bg-gradient-to-br from-purple-200 to-purple-300 rounded-2xl flex-shrink-0 relative overflow-hidden group p-8 flex flex-col justify-between shadow-lg">
                <div class="text-6xl">🏆</div>
                <div>
                    <div class="text-2xl font-serif font-bold mb-2">Amazing Work</div>
                    <div class="text-sm opacity-80">You crushed that deadline!</div>
                </div>
                <div class="text-xs opacity-60">Achievement Template</div>
            </div>
             <!-- Card 4 - Team Spirit -->
            <div class="w-64 h-80 bg-gradient-to-br from-green-200 to-green-300 rounded-2xl flex-shrink-0 relative overflow-hidden group p-8 flex flex-col justify-between shadow-lg">
                <div class="text-6xl">🤝</div>
                <div>
                    <div class="text-2xl font-serif font-bold mb-2">Team Player</div>
                    <div class="text-sm opacity-80">Thanks for the collaboration</div>
                </div>
                <div class="text-xs opacity-60">Teamwork Template</div>
            </div>
             <!-- Card 5 - Innovation -->
            <div class="w-64 h-80 bg-gradient-to-br from-pink-200 to-pink-300 rounded-2xl flex-shrink-0 relative overflow-hidden group p-8 flex flex-col justify-between shadow-lg">
                <div class="text-6xl">💡</div>
                <div>
                    <div class="text-2xl font-serif font-bold mb-2">Brilliant Idea</div>
                    <div class="text-sm opacity-80">Your creativity inspires us</div>
                </div>
                <div class="text-xs opacity-60">Innovation Template</div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Problem/Solution Section -->
  <section class="bg-dark text-white py-24 overflow-hidden">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-4">Remote work changed <br /> how we recognize teams</h2>
      <p class="text-center text-gray-400 mb-16">Recognition shouldn't be harder just because we're distributed.</p>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-16 items-center">
        <!-- The Problem -->
        <div>
          <h3 class="text-xl font-serif mb-2">The Problem</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            Remote teams struggle with recognition fatigue. Generic Slack messages get lost, and meaningful appreciation takes too much time.
          </p>
          <div class="bg-gray-800/50 rounded-xl p-6 border border-gray-700 relative">
             <div class="space-y-3">
                <div class="flex items-start gap-3">
                    <div class="text-2xl opacity-50">😕</div>
                    <div class="flex-1">
                        <div class="text-xs text-gray-400">Generic messages</div>
                        <div class="text-sm text-gray-500 mt-1">"Good job everyone!"</div>
                    </div>
                </div>
                <div class="flex items-start gap-3">
                    <div class="text-2xl opacity-50">⏰</div>
                    <div class="flex-1">
                        <div class="text-xs text-gray-400">Time-consuming</div>
                        <div class="text-sm text-gray-500 mt-1">15+ minutes to create something meaningful</div>
                    </div>
                </div>
                <div class="flex items-start gap-3">
                    <div class="text-2xl opacity-50">📱</div>
                    <div class="flex-1">
                        <div class="text-xs text-gray-400">Gets lost</div>
                        <div class="text-sm text-gray-500 mt-1">Buried in chat history</div>
                    </div>
                </div>
             </div>
          </div>
        </div>

        <!-- The Solution -->
        <div>
          <h3 class="text-xl font-serif mb-2">The Kudobox Way</h3>
          <p class="text-gray-400 text-sm mb-8 leading-relaxed">
            Create beautiful, shareable thank-you cards in seconds. Make recognition visual, instant, and memorable.
          </p>
          <div class="relative h-64 flex items-center justify-center">
             <!-- Central Card Icon -->
             <div class="relative z-10 bg-gradient-to-br from-orange-400 to-orange-600 w-32 h-40 rounded-xl shadow-2xl flex flex-col items-center justify-center p-4">
                <div class="text-4xl mb-2">🎉</div>
                <div class="text-white text-sm font-bold text-center">Thank You!</div>
                <div class="text-white/70 text-xs mt-1">10 seconds</div>
             </div>
             <!-- Floating Elements -->
             <div class="absolute top-8 left-8 bg-blue-500/20 backdrop-blur px-3 py-1 rounded-full text-xs text-blue-300 border border-blue-500/30">
                Instant
             </div>
             <div class="absolute bottom-8 left-12 bg-green-500/20 backdrop-blur px-3 py-1 rounded-full text-xs text-green-300 border border-green-500/30">
                Visual
             </div>
             <div class="absolute top-12 right-8 bg-purple-500/20 backdrop-blur px-3 py-1 rounded-full text-xs text-purple-300 border border-purple-500/30">
                Shareable
             </div>
             <div class="absolute bottom-12 right-12 bg-pink-500/20 backdrop-blur px-3 py-1 rounded-full text-xs text-pink-300 border border-pink-500/30">
                Memorable
             </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Features Section 1 -->
  <section class="py-24 bg-cream" id="features">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        Recognition made simple, meaningful, and instant
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
        <!-- Card 1: AI Search -->
        <div class="lg:col-span-2 bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden relative group">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">AI-powered creator search</h3>
                <p class="text-gray-500 text-sm">Our AI lets you search all platforms - not just one. Simply search and find the right creator ambassadors for your business in minutes.</p>
            </div>
            <div class="bg-purple-50 rounded-xl p-6 h-64 relative border border-purple-100">
                <!-- Mock Search Bar -->
                <div class="bg-white rounded-full p-2 shadow-sm flex items-center gap-2 mb-4 w-3/4 mx-auto">
                    <div class="w-8 h-8 bg-purple-100 rounded-full flex items-center justify-center text-purple-600">✨</div>
                    <div class="text-sm text-gray-400">Tech & Startups</div>
                    <div class="ml-auto bg-black text-white px-4 py-1.5 rounded-full text-xs font-bold">Search</div>
                </div>
                <!-- Results Mockup -->
                <div class="flex gap-4 justify-center">
                    <div class="bg-white p-3 rounded-xl shadow-sm w-32">
                        <div class="w-8 h-8 bg-gray-200 rounded-full mb-2"></div>
                        <div class="h-2 w-16 bg-gray-100 rounded mb-1"></div>
                        <div class="h-2 w-10 bg-gray-100 rounded"></div>
                    </div>
                    <div class="bg-white p-3 rounded-xl shadow-sm w-32">
                        <div class="w-8 h-8 bg-gray-200 rounded-full mb-2"></div>
                        <div class="h-2 w-16 bg-gray-100 rounded mb-1"></div>
                        <div class="h-2 w-10 bg-gray-100 rounded"></div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Card 2: Network -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">World's largest B2B creator network</h3>
                <p class="text-gray-500 text-sm">The largest selection of creators across Newsletters, LinkedIn, YouTube, Instagram, Twitter, and more.</p>
            </div>
            <div class="bg-purple-50 rounded-xl h-48 relative overflow-hidden flex items-center justify-center">
                <div class="absolute inset-0 bg-[url('https://upload.wikimedia.org/wikipedia/commons/e/ec/World_map_blank_without_borders.svg')] bg-contain bg-no-repeat bg-center opacity-10"></div>
                <div class="flex gap-2 flex-wrap justify-center p-4">
                    <span class="bg-white px-2 py-1 rounded shadow-sm text-xs">Newsletter</span>
                    <span class="bg-white px-2 py-1 rounded shadow-sm text-xs">YouTube</span>
                    <span class="bg-white px-2 py-1 rounded shadow-sm text-xs">LinkedIn</span>
                </div>
            </div>
        </div>

        <!-- Card 3: Media Kits -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-purple-50 rounded-xl mb-6 p-4 relative">
                <div class="bg-white rounded-xl shadow-sm p-4 h-full w-full relative transform rotate-[-2deg]">
                    <div class="flex items-center gap-3 mb-3">
                        <div class="w-10 h-10 bg-gray-200 rounded-full"></div>
                        <div>
                            <div class="h-3 w-20 bg-gray-100 rounded mb-1"></div>
                            <div class="h-2 w-12 bg-gray-100 rounded"></div>
                        </div>
                    </div>
                    <div class="flex gap-2 mt-4">
                        <div class="h-16 w-1/3 bg-purple-100 rounded-lg"></div>
                        <div class="h-16 w-1/3 bg-orange-100 rounded-lg"></div>
                        <div class="h-16 w-1/3 bg-blue-100 rounded-lg"></div>
                    </div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Creator media kits</h3>
             <p class="text-gray-500 text-sm">Analyze creators with verified stats, past prices, rates, and much more.</p>
        </div>

        <!-- Card 4: Recommendations -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-purple-50 rounded-xl mb-6 p-4 flex items-center justify-center">
                <div class="bg-white p-4 rounded-xl shadow-sm w-full max-w-[200px]">
                    <div class="text-xs text-gray-400 mb-2">We need to reach our new AI video tool to growth experts...</div>
                    <div class="flex justify-end">
                        <div class="bg-black text-white text-xs px-3 py-1.5 rounded-lg">2.1k/M</div>
                    </div>
                </div>
             </div>
             <h3 class="text-xl font-serif mb-2">AI creator recommendations</h3>
             <p class="text-gray-500 text-sm">Tell us your goals - and our AI will build a campaign for you in seconds.</p>
        </div>

        <!-- Card 5: Evaluate -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 overflow-hidden">
             <div class="h-48 bg-purple-50 rounded-xl mb-6 p-4 flex items-center justify-center relative">
                 <div class="bg-white p-4 rounded-xl shadow-sm w-full max-w-[220px] flex items-center gap-4">
                    <div class="w-12 h-12 rounded-full bg-gray-200"></div>
                    <div class="flex-1">
                        <div class="h-3 w-20 bg-gray-100 rounded mb-2"></div>
                        <div class="h-2 w-full bg-gray-50 rounded"></div>
                    </div>
                    <div class="w-10 h-10 rounded-full border-4 border-green-400 flex items-center justify-center text-xs font-bold text-green-600">98</div>
                 </div>
             </div>
             <h3 class="text-xl font-serif mb-2">Evaluate a creator in seconds</h3>
             <p class="text-gray-500 text-sm">Our AI evaluates and summarizes their latest content - no more digging in their feeds.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Testimonial 1 -->
  <section class="py-16 bg-cream">
    <div class="max-w-4xl mx-auto px-4 text-center">
        <div class="flex justify-center mb-8">
            <div class="flex items-center gap-2 font-bold text-xl opacity-80">
                <div class="w-6 h-6 bg-black rounded"></div> INTERCOM
            </div>
        </div>
        <blockquote class="text-2xl md:text-3xl font-serif leading-relaxed mb-8">
            "Partnering with creators through Passionfroot has been a game-changer for Intercom's Startup program. By collaborating with top newsletters, we've reached thousands of founders."
        </blockquote>
        <div class="flex items-center justify-center gap-4">
            <div class="w-12 h-12 rounded-full bg-gray-300"></div>
            <div class="text-left">
                <div class="font-bold text-sm">John Doe</div>
                <div class="text-xs text-gray-500">Head of Partnerships at Intercom</div>
            </div>
        </div>
    </div>
  </section>

  <!-- Features Section 2 (Blue) -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        Build and run your <br /> campaign - at scale.
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Card 1 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-blue-50 rounded-xl h-64 mb-8 p-4 relative overflow-hidden">
                <!-- Kanban Board Mockup -->
                <div class="flex gap-4 h-full">
                    <div class="w-1/3 bg-white/50 rounded-lg p-2 space-y-2">
                        <div class="h-2 w-12 bg-blue-200 rounded"></div>
                        <div class="bg-white p-2 rounded shadow-sm h-16"></div>
                        <div class="bg-white p-2 rounded shadow-sm h-16"></div>
                    </div>
                    <div class="w-1/3 bg-white/50 rounded-lg p-2 space-y-2">
                        <div class="h-2 w-12 bg-blue-200 rounded"></div>
                         <div class="bg-white p-2 rounded shadow-sm h-16"></div>
                    </div>
                    <div class="w-1/3 bg-white/50 rounded-lg p-2 space-y-2">
                        <div class="h-2 w-12 bg-blue-200 rounded"></div>
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Design and run your campaign</h3>
            <p class="text-gray-500 text-sm">Build your perfect roster, then deploy and manage your creator campaign at scale from one integrated dash.</p>
        </div>

        <!-- Card 2 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-blue-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                 <div class="bg-white rounded-xl shadow-lg p-4 w-3/4">
                    <div class="flex justify-between items-center mb-4">
                        <div class="h-3 w-20 bg-gray-200 rounded"></div>
                        <div class="h-6 w-20 bg-blue-500 rounded text-white text-[10px] flex items-center justify-center">Apply now</div>
                    </div>
                    <div class="space-y-2">
                        <div class="h-2 w-full bg-gray-100 rounded"></div>
                        <div class="h-2 w-5/6 bg-gray-100 rounded"></div>
                    </div>
                 </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Publish your own live campaign</h3>
            <p class="text-gray-500 text-sm">Tired of outreach? Publish your campaign with your creator requirements and let relevant creators apply and come to you!</p>
        </div>

        <!-- Card 3 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-blue-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                <!-- Calendar Mockup -->
                <div class="bg-white rounded-xl shadow-sm p-4 w-3/4">
                    <div class="grid grid-cols-7 gap-2 mb-2">
                        {#each Array(7) as _}
                            <div class="h-4 w-full bg-gray-100 rounded"></div>
                        {/each}
                    </div>
                    <div class="grid grid-cols-7 gap-2">
                        {#each Array(28) as _, i}
                            <div class="h-6 w-full {i === 14 ? 'bg-blue-500' : 'bg-gray-50'} rounded text-[8px] flex items-center justify-center text-gray-400">
                                {i === 14 ? 'Book' : ''}
                            </div>
                        {/each}
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Book ad slots directly</h3>
            <p class="text-gray-500 text-sm">Skip the scheduling back-and-forth - book open slots directly in creators' calendars.</p>
        </div>

        <!-- Card 4 -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="bg-blue-50 rounded-xl h-64 mb-8 p-4 flex items-center justify-center">
                <!-- Chat Mockup -->
                <div class="w-full max-w-sm space-y-3">
                    <div class="flex gap-2">
                        <div class="w-8 h-8 bg-gray-200 rounded-full"></div>
                        <div class="bg-white p-3 rounded-2xl rounded-tl-none shadow-sm text-xs text-gray-500 w-2/3">
                            Hey! I'd love to work with you on this campaign.
                        </div>
                    </div>
                    <div class="flex gap-2 flex-row-reverse">
                        <div class="w-8 h-8 bg-blue-500 rounded-full"></div>
                        <div class="bg-blue-500 text-white p-3 rounded-2xl rounded-tr-none shadow-sm text-xs w-2/3">
                            Sounds great! Let's do it.
                        </div>
                    </div>
                </div>
            </div>
            <h3 class="text-xl font-serif mb-2">Scale your outreach and connect directly in-app</h3>
            <p class="text-gray-500 text-sm">Passionfroot is not a database, it's the largest B2B creator network in the world. This means you can book all creators directly from your campaign. No more email outreach or ghosted DMs.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Thousands of campaigns -->
  <section class="py-24 bg-cream relative overflow-hidden">
    <!-- Floating Icons Background (Simplified) -->
    <div class="absolute inset-0 opacity-10 pointer-events-none">
        <div class="absolute top-10 left-10 w-12 h-12 bg-black rounded-lg transform rotate-12"></div>
        <div class="absolute top-20 right-20 w-12 h-12 bg-blue-500 rounded-lg transform -rotate-6"></div>
        <div class="absolute bottom-20 left-1/3 w-12 h-12 bg-pink-500 rounded-lg transform rotate-45"></div>
        <div class="absolute bottom-10 right-1/4 w-12 h-12 bg-orange-500 rounded-lg transform -rotate-12"></div>
    </div>

    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <div class="inline-block bg-green-100 text-green-800 px-4 py-1 rounded-full text-xs font-bold mb-6">
            Get on Passionfroot ->
        </div>
        <h2 class="text-4xl md:text-6xl font-serif mb-4">Thousands of campaigns <br /> launched to date</h2>
        <p class="text-gray-500 mb-10">with 60% lower CPC than LinkedIn Ads*</p>
        
        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Get access &rarr;</Button>
            <Button href="#" type="white">Talk to us</Button>
        </div>
    </div>
  </section>

  <!-- Payments Section (Green) -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">
        Put creator payments & <br /> results on auto-pilot
      </h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-6">
        <!-- Left Large Card -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 md:row-span-2 flex flex-col">
            <div class="mb-8">
                <h3 class="text-xl font-serif mb-2">Pay quickly and safely</h3>
                <p class="text-gray-500 text-sm">Pay one provider - not hundreds. Enjoy worldwide creator payments for seamless and secure transactions - your finance team will love you.</p>
            </div>
            <div class="flex-1 bg-green-50 rounded-2xl relative overflow-hidden min-h-[300px]">
                <div class="absolute inset-0 bg-[radial-gradient(circle_at_center,_var(--tw-gradient-stops))] from-green-200/50 to-transparent"></div>
                <!-- Globe/Map Abstract -->
                <div class="absolute inset-0 flex items-center justify-center">
                    <div class="w-64 h-64 border border-green-200 rounded-full opacity-50"></div>
                    <div class="w-48 h-48 border border-green-200 rounded-full opacity-50 absolute"></div>
                    <div class="w-96 h-96 border border-green-200 rounded-full opacity-30 absolute"></div>
                </div>
                <!-- Floating Avatars -->
                <div class="absolute top-1/4 left-1/4 bg-white p-1 rounded-full shadow-lg flex items-center gap-2 pr-3 animate-bounce">
                    <div class="w-8 h-8 bg-yellow-200 rounded-full"></div>
                    <span class="text-xs font-bold">$500</span>
                </div>
                <div class="absolute bottom-1/3 right-1/4 bg-white p-1 rounded-full shadow-lg flex items-center gap-2 pr-3 animate-bounce delay-700">
                    <div class="w-8 h-8 bg-blue-200 rounded-full"></div>
                    <span class="text-xs font-bold">$1200</span>
                </div>
            </div>
        </div>

        <!-- Right Top Card -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100">
            <div class="flex justify-between items-start mb-4">
                <div>
                     <h3 class="text-xl font-serif mb-2">Measure returns effortlessly</h3>
                     <p class="text-gray-500 text-sm">Get results reported directly in your dash so you can take the guess work out of creator marketing.</p>
                </div>
                <span class="bg-green-100 text-green-700 px-2 py-1 rounded text-xs font-bold">Tracking live</span>
            </div>
            <div class="bg-green-50 rounded-xl h-40 flex items-end p-4 gap-2">
                <div class="w-1/5 bg-green-300 h-[40%] rounded-t"></div>
                <div class="w-1/5 bg-green-400 h-[60%] rounded-t"></div>
                <div class="w-1/5 bg-green-500 h-[30%] rounded-t"></div>
                <div class="w-1/5 bg-green-600 h-[80%] rounded-t"></div>
                <div class="w-1/5 bg-green-700 h-[50%] rounded-t"></div>
            </div>
        </div>

        <!-- Right Bottom Card (Testimonial) -->
        <div class="bg-white rounded-3xl p-8 shadow-sm border border-gray-100 flex gap-6 items-center">
            <div class="w-24 h-24 bg-gray-200 rounded-full flex-shrink-0 overflow-hidden">
                <!-- Placeholder for person -->
                <svg class="w-full h-full text-gray-400" fill="currentColor" viewBox="0 0 24 24"><path d="M24 24H0V0h24v24z" fill="none"/><path d="M12 12c2.21 0 4-1.79 4-4s-1.79-4-4-4-4 1.79-4 4 1.79 4 4 4zm0 2c-2.67 0-8 1.34-8 4v2h16v-2c0-2.66-5.33-4-8-4z"/></svg>
            </div>
            <div>
                <div class="text-green-600 text-4xl font-serif leading-none mb-2">"</div>
                <p class="text-sm text-gray-600 italic mb-4">Passionfroot helped us streamline procurement and now automates our creator payouts globally. Our finance department loves it.</p>
                <div class="text-xs font-bold">Julia</div>
                <div class="text-[10px] text-gray-400">Senior Marketing Manager at Linktree</div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- Powering People Grid -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16 max-w-2xl mx-auto">
        Powering the people building category-defining brands
      </h2>

      <div class="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-4 gap-4">
         <!-- Row 1 -->
         <div class="aspect-square bg-gray-200 rounded-2xl relative overflow-hidden group">
            <div class="absolute inset-0 bg-black/20 group-hover:bg-black/40 transition-colors"></div>
            <div class="absolute bottom-4 left-4 text-white font-bold">Gamma</div>
            <div class="absolute bottom-4 right-4 text-white text-xl">+</div>
         </div>
         <div class="aspect-square bg-white rounded-2xl flex items-center justify-center border border-gray-100">
            <span class="text-2xl font-bold flex items-center gap-2"><div class="w-6 h-6 bg-purple-500 rounded-tl-lg rounded-br-lg"></div> Figma</span>
         </div>
         <div class="col-span-2 bg-[#FFF9C4] rounded-2xl p-8 flex flex-col justify-between">
            <div class="text-4xl font-serif text-yellow-600">"</div>
            <p class="text-lg font-serif leading-relaxed">Partnering with creators through Passionfroot has been a strong growth channel. Instead of scouring the internet, their AI search enabled us to find...</p>
            <div class="flex justify-between items-end">
                <div class="text-xs">
                    <div class="font-bold">John Doe</div>
                    <div class="text-gray-500">Head of Partnerships</div>
                </div>
                <div class="text-xl">+</div>
            </div>
         </div>

         <!-- Row 2 -->
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
            <span class="text-3xl font-bold text-gray-700">HubSpot</span>
         </div>
         <div class="aspect-square bg-gray-200 rounded-2xl relative overflow-hidden group">
             <div class="absolute bottom-4 left-4 text-white font-bold">Munch</div>
             <div class="absolute bottom-4 right-4 text-white text-xl">+</div>
         </div>
         <div class="aspect-square bg-gray-200 rounded-2xl relative overflow-hidden group">
             <div class="absolute bottom-4 left-4 text-white font-bold">Freshbooks</div>
             <div class="absolute bottom-4 right-4 text-white text-xl">+</div>
         </div>

         <!-- Row 3 -->
         <div class="col-span-2 bg-[#E6F0FF] rounded-2xl p-8 flex flex-col justify-between">
            <div class="text-4xl font-serif text-blue-600">"</div>
            <p class="text-lg font-serif leading-relaxed">Passionfroot really helped us level up our creator program into a strong growth channel. Instead of scouring the internet...</p>
            <div class="flex justify-between items-end">
                <div class="text-xs">
                    <div class="font-bold">Jane Smith</div>
                    <div class="text-gray-500">Growth Lead</div>
                </div>
                <div class="text-xl">+</div>
            </div>
         </div>
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
             <span class="text-2xl font-bold flex items-center gap-2"><div class="w-6 h-6 bg-black rounded"></div> Framer</span>
         </div>
         
         <!-- Row 4 -->
         <div class="aspect-square bg-gray-200 rounded-2xl relative overflow-hidden group">
             <div class="absolute bottom-4 left-4 text-white font-bold">Replit</div>
             <div class="absolute bottom-4 right-4 text-white text-xl">+</div>
         </div>
         <div class="aspect-square bg-gray-200 rounded-2xl relative overflow-hidden group">
             <div class="absolute bottom-4 left-4 text-white font-bold">Pika</div>
             <div class="absolute bottom-4 right-4 text-white text-xl">+</div>
         </div>
         <div class="col-span-2 bg-white rounded-2xl flex items-center justify-center border border-gray-100 p-8">
             <span class="text-2xl font-bold">ElevenLabs</span>
         </div>
      </div>
    </div>
  </section>

  <!-- Orange CTA Section -->
  <section class="bg-orange-brand py-24 relative overflow-hidden">
    <div class="max-w-4xl mx-auto px-4 text-center relative z-10">
        <h2 class="text-4xl md:text-6xl font-serif mb-8 text-dark">Let's make creators your <br /> next growth channel</h2>
        
        <div class="flex flex-col md:flex-row justify-center gap-6 mb-10 text-sm font-medium text-dark/80">
            <div class="flex items-center gap-2">
                <div class="bg-dark text-white rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                Get better returns on your time & money
            </div>
            <div class="flex items-center gap-2">
                <div class="bg-dark text-white rounded-full p-0.5"><svg class="w-3 h-3" fill="none" stroke="currentColor" viewBox="0 0 24 24"><path stroke-linecap="round" stroke-linejoin="round" stroke-width="3" d="M5 13l4 4L19 7"></path></svg></div>
                Save 70% of your time per campaign
            </div>
        </div>

        <div class="flex justify-center gap-4">
            <Button href="#" type="primary">Get access &rarr;</Button>
            <Button href="#" type="white">Talk to us</Button>
        </div>
    </div>

    <!-- Bottom Illustration (Cartoon Line) -->
    <div class="absolute bottom-0 left-0 right-0 h-32 opacity-20 pointer-events-none flex items-end justify-center overflow-hidden">
        <!-- Abstract representation of the cartoon line -->
        <svg width="1200" height="100" viewBox="0 0 1200 100" fill="none" xmlns="http://www.w3.org/2000/svg">
            <path d="M0 100 C 50 50, 100 50, 150 100" stroke="black" stroke-width="2" fill="none"/>
            <circle cx="75" cy="80" r="10" stroke="black" stroke-width="2"/>
            <path d="M150 100 C 200 60, 250 60, 300 100" stroke="black" stroke-width="2" fill="none"/>
            <circle cx="225" cy="85" r="12" stroke="black" stroke-width="2"/>
            <path d="M300 100 C 350 40, 400 40, 450 100" stroke="black" stroke-width="2" fill="none"/>
             <circle cx="375" cy="70" r="15" stroke="black" stroke-width="2"/>
             <!-- Repeat pattern -->
             <path d="M450 100 C 500 50, 550 50, 600 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M600 100 C 650 60, 700 60, 750 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M750 100 C 800 40, 850 40, 900 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M900 100 C 950 50, 1000 50, 1050 100" stroke="black" stroke-width="2" fill="none"/>
             <path d="M1050 100 C 1100 60, 1150 60, 1200 100" stroke="black" stroke-width="2" fill="none"/>
        </svg>
    </div>
  </section>

  <!-- Case Studies -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif text-center mb-16">Case Studies</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-8">
        <!-- Large Card Top -->
        <div class="md:col-span-2 bg-[#FFCCBC] rounded-3xl p-10 md:p-16 flex flex-col md:flex-row items-center gap-10">
            <div class="flex-1">
                <div class="text-4xl font-bold text-white mb-8">guidde.</div>
            </div>
            <div class="flex-1 bg-white/90 backdrop-blur rounded-2xl p-8 shadow-sm">
                <div class="text-xs font-bold text-gray-400 uppercase mb-4">Customer Story</div>
                <h3 class="text-2xl font-serif mb-4">How Guidde made creators a scalable growth channel with Passionfroot</h3>
                <p class="text-gray-500 text-sm mb-6">Guidde is the generative AI platform for business that helps teams create video documentation in a matter...</p>
                <div class="flex justify-between items-center">
                    <span class="text-xs text-gray-400">4 min read</span>
                    <button class="bg-black text-white px-4 py-2 rounded-lg text-xs font-bold">Read more &rarr;</button>
                </div>
            </div>
        </div>

        <!-- Bottom Left -->
        <div class="bg-[#B3E5FC] rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="flex items-center gap-2 font-bold opacity-80 mb-8">
                <div class="w-6 h-6 bg-black rounded"></div> INTERCOM
            </div>
            <div class="bg-white/90 backdrop-blur rounded-2xl p-6 shadow-sm mt-auto">
                <div class="text-xs font-bold text-gray-400 uppercase mb-2">Customer Story</div>
                <h3 class="text-xl font-serif mb-4">Becoming the definitive AI-first Customer Service Platform</h3>
                <div class="flex justify-between items-center mt-4">
                    <span class="text-xs text-gray-400">3 min read</span>
                    <button class="bg-black text-white px-3 py-1.5 rounded-lg text-xs font-bold">Read more &rarr;</button>
                </div>
            </div>
        </div>

        <!-- Bottom Right -->
        <div class="bg-[#FFCC80] rounded-3xl p-8 flex flex-col justify-between h-96">
            <div class="flex items-center gap-2 font-bold opacity-80 mb-8 text-blue-900">
                <div class="w-6 h-6 bg-blue-600 rounded"></div> Freshbooks
            </div>
            <div class="bg-white/90 backdrop-blur rounded-2xl p-6 shadow-sm mt-auto">
                <div class="text-xs font-bold text-gray-400 uppercase mb-2">Customer Story</div>
                <h3 class="text-xl font-serif mb-4">How Freshbooks reached 2M+ impressions with Passionfroot</h3>
                <div class="flex justify-between items-center mt-4">
                    <span class="text-xs text-gray-400">3 min read</span>
                    <button class="bg-black text-white px-3 py-1.5 rounded-lg text-xs font-bold">Read more &rarr;</button>
                </div>
            </div>
        </div>
      </div>
    </div>
  </section>

  <!-- FAQ -->
  <section class="py-24 bg-cream">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
      <h2 class="text-3xl md:text-5xl font-serif mb-16">Frequently Asked Questions</h2>

      <div class="grid grid-cols-1 md:grid-cols-2 gap-x-12 gap-y-6">
        {#each [
            "What is Passionfroot?",
            "What types of businesses can use Passionfroot?",
            "How does Passionfroot work?",
            "What platforms can I use Passionfroot for?",
            "How do I discover the right creators for my brand?",
            "How are payments managed?",
            "Can I run multiple campaigns at once?",
            "How do I get started with Passionfroot?"
        ] as question}
            <div class="border-b border-gray-200 py-4 flex justify-between items-center group cursor-pointer">
                <span class="font-medium text-lg group-hover:text-orange-brand transition-colors">{question}</span>
                <div class="w-6 h-6 rounded-full bg-dark text-white flex items-center justify-center text-sm group-hover:bg-orange-brand transition-colors">+</div>
            </div>
        {/each}
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

