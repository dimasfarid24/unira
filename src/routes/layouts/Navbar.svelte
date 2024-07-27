<!-- src/routes/components/Navbar.svelte -->
<script>
    // Script untuk komponen Navbar
</script>

<style>
    /* Gaya untuk komponen Navbar */
</style>


<nav>
    <header class="flex flex-wrap sm:justify-start sm:flex-nowrap w-full bg-blue-950 text-sm py-4">
        <nav class="max-w-[85rem] w-full mx-auto px-4 sm:flex sm:items-center sm:justify-between" aria-label="Global">
          <div class="flex items-center justify-between">
            <a class="flex text-xl font-semibold " href="/">
                <img src="https://unira.ac.id/img/logo.png" class=" col-start-1 w-16 h-16" alt="">
                <div class="text-slate-300 px-2 pt-1">
                  <strong class="">UNIVERSITAS MADURA</strong>
                  <small class=" text-sm text-nowrap">Jl. Panglegur Km. 3,5 Pamekasan Jawa Timur</small>
                </div>
            </a>
            <div class="lg:hidden">
              <button type="button" class="hs-collapse-toggle p-2 inline-flex justify-center items-center gap-x-2 rounded-lg border border-gray-200 bg-white text-gray-800 shadow-sm hover:bg-gray-50 disabled:opacity-50 disabled:pointer-events-none" data-hs-collapse="#navbar-with-collapse" aria-controls="navbar-with-collapse" aria-label="Toggle navigation">
                <svg class="hs-collapse-open:hidden flex-shrink-0 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><line x1="3" x2="21" y1="6" y2="6"/><line x1="3" x2="21" y1="12" y2="12"/><line x1="3" x2="21" y1="18" y2="18"/></svg>
                <svg class="hs-collapse-open:block hidden flex-shrink-0 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="M18 6 6 18"/><path d="m6 6 12 12"/></svg>
              </button>
            </div>
          </div>
          <div id="navbar-with-collapse" class="hidden transition-all duration-[0.1ms] overflow-hidden basis-full grow lg:block">
            <div class="flex flex-col text-xs gap-5 mt-5 lg:flex-row lg:items-center lg:justify-end lg:mt-0 lg:ps-5">
              <a class="    font-medium text-gray-400 hover:text-gray-200" href="/" aria-current="page">BERANDA</a>
              <!-- dropdown Profil -->
              <div class="hs-dropdown [--trigger:hover]">
                <button id="hs-dropdown-hover-event" type="button" class=" hs-dropdown-toggle inline-flex items-center font-medium text-gray-400 shadow-sm hover:text-gray-200  disabled:opacity-50 disabled:pointer-events-none" aria-haspopup="menu" aria-expanded="false" aria-label="Dropdown">
                  PROFIL
                  <svg class="hs-dropdown-open:rotate-180 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
                </button>

                <div class="hs-dropdown-menu transition-[opacity,margin] duration hs-dropdown-open:opacity-100 opacity-0 hidden min-w-28 bg-indigo-800 shadow-md rounded-lg p-1 space-y-0.5 mt-2 after:h-4 after:absolute after:-bottom-4 after:start-0 after:w-full before:h-4 before:absolute before:-top-4 before:start-0 before:w-full" role="menu" aria-orientation="vertical" aria-labelledby="hs-dropdown-hover-event">
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="/profil/universitas-madura">
                    UNIRA
                  </a>
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="/profil/dosen">
                    Dosen
                  </a>
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="/profil/mahasiswa">
                    Mahasiswa
                  </a>
                </div>
              </div>
              <!-- end dropdown Profil -->
              <!-- dropdown Fakultas -->
              <div class="hs-dropdown [--trigger:hover]">
                <button id="hs-dropdown-hover-event" type="button" class=" hs-dropdown-toggle inline-flex items-center font-medium text-gray-400 shadow-sm hover:text-gray-200  disabled:opacity-50 disabled:pointer-events-none" aria-haspopup="menu" aria-expanded="false" aria-label="Dropdown">
                  FAKULTAS
                  <svg class="hs-dropdown-open:rotate-180 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
                </button>

                <div class="hs-dropdown-menu transition-[opacity,margin] duration hs-dropdown-open:opacity-100 opacity-0 hidden min-w-32 bg-indigo-800 shadow-md rounded-lg p-1 space-y-0.5 mt-2 after:h-4 after:absolute after:-bottom-4 after:start-0 after:w-full before:h-4 before:absolute before:-top-4 before:start-0 before:w-full" role="menu" aria-orientation="vertical" aria-labelledby="hs-dropdown-hover-event">
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="https://feb.unira.ac.id">
                    Ekonomi & Bisnis
                  </a>
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="https://fia.unira.ac.id">
                    Ilmu Administrasi
                  </a>
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="https://fp.unira.ac.id">
                    Pertanian
                  </a>
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="https://fh.unira.ac.id">
                    Hukum
                  </a>
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="https://fkip.unira.ac.id">
                    Keguruan & Ilmu Pengetahuan
                  </a>
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="https://ft.unira.ac.id">
                    Teknik
                  </a>
                </div>
              </div>
              <!-- end dropdpwn Fakultas -->
              <a class="font-medium text-gray-400 hover:text-gray-200" href="/pengumuman">PENGUMUMAN</a>
              <a class="font-medium text-gray-400 hover:text-gray-200" href="/berita">BERITA</a>
              <!-- dropdown Informasi -->
              <div class="hs-dropdown [--trigger:hover]">
                <button id="hs-dropdown-hover-event" type="button" class=" hs-dropdown-toggle inline-flex items-center font-medium text-gray-400 shadow-sm hover:text-gray-200  disabled:opacity-50 disabled:pointer-events-none" aria-haspopup="menu" aria-expanded="false" aria-label="Dropdown">
                  INFORMASI
                  <svg class="hs-dropdown-open:rotate-180 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
                </button>

                <div class="hs-dropdown-menu transition-[opacity,margin] duration hs-dropdown-open:opacity-100 opacity-0 hidden min-w-32 bg-indigo-800 shadow-md rounded-lg p-1 space-y-0.5 mt-2 after:h-4 after:absolute after:-bottom-4 after:start-0 after:w-full before:h-4 before:absolute before:-top-4 before:start-0 before:w-full" role="menu" aria-orientation="vertical" aria-labelledby="hs-dropdown-hover-event">
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="/kegiatan">
                    Kegiatan
                  </a>
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="/galeri">
                    Galeri
                  </a>
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="/kerjasama">
                    Kerjasama
                  </a>
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="/unira-dalam-angka">
                    Unira Dalam Angka
                  </a>
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="/tentang-madura">
                    Tentang Madura
                  </a>
                </div>
              </div>
              <!-- end dropdown Informasi -->
              <!-- dropdown Penelitian & Pengabdian -->
              <div class="hs-dropdown [--trigger:hover]">
                <button id="hs-dropdown-hover-event" type="button" class=" hs-dropdown-toggle inline-flex items-center font-medium text-gray-400 text-nowrap shadow-sm hover:text-gray-200  disabled:opacity-50 disabled:pointer-events-none" aria-haspopup="menu" aria-expanded="false" aria-label="Dropdown">
                  PENELITIAN & PENGABDIAN
                  <svg class="hs-dropdown-open:rotate-180 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
                </button>

                <div class="hs-dropdown-menu transition-[opacity,margin] duration hs-dropdown-open:opacity-100 opacity-0 hidden min-w-32 bg-indigo-800 shadow-md rounded-lg p-1 space-y-0.5 mt-2 after:h-4 after:absolute after:-bottom-4 after:start-0 after:w-full before:h-4 before:absolute before:-top-4 before:start-0 before:w-full" role="menu" aria-orientation="vertical" aria-labelledby="hs-dropdown-hover-event">
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="/penelitian">
                    Penelitian
                  </a>
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="/pengabdian">
                    Pengabdian Masyarakat
                  </a>
                </div>
              </div>
              <!-- end dropdown Penelitian & Pengabdian -->
              <!-- dropdown Layanan Kampus -->
              <div class="hs-dropdown [--trigger:hover]">
                <button id="hs-dropdown-hover-event" type="button" class=" hs-dropdown-toggle inline-flex items-center font-medium text-gray-400 text-nowrap shadow-sm hover:text-gray-200  disabled:opacity-50 disabled:pointer-events-none" aria-haspopup="menu" aria-expanded="false" aria-label="Dropdown">
                  LAYANAN KAMPUS
                  <svg class="hs-dropdown-open:rotate-180 size-4" xmlns="http://www.w3.org/2000/svg" width="24" height="24" viewBox="0 0 24 24" fill="none" stroke="currentColor" stroke-width="2" stroke-linecap="round" stroke-linejoin="round"><path d="m6 9 6 6 6-6"/></svg>
                </button>

                <div class="hs-dropdown-menu transition-[opacity,margin] duration hs-dropdown-open:opacity-100 opacity-0 hidden min-w-32 bg-indigo-800 shadow-md rounded-lg p-1 space-y-0.5 mt-2 after:h-4 after:absolute after:-bottom-4 after:start-0 after:w-full before:h-4 before:absolute before:-top-4 before:start-0 before:w-full" role="menu" aria-orientation="vertical" aria-labelledby="hs-dropdown-hover-event">
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="/">
                    Pendaftaran Mahasiswa Baru (PMB)
                  </a>
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="/">
                    Sistem Informasi Akademik Terpadu (SIMAT)
                  </a>
                  <a class="flex items-center gap-x-3.5 py-2 px-3 rounded-lg text-xs text-slate-100 hover:bg-gray-100 hover:text-black" href="/">
                    Sistem Informasi Sumber Daya Terintegrasi (SISTER)
                  </a>
                </div>
              </div>
              <!-- end dropdown Layanan Kampus -->
            </div>
          </div>
        </nav>
      </header>
</nav>