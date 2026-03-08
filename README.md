<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AI Video Generator - Turn Text into Videos Instantly</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body { background: #0a0f1e; color: white; font-family: system-ui; }
    .neon { text-shadow: 0 0 25px #00f3ff, 0 0 50px #00f3ff; }
    .btn-neon { background: linear-gradient(45deg, #00f3ff, #00b8ff); transition: all 0.3s; }
    .btn-neon:hover { transform: scale(1.08); box-shadow: 0 0 40px #00f3ff; }
  </style>
</head>
<body class="min-h-screen">

  <!-- Header -->
  <header class="border-b border-cyan-500/30">
    <div class="max-w-7xl mx-auto px-6 py-5 flex items-center justify-between">
      <div class="flex items-center gap-3 text-2xl font-bold neon">⚡ AI Video Generator</div>
      <nav class="space-x-8 text-sm">
        <a href="#how" class="hover:text-cyan-400">How it Works</a>
        <a href="#features" class="hover:text-cyan-400">Features</a>
        <a href="https://github.com/sindalma/ai-video-generator" target="_blank" class="hover:text-cyan-400">GitHub</a>
      </nav>
      <a href="https://t.me/AIsindal_bot" target="_blank" class="btn-neon text-black font-semibold px-8 py-3 rounded-xl">Try Free Now</a>
    </div>
  </header>

  <!-- Hero -->
  <section class="max-w-7xl mx-auto px-6 py-24 grid md:grid-cols-2 gap-12 items-center">
    <div>
      <span class="bg-cyan-500/20 text-cyan-400 px-6 py-2 rounded-full text-sm font-medium">100% Free • Instant Videos</span>
      <h1 class="text-6xl font-bold leading-tight mt-6 neon">
        Turn Any Text Into<br>Professional Videos<br><span class="text-cyan-400">in Seconds</span>
      </h1>
      <p class="text-xl text-gray-300 mt-6 max-w-lg">
        Just type a sentence in Telegram and get a stunning short video with Nigerian voice, engaging script, stock footage, subtitles & music — completely automatic.
      </p>
      <div class="mt-10 flex gap-4">
        <a href="https://t.me/AIsindal_bot" target="_blank" 
           class="btn-neon text-black font-semibold px-12 py-5 rounded-2xl text-xl">Start Creating Videos Free</a>
      </div>
      <p class="mt-8 text-gray-400 text-sm">No credit card • No signup • Works in any Telegram topic</p>
    </div>

    <div class="rounded-3xl overflow-hidden border border-cyan-500/30 shadow-2xl">
      <img src="https://picsum.photos/id/1015/800/520" alt="AI Video Generator Demo" class="w-full" />
    </div>
  </section>

  <!-- Features -->
  <section id="features" class="py-20 bg-black/40">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-12">Everything You Need in One Bot</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-zinc-900 p-8 rounded-3xl text-center">
          <h3 class="text-2xl font-semibold mb-3">🇳🇬 Natural Nigerian Voice</h3>
          <p class="text-gray-400">Warm EzinneNeural voice that sounds authentic and professional.</p>
        </div>
        <div class="bg-zinc-900 p-8 rounded-3xl text-center">
          <h3 class="text-2xl font-semibold mb-3">Engaging AI Scripts</h3>
          <p class="text-gray-400">Storytelling scripts with emotional hooks and vivid language.</p>
        </div>
        <div class="bg-zinc-900 p-8 rounded-3xl text-center">
          <h3 class="text-2xl font-semibold mb-3">Auto Subtitles + Music</h3>
          <p class="text-gray-400">Beautiful text overlays + royalty-free motivational music.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Final CTA -->
  <section class="py-24 text-center bg-gradient-to-b from-transparent via-cyan-500/10 to-transparent">
    <div class="max-w-2xl mx-auto px-6">
      <h2 class="text-5xl font-bold mb-4">Ready to create your first video?</h2>
      <p class="text-xl text-gray-400 mb-10">Open Telegram and chat with your bot right now</p>
      <a href="https://t.me/AIsindal_bot" target="_blank" 
         class="inline-block bg-gradient-to-r from-cyan-400 to-blue-500 text-black font-bold text-2xl px-16 py-6 rounded-3xl hover:scale-105 transition">
        Open @AIsindal_bot Now →
      </a>
    </div>
  </section>

  <footer class="text-center py-12 text-gray-500">
    Made with ❤️ in Lagos • AI Video Generator by sindalma
  </footer>

</body>
</html>
