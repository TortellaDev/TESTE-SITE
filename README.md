<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>F.B.S - Find By Sound</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-white text-gray-800">
  <!-- Header -->
  <header class="bg-red-500 text-white p-4 flex justify-between items-center">
    <h1 class="text-2xl font-bold">Find By Sound</h1>
    <nav>
      <a href="index.html" class="mx-2 hover:underline">Início</a>
      <a href="artists.html" class="mx-2 hover:underline">Artistas</a>
      <a href="about.html" class="mx-2 hover:underline">Sobre</a>
      <a href="login.html" class="ml-4 bg-white text-red-500 px-3 py-1 rounded hover:bg-gray-100">Entrar</a>
    </nav>
  </header>

  <!-- Hero Section -->
  <section class="bg-orange-400 text-white p-10 text-center">
    <h2 class="text-3xl font-bold mb-4">Conectando artistas e apaixonados por arte em São Paulo</h2>
    <p>Descubra talentos, conheça novos espaços e viva a arte.</p>
  </section>

  <!-- Destaques -->
  <section class="p-6 grid md:grid-cols-3 gap-6">
    <div class="bg-gray-100 p-4 rounded shadow">
      <h3 class="text-xl font-semibold mb-2">Artistas em destaque</h3>
      <p>Confira os talentos da semana selecionados pela curadoria.</p>
    </div>
    <div class="bg-gray-100 p-4 rounded shadow">
      <h3 class="text-xl font-semibold mb-2">Eventos próximos</h3>
      <p>Veja os eventos culturais e encontros artísticos em SP.</p>
    </div>
    <div class="bg-gray-100 p-4 rounded shadow">
      <h3 class="text-xl font-semibold mb-2">Cadastre-se</h3>
      <p>Se você é artista, crie seu perfil e compartilhe sua arte.</p>
    </div>
  </section>

  <!-- Footer -->
  <footer class="bg-blue-600 text-white text-center p-4 mt-10">
    © 2025 Find By Sound. Todos os direitos reservados.
  </footer>
</body>
</html>
<section class="p-6 bg-white">
  <h2 class="text-2xl font-bold mb-4 text-center">Artistas em destaque</h2>
  <div class="grid sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-6">
    
    <!-- Card de Artista -->
    <div class="bg-gray-100 rounded-lg shadow p-4 text-center hover:shadow-lg transition">
      <img src="https://via.placeholder.com/150" alt="Artista 1" class="w-32 h-32 mx-auto rounded-full mb-3 object-cover">
      <h3 class="text-xl font-semibold">DJ Aurora</h3>
      <p class="text-sm text-gray-600">Techno / Ambient</p>
      <button class="mt-3 bg-red-500 text-white px-4 py-1 rounded hover:bg-red-600">Ver Perfil</button>
    </div>

    <!-- Card 2 -->
    <div class="bg-gray-100 rounded-lg shadow p-4 text-center hover:shadow-lg transition">
      <img src="https://via.placeholder.com/150" alt="Artista 2" class="w-32 h-32 mx-auto rounded-full mb-3 object-cover">
      <h3 class="text-xl font-semibold">MC Zulu</h3>
      <p class="text-sm text-gray-600">Rap / Experimental</p>
      <button class="mt-3 bg-red-500 text-white px-4 py-1 rounded hover:bg-red-600">Ver Perfil</button>
    </div>

    <!-- Card 3 -->
    <div class="bg-gray-100 rounded-lg shadow p-4 text-center hover:shadow-lg transition">
      <img src="https://via.placeholder.com/150" alt="Artista 3" class="w-32 h-32 mx-auto rounded-full mb-3 object-cover">
      <h3 class="text-xl font-semibold">Luma Luz</h3>
      <p class="text-sm text-gray-600">Pop Art / Performance</p>
      <button class="mt-3 bg-red-500 text-white px-4 py-1 rounded hover:bg-red-600">Ver Perfil</button>
    </div>

  </div>
</section>
<section class="p-6 bg-orange-50 text-gray-800">
  <div class="max-w-4xl mx-auto text-center">
    <h2 class="text-2xl font-bold mb-3">Você ama arte?</h2>
    <p class="mb-5">Conecte-se com artistas independentes, receba recomendações e explore novos espaços culturais na cidade.</p>
    <a href="#" class="bg-blue-600 text-white px-6 py-2 rounded hover:bg-blue-700">Criar Conta como Entusiasta</a>
  </div>
</section>
<!-- Hero section com imagem de fundo -->
<section class="bg-[url('assets/img/sao-paulo-night.jpg')] bg-cover bg-center text-white p-10">
  <h2 class="text-3xl font-bold">Conectando artistas em São Paulo</h2>
</section>

<!-- Card de artista com imagem de fundo -->
<div class="bg-[url('assets/img/artist-bg.jpg')] bg-cover bg-center rounded-lg p-6">
  <h3 class="text-white">Nome do Artista</h3>
</div>
