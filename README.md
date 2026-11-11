<html lang="vi">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
  <title>CÔNG TY TNHH SẢN XUẤT TM & DV ATM VIỆT NAM - Sàn Gỗ Châu Âu Kaindl & Kronopol Đà Nẵng</title>
  <meta name="description" content="CÔNG TY TNHH SẢN XUẤT TM & DV ATM VIỆT NAM (atmvietnam.com) - Phân phối & thi công Sàn gỗ Châu Âu Kaindl (Áo), Kronopol (Ba Lan), Phụ kiện Arbiton chính hãng tại 119 Nguyễn Công Triều, Phường An Khê, TP Đà Nẵng. Hotline: 0936.434.266 - 0905.513.828.">

  <!-- Open Graph / Thumbnail là ảnh Logo khi chia sẻ link trang web -->
  <meta property="og:type" content="website">
  <meta property="og:url" content="https://atmvietnam.com/">
  <meta property="og:title" content="CÔNG TY TNHH SẢN XUẤT TM & DV ATM VIỆT NAM - Sàn Gỗ Châu Âu Đà Nẵng">
  <meta property="og:description" content="Tổng kho phân phối và thi công Sàn gỗ công nghiệp Châu Âu Kaindl (Áo), Kronopol (Ba Lan) & Phụ kiện Arbiton chính hãng tại Đà Nẵng & Miền Trung.">
  <meta property="og:image" content="https://drive.google.com/thumbnail?id=15EXVtS8kteXe5ITBqmin2tkRMdHbW7mM&sz=w1200">
  <meta name="twitter:card" content="summary_large_image">
  <meta name="twitter:image" content="https://drive.google.com/thumbnail?id=15EXVtS8kteXe5ITBqmin2tkRMdHbW7mM&sz=w1200">
  <link rel="icon" href="https://drive.google.com/thumbnail?id=15EXVtS8kteXe5ITBqmin2tkRMdHbW7mM&sz=w256">

  <!-- Google Fonts: Inter & Montserrat chuẩn Flatsome -->
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

  <!-- Font Awesome 6 Icons -->
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

  <!-- Tailwind CSS -->
  <script src="https://cdn.tailwindcss.com"></script>
  <script>
    tailwind.config = {
      theme: {
        extend: {
          colors: {
            atmBlue: '#0F4C81',      /* Màu xanh thương hiệu chủ đạo theo logo ATM */
            atmDark: '#0A3256',      /* Màu xanh đậm thanh điều hướng Flatsome */
            atmRed: '#C82333',       /* Màu đỏ điểm nhấn Kaindl / ATM */
            atmGold: '#B87333',      /* Màu gỗ sồi Châu Âu Kronopol */
            atmBg: '#F7F5F0',        /* Nền kem gỗ ấm áp */
          },
          fontFamily: {
            sans: ['Inter', 'sans-serif'],
          }
        }
      }
    }
  </script>

  <style>
    /* Khóa tràn viền tuyệt đối trên cả máy tính và điện thoại */
    *, *::before, *::after {
      box-sizing: border-box;
    }
    html, body {
      margin: 0;
      padding: 0;
      width: 100%;
      max-width: 100vw;
      overflow-x: hidden;
      font-family: 'Inter', sans-serif;
      color: #1E293B;
      background-color: #FFFFFF;
      scroll-behavior: smooth;
    }

    /* Mở rộng khung bao ngoài (nếu chạy trên GitHub Pages / Flatsome wrapper) gần full viền màn hình */
    .container-lg,
    .markdown-body,
    #wrapper,
    #main {
      width: 100% !important;
      max-width: 100% !important;
      margin-left: auto !important;
      margin-right: auto !important;
      padding-left: 0 !important;
      padding-right: 0 !important;
    }

    /* Chỉnh giao diện trên máy tính gần full viền (98% màn hình ngang), điện thoại 100% không tràn viền */
    .container-1500 {
      width: 100%;
      max-width: 100%;
      margin-left: auto;
      margin-right: auto;
      padding-left: 10px;
      padding-right: 10px;
    }
    @media (min-width: 1024px) {
      .container-lg,
      .markdown-body {
        width: 98vw !important;
        max-width: 98vw !important;
      }
      .container-1500 {
        width: 98% !important;
        max-width: 98% !important;
        padding-left: 8px;
        padding-right: 8px;
      }
    }

    /* Tên danh mục trên máy tính & trang chủ: viết liền trên 1 hàng, chữ nhỏ gọn, tuyệt đối không xuống dòng bên trong tên danh mục */
    .cat-nowrap-item {
      white-space: nowrap !important;
      display: inline-flex;
      align-items: center;
      justify-content: center;
      line-height: 1.2;
      transition: all 0.2s ease;
    }

    /* Tiêu đề Section chuẩn Flatsome UX Builder (Title Element) */
    .flatsome-section-title {
      display: flex;
      align-items: center;
      justify-content: space-between;
      border-bottom: 2px solid #E2E8F0;
      margin-bottom: 20px;
      padding-bottom: 10px;
      flex-wrap: wrap;
      gap: 10px;
    }
    .flatsome-section-title h2 {
      position: relative;
      font-weight: 800;
      text-transform: uppercase;
      color: #0F4C81;
      margin: 0;
    }
    .flatsome-section-title h2::after {
      content: '';
      position: absolute;
      left: 0;
      bottom: -12px;
      width: 100%;
      height: 3px;
      background-color: #C82333;
    }

    /* Tên sản phẩm: hiển thị đầy đủ, không bị cắt chữ hay tràn ra ngoài */
    .product-full-title {
      white-space: normal !important;
      overflow: visible !important;
      text-overflow: clip !important;
      word-break: break-word;
      overflow-wrap: break-word;
      line-height: 1.38;
    }

    /* Hiệu ứng mượt cho thẻ sản phẩm Flatsome Box */
    .ux-product-box {
      transition: transform 0.25s ease, box-shadow 0.25s ease, border-color 0.25s ease;
    }
    .ux-product-box:hover {
      transform: translateY(-3px);
      box-shadow: 0 12px 24px -6px rgba(15, 76, 129, 0.14);
      border-color: #0F4C81;
    }

    /* Hiệu ứng rung nhẹ cho nút Hotline/Zalo nổi */
    @keyframes pulseRing {
      0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 35, 51, 0.6); }
      70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(200, 35, 51, 0); }
      100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(200, 35, 51, 0); }
    }
    .pulse-btn {
      animation: pulseRing 2s infinite;
    }
  </style>
</head>
<body class="bg-white text-slate-800 antialiased selection:bg-atmBlue selection:text-white">

  <!-- =====================================================================
       FLATSOME HEADER WRAPPER (Không để nút Gọi ngay trên Header để tránh tràn viền)
       ===================================================================== -->
  <header id="header" class="sticky top-0 z-40 bg-white shadow-sm border-b border-slate-200 w-full">
    
    <!-- TOP BAR FLATSOME -->
    <div id="top-bar" class="bg-atmDark text-white text-[11px] sm:text-xs py-1.5 w-full">
      <div class="container-1500 flex flex-wrap items-center justify-between gap-2">
        <div class="flex items-center gap-2 truncate">
          <span class="font-semibold tracking-wide text-amber-300">CÔNG TY TNHH SẢN XUẤT TM & DV ATM VIỆT NAM</span>
          <span class="hidden lg:inline text-slate-300">|</span>
          <span class="hidden lg:inline text-slate-200"><i class="fa-solid fa-location-dot text-red-400 mr-1"></i>119 Nguyễn Công Triều, Phường An Khê, TP Đà Nẵng</span>
        </div>
        <div class="flex items-center gap-3 sm:gap-4 shrink-0">
          <span class="hidden sm:inline text-slate-200"><i class="fa-solid fa-globe text-sky-300 mr-1"></i>atmvietnam.com</span>
          <span class="text-amber-300 font-medium"><i class="fa-solid fa-phone-volume mr-1"></i>0936.434.266 - 0905.513.828</span>
        </div>
      </div>
    </div>

    <!-- HEADER MAIN (MASTHEAD) - Logo chỉnh gọn nhỏ lại, không để nút gọi ngay -->
    <div id="masthead" class="py-2.5 bg-white w-full">
      <div class="container-1500 flex items-center justify-between gap-3">
        
        <!-- Logo gọn nhỏ + Tên thương hiệu -->
        <a href="#top" class="flex items-center gap-2.5 min-w-0 group">
          <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg border border-slate-200 bg-white p-1 flex items-center justify-center shrink-0 overflow-hidden shadow-xs">
            <img 
              src="https://drive.google.com/thumbnail?id=15EXVtS8kteXe5ITBqmin2tkRMdHbW7mM&sz=w400" 
              data-drive-id="15EXVtS8kteXe5ITBqmin2tkRMdHbW7mM"
              data-fallback-type="logo"
              alt="Logo Công Ty TNHH SX TM & DV ATM Việt Nam" 
              class="max-h-8 sm:max-h-9 w-auto object-contain"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="min-w-0">
            <div class="text-xs sm:text-sm md:text-base font-extrabold text-atmBlue tracking-tight leading-tight truncate">
              ATM VIỆT NAM
            </div>
            <div class="text-[10px] sm:text-[11px] text-slate-500 font-medium leading-tight truncate">
              Sàn Gỗ Châu Âu Kaindl & Kronopol Chính Hãng
            </div>
          </div>
        </a>

        <!-- Thanh tìm kiếm sản phẩm (Desktop) -->
        <div class="hidden md:flex flex-1 max-w-md mx-4">
          <div class="relative w-full">
            <input 
              type="text" 
              id="productSearchInput"
              oninput="filterProductsBySearch(this.value)"
              placeholder="Tìm mã sàn gỗ Kaindl, Kronopol, phụ kiện Arbiton..." 
              class="w-full pl-3.5 pr-9 py-1.5 text-xs border border-slate-300 rounded-md focus:outline-none focus:border-atmBlue bg-slate-50"
            >
            <i class="fa-solid fa-magnifying-glass absolute right-3 top-1/2 -translate-y-1/2 text-slate-400 text-xs"></i>
          </div>
        </div>

        <!-- Menu Điều Hướng Chính (Desktop) - Không có nút Gọi ngay để tránh tràn viền -->
        <nav class="hidden xl:flex items-center gap-4 text-xs font-bold uppercase text-slate-700 shrink-0">
          <a href="#top" class="text-atmBlue hover:text-atmRed transition">Trang chủ</a>
          <a href="#gioi-thieu" class="hover:text-atmBlue transition">Giới thiệu</a>
          <a href="#san-pham-kaindl" class="hover:text-atmBlue transition">Sàn gỗ Kaindl</a>
          <a href="#san-pham-kronopol" class="hover:text-atmBlue transition">Sàn gỗ Kronopol</a>
          <a href="#phu-kien" class="hover:text-atmBlue transition">Phụ kiện</a>
          <a href="#du-an-da-nang" class="hover:text-atmBlue transition">Dự án Đà Nẵng</a>
          <a href="#tin-tuc" class="hover:text-atmBlue transition">Bài viết</a>
          <a href="#bao-gia-lien-he" class="hover:text-atmBlue transition">Báo giá & Bản đồ</a>
        </nav>

        <!-- Nút mở Menu trên Điện thoại -->
        <button 
          type="button" 
          onclick="toggleMobileMenu()" 
          aria-label="Mở danh mục"
          class="xl:hidden inline-flex items-center gap-1.5 px-2.5 py-1.5 rounded-md border border-slate-300 text-xs font-bold text-atmBlue bg-slate-50 hover:bg-slate-100 shrink-0"
        >
          <i class="fa-solid fa-bars text-sm"></i>
          <span>DANH MỤC</span>
        </button>
      </div>
    </div>

    <!-- THANH DANH MỤC SẢN PHẨM TRÊN MÁY TÍNH (Chữ nhỏ gọn, viết liền trên 1 hàng hoặc xuống hàng 2, tuyệt đối không xuống dòng bên trong tên danh mục) -->
    <div id="wide-nav" class="hidden md:block bg-atmBlue border-t border-atmDark w-full">
      <div class="container-1500 py-1.5">
        <div class="flex flex-wrap items-center justify-center gap-x-1.5 gap-y-1">
          <button onclick="scrollToCategory('all')" class="cat-nowrap-item px-2.5 py-1 rounded text-[11.5px] font-semibold bg-atmRed text-white">
            <i class="fa-solid fa-table-cells-large mr-1 text-[10px]"></i>Tất cả sản phẩm
          </button>
          <button onclick="scrollToCategory('kaindl-xpt')" class="cat-nowrap-item px-2.5 py-1 rounded text-[11.5px] font-medium text-white hover:bg-white/15">
            Sàn gỗ Kaindl Floorganic XPT
          </button>
          <button onclick="scrollToCategory('kaindl-12mm')" class="cat-nowrap-item px-2.5 py-1 rounded text-[11.5px] font-medium text-white hover:bg-white/15">
            KAINDL AQUApro 12mm
          </button>
          <button onclick="scrollToCategory('kaindl-8mm')" class="cat-nowrap-item px-2.5 py-1 rounded text-[11.5px] font-medium text-white hover:bg-white/15">
            KAINDL AQUApro 8mm
          </button>
          <button onclick="scrollToCategory('kaindl-fishbone')" class="cat-nowrap-item px-2.5 py-1 rounded text-[11.5px] font-medium text-white hover:bg-white/15">
            Sàn gỗ Kaindl Fishbone
          </button>
          <button onclick="scrollToCategory('kronopol-symfonia')" class="cat-nowrap-item px-2.5 py-1 rounded text-[11.5px] font-medium text-white hover:bg-white/15">
            Kronopol Aqua Symfonia 12mm/AC5
          </button>
          <button onclick="scrollToCategory('kronopol-fiori')" class="cat-nowrap-item px-2.5 py-1 rounded text-[11.5px] font-medium text-white hover:bg-white/15">
            Kronopol Aqua Fiori 10mm/AC6
          </button>
          <button onclick="scrollToCategory('kronopol-infinity')" class="cat-nowrap-item px-2.5 py-1 rounded text-[11.5px] font-medium text-white hover:bg-white/15">
            Kronopol Aqua Zero Infinity 10mm/AC5
          </button>
          <button onclick="scrollToCategory('phu-kien-arbiton')" class="cat-nowrap-item px-2.5 py-1 rounded text-[11.5px] font-medium text-white hover:bg-white/15">
            Phụ kiện Châu Âu Arbiton
          </button>
        </div>
      </div>
    </div>

    <!-- MENU ĐIỆN THOẠI MỞ RỘNG (Drawer gọn đẹp) -->
    <div id="mobileMenuDrawer" class="hidden xl:hidden bg-white border-t border-slate-200 shadow-lg w-full">
      <div class="container-1500 py-3 space-y-3">
        <!-- Tìm kiếm trên điện thoại -->
        <div class="relative w-full md:hidden">
          <input 
            type="text" 
            oninput="filterProductsBySearch(this.value)"
            placeholder="Tìm sản phẩm sàn gỗ Kaindl, Kronopol..." 
            class="w-full pl-3 pr-8 py-1.5 text-xs border border-slate-300 rounded focus:outline-none focus:border-atmBlue"
          >
          <i class="fa-solid fa-magnifying-glass absolute right-3 top-1/2 -translate-y-1/2 text-slate-400 text-xs"></i>
        </div>
        <div class="grid grid-cols-2 sm:grid-cols-3 gap-1.5 text-xs font-semibold">
          <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 hover:bg-atmBlue hover:text-white">Giới thiệu ATM</a>
          <a href="#san-pham-kaindl" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 hover:bg-atmBlue hover:text-white">Sàn gỗ Kaindl (Áo)</a>
          <a href="#san-pham-kronopol" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 hover:bg-atmBlue hover:text-white">Sàn gỗ Kronopol</a>
          <a href="#phu-kien" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 hover:bg-atmBlue hover:text-white">Phụ kiện Arbiton</a>
          <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-slate-100 text-slate-700 hover:bg-atmBlue hover:text-white">Dự án Đà Nẵng</a>
          <a href="#bao-gia-lien-he" onclick="toggleMobileMenu()" class="px-2.5 py-2 rounded bg-atmRed text-white">Báo giá & Bản đồ</a>
        </div>
      </div>
    </div>
  </header>

  <!-- =====================================================================
       SECTION 1: SLIDER 2 ẢNH BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
       - Thiết kế ảnh banner Điện Thoại KHÁC với ảnh banner Máy Tính
       - Chữ chỉnh nhỏ gọn nằm trọn bên trong ảnh, tuyệt đối không tràn viền
       ===================================================================== -->
  <section id="top" class="w-full bg-slate-900 relative overflow-hidden">
    <div class="container-1500 px-0 py-0 sm:py-2">
      <div class="relative w-full overflow-hidden sm:rounded-xl shadow-md">
        
        <!-- VÙNG CHỨA 2 SLIDE KÍCH THƯỚC BẰNG NHAU (Mobile: cao 270px cố định | Desktop: cao 420px cố định) -->
        <div id="heroSliderTrack" class="relative w-full h-[270px] sm:h-[310px] md:h-[420px]">

          <!-- ==================== SLIDE 1: SÀN GỖ CHÂU ÂU KAINDL (ÁO) ==================== -->
          <div class="hero-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-100 z-10">
            
            <!-- 1A. BANNER MÁY TÍNH SLIDE 1 (Chỉ hiện trên máy tính/tablet ngang md trở lên) -->
            <div class="hidden md:flex w-full h-full relative items-center bg-gradient-to-r from-[#0A2E4D] via-[#0F4C81] to-[#1A365D] overflow-hidden">
              <!-- Ảnh nền thực tế bên phải kết hợp lớp phủ chuyển sắc -->
              <div class="absolute inset-y-0 right-0 w-3/5 h-full">
                <img 
                  src="https://drive.google.com/thumbnail?id=1vfbxmbBE5X-W0j-zBCcCZGaa1etzNJ2r&sz=w1200" 
                  data-drive-id="1vfbxmbBE5X-W0j-zBCcCZGaa1etzNJ2r"
                  alt="Banner Máy Tính Sàn Gỗ Châu Âu Kaindl" 
                  class="w-full h-full object-cover object-center opacity-75"
                  onerror="handleDriveImageError(this)"
                >
                <div class="absolute inset-0 bg-gradient-to-r from-[#0A2E4D] via-[#0F4C81]/80 to-transparent"></div>
              </div>

              <!-- Nội dung chữ trên máy tính: nhỏ gọn, căn lề an toàn bên trong ảnh -->
              <div class="relative z-10 w-full max-w-[680px] pl-10 pr-6 py-6 text-white">
                <div class="inline-flex items-center gap-2 px-3 py-1 rounded bg-atmRed text-white text-xs font-bold uppercase tracking-wider mb-3">
                  <span>SÀN GỖ CHÂU ÂU NHẬP KHẨU CỘNG HÒA ÁO</span>
                </div>
                <h1 class="text-2xl lg:text-3xl font-extrabold leading-snug mb-2.5 text-white">
                  SÀN GỖ KAINDL AQUA PRO & FLOORGANIC XPT
                </h1>
                <p class="text-xs lg:text-sm text-slate-100 leading-relaxed mb-4">
                  Công nghệ hèm khóa siêu chịu nước 100 giờ, cốt gỗ HDF sạch chuẩn Châu Âu E1 an toàn sức khỏe, giảm ồn 32dB, bảo hành chính hãng lên đến 30 năm tại ATM Việt Nam.
                </p>
                <div class="grid grid-cols-3 gap-2.5 mb-4 max-w-lg">
                  <div class="bg-white/10 backdrop-blur-xs border border-white/20 rounded px-3 py-2">
                    <div class="text-amber-300 font-extrabold text-xs">CHỊU NƯỚC 100H</div>
                    <div class="text-[11px] text-slate-200">Hèm khóa Aqua Pro</div>
                  </div>
                  <div class="bg-white/10 backdrop-blur-xs border border-white/20 rounded px-3 py-2">
                    <div class="text-amber-300 font-extrabold text-xs">TIÊU CHUẨN E1</div>
                    <div class="text-[11px] text-slate-200">Cốt gỗ sạch Châu Âu</div>
                  </div>
                  <div class="bg-white/10 backdrop-blur-xs border border-white/20 rounded px-3 py-2">
                    <div class="text-amber-300 font-extrabold text-xs">BẢO HÀNH 30 NĂM</div>
                    <div class="text-[11px] text-slate-200">Chống mài mòn AC5</div>
                  </div>
                </div>
                <div class="flex items-center gap-3 text-xs">
                  <a href="#san-pham-kaindl" class="px-4 py-2 rounded bg-amber-400 text-slate-900 font-bold hover:bg-amber-300 transition">
                    Xem Bảng Mã Kaindl
                  </a>
                  <span class="text-slate-200 font-medium">
                    <i class="fa-solid fa-location-dot text-amber-300 mr-1"></i>119 Nguyễn Công Triều, Đà Nẵng
                  </span>
                </div>
              </div>
            </div>

            <!-- 1B. BANNER ĐIỆN THOẠI SLIDE 1 (Thiết kế riêng cho màn hình dọc/nhỏ, chữ nhỏ gọn không tràn viền) -->
            <div class="flex md:hidden w-full h-full relative items-center justify-center bg-gradient-to-b from-[#0A2E4D] via-[#0F4C81] to-[#09223A] px-5 py-4 overflow-hidden">
              <img 
                src="https://drive.google.com/thumbnail?id=1JUY5C8ye2QD2K1glBtRtv9aMLjtz_3O1&sz=w800" 
                data-drive-id="1JUY5C8ye2QD2K1glBtRtv9aMLjtz_3O1"
                alt="Banner Điện Thoại Sàn Gỗ Kaindl" 
                class="absolute inset-0 w-full h-full object-cover opacity-25"
                onerror="handleDriveImageError(this)"
              >
              <div class="relative z-10 w-full max-w-[92%] mx-auto text-center text-white space-y-1.5">
                <span class="inline-block px-2.5 py-0.5 rounded bg-atmRed text-[10px] font-bold uppercase tracking-wide">
                  NHẬP KHẨU CỘNG HÒA ÁO
                </span>
                <h2 class="text-[15px] sm:text-base font-extrabold leading-tight text-amber-300">
                  SÀN GỖ CHỊU NƯỚC KAINDL AQUA PRO
                </h2>
                <p class="text-[11px] text-slate-100 leading-snug">
                  Chịu nước 100h • Chuẩn xanh E1 Châu Âu • Chống xước AC5 • Bảo hành 30 năm
                </p>
                <div class="grid grid-cols-2 gap-1.5 pt-1 text-[10px]">
                  <div class="bg-white/15 rounded py-1 px-1.5 font-semibold">Hèm khóa chống thấm</div>
                  <div class="bg-white/15 rounded py-1 px-1.5 font-semibold">Cốt HDF mật độ cao</div>
                </div>
                <div class="pt-1 text-[10.5px] font-semibold text-amber-200">
                  ATM VIỆT NAM • 119 Nguyễn Công Triều, Đà Nẵng
                </div>
              </div>
            </div>
          </div>

          <!-- ==================== SLIDE 2: SÀN GỖ BA LAN KRONOPOL ==================== -->
          <div class="hero-slide absolute inset-0 w-full h-full transition-opacity duration-700 opacity-0 z-0 pointer-events-none">
            
            <!-- 2A. BANNER MÁY TÍNH SLIDE 2 (Chỉ hiện trên máy tính/tablet ngang md trở lên) -->
            <div class="hidden md:flex w-full h-full relative items-center bg-gradient-to-r from-[#2C1810] via-[#4A2C1D] to-[#1E293B] overflow-hidden">
              <div class="absolute inset-y-0 right-0 w-3/5 h-full">
                <img 
                  src="https://drive.google.com/thumbnail?id=1eA06-E2FXjRtQXCUTPn5Ej3NTGhDpZT-&sz=w1200" 
                  data-drive-id="1eA06-E2FXjRtQXCUTPn5Ej3NTGhDpZT-"
                  alt="Banner Máy Tính Sàn Gỗ Kronopol Ba Lan" 
                  class="w-full h-full object-cover object-center opacity-75"
                  onerror="handleDriveImageError(this)"
                >
                <div class="absolute inset-0 bg-gradient-to-r from-[#2C1810] via-[#4A2C1D]/85 to-transparent"></div>
              </div>

              <!-- Nội dung chữ trên máy tính: nhỏ gọn, căn lề an toàn -->
              <div class="relative z-10 w-full max-w-[680px] pl-10 pr-6 py-6 text-white">
                <div class="inline-flex items-center gap-2 px-3 py-1 rounded bg-amber-600 text-white text-xs font-bold uppercase tracking-wider mb-3">
                  <span>SWISS KRONO GROUP - NHẬP KHẨU BA LAN</span>
                </div>
                <h2 class="text-2xl lg:text-3xl font-extrabold leading-snug mb-2.5 text-white">
                  SÀN GỖ KRONOPOL AQUA ZERO - BẢO HÀNH CẢ NGẬP NƯỚC
                </h2>
                <p class="text-xs lg:text-sm text-amber-50 leading-relaxed mb-4">
                  Cốt xanh Green HDF Q7 thế hệ mới kết hợp hèm khóa độc quyền Aqua Pearl ngăn nước 24h. Bề mặt vân gỗ 3D EIR chân thực, độ chống mài mòn lên tới AC5 & AC6.
                </p>
                <div class="grid grid-cols-3 gap-2.5 mb-4 max-w-lg">
                  <div class="bg-white/10 backdrop-blur-xs border border-white/20 rounded px-3 py-2">
                    <div class="text-amber-300 font-extrabold text-xs">AQUA PEARL 24H</div>
                    <div class="text-[11px] text-slate-200">Bảo hành ngập nước</div>
                  </div>
                  <div class="bg-white/10 backdrop-blur-xs border border-white/20 rounded px-3 py-2">
                    <div class="text-amber-300 font-extrabold text-xs">CHỐNG XƯỚC AC6</div>
                    <div class="text-[11px] text-slate-200">Vân gỗ Sồi 3D EIR</div>
                  </div>
                  <div class="bg-white/10 backdrop-blur-xs border border-white/20 rounded px-3 py-2">
                    <div class="text-amber-300 font-extrabold text-xs">THI CÔNG TRỌN GÓI</div>
                    <div class="text-[11px] text-slate-200">Đà Nẵng & Miền Trung</div>
                  </div>
                </div>
                <div class="flex items-center gap-3 text-xs">
                  <a href="#san-pham-kronopol" class="px-4 py-2 rounded bg-amber-400 text-slate-900 font-bold hover:bg-amber-300 transition">
                    Xem Bộ Sưu Tập Kronopol
                  </a>
                  <span class="text-amber-100 font-medium">
                    <i class="fa-solid fa-phone mr-1 text-amber-300"></i>Hotline: 0936.434.266 - 0905.513.828
                  </span>
                </div>
              </div>
            </div>

            <!-- 2B. BANNER ĐIỆN THOẠI SLIDE 2 (Thiết kế riêng cho điện thoại, chữ nhỏ gọn nằm hết trong khung) -->
            <div class="flex md:hidden w-full h-full relative items-center justify-center bg-gradient-to-b from-[#2C1810] via-[#4A2C1D] to-[#1F120C] px-5 py-4 overflow-hidden">
              <img 
                src="https://drive.google.com/thumbnail?id=1iQwq6KV0bx79dzrD_TsToktor4mH7_n_&sz=w800" 
                data-drive-id="1iQwq6KV0bx79dzrD_TsToktor4mH7_n_"
                alt="Banner Điện Thoại Sàn Gỗ Kronopol" 
                class="absolute inset-0 w-full h-full object-cover opacity-25"
                onerror="handleDriveImageError(this)"
              >
              <div class="relative z-10 w-full max-w-[92%] mx-auto text-center text-white space-y-1.5">
                <span class="inline-block px-2.5 py-0.5 rounded bg-amber-600 text-[10px] font-bold uppercase tracking-wide">
                  SÀN GỖ BA LAN CHÍNH HÃNG
                </span>
                <h2 class="text-[15px] sm:text-base font-extrabold leading-tight text-amber-300">
                  KRONOPOL AQUA ZERO - BẢO HÀNH NGẬP NƯỚC
                </h2>
                <p class="text-[11px] text-amber-50 leading-snug">
                  Cốt xanh Green HDF Q7 • Hèm khóa Aqua Pearl 24h • Độ bền AC5/AC6 vượt trội
                </p>
                <div class="grid grid-cols-2 gap-1.5 pt-1 text-[10px]">
                  <div class="bg-white/15 rounded py-1 px-1.5 font-semibold">Vân gỗ 3D tự nhiên</div>
                  <div class="bg-white/15 rounded py-1 px-1.5 font-semibold">An toàn sức khỏe E1</div>
                </div>
                <div class="pt-1 text-[10.5px] font-semibold text-amber-200">
                  Hotline: 0936.434.266 - 0905.513.828
                </div>
              </div>
            </div>

          </div>
        </div>

        <!-- Nút điều hướng 2 Banner -->
        <button 
          type="button" 
          onclick="changeSlide(-1)" 
          aria-label="Banner trước"
          class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition"
        >
          <i class="fa-solid fa-chevron-left text-xs"></i>
        </button>
        <button 
          type="button" 
          onclick="changeSlide(1)" 
          aria-label="Banner tiếp theo"
          class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/40 hover:bg-black/70 text-white flex items-center justify-center transition"
        >
          <i class="fa-solid fa-chevron-right text-xs"></i>
        </button>

        <!-- Chấm tròn chỉ báo Slide -->
        <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
          <button type="button" onclick="goToSlide(0)" class="slider-dot w-6 h-2 rounded-full bg-amber-400 transition-all" aria-label="Slide 1"></button>
          <button type="button" onclick="goToSlide(1)" class="slider-dot w-2.5 h-2 rounded-full bg-white/60 transition-all" aria-label="Slide 2"></button>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 2: DANH MỤC SẢN PHẨM TRANG CHỦ (Tối ưu nhỏ gọn trên Máy Tính & Điện Thoại)
       - Trên máy tính: viết liền trên 1 hàng (hoặc xuống hàng 2), chữ nhỏ gọn, tuyệt đối không xuống dòng bên trong tên danh mục
       ===================================================================== -->
  <section class="py-4 bg-atmBg border-b border-slate-200 w-full">
    <div class="container-1500">
      <div class="flex items-center justify-between mb-2.5">
        <span class="text-xs font-extrabold uppercase text-atmBlue tracking-wide">
          <i class="fa-solid fa-layer-group mr-1.5 text-atmRed"></i>DANH MỤC SẢN PHẨM CHÍNH HÃNG
        </span>
        <span class="text-[11px] text-slate-500 hidden sm:inline">Chọn danh mục để lọc nhanh sản phẩm</span>
      </div>

      <!-- Hiển thị trên Máy tính: các nút danh mục chữ nhỏ gọn, nằm trên 1 hàng hoặc xuống hàng 2, không bao giờ ngắt chữ trong tên danh mục -->
      <div class="hidden md:flex flex-wrap items-center gap-1.5">
        <button onclick="filterByCategory('all', this)" class="cat-filter-btn cat-nowrap-item px-3 py-1.5 rounded border border-atmBlue bg-atmBlue text-white text-xs font-semibold">
          Tất cả sản phẩm (14)
        </button>
        <button onclick="filterByCategory('kaindl-xpt', this)" class="cat-filter-btn cat-nowrap-item px-3 py-1.5 rounded border border-slate-300 bg-white text-slate-700 hover:border-atmBlue hover:text-atmBlue text-xs font-medium">
          Sàn gỗ Kaindl Floorganic XPT
        </button>
        <button onclick="filterByCategory('kaindl-12mm', this)" class="cat-filter-btn cat-nowrap-item px-3 py-1.5 rounded border border-slate-300 bg-white text-slate-700 hover:border-atmBlue hover:text-atmBlue text-xs font-medium">
          KAINDL AQUApro 12mm
        </button>
        <button onclick="filterByCategory('kaindl-8mm', this)" class="cat-filter-btn cat-nowrap-item px-3 py-1.5 rounded border border-slate-300 bg-white text-slate-700 hover:border-atmBlue hover:text-atmBlue text-xs font-medium">
          KAINDL AQUApro 8mm
        </button>
        <button onclick="filterByCategory('kaindl-fishbone', this)" class="cat-filter-btn cat-nowrap-item px-3 py-1.5 rounded border border-slate-300 bg-white text-slate-700 hover:border-atmBlue hover:text-atmBlue text-xs font-medium">
          Sàn gỗ Kaindl Fishbone
        </button>
        <button onclick="filterByCategory('kronopol-symfonia', this)" class="cat-filter-btn cat-nowrap-item px-3 py-1.5 rounded border border-slate-300 bg-white text-slate-700 hover:border-atmBlue hover:text-atmBlue text-xs font-medium">
          Kronopol Aqua Symfonia 12mm/AC5
        </button>
        <button onclick="filterByCategory('kronopol-fiori', this)" class="cat-filter-btn cat-nowrap-item px-3 py-1.5 rounded border border-slate-300 bg-white text-slate-700 hover:border-atmBlue hover:text-atmBlue text-xs font-medium">
          Kronopol Aqua Fiori 10mm/AC6
        </button>
        <button onclick="filterByCategory('kronopol-infinity', this)" class="cat-filter-btn cat-nowrap-item px-3 py-1.5 rounded border border-slate-300 bg-white text-slate-700 hover:border-atmBlue hover:text-atmBlue text-xs font-medium">
          Kronopol Aqua Zero Infinity 10mm/AC5
        </button>
        <button onclick="filterByCategory('phu-kien-arbiton', this)" class="cat-filter-btn cat-nowrap-item px-3 py-1.5 rounded border border-slate-300 bg-white text-slate-700 hover:border-atmBlue hover:text-atmBlue text-xs font-medium">
          Phụ kiện Châu Âu Arbiton
        </button>
      </div>

      <!-- Hiển thị trên Điện thoại: Chia lưới gọn đẹp, chữ nhỏ gọn, không tràn viền -->
      <div class="grid grid-cols-2 sm:grid-cols-3 gap-1.5 md:hidden">
        <button onclick="filterByCategory('all', this)" class="cat-filter-btn cat-nowrap-item px-2 py-1.5 rounded border border-atmBlue bg-atmBlue text-white text-[11px] font-semibold overflow-hidden">
          Tất cả sản phẩm
        </button>
        <button onclick="filterByCategory('kaindl-xpt', this)" class="cat-filter-btn cat-nowrap-item px-2 py-1.5 rounded border border-slate-300 bg-white text-slate-700 text-[11px] font-medium overflow-hidden">
          Kaindl Floorganic XPT
        </button>
        <button onclick="filterByCategory('kaindl-12mm', this)" class="cat-filter-btn cat-nowrap-item px-2 py-1.5 rounded border border-slate-300 bg-white text-slate-700 text-[11px] font-medium overflow-hidden">
          KAINDL AQUApro 12mm
        </button>
        <button onclick="filterByCategory('kaindl-8mm', this)" class="cat-filter-btn cat-nowrap-item px-2 py-1.5 rounded border border-slate-300 bg-white text-slate-700 text-[11px] font-medium overflow-hidden">
          KAINDL AQUApro 8mm
        </button>
        <button onclick="filterByCategory('kaindl-fishbone', this)" class="cat-filter-btn cat-nowrap-item px-2 py-1.5 rounded border border-slate-300 bg-white text-slate-700 text-[11px] font-medium overflow-hidden">
          Kaindl Fishbone
        </button>
        <button onclick="filterByCategory('kronopol-symfonia', this)" class="cat-filter-btn cat-nowrap-item px-2 py-1.5 rounded border border-slate-300 bg-white text-slate-700 text-[11px] font-medium overflow-hidden">
          Kronopol Symfonia 12mm
        </button>
        <button onclick="filterByCategory('kronopol-fiori', this)" class="cat-filter-btn cat-nowrap-item px-2 py-1.5 rounded border border-slate-300 bg-white text-slate-700 text-[11px] font-medium overflow-hidden">
          Kronopol Fiori 10mm
        </button>
        <button onclick="filterByCategory('phu-kien-arbiton', this)" class="cat-filter-btn cat-nowrap-item px-2 py-1.5 rounded border border-slate-300 bg-white text-slate-700 text-[11px] font-medium overflow-hidden">
          Phụ kiện Arbiton
        </button>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 3: 4 GIÁ TRỊ CỐT LÕI (Chuẩn giao diện kaindl.com.vn & kronopolvietnam.com)
       ===================================================================== -->
  <section class="py-5 bg-white border-b border-slate-100 w-full">
    <div class="container-1500">
      <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
        <div class="flex items-start gap-3 p-3 rounded-lg bg-slate-50 border border-slate-200/80">
          <div class="w-9 h-9 rounded-lg bg-atmBlue text-white flex items-center justify-center shrink-0 text-sm">
            <i class="fa-solid fa-droplet-slash"></i>
          </div>
          <div>
            <h3 class="text-xs sm:text-sm font-bold text-atmBlue">SIÊU CHỊU NƯỚC 24H - 100H</h3>
            <p class="text-[11px] text-slate-600 mt-0.5 leading-snug">Hèm khóa Aqua Pro & Aqua Pearl bảo hành cả ngập nước.</p>
          </div>
        </div>
        <div class="flex items-start gap-3 p-3 rounded-lg bg-slate-50 border border-slate-200/80">
          <div class="w-9 h-9 rounded-lg bg-atmBlue text-white flex items-center justify-center shrink-0 text-sm">
            <i class="fa-solid fa-leaf"></i>
          </div>
          <div>
            <h3 class="text-xs sm:text-sm font-bold text-atmBlue">TIÊU CHUẨN CHÂU ÂU E1</h3>
            <p class="text-[11px] text-slate-600 mt-0.5 leading-snug">Cốt gỗ sạch HDF tự nhiên, an toàn sức khỏe gia đình.</p>
          </div>
        </div>
        <div class="flex items-start gap-3 p-3 rounded-lg bg-slate-50 border border-slate-200/80">
          <div class="w-9 h-9 rounded-lg bg-atmBlue text-white flex items-center justify-center shrink-0 text-sm">
            <i class="fa-solid fa-shield-halved"></i>
          </div>
          <div>
            <h3 class="text-xs sm:text-sm font-bold text-atmBlue">CHỐNG TRẦY XƯỚC AC5 / AC6</h3>
            <p class="text-[11px] text-slate-600 mt-0.5 leading-snug">Bề mặt vân gỗ Sồi 3D chịu lực cao, bền màu 30 năm.</p>
          </div>
        </div>
        <div class="flex items-start gap-3 p-3 rounded-lg bg-slate-50 border border-slate-200/80">
          <div class="w-9 h-9 rounded-lg bg-atmBlue text-white flex items-center justify-center shrink-0 text-sm">
            <i class="fa-solid fa-Screwdriver-wrench"></i>
          </div>
          <div>
            <h3 class="text-xs sm:text-sm font-bold text-atmBlue">TỔNG KHO ĐÀ NẴNG UY TÍN</h3>
            <p class="text-[11px] text-slate-600 mt-0.5 leading-snug">Khảo sát tận nơi, thi công chuẩn kỹ thuật tại Đà Nẵng.</p>
          </div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 4: GIỚI THIỆU CÔNG TY TNHH SẢN XUẤT TM & DV ATM VIỆT NAM
       - Lấy ảnh công ty thực tế: 1zI_cY1-hS8O_VQZ2TBrMkCy9R4GYn_3x
       ===================================================================== -->
  <section id="gioi-thieu" class="py-8 bg-white w-full">
    <div class="container-1500">
      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center bg-atmBg p-4 sm:p-6 rounded-xl border border-slate-200">
        
        <!-- Cột Thông tin Công ty (7/12) -->
        <div class="lg:col-span-7 space-y-3">
          <div class="text-xs font-bold uppercase text-atmRed tracking-wider">
            ĐẠI LÝ PHÂN PHỐI & THI CÔNG CHÍNH HÃNG TẠI ĐÀ NẴNG - MIỀN TRUNG
          </div>
          <h2 class="text-lg sm:text-xl md:text-2xl font-extrabold text-atmBlue leading-snug">
            CÔNG TY TNHH SẢN XUẤT TM & DV ATM VIỆT NAM
          </h2>
          <p class="text-xs sm:text-sm text-slate-700 leading-relaxed">
            <strong>CÔNG TY TNHH SẢN XUẤT TM & DV ATM VIỆT NAM</strong> (Mã số thuế: <strong>0402061852</strong>) có trụ sở và Showroom trưng bày tại <strong>119 Nguyễn Công Triều, Phường An Khê, TP Đà Nẵng</strong>. Chúng tôi tự hào là đơn vị phân phối và thi công hoàn thiện chính hãng các dòng <strong>Sàn gỗ Châu Âu cao cấp Kaindl (Cộng hòa Áo)</strong>, <strong>Sàn gỗ Kronopol (Ba Lan)</strong> cùng hệ thống <strong>Phào nẹp Châu Âu Arbiton</strong> và vật liệu hoàn thiện nội thất tại Đà Nẵng và khu vực Miền Trung.
          </p>
          <ul class="space-y-1.5 text-xs sm:text-sm text-slate-700">
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-circle-check text-atmBlue mt-1 shrink-0"></i>
              <span>Cung cấp 100% sản phẩm nhập khẩu chính ngạch Châu Âu (CO, CQ đầy đủ), cốt gỗ sạch đạt chuẩn khí thải E1, CARB P2.</span>
            </li>
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-circle-check text-atmBlue mt-1 shrink-0"></i>
              <span>Chính sách bảo hành chính hãng lên đến 30 năm và cam kết bảo hành ngập nước minh bạch.</span>
            </li>
            <li class="flex items-start gap-2">
              <i class="fa-solid fa-circle-check text-atmBlue mt-1 shrink-0"></i>
              <span>Đội ngũ kỹ thuật viên giàu kinh nghiệm thi công biệt thự, căn hộ cao cấp, khách sạn, văn phòng tại Đà Nẵng.</span>
            </li>
          </ul>
          <div class="pt-2 flex flex-wrap items-center gap-3 text-xs">
            <div class="px-3 py-2 rounded bg-white border border-slate-200 font-semibold text-slate-700">
              <i class="fa-solid fa-location-dot text-atmRed mr-1.5"></i>119 Nguyễn Công Triều, Phường An Khê, TP Đà Nẵng
            </div>
            <div class="px-3 py-2 rounded bg-white border border-slate-200 font-semibold text-atmBlue">
              <i class="fa-solid fa-phone-volume text-atmRed mr-1.5"></i>0936.434.266 - 0905.513.828
            </div>
          </div>
        </div>

        <!-- Cột Ảnh thực tế Công ty (5/12) -->
        <div class="lg:col-span-5">
          <div class="rounded-lg overflow-hidden border border-slate-300 bg-white shadow-sm">
            <img 
              src="https://drive.google.com/thumbnail?id=1zI_cY1-hS8O_VQZ2TBrMkCy9R4GYn_3x&sz=w1000" 
              data-drive-id="1zI_cY1-hS8O_VQZ2TBrMkCy9R4GYn_3x"
              alt="Hình ảnh thực tế Công Ty TNHH Sản Xuất TM & DV ATM Việt Nam" 
              class="w-full h-60 sm:h-72 object-cover"
              onerror="handleDriveImageError(this)"
            >
            <div class="px-3 py-2 bg-white text-center text-xs font-semibold text-slate-600 border-t border-slate-100">
              Showroom & Kho Sàn Gỗ ATM Việt Nam - 119 Nguyễn Công Triều, TP Đà Nẵng
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 5: SẢN PHẨM THỰC TẾ (14 ẢNH SẢN PHẨM TỪ GOOGLE DRIVE)
       - Không để các nhãn dán (badges/stickers) ở trang chủ
       - Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
       - Tên sản phẩm hiển thị đầy đủ, không bị tràn hoặc cắt thiếu chữ
       ===================================================================== -->
  <section id="san-pham-kaindl" class="py-6 bg-white w-full">
    <div class="container-1500">
      
      <!-- KHỐI 1: SÀN GỖ CHÂU ÂU KAINDL - NHẬP KHẨU CỘNG HÒA ÁO -->
      <div class="flatsome-section-title">
        <h2 class="text-base sm:text-lg md:text-xl">SÀN GỖ CHÂU ÂU KAINDL (NHẬP KHẨU ÁO)</h2>
        <div class="flex flex-wrap items-center gap-1.5">
          <span class="cat-nowrap-item text-[11px] font-medium text-slate-600 bg-slate-100 px-2.5 py-1 rounded">Siêu chịu nước 100h</span>
          <span class="cat-nowrap-item text-[11px] font-medium text-slate-600 bg-slate-100 px-2.5 py-1 rounded">Bảo hành 30 năm</span>
        </div>
      </div>

      <p class="text-xs sm:text-sm text-slate-600 mb-5 leading-relaxed">
        Sàn gỗ Kaindl được sản xuất tại Salzburg (Cộng hòa Áo) nổi bật với công nghệ <strong>Floorganic XPT</strong> và <strong>Aqua Pro</strong> chống thấm nước vượt trội, cốt gỗ HDF mật độ cao 870–890 kg/m³ đạt chuẩn khí thải E1 & CARB P2 cùng hệ vân gỗ Sồi Châu Âu tự nhiên.
      </p>

      <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột tablet, 4 cột máy tính -->
      <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">

        <!-- Sản phẩm 1: 1hv9jwezuV3PNLDCiy7g_L6I1WrbWuB3a -->
        <div class="ux-product-box product-card rounded-lg border border-slate-200 bg-white overflow-hidden flex flex-col" data-category="kaindl-xpt">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1hv9jwezuV3PNLDCiy7g_L6I1WrbWuB3a&sz=w800" 
              data-drive-id="1hv9jwezuV3PNLDCiy7g_L6I1WrbWuB3a"
              alt="Sàn gỗ Kaindl Aqua Pro XPT K2909 SC" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] sm:text-xs text-slate-500 font-medium mb-1">Sàn gỗ Kaindl Floorganic XPT</div>
              <h3 class="product-full-title text-xs sm:text-sm font-bold text-slate-800 mb-1.5">
                Sàn gỗ Kaindl Aqua Pro XPT K2909 SC
              </h3>
              <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                <div>Kích thước: 1290 x 193 x 12 mm</div>
                <div>Tiêu chuẩn: AC5, CARB P2 | Xuất xứ: Áo</div>
              </div>
            </div>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
              <span class="text-xs sm:text-sm font-extrabold text-atmRed">Liên hệ báo giá</span>
              <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Sàn gỗ Kaindl Aqua Pro XPT K2909 SC')" class="text-[11px] font-bold text-atmBlue hover:underline">
                Nhận mẫu
              </a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 2: 1mMa86xQX1nXsmIrQpAdfgYkuo5P7vmad -->
        <div class="ux-product-box product-card rounded-lg border border-slate-200 bg-white overflow-hidden flex flex-col" data-category="kaindl-xpt">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1mMa86xQX1nXsmIrQpAdfgYkuo5P7vmad&sz=w800" 
              data-drive-id="1mMa86xQX1nXsmIrQpAdfgYkuo5P7vmad"
              alt="Sàn gỗ Kaindl Aqua XPT K2753 AE" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] sm:text-xs text-slate-500 font-medium mb-1">Sàn gỗ Kaindl Floorganic XPT</div>
              <h3 class="product-full-title text-xs sm:text-sm font-bold text-slate-800 mb-1.5">
                Sàn gỗ Kaindl Aqua XPT K2753 AE
              </h3>
              <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                <div>Kích thước: 1290 x 193 x 12 mm</div>
                <div>Tiêu chuẩn: AC5, Chịu nước 100h | Áo</div>
              </div>
            </div>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
              <span class="text-xs sm:text-sm font-extrabold text-atmRed">Liên hệ báo giá</span>
              <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Sàn gỗ Kaindl Aqua XPT K2753 AE')" class="text-[11px] font-bold text-atmBlue hover:underline">
                Nhận mẫu
              </a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 3: 1tvR1QBqBngYAqViHhX26Kc0_kd8Z0rPb -->
        <div class="ux-product-box product-card rounded-lg border border-slate-200 bg-white overflow-hidden flex flex-col" data-category="kaindl-xpt">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1tvR1QBqBngYAqViHhX26Kc0_kd8Z0rPb&sz=w800" 
              data-drive-id="1tvR1QBqBngYAqViHhX26Kc0_kd8Z0rPb"
              alt="Sàn gỗ Kaindl Aqua XPT K2928 AE" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] sm:text-xs text-slate-500 font-medium mb-1">Sàn gỗ Kaindl Floorganic XPT</div>
              <h3 class="product-full-title text-xs sm:text-sm font-bold text-slate-800 mb-1.5">
                Sàn gỗ Kaindl Aqua XPT K2928 AE
              </h3>
              <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                <div>Kích thước: 1290 x 193 x 12 mm</div>
                <div>Vân gỗ: Aviva Oak (Sồi) | Xuất xứ: Áo</div>
              </div>
            </div>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
              <span class="text-xs sm:text-sm font-extrabold text-atmRed">Liên hệ báo giá</span>
              <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Sàn gỗ Kaindl Aqua XPT K2928 AE')" class="text-[11px] font-bold text-atmBlue hover:underline">
                Nhận mẫu
              </a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 4: 1yIBbAwjI8aOB-W9T8D32Twf3gjR3PPrW -->
        <div class="ux-product-box product-card rounded-lg border border-slate-200 bg-white overflow-hidden flex flex-col" data-category="kaindl-xpt">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1yIBbAwjI8aOB-W9T8D32Twf3gjR3PPrW&sz=w800" 
              data-drive-id="1yIBbAwjI8aOB-W9T8D32Twf3gjR3PPrW"
              alt="Sàn gỗ Kaindl Aqua XPT K2733 RB" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] sm:text-xs text-slate-500 font-medium mb-1">Sàn gỗ Kaindl Floorganic XPT</div>
              <h3 class="product-full-title text-xs sm:text-sm font-bold text-slate-800 mb-1.5">
                Sàn gỗ Kaindl Aqua XPT K2733 RB
              </h3>
              <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                <div>Kích thước: 1383 x 193 x 12 mm</div>
                <div>Vân gỗ: Dakota Oak | Bảo hành 30 năm</div>
              </div>
            </div>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
              <span class="text-xs sm:text-sm font-extrabold text-atmRed">Liên hệ báo giá</span>
              <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Sàn gỗ Kaindl Aqua XPT K2733 RB')" class="text-[11px] font-bold text-atmBlue hover:underline">
                Nhận mẫu
              </a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 5: 1q0Xr500W-rMUks8zsYjnbLZvv_btgnU7 -->
        <div class="ux-product-box product-card rounded-lg border border-slate-200 bg-white overflow-hidden flex flex-col" data-category="kaindl-12mm">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1q0Xr500W-rMUks8zsYjnbLZvv_btgnU7&sz=w800" 
              data-drive-id="1q0Xr500W-rMUks8zsYjnbLZvv_btgnU7"
              alt="Sàn gỗ Kaindl Aqua Pro K2217 SQ" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] sm:text-xs text-slate-500 font-medium mb-1">KAINDL AQUApro 12mm</div>
              <h3 class="product-full-title text-xs sm:text-sm font-bold text-slate-800 mb-1.5">
                Sàn gỗ Kaindl Aqua Pro K2217 SQ
              </h3>
              <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                <div>Kích thước: 1383 x 193 x 12 mm</div>
                <div>Tiêu chuẩn: E1, AC5 | Xuất xứ: Áo</div>
              </div>
            </div>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
              <span class="text-xs sm:text-sm font-extrabold text-atmRed">765.000đ/m²</span>
              <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Sàn gỗ Kaindl Aqua Pro K2217 SQ')" class="text-[11px] font-bold text-atmBlue hover:underline">
                Nhận mẫu
              </a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 6: 12Zl5ofGWqjRrlb76meLrlYv0hkZ1PT21 -->
        <div class="ux-product-box product-card rounded-lg border border-slate-200 bg-white overflow-hidden flex flex-col" data-category="kaindl-12mm">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=12Zl5ofGWqjRrlb76meLrlYv0hkZ1PT21&sz=w800" 
              data-drive-id="12Zl5ofGWqjRrlb76meLrlYv0hkZ1PT21"
              alt="Sàn gỗ Kaindl Aqua Pro K4424 RI" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] sm:text-xs text-slate-500 font-medium mb-1">KAINDL AQUApro 12mm</div>
              <h3 class="product-full-title text-xs sm:text-sm font-bold text-slate-800 mb-1.5">
                Sàn gỗ Kaindl Aqua Pro K4424 RI
              </h3>
              <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                <div>Kích thước: 1383 x 193 x 12 mm</div>
                <div>Tiêu chuẩn: E1, AC5 | Xuất xứ: Áo</div>
              </div>
            </div>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
              <span class="text-xs sm:text-sm font-extrabold text-atmRed">765.000đ/m²</span>
              <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Sàn gỗ Kaindl Aqua Pro K4424 RI')" class="text-[11px] font-bold text-atmBlue hover:underline">
                Nhận mẫu
              </a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 7: 1wY73ITIFu7qjQn_5PdBB167RkfB6EKSc -->
        <div class="ux-product-box product-card rounded-lg border border-slate-200 bg-white overflow-hidden flex flex-col" data-category="kaindl-8mm">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1wY73ITIFu7qjQn_5PdBB167RkfB6EKSc&sz=w800" 
              data-drive-id="1wY73ITIFu7qjQn_5PdBB167RkfB6EKSc"
              alt="Sàn gỗ Kaindl Aqua Pro K5574 AV" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] sm:text-xs text-slate-500 font-medium mb-1">KAINDL AQUApro 8mm</div>
              <h3 class="product-full-title text-xs sm:text-sm font-bold text-slate-800 mb-1.5">
                Sàn gỗ Kaindl Aqua Pro K5574 AV
              </h3>
              <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                <div>Kích thước: 1383 x 193 x 8 mm</div>
                <div>Tiêu chuẩn: E1, AC4 | Xuất xứ: Áo</div>
              </div>
            </div>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
              <span class="text-xs sm:text-sm font-extrabold text-atmRed">455.000đ/m²</span>
              <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Sàn gỗ Kaindl Aqua Pro K5574 AV')" class="text-[11px] font-bold text-atmBlue hover:underline">
                Nhận mẫu
              </a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 8: 1WWVj5WrjnS0HwIcEoeli3PPeFPcGctQJ -->
        <div class="ux-product-box product-card rounded-lg border border-slate-200 bg-white overflow-hidden flex flex-col" data-category="kaindl-fishbone">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1WWVj5WrjnS0HwIcEoeli3PPeFPcGctQJ&sz=w800" 
              data-drive-id="1WWVj5WrjnS0HwIcEoeli3PPeFPcGctQJ"
              alt="Sàn gỗ Kaindl Xương cá K4439" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] sm:text-xs text-slate-500 font-medium mb-1">Sàn gỗ Kaindl Fishbone</div>
              <h3 class="product-full-title text-xs sm:text-sm font-bold text-slate-800 mb-1.5">
                Sàn gỗ Kaindl Xương cá K4439
              </h3>
              <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                <div>Kích thước: 1383 x 244 x 8 mm</div>
                <div>Vân gỗ: Sồi Xương Cá | E1, AC4</div>
              </div>
            </div>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
              <span class="text-xs sm:text-sm font-extrabold text-atmRed">565.000đ/m²</span>
              <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Sàn gỗ Kaindl Xương cá K4439')" class="text-[11px] font-bold text-atmBlue hover:underline">
                Nhận mẫu
              </a>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 6: SÀN GỖ KRONOPOL BA LAN & PHỤ KIỆN CHÂU ÂU ARBITON
       ===================================================================== -->
  <section id="san-pham-kronopol" class="py-6 bg-atmBg w-full border-t border-slate-200">
    <div class="container-1500">
      
      <div class="flatsome-section-title">
        <h2 class="text-base sm:text-lg md:text-xl">SÀN GỖ KRONOPOL (BA LAN) & PHỤ KIỆN ARBITON</h2>
        <div class="flex flex-wrap items-center gap-1.5">
          <span class="cat-nowrap-item text-[11px] font-medium text-slate-600 bg-white px-2.5 py-1 rounded border border-slate-200">Hèm khóa Aqua Pearl</span>
          <span class="cat-nowrap-item text-[11px] font-medium text-slate-600 bg-white px-2.5 py-1 rounded border border-slate-200">Cốt xanh Green HDF Q7</span>
        </div>
      </div>

      <p class="text-xs sm:text-sm text-slate-600 mb-5 leading-relaxed">
        Sàn gỗ <strong>Kronopol Aqua Zero</strong> thuộc tập đoàn <strong>Swiss Krono (Ba Lan)</strong> sở hữu cốt gỗ xanh chịu nước thế hệ mới, hèm khóa chống thấm Aqua Pearl 24 giờ và bề mặt vân gỗ 3D EIR chống trầy xước tiêu chuẩn AC5/AC6.
      </p>

      <!-- Lưới sản phẩm: 2 cột trên điện thoại, 3 cột tablet, 4 cột máy tính -->
      <div id="phu-kien" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">

        <!-- Sản phẩm 9: 16XIUXYoDf67hofbNLZODACe268I62i79 -->
        <div class="ux-product-box product-card rounded-lg border border-slate-200 bg-white overflow-hidden flex flex-col" data-category="kaindl-fishbone">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=16XIUXYoDf67hofbNLZODACe268I62i79&sz=w800" 
              data-drive-id="16XIUXYoDf67hofbNLZODACe268I62i79"
              alt="Sàn gỗ Kaindl Xương cá K4378" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] sm:text-xs text-slate-500 font-medium mb-1">Sàn gỗ Kaindl Fishbone</div>
              <h3 class="product-full-title text-xs sm:text-sm font-bold text-slate-800 mb-1.5">
                Sàn gỗ Kaindl Xương cá K4378
              </h3>
              <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                <div>Kích thước: 1383 x 244 x 8 mm</div>
                <div>Vân gỗ: Sồi Xương Cá | Xuất xứ: Áo</div>
              </div>
            </div>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
              <span class="text-xs sm:text-sm font-extrabold text-atmRed">565.000đ/m²</span>
              <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Sàn gỗ Kaindl Xương cá K4378')" class="text-[11px] font-bold text-atmBlue hover:underline">
                Nhận mẫu
              </a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 10: 19W2_yQQ1ntVIc3MLSD2nXzLM4thBmW-9 -->
        <div class="ux-product-box product-card rounded-lg border border-slate-200 bg-white overflow-hidden flex flex-col" data-category="kronopol-symfonia">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=19W2_yQQ1ntVIc3MLSD2nXzLM4thBmW-9&sz=w800" 
              data-drive-id="19W2_yQQ1ntVIc3MLSD2nXzLM4thBmW-9"
              alt="Sàn gỗ Kronopol Aqua Symfonia D40104" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] sm:text-xs text-slate-500 font-medium mb-1">Kronopol Aqua Symfonia 12mm/AC5</div>
              <h3 class="product-full-title text-xs sm:text-sm font-bold text-slate-800 mb-1.5">
                Sàn gỗ Kronopol Aqua Symfonia D40104
              </h3>
              <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                <div>Kích thước: 1380 x 191 x 12 mm</div>
                <div>Tiêu chuẩn: E1, AC5 | Xuất xứ: Ba Lan</div>
              </div>
            </div>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
              <span class="text-xs sm:text-sm font-extrabold text-atmRed">865.000đ/m²</span>
              <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Sàn gỗ Kronopol Aqua Symfonia D40104')" class="text-[11px] font-bold text-atmBlue hover:underline">
                Nhận mẫu
              </a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 11: 1MdYJJ_pUzdIvg7jdCzKqu2H7Cc50qLgs -->
        <div class="ux-product-box product-card rounded-lg border border-slate-200 bg-white overflow-hidden flex flex-col" data-category="kronopol-symfonia">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1MdYJJ_pUzdIvg7jdCzKqu2H7Cc50qLgs&sz=w800" 
              data-drive-id="1MdYJJ_pUzdIvg7jdCzKqu2H7Cc50qLgs"
              alt="Sàn gỗ Kronopol Aqua Symfonia D40394" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] sm:text-xs text-slate-500 font-medium mb-1">Kronopol Aqua Symfonia 12mm/AC5</div>
              <h3 class="product-full-title text-xs sm:text-sm font-bold text-slate-800 mb-1.5">
                Sàn gỗ Kronopol Aqua Symfonia D40394
              </h3>
              <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                <div>Kích thước: 1380 x 191 x 12 mm</div>
                <div>Tiêu chuẩn: E1, AC5 | Xuất xứ: Ba Lan</div>
              </div>
            </div>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
              <span class="text-xs sm:text-sm font-extrabold text-atmRed">865.000đ/m²</span>
              <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Sàn gỗ Kronopol Aqua Symfonia D40394')" class="text-[11px] font-bold text-atmBlue hover:underline">
                Nhận mẫu
              </a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 12: 1PsJw2s5f4K_RkpbFMg-9FzE1IfJSXWeH -->
        <div class="ux-product-box product-card rounded-lg border border-slate-200 bg-white overflow-hidden flex flex-col" data-category="kronopol-fiori">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1PsJw2s5f4K_RkpbFMg-9FzE1IfJSXWeH&sz=w800" 
              data-drive-id="1PsJw2s5f4K_RkpbFMg-9FzE1IfJSXWeH"
              alt="Sàn gỗ Kronopol Aqua Zero Fiori D4588" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] sm:text-xs text-slate-500 font-medium mb-1">Kronopol Aqua Fiori 10mm/AC6</div>
              <h3 class="product-full-title text-xs sm:text-sm font-bold text-slate-800 mb-1.5">
                Sàn gỗ Kronopol Aqua Zero Fiori D4588
              </h3>
              <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                <div>Kích thước: 1380 x 159 x 10 mm</div>
                <div>Vân 3D Sunflower Oak | AC6 Ba Lan</div>
              </div>
            </div>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
              <span class="text-xs sm:text-sm font-extrabold text-atmRed">795.000đ/m²</span>
              <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Sàn gỗ Kronopol Aqua Zero Fiori D4588')" class="text-[11px] font-bold text-atmBlue hover:underline">
                Nhận mẫu
              </a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 13: 1uPBdZ9Lrb05JAu1uR8hwE0idEd8B4FI1 -->
        <div class="ux-product-box product-card rounded-lg border border-slate-200 bg-white overflow-hidden flex flex-col" data-category="kronopol-infinity">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1uPBdZ9Lrb05JAu1uR8hwE0idEd8B4FI1&sz=w800" 
              data-drive-id="1uPBdZ9Lrb05JAu1uR8hwE0idEd8B4FI1"
              alt="Sàn gỗ Kronopol Aqua Zero Infinity D4592" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] sm:text-xs text-slate-500 font-medium mb-1">Kronopol Aqua Zero Infinity 10mm/AC5</div>
              <h3 class="product-full-title text-xs sm:text-sm font-bold text-slate-800 mb-1.5">
                Sàn gỗ Kronopol Aqua Zero Infinity D4592
              </h3>
              <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                <div>Kích thước: 1380 x 242 x 10 mm</div>
                <div>Bản rộng Châu Âu | AC5 Ba Lan</div>
              </div>
            </div>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
              <span class="text-xs sm:text-sm font-extrabold text-atmRed">780.000đ/m²</span>
              <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Sàn gỗ Kronopol Aqua Zero Infinity D4592')" class="text-[11px] font-bold text-atmBlue hover:underline">
                Nhận mẫu
              </a>
            </div>
          </div>
        </div>

        <!-- Sản phẩm 14: 1Gq9x0MFgt_jTZJwpaw77NyoqX8O8UrS1 -->
        <div class="ux-product-box product-card rounded-lg border border-slate-200 bg-white overflow-hidden flex flex-col" data-category="phu-kien-arbiton">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1Gq9x0MFgt_jTZJwpaw77NyoqX8O8UrS1&sz=w800" 
              data-drive-id="1Gq9x0MFgt_jTZJwpaw77NyoqX8O8UrS1"
              alt="Phào chân tường Châu Âu Arbiton 04" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
            <div>
              <div class="text-[10.5px] sm:text-xs text-slate-500 font-medium mb-1">Phụ kiện Châu Âu Arbiton</div>
              <h3 class="product-full-title text-xs sm:text-sm font-bold text-slate-800 mb-1.5">
                Phào chân tường Châu Âu Arbiton 04
              </h3>
              <div class="text-[11px] text-slate-600 space-y-0.5 mb-2">
                <div>Quy cách: 2400 x 80 x 15 mm</div>
                <div>Chống nước 100%, đàn hồi ôm sát tường</div>
              </div>
            </div>
            <div class="pt-2 border-t border-slate-100 flex items-center justify-between gap-1">
              <span class="text-xs sm:text-sm font-extrabold text-atmRed">Liên hệ</span>
              <a href="#bao-gia-lien-he" onclick="selectProductForQuote('Phào chân tường Châu Âu Arbiton 04')" class="text-[11px] font-bold text-atmBlue hover:underline">
                Nhận mẫu
              </a>
            </div>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 7: DANH MỤC CÁC DỰ ÁN & CÔNG TRÌNH THỰC TẾ TẠI ĐÀ NẴNG
       - Sử dụng toàn bộ ảnh công trình thực tế từ Google Drive
       ===================================================================== -->
  <section id="du-an-da-nang" class="py-8 bg-white w-full border-t border-slate-200">
    <div class="container-1500">
      
      <div class="flatsome-section-title">
        <h2 class="text-base sm:text-lg md:text-xl">DỰ ÁN & CÔNG TRÌNH THI CÔNG TẠI ĐÀ NẴNG</h2>
        <span class="text-xs text-slate-500 font-medium">Hình ảnh nghiệm thu thực tế bởi đội ngũ kỹ thuật ATM Việt Nam</span>
      </div>

      <!-- Lưới dự án: 2 cột trên điện thoại, 4 cột trên máy tính -->
      <div class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">

        <!-- Công trình 1: 1vfbxmbBE5X-W0j-zBCcCZGaa1etzNJ2r -->
        <div class="rounded-lg border border-slate-200 overflow-hidden bg-white ux-product-box">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1vfbxmbBE5X-W0j-zBCcCZGaa1etzNJ2r&sz=w800" 
              data-drive-id="1vfbxmbBE5X-W0j-zBCcCZGaa1etzNJ2r"
              alt="Công trình Biệt thự Euro Village Đà Nẵng" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5">
            <h3 class="product-full-title text-xs sm:text-sm font-bold text-atmBlue mb-1">
              Biệt thự Euro Village Đà Nẵng
            </h3>
            <p class="text-[11px] text-slate-600 leading-snug">
              Thi công 185m² Sàn gỗ Kaindl Aqua Pro 12mm K4424 tại đường Trần Hưng Đạo, An Hải, Đà Nẵng.
            </p>
          </div>
        </div>

        <!-- Công trình 2: 1JUY5C8ye2QD2K1glBtRtv9aMLjtz_3O1 -->
        <div class="rounded-lg border border-slate-200 overflow-hidden bg-white ux-product-box">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1JUY5C8ye2QD2K1glBtRtv9aMLjtz_3O1&sz=w800" 
              data-drive-id="1JUY5C8ye2QD2K1glBtRtv9aMLjtz_3O1"
              alt="Công trình Căn hộ The Monarchy Đà Nẵng" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5">
            <h3 class="product-full-title text-xs sm:text-sm font-bold text-atmBlue mb-1">
              Căn hộ Monarchy Đà Nẵng
            </h3>
            <p class="text-[11px] text-slate-600 leading-snug">
              Lắp đặt trọn gói Sàn gỗ Kronopol Aqua Symfonia D40104 tại 535 Trần Hưng Đạo, Đà Nẵng.
            </p>
          </div>
        </div>

        <!-- Công trình 3: 1eA06-E2FXjRtQXCUTPn5Ej3NTGhDpZT- -->
        <div class="rounded-lg border border-slate-200 overflow-hidden bg-white ux-product-box">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1eA06-E2FXjRtQXCUTPn5Ej3NTGhDpZT-&sz=w800" 
              data-drive-id="1eA06-E2FXjRtQXCUTPn5Ej3NTGhDpZT-"
              alt="Công trình Căn hộ Hiyori Garden Tower Đà Nẵng" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5">
            <h3 class="product-full-title text-xs sm:text-sm font-bold text-atmBlue mb-1">
              Căn hộ Hiyori Garden Tower Đà Nẵng
            </h3>
            <p class="text-[11px] text-slate-600 leading-snug">
              Hoàn thiện Sàn gỗ Kaindl Floorganic XPT K2909 chống ồn tại đường Võ Văn Kiệt, Đà Nẵng.
            </p>
          </div>
        </div>

        <!-- Công trình 4: 1iQwq6KV0bx79dzrD_TsToktor4mH7_n_ -->
        <div class="rounded-lg border border-slate-200 overflow-hidden bg-white ux-product-box">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1iQwq6KV0bx79dzrD_TsToktor4mH7_n_&sz=w800" 
              data-drive-id="1iQwq6KV0bx79dzrD_TsToktor4mH7_n_"
              alt="Công trình Khu đô thị Hòa Xuân Đà Nẵng" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5">
            <h3 class="product-full-title text-xs sm:text-sm font-bold text-atmBlue mb-1">
              Nhà phố Khu đô thị Hòa Xuân Đà Nẵng
            </h3>
            <p class="text-[11px] text-slate-600 leading-snug">
              Thi công 140m² Sàn gỗ Xương cá Kaindl Fishbone K4439 sang trọng tại Khu đô thị Hòa Xuân.
            </p>
          </div>
        </div>

        <!-- Công trình 5: 1YNMO6kTL8bkfZ2TfCchsKVowEFAv4qpZ -->
        <div class="rounded-lg border border-slate-200 overflow-hidden bg-white ux-product-box">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1YNMO6kTL8bkfZ2TfCchsKVowEFAv4qpZ&sz=w800" 
              data-drive-id="1YNMO6kTL8bkfZ2TfCchsKVowEFAv4qpZ"
              alt="Công trình Biệt thự Khu đô thị Nam Hòa Xuân" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5">
            <h3 class="product-full-title text-xs sm:text-sm font-bold text-atmBlue mb-1">
              Biệt thự Khu đô thị Nam Hòa Xuân
            </h3>
            <p class="text-[11px] text-slate-600 leading-snug">
              Lắp đặt 210m² Sàn gỗ Ba Lan Kronopol Aqua Fiori D4588 chuẩn AC6 siêu chịu nước.
            </p>
          </div>
        </div>

        <!-- Công trình 6: 1Xu8HgIVttsuZPBOy1yheMhIdU3jUTspI -->
        <div class="rounded-lg border border-slate-200 overflow-hidden bg-white ux-product-box">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1Xu8HgIVttsuZPBOy1yheMhIdU3jUTspI&sz=w800" 
              data-drive-id="1Xu8HgIVttsuZPBOy1yheMhIdU3jUTspI"
              alt="Công trình Căn hộ Azura Đà Nẵng" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5">
            <h3 class="product-full-title text-xs sm:text-sm font-bold text-atmBlue mb-1">
              Căn hộ Azura Đà Nẵng
            </h3>
            <p class="text-[11px] text-slate-600 leading-snug">
              Thi công Sàn gỗ Kaindl Aqua Pro K2217 SQ kết hợp phào chân tường Arbiton tại 339 Trần Hưng Đạo.
            </p>
          </div>
        </div>

        <!-- Công trình 7: 1UTe_Nz3Jem_9Q9t08tNRKafz3eZiWvFN -->
        <div class="rounded-lg border border-slate-200 overflow-hidden bg-white ux-product-box">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1UTe_Nz3Jem_9Q9t08tNRKafz3eZiWvFN&sz=w800" 
              data-drive-id="1UTe_Nz3Jem_9Q9t08tNRKafz3eZiWvFN"
              alt="Công trình Khu đô thị FPT City Đà Nẵng" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5">
            <h3 class="product-full-title text-xs sm:text-sm font-bold text-atmBlue mb-1">
              Biệt thự Khu đô thị FPT City Đà Nẵng
            </h3>
            <p class="text-[11px] text-slate-600 leading-snug">
              Hoàn thiện hạng mục Sàn gỗ Kronopol Aqua Zero Infinity D4592 bản rộng tại Ngũ Hành Sơn, Đà Nẵng.
            </p>
          </div>
        </div>

        <!-- Công trình 8: 1YNMO6kTL8bkfZ2TfCchsKVowEFAv4qpZ (Ảnh thứ 8 trong danh sách) -->
        <div class="rounded-lg border border-slate-200 overflow-hidden bg-white ux-product-box">
          <div class="aspect-4/3 w-full bg-slate-100 overflow-hidden">
            <img 
              src="https://drive.google.com/thumbnail?id=1YNMO6kTL8bkfZ2TfCchsKVowEFAv4qpZ&sz=w800" 
              data-drive-id="1YNMO6kTL8bkfZ2TfCchsKVowEFAv4qpZ"
              alt="Công trình Indochina Mall Bạch Đằng Đà Nẵng" 
              class="w-full h-full object-cover"
              onerror="handleDriveImageError(this)"
            >
          </div>
          <div class="p-2.5 sm:p-3.5">
            <h3 class="product-full-title text-xs sm:text-sm font-bold text-atmBlue mb-1">
              Khu căn hộ Indochina Bạch Đằng Đà Nẵng
            </h3>
            <p class="text-[11px] text-slate-600 leading-snug">
              Lắp đặt Sàn gỗ Kaindl Aqua XPT K2753 AE tại 74 Bạch Đằng, Hải Châu, Đà Nẵng.
            </p>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 8: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (KINH NGHIỆM & TƯ VẤN SÀN GỖ)
       ===================================================================== -->
  <section id="tin-tuc" class="py-8 bg-atmBg w-full border-t border-slate-200">
    <div class="container-1500">
      
      <div class="flatsome-section-title">
        <h2 class="text-base sm:text-lg md:text-xl">BÀI VIẾT & KINH NGHIỆM CHỌN SÀN GỖ</h2>
        <span class="text-xs text-slate-500 font-medium">Cẩm nang kỹ thuật từ chuyên gia Sàn gỗ Châu Âu</span>
      </div>

      <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4">
        
        <!-- Bài viết 1 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between p-4 ux-product-box">
          <div>
            <div class="text-[11px] font-bold text-atmRed uppercase mb-1">Tư vấn chọn sàn gỗ</div>
            <h3 class="product-full-title text-sm font-bold text-atmBlue mb-2">
              Chọn sàn gỗ Châu Âu cho từng không gian: Góc tư vấn từ chuyên gia Kaindl & Kronopol
            </h3>
            <p class="text-xs text-slate-600 leading-relaxed">
              Hướng dẫn cách phối màu vân gỗ Sồi sáng (Vivo Oak, Aviva Oak) cho căn hộ hiện đại và chọn độ dày 8mm, 10mm, 12mm phù hợp từng mật độ đi lại tại Đà Nẵng.
            </p>
          </div>
          <div class="mt-3 pt-2.5 border-t border-slate-100 flex items-center justify-between text-[11px] text-slate-500">
            <span>Chuyên mục: Kinh nghiệm Sàn gỗ</span>
            <a href="#bao-gia-lien-he" class="font-bold text-atmBlue hover:underline">Tư vấn thêm →</a>
          </div>
        </article>

        <!-- Bài viết 2 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between p-4 ux-product-box">
          <div>
            <div class="text-[11px] font-bold text-atmRed uppercase mb-1">Tiêu chuẩn kỹ thuật</div>
            <h3 class="product-full-title text-sm font-bold text-atmBlue mb-2">
              Tìm hiểu sự khác biệt giữa tiêu chuẩn E1, CARB P2 và chỉ số chống mài mòn AC4, AC5, AC6
            </h3>
            <p class="text-xs text-slate-600 leading-relaxed">
              Giải mã các thông số kỹ thuật quan trọng trên hộp sàn gỗ Châu Âu nhập khẩu giúp gia chủ lựa chọn vật liệu lát sàn an toàn tuyệt đối cho sức khỏe trẻ nhỏ.
            </p>
          </div>
          <div class="mt-3 pt-2.5 border-t border-slate-100 flex items-center justify-between text-[11px] text-slate-500">
            <span>Chuyên mục: Tiêu chuẩn Châu Âu</span>
            <a href="#bao-gia-lien-he" class="font-bold text-atmBlue hover:underline">Tư vấn thêm →</a>
          </div>
        </article>

        <!-- Bài viết 3 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between p-4 ux-product-box">
          <div>
            <div class="text-[11px] font-bold text-atmRed uppercase mb-1">Hướng dẫn bảo quản</div>
            <h3 class="product-full-title text-sm font-bold text-atmBlue mb-2">
              Kinh nghiệm vệ sinh và chống nồm ẩm cho sàn gỗ công nghiệp bền đẹp trên 30 năm
            </h3>
            <p class="text-xs text-slate-600 leading-relaxed">
              Bí quyết sử dụng nước lau sàn chuyên dụng và xử lý kịp thời khi sàn bị đổ nước với công nghệ hèm khóa khít Aqua Pro & Aqua Pearl không lo phồng rộp.
            </p>
          </div>
          <div class="mt-3 pt-2.5 border-t border-slate-100 flex items-center justify-between text-[11px] text-slate-500">
            <span>Chuyên mục: Bảo dưỡng Sàn gỗ</span>
            <a href="#bao-gia-lien-he" class="font-bold text-atmBlue hover:underline">Tư vấn thêm →</a>
          </div>
        </article>

        <!-- Bài viết 4 -->
        <article class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between p-4 ux-product-box">
          <div>
            <div class="text-[11px] font-bold text-atmRed uppercase mb-1">Báo giá thi công</div>
            <h3 class="product-full-title text-sm font-bold text-atmBlue mb-2">
              Quy trình khảo sát và thi công sàn gỗ Châu Âu chuẩn kỹ thuật tại ATM Việt Nam Đà Nẵng
            </h3>
            <p class="text-xs text-slate-600 leading-relaxed">
              Từ khâu kiểm tra độ phẳng cốt nền, trải foam xốp giảm ồn Châu Âu đến lắp đặt hèm khóa và đóng phào nẹp Arbiton tỉ mỉ không để lộ khe hở.
            </p>
          </div>
          <div class="mt-3 pt-2.5 border-t border-slate-100 flex items-center justify-between text-[11px] text-slate-500">
            <span>Chuyên mục: Thi công Sàn gỗ</span>
            <a href="#bao-gia-lien-he" class="font-bold text-atmBlue hover:underline">Tư vấn thêm →</a>
          </div>
        </article>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 9: DANH MỤC CÁC ĐỐI TÁC & THƯƠNG HIỆU ĐỒNG HÀNH
       ===================================================================== -->
  <section class="py-7 bg-white w-full border-t border-slate-200">
    <div class="container-1500">
      <div class="flatsome-section-title">
        <h2 class="text-base sm:text-lg md:text-xl">ĐỐI TÁC & THƯƠNG HIỆU ĐỒNG HÀNH</h2>
        <span class="text-xs text-slate-500">Hệ sinh thái thương hiệu Châu Âu & đối tác dự án uy tín</span>
      </div>

      <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
        <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
          <div class="text-sm font-black text-atmRed tracking-wider">KAINDL</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Sàn gỗ Cộng hòa Áo</div>
        </div>
        <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
          <div class="text-sm font-black text-atmBlue tracking-wider">KRONOPOL</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Swiss Krono Ba Lan</div>
        </div>
        <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
          <div class="text-sm font-black text-slate-800 tracking-wider">ARBITON</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Phụ kiện Châu Âu</div>
        </div>
        <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
          <div class="text-sm font-black text-emerald-700 tracking-wider">EPLF® EUROPE</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Hiệp hội Sàn gỗ Châu Âu</div>
        </div>
        <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
          <div class="text-sm font-black text-sky-700 tracking-wider">BLUE ANGEL</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Chứng nhận Xanh Đức</div>
        </div>
        <div class="p-3.5 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
          <div class="text-sm font-black text-amber-700 tracking-wider">1ST FLOOR</div>
          <div class="text-[11px] text-slate-500 mt-0.5">Hệ thống Sàn gỗ Châu Âu</div>
        </div>
      </div>
    </div>
  </section>

  <!-- =====================================================================
       SECTION 10: FORM YÊU CẦU BÁO GIÁ + GOOGLE MAP + FANPAGE NGOÀI TRANG CHỦ
       ===================================================================== -->
  <section id="bao-gia-lien-he" class="py-8 bg-atmBg w-full border-t border-slate-200">
    <div class="container-1500">
      
      <div class="flatsome-section-title">
        <h2 class="text-base sm:text-lg md:text-xl">YÊU CẦU BÁO GIÁ, BẢN ĐỒ GOOGLE MAPS & FANPAGE</h2>
        <span class="text-xs text-slate-600 font-semibold">Hỗ trợ mang mẫu tận công trình miễn phí tại Đà Nẵng</span>
      </div>

      <div class="grid grid-cols-1 lg:grid-cols-12 gap-6">
        
        <!-- 1. FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ (4/12) -->
        <div class="lg:col-span-4 bg-white p-5 rounded-xl border border-slate-200 shadow-xs">
          <div class="border-b border-slate-100 pb-3 mb-4">
            <h3 class="text-base font-extrabold text-atmBlue uppercase">NHẬN BÁO GIÁ MIỄN PHÍ</h3>
            <p class="text-xs text-slate-500 mt-0.5">Vui lòng nhập thông tin, chuyên viên ATM Việt Nam sẽ liên hệ báo giá chi tiết ngay.</p>
          </div>

          <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3 text-xs">
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Họ và tên của bạn *</label>
              <input type="text" id="quoteName" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 rounded border border-slate-300 focus:outline-none focus:border-atmBlue">
            </div>
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Số điện thoại liên hệ *</label>
              <input type="tel" id="quotePhone" required placeholder="Ví dụ: 0936 434 266" class="w-full px-3 py-2 rounded border border-slate-300 focus:outline-none focus:border-atmBlue">
            </div>
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Dòng sản phẩm quan tâm</label>
              <select id="quoteProduct" class="w-full px-3 py-2 rounded border border-slate-300 focus:outline-none focus:border-atmBlue bg-white">
                <option value="Tư vấn tổng hợp Sàn gỗ Châu Âu">Tư vấn tổng hợp Sàn gỗ Châu Âu</option>
                <option value="Sàn gỗ Kaindl Floorganic XPT (Áo)">Sàn gỗ Kaindl Floorganic XPT (Áo)</option>
                <option value="Sàn gỗ KAINDL AQUApro 12mm">Sàn gỗ KAINDL AQUApro 12mm</option>
                <option value="Sàn gỗ KAINDL AQUApro 8mm">Sàn gỗ KAINDL AQUApro 8mm</option>
                <option value="Sàn gỗ Kaindl Fishbone (Xương cá)">Sàn gỗ Kaindl Fishbone (Xương cá)</option>
                <option value="Sàn gỗ Kronopol Aqua Symfonia 12mm/AC5">Sàn gỗ Kronopol Aqua Symfonia 12mm/AC5</option>
                <option value="Sàn gỗ Kronopol Aqua Fiori 10mm/AC6">Sàn gỗ Kronopol Aqua Fiori 10mm/AC6</option>
                <option value="Sàn gỗ Kronopol Aqua Zero Infinity 10mm/AC5">Sàn gỗ Kronopol Aqua Zero Infinity 10mm/AC5</option>
                <option value="Phụ kiện Sàn gỗ Châu Âu Arbiton">Phụ kiện Sàn gỗ Châu Âu Arbiton</option>
              </select>
            </div>
            <div>
              <label class="block font-semibold text-slate-700 mb-1">Diện tích dự kiến (m²) & Địa chỉ công trình</label>
              <textarea id="quoteNote" rows="3" placeholder="Nhập diện tích (m²), địa chỉ tại Đà Nẵng hoặc yêu cầu mang mẫu..." class="w-full px-3 py-2 rounded border border-slate-300 focus:outline-none focus:border-atmBlue"></textarea>
            </div>
            <button type="submit" class="w-full py-2.5 px-4 rounded bg-atmRed hover:bg-red-700 text-white font-bold uppercase tracking-wide transition cursor-pointer">
              GỬI YÊU CẦU BÁO GIÁ NGAY
            </button>
          </form>

          <!-- Thông báo gửi thành công -->
          <div id="quoteSuccessBox" class="hidden mt-3 p-3 rounded bg-emerald-50 border border-emerald-200 text-emerald-800 text-xs">
            <div class="font-bold mb-0.5"><i class="fa-solid fa-circle-check mr-1"></i>Đã ghi nhận yêu cầu báo giá!</div>
            <div id="quoteSuccessText">Phòng Kinh doanh ATM Việt Nam (0936.434.266 - 0905.513.828) sẽ liên hệ quý khách ngay.</div>
          </div>
        </div>

        <!-- 2. ĐƯA ẢNH BẢN ĐỒ GOOGLE MAP RA NGOÀI TRANG CHỦ (4/12) -->
        <div class="lg:col-span-4 bg-white p-5 rounded-xl border border-slate-200 shadow-xs flex flex-col justify-between">
          <div>
            <div class="border-b border-slate-100 pb-3 mb-3 flex items-center justify-between gap-2">
              <div>
                <h3 class="text-base font-extrabold text-atmBlue uppercase">BẢN ĐỒ SHOWROOM ĐÀ NẴNG</h3>
                <p class="text-xs text-slate-500 mt-0.5">119 Nguyễn Công Triều, Phường An Khê, TP Đà Nẵng</p>
              </div>
              <a 
                href="https://share.google/DiBzuBTxcYm8UBxZO" 
                target="_blank" 
                rel="noopener noreferrer"
                class="shrink-0 px-2.5 py-1.5 rounded bg-atmBlue text-white text-[11px] font-bold hover:bg-atmDark transition"
              >
                <i class="fa-solid fa-map-location-dot mr-1"></i>Mở Map
              </a>
            </div>

            <!-- Google Map trực tiếp ngoài trang chủ -->
            <div class="w-full h-64 rounded-lg overflow-hidden border border-slate-200 bg-slate-100">
              <iframe 
                title="Bản đồ Công Ty TNHH SX TM & DV ATM Việt Nam - 119 Nguyễn Công Triều, Đà Nẵng"
                src="https://maps.google.com/maps?q=119%20Nguy%E1%BB%85n%20C%C3%B4ng%20Tri%E1%BB%81u,%20An%20Kh%C3%AA,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed" 
                class="w-full h-full border-0" 
                allowfullscreen="" 
                loading="lazy" 
                referrerpolicy="no-referrer-when-downgrade">
              </iframe>
            </div>
          </div>

          <div class="mt-3 pt-3 border-t border-slate-100 flex items-center justify-between text-xs">
            <span class="text-slate-600 font-medium"><i class="fa-solid fa-location-arrow text-atmRed mr-1"></i>Chỉ đường Google Maps chính thức:</span>
            <a href="https://share.google/DiBzuBTxcYm8UBxZO" target="_blank" rel="noopener noreferrer" class="font-bold text-atmBlue hover:underline">
              Xem trên Google Maps →
            </a>
          </div>
        </div>

        <!-- 3. ĐƯA FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ (4/12) -->
        <div class="lg:col-span-4 bg-white p-5 rounded-xl border border-slate-200 shadow-xs flex flex-col justify-between">
          <div>
            <div class="border-b border-slate-100 pb-3 mb-3 flex items-center justify-between gap-2">
              <div>
                <h3 class="text-base font-extrabold text-atmBlue uppercase">FANPAGE FACEBOOK CHÍNH THỨC</h3>
                <p class="text-xs text-slate-500 mt-0.5">Cập nhật hình ảnh thi công thực tế hàng ngày</p>
              </div>
              <a 
                href="https://www.facebook.com/profile.php?id=100064390740558" 
                target="_blank" 
                rel="noopener noreferrer"
                class="shrink-0 px-2.5 py-1.5 rounded bg-[#1877F2] text-white text-[11px] font-bold hover:bg-blue-700 transition"
              >
                <i class="fa-brands fa-facebook mr-1"></i>Theo dõi
              </a>
            </div>

            <!-- Khung Fanpage trực quan + Plugin nhúng Facebook -->
            <div class="rounded-lg border border-slate-200 overflow-hidden bg-slate-50">
              <div class="relative h-28 bg-gradient-to-r from-atmDark to-atmBlue p-3 flex items-end">
                <img 
                  src="https://drive.google.com/thumbnail?id=1zI_cY1-hS8O_VQZ2TBrMkCy9R4GYn_3x&sz=w600" 
                  data-drive-id="1zI_cY1-hS8O_VQZ2TBrMkCy9R4GYn_3x"
                  alt="Ảnh bìa Fanpage ATM Việt Nam" 
                  class="absolute inset-0 w-full h-full object-cover opacity-35"
                  onerror="handleDriveImageError(this)"
                >
                <div class="relative z-10 flex items-center gap-2.5">
                  <div class="w-12 h-12 rounded-lg bg-white p-1 shadow border border-white shrink-0 flex items-center justify-center overflow-hidden">
                    <img 
                      src="https://drive.google.com/thumbnail?id=15EXVtS8kteXe5ITBqmin2tkRMdHbW7mM&sz=w200" 
                      data-drive-id="15EXVtS8kteXe5ITBqmin2tkRMdHbW7mM"
                      data-fallback-type="logo"
                      alt="Logo Fanpage ATM Việt Nam" 
                      class="max-h-10 w-auto object-contain"
                      onerror="handleDriveImageError(this)"
                    >
                  </div>
                  <div class="text-white">
                    <div class="text-xs sm:text-sm font-extrabold leading-tight">CÔNG TY TNHH SX TM & DV ATM VIỆT NAM</div>
                    <div class="text-[11px] text-amber-200">Phân phối & Thi công Sàn gỗ Châu Âu Đà Nẵng</div>
                  </div>
                </div>
              </div>

              <div class="p-3 space-y-2 text-xs text-slate-700">
                <div class="flex items-center gap-2">
                  <i class="fa-solid fa-location-dot text-atmRed w-4 text-center"></i>
                  <span>119 Nguyễn Công Triều, Phường An Khê, TP Đà Nẵng</span>
                </div>
                <div class="flex items-center gap-2">
                  <i class="fa-solid fa-phone text-atmBlue w-4 text-center"></i>
                  <span class="font-bold">0936.434.266 - 0905.513.828</span>
                </div>
                <div class="flex items-center gap-2">
                  <i class="fa-brands fa-facebook text-[#1877F2] w-4 text-center"></i>
                  <a href="https://www.facebook.com/profile.php?id=100064390740558" target="_blank" rel="noopener noreferrer" class="text-[#1877F2] font-semibold hover:underline break-all">
                    facebook.com/profile.php?id=100064390740558
                  </a>
                </div>
              </div>
            </div>
          </div>

          <div class="mt-3 pt-3 border-t border-slate-100">
            <a 
              href="https://www.facebook.com/profile.php?id=100064390740558" 
              target="_blank" 
              rel="noopener noreferrer" 
              class="w-full py-2 px-3 rounded bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold flex items-center justify-center gap-2 transition"
            >
              <i class="fa-brands fa-facebook-messenger text-sm"></i>
              <span>NHẮN TIN TRỰC TIẾP QUA FANPAGE</span>
            </a>
          </div>
        </div>

      </div>
    </div>
  </section>

  <!-- =====================================================================
       FLATSOME FOOTER (Chân trang đầy đủ thông tin pháp lý, danh mục & liên hệ)
       ===================================================================== -->
  <footer class="bg-atmDark text-slate-200 pt-10 pb-20 md:pb-8 w-full border-t-4 border-atmRed">
    <div class="container-1500">
      <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-white/10">
        
        <!-- Cột 1: Thông tin công ty (5/12) -->
        <div class="lg:col-span-5 space-y-3">
          <div class="flex items-center gap-3">
            <div class="w-10 h-10 rounded bg-white p-1 flex items-center justify-center shrink-0">
              <img 
                src="https://drive.google.com/thumbnail?id=15EXVtS8kteXe5ITBqmin2tkRMdHbW7mM&sz=w200" 
                data-drive-id="15EXVtS8kteXe5ITBqmin2tkRMdHbW7mM"
                data-fallback-type="logo"
                alt="Logo ATM Việt Nam" 
                class="max-h-8 w-auto object-contain"
                onerror="handleDriveImageError(this)"
              >
            </div>
            <div>
              <h3 class="text-sm sm:text-base font-extrabold text-white">CÔNG TY TNHH SẢN XUẤT TM & DV ATM VIỆT NAM</h3>
              <p class="text-[11px] text-amber-300">Website chính thức: atmvietnam.com</p>
            </div>
          </div>
          <ul class="space-y-2 text-xs text-slate-300 pt-1">
            <li><i class="fa-solid fa-building text-amber-400 w-5"></i><strong>Mã số thuế:</strong> 0402061852</li>
            <li><i class="fa-solid fa-location-dot text-amber-400 w-5"></i><strong>Địa chỉ:</strong> 119 Nguyễn Công Triều, Phường An Khê, TP Đà Nẵng</li>
            <li><i class="fa-solid fa-phone-volume text-amber-400 w-5"></i><strong>Hotline:</strong> <a href="tel:0936434266" class="text-white font-bold hover:underline">0936.434.266</a> - <a href="tel:0905513828" class="text-white font-bold hover:underline">0905.513.828</a></li>
            <li><i class="fa-solid fa-globe text-amber-400 w-5"></i><strong>Website:</strong> <a href="https://atmvietnam.com" class="text-white hover:underline">https://atmvietnam.com</a></li>
            <li><i class="fa-solid fa-map text-amber-400 w-5"></i><strong>Google Map:</strong> <a href="https://share.google/DiBzuBTxcYm8UBxZO" target="_blank" rel="noopener noreferrer" class="text-amber-300 hover:underline">Xem vị trí trên Google Maps</a></li>
          </ul>
        </div>

        <!-- Cột 2: Danh mục sản phẩm (4/12) -->
        <div class="lg:col-span-4 space-y-2.5">
          <h4 class="text-xs sm:text-sm font-extrabold uppercase text-white tracking-wider border-b border-white/15 pb-2">
            DANH MỤC SẢN PHẨM CHÂU ÂU
          </h4>
          <ul class="grid grid-cols-1 sm:grid-cols-2 gap-1.5 text-xs text-slate-300">
            <li><a href="#san-pham-kaindl" class="hover:text-amber-300">› Sàn gỗ Kaindl Floorganic XPT</a></li>
            <li><a href="#san-pham-kaindl" class="hover:text-amber-300">› KAINDL AQUApro 12mm</a></li>
            <li><a href="#san-pham-kaindl" class="hover:text-amber-300">› KAINDL AQUApro 8mm</a></li>
            <li><a href="#san-pham-kaindl" class="hover:text-amber-300">› Sàn gỗ Kaindl Fishbone</a></li>
            <li><a href="#san-pham-kronopol" class="hover:text-amber-300">› Kronopol Symfonia 12mm</a></li>
            <li><a href="#san-pham-kronopol" class="hover:text-amber-300">› Kronopol Aqua Fiori 10mm</a></li>
            <li><a href="#san-pham-kronopol" class="hover:text-amber-300">› Kronopol Infinity 10mm</a></li>
            <li><a href="#phu-kien" class="hover:text-amber-300">› Phụ kiện Châu Âu Arbiton</a></li>
          </ul>
        </div>

        <!-- Cột 3: Chính sách & Kết nối (3/12) -->
        <div class="lg:col-span-3 space-y-2.5">
          <h4 class="text-xs sm:text-sm font-extrabold uppercase text-white tracking-wider border-b border-white/15 pb-2">
            CAM KẾT DỊCH VỤ
          </h4>
          <ul class="space-y-1.5 text-xs text-slate-300">
            <li>✓ Nhập khẩu chính ngạch Áo & Ba Lan</li>
            <li>✓ Bảo hành sản phẩm lên tới 30 năm</li>
            <li>✓ Bảo hành ngập nước chính hãng</li>
            <li>✓ Khảo sát & mang mẫu tận nơi tại Đà Nẵng</li>
          </ul>
          <div class="pt-2 flex items-center gap-2">
            <a href="https://www.facebook.com/profile.php?id=100064390740558" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded bg-[#1877F2] text-white text-xs font-bold hover:opacity-90">
              <i class="fa-brands fa-facebook-f mr-1"></i>Fanpage
            </a>
            <a href="https://zalo.me/0936434266" target="_blank" rel="noopener noreferrer" class="px-3 py-1.5 rounded bg-sky-500 text-white text-xs font-bold hover:opacity-90">
              Chat Zalo
            </a>
          </div>
        </div>

      </div>

      <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
        <div>© Bản quyền thuộc về <strong>CÔNG TY TNHH SẢN XUẤT TM & DV ATM VIỆT NAM</strong> (atmvietnam.com).</div>
        <div>119 Nguyễn Công Triều, Phường An Khê, TP Đà Nẵng</div>
      </div>
    </div>
  </footer>

  <!-- =====================================================================
       CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
       - Tương thích mượt mà trên cả Máy Tính và Điện Thoại
       ===================================================================== -->
  <div class="fixed left-3 bottom-3 sm:left-4 sm:bottom-5 z-50 flex flex-col gap-2.5">
    
    <!-- Nút Zalo nổi bật -->
    <a 
      href="https://zalo.me/0936434266" 
      target="_blank" 
      rel="noopener noreferrer"
      class="flex items-center gap-2 bg-[#0068FF] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
      title="Chat Zalo 0936.434.266"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] font-black text-[10px] flex items-center justify-center shrink-0">Zalo</span>
      <span class="text-xs font-bold pr-1">Chat Zalo</span>
    </a>

    <!-- Nút Facebook Fanpage nổi bật -->
    <a 
      href="https://www.facebook.com/profile.php?id=100064390740558" 
      target="_blank" 
      rel="noopener noreferrer"
      class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white px-3 py-2 rounded-full shadow-lg transition transform hover:scale-105"
      title="Fanpage ATM Việt Nam"
    >
      <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0">
        <i class="fa-brands fa-facebook-f text-xs"></i>
      </span>
      <span class="text-xs font-bold pr-1">Facebook</span>
    </a>

    <!-- Nút Hotline 1 nổi bật -->
    <a 
      href="tel:0936434266" 
      class="pulse-btn flex items-center gap-2 bg-atmRed hover:bg-red-700 text-white px-3 py-2 rounded-full shadow-lg transition"
      title="Gọi ngay 0936.434.266"
    >
      <span class="w-6 h-6 rounded-full bg-white text-atmRed flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone-volume text-xs"></i>
      </span>
      <span class="text-xs font-extrabold pr-1">0936.434.266</span>
    </a>

    <!-- Nút Hotline 2 nổi bật -->
    <a 
      href="tel:0905513828" 
      class="flex items-center gap-2 bg-atmBlue hover:bg-atmDark text-white px-3 py-2 rounded-full shadow-lg transition"
      title="Gọi ngay 0905.513.828"
    >
      <span class="w-6 h-6 rounded-full bg-white text-atmBlue flex items-center justify-center shrink-0">
        <i class="fa-solid fa-phone text-xs"></i>
      </span>
      <span class="text-xs font-extrabold pr-1">0905.513.828</span>
    </a>
  </div>

  <!-- =====================================================================
       JAVASCRIPT ĐIỀU KHIỂN SLIDER, LỌC DANH MỤC, FORM & FALLBACK ẢNH DRIVE
       ===================================================================== -->
  <script>
    /* 1. Xử lý dự phòng thông minh cho ảnh Google Drive (thử lần lượt các endpoint trực tiếp của Google Drive) */
    function handleDriveImageError(imgEl) {
      const fileId = imgEl.getAttribute('data-drive-id');
      const fallbackType = imgEl.getAttribute('data-fallback-type') || 'wood';
      const step = parseInt(imgEl.getAttribute('data-retry-step') || '0', 10);

      if (fileId && step === 0) {
        imgEl.setAttribute('data-retry-step', '1');
        imgEl.src = 'https://lh3.googleusercontent.com/d/' + fileId + '=w1000';
        return;
      }
      if (fileId && step === 1) {
        imgEl.setAttribute('data-retry-step', '2');
        imgEl.src = 'https://drive.google.com/uc?export=view&id=' + fileId;
        return;
      }

      // Dự phòng SVG sắc nét nếu mạng chặn Google Drive
      imgEl.onerror = null;
      if (fallbackType === 'logo') {
        const svgLogo = `<svg xmlns="http://www.w3.org/2000/svg" width="120" height="120" viewBox="0 0 120 120">
          <rect width="120" height="120" rx="18" fill="#0F4C81"/>
          <text x="60" y="62" text-anchor="middle" fill="#FFFFFF" font-family="Inter, sans-serif" font-weight="900" font-size="34">ATM</text>
          <text x="60" y="88" text-anchor="middle" fill="#FCD34D" font-family="Inter, sans-serif" font-weight="700" font-size="14">VIET NAM</text>
        </svg>`;
        imgEl.src = 'data:image/svg+xml;utf8,' + encodeURIComponent(svgLogo);
      } else {
        const label = (imgEl.getAttribute('alt') || 'Sàn Gỗ Châu Âu ATM Việt Nam').replace(/[<>&"']/g, '');
        const svgWood = `<svg xmlns="http://www.w3.org/2000/svg" width="800" height="600" viewBox="0 0 800 600">
          <defs>
            <linearGradient id="woodGrad" x1="0" y1="0" x2="1" y2="1">
              <stop offset="0%" stop-color="#C89D70"/>
              <stop offset="50%" stop-color="#B07D4F"/>
              <stop offset="100%" stop-color="#8F5E36"/>
            </linearGradient>
          </defs>
          <rect width="800" height="600" fill="url(#woodGrad)"/>
          <line x1="0" y1="150" x2="800" y2="150" stroke="#784B27" stroke-width="2" opacity="0.45"/>
          <line x1="0" y1="300" x2="800" y2="300" stroke="#784B27" stroke-width="2" opacity="0.45"/>
          <line x1="0" y1="450" x2="800" y2="450" stroke="#784B27" stroke-width="2" opacity="0.45"/>
          <rect x="40" y="220" width="720" height="160" rx="12" fill="#0F4C81" opacity="0.88"/>
          <text x="400" y="285" text-anchor="middle" fill="#FCD34D" font-family="Inter, sans-serif" font-weight="800" font-size="22">ATM VIỆT NAM - SÀN GỖ CHÂU ÂU</text>
          <text x="400" y="325" text-anchor="middle" fill="#FFFFFF" font-family="Inter, sans-serif" font-weight="600" font-size="18">${label}</text>
        </svg>`;
        imgEl.src = 'data:image/svg+xml;utf8,' + encodeURIComponent(svgWood);
      }
    }

    /* 2. Tự động trượt 2 Banner kích thước bằng nhau */
    let currentSlideIndex = 0;
    const slides = document.querySelectorAll('.hero-slide');
    const dots = document.querySelectorAll('.slider-dot');
    let slideInterval = null;

    function showSlide(index) {
      if (!slides.length) return;
      currentSlideIndex = (index + slides.length) % slides.length;
      slides.forEach((slide, i) => {
        if (i === currentSlideIndex) {
          slide.classList.remove('opacity-0', 'z-0', 'pointer-events-none');
          slide.classList.add('opacity-100', 'z-10');
        } else {
          slide.classList.remove('opacity-100', 'z-10');
          slide.classList.add('opacity-0', 'z-0', 'pointer-events-none');
        }
      });
      dots.forEach((dot, i) => {
        if (i === currentSlideIndex) {
          dot.className = 'slider-dot w-6 h-2 rounded-full bg-amber-400 transition-all';
        } else {
          dot.className = 'slider-dot w-2.5 h-2 rounded-full bg-white/60 transition-all';
        }
      });
    }

    function changeSlide(step) {
      showSlide(currentSlideIndex + step);
      resetSlideTimer();
    }

    function goToSlide(index) {
      showSlide(index);
      resetSlideTimer();
    }

    function resetSlideTimer() {
      if (slideInterval) clearInterval(slideInterval);
      slideInterval = setInterval(() => {
        showSlide(currentSlideIndex + 1);
      }, 5000);
    }

    /* 3. Lọc sản phẩm theo Danh mục hoặc Thanh tìm kiếm */
    function filterByCategory(categorySlug, btnEl) {
      const cards = document.querySelectorAll('.product-card');
      cards.forEach(card => {
        const cardCat = card.getAttribute('data-category');
        if (categorySlug === 'all' || cardCat === categorySlug) {
          card.style.display = 'flex';
        } else {
          card.style.display = 'none';
        }
      });

      if (btnEl) {
        const allBtns = document.querySelectorAll('.cat-filter-btn');
        allBtns.forEach(b => {
          b.classList.remove('bg-atmBlue', 'text-white', 'border-atmBlue');
          b.classList.add('bg-white', 'text-slate-700', 'border-slate-300');
        });
        btnEl.classList.remove('bg-white', 'text-slate-700', 'border-slate-300');
        btnEl.classList.add('bg-atmBlue', 'text-white', 'border-atmBlue');
      }
    }

    function scrollToCategory(categorySlug) {
      filterByCategory(categorySlug, null);
      const target = document.getElementById('san-pham-kaindl');
      if (target) {
        target.scrollIntoView({ behavior: 'smooth' });
      }
    }

    function filterProductsBySearch(keyword) {
      const q = (keyword || '').toLowerCase().trim();
      const cards = document.querySelectorAll('.product-card');
      cards.forEach(card => {
        const text = card.innerText.toLowerCase();
        card.style.display = (!q || text.includes(q)) ? 'flex' : 'none';
      });
    }

    /* 4. Chọn sản phẩm điền sẵn vào Form Báo Giá */
    function selectProductForQuote(productName) {
      const noteInput = document.getElementById('quoteNote');
      if (noteInput) {
        noteInput.value = 'Tôi muốn nhận báo giá & xem mẫu thực tế mã: ' + productName;
      }
    }

    /* 5. Xử lý gửi Form Báo Giá (Không dùng alert) */
    function submitQuoteForm(event) {
      event.preventDefault();
      const name = document.getElementById('quoteName').value.trim();
      const phone = document.getElementById('quotePhone').value.trim();
      const product = document.getElementById('quoteProduct').value;
      const successBox = document.getElementById('quoteSuccessBox');
      const successText = document.getElementById('quoteSuccessText');

      if (successBox && successText) {
        successText.textContent = `Cảm ơn ${name} (${phone})! Yêu cầu báo giá "${product}" đã được gửi tới Hotline 0936.434.266 - 0905.513.828.`;
        successBox.classList.remove('hidden');
        document.getElementById('quoteForm').reset();
      }
    }

    /* 6. Đóng/Mở Menu trên Điện thoại */
    function toggleMobileMenu() {
      const drawer = document.getElementById('mobileMenuDrawer');
      if (drawer) {
        drawer.classList.toggle('hidden');
      }
    }

    window.onload = function () {
      resetSlideTimer();
    };
  </script>
</body>
</html>
