<template>
  <div>
    <section class="bg-[#f5f7fb] relative overflow-hidden pt-[100px] md:pt-[100px]">

      <!-- GRADIENT SHAPE -->
      <div class="absolute right-0 top-0 w-[520px] h-[520px] 
                bg-gradient-to-r from-[#7C3AED] to-[#06B6D4] 
                rounded-full blur-[120px] opacity-60 
                translate-x-1/3 -translate-y-1/4">
      </div>

      <!-- MAIN -->
      <div class="max-w-6xl mx-auto px-4 md:px-6 pt-12 pb-16 
                grid grid-cols-1 md:grid-cols-2 items-center gap-10">

        <!-- LEFT -->
        <div class="text-center md:text-left">

          <!-- BADGE -->
          <div
            class="inline-flex items-center gap-2 bg-white border px-4 py-1.5 rounded-full text-sm text-gray-500 shadow-sm">
            <svg class="w-4 h-4 text-[#7C3AED]" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
              stroke-linecap="round" stroke-linejoin="round">
              <path d="M12 3l2 5 5 2-5 2-2 5-2-5-5-2 5-2z" />
            </svg>
            WELCOME TO MY PRACTICE
          </div>

          <!-- TITLE -->
          <h1 class="mt-5 text-[28px] sm:text-[34px] md:text-[40px] 
                   font-extrabold text-gray-900 leading-[1.2]">
            Dr. Rajesh
            <span class="block md:inline bg-gradient-to-r from-[#7C3AED] to-[#06B6D4] 
                       bg-clip-text text-transparent">
              Kumar
            </span>
          </h1>

          <!-- SUBTITLE -->
          <p class="mt-4 text-gray-800 font-semibold text-sm md:text-base">
            Specialist in Orthopedic & Joint Replacement Surgery
          </p>

          <!-- DESC -->
          <p class="mt-3 text-gray-500 max-w-md mx-auto md:mx-0 text-sm md:text-base">
            Providing advanced orthopedic care including joint replacement, fracture treatment,
            and minimally invasive procedures to restore mobility and improve quality of life.
          </p>

          <!-- BUTTONS -->
          <div class="mt-6 flex flex-col sm:flex-row items-center md:items-start gap-3 sm:gap-4">

            <!-- BOOK -->
            <button class="w-full sm:w-auto flex justify-center items-center gap-2 
                      bg-gradient-to-r from-[#7C3AED] to-[#06B6D4]
                         text-white px-5 py-2.5 rounded-lg shadow-md hover:opacity-90">

              <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                stroke-linecap="round" stroke-linejoin="round">
                <rect x="3" y="4" width="18" height="18" rx="2" />
                <path d="M16 2v4M8 2v4M3 10h18" />
              </svg>

              Book Appointment
            </button>

            <!-- WATCH -->
            <button class="w-full sm:w-auto flex justify-center items-center gap-2 
                         bg-white border text-gray-700 px-5 py-2.5 rounded-lg shadow-sm hover:bg-gray-50">

              <svg class="w-4 h-4" fill="currentColor" viewBox="0 0 24 24">
                <path d="M5 3l14 9-14 9V3z" />
              </svg>

              Watch Introduction
            </button>

          </div>
        </div>

        <!-- RIGHT -->
        <div class="relative flex justify-center mt-8 md:mt-0">

          <!-- SHAPE -->
          <div class="absolute w-[280px] sm:w-[320px] md:w-[360px] 
                    h-[280px] sm:h-[320px] md:h-[360px] 
                    bg-gradient-to-tr from-[#7C3AED] to-[#06B6D4] 
                    rounded-[50px] md:rounded-[60px] rotate-12 opacity-90">
          </div>

          <!-- IMAGE -->
          <img src="/images/doctor-preview.png" class="relative w-[480px]  z-10" />

          <!-- FLOAT CARD -->
          <div class="absolute bottom-2 md:bottom-4 
                    left-1/2 md:left-6 
                    -translate-x-1/2 md:translate-x-0
                    bg-white px-4 py-2 rounded-xl shadow-lg 
                    flex items-center gap-3 z-20">

            <img src="https://randomuser.me/api/portraits/men/45.jpg" class="w-9 h-9 rounded-full" />

            <div>
              <p class="text-xs md:text-sm font-semibold text-gray-800">
                Dr. Rajesh Kumar
              </p>
              <p class="text-[10px] md:text-xs text-gray-500">
                Orthopedic Surgeon
              </p>
            </div>
          </div>

        </div>
      </div>

      <!-- STATS -->
      <div class="max-w-4xl mx-auto px-4 md:px-6 pb-10 pt-3">
        <div class="bg-white rounded-xl shadow-md border 
                  flex flex-wrap md:flex-nowrap 
                  justify-center md:justify-between 
                  items-center 
                  px-4  py-2 gap-6">

          <!-- ITEM -->
          <div class="flex items-center gap-3 w-[45%] md:w-auto justify-center md:justify-start">
            <svg class="w-6 h-6 text-[#7C3AED]" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
              stroke-linecap="round" stroke-linejoin="round">
              <circle cx="12" cy="12" r="9" />
              <path d="M12 7v5l3 2" />
            </svg>
            <div>
              <p class="font-semibold">18+</p>
              <p class="text-xs text-gray-500">Experience</p>
            </div>
          </div>

          <div class="hidden md:block w-px h-10 bg-gray-200"></div>

          <div class="flex items-center gap-3 w-[45%] md:w-auto justify-center md:justify-start">
            <svg class="w-6 h-6 text-[#7C3AED]" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
              stroke-linecap="round" stroke-linejoin="round">
              <path d="M6 8a2 2 0 1 1 2-2l8 8a2 2 0 1 1-2 2l-8-8z" />
              <path d="M14 6l4 4" />
            </svg>
            <div>
              <p class="font-semibold">7,500+</p>
              <p class="text-xs text-gray-500">Surgeries</p>
            </div>
          </div>

          <div class="hidden md:block w-px h-10 bg-gray-200"></div>

          <div class="flex items-center gap-3 w-[45%] md:w-auto justify-center md:justify-start">
            <svg class="w-6 h-6 text-[#7C3AED]" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
              stroke-linecap="round" stroke-linejoin="round">
              <path d="M12 3l7 4v5c0 5-3.5 9-7 9s-7-4-7-9V7l7-4z" />
              <path d="M9 12l2 2 4-4" />
            </svg>
            <div>
              <p class="font-semibold">98%</p>
              <p class="text-xs text-gray-500">Success</p>
            </div>
          </div>

          <div class="hidden md:block w-px h-10 bg-gray-200"></div>

          <div class="flex items-center gap-3 w-[45%] md:w-auto justify-center md:justify-start">
            <svg class="w-5 h-5 text-yellow-400" viewBox="0 0 24 24" fill="currentColor">
              <path d="M12 2l3 6 6 .9-4.5 4.4 1.1 6.5L12 17l-5.6 2.8 1.1-6.5L3 8.9 9 8z" />
            </svg>
            <div>
              <p class="font-semibold">4.9/5</p>
              <p class="text-xs text-gray-500">Rating</p>
            </div>
          </div>

        </div>
      </div>

    </section>
    <section class="py-8">

      <!-- HEADER -->
      <div class="text-center mb-12">
        <p class="text-sm text-[#7C3AED] font-semibold">My Expertise</p>

        <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mt-2">
          Orthopedic Services
        </h2>

        <p class="text-gray-500 mt-2 text-sm md:text-base">
          Advanced orthopedic treatments using modern techniques and care
        </p>
      </div>

      <!-- CARDS -->
      <div class="max-w-6xl mx-auto px-4 grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-6">

        <!-- CARD 1 -->
        <div class="bg-white rounded-2xl border shadow-sm p-5 hover:shadow-md transition">
          <div class="flex items-start gap-4">

            <div class="w-12 h-12 flex items-center justify-center rounded-xl bg-purple-100">
              <!-- Joint -->
              <svg class="w-6 h-6 text-[#7C3AED]" fill="none" stroke="currentColor" stroke-width="2"
                viewBox="0 0 24 24">
                <circle cx="7" cy="12" r="3" />
                <circle cx="17" cy="12" r="3" />
                <path d="M10 12h4" />
              </svg>
            </div>

            <div>
              <h3 class="font-semibold text-gray-900 text-sm md:text-base">
                Joint Replacement Surgery
              </h3>
              <p class="text-xs text-gray-500 mt-1">
                Advanced knee and hip replacement procedures for pain-free mobility
              </p>
            </div>

          </div>
        </div>

        <!-- CARD 2 -->
        <div class="bg-white rounded-2xl border shadow-sm p-5 hover:shadow-md transition">
          <div class="flex items-start gap-4">

            <div class="w-12 h-12 flex items-center justify-center rounded-xl bg-blue-100">
              <!-- Bone fracture -->
              <svg class="w-6 h-6 text-blue-600" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                <path d="M6 8l8 8M14 6l4 4M6 16l4-4" />
              </svg>
            </div>

            <div>
              <h3 class="font-semibold text-gray-900 text-sm md:text-base">
                Fracture & Trauma Care
              </h3>
              <p class="text-xs text-gray-500 mt-1">
                Expert treatment for bone fractures and accident injuries
              </p>
            </div>

          </div>
        </div>

        <!-- CARD 3 -->
        <div class="bg-white rounded-2xl border shadow-sm p-5 hover:shadow-md transition">
          <div class="flex items-start gap-4">

            <div class="w-12 h-12 flex items-center justify-center rounded-xl bg-indigo-100">
              <!-- Arthroscopy -->
              <svg class="w-6 h-6 text-indigo-600" fill="none" stroke="currentColor" stroke-width="2"
                viewBox="0 0 24 24">
                <circle cx="12" cy="12" r="5" />
                <path d="M19 12h2M3 12h2" />
              </svg>
            </div>

            <div>
              <h3 class="font-semibold text-gray-900 text-sm md:text-base">
                Arthroscopy Surgery
              </h3>
              <p class="text-xs text-gray-500 mt-1">
                Minimally invasive joint procedures for faster recovery
              </p>
            </div>

          </div>
        </div>

        <!-- CARD 4 -->
        <div class="bg-white rounded-2xl border shadow-sm p-5 hover:shadow-md transition">
          <div class="flex items-start gap-4">

            <div class="w-12 h-12 flex items-center justify-center rounded-xl bg-orange-100">
              <!-- Spine -->
              <svg class="w-6 h-6 text-orange-500" fill="none" stroke="currentColor" stroke-width="2"
                viewBox="0 0 24 24">
                <path d="M12 2v20M9 6h6M9 12h6M9 18h6" />
              </svg>
            </div>

            <div>
              <h3 class="font-semibold text-gray-900 text-sm md:text-base">
                Spine Treatment
              </h3>
              <p class="text-xs text-gray-500 mt-1">
                Care for back pain, slipped disc, and spinal disorders
              </p>
            </div>

          </div>
        </div>

        <!-- CARD 5 -->
        <div class="bg-white rounded-2xl border shadow-sm p-5 hover:shadow-md transition">
          <div class="flex items-start gap-4">

            <div class="w-12 h-12 flex items-center justify-center rounded-xl bg-cyan-100">
              <!-- Sports -->
              <svg class="w-6 h-6 text-cyan-600" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                <circle cx="12" cy="12" r="4" />
                <path d="M2 12h4M18 12h4M12 2v4M12 18v4" />
              </svg>
            </div>

            <div>
              <h3 class="font-semibold text-gray-900 text-sm md:text-base">
                Sports Injury Treatment
              </h3>
              <p class="text-xs text-gray-500 mt-1">
                Treatment for ligament tears, sprains, and sports injuries
              </p>
            </div>

          </div>
        </div>

        <!-- CARD 6 -->
        <div class="bg-white rounded-2xl border shadow-sm p-5 hover:shadow-md transition">
          <div class="flex items-start gap-4">

            <div class="w-12 h-12 flex items-center justify-center rounded-xl bg-teal-100">
              <!-- Arthritis -->
              <svg class="w-6 h-6 text-teal-600" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                <path d="M8 12a4 4 0 1 1 8 0" />
                <path d="M6 16h12" />
              </svg>
            </div>

            <div>
              <h3 class="font-semibold text-gray-900 text-sm md:text-base">
                Arthritis Management
              </h3>
              <p class="text-xs text-gray-500 mt-1">
                Personalized care to reduce pain and improve joint function
              </p>
            </div>

          </div>
        </div>

      </div>

    </section>

    <about />
    <!-- why we choose -->
    <div class="p-6">
      <div
        class="max-w-4xl mx-auto rounded-2xl p-8 flex flex-col md:flex-row items-center justify-between gap-6 shadow-lg"
        style="background: linear-gradient(135deg, #0f172a, #1e3a8a, #0f172a);">

        <!-- Left Content (60%) -->
        <div class="w-full md:w-3/5 text-white">
          <h2 class="text-2xl font-semibold mb-4">
            Why Choose Dr. Achiri?
          </h2>

          <p class="text-sm text-gray-300 mb-6">
            Providing the advanced, experienced techniques and care.
          </p>

          <!-- Points -->
          <ul class="space-y-3">
            <li class="flex items-center gap-3">
              <span class="w-5 h-5 flex items-center justify-center bg-green-500 rounded-full text-xs">✔</span>
              <span>Board Certified & Harvard Trained</span>
            </li>

            <li class="flex items-center gap-3">
              <span class="w-5 h-5 flex items-center justify-center bg-green-500 rounded-full text-xs">✔</span>
              <span>15+ Years of Surgical Experience</span>
            </li>

            <li class="flex items-center gap-3">
              <span class="w-5 h-5 flex items-center justify-center bg-green-500 rounded-full text-xs">✔</span>
              <span>State-of-the-Art Technology</span>
            </li>

            <li class="flex items-center gap-3">
              <span class="w-5 h-5 flex items-center justify-center bg-green-500 rounded-full text-xs">✔</span>
              <span>Personalized Patient Care</span>
            </li>

            <li class="flex items-center gap-3">
              <span class="w-5 h-5 flex items-center justify-center bg-green-500 rounded-full text-xs">✔</span>
              <span>International Patient Services</span>
            </li>
          </ul>
        </div>

        <!-- Right Image (40%) -->
        <div class="w-full md:w-2/5 relative">
          <img src="https://images.unsplash.com/photo-1582750433449-648ed127bb54" alt="Doctor"
            class="rounded-2xl w-full h-72 object-cover" />

          <!-- Play Button -->
          <div class="absolute inset-0 flex items-center justify-center">
            <div class="bg-white p-4 rounded-full shadow-lg cursor-pointer hover:scale-110 transition">
              ▶
            </div>
          </div>
        </div>

      </div>
    </div>
    <section class="bg-[#f5f7fb] py-14">

      <!-- HEADER -->
      <div class="text-center mb-12">
        <p class="text-xs font-semibold text-[#7C3AED] tracking-wide uppercase">
          Patient Testimonials
        </p>

        <h2 class="text-3xl md:text-4xl font-bold text-gray-900 mt-2">
          What Patients Say
        </h2>

        <p class="text-gray-500 mt-2 text-sm">
          Trusted by thousands of patients
        </p>
      </div>

      <!-- CARDS -->
      <div class="max-w-6xl mx-auto px-4 grid grid-cols-1 md:grid-cols-3 gap-6">

        <!-- CARD -->
        <div class="bg-white border rounded-2xl p-6 shadow-sm hover:shadow-md transition">

          <!-- TOP -->
          <div class="flex items-center justify-between mb-4">

            <div class="flex items-center gap-3">
              <img src="https://randomuser.me/api/portraits/men/32.jpg" class="w-10 h-10 rounded-full object-cover" />

              <div>
                <p class="text-sm font-semibold text-gray-900">Lance Altman</p>
                <p class="text-xs text-gray-500">El Oued</p>
              </div>
            </div>

            <!-- STARS -->
            <div class="flex gap-1 text-yellow-400">
              ★★★★★
            </div>

          </div>

          <!-- RATING -->
          <div class="flex items-center gap-2 text-sm mb-2">
            <span class="text-yellow-400">★★★★★</span>
            <span class="text-gray-600 text-xs">4.9</span>
          </div>

          <!-- TEXT -->
          <p class="text-gray-500 text-sm leading-relaxed">
            "Very professional and caring doctor. The surgery went smoothly and recovery was fast."
          </p>

        </div>

        <!-- CARD -->
        <div class="bg-white border rounded-2xl p-6 shadow-sm hover:shadow-md transition">

          <div class="flex items-center justify-between mb-4">
            <div class="flex items-center gap-3">
              <img src="https://randomuser.me/api/portraits/men/45.jpg" class="w-10 h-10 rounded-full object-cover" />
              <div>
                <p class="text-sm font-semibold text-gray-900">Marc Watson</p>
                <p class="text-xs text-gray-500">Alger</p>
              </div>
            </div>

            <div class="flex gap-1 text-yellow-400">★★★★★</div>
          </div>

          <div class="flex items-center gap-2 text-sm mb-2">
            <span class="text-yellow-400">★★★★★</span>
            <span class="text-gray-600 text-xs">5.0</span>
          </div>

          <p class="text-gray-500 text-sm leading-relaxed">
            "Excellent expertise and very compassionate. Highly recommend Dr. Achir for any surgical needs."
          </p>

        </div>

        <!-- CARD -->
        <div class="bg-white border rounded-2xl p-6 shadow-sm hover:shadow-md transition">

          <div class="flex items-center justify-between mb-4">
            <div class="flex items-center gap-3">
              <img src="https://randomuser.me/api/portraits/women/44.jpg" class="w-10 h-10 rounded-full object-cover" />
              <div>
                <p class="text-sm font-semibold text-gray-900">Sally Welch</p>
                <p class="text-xs text-gray-500">Tamanrasset</p>
              </div>
            </div>

            <div class="flex gap-1 text-yellow-400">★★★★★</div>
          </div>

          <div class="flex items-center gap-2 text-sm mb-2">
            <span class="text-yellow-400">★★★★★</span>
            <span class="text-gray-600 text-xs">4.9</span>
          </div>

          <p class="text-gray-500 text-sm leading-relaxed">
            "Outstanding care from consultation to recovery. Made me feel completely comfortable."
          </p>

        </div>

      </div>

    </section>
    <div class="bg-gradient-to-r from-gray-50 to-blue-100 py-10 px-6">

      <!-- Header -->
      <div class="text-center mb-10">
        <h2 class="text-2xl font-semibold text-gray-800 flex items-center justify-center gap-2">
          💙 Health Tips & Advice
        </h2>
        <p class="text-gray-500 text-sm">
          Stay informed with Dr. Achi’s latest medical tips and advice
        </p>
      </div>

      <!-- Cards Row -->
      <div class="grid grid-cols-1 md:grid-cols-4 gap-6 max-w-6xl mx-auto">

        <!-- Card 1 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden">
          <img src="https://images.unsplash.com/photo-1584515933487-779824d29309" class="w-full h-36 object-cover" />

          <div class="p-4">
            <p class="text-xs text-gray-400 mb-1">April 10, 2025</p>

            <h3 class="font-semibold text-gray-800 text-sm mb-2">
              Tips for a Speedy Recovery After Surgery
            </h3>

            <p class="text-gray-500 text-xs mb-3">
              Learn proven strategies to enhance recovery after surgery and reduce complications.
            </p>

            <a href="#" class="text-blue-600 text-xs font-medium hover:underline">
              Read More →
            </a>
          </div>
        </div>

        <!-- Card 2 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden">
          <img src="https://images.unsplash.com/photo-1579154204601-01588f351e67" class="w-full h-36 object-cover" />

          <div class="p-4">
            <p class="text-xs text-gray-400 mb-1">April 18, 2025</p>

            <h3 class="font-semibold text-gray-800 text-sm mb-2">
              Why to Prevent Hernias; Tips and Advice
            </h3>

            <p class="text-gray-500 text-xs mb-3">
              Learn prevention tips for hernias and how lifestyle changes can help.
            </p>

            <a href="#" class="text-blue-600 text-xs font-medium hover:underline">
              Read More →
            </a>
          </div>
        </div>

        <!-- Card 3 -->
        <div class="bg-white rounded-xl shadow-md overflow-hidden">
          <img src="https://images.unsplash.com/photo-1582750433449-648ed127bb54" class="w-full h-36 object-cover" />

          <div class="p-4">
            <p class="text-xs text-gray-400 mb-1">April 11, 2025</p>

            <h3 class="font-semibold text-gray-800 text-sm mb-2">
              The Benefits of Minimally Invasive Surgery
            </h3>

            <p class="text-gray-500 text-xs mb-3">
              Discover advantages like faster recovery and reduced pain.
            </p>

            <a href="#" class="text-blue-600 text-xs font-medium hover:underline">
              Read More →
            </a>
          </div>
        </div>

        <!-- Emergency Card -->
        <div class="rounded-xl p-5 text-white flex flex-col justify-between"
          style="background: linear-gradient(135deg, #4f46e5, #9333ea);">
          <div>
            <h3 class="text-lg font-semibold mb-2 flex items-center gap-2">
              ❤️ Emergency Care Available
            </h3>

            <p class="text-sm mb-4">
              24/7 surgical emergency services
            </p>
          </div>

          <button class="border border-white rounded-lg py-2 text-sm hover:bg-white hover:text-purple-600 transition">
            📞 +213 698 96 63 26
          </button>
        </div>

      </div>
    </div>
    <!-- Top Gradient Stats Bar -->
    <div class="text-white py-6 px-4" style="background: linear-gradient(90deg, #4f46e5, #7c3aed);">
      <div class="max-w-6xl mx-auto grid grid-cols-2 md:grid-cols-4 text-center gap-6">

        <div>
          <h2 class="text-xl md:text-2xl font-bold">5,000+</h2>
          <p class="text-sm opacity-80">Successful Surgeries</p>
        </div>

        <div>
          <h2 class="text-xl md:text-2xl font-bold">98%</h2>
          <p class="text-sm opacity-80">Patient Satisfaction</p>
        </div>

        <div>
          <h2 class="text-xl md:text-2xl font-bold">15+</h2>
          <p class="text-sm opacity-80">Years Experience</p>
        </div>

        <div>
          <h2 class="text-xl md:text-2xl font-bold">24/7</h2>
          <p class="text-sm opacity-80">Emergency Care</p>
        </div>

      </div>
    </div>

    <!-- Insurance Section -->
    <div class="bg-gray-100 py-8">
      <div class="max-w-6xl mx-auto text-center">

        <h3 class="text-gray-700 font-semibold mb-6">
          We Accept Major Insurance Plans
        </h3>

        <!-- Logos -->
        <div class="flex flex-wrap justify-center gap-4">
          <span class="px-5 py-2 border border-purple-400 text-purple-600 rounded-lg text-sm font-medium">
            Aetna
          </span>
          <span class="px-5 py-2 border border-blue-400 text-blue-600 rounded-lg text-sm font-medium">
            Allianz
          </span>
          <span class="px-5 py-2 border border-indigo-400 text-indigo-600 rounded-lg text-sm font-medium">
            Cigna
          </span>
          <span class="px-5 py-2 border border-pink-400 text-pink-600 rounded-lg text-sm font-medium">
            AXA
          </span>
        </div>
      </div>
    </div>

    <div class="bg-gradient-to-br from-purple-50 via-white to-purple-100 py-12 px-6">

      <!-- Header -->
      <div class="text-center mb-12">
        <h2 class="text-3xl font-semibold text-gray-800">
          Our Clinic Locations
        </h2>
        <p class="text-gray-500 text-sm mt-2">
          Serving patients across multiple locations in Algeria
        </p>
      </div>

      <!-- Cards -->
      <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-6xl mx-auto">

        <!-- CARD -->
        <div
          class="group relative rounded-2xl p-[1px] bg-gradient-to-r from-purple-400 via-purple-500 to-indigo-500 hover:shadow-xl transition">
          <div
            class="bg-white rounded-2xl p-6 h-full group-hover:bg-gradient-to-br group-hover:from-purple-50 group-hover:to-white transition">

            <!-- Title -->
            <div class="flex items-center justify-between mb-4">
              <div class="flex items-center gap-2">
                <div class="bg-purple-100 p-2 rounded-lg">
                  <svg class="w-5 h-5 text-purple-600" fill="none" stroke="currentColor" stroke-width="2"
                    viewBox="0 0 24 24">
                    <path stroke-linecap="round" stroke-linejoin="round"
                      d="M17.657 16.657L13.414 20.9a2 2 0 01-2.828 0l-4.243-4.243a8 8 0 1111.314 0z" />
                    <path stroke-linecap="round" stroke-linejoin="round" d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                  </svg>
                </div>

                <h3 class="font-semibold text-gray-800">
                  Main Hospital - Algiers
                </h3>
              </div>

              <span class="text-xs bg-purple-100 text-purple-600 px-2 py-1 rounded-full">
                Primary
              </span>
            </div>

            <!-- Address -->
            <p class="text-gray-500 text-sm mb-3">
              Main Crossroads, B. Oued, Algiers
            </p>

            <!-- Time -->
            <div class="flex items-center gap-2 text-gray-500 text-sm mb-3">
              <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                <circle cx="12" cy="12" r="10" />
                <path d="M12 6v6l4 2" />
              </svg>
              Mon - Sat: 9:00 AM - 6:00 PM
            </div>

            <!-- Phone -->
            <div class="flex items-center gap-2 text-purple-600 text-sm font-medium mb-5">
              <svg class="w-4 h-4" fill="none" stroke="currentColor" stroke-width="2" viewBox="0 0 24 24">
                <path
                  d="M3 5a2 2 0 012-2h2.28a2 2 0 011.94 1.515l.516 2.065a2 2 0 01-.45 1.867l-1.27 1.27a16 16 0 006.586 6.586l1.27-1.27a2 2 0 011.867-.45l2.065.516A2 2 0 0121 16.72V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
              </svg>
              +213 698 96 63 26
            </div>

            <!-- Button -->
            <button
              class="w-full flex items-center justify-center gap-2 bg-gradient-to-r from-[#7C3AED] to-[#06B6D4]  text-white py-2 rounded-lg text-sm hover:opacity-90 transition">
              Get Directions
            </button>

          </div>
        </div>

        <!-- Duplicate & change content -->
        <div v-for="(item, i) in 2" :key="i"
          class="group relative rounded-2xl p-[1px] bg-gradient-to-r from-purple-400 via-purple-500 to-indigo-500 hover:shadow-xl transition">
          <div class="bg-white rounded-2xl p-6 h-full group-hover:bg-purple-50 transition">

            <div class="flex items-center gap-2 mb-4">
              <div class="bg-purple-100 p-2 rounded-lg">
                <svg class="w-5 h-5 text-purple-600" fill="none" stroke="currentColor" stroke-width="2"
                  viewBox="0 0 24 24">
                  <path d="M17.657 16.657L13.414 20.9a2 2 0 01-2.828 0l-4.243-4.243a8 8 0 1111.314 0z" />
                  <path d="M15 11a3 3 0 11-6 0 3 3 0 016 0z" />
                </svg>
              </div>
              <h3 class="font-semibold text-gray-800">
                {{ i === 0 ? 'Oran Branch' : 'Constantine Clinic' }}
              </h3>
            </div>

            <p class="text-gray-500 text-sm mb-3">
              {{ i === 0 ? 'City Center, Oran' : 'Medical District, Constantine' }}
            </p>

            <div class="flex items-center gap-2 text-gray-500 text-sm mb-3">
              <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                <circle cx="12" cy="12" r="10" />
                <path d="M12 6v6l4 2" />
              </svg>
              9:00 AM - 5:00 PM
            </div>

            <div class="flex items-center gap-2 text-purple-600 text-sm font-medium mb-5">
              <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2">
                <path
                  d="M3 5a2 2 0 012-2h2.28a2 2 0 011.94 1.515l.516 2.065a2 2 0 01-.45 1.867l-1.27 1.27a16 16 0 006.586 6.586l1.27-1.27a2 2 0 011.867-.45l2.065.516A2 2 0 0121 16.72V19a2 2 0 01-2 2h-1C9.716 21 3 14.284 3 6V5z" />
              </svg>
              +213 XXX XXX
            </div>

            <button
              class="w-full bg-gradient-to-r from-[#7C3AED] to-[#06B6D4]  text-white py-2 rounded-lg text-sm hover:opacity-90 transition">
              Get Directions
            </button>

          </div>
        </div>

      </div>
    </div>

    <section class="max-w-5xl mx-auto py-10 px-4">

      <!-- HEADER -->
      <div class="flex items-center justify-between bg-purple-50 border border-purple-100 rounded-xl p-4">
        <div>
          <h2 class="text-lg font-semibold text-gray-800">
            Frequently Asked Questions
          </h2>
          <p class="text-sm text-gray-500">
            Answers to common patient questions
          </p>
        </div>

        <button @click="toggleFAQ"
          class="text-sm font-medium border border-purple-400 text-purple-600 px-4 py-2 rounded-lg hover:bg-purple-100 transition">
          {{ showFAQ ? "Hide FAQ" : "View All FAQ →" }}
        </button>
      </div>

      <!-- FAQ LIST -->
      <div v-if="showFAQ" class="mt-6 space-y-4">
        <div v-for="(item, index) in faqs" :key="index" class="border rounded-lg p-4 cursor-pointer bg-white shadow-sm">
          <!-- QUESTION -->
          <div class="flex justify-between items-center" @click="toggleItem(index)">
            <h3 class="font-medium text-gray-800">
              {{ item.question }}
            </h3>
            <span class="text-purple-600 text-xl">
              {{ activeIndex === index ? '-' : '+' }}
            </span>
          </div>

          <!-- ANSWER -->
          <p v-if="activeIndex === index" class="mt-3 text-gray-500 text-sm">
            {{ item.answer }}
          </p>
        </div>
      </div>

    </section>

  </div>
</template>
<script>
import About from "./About.vue";
export default {
  name: "HeroSection",
  components: {
    About
  },
  data() {
    return {
      showFAQ: false,
      activeIndex: null,

      faqs: [
        {
          question: "What orthopedic conditions do you treat?",
          answer:
            "We treat joint pain, fractures, arthritis, sports injuries, and spine-related conditions using advanced medical techniques.",
        },
        {
          question: "Do you provide minimally invasive surgery?",
          answer:
            "Yes, we specialize in minimally invasive procedures that ensure faster recovery and less pain.",
        },
        {
          question: "How long does recovery take after joint replacement?",
          answer:
            "Recovery typically takes 4–8 weeks depending on the patient’s condition and rehabilitation.",
        },
        {
          question: "Do I need an appointment before visiting?",
          answer:
            "Yes, it is recommended to book an appointment to avoid waiting time.",
        },
      ],
    };
  },
  methods: {
    toggleFAQ() {
      this.showFAQ = !this.showFAQ;
    },
    toggleItem(index) {
      this.activeIndex = this.activeIndex === index ? null : index;
    },
  },
};
</script>
