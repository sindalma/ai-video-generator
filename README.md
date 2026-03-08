<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>AI Video Generator</title>
  <script src="https://cdn.tailwindcss.com"></script>
  <style>
    body { background: #0a0f1e; color: white; font-family: system-ui; }
    .neon { text-shadow: 0 0 20px #00f3ff, 0 0 40px #00f3ff; }
    .btn-neon { background: linear-gradient(45deg, #00f3ff, #00b8ff); transition: all 0.3s; }
    .btn-neon:hover { transform: scale(1.05); box-shadow: 0 0 40px #00f3ff; }
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
        <a href="https://t.me/AIsindal_bot" target="_blank" class="hover:text-cyan-400">Try Now</a>
      </nav>
    </div>
  </header>

  <!-- Hero -->
  <section class="max-w-7xl mx-auto px-6 py-24 grid md:grid-cols-2 gap-12 items-center">
    <div>
      <span class="bg-cyan-500/20 text-cyan-400 px-5 py-2 rounded-full text-sm font-medium">100% Automated • Nigerian Voice</span>
      <h1 class="text-6xl font-bold leading-tight mt-6 neon">
        Turn Any Idea Into<br>A Professional Video<br><span class="text-cyan-400">In Seconds</span>
      </h1>
      <p class="text-xl text-gray-300 mt-6 max-w-lg">
        Just type in Telegram. Our AI creates engaging scripts, adds Nigerian voiceover, stock footage, subtitles, and motivational music — then posts the video back instantly.
      </p>
      <div class="mt-10 flex gap-4">
        <a href="https://t.me/AIsindal_bot" target="_blank" 
           class="btn-neon text-black font-semibold px-12 py-5 rounded-2xl text-xl">Start Creating Free →</a>
      </div>
      <p class="text-sm text-gray-400 mt-6">No editing skills needed • Works in any Telegram topic</p>
    </div>

    <div class="rounded-3xl overflow-hidden border border-cyan-500/30 shadow-2xl">
      <img src="https://picsum.photos/id/1015/800/500" alt="AI Video Generator Demo" class="w-full" />
    </div>
  </section>

  <!-- How it Works -->
  <section id="how" class="bg-black/50 py-20">
    <div class="max-w-7xl mx-auto px-6">
      <h2 class="text-4xl font-bold text-center mb-12">How It Works</h2>
      <div class="grid md:grid-cols-5 gap-6">
        <div class="text-center">
          <div class="w-12 h-12 bg-cyan-500 text-black rounded-full flex items-center justify-center mx-auto mb-4 font-bold">1</div>
          <p class="font-medium">Type any idea in Telegram</p>
        </div>
        <div class="text-center">
          <div class="w-12 h-12 bg-cyan-500 text-black rounded-full flex items-center justify-center mx-auto mb-4 font-bold">2</div>
          <p class="font-medium">AI writes engaging script</p>
        </div>
        <div class="text-center">
          <div class="w-12 h-12 bg-cyan-500 text-black rounded-full flex items-center justify-center mx-auto mb-4 font-bold">3</div>
          <p class="font-medium">Fetches stock footage</p>
        </div>
        <div class="text-center">
          <div class="w-12 h-12 bg-cyan-500 text-black rounded-full flex items-center justify-center mx-auto mb-4 font-bold">4</div>
          <p class="font-medium">Adds Nigerian voice + music</p>
        </div>
        <div class="text-center">
          <div class="w-12 h-12 bg-cyan-500 text-black rounded-full flex items-center justify-center mx-auto mb-4 font-bold">5</div>
          <p class="font-medium">Posts video back instantly</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Features -->
  <section id="features" class="py-20">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <h2 class="text-4xl font-bold mb-12">Why Creators Love It</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-zinc-900 p-8 rounded-3xl">
          <h3 class="text-2xl font-semibold mb-3">🇳🇬 Natural Nigerian Voice</h3>
          <p class="text-gray-400">EzinneNeural — warm, clear, and sounds like home.</p>
        </div>
        <div class="bg-zinc-900 p-8 rounded-3xl">
          <h3 class="text-2xl font-semibold mb-3">Engaging Storytelling</h3>
          <p class="text-gray-400">Hooks, emotion, and vivid narration that keeps viewers watching.</p>
        </div>
        <div class="bg-zinc-900 p-8 rounded-3xl">
          <h3 class="text-2xl font-semibold mb-3">Auto Subtitles + Music</h3>
          <p class="text-gray-400">Beautiful text overlays and perfect background music.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- Final CTA -->
  <section class="py-24 text-center bg-gradient-to-b from-transparent via-cyan-500/10 to-transparent">
    <div class="max-w-2xl mx-auto px-6">
      <h2 class="text-5xl font-bold mb-6">Ready to create your first video?</h2>
      <p class="text-2xl text-gray-300 mb-10">Open Telegram and start typing</p>
      <a href="https://t.me/AIsindal_bot" target="_blank" 
         class="inline-block bg-gradient-to-r from-cyan-400 to-blue-500 text-black font-bold text-2xl px-16 py-7 rounded-3xl hover:scale-110 transition">
        Open @AIsindal_bot Now →
      </a>
    </div>
  </section>

  <footer class="text-center py-12 text-gray-500 text-sm border-t border-white/10">
    AI Video Generator • Built in Lagos • Powered by Groq, Pexels &amp; Edge TTS
  </footer>

</body>
</html>
