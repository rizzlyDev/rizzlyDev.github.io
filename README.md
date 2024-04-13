<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Autism Awareness</title>
  <!-- Include Tailwind CSS -->
  <link href="https://cdn.jsdelivr.net/npm/tailwindcss@2.2.19/dist/tailwind.min.css" rel="stylesheet">
  <style>
    /* Additional Custom Styles */
    .autism-bg {
      background-color: #; /* Zinc background */
    }
    .autism-bg-dark {
      background-color: #FFC0CB;
    }
    .autism-bg-light {
      background-color: #eff6ff;
    }
    .autism-text {
      color: #2b6cb0;
    }
    .autism-text-light {
      color: #80d4ff;
    }
    .autism-btn {
      background-color: #2b6cb0;
    }
    .autism-btn:hover {
      background-color: #2565a7;
    }
    /* Keyframe Animation */
    @keyframes fadeInUp {
      from {
        opacity: 0;
        transform: translateY(20px);
      }
      to {
        opacity: 1;
        transform: translateY(0);
      }
    }
    /* Add Animated Class */
    .animated {
      animation: fadeInUp 0.5s ease-out;
    }
  </style>
</head>
<body class="autism-bg-blue-500 text-black">

  <!-- Navigation -->
  <nav class="bg-white shadow-md">
    <div class="container mx-auto px-4">
      <div class="flex justify-between items-center py-4">
        <div class="text-2xl font-semibold autism-text">Autism Awareness by rizz</div>
        <ul class="flex space-x-4">
          <li><a href="#about" class="autism-text hover:text-autism-text-light">About</a></li>
          <li><a href="#resources" class="autism-text hover:text-autism-text-light">Resources</a></li>
       
        </ul>
      </div>
    </div>
  </nav>

  <!-- Hero Section -->
  <section class="py-16 md:py-24 bg-gradient-to-r from-blue-400 to-blue-600 text-white">
    <div class="container mx-auto px-4">
      <div class="text-center">
        <h1 class="text-4xl md:text-6xl font-bold mb-4 animated">Understanding Autism</h1>
        <p class="text-lg md:text-xl mb-8 animated">Promoting awareness</p>
        <a href="#about" class="autism-btn inline-block px-6 py-3 rounded-lg font-semibold transition duration-300 ease-in-out hover:bg-blue-500 animated">Learn More</a>
      </div>
    </div>
  </section>

  <!-- About Section -->
  <section id="about" class="py-16">
    <div class="container mx-auto px-4">
      <div class="grid grid-cols-1 md:grid-cols-2 gap-8 items-center">
        <div>
          <h2 class="text-3xl font-bold mb-4 animated">What is Autism?</h2>
          <p class="text-lg mb-6 animated">Autism, or autism spectrum disorder (ASD), is a complex neurodevelopmental condition that affects social interaction, communication, and behavior. It is typically diagnosed in early childhood and can vary widely in severity.</p>
          <p class="text-lg animated">People with autism may have difficulty with social interactions, exhibit repetitive behaviors, and have specific interests or sensory sensitivities.</p>
        </div>
        <div>
          <img src="autism.png" alt="Autism Awareness" class="w-full rounded-lg shadow-md animated">
        </div>
      </div>
    </div>
  </section>

  <!-- Resources Section -->
  <section id="resources" class="py-16 bg-gray-100">
    <div class="container mx-auto px-4">
      <h2 class="text-3xl font-bold mb-8 text-center animated">Resources</h2>
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
        <div class="p-6 bg-white rounded-lg shadow-md animated">
          <h3 class="text-xl font-semibold mb-4">Understanding Autism</h3>
          <p class="mb-4">Learn more about autism spectrum disorder, its symptoms, and how it affects individuals.</p>
          <a href="#" class="autism-btn inline-block px-4 py-2 rounded-lg font-semibold transition duration-300 ease-in-out hover:bg-blue-500">Read More</a>
        </div>
        <div class="p-6 bg-white rounded-lg shadow-md animated">
          <h3 class="text-xl font-semibold mb-4">Support Organizations</h3>
          <p class="mb-4">Discover organizations and support groups dedicated to helping individuals with autism and their families.</p>
          <a href="#" class="autism-btn inline-block px-4 py-2 rounded-lg font-semibold transition duration-300 ease-in-out hover:bg-blue-500">Find Support</a>
        </div>
        <div class="p-6 bg-white rounded-lg shadow-md animated">
          <h3 class="text-xl font-semibold mb-4">Educational Materials</h3>
          <p class="mb-4">Access educational resources and materials for educators, parents, and caregivers of individuals with autism.</p>
          <a href="#" class="autism-btn inline-block px-4 py-2 rounded-lg font-semibold transition duration-300 ease-in-out hover:bg-blue-500">Explore Resources</a>
        </div>
      </div>
    </div>
  </section>

  
</body>
</html>
