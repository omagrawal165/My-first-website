<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Vision Academy - Home</title>
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
</head>
<body class="bg-gray-50 font-sans">
  <!-- Header -->
  <header class="bg-blue-700 text-white p-6">
    <div class="container mx-auto flex justify-between items-center">
      <h1 class="text-2xl font-bold">Vision Academy</h1>
      <nav>
        <a href="#home" class="px-4">Home</a>
        <a href="#gallery" class="px-4">Gallery</a>
        <a href="#videos" class="px-4">Videos</a>
        <a href="#contact" class="px-4">Contact</a>
        <a href="login.html" class="bg-white text-blue-700 px-4 py-2 rounded ml-4">Login</a>
      </nav>
    </div>
  </header>  <!-- Home Section -->  <section id="home" class="p-8 text-center">
    <h2 class="text-3xl font-semibold">Welcome to Vision Academy</h2>
    <p class="mt-4 text-lg">Providing quality education from 1st to 10th grade SSC Board (Semi-English).</p>
  </section>  <!-- Gallery Section -->  <section id="gallery" class="p-8 bg-white">
    <h2 class="text-2xl font-semibold mb-4">Photo Gallery</h2>
    <div class="grid grid-cols-2 md:grid-cols-4 gap-4">
      <!-- Replace with your images -->
      <img src="/images/class1.jpg" alt="Class 1" class="rounded shadow">
      <img src="/images/class2.jpg" alt="Class 2" class="rounded shadow">
      <img src="/images/activity.jpg" alt="Activity" class="rounded shadow">
      <img src="/images/faculty.jpg" alt="Faculty" class="rounded shadow">
    </div>
  </section>  <!-- Video Section -->  <section id="videos" class="p-8">
    <h2 class="text-2xl font-semibold mb-4">Videos</h2>
    <div class="grid grid-cols-1 md:grid-cols-2 gap-4">
      <!-- Replace with your videos -->
      <video controls class="w-full rounded shadow">
        <source src="/videos/introduction.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
      <video controls class="w-full rounded shadow">
        <source src="/videos/lecture.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
    
