<html lang="vi">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0" />
  <title>CÔNG TY TNHH NHÔM KÍNH NHẬT PHÁT | Cửa Nhôm Xingfa &amp; Kính Cường Lực Đà Nẵng</title>
  <meta name="description" content="CÔNG TY TNHH NHÔM KÍNH NHẬT PHÁT - Chuyên thiết kế, sản xuất và thi công Cửa nhôm Xingfa, Cửa kính cường lực, Cửa nhựa lõi thép, Cầu thang kính, Kính ốp bếp, Phòng tắm kính uy tín tại Đà Nẵng. Hotline: 0905 586 981." />

  <!-- Meta Open Graph & Twitter Thumbnail sử dụng Logo công ty khi chia sẻ link qua Zalo/Facebook -->
  <meta property="og:type" content="website" />
  <meta property="og:site_name" content="nhomkinhnhatphat.com" />
  <meta property="og:title" content="CÔNG TY TNHH NHÔM KÍNH NHẬT PHÁT - Nhôm Kính Xingfa Đà Nẵng" />
  <meta property="og:description" content="Thi công Cửa nhôm Xingfa nhập khẩu, Cửa kính cường lực, Cầu thang kính, Phòng tắm kính tại Đà Nẵng. Địa chỉ: 253/11 Nguyễn Hoàng, Hải Châu, Đà Nẵng. Hotline: 0905 586 981." />
  <meta property="og:url" content="https://nhomkinhnhatphat.com/" />
  <meta property="og:image" content="https://nhomkinhnhatphat.com/wp-content/uploads/logo-nhom-kinh-nhat-phat.png" />
  <meta property="og:image:alt" content="Logo Công Ty TNHH Nhôm Kính Nhật Phát" />
  <meta property="og:image:width" content="1200" />
  <meta property="og:image:height" content="630" />
  <meta name="twitter:card" content="summary_large_image" />
  <meta name="twitter:title" content="CÔNG TY TNHH NHÔM KÍNH NHẬT PHÁT" />
  <meta name="twitter:description" content="Cửa nhôm Xingfa &amp; Kính cường lực chất lượng tại Đà Nẵng - Hotline: 0905 586 981" />
  <meta name="twitter:image" content="https://nhomkinhnhatphat.com/wp-content/uploads/logo-nhom-kinh-nhat-phat.png" />

  <!-- Favicon SVG Logo Nhật Phát -->
  <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230B3D6B'/%3E%3Crect x='8' y='8' width='48' height='48' rx='7' fill='none' stroke='%23E59400' stroke-width='3'/%3E%3Cpath d='M18 44V20h6l11 15V20h5v24h-6L23 29v15z' fill='%23FFFFFF'/%3E%3Ccircle cx='46' cy='18' r='5' fill='%23E59400'/%3E%3C/svg%3E" />

  <!-- Google Font Inter -->
  <link rel="preconnect" href="https://fonts.googleapis.com" />
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet" />

  <!-- Font Awesome Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />

  <!-- Tailwind CSS CDN -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          },
          colors: {
            brand: {
              dark: '#082E52',
              primary: '#0B3D6B',
              secondary: '#1565A8',
              light: '#EAF2FA',
              accent: '#E59400',
              accentHover: '#C98000',
            }
          }
        }
      }
    }
  </script>

  <style>
    /* Reset chuẩn chống tràn viền & đảm bảo hiển thị ổn định trên mọi trình duyệt */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100%;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      color: #1E293B;
      background-color: #FFFFFF;
      scroll-behavior: smooth;
      -webkit-font-smoothing: antialiased;
    }

    /* Chiều ngang giao diện 95% trên máy tính, tối ưu gọn gàng trên điện thoại */
    .flatsome-container {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 12px;
      padding-right: 12px;
    }
    @media (min-width: 1024px) {
      .flatsome-container {
        width: 95%;
        max-width: 95%;
        padding-left: 0;
        padding-right: 0;
      }
    }

    /* Menu Dropdown kiểu Flatsome mượt mà */
    .nav-dropdown {
      opacity: 0;
      visibility: hidden;
      transform: translateY(8px);
      transition: all 0.2s ease;
    }
    .nav-item:hover > .nav-dropdown,
    .nav-item:focus-within > .nav-dropdown {
      opacity: 1;
      visibility: visible;
      transform: translateY(0);
    }

    /* Đường gạch chân tiêu đề chuẩn Flatsome */
    .section-title-wrap {
      position: relative;
      display: flex;
      align-items: center;
      justify-content: center;
      margin-bottom: 1.5rem;
    }
    .section-title-wrap::before,
    .section-title-wrap::after {
      content: "";
      flex: 1;
      height: 2px;
      background-color: #E2E8F0;
      max-width: 180px;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline nổi */
    @keyframes phonePulse {
      0% { box-shadow: 0 0 0 0 rgba(229, 148, 0, 0.55); }
      70% { box-shadow: 0 0 0 12px rgba(229, 148, 0, 0); }
      100% { box-shadow: 0 0 0 0 rgba(229, 148, 0, 0); }
    }
    .pulse-hotline {
      animation: phonePulse 2s infinite;
    }

    /* Ẩn thanh cuộn ngang phụ */
    .no-scrollbar::-webkit-scrollbar {
      display: none;
    }
    .no-scrollbar {
      -ms-overflow-style: none;
      scrollbar-width: none;
    }

    /* Banner Slider chuyển động mượt */
    .banner-slide {
      transition: opacity 0.6s ease, transform 0.6s ease;
    }
  </style>
</head>
<body class="bg-white text-slate-800 antialiased">

  <!-- ==================== TOP BAR (FLATSOME STYLE - SẠCH SẼ, KHÔNG CÓ THANH EDIT UX BUILDER) ==================== -->
  <div class="bg-brand-primary text-white text-xs py-2 border-b border-brand-dark">
    <div class="flatsome-container flex flex-wrap items-center justify-between gap-2">
      <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
        <span class="inline-flex items-center gap-1.5">
          <i class="fa-solid fa-location-dot text-brand-accent"></i>
          <span>253/11 Nguyễn Hoàng, Phường Hải Châu, TP Đà Nẵng</span>
        </span>
        <span class="hidden sm:inline-flex items-center gap-1.5">
          <i class="fa-regular fa-clock text-brand-accent"></i>
          <span>Làm việc: 07:30 - 20:00 (T2 - CN)</span>
        </span>
      </div>
      <div class="flex items-center gap-4">
        <a href="tel:0905586981" class="inline-flex items-center gap-1.5 font-semibold hover:text-brand-accent transition-colors">
          <i class="fa-solid fa-phone text-brand-accent"></i>
          <span>0905 586 981</span>
        </a>
        <span class="hidden md:inline text-white/40">|</span>
        <span class="hidden md:inline text-white/90">nhomkinhnhatphat.com</span>
      </div>
    </div>
  </div>

  <!-- ==================== HEADER & NAVIGATION (LOGO GỌN NHỎ, KHÔNG NÚT GỌI NGAY, MENU 1 HÀNG KHÔNG XUỐNG DÒNG CHỮ) ==================== -->
  <header id="main-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur-md shadow-sm border-b border-slate-200 w-full">
    <div class="flatsome-container py-2.5 flex items-center justify-between gap-3">

      <!-- Logo Công Ty TNHH Nhôm Kính Nhật Phát (Thiết kế gọn, nhỏ, chuyên nghiệp) -->
      <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group" aria-label="Trang chủ Nhôm Kính Nhật Phát">
        <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="Logo Nhôm Kính Nhật Phát">
          <defs>
            <linearGradient id="npGrad" x1="0%" y1="0%" x2="100%" y2="100%">
              <stop offset="0%" stop-color="#0B3D6B" />
              <stop offset="100%" stop-color="#1565A8" />
            </linearGradient>
          </defs>
          <!-- Khung cửa nhôm kiến trúc -->
          <rect x="2" y="2" width="60" height="60" rx="12" fill="url(#npGrad)" />
          <rect x="7" y="7" width="50" height="50" rx="8" fill="none" stroke="#E59400" stroke-width="2.2" />
          <!-- Mặt trời Nhật Phát ở góc trên phải -->
          <circle cx="47" cy="17" r="4.5" fill="#E59400" />
          <!-- Chữ lồng NP sắc nét -->
          <path d="M16 45V20h5.2l10.2 14.5V20h4.8v25h-5L20.8 30.2V45H16z" fill="#FFFFFF" />
          <path d="M40 28h5.5c3.6 0 6 2.1 6 5.4 0 3.4-2.4 5.5-6 5.5h-1.8V45H40V28zm3.7 7.6h1.6c1.5 0 2.5-.8 2.5-2.2s-1-2.1-2.5-2.1h-1.6v4.3z" fill="#E59400" />
        </svg>
        <div class="leading-tight">
          <div class="text-[13px] sm:text-[15px] font-extrabold tracking-tight text-brand-primary whitespace-nowrap">
            NHÔM KÍNH <span class="text-brand-accent">NHẬT PHÁT</span>
          </div>
          <div class="text-[9.5px] sm:text-[10px] font-semibold text-slate-500 tracking-wide uppercase whitespace-nowrap">
            nhomkinhnhatphat.com
          </div>
        </div>
      </a>

      <!-- Menu Máy Tính: Chữ nhỏ gọn, viết liền trên 1 hàng, tuyệt đối không xuống dòng tên danh mục -->
      <nav class="hidden lg:flex items-center justify-end flex-wrap gap-x-1 xl:gap-x-2 gap-y-1" aria-label="Menu chính">
        <a href="#trang-chu" class="px-2 py-2 text-[12px] xl:text-[13px] font-bold text-brand-primary hover:text-brand-accent whitespace-nowrap transition-colors">
          Trang chủ
        </a>
        <a href="#gioi-thieu" class="px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap transition-colors">
          Giới thiệu
        </a>

        <!-- Dropdown: Cửa nhôm xingfa -->
        <div class="nav-item relative">
          <a href="#san-pham" onclick="filterProducts('xingfa')" class="inline-flex items-center gap-1 px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap transition-colors">
            <span>Cửa nhôm xingfa</span>
            <i class="fa-solid fa-chevron-down text-[9px] text-slate-400"></i>
          </a>
          <div class="nav-dropdown absolute left-0 top-full pt-1 w-56 z-50">
            <ul class="bg-white rounded-lg shadow-xl border border-slate-200 py-1.5 text-[13px]">
              <li><a href="#san-pham" onclick="filterProducts('xingfa', '1 cánh')" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium whitespace-nowrap">Cửa nhôm xingfa 1 cánh</a></li>
              <li><a href="#san-pham" onclick="filterProducts('xingfa', '2 cánh')" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium whitespace-nowrap">Cửa nhôm xingfa 2 cánh</a></li>
              <li><a href="#san-pham" onclick="filterProducts('xingfa', '3 cánh')" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium whitespace-nowrap">Cửa nhôm xingfa 3 cánh</a></li>
              <li><a href="#san-pham" onclick="filterProducts('xingfa', '4 cánh')" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium whitespace-nowrap">Cửa nhôm xingfa 4 cánh</a></li>
              <li><a href="#san-pham" onclick="filterProducts('xingfa', '5 cánh')" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium whitespace-nowrap">Cửa nhôm xingfa 5 cánh</a></li>
            </ul>
          </div>
        </div>

        <a href="#san-pham" onclick="filterProducts('kinh-cuong-luc')" class="px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap transition-colors">
          Cửa kính cường lực
        </a>

        <!-- Dropdown: Sản phẩm -->
        <div class="nav-item relative">
          <a href="#danh-muc" class="inline-flex items-center gap-1 px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap transition-colors">
            <span>Sản phẩm</span>
            <i class="fa-solid fa-chevron-down text-[9px] text-slate-400"></i>
          </a>
          <div class="nav-dropdown absolute left-0 top-full pt-1 w-52 z-50">
            <ul class="bg-white rounded-lg shadow-xl border border-slate-200 py-1.5 text-[13px]">
              <li><a href="#san-pham" onclick="filterProducts('xingfa')" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium whitespace-nowrap">Cửa nhôm xingfa</a></li>
              <li><a href="#san-pham" onclick="filterProducts('nhua-loi-thep')" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium whitespace-nowrap">Cửa nhựa lõi thép</a></li>
              <li><a href="#san-pham" onclick="filterProducts('cua-tu-dong')" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium whitespace-nowrap">Cửa kính tự động</a></li>
              <li><a href="#san-pham" onclick="filterProducts('cau-thang-kinh')" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium whitespace-nowrap">Cầu thang kính</a></li>
              <li><a href="#san-pham" onclick="filterProducts('kinh-op-bep')" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium whitespace-nowrap">Kính ốp bếp</a></li>
              <li><a href="#san-pham" onclick="filterProducts('phong-tam-kinh')" class="block px-4 py-2 text-slate-700 hover:bg-brand-light hover:text-brand-primary font-medium whitespace-nowrap">Phòng tắm kính</a></li>
            </ul>
          </div>
        </div>

        <a href="#cong-trinh" class="px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap transition-colors">
          Công trình
        </a>
        <a href="#bao-gia" class="px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap transition-colors">
          Báo giá
        </a>
        <a href="#tin-tuc" class="px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap transition-colors">
          Tin tức
        </a>
        <a href="#lien-he" class="px-2 py-2 text-[12px] xl:text-[13px] font-semibold text-slate-700 hover:text-brand-primary whitespace-nowrap transition-colors">
          Liên hệ
        </a>
      </nav>

      <!-- Nút mở Menu Mobile (Chỉ hiển thị dưới 1024px) -->
      <button id="mobile-menu-btn" type="button" onclick="toggleMobileMenu(true)" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-primary hover:bg-brand-light transition-colors" aria-label="Mở danh mục">
        <i class="fa-solid fa-bars text-lg"></i>
      </button>
    </div>
  </header>

  <!-- ==================== MOBILE OFF-CANVAS DRAWER (FLATSOME STYLE) ==================== -->
  <div id="mobile-menu-overlay" onclick="toggleMobileMenu(false)" class="fixed inset-0 bg-slate-900/50 z-50 hidden transition-opacity"></div>
  <aside id="mobile-menu-drawer" class="fixed top-0 left-0 h-full w-[82%] max-w-[320px] bg-white z-50 shadow-2xl transform -translate-x-full transition-transform duration-300 flex flex-col">
    <div class="p-4 bg-brand-primary text-white flex items-center justify-between">
      <div class="font-bold text-sm tracking-wide">DANH MỤC NHẬT PHÁT</div>
      <button type="button" onclick="toggleMobileMenu(false)" class="w-8 h-8 rounded-lg bg-white/15 flex items-center justify-center text-white hover:bg-white/25" aria-label="Đóng menu">
        <i class="fa-solid fa-xmark"></i>
      </button>
    </div>
    <nav class="flex-1 overflow-y-auto divide-y divide-slate-100 text-sm">
      <a href="#trang-chu" onclick="toggleMobileMenu(false)" class="block px-4 py-3 font-semibold text-brand-primary hover:bg-brand-light">Trang chủ</a>
      <a href="#gioi-thieu" onclick="toggleMobileMenu(false)" class="block px-4 py-3 font-semibold text-slate-700 hover:bg-brand-light">Giới thiệu</a>

      <!-- Accordion: Cửa nhôm xingfa -->
      <div>
        <button type="button" onclick="toggleSubmenu('mob-sub-xingfa', 'mob-icon-xingfa')" class="w-full px-4 py-3 font-semibold text-slate-700 hover:bg-brand-light flex items-center justify-between text-left">
          <span>Cửa nhôm xingfa</span>
          <i id="mob-icon-xingfa" class="fa-solid fa-chevron-down text-xs text-slate-400 transition-transform"></i>
        </button>
        <div id="mob-sub-xingfa" class="hidden bg-slate-50 divide-y divide-slate-100">
          <a href="#san-pham" onclick="filterProducts('xingfa', '1 cánh'); toggleMobileMenu(false)" class="block pl-8 pr-4 py-2.5 text-slate-600 hover:text-brand-primary">Cửa nhôm xingfa 1 cánh</a>
          <a href="#san-pham" onclick="filterProducts('xingfa', '2 cánh'); toggleMobileMenu(false)" class="block pl-8 pr-4 py-2.5 text-slate-600 hover:text-brand-primary">Cửa nhôm xingfa 2 cánh</a>
          <a href="#san-pham" onclick="filterProducts('xingfa', '3 cánh'); toggleMobileMenu(false)" class="block pl-8 pr-4 py-2.5 text-slate-600 hover:text-brand-primary">Cửa nhôm xingfa 3 cánh</a>
          <a href="#san-pham" onclick="filterProducts('xingfa', '4 cánh'); toggleMobileMenu(false)" class="block pl-8 pr-4 py-2.5 text-slate-600 hover:text-brand-primary">Cửa nhôm xingfa 4 cánh</a>
          <a href="#san-pham" onclick="filterProducts('xingfa', '5 cánh'); toggleMobileMenu(false)" class="block pl-8 pr-4 py-2.5 text-slate-600 hover:text-brand-primary">Cửa nhôm xingfa 5 cánh</a>
        </div>
      </div>

      <a href="#san-pham" onclick="filterProducts('kinh-cuong-luc'); toggleMobileMenu(false)" class="block px-4 py-3 font-semibold text-slate-700 hover:bg-brand-light">Cửa kính cường lực</a>

      <!-- Accordion: Sản phẩm -->
      <div>
        <button type="button" onclick="toggleSubmenu('mob-sub-sp', 'mob-icon-sp')" class="w-full px-4 py-3 font-semibold text-slate-700 hover:bg-brand-light flex items-center justify-between text-left">
          <span>Sản phẩm</span>
          <i id="mob-icon-sp" class="fa-solid fa-chevron-down text-xs text-slate-400 transition-transform"></i>
        </button>
        <div id="mob-sub-sp" class="hidden bg-slate-50 divide-y divide-slate-100">
          <a href="#san-pham" onclick="filterProducts('xingfa'); toggleMobileMenu(false)" class="block pl-8 pr-4 py-2.5 text-slate-600 hover:text-brand-primary">Cửa nhôm xingfa</a>
          <a href="#san-pham" onclick="filterProducts('nhua-loi-thep'); toggleMobileMenu(false)" class="block pl-8 pr-4 py-2.5 text-slate-600 hover:text-brand-primary">Cửa nhựa lõi thép</a>
          <a href="#san-pham" onclick="filterProducts('cua-tu-dong'); toggleMobileMenu(false)" class="block pl-8 pr-4 py-2.5 text-slate-600 hover:text-brand-primary">Cửa kính tự động</a>
          <a href="#san-pham" onclick="filterProducts('cau-thang-kinh'); toggleMobileMenu(false)" class="block pl-8 pr-4 py-2.5 text-slate-600 hover:text-brand-primary">Cầu thang kính</a>
          <a href="#san-pham" onclick="filterProducts('kinh-op-bep'); toggleMobileMenu(false)" class="block pl-8 pr-4 py-2.5 text-slate-600 hover:text-brand-primary">Kính ốp bếp</a>
          <a href="#san-pham" onclick="filterProducts('phong-tam-kinh'); toggleMobileMenu(false)" class="block pl-8 pr-4 py-2.5 text-slate-600 hover:text-brand-primary">Phòng tắm kính</a>
        </div>
      </div>

      <a href="#cong-trinh" onclick="toggleMobileMenu(false)" class="block px-4 py-3 font-semibold text-slate-700 hover:bg-brand-light">Công trình</a>
      <a href="#bao-gia" onclick="toggleMobileMenu(false)" class="block px-4 py-3 font-semibold text-slate-700 hover:bg-brand-light">Báo giá</a>
      <a href="#tin-tuc" onclick="toggleMobileMenu(false)" class="block px-4 py-3 font-semibold text-slate-700 hover:bg-brand-light">Tin tức</a>
      <a href="#lien-he" onclick="toggleMobileMenu(false)" class="block px-4 py-3 font-semibold text-slate-700 hover:bg-brand-light">Liên hệ</a>
    </nav>
    <div class="p-4 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 space-y-1.5">
      <div class="font-bold text-brand-primary">CÔNG TY TNHH NHÔM KÍNH NHẬT PHÁT</div>
      <div><i class="fa-solid fa-phone text-brand-accent mr-1.5"></i>0905 586 981</div>
      <div><i class="fa-solid fa-location-dot text-brand-accent mr-1.5"></i>253/11 Nguyễn Hoàng, Hải Châu, Đà Nẵng</div>
    </div>
  </aside>

  <!-- ==================== 2 BANNER TỰ TRƯỢT CHUYÊN NGHIỆP (KÍCH THƯỚC BẰNG NHAU, CHỮ CÁCH XA VIỀN, KHÔNG CẮT CHỮ TRÊN MOBILE & PC) ==================== -->
  <section id="trang-chu" class="w-full bg-slate-100 py-3 sm:py-4">
    <div class="flatsome-container">
      <!-- Container khóa chiều cao đồng nhất cho cả 2 slide -->
      <div id="hero-slider" class="relative w-full rounded-xl overflow-hidden shadow-md bg-brand-dark grid" style="min-height: 330px;">

        <!-- SLIDE 1 -->
        <div class="banner-slide col-start-1 row-start-1 relative w-full h-full flex items-center opacity-100 z-10" data-slide="0">
          <!-- Ảnh nền công trình thực tế với lớp phủ xanh đồng bộ logo -->
          <img
            src="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&sz=w1600"
            data-drive-id="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
            onerror="handleDriveImgError(this, '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ', 'Nhom+Kinh+Nhat+Phat')"
            alt="Thi công cửa nhôm Xingfa Nhật Phát Đà Nẵng"
            class="absolute inset-0 w-full h-full object-cover object-center"
          />
          <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/95 via-brand-primary/85 to-brand-primary/55"></div>

          <!-- Nội dung chữ đặt trong khung an toàn cách xa viền (px-12 sm:px-16 md:px-20 py-10 sm:py-12 md:py-16) -->
          <div class="relative z-10 w-full px-11 sm:px-16 md:px-20 py-10 sm:py-12 md:py-14 grid grid-cols-1 md:grid-cols-12 items-center gap-6">
            <div class="md:col-span-7 space-y-3 sm:space-y-4 text-white">
              <div class="text-[11px] sm:text-xs font-bold uppercase tracking-widest text-brand-accent">
                CÔNG TY TNHH NHÔM KÍNH NHẬT PHÁT
              </div>
              <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                Cửa Nhôm Xingfa Nhập Khẩu Chính Hãng Tại Đà Nẵng
              </h1>
              <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-xl">
                Chuyên gia công, lắp đặt cửa nhôm Xingfa tem đỏ Quảng Đông, phụ kiện Kinlong đồng bộ, kính cường lực an toàn với giá tận xưởng.
              </p>
              <div class="pt-1 flex flex-wrap items-center gap-3">
                <a href="#form-bao-gia" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-xs sm:text-sm shadow transition-colors">
                  <i class="fa-solid fa-file-invoice-dollar"></i>
                  <span>Nhận Báo Giá Ngay</span>
                </a>
                <a href="#san-pham" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white font-semibold text-xs sm:text-sm transition-colors">
                  <span>Xem Sản Phẩm</span>
                </a>
              </div>
            </div>
            <div class="hidden md:flex md:col-span-5 justify-end">
              <div class="w-full max-w-[340px] aspect-[4/3] rounded-xl overflow-hidden border-2 border-white/25 shadow-xl bg-white/10">
                <img
                  src="https://drive.google.com/thumbnail?id=1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-&sz=w1000"
                  data-drive-id="1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-"
                  onerror="handleDriveImgError(this, '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-', 'Cua+Nhom+Xingfa')"
                  alt="Cửa đi mở quay 4 cánh nhôm Xingfa Nhật Phát"
                  class="w-full h-full object-cover"
                />
              </div>
            </div>
          </div>
        </div>

        <!-- SLIDE 2 (Kích thước và bố cục hoàn toàn bằng Slide 1) -->
        <div class="banner-slide col-start-1 row-start-1 relative w-full h-full flex items-center opacity-0 pointer-events-none z-0" data-slide="1">
          <img
            src="https://drive.google.com/thumbnail?id=1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ&sz=w1600"
            data-drive-id="1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ"
            onerror="handleDriveImgError(this, '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ', 'Du+An+Nhật+Phat')"
            alt="Thi công kính cường lực và công trình khách sạn Đà Nẵng"
            class="absolute inset-0 w-full h-full object-cover object-center"
          />
          <div class="absolute inset-0 bg-gradient-to-r from-brand-dark/95 via-brand-primary/85 to-brand-secondary/55"></div>

          <div class="relative z-10 w-full px-11 sm:px-16 md:px-20 py-10 sm:py-12 md:py-14 grid grid-cols-1 md:grid-cols-12 items-center gap-6">
            <div class="md:col-span-7 space-y-3 sm:space-y-4 text-white">
              <div class="text-[11px] sm:text-xs font-bold uppercase tracking-widest text-brand-accent">
                THI CÔNG TRỌN GÓI NHÀ PHỐ - KHÁCH SẠN - RESORT
              </div>
              <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold leading-snug text-white">
                Cửa Kính Cường Lực, Cầu Thang &amp; Phòng Tắm Kính
              </h2>
              <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-xl">
                Khảo sát đo đạc tận nơi tại Đà Nẵng, thi công đúng tiến độ, bảo hành dài hạn. Liên hệ trực tiếp hotline 0905 586 981 để được tư vấn miễn phí.
              </p>
              <div class="pt-1 flex flex-wrap items-center gap-3">
                <a href="#cong-trinh" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-xs sm:text-sm shadow transition-colors">
                  <i class="fa-solid fa-building"></i>
                  <span>Xem Công Trình Thực Tế</span>
                </a>
                <a href="tel:0905586981" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2.5 rounded-lg bg-white/15 hover:bg-white/25 border border-white/30 text-white font-semibold text-xs sm:text-sm transition-colors">
                  <i class="fa-solid fa-phone"></i>
                  <span>0905 586 981</span>
                </a>
              </div>
            </div>
            <div class="hidden md:flex md:col-span-5 justify-end">
              <div class="w-full max-w-[340px] aspect-[4/3] rounded-xl overflow-hidden border-2 border-white/25 shadow-xl bg-white/10">
                <img
                  src="https://drive.google.com/thumbnail?id=1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH&sz=w1000"
                  data-drive-id="1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH"
                  onerror="handleDriveImgError(this, '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH', 'Phong+Tam+Kinh')"
                  alt="Thi công phòng tắm kính cường lực tại Đà Nẵng"
                  class="w-full h-full object-cover"
                />
              </div>
            </div>
          </div>
        </div>

        <!-- Nút điều hướng Banner đặt sát mép ngoài, nhỏ gọn không che chữ -->
        <button type="button" onclick="prevSlide()" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/30 hover:bg-brand-accent text-white flex items-center justify-center transition-colors">
          <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button type="button" onclick="nextSlide()" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/30 hover:bg-brand-accent text-white flex items-center justify-center transition-colors">
          <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Chấm chỉ báo Slide -->
        <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" onclick="goToSlide(0)" class="slider-dot w-6 h-2 rounded-full bg-brand-accent transition-all" aria-label="Slide 1"></button>
          <button type="button" onclick="goToSlide(1)" class="slider-dot w-2 h-2 rounded-full bg-white/60 hover:bg-white transition-all" aria-label="Slide 2"></button>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== DANH MỤC SẢN PHẨM NỔI BẬT (THEO WEB MẪU, CHỮ NHỎ GỌN, ĐẸP TRÊN PC & MOBILE) ==================== -->
  <section id="danh-muc" class="py-8 sm:py-10 bg-white">
    <div class="flatsome-container">
      <div class="section-title-wrap">
        <h2 class="px-4 text-base sm:text-xl font-extrabold uppercase tracking-wide text-brand-primary text-center">
          Danh Mục Sản Phẩm
        </h2>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
        <!-- Danh mục 1: Cửa nhôm xingfa -->
        <a href="#san-pham" onclick="filterProducts('xingfa')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-primary transition-all flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX&sz=w800"
              onerror="handleDriveImgError(this, '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX', 'Cua+Nhom+Xingfa')"
              alt="Cửa nhôm xingfa"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="p-2.5 text-center bg-white flex-1 flex items-center justify-center">
            <h3 class="text-[11.5px] sm:text-[12.5px] font-bold uppercase text-brand-primary group-hover:text-brand-accent transition-colors leading-snug">
              Cửa nhôm xingfa
            </h3>
          </div>
        </a>

        <!-- Danh mục 2: Cửa nhựa lõi thép -->
        <a href="#san-pham" onclick="filterProducts('nhua-loi-thep')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-primary transition-all flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA&sz=w800"
              onerror="handleDriveImgError(this, '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA', 'Cua+Nhua+Loi+Thep')"
              alt="Cửa nhựa lõi thép"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="p-2.5 text-center bg-white flex-1 flex items-center justify-center">
            <h3 class="text-[11.5px] sm:text-[12.5px] font-bold uppercase text-brand-primary group-hover:text-brand-accent transition-colors leading-snug">
              Cửa nhựa lõi thép
            </h3>
          </div>
        </a>

        <!-- Danh mục 3: Cửa kính tự động -->
        <a href="#san-pham" onclick="filterProducts('cua-tu-dong')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-primary transition-all flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ&sz=w800"
              onerror="handleDriveImgError(this, '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ', 'Cua+Kinh+Tu+Dong')"
              alt="Cửa kính tự động"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="p-2.5 text-center bg-white flex-1 flex items-center justify-center">
            <h3 class="text-[11.5px] sm:text-[12.5px] font-bold uppercase text-brand-primary group-hover:text-brand-accent transition-colors leading-snug">
              Cửa kính tự động
            </h3>
          </div>
        </a>

        <!-- Danh mục 4: Cầu thang kính -->
        <a href="#san-pham" onclick="filterProducts('cau-thang-kinh')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-primary transition-all flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul&sz=w800"
              onerror="handleDriveImgError(this, '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul', 'Cau+Thang+Kinh')"
              alt="Cầu thang kính"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="p-2.5 text-center bg-white flex-1 flex items-center justify-center">
            <h3 class="text-[11.5px] sm:text-[12.5px] font-bold uppercase text-brand-primary group-hover:text-brand-accent transition-colors leading-snug">
              Cầu thang kính
            </h3>
          </div>
        </a>

        <!-- Danh mục 5: Kính ốp bếp -->
        <a href="#san-pham" onclick="filterProducts('kinh-op-bep')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-primary transition-all flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb&sz=w800"
              onerror="handleDriveImgError(this, '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb', 'Kinh+Op+Bep')"
              alt="Kính ốp bếp"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="p-2.5 text-center bg-white flex-1 flex items-center justify-center">
            <h3 class="text-[11.5px] sm:text-[12.5px] font-bold uppercase text-brand-primary group-hover:text-brand-accent transition-colors leading-snug">
              Kính ốp bếp
            </h3>
          </div>
        </a>

        <!-- Danh mục 6: Phòng tắm kính -->
        <a href="#san-pham" onclick="filterProducts('phong-tam-kinh')" class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-primary transition-all flex flex-col">
          <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH&sz=w800"
              onerror="handleDriveImgError(this, '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH', 'Phong+Tam+Kinh')"
              alt="Phòng tắm kính"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="p-2.5 text-center bg-white flex-1 flex items-center justify-center">
            <h3 class="text-[11.5px] sm:text-[12.5px] font-bold uppercase text-brand-primary group-hover:text-brand-accent transition-colors leading-snug">
              Phòng tắm kính
            </h3>
          </div>
        </a>
      </div>
    </div>
  </section>

  <!-- ==================== GIỚI THIỆU CÔNG TY TNHH NHÔM KÍNH NHẬT PHÁT ==================== -->
  <section id="gioi-thieu" class="py-9 sm:py-12 bg-slate-50 border-y border-slate-200/80">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-center">
        <div class="lg:col-span-7 space-y-3.5">
          <div class="text-xs font-bold uppercase tracking-wider text-brand-accent">
            VỀ CHÚNG TÔI
          </div>
          <h2 class="text-lg sm:text-2xl font-extrabold text-brand-primary leading-snug">
            CÔNG TY TNHH NHÔM KÍNH NHẬT PHÁT - ĐƠN VỊ THI CÔNG NHÔM KÍNH UY TÍN TẠI ĐÀ NẴNG
          </h2>
          <p class="text-sm text-slate-600 leading-relaxed">
            <strong>Công Ty TNHH Nhôm Kính Nhật Phát</strong> là đơn vị chuyên thiết kế, gia công sản xuất và thi công lắp đặt trọn gói các hạng mục nhôm kính cao cấp tại Đà Nẵng và khu vực Miền Trung. Các dòng sản phẩm chủ lực bao gồm: <strong>Cửa nhôm Xingfa nhập khẩu tem đỏ Quảng Đông</strong>, Cửa kính cường lực, Cửa nhựa lõi thép, Cửa kính tự động, Cầu thang kính, Kính ốp bếp và Phòng tắm kính.
          </p>
          <p class="text-sm text-slate-600 leading-relaxed">
            Với phương châm đặt chất lượng và sự bền vững của công trình lên hàng đầu, Nhật Phát luôn sử dụng vật tư chính hãng, máy móc ép góc hiện đại cùng chính sách bảo hành minh bạch, mang lại không gian sang trọng, cách âm cách nhiệt và an toàn cho mọi ngôi nhà, biệt thự và khách sạn.
          </p>

          <!-- 4 chỉ số nổi bật giống bố cục Flatsome mẫu -->
          <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 pt-2">
            <div class="bg-white rounded-xl p-3 border border-slate-200 text-center">
              <div class="text-xl sm:text-2xl font-extrabold text-brand-primary">150+</div>
              <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5 font-medium">Dự án hoàn thành</div>
            </div>
            <div class="bg-white rounded-xl p-3 border border-slate-200 text-center">
              <div class="text-xl sm:text-2xl font-extrabold text-brand-primary">50+</div>
              <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5 font-medium">Thợ giàu kinh nghiệm</div>
            </div>
            <div class="bg-white rounded-xl p-3 border border-slate-200 text-center">
              <div class="text-xl sm:text-2xl font-extrabold text-brand-primary">100+</div>
              <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5 font-medium">Mẫu mã đa dạng</div>
            </div>
            <div class="bg-white rounded-xl p-3 border border-slate-200 text-center">
              <div class="text-xl sm:text-2xl font-extrabold text-brand-accent">100%</div>
              <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5 font-medium">Khách hàng hài lòng</div>
            </div>
          </div>
        </div>

        <div class="lg:col-span-5">
          <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5 shadow-sm space-y-3">
            <div class="aspect-[16/10] w-full rounded-lg overflow-hidden bg-slate-100">
              <img
                src="https://drive.google.com/thumbnail?id=1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy&sz=w1000"
                onerror="handleDriveImgError(this, '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy', 'Nhom+Kinh+Nhat+Phat')"
                alt="Thi công công trình Công Ty TNHH Nhôm Kính Nhật Phát"
                class="w-full h-full object-cover"
                loading="lazy"
              />
            </div>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-2.5 text-xs sm:text-[13px] text-slate-700 pt-1">
              <div class="flex items-center gap-2">
                <i class="fa-solid fa-circle-check text-brand-accent shrink-0"></i>
                <span>Khảo sát &amp; tư vấn miễn phí</span>
              </div>
              <div class="flex items-center gap-2">
                <i class="fa-solid fa-circle-check text-brand-accent shrink-0"></i>
                <span>Nhôm Xingfa nhập khẩu 100%</span>
              </div>
              <div class="flex items-center gap-2">
                <i class="fa-solid fa-circle-check text-brand-accent shrink-0"></i>
                <span>Giá trực tiếp tại xưởng</span>
              </div>
              <div class="flex items-center gap-2">
                <i class="fa-solid fa-circle-check text-brand-accent shrink-0"></i>
                <span>Bảo hành dài hạn tận nơi</span>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== SẢN PHẨM NỔI BẬT (2 CỘT TRÊN MOBILE, GIÁ & GIẢM GIÁ % GÓC TRÊN BÊN TRÁI, TÊN ĐẦY ĐỦ KHÔNG THIẾU CHỮ) ==================== -->
  <section id="san-pham" class="py-10 sm:py-12 bg-white">
    <div class="flatsome-container">
      <div class="section-title-wrap">
        <h2 class="px-4 text-base sm:text-xl font-extrabold uppercase tracking-wide text-brand-primary text-center">
          Sản Phẩm Cửa Nhôm Xingfa &amp; Kính Cường Lực
        </h2>
      </div>

      <!-- Thanh lọc danh mục sản phẩm gọn gàng -->
      <div id="product-filter-bar" class="flex flex-wrap items-center justify-center gap-2 mb-6">
        <button type="button" data-filter="all" onclick="filterProducts('all')" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-brand-primary text-white border border-brand-primary transition-colors">
          Tất cả
        </button>
        <button type="button" data-filter="xingfa" onclick="filterProducts('xingfa')" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-colors">
          Cửa nhôm Xingfa
        </button>
        <button type="button" data-filter="kinh-cuong-luc" onclick="filterProducts('kinh-cuong-luc')" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-colors">
          Cửa kính cường lực
        </button>
        <button type="button" data-filter="nhua-loi-thep" onclick="filterProducts('nhua-loi-thep')" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-colors">
          Cửa nhựa lõi thép
        </button>
        <button type="button" data-filter="cua-tu-dong" onclick="filterProducts('cua-tu-dong')" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-colors">
          Cửa kính tự động
        </button>
        <button type="button" data-filter="cau-thang-kinh" onclick="filterProducts('cau-thang-kinh')" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-colors">
          Cầu thang kính
        </button>
        <button type="button" data-filter="kinh-op-bep" onclick="filterProducts('kinh-op-bep')" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-colors">
          Kính ốp bếp
        </button>
        <button type="button" data-filter="phong-tam-kinh" onclick="filterProducts('phong-tam-kinh')" class="filter-btn px-3.5 py-1.5 rounded-lg text-xs sm:text-[13px] font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-colors">
          Phòng tắm kính
        </button>
      </div>

      <!-- Thông báo đang lọc theo cánh (nếu có) -->
      <div id="subfilter-notice" class="hidden text-center mb-4">
        <span class="inline-flex items-center gap-2 text-xs font-medium text-brand-primary bg-brand-light px-3 py-1.5 rounded-lg">
          <span id="subfilter-text"></span>
          <button type="button" onclick="filterProducts('all')" class="text-brand-accent font-bold hover:underline ml-1">Xem tất cả</button>
        </span>
      </div>

      <!-- Lưới sản phẩm: 2 cột trên điện thoại (grid-cols-2), 3 cột trên tablet, 4 cột trên màn hình lớn -->
      <div id="product-grid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
        <!-- Dữ liệu sản phẩm được render tự động bằng JavaScript bên dưới -->
      </div>
    </div>
  </section>

  <!-- ==================== BẢNG BÁO GIÁ THAM KHẢO NHANH (CHUẨN FLATSOME) ==================== -->
  <section id="bao-gia" class="py-10 sm:py-12 bg-slate-50 border-y border-slate-200/80">
    <div class="flatsome-container">
      <div class="section-title-wrap">
        <h2 class="px-4 text-base sm:text-xl font-extrabold uppercase tracking-wide text-brand-primary text-center">
          Bảng Báo Giá Cửa Nhôm Xingfa &amp; Kính Cường Lực
        </h2>
      </div>
      <p class="text-center text-xs sm:text-sm text-slate-600 max-w-2xl mx-auto mb-6">
        Đơn giá áp dụng cho công trình tại Đà Nẵng (đã bao gồm kính an toàn 6.38mm / cường lực 8mm-10mm, gioăng EPDM, keo silicon chịu nước và công lắp đặt hoàn thiện).
      </p>

      <div class="grid grid-cols-1 lg:grid-cols-2 gap-5">
        <!-- Bảng 1: Cửa nhôm Xingfa Quảng Đông -->
        <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden">
          <div class="bg-brand-primary text-white px-4 py-3 font-bold text-sm">
            1. Cửa Nhôm Xingfa Quảng Đông Tem Đỏ (Hệ 55 / 93)
          </div>
          <div class="overflow-x-auto">
            <table class="w-full text-left border-collapse text-xs sm:text-sm">
              <thead>
                <tr class="bg-brand-light text-brand-primary border-b border-slate-200">
                  <th class="py-2.5 px-3 font-bold">Hạng mục cửa</th>
                  <th class="py-2.5 px-3 font-bold">Độ dày</th>
                  <th class="py-2.5 px-3 font-bold text-right">Đơn giá / m²</th>
                </tr>
              </thead>
              <tbody class="divide-y divide-slate-100 text-slate-700">
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">Cửa đi mở quay 1, 2, 3, 4 cánh</td>
                  <td class="py-2.5 px-3">2.0 mm</td>
                  <td class="py-2.5 px-3 text-right font-bold text-brand-accent">1.850.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">Cửa đi xếp trượt gấp nhiều cánh</td>
                  <td class="py-2.5 px-3">2.0 mm</td>
                  <td class="py-2.5 px-3 text-right font-bold text-brand-accent">1.950.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">Cửa sổ mở quay / mở hất 1-2 cánh</td>
                  <td class="py-2.5 px-3">1.4 mm</td>
                  <td class="py-2.5 px-3 text-right font-bold text-brand-accent">1.700.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">Cửa đi &amp; cửa sổ mở trượt hệ 93</td>
                  <td class="py-2.5 px-3">2.0 mm</td>
                  <td class="py-2.5 px-3 text-right font-bold text-brand-accent">1.750.000 ₫</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">Vách kính cố định khung nhôm Xingfa</td>
                  <td class="py-2.5 px-3">1.4 mm</td>
                  <td class="py-2.5 px-3 text-right font-bold text-brand-accent">1.450.000 ₫</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>

        <!-- Bảng 2: Cửa kính cường lực & Hạng mục kính -->
        <div class="bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden">
          <div class="bg-brand-secondary text-white px-4 py-3 font-bold text-sm">
            2. Cửa Kính Cường Lực, Cầu Thang, Kính Bếp &amp; Phòng Tắm
          </div>
          <div class="overflow-x-auto">
            <table class="w-full text-left border-collapse text-xs sm:text-sm">
              <thead>
                <tr class="bg-brand-light text-brand-primary border-b border-slate-200">
                  <th class="py-2.5 px-3 font-bold">Hạng mục kính cường lực</th>
                  <th class="py-2.5 px-3 font-bold">Quy cách</th>
                  <th class="py-2.5 px-3 font-bold text-right">Đơn giá tham khảo</th>
                </tr>
              </thead>
              <tbody class="divide-y divide-slate-100 text-slate-700">
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">Cửa kính cường lực bản lề sàn</td>
                  <td class="py-2.5 px-3">Kính 10mm - 12mm</td>
                  <td class="py-2.5 px-3 text-right font-bold text-brand-accent">750.000 ₫/m²</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">Phòng tắm kính cường lực 10mm</td>
                  <td class="py-2.5 px-3">Phụ kiện Inox 304</td>
                  <td class="py-2.5 px-3 text-right font-bold text-brand-accent">820.000 ₫/m²</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">Cầu thang kính cường lực tay vịn gỗ/inox</td>
                  <td class="py-2.5 px-3">Kính 10mm</td>
                  <td class="py-2.5 px-3 text-right font-bold text-brand-accent">1.250.000 ₫/md</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">Kính ốp bếp cường lực sơn màu</td>
                  <td class="py-2.5 px-3">Kính 8mm</td>
                  <td class="py-2.5 px-3 text-right font-bold text-brand-accent">720.000 ₫/md</td>
                </tr>
                <tr class="hover:bg-slate-50">
                  <td class="py-2.5 px-3 font-medium">Cửa kính trượt tự động Hàn Quốc/Nhật</td>
                  <td class="py-2.5 px-3">Trọn bộ Motor</td>
                  <td class="py-2.5 px-3 text-right font-bold text-brand-accent">Liên hệ</td>
                </tr>
              </tbody>
            </table>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG ==================== -->
  <section id="cong-trinh" class="py-10 sm:py-12 bg-white">
    <div class="flatsome-container">
      <div class="section-title-wrap">
        <h2 class="px-4 text-base sm:text-xl font-extrabold uppercase tracking-wide text-brand-primary text-center">
          Các Dự Án Tiêu Biểu Tại Đà Nẵng
        </h2>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-5">
        <!-- Dự án 1 -->
        <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ&sz=w1000"
              onerror="handleDriveImgError(this, '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ', 'Khach+San+Ruby+Light')"
              alt="DỰ ÁN KHÁCH SẠN RUBY LIGHT"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-sm sm:text-[15px] font-bold text-brand-primary group-hover:text-brand-accent transition-colors leading-snug">
              DỰ ÁN KHÁCH SẠN RUBY LIGHT
            </h3>
            <p class="text-xs text-slate-500 mt-2">
              Hạng mục: Hệ thống cửa nhôm Xingfa mặt tiền, vách kính cường lực và cabin phòng tắm kính tại Đà Nẵng.
            </p>
          </div>
        </article>

        <!-- Dự án 2 -->
        <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&sz=w1000"
              onerror="handleDriveImgError(this, '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ', 'My+Son+Heritage+Resort')"
              alt="DỰ ÁN RESORT MỸ SƠN 4 SAO MY SON HERITAGE RESORT & SPA"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-sm sm:text-[15px] font-bold text-brand-primary group-hover:text-brand-accent transition-colors leading-snug">
              DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT &amp; SPA”
            </h3>
            <p class="text-xs text-slate-500 mt-2">
              Hạng mục: Cửa đi mở trượt, cửa xếp trượt nhôm Xingfa cách âm cao cấp cho toàn bộ khu nghỉ dưỡng.
            </p>
          </div>
        </article>

        <!-- Dự án 3 -->
        <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy&sz=w1000"
              onerror="handleDriveImgError(this, '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy', 'Khach+San+Golden+Line')"
              alt="THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-sm sm:text-[15px] font-bold text-brand-primary group-hover:text-brand-accent transition-colors leading-snug">
              THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE
            </h3>
            <p class="text-xs text-slate-500 mt-2">
              Hạng mục: Vách kính mặt dựng nhôm hệ 65, cửa sảnh kính tự động và lan can kính cường lực.
            </p>
          </div>
        </article>

        <!-- Dự án 4 -->
        <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64&sz=w1000"
              onerror="handleDriveImgError(this, '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64', 'Khach+San+Jolia')"
              alt="THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-sm sm:text-[15px] font-bold text-brand-primary group-hover:text-brand-accent transition-colors leading-snug">
              THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA
            </h3>
            <p class="text-xs text-slate-500 mt-2">
              Hạng mục: Cửa sổ mở hất, cửa đi ban công nhôm Xingfa sơn tĩnh điện chống ăn mòn hơi biển.
            </p>
          </div>
        </article>

        <!-- Dự án 5 -->
        <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt&sz=w1000"
              onerror="handleDriveImgError(this, '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt', 'Khach+San+Soho')"
              alt="THI CÔNG DỰ ÁN KHÁCH SẠN SOHO"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-sm sm:text-[15px] font-bold text-brand-primary group-hover:text-brand-accent transition-colors leading-snug">
              THI CÔNG DỰ ÁN KHÁCH SẠN SOHO
            </h3>
            <p class="text-xs text-slate-500 mt-2">
              Hạng mục: Hệ cửa nhôm kính hộp cách âm, vách tắm kính và cầu thang kính cường lực hiện đại.
            </p>
          </div>
        </article>

        <!-- Dự án 6 -->
        <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=1za_IJpAm850uulT6IuhBsk1THb3LuPuc&sz=w1000"
              onerror="handleDriveImgError(this, '1za_IJpAm850uulT6IuhBsk1THb3LuPuc', 'Raon+Da+Nang+Hotel')"
              alt="THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between">
            <h3 class="text-sm sm:text-[15px] font-bold text-brand-primary group-hover:text-brand-accent transition-colors leading-snug">
              THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL
            </h3>
            <p class="text-xs text-slate-500 mt-2">
              Hạng mục: Toàn bộ cửa kính cường lực chịu áp lực gió biển cao và cửa nhôm Xingfa đồng bộ.
            </p>
          </div>
        </article>
      </div>
    </div>
  </section>

  <!-- ==================== FORM YÊU CẦU TƯ VẤN & BÁO GIÁ NGAY TRANG CHỦ ==================== -->
  <section id="form-bao-gia" class="py-10 sm:py-12 bg-brand-primary text-white">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-8 items-center">
        <!-- Cột trái: Thông tin cam kết -->
        <div class="lg:col-span-5 space-y-4">
          <div class="text-xs font-bold uppercase tracking-widest text-brand-accent">
            TƯ VẤN &amp; BÁO GIÁ MIỄN PHÍ
          </div>
          <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold leading-snug">
            Đăng Ký Nhận Báo Giá Chi Tiết Theo Kích Thước Công Trình
          </h2>
          <p class="text-sm text-slate-200 leading-relaxed">
            Để lại thông tin hạng mục bạn đang quan tâm, đội ngũ kỹ thuật của <strong>Nhôm Kính Nhật Phát</strong> sẽ liên hệ tư vấn mẫu mã, khảo sát thực tế tại Đà Nẵng và gửi bảng dự toán chính xác trong vòng 15 phút.
          </p>
          <div class="space-y-2.5 text-sm pt-1">
            <div class="flex items-center gap-3">
              <span class="w-8 h-8 rounded-lg bg-white/10 flex items-center justify-center text-brand-accent shrink-0">
                <i class="fa-solid fa-phone"></i>
              </span>
              <div>
                <div class="text-xs text-slate-300">Hotline / Zalo hỗ trợ 24/7</div>
                <a href="tel:0905586981" class="font-bold text-base hover:text-brand-accent">0905 586 981</a>
              </div>
            </div>
            <div class="flex items-center gap-3">
              <span class="w-8 h-8 rounded-lg bg-white/10 flex items-center justify-center text-brand-accent shrink-0">
                <i class="fa-solid fa-location-dot"></i>
              </span>
              <div>
                <div class="text-xs text-slate-300">Văn phòng &amp; Xưởng sản xuất</div>
                <div class="font-medium text-sm">253/11 Nguyễn Hoàng, Phường Hải Châu, TP Đà Nẵng</div>
              </div>
            </div>
          </div>
        </div>

        <!-- Cột phải: Form gửi yêu cầu -->
        <div class="lg:col-span-7">
          <form id="quote-form" onsubmit="handleQuoteSubmit(event)" class="bg-white text-slate-800 rounded-xl p-5 sm:p-6 shadow-xl space-y-4">
            <h3 class="text-base sm:text-lg font-extrabold text-brand-primary border-b border-slate-100 pb-2.5">
              Form Yêu Cầu Tư Vấn &amp; Báo Giá
            </h3>
            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="q-name" class="block text-xs font-bold text-slate-700 mb-1">Họ và tên *</label>
                <input id="q-name" name="name" type="text" required placeholder="Nhập họ tên của bạn..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/20" />
              </div>
              <div>
                <label for="q-phone" class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                <input id="q-phone" name="phone" type="tel" required placeholder="Ví dụ: 0905 586 981" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/20" />
              </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
              <div>
                <label for="q-category" class="block text-xs font-bold text-slate-700 mb-1">Hạng mục cần báo giá</label>
                <select id="q-category" name="category" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm bg-white focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/20">
                  <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa</option>
                  <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                  <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                  <option value="Cửa kính tự động">Cửa kính tự động</option>
                  <option value="Cầu thang kính">Cầu thang kính</option>
                  <option value="Kính ốp bếp">Kính ốp bếp</option>
                  <option value="Phòng tắm kính">Phòng tắm kính</option>
                </select>
              </div>
              <div>
                <label for="q-area" class="block text-xs font-bold text-slate-700 mb-1">Địa chỉ công trình / Diện tích dự kiến</label>
                <input id="q-area" name="area" type="text" placeholder="Ví dụ: Hải Châu, Đà Nẵng - 25m2" class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/20" />
              </div>
            </div>

            <div>
              <label for="q-note" class="block text-xs font-bold text-slate-700 mb-1">Nội dung yêu cầu chi tiết</label>
              <textarea id="q-note" name="note" rows="3" placeholder="Ghi chú số lượng bộ cửa, màu nhôm (xám ghi, đen, trắng sứ, vân gỗ)..." class="w-full px-3.5 py-2.5 rounded-lg border border-slate-300 text-sm focus:outline-none focus:border-brand-primary focus:ring-2 focus:ring-brand-primary/20"></textarea>
            </div>

            <button type="submit" class="w-full sm:w-auto px-6 py-3 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white font-bold text-sm shadow transition-colors inline-flex items-center justify-center gap-2">
              <i class="fa-solid fa-paper-plane"></i>
              <span>Gửi Yêu Cầu Báo Giá</span>
            </button>
          </form>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== DANH MỤC CÁC BÀI VIẾT / TIN TỨC NỔI BẬT TRANG CHỦ ==================== -->
  <section id="tin-tuc" class="py-10 sm:py-12 bg-white">
    <div class="flatsome-container">
      <div class="section-title-wrap">
        <h2 class="px-4 text-base sm:text-xl font-extrabold uppercase tracking-wide text-brand-primary text-center">
          Tin Tức &amp; Kinh Nghiệm Nhôm Kính
        </h2>
      </div>

      <!-- Danh mục bài viết trang chủ -->
      <div class="flex flex-wrap items-center justify-center gap-2 mb-6">
        <button type="button" onclick="filterPosts('all', this)" class="post-cat-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-brand-primary text-white border border-brand-primary transition-colors">
          Tất cả bài viết
        </button>
        <button type="button" onclick="filterPosts('tu-van-xingfa', this)" class="post-cat-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-colors">
          Tư vấn Cửa nhôm Xingfa
        </button>
        <button type="button" onclick="filterPosts('kinh-cuong-luc', this)" class="post-cat-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-colors">
          Kinh nghiệm Kính cường lực
        </button>
        <button type="button" onclick="filterPosts('bao-gia-thi-cong', this)" class="post-cat-btn px-3.5 py-1.5 rounded-lg text-xs font-semibold bg-white text-slate-700 border border-slate-200 hover:border-brand-primary hover:text-brand-primary transition-colors">
          Cẩm nang báo giá &amp; thi công
        </button>
      </div>

      <div id="post-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-5">
        <!-- Bài viết được render bởi JavaScript -->
      </div>
    </div>
  </section>

  <!-- ==================== ĐỐI TÁC CỦA CHÚNG TÔI ==================== -->
  <section id="doi-tac" class="py-9 sm:py-11 bg-slate-50 border-t border-slate-200/80">
    <div class="flatsome-container">
      <div class="section-title-wrap">
        <h2 class="px-4 text-base sm:text-xl font-extrabold uppercase tracking-wide text-brand-primary text-center">
          Đối Tác Của Chúng Tôi
        </h2>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4 items-center">
        <div class="bg-white rounded-xl border border-slate-200 p-3 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:border-brand-primary transition-colors">
          <img src="https://drive.google.com/thumbnail?id=13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk&sz=w600" onerror="handleDriveImgError(this, '13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk', 'Doi+Tac+1')" alt="Đối tác cung cấp nhôm kính 1" class="max-h-full max-w-full object-contain" loading="lazy" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:border-brand-primary transition-colors">
          <img src="https://drive.google.com/thumbnail?id=1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq&sz=w600" onerror="handleDriveImgError(this, '1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq', 'Doi+Tac+2')" alt="Đối tác cung cấp nhôm kính 2" class="max-h-full max-w-full object-contain" loading="lazy" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:border-brand-primary transition-colors">
          <img src="https://drive.google.com/thumbnail?id=1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn&sz=w600" onerror="handleDriveImgError(this, '1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn', 'Doi+Tac+3')" alt="Đối tác cung cấp nhôm kính 3" class="max-h-full max-w-full object-contain" loading="lazy" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:border-brand-primary transition-colors">
          <img src="https://drive.google.com/thumbnail?id=1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT&sz=w600" onerror="handleDriveImgError(this, '1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT', 'Doi+Tac+4')" alt="Đối tác cung cấp nhôm kính 4" class="max-h-full max-w-full object-contain" loading="lazy" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:border-brand-primary transition-colors">
          <img src="https://drive.google.com/thumbnail?id=1SDcarhnX0yypmqdbawICjYBRtFnKngn-&sz=w600" onerror="handleDriveImgError(this, '1SDcarhnX0yypmqdbawICjYBRtFnKngn-', 'Doi+Tac+5')" alt="Đối tác cung cấp nhôm kính 5" class="max-h-full max-w-full object-contain" loading="lazy" />
        </div>
        <div class="bg-white rounded-xl border border-slate-200 p-3 h-20 sm:h-24 flex items-center justify-center shadow-sm hover:border-brand-primary transition-colors">
          <img src="https://drive.google.com/thumbnail?id=1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg&sz=w600" onerror="handleDriveImgError(this, '1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg', 'Doi+Tac+6')" alt="Đối tác cung cấp nhôm kính 6" class="max-h-full max-w-full object-contain" loading="lazy" />
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== BẢN ĐỒ GOOGLE MAP & FANPAGE FACEBOOK NGAY TRANG CHỦ ==================== -->
  <section id="lien-he" class="py-10 sm:py-12 bg-white border-t border-slate-200/80">
    <div class="flatsome-container">
      <div class="section-title-wrap">
        <h2 class="px-4 text-base sm:text-xl font-extrabold uppercase tracking-wide text-brand-primary text-center">
          Bản Đồ Chỉ Đường &amp; Fanpage Facebook
        </h2>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
        <!-- Cột trái: Google Map trực tiếp trên trang chủ -->
        <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
          <div class="px-4 py-3 bg-brand-light border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 text-brand-primary font-bold text-sm">
              <i class="fa-solid fa-map-location-dot text-brand-accent"></i>
              <span>253/11 Nguyễn Hoàng, Phường Hải Châu, TP Đà Nẵng</span>
            </div>
            <a href="https://maps.google.com/?q=253/11+Nguy%E1%BB%85n+Ho%C3%A0ng,+H%E1%BA%A3i+Ch%C3%A2u,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-brand-secondary hover:underline">
              Mở Google Maps <i class="fa-solid fa-arrow-up-right-from-square text-[10px]"></i>
            </a>
          </div>
          <div class="w-full flex-1 min-h-[280px] sm:min-h-[320px] bg-slate-100">
            <iframe
              title="Bản đồ Công Ty TNHH Nhôm Kính Nhật Phát - 253/11 Nguyễn Hoàng, Hải Châu, Đà Nẵng"
              src="https://maps.google.com/maps?q=253%2F11%20Nguy%E1%BB%85n%20Ho%C3%A0ng%2C%20H%E1%BA%A3i%20Ch%C3%A2u%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
              class="w-full h-full min-h-[280px] sm:min-h-[320px] border-0"
              loading="lazy"
              referrerpolicy="no-referrer-when-downgrade">
            </iframe>
          </div>
        </div>

        <!-- Cột phải: Fanpage Facebook đưa ra ngoài trang chủ -->
        <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
          <div class="px-4 py-3 bg-brand-light border-b border-slate-200 flex items-center justify-between">
            <div class="flex items-center gap-2 text-brand-primary font-bold text-sm">
              <i class="fa-brands fa-facebook text-[#1877F2] text-base"></i>
              <span>Fanpage Facebook Chính Thức</span>
            </div>
            <span class="text-xs text-slate-500">Cập nhật hàng ngày</span>
          </div>

          <!-- Khung Fanpage Facebook trực quan (Tương thích mượt khi chèn Page Plugin hoặc nhúng link fanpage thực tế trên UX Builder) -->
          <div class="p-4 flex-1 flex flex-col justify-between gap-4">
            <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm">
              <!-- Ảnh bìa Fanpage -->
              <div class="relative h-36 bg-brand-dark overflow-hidden">
                <img
                  src="https://drive.google.com/thumbnail?id=1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ&sz=w800"
                  onerror="handleDriveImgError(this, '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ', 'Fanpage+Nhat+Phat')"
                  alt="Ảnh bìa Fanpage Công Ty TNHH Nhôm Kính Nhật Phát"
                  class="w-full h-full object-cover opacity-75"
                  loading="lazy"
                />
                <div class="absolute inset-0 bg-gradient-to-t from-black/80 via-black/30 to-transparent"></div>
                <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                  <!-- Avatar Logo Fanpage -->
                  <div class="w-12 h-12 rounded-lg bg-white p-1 shadow shrink-0 flex items-center justify-center">
                    <svg class="w-full h-full" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
                      <rect x="2" y="2" width="60" height="60" rx="10" fill="#0B3D6B" />
                      <rect x="7" y="7" width="50" height="50" rx="6" fill="none" stroke="#E59400" stroke-width="2.5" />
                      <circle cx="47" cy="17" r="4.5" fill="#E59400" />
                      <path d="M16 45V20h5.2l10.2 14.5V20h4.8v25h-5L20.8 30.2V45H16z" fill="#FFFFFF" />
                      <path d="M40 28h5.5c3.6 0 6 2.1 6 5.4 0 3.4-2.4 5.5-6 5.5h-1.8V45H40V28zm3.7 7.6h1.6c1.5 0 2.5-.8 2.5-2.2s-1-2.1-2.5-2.1h-1.6v4.3z" fill="#E59400" />
                    </svg>
                  </div>
                  <div class="text-white min-w-0">
                    <div class="font-bold text-sm leading-tight truncate">
                      Nhôm Kính Nhật Phát - Đà Nẵng
                    </div>
                    <div class="text-[11px] text-slate-200 mt-0.5">
                      4.850 người theo dõi · Công ty nhôm kính
                    </div>
                  </div>
                </div>
              </div>

              <!-- Nội dung bài đăng mới nhất trên Fanpage -->
              <div class="p-3.5 bg-slate-50 space-y-2.5 text-xs text-slate-600">
                <p class="leading-relaxed">
                  Cập nhật các công trình thi công thực tế cửa nhôm Xingfa, phòng tắm kính, cầu thang kính tại Hải Châu, Sơn Trà, Cẩm Lệ, Hòa Xuân - Đà Nẵng cùng ưu đãi lắp đặt trọn gói.
                </p>
                <div class="flex flex-wrap items-center gap-2 pt-1">
                  <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-1.5 px-3 py-2 rounded-lg bg-[#1877F2] hover:bg-[#166FE5] text-white font-bold text-xs transition-colors">
                    <i class="fa-brands fa-facebook-f"></i>
                    <span>Thích Trang</span>
                  </a>
                  <a href="https://m.me/" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-1.5 px-3 py-2 rounded-lg bg-white hover:bg-slate-100 text-slate-800 border border-slate-300 font-bold text-xs transition-colors">
                    <i class="fa-brands fa-facebook-messenger text-[#0084FF]"></i>
                    <span>Nhắn Tin Ngay</span>
                  </a>
                </div>
              </div>
            </div>

            <!-- Thông tin liên hệ trực tiếp -->
            <div class="bg-brand-light/70 rounded-xl p-3.5 text-xs text-slate-700 space-y-1.5">
              <div class="font-bold text-brand-primary">LIÊN HỆ NHANH QUA ZALO / HOTLINE</div>
              <div>Điện thoại &amp; Zalo: <a href="tel:0905586981" class="font-bold text-brand-accent">0905 586 981</a></div>
              <div>Website: <span class="font-semibold text-brand-primary">nhomkinhnhatphat.com</span></div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- ==================== FOOTER CHUẨN FLATSOME ==================== -->
  <footer class="bg-brand-dark text-slate-200 pt-10 pb-6 border-t-4 border-brand-accent">
    <div class="flatsome-container">
      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-white/10">

        <!-- Cột 1: Thông tin công ty -->
        <div class="space-y-3">
          <div class="flex items-center gap-2.5">
            <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" xmlns="http://www.w3.org/2000/svg">
              <rect x="2" y="2" width="60" height="60" rx="12" fill="#0B3D6B" />
              <rect x="7" y="7" width="50" height="50" rx="8" fill="none" stroke="#E59400" stroke-width="2.5" />
              <circle cx="47" cy="17" r="4.5" fill="#E59400" />
              <path d="M16 45V20h5.2l10.2 14.5V20h4.8v25h-5L20.8 30.2V45H16z" fill="#FFFFFF" />
              <path d="M40 28h5.5c3.6 0 6 2.1 6 5.4 0 3.4-2.4 5.5-6 5.5h-1.8V45H40V28zm3.7 7.6h1.6c1.5 0 2.5-.8 2.5-2.2s-1-2.1-2.5-2.1h-1.6v4.3z" fill="#E59400" />
            </svg>
            <div>
              <div class="text-sm font-extrabold text-white">CÔNG TY TNHH NHÔM KÍNH NHẬT PHÁT</div>
              <div class="text-[11px] text-brand-accent font-semibold">nhomkinhnhatphat.com</div>
            </div>
          </div>
          <p class="text-xs text-slate-300 leading-relaxed">
            Chuyên thiết kế, sản xuất và thi công cửa nhôm Xingfa nhập khẩu, cửa kính cường lực, cầu thang kính, kính ốp bếp và phòng tắm kính chuyên nghiệp tại Đà Nẵng.
          </p>
          <ul class="space-y-1.5 text-xs text-slate-300">
            <li><i class="fa-solid fa-location-dot text-brand-accent mr-2"></i>253/11 Nguyễn Hoàng, Phường Hải Châu, TP Đà Nẵng</li>
            <li><i class="fa-solid fa-phone text-brand-accent mr-2"></i>Hotline: <a href="tel:0905586981" class="text-white font-bold hover:text-brand-accent">0905 586 981</a></li>
            <li><i class="fa-solid fa-globe text-brand-accent mr-2"></i>Website: nhomkinhnhatphat.com</li>
          </ul>
        </div>

        <!-- Cột 2: Cửa nhôm xingfa -->
        <div>
          <h3 class="text-sm font-bold uppercase text-white mb-3 pb-2 border-b border-white/15">Cửa Nhôm Xingfa</h3>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#san-pham" onclick="filterProducts('xingfa', '1 cánh')" class="hover:text-brand-accent transition-colors">Cửa nhôm xingfa 1 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProducts('xingfa', '2 cánh')" class="hover:text-brand-accent transition-colors">Cửa nhôm xingfa 2 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProducts('xingfa', '3 cánh')" class="hover:text-brand-accent transition-colors">Cửa nhôm xingfa 3 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProducts('xingfa', '4 cánh')" class="hover:text-brand-accent transition-colors">Cửa nhôm xingfa 4 cánh</a></li>
            <li><a href="#san-pham" onclick="filterProducts('xingfa', '5 cánh')" class="hover:text-brand-accent transition-colors">Cửa nhôm xingfa 5 cánh</a></li>
          </ul>
        </div>

        <!-- Cột 3: Danh mục sản phẩm -->
        <div>
          <h3 class="text-sm font-bold uppercase text-white mb-3 pb-2 border-b border-white/15">Sản Phẩm &amp; Dịch Vụ</h3>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#san-pham" onclick="filterProducts('xingfa')" class="hover:text-brand-accent transition-colors">Cửa nhôm xingfa Đà Nẵng</a></li>
            <li><a href="#san-pham" onclick="filterProducts('kinh-cuong-luc')" class="hover:text-brand-accent transition-colors">Cửa kính cường lực</a></li>
            <li><a href="#san-pham" onclick="filterProducts('nhua-loi-thep')" class="hover:text-brand-accent transition-colors">Cửa nhựa lõi thép</a></li>
            <li><a href="#san-pham" onclick="filterProducts('cua-tu-dong')" class="hover:text-brand-accent transition-colors">Cửa kính tự động</a></li>
            <li><a href="#san-pham" onclick="filterProducts('cau-thang-kinh')" class="hover:text-brand-accent transition-colors">Cầu thang kính</a></li>
            <li><a href="#san-pham" onclick="filterProducts('kinh-op-bep')" class="hover:text-brand-accent transition-colors">Kính ốp bếp &amp; Phòng tắm kính</a></li>
          </ul>
        </div>

        <!-- Cột 4: Liên kết nhanh -->
        <div>
          <h3 class="text-sm font-bold uppercase text-white mb-3 pb-2 border-b border-white/15">Hỗ Trợ Khách Hàng</h3>
          <ul class="space-y-2 text-xs text-slate-300">
            <li><a href="#gioi-thieu" class="hover:text-brand-accent transition-colors">Giới thiệu Nhôm Kính Nhật Phát</a></li>
            <li><a href="#cong-trinh" class="hover:text-brand-accent transition-colors">Công trình đã thi công</a></li>
            <li><a href="#bao-gia" class="hover:text-brand-accent transition-colors">Bảng báo giá nhôm kính mới nhất</a></li>
            <li><a href="#tin-tuc" class="hover:text-brand-accent transition-colors">Tin tức &amp; Tư vấn kỹ thuật</a></li>
            <li><a href="#form-bao-gia" class="hover:text-brand-accent transition-colors">Đăng ký khảo sát miễn phí</a></li>
          </ul>
        </div>
      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
        <div>Copyright © 2026 CÔNG TY TNHH NHÔM KÍNH NHẬT PHÁT (nhomkinhnhatphat.com).</div>
        <div>Thiết kế tối ưu chuẩn Flatsome UX Builder.</div>
      </div>
    </div>
  </footer>

  <!-- ==================== CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TƯƠNG THÍCH PC & MOBILE ==================== -->
  <div class="fixed bottom-4 right-3 sm:bottom-5 sm:right-5 z-40 flex flex-col items-end gap-2.5">
    <!-- Nút Facebook -->
    <a href="https://www.facebook.com/" target="_blank" rel="noopener noreferrer" aria-label="Nhắn tin Facebook Nhôm Kính Nhật Phát" class="group flex items-center gap-2 bg-[#1877F2] hover:bg-[#1465D1] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition-all">
      <i class="fa-brands fa-facebook-f w-5 h-5 flex items-center justify-center text-base"></i>
      <span class="hidden md:inline text-xs font-bold pr-1">Facebook</span>
    </a>

    <!-- Nút Zalo -->
    <a href="https://zalo.me/0905586981" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0905 586 981" class="group flex items-center gap-2 bg-[#0068FF] hover:bg-[#0055D4] text-white rounded-full shadow-lg p-2.5 sm:px-3.5 sm:py-2.5 transition-all">
      <span class="w-5 h-5 rounded-full bg-white text-[#0068FF] font-extrabold text-[10px] flex items-center justify-center leading-none">Zalo</span>
      <span class="hidden md:inline text-xs font-bold pr-1">Zalo 0905 586 981</span>
    </a>

    <!-- Nút Hotline -->
    <a href="tel:0905586981" aria-label="Gọi Hotline 0905 586 981" class="pulse-hotline group flex items-center gap-2 bg-brand-accent hover:bg-brand-accentHover text-white rounded-full shadow-xl p-2.5 sm:px-4 sm:py-2.5 transition-all">
      <i class="fa-solid fa-phone-volume w-5 h-5 flex items-center justify-center text-sm"></i>
      <span class="hidden sm:inline text-xs font-extrabold pr-0.5">0905 586 981</span>
    </a>
  </div>

  <!-- ==================== MODAL XEM CHI TIẾT SẢN PHẨM / BÀI VIẾT ==================== -->
  <div id="detail-modal" class="fixed inset-0 z-50 hidden items-center justify-center bg-slate-900/60 p-3 sm:p-4">
    <div class="bg-white rounded-xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
      <button type="button" onclick="closeDetailModal()" aria-label="Đóng cửa sổ" class="sticky top-3 float-right mr-3 z-10 w-8 h-8 rounded-full bg-slate-100 hover:bg-brand-primary hover:text-white text-slate-700 flex items-center justify-center transition-colors">
        <i class="fa-solid fa-xmark"></i>
      </button>
      <div id="detail-modal-body" class="p-5 sm:p-6"></div>
    </div>
  </div>

  <!-- ==================== TOAST THÔNG BÁO (THAY THẾ HOÀN TOÀN ALERT) ==================== -->
  <div id="toast-box" class="fixed top-20 right-4 z-50 hidden max-w-sm bg-brand-primary text-white px-4 py-3 rounded-xl shadow-xl border-l-4 border-brand-accent text-xs sm:text-sm font-medium">
    <div class="flex items-start gap-2.5">
      <i class="fa-solid fa-circle-check text-brand-accent text-base mt-0.5 shrink-0"></i>
      <span id="toast-message"></span>
    </div>
  </div>

  <!-- ==================== JAVASCRIPT XỬ LÝ TƯƠNG TÁC ==================== -->
  <script>
    /**
     * Hàm dự phòng tải ảnh Google Drive đảm bảo ảnh luôn hiển thị đẹp, không vỡ hình
     */
    function handleDriveImgError(imgEl, driveId, fallbackLabel) {
      try {
        const step = parseInt(imgEl.dataset.retryStep || '0', 10);
        if (step === 0) {
          imgEl.dataset.retryStep = '1';
          imgEl.src = 'https://lh3.googleusercontent.com/d/' + driveId + '=w1000';
        } else if (step === 1) {
          imgEl.dataset.retryStep = '2';
          imgEl.src = 'https://drive.google.com/uc?export=view&id=' + driveId;
        } else {
          imgEl.onerror = null;
          imgEl.src = 'https://placehold.co/600x450/0B3D6B/FFFFFF?text=' + (fallbackLabel || 'Nhom+Kinh+Nhat+Phat');
        }
      } catch (e) {
        imgEl.onerror = null;
      }
    }

    /**
     * Danh sách sản phẩm đầy đủ với hình ảnh thực tế từ Google Drive, giá bán & % giảm giá góc trên bên trái
     */
    const PRODUCTS = [
      {
        id: 1,
        name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
        category: 'xingfa',
        tagWing: '1 cánh',
        price: 1850000,
        oldPrice: 2150000,
        discount: 14,
        driveId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
        specs: 'Nhôm Xingfa hệ 55 dày 2.0mm nhập khẩu Quảng Đông, kính cường lực 8mm, phụ kiện Kinlong đồng bộ, thích hợp cửa thông phòng, cửa ban công, cửa nhà vệ sinh.'
      },
      {
        id: 2,
        name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
        category: 'xingfa',
        tagWing: '2 cánh',
        price: 1890000,
        oldPrice: 2200000,
        discount: 14,
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        specs: 'Nhôm Xingfa hệ 55 dày 2.0mm tem đỏ chính hãng, ép góc CNC kín khít tuyệt đối, gioăng kép EPDM cách âm cách nhiệt vượt trội.'
      },
      {
        id: 3,
        name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
        category: 'xingfa',
        tagWing: '3 cánh',
        price: 1920000,
        oldPrice: 2250000,
        discount: 15,
        driveId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
        specs: 'Thiết kế cân đối cho mặt tiền nhà phố có bề ngang vừa phải, nhôm Xingfa hệ 55 dày 2.0mm, khóa đa điểm chống trộm an toàn.'
      },
      {
        id: 4,
        name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
        category: 'xingfa',
        tagWing: '4 cánh',
        price: 1950000,
        oldPrice: 2300000,
        discount: 15,
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        specs: 'Mẫu cửa mặt tiền sang trọng nhất cho nhà phố và biệt thự, khung nhôm Xingfa 2.0mm sơn tĩnh điện bền màu, chịu áp lực gió bão đến 1600 Pa.'
      },
      {
        id: 5,
        name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
        category: 'xingfa',
        tagWing: '5 cánh',
        price: 1980000,
        oldPrice: 2350000,
        discount: 16,
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        specs: 'Cửa đi xếp trượt gấp 4-5-6 cánh nhôm Xingfa hệ 63, mở rộng tối đa 95% không gian lối đi, ray trượt êm nhẹ, phù hợp biệt thự và khách sạn.'
      },
      {
        id: 6,
        name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
        category: 'xingfa',
        tagWing: '2 cánh',
        price: 1700000,
        oldPrice: 2000000,
        discount: 15,
        driveId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
        specs: 'Nhôm Xingfa hệ 55 dày 1.4mm, thanh hạn vị chống gió giật hiệu quả, mở thoáng đón gió ngay cả khi trời mưa phùn.'
      },
      {
        id: 7,
        name: 'Cửa kính cường lực bản lề sàn 10mm - 12mm',
        category: 'kinh-cuong-luc',
        tagWing: '',
        price: 750000,
        oldPrice: 880000,
        discount: 15,
        driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
        specs: 'Kính cường lực tôi nhiệt an toàn 10mm-12mm kết hợp bản lề thủy lực VVP/Hafele chính hãng, đóng mở êm ái, lấy sáng tối đa cho mặt tiền showroom.'
      },
      {
        id: 8,
        name: 'Cửa nhựa lõi thép uPVC mở quay cách âm',
        category: 'nhua-loi-thep',
        tagWing: '',
        price: 1450000,
        oldPrice: 1650000,
        discount: 12,
        driveId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
        specs: 'Thanh nhựa Sparlee lõi thép gia cường mạ kẽm dày 1.2mm - 1.5mm, cách âm cách nhiệt hiệu quả, không cong vênh mối mọt.'
      },
      {
        id: 9,
        name: 'Cửa kính trượt tự động cảm biến Hàn Quốc',
        category: 'cua-tu-dong',
        tagWing: '',
        price: 18500000,
        oldPrice: 21000000,
        discount: 12,
        driveId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
        specs: 'Hệ thống mắt thần radar cảm biến chuyển động thông minh, motor không chổi than vận hành bền bỉ cho sảnh khách sạn, văn phòng, siêu thị.'
      },
      {
        id: 10,
        name: 'Cầu thang kính cường lực tay vịn gỗ hiện đại',
        category: 'cau-thang-kinh',
        tagWing: '',
        price: 1250000,
        oldPrice: 1450000,
        discount: 14,
        driveId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
        specs: 'Kính cường lực 10mm kết hợp trụ Inox 304 và tay vịn gỗ tự nhiên sang trọng, tạo cảm giác rộng rãi và thoáng sáng cho nội thất nhà phố.'
      },
      {
        id: 11,
        name: 'Kính ốp bếp cường lực sơn màu chịu nhiệt',
        category: 'kinh-op-bep',
        tagWing: '',
        price: 720000,
        oldPrice: 850000,
        discount: 15,
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        specs: 'Kính cường lực 8mm sơn màu chịu nhiệt cao cấp, bề mặt bóng mịn không mạch vữa, chống bám dầu mỡ và cực kỳ dễ lau chùi.'
      },
      {
        id: 12,
        name: 'Phòng tắm kính cường lực vát góc Inox 304',
        category: 'phong-tam-kinh',
        tagWing: '',
        price: 820000,
        oldPrice: 950000,
        discount: 14,
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        specs: 'Vách tắm kính cường lực 10mm ngăn nước tuyệt đối, bản lề và kẹp kính Inox 304 chống gỉ sét trong môi trường ẩm ướt.'
      }
    ];

    /**
     * Danh sách bài viết / tin tức trang chủ
     */
    const POSTS = [
      {
        id: 1,
        category: 'tu-van-xingfa',
        catLabel: 'Tư vấn Cửa nhôm Xingfa',
        date: '18/11/2026',
        title: 'Cửa nhôm Xingfa có phù hợp với khí hậu mưa bão tại Đà Nẵng không?',
        excerpt: 'Với kết cấu thanh nhôm đa khoang cùng hệ gioăng kép EPDM và sơn tĩnh điện ngoài trời, cửa nhôm Xingfa chịu gió bão vượt trội và chống ăn mòn hơi muối biển rất hiệu quả.',
        driveId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
        content: 'Đà Nẵng là khu vực ven biển có độ ẩm cao và thường xuyên chịu ảnh hưởng của gió bão miền Trung. Cửa nhôm Xingfa nhập khẩu tem đỏ Quảng Đông sở hữu độ dày tiêu chuẩn 1.4mm - 2.0mm, bề mặt sơn tĩnh điện cao cấp chống oxy hóa, chịu áp lực gió lên tới 1600 Pascal. Kết hợp keo silicon chống thấm và gioăng kép EPDM giúp ngăn nước mưa tạt tuyệt đối, là giải pháp tối ưu cho nhà phố, biệt thự và khách sạn tại Đà Nẵng.'
      },
      {
        id: 2,
        category: 'tu-van-xingfa',
        catLabel: 'Tư vấn Cửa nhôm Xingfa',
        date: '12/11/2026',
        title: 'So sánh cửa nhôm Xingfa và cửa gỗ: Nên chọn loại nào cho nhà phố?',
        excerpt: 'Phân tích chi tiết về độ bền, khả năng chống mối mọt, cách âm, thẩm mỹ và chi phí bảo trì giúp gia chủ dễ dàng lựa chọn giải pháp cửa tối ưu.',
        driveId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
        content: 'Nếu cửa gỗ tự nhiên mang vẻ ấm cúng nhưng dễ cong vênh, co ngót khi gặp nắng nóng hoặc ẩm ướt, thì cửa nhôm Xingfa khắc phục triệt để các nhược điểm này. Nhôm Xingfa có đa dạng màu sắc từ ghi xám, đen tuyền, trắng sứ đến vân gỗ sang trọng, không mối mọt, cách âm tốt khi đi kèm kính hộp và có tuổi thọ sử dụng hàng chục năm mà hầu như không tốn chi phí bảo dưỡng.'
      },
      {
        id: 3,
        category: 'kinh-cuong-luc',
        catLabel: 'Kinh nghiệm Kính cường lực',
        date: '05/11/2026',
        title: 'Kinh nghiệm chọn phòng tắm kính cường lực bền đẹp, chống rò nước',
        excerpt: 'Nên dùng kính dày 10mm hay 12mm? Chọn phụ kiện Inox 304 và kiểu mở quay hay cửa lùa cho phòng tắm diện tích nhỏ?',
        driveId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
        content: 'Để phòng tắm kính vận hành êm ái và bền đẹp theo thời gian, gia chủ nên ưu tiên kính cường lực dày 10mm đạt chuẩn, bộ phụ kiện bản lề, kẹp kính và thanh giằng làm từ Inox 304 chống rỉ tuyệt đối. Với phòng tắm nhỏ hẹp, kiểu vách tắm kính vát góc 135 độ hoặc cửa trượt lùa sẽ giúp tối ưu không gian hiệu quả nhất.'
      },
      {
        id: 4,
        category: 'bao-gia-thi-cong',
        catLabel: 'Cẩm nang báo giá & thi công',
        date: '28/10/2026',
        title: 'Cách nhận biết nhôm Xingfa Quảng Đông tem đỏ chính hãng 100%',
        excerpt: 'Hướng dẫn kiểm tra mã QR tem đỏ, ánh kim bên trong khoang nhôm và độ dày thanh profile để tránh mua nhầm hàng giả, hàng kém chất lượng.',
        driveId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
        content: 'Nhôm Xingfa nhập khẩu Quảng Đông chính hãng có tem đỏ in sắc nét kèm mã QR xác thực xuất xứ, bên trong thanh nhôm có ánh kim crom đặc trưng chống oxy hóa, góc ép nhôm bằng máy thủy lực kín khít không lộ khe hở. Tại Nhôm Kính Nhật Phát, khách hàng luôn được kiểm tra trực tiếp phôi nhôm và phụ kiện trước khi lắp đặt.'
      },
      {
        id: 5,
        category: 'kinh-cuong-luc',
        catLabel: 'Kinh nghiệm Kính cường lực',
        date: '20/10/2026',
        title: 'Chọn màu kính ốp bếp cường lực hợp phong thủy và dễ vệ sinh',
        excerpt: 'Tổng hợp các gam màu kính ốp bếp được ưa chuộng nhất năm 2026 như xanh ngọc, vàng chanh, trắng sữa, đen kim sa cho gian bếp hiện đại.',
        driveId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
        content: 'Kính ốp bếp cường lực 8mm được đo cắt nguyên tấm theo thực tế tủ bếp, không có đường ron gạch nên tránh tích tụ dầu mỡ và ẩm mốc. Việc lựa chọn màu sắc hài hòa với màu mặt đá bếp và ánh sáng đèn LED giúp gian bếp luôn sáng bóng, sạch sẽ và tạo cảm hứng nấu nướng mỗi ngày.'
      },
      {
        id: 6,
        category: 'bao-gia-thi-cong',
        catLabel: 'Cẩm nang báo giá & thi công',
        date: '14/10/2026',
        title: 'Những yếu tố ảnh hưởng đến báo giá cửa nhôm kính trọn gói tại Đà Nẵng',
        excerpt: 'Hiểu rõ cấu thành giá theo diện tích cửa, hệ nhôm, độ dày kính và hãng phụ kiện để dự trù ngân sách xây dựng chính xác nhất.',
        driveId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
        content: 'Báo giá cửa nhôm kính phụ thuộc vào 4 yếu tố chính: chủng loại thanh nhôm (nhập khẩu hay trong nước, hệ 55/63/93), loại kính sử dụng (kính an toàn 6.38mm, cường lực 8-10mm hay kính hộp), bộ phụ kiện kim khí (Kinlong, Cmech, Draho...) và diện tích thực tế của từng bộ cửa. Liên hệ hotline 0905 586 981 để nhận bảng dự toán chi tiết minh bạch từng hạng mục.'
      }
    ];

    function formatVND(num) {
      return num.toString().replace(/\B(?=(\d{3})+(?!\d))/g, '.') + ' ₫';
    }

    /**
     * Render danh sách sản phẩm
     */
    function renderProducts(category = 'all', wingFilter = '') {
      const grid = document.getElementById('product-grid');
      const notice = document.getElementById('subfilter-notice');
      const noticeText = document.getElementById('subfilter-text');
      if (!grid) return;

      let filtered = PRODUCTS;
      if (category !== 'all') {
        filtered = filtered.filter(p => p.category === category);
      }
      if (wingFilter) {
        const wingMatches = filtered.filter(p => p.tagWing === wingFilter);
        if (wingMatches.length > 0) {
          filtered = wingMatches;
        }
        notice.classList.remove('hidden');
        noticeText.textContent = 'Đang xem: Cửa nhôm xingfa ' + wingFilter;
      } else {
        notice.classList.add('hidden');
      }

      grid.innerHTML = filtered.map(p => `
        <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md hover:border-brand-primary transition-all flex flex-col">
          <!-- Khung ảnh sản phẩm + Nhãn giảm giá % góc trên bên trái -->
          <div class="relative aspect-[4/3] w-full overflow-hidden bg-slate-100">
            <span class="absolute top-2 left-2 z-10 inline-flex items-center justify-center px-2 py-1 rounded-md bg-brand-accent text-white text-[11px] font-extrabold shadow">
              -${p.discount}%
            </span>
            <img
              src="https://drive.google.com/thumbnail?id=${p.driveId}&sz=w800"
              onerror="handleDriveImgError(this, '${p.driveId}', 'San+Pham')"
              alt="${p.name}"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>

          <!-- Thông tin sản phẩm: Tên hiển thị đầy đủ không cắt chữ, không tràn viền -->
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between gap-2">
            <div>
              <h3 class="text-[12.5px] sm:text-sm font-bold text-slate-800 group-hover:text-brand-primary leading-snug break-words">
                ${p.name}
              </h3>
            </div>
            <div class="space-y-2 pt-1">
              <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                <span class="text-[13px] sm:text-[15px] font-extrabold text-brand-accent">${formatVND(p.price)}</span>
                <span class="text-[11px] sm:text-xs text-slate-400 line-through">${formatVND(p.oldPrice)}</span>
              </div>
              <div class="flex items-center gap-1.5">
                <button type="button" onclick="openProductDetail(${p.id})" class="flex-1 py-1.5 px-2 rounded-lg bg-brand-primary hover:bg-brand-secondary text-white text-[11px] sm:text-xs font-semibold transition-colors text-center">
                  Xem chi tiết
                </button>
                <button type="button" onclick="selectProductForQuote('${p.name.replace(/'/g, "\\'")}')" class="py-1.5 px-2.5 rounded-lg bg-brand-light hover:bg-brand-accent hover:text-white text-brand-primary text-[11px] sm:text-xs font-bold transition-colors" title="Nhận báo giá mẫu này">
                  Báo giá
                </button>
              </div>
            </div>
          </div>
        </article>
      `).join('');
    }

    /**
     * Lọc sản phẩm theo danh mục & đồng bộ trạng thái nút lọc
     */
    function filterProducts(category, wingFilter = '') {
      renderProducts(category, wingFilter);
      const btns = document.querySelectorAll('.filter-btn');
      btns.forEach(btn => {
        if (btn.dataset.filter === category) {
          btn.classList.remove('bg-white', 'text-slate-700', 'border-slate-200');
          btn.classList.add('bg-brand-primary', 'text-white', 'border-brand-primary');
        } else {
          btn.classList.add('bg-white', 'text-slate-700', 'border-slate-200');
          btn.classList.remove('bg-brand-primary', 'text-white', 'border-brand-primary');
        }
      });
    }

    /**
     * Render bài viết tin tức trang chủ
     */
    function renderPosts(category = 'all') {
      const grid = document.getElementById('post-grid');
      if (!grid) return;
      const list = category === 'all' ? POSTS : POSTS.filter(item => item.category === category);

      grid.innerHTML = list.map(post => `
        <article class="group bg-white rounded-xl border border-slate-200 overflow-hidden shadow-sm hover:shadow-md transition-all flex flex-col">
          <div class="aspect-[16/10] w-full overflow-hidden bg-slate-100">
            <img
              src="https://drive.google.com/thumbnail?id=${post.driveId}&sz=w800"
              onerror="handleDriveImgError(this, '${post.driveId}', 'Tin+Tuc')"
              alt="${post.title}"
              class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-300"
              loading="lazy"
            />
          </div>
          <div class="p-4 flex-1 flex flex-col justify-between gap-2.5">
            <div>
              <div class="flex items-center justify-between text-[11px] text-slate-500 mb-1.5">
                <span class="font-semibold text-brand-secondary">${post.catLabel}</span>
                <span>${post.date}</span>
              </div>
              <h3 class="text-sm font-bold text-slate-800 group-hover:text-brand-primary leading-snug mb-1.5">
                ${post.title}
              </h3>
              <p class="text-xs text-slate-600 leading-relaxed">
                ${post.excerpt}
              </p>
            </div>
            <div>
              <button type="button" onclick="openPostDetail(${post.id})" class="inline-flex items-center gap-1.5 text-xs font-bold text-brand-primary hover:text-brand-accent transition-colors">
                <span>Đọc tiếp</span>
                <i class="fa-solid fa-arrow-right text-[10px]"></i>
              </button>
            </div>
          </div>
        </article>
      `).join('');
    }

    function filterPosts(category, clickedBtn) {
      renderPosts(category);
      document.querySelectorAll('.post-cat-btn').forEach(btn => {
        btn.classList.remove('bg-brand-primary', 'text-white', 'border-brand-primary');
        btn.classList.add('bg-white', 'text-slate-700', 'border-slate-200');
      });
      if (clickedBtn) {
        clickedBtn.classList.remove('bg-white', 'text-slate-700', 'border-slate-200');
        clickedBtn.classList.add('bg-brand-primary', 'text-white', 'border-brand-primary');
      }
    }

    /**
     * Mở modal chi tiết sản phẩm
     */
    function openProductDetail(productId) {
      const p = PRODUCTS.find(item => item.id === productId);
      if (!p) return;
      const modal = document.getElementById('detail-modal');
      const body = document.getElementById('detail-modal-body');

      body.innerHTML = `
        <div class="grid grid-cols-1 sm:grid-cols-2 gap-5 items-start">
          <div class="relative rounded-xl overflow-hidden border border-slate-200 bg-slate-100">
            <span class="absolute top-2.5 left-2.5 px-2.5 py-1 rounded-md bg-brand-accent text-white text-xs font-extrabold shadow">-${p.discount}%</span>
            <img src="https://drive.google.com/thumbnail?id=${p.driveId}&sz=w1000" onerror="handleDriveImgError(this, '${p.driveId}', 'San+Pham')" alt="${p.name}" class="w-full aspect-[4/3] object-cover" />
          </div>
          <div class="space-y-3">
            <h3 class="text-lg font-extrabold text-brand-primary leading-snug">${p.name}</h3>
            <div class="flex items-baseline gap-2.5">
              <span class="text-xl font-extrabold text-brand-accent">${formatVND(p.price)}</span>
              <span class="text-sm text-slate-400 line-through">${formatVND(p.oldPrice)}</span>
            </div>
            <p class="text-sm text-slate-600 leading-relaxed">${p.specs}</p>
            <ul class="text-xs text-slate-600 space-y-1.5 border-t border-slate-100 pt-3">
              <li><i class="fa-solid fa-check text-brand-accent mr-1.5"></i>Khảo sát &amp; đo đạc miễn phí tại Đà Nẵng</li>
              <li><i class="fa-solid fa-check text-brand-accent mr-1.5"></i>Cam kết nhôm kính &amp; phụ kiện chính hãng 100%</li>
              <li><i class="fa-solid fa-check text-brand-accent mr-1.5"></i>Bảo hành kỹ thuật tận nơi nhanh chóng</li>
            </ul>
            <div class="flex flex-wrap gap-2 pt-2">
              <a href="tel:0905586981" class="flex-1 inline-flex items-center justify-center gap-1.5 px-4 py-2.5 rounded-lg bg-brand-accent hover:bg-brand-accentHover text-white text-xs font-bold">
                <i class="fa-solid fa-phone"></i> Gọi 0905 586 981
              </a>
              <button type="button" onclick="closeDetailModal(); selectProductForQuote('${p.name.replace(/'/g, "\\'")}')" class="flex-1 inline-flex items-center justify-center gap-1.5 px-4 py-2.5 rounded-lg bg-brand-primary hover:bg-brand-secondary text-white text-xs font-bold">
                Nhận báo giá
              </button>
            </div>
          </div>
        </div>
      `;
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    /**
     * Mở modal đọc chi tiết bài viết
     */
    function openPostDetail(postId) {
      const post = POSTS.find(item => item.id === postId);
      if (!post) return;
      const modal = document.getElementById('detail-modal');
      const body = document.getElementById('detail-modal-body');

      body.innerHTML = `
        <div class="space-y-4">
          <div class="text-xs font-bold text-brand-secondary">${post.catLabel} · ${post.date}</div>
          <h3 class="text-lg sm:text-xl font-extrabold text-brand-primary leading-snug">${post.title}</h3>
          <div class="rounded-xl overflow-hidden bg-slate-100 aspect-[16/9]">
            <img src="https://drive.google.com/thumbnail?id=${post.driveId}&sz=w1000" onerror="handleDriveImgError(this, '${post.driveId}', 'Tin+Tuc')" alt="${post.title}" class="w-full h-full object-cover" />
          </div>
          <p class="text-sm text-slate-700 leading-relaxed">${post.content}</p>
          <div class="p-3.5 rounded-xl bg-brand-light text-xs text-brand-primary flex flex-wrap items-center justify-between gap-2">
            <span>Cần tư vấn trực tiếp cho công trình của bạn tại Đà Nẵng?</span>
            <a href="tel:0905586981" class="font-extrabold text-brand-accent hover:underline">Hotline: 0905 586 981</a>
          </div>
        </div>
      `;
      modal.classList.remove('hidden');
      modal.classList.add('flex');
    }

    function closeDetailModal() {
      const modal = document.getElementById('detail-modal');
      modal.classList.add('hidden');
      modal.classList.remove('flex');
    }

    /**
     * Điền sẵn sản phẩm vào Form Báo Giá và cuộn xuống mượt mà
     */
    function selectProductForQuote(productName) {
      const noteEl = document.getElementById('q-note');
      if (noteEl) {
        noteEl.value = 'Tôi muốn nhận báo giá chi tiết cho mẫu: ' + productName;
      }
      const formSection = document.getElementById('form-bao-gia');
      if (formSection) {
        formSection.scrollIntoView({ behavior: 'smooth' });
      }
    }

    /**
     * Xử lý gửi Form Báo Giá (dùng Toast thông báo thân thiện, không dùng alert)
     */
    function handleQuoteSubmit(e) {
      e.preventDefault();
      const name = document.getElementById('q-name').value.trim();
      const phone = document.getElementById('q-phone').value.trim();
      if (!name || !phone) {
        showToast('Vui lòng nhập đầy đủ Họ tên và Số điện thoại để Nhật Phát liên hệ lại!');
        return;
      }
      showToast('Cảm ơn ' + name + '! Yêu cầu báo giá đã được gửi đến Công Ty TNHH Nhôm Kính Nhật Phát. Kỹ thuật viên sẽ liên hệ số ' + phone + ' trong ít phút.');
      e.target.reset();
    }

    function showToast(msg) {
      const box = document.getElementById('toast-box');
      const text = document.getElementById('toast-message');
      text.textContent = msg;
      box.classList.remove('hidden');
      clearTimeout(window.__toastTimer);
      window.__toastTimer = setTimeout(() => {
        box.classList.add('hidden');
      }, 5000);
    }

    /**
     * Điều khiển Mobile Off-canvas Menu
     */
    function toggleMobileMenu(show) {
      const overlay = document.getElementById('mobile-menu-overlay');
      const drawer = document.getElementById('mobile-menu-drawer');
      if (show) {
        overlay.classList.remove('hidden');
        drawer.classList.remove('-translate-x-full');
      } else {
        overlay.classList.add('hidden');
        drawer.classList.add('-translate-x-full');
      }
    }

    function toggleSubmenu(subId, iconId) {
      const sub = document.getElementById(subId);
      const icon = document.getElementById(iconId);
      if (sub) sub.classList.toggle('hidden');
      if (icon) icon.classList.toggle('rotate-180');
    }

    /**
     * Điều khiển 2 Banner tự trượt chuyên nghiệp (có hỗ trợ vuốt tay trên điện thoại)
     */
    let currentSlide = 0;
    let slideInterval = null;

    function goToSlide(index) {
      const slides = document.querySelectorAll('.banner-slide');
      const dots = document.querySelectorAll('.slider-dot');
      if (!slides.length) return;

      currentSlide = (index + slides.length) % slides.length;
      slides.forEach((slide, i) => {
        if (i === currentSlide) {
          slide.classList.remove('opacity-0', 'pointer-events-none', 'z-0');
          slide.classList.add('opacity-100', 'z-10');
        } else {
          slide.classList.add('opacity-0', 'pointer-events-none', 'z-0');
          slide.classList.remove('opacity-100', 'z-10');
        }
      });

      dots.forEach((dot, i) => {
        if (i === currentSlide) {
          dot.classList.remove('w-2', 'bg-white/60');
          dot.classList.add('w-6', 'bg-brand-accent');
        } else {
          dot.classList.remove('w-6', 'bg-brand-accent');
          dot.classList.add('w-2', 'bg-white/60');
        }
      });
    }

    function nextSlide() {
      goToSlide(currentSlide + 1);
      resetSliderTimer();
    }

    function prevSlide() {
      goToSlide(currentSlide - 1);
      resetSliderTimer();
    }

    function resetSliderTimer() {
      clearInterval(slideInterval);
      slideInterval = setInterval(() => {
        goToSlide(currentSlide + 1);
      }, 5000);
    }

    // Khởi tạo giao diện khi tải trang xong
    window.addEventListener('DOMContentLoaded', () => {
      renderProducts('all');
      renderPosts('all');
      resetSliderTimer();

      // Hỗ trợ vuốt cảm ứng cho Banner trên điện thoại
      const sliderEl = document.getElementById('hero-slider');
      let touchStartX = 0;
      if (sliderEl) {
        sliderEl.addEventListener('touchstart', (e) => {
          touchStartX = e.changedTouches[0].screenX;
        }, { passive: true });
        sliderEl.addEventListener('touchend', (e) => {
          const diff = e.changedTouches[0].screenX - touchStartX;
          if (Math.abs(diff) > 45) {
            if (diff < 0) nextSlide();
            else prevSlide();
          }
        }, { passive: true });
      }

      // Đóng modal khi bấm ra ngoài
      const modal = document.getElementById('detail-modal');
      if (modal) {
        modal.addEventListener('click', (e) => {
          if (e.target === modal) closeDetailModal();
        });
      }
    });
  </script>
</body>
</html>
