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
    .btn-neon:hover { transform: scale(1.05); box-shadow: 0 0 30px #00f3ff; }
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
      <a href="https://t.me/AIsindal_bot" target="_blank" 
         class="btn-neon text-black font-semibold px-8 py-3 rounded-xl">Try Now →</a>
    </div>
  </header>

  <!-- Hero -->
  <section class="max-w-7xl mx-auto px-6 py-24 grid md:grid-cols-2 gap-12 items-center">
    <div>
      <span class="bg-cyan-500/20 text-cyan-400 px-5 py-2 rounded-full text-sm font-medium">Automated Content Pipeline</span>
      <h1 class="text-6xl font-bold leading-tight mt-6 neon">
        Turn Any Text into<br>Stunning Videos<br><span class="text-cyan-400">in Seconds</span>
      </h1>
      <p class="text-xl text-gray-300 mt-6 max-w-lg">
        Your personal AI Video Generator. Just type in Telegram and get professional videos with Nigerian voice, engaging scripts, stock footage & music — automatically.
      </p>
      <div class="mt-10 flex gap-4">
        <a href="https://t.me/AIsindal_bot" target="_blank" 
           class="btn-neon text-black font-semibold px-10 py-4 rounded-2xl text-lg">Start Creating Free</a>
        <a href="#how" class="border border-white/50 hover:bg-white/10 px-8 py-4 rounded-2xl">Watch Demo</a>
      </div>
    </div>

    <div class="bg-gradient-to-br from-cyan-500/10 to-purple-500/10 rounded-3xl p-8 border border-cyan-500/30">
      <img src="https://picsum.photos/id/1015/800/500" alt="AI Video Generator Demo" class="rounded-2xl shadow-2xl" />
    </div>
  </section>

  <!-- Features -->
  <section id="features" class="bg-black/50 py-20">
    <div class="max-w-7xl mx-auto px-6 text-center">
      <h2 class="text-4xl font-bold mb-12">Powerful Features</h2>
      <div class="grid md:grid-cols-3 gap-8">
        <div class="bg-zinc-900 p-8 rounded-3xl">
          <h3 class="text-2xl font-semibold mb-3">🇳🇬 Nigerian Voice</h3>
          <p class="text-gray-400">Natural EzinneNeural voice that sounds local and professional.</p>
        </div>
        <div class="bg-zinc-900 p-8 rounded-3xl">
          <h3 class="text-2xl font-semibold mb-3">Engaging Scripts</h3>
          <p class="text-gray-400">AI writes storytelling scripts with hooks and emotion.</p>
        </div>
        <div class="bg-zinc-900 p-8 rounded-3xl">
          <h3 class="text-2xl font-semibold mb-3">Auto Subtitles + Music</h3>
          <p class="text-gray-400">Beautiful text overlays and royalty-free motivational music.</p>
        </div>
      </div>
    </div>
  </section>

  <!-- CTA -->
  <section class="py-24 text-center">
    <div class="max-w-2xl mx-auto px-6">
      <h2 class="text-5xl font-bold mb-6">Ready to create your first video?</h2>
      <p class="text-xl text-gray-400 mb-10">Just open Telegram and talk to your bot</p>
      <a href="https://t.me/AIsindal_bot" target="_blank" 
         class="inline-block bg-gradient-to-r from-cyan-400 to-blue-500 text-black font-bold text-2xl px-16 py-6 rounded-3xl hover:scale-105 transition">
        Open @AIsindal_bot Now →
      </a>
    </div>
  </section>

  <footer class="text-center py-10 text-gray-500 text-sm">
    Made with ❤️ in Lagos • AI Video Generator by sindalma
  </footer>

</body>
</html>
