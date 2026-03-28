<template>
    <header
        :class="['fixed w-full z-50 transition-all duration-300', isScrolled ? 'shadow bg-white/95 backdrop-blur' : '']">

        <!-- 🔷 TOP BAR -->
        <div class=" text-white text-sm" style="background: linear-gradient(135deg, #0B1C2C, #0F2A44);">
            <div class="max-w-7xl mx-auto px-4 py-2 
                  flex flex-wrap md:flex-nowrap 
                  justify-between items-center gap-2">

                <!-- LEFT -->
                <div class="flex items-center gap-4 flex-wrap">

                    <!-- PHONE -->
                    <a href="tel:+919876543210" class="flex items-center gap-2 whitespace-nowrap">
                        <svg class="w-4 h-4" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                            stroke-linecap="round" stroke-linejoin="round">
                            <path d="M22 16.92v3a2 2 0 0 1-2.18 2 
      19.86 19.86 0 0 1-8.63-3.07 
      19.5 19.5 0 0 1-6-6 
      19.86 19.86 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3 
      a2 2 0 0 1 2 1.72 
      12.84 12.84 0 0 0 .7 2.81 
      2 2 0 0 1-.45 2.11L8.09 9.91 
      a16 16 0 0 0 6 6l1.27-1.27 
      a2 2 0 0 1 2.11-.45 
      12.84 12.84 0 0 0 2.81.7 
      2 2 0 0 1 1.72 2z" />
                        </svg>
                        <span class="text-xs sm:text-sm">+91 98765 43210</span>
                    </a>

                    <!-- LOCATION (FIXED ICON) -->
                    <a href="https://maps.google.com/?q=Bangalore,India" target="_blank"
                        class="flex items-center gap-2 whitespace-nowrap">

                        <svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4 flex-shrink-0" viewBox="0 0 24 24"
                            fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                            stroke-linejoin="round">
                            <path d="M21 10c0 7-9 13-9 13s-9-6-9-13a9 9 0 1 1 18 0z" />
                            <circle cx="12" cy="10" r="3" />
                        </svg>

                        <span class="text-xs sm:text-sm">Bangalore</span>
                    </a>

                </div>

                <!-- RIGHT -->
                <div class="flex items-center gap-2 text-xs sm:text-sm">
                    <svg xmlns="http://www.w3.org/2000/svg" class="w-4 h-4 flex-shrink-0" viewBox="0 0 24 24"
                        fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round"
                        stroke-linejoin="round">
                        <circle cx="12" cy="12" r="10" />
                        <path d="M12 6v6l4 2" />
                    </svg>
                    <span>Mon - Sat: 9AM - 7PM</span>
                </div>

            </div>
        </div>

        <!-- 🔷 NAVBAR -->
        <nav :class="['transition-all duration-300 bg-white', isScrolled ? 'h-[60px]' : 'h-[60px]']">
            <div class="max-w-7xl mx-auto px-4 md:px-6 flex justify-between items-center h-full">

                <!-- LOGO -->
                <div class="text-lg md:text-4xl font-bold 
                    bg-gradient-to-r from-[#7C3AED] to-[#06B6D4] 
                    bg-clip-text text-transparent">
                    Dr. Achiri
                </div>

                <!-- DESKTOP MENU -->
                <ul class="hidden md:flex gap-6 font-medium text-gray-700">
                    <li><a href="#" class="hover:text-[#7C3AED]">Home</a></li>
                    <li><a href="#" class="hover:text-[#7C3AED]">Services</a></li>
                    <li><a href="#" class="hover:text-[#7C3AED]">About</a></li>
                    <li><a href="#" class="hover:text-[#7C3AED]">Testimonials</a></li>
                    <li><a href="#" class="hover:text-[#7C3AED]">FAQ</a></li>
                </ul>

                <!-- RIGHT -->
                <div class="flex items-center gap-2">

                    <!-- MOBILE CALL -->
                    <a href="tel:+919876543210" class="md:hidden bg-green-500 text-white p-2 rounded-lg">
                        <svg class="w-5 h-5" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2"
                            stroke-linecap="round" stroke-linejoin="round">
                            <path d="M22 16.92v3a2 2 0 0 1-2.18 2 
      19.86 19.86 0 0 1-8.63-3.07 
      19.5 19.5 0 0 1-6-6 
      19.86 19.86 0 0 1-3.07-8.67A2 2 0 0 1 4.11 2h3 
      a2 2 0 0 1 2 1.72 
      12.84 12.84 0 0 0 .7 2.81 
      2 2 0 0 1-.45 2.11L8.09 9.91 
      a16 16 0 0 0 6 6l1.27-1.27 
      a2 2 0 0 1 2.11-.45 
      12.84 12.84 0 0 0 2.81.7 
      2 2 0 0 1 1.72 2z" />
                        </svg>

                    </a>

                    <!-- BOOK BUTTON -->
                    <button class="hidden md:flex items-center gap-2 
                        bg-gradient-to-r from-[#7C3AED] to-[#06B6D4] text-white px-4 py-2 rounded-lg shadow-md">
                        Book Appointment
                    </button>

                    <!-- HAMBURGER -->
                    <button @click="toggleMenu" class="md:hidden">
                        <svg xmlns="http://www.w3.org/2000/svg" class="w-7 h-7" viewBox="0 0 24 24" fill="none"
                            stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round">
                            <line x1="3" y1="6" x2="21" y2="6" />
                            <line x1="3" y1="12" x2="21" y2="12" />
                            <line x1="3" y1="18" x2="21" y2="18" />
                        </svg>
                    </button>

                </div>

            </div>
        </nav>

        <!-- MOBILE MENU -->
        <div v-if="mobileMenu" class="md:hidden bg-white shadow-lg px-4 py-4 space-y-4">
            <a href="#" class="block">Home</a>
            <a href="#" class="block">Services</a>
            <a href="#" class="block">About</a>
            <a href="#" class="block">Testimonials</a>
            <a href="#" class="block">FAQ</a>

            <button class="w-full bg-gradient-to-r from-[#7C3AED] to-[#06B6D4] text-white py-2 rounded-lg">
                Book Appointment
            </button>
        </div>

    </header>
</template>

<script>
export default {
    data() {
        return {
            mobileMenu: false,
            isScrolled: false,
        };
    },
    methods: {
        toggleMenu() {
            this.mobileMenu = !this.mobileMenu;
        },
        handleScroll() {
            this.isScrolled = window.scrollY > 20;
        }
    },
    mounted() {
        window.addEventListener("scroll", this.handleScroll);
    },
    beforeUnmount() {
        window.removeEventListener("scroll", this.handleScroll);
    }
};
</script>