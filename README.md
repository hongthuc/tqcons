<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CÔNG TY TNHH XÂY DỰNG TQCONS - Thiết Kế &amp; Thi Công Xây Dựng Đà Nẵng | tqcons.com</title>
    <meta name="description" content="CÔNG TY TNHH XÂY DỰNG TQCONS chuyên thiết kế kiến trúc, thi công phần thô, thi công hoàn thiện và nội thất trọn gói tại Đà Nẵng. Địa chỉ: 170 Lê Sỹ, Phường Hòa Xuân, TP Đà Nẵng. Hotline: 0948.259.979.">

    <!-- Ảnh thumbnail là ảnh logo trang web khi chia sẻ link (Zalo, Facebook, Messenger) -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://tqcons.com/">
    <meta property="og:site_name" content="CÔNG TY TNHH XÂY DỰNG TQCONS">
    <meta property="og:title" content="CÔNG TY TNHH XÂY DỰNG TQCONS - Thiết Kế &amp; Thi Công Trọn Gói Đà Nẵng">
    <meta property="og:description" content="Thiết kế kiến trúc - Thi công phần thô - Thi công hoàn thiện - Nội thất nhà phố, biệt thự, khách sạn, căn hộ tại Đà Nẵng. Hotline: 0948.259.979.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/1qUuDypH8KEDmMR92is2nr8m9bxBwtaER=w800">
    <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/1qUuDypH8KEDmMR92is2nr8m9bxBwtaER=w800">
    <meta property="og:image:width" content="800">
    <meta property="og:image:height" content="800">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH XÂY DỰNG TQCONS | tqcons.com">
    <meta name="twitter:description" content="Chuyên thiết kế &amp; thi công xây dựng trọn gói uy tín tại Đà Nẵng - Hotline: 0948.259.979.">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/1qUuDypH8KEDmMR92is2nr8m9bxBwtaER=w800">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/1qUuDypH8KEDmMR92is2nr8m9bxBwtaER=w200">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>

    <!-- Cấu hình màu sắc theo nhận diện thương hiệu & Flatsome Theme Options -->
    <style>
        :root {
            --brand-primary: #0E3A66;      /* Xanh navy kiến trúc chủ đạo theo tông logo */
            --brand-primary-dark: #092645; /* Xanh đậm footer & hover */
            --brand-accent: #D97706;       /* Vàng cam xây dựng nhấn mạnh */
            --brand-accent-hover: #B45309;
            --brand-bg-soft: #F4F7FA;
            --brand-text: #1F2937;
            --brand-muted: #526071;
            --brand-border: #E2E8F0;
        }

        *, *::before, *::after {
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
            max-width: 100%;
            overflow-x: hidden;
        }

        body {
            font-family: 'Inter', -apple-system, BlinkMacSystemFont, sans-serif;
            color: var(--brand-text);
            background-color: #FFFFFF;
            margin: 0;
            padding: 0;
            max-width: 100%;
            overflow-x: hidden;
            -webkit-font-smoothing: antialiased;
        }

        /* Khung chứa chuẩn Flatsome: 95% chiều ngang màn hình trên máy tính, không tràn viền */
        .site-container {
            width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        @media (min-width: 640px) {
            .site-container {
                padding-left: 18px;
                padding-right: 18px;
            }
        }

        @media (min-width: 1024px) {
            .site-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Tiêu đề section kiểu Flatsome đơn giản, dễ dựng lại trên UX Builder */
        .section-heading {
            position: relative;
            display: inline-block;
            color: var(--brand-primary);
            padding-bottom: 10px;
        }

        .section-heading::after {
            content: "";
            position: absolute;
            left: 50%;
            bottom: 0;
            transform: translateX(-50%);
            width: 56px;
            height: 3px;
            background-color: var(--brand-accent);
            border-radius: 999px;
        }

        .section-heading-left::after {
            left: 0;
            transform: none;
        }

        /* Menu máy tính: 1 hàng gọn đẹp, chữ nhỏ vừa, tuyệt đối không xuống dòng */
        .desktop-nav-link {
            white-space: nowrap;
            font-size: 12px;
            font-weight: 600;
            color: var(--brand-text);
            padding: 8px 6px;
            transition: color 0.2s ease;
            display: inline-flex;
            align-items: center;
            gap: 4px;
        }

        @media (min-width: 1280px) {
            .desktop-nav-link {
                font-size: 13px;
                padding: 8px 9px;
            }
        }

        .desktop-nav-link:hover,
        .desktop-nav-link.active {
            color: var(--brand-accent);
        }

        /* Dropdown menu Flatsome */
        .nav-dropdown-parent {
            position: relative;
        }

        .nav-dropdown-menu {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 220px;
            background: #FFFFFF;
            border: 1px solid var(--brand-border);
            border-top: 2px solid var(--brand-accent);
            border-radius: 0 0 8px 8px;
            box-shadow: 0 10px 25px rgba(14, 58, 102, 0.12);
            opacity: 0;
            visibility: hidden;
            transform: translateY(6px);
            transition: all 0.2s ease;
            z-index: 60;
        }

        .nav-dropdown-parent:hover .nav-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Banner slider: 2 ảnh kích thước bằng nhau tuyệt đối, chữ nằm gọn an toàn trong khung */
        .banner-viewport {
            position: relative;
            width: 100%;
            overflow: hidden;
            background-color: var(--brand-primary-dark);
        }

        .banner-track {
            display: flex;
            align-items: stretch; /* Đảm bảo 2 slide luôn có chiều cao bằng nhau tuyệt đối */
            transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
            width: 100%;
        }

        .banner-slide {
            min-width: 100%;
            width: 100%;
            flex-shrink: 0;
            position: relative;
            display: flex;
            align-items: center;
            overflow: hidden;
        }

        /* Tab danh mục trang chủ nhỏ gọn, không vỡ dòng trên máy tính */
        .cat-tab-btn {
            white-space: nowrap;
            font-size: 12px;
            font-weight: 600;
            padding: 7px 14px;
            border-radius: 6px;
            border: 1px solid var(--brand-border);
            background-color: #FFFFFF;
            color: var(--brand-text);
            transition: all 0.2s ease;
            cursor: pointer;
        }

        .cat-tab-btn:hover {
            border-color: var(--brand-primary);
            color: var(--brand-primary);
        }

        .cat-tab-btn.active {
            background-color: var(--brand-primary);
            border-color: var(--brand-primary);
            color: #FFFFFF;
        }

        /* Hiệu ứng ảnh sản phẩm / dự án mượt kiểu Flatsome */
        .card-img-wrap {
            overflow: hidden;
            background-color: #E8EEF4;
        }

        .card-img-wrap img {
            transition: transform 0.45s ease;
        }

        .project-card:hover .card-img-wrap img {
            transform: scale(1.05);
        }

        /* Nút liên hệ nổi có hiệu ứng nhịp nhẹ */
        @keyframes pulseRing {
            0% {
                box-shadow: 0 0 0 0 rgba(217, 119, 6, 0.45);
            }
            70% {
                box-shadow: 0 0 0 11px rgba(217, 119, 6, 0);
            }
            100% {
                box-shadow: 0 0 0 0 rgba(217, 119, 6, 0);
            }
        }

        .hotline-pulse {
            animation: pulseRing 2.2s infinite;
        }

        /* Đệm đáy trên điện thoại để thanh liên hệ nổi không che footer */
        @media (max-width: 767px) {
            body {
                padding-bottom: 62px;
            }
        }
    </style>
</head>
<body class="bg-white text-gray-800">

    <!-- =========================================================
         FLATSOME SECTION 1: TOP BAR (Thông tin liên hệ gọn nhẹ)
         ========================================================= -->
    <div class="w-full text-white text-[11px] sm:text-xs py-2" style="background-color: var(--brand-primary-dark);">
        <div class="site-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-location-dot text-amber-400"></i>
                    <span>170 Lê Sỹ, Phường Hòa Xuân, TP Đà Nẵng</span>
                </span>
                <span class="hidden sm:inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-globe text-amber-400"></i>
                    <span>tqcons.com</span>
                </span>
            </div>
            <div class="flex items-center gap-4">
                <a href="tel:0948259979" class="inline-flex items-center gap-1.5 hover:text-amber-300 transition font-medium">
                    <i class="fa-solid fa-phone text-amber-400"></i>
                    <span>0948.259.979</span>
                </a>
                <a href="mailto:info@tqcons.com" class="hidden md:inline-flex items-center gap-1.5 hover:text-amber-300 transition">
                    <i class="fa-solid fa-envelope text-amber-400"></i>
                    <span>info@tqcons.com</span>
                </a>
            </div>
        </div>
    </div>

    <!-- =========================================================
         FLATSOME SECTION 2: HEADER (Logo nhỏ gọn + Menu 1 hàng, không nút gọi ngay)
         ========================================================= -->
    <header class="sticky top-0 z-50 bg-white border-b border-slate-200 shadow-sm w-full">
        <div class="site-container flex items-center justify-between h-14 sm:h-16 gap-3">
            <!-- Logo chỉnh gọn nhỏ lại -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 py-1">
                <img
                    src="https://lh3.googleusercontent.com/d/1qUuDypH8KEDmMR92is2nr8m9bxBwtaER=w400"
                    alt="Logo CÔNG TY TNHH XÂY DỰNG TQCONS"
                    class="h-9 sm:h-10 lg:h-11 w-auto max-w-[130px] object-contain"
                    onerror="handleDriveImgError(this, '1qUuDypH8KEDmMR92is2nr8m9bxBwtaER', 400)"
                >
                <div class="leading-tight">
                    <span class="block text-[13px] sm:text-sm font-extrabold tracking-tight" style="color: var(--brand-primary);">TQCONS</span>
                    <span class="block text-[10px] text-slate-500 font-medium">tqcons.com</span>
                </div>
            </a>

            <!-- Menu Desktop: viết liền trên 1 hàng, chữ nhỏ gọn, tuyệt đối không xuống dòng -->
            <nav class="hidden lg:flex items-center justify-end flex-nowrap gap-1 xl:gap-2" aria-label="Menu chính">
                <a href="#trang-chu" class="desktop-nav-link active">Trang chủ</a>
                <a href="#gioi-thieu" class="desktop-nav-link">Giới thiệu</a>

                <!-- Dropdown: Công trình thực tế (theo web mẫu tintruongthinh.com) -->
                <div class="nav-dropdown-parent">
                    <a href="#cong-trinh-thuc-te" class="desktop-nav-link">
                        <span>Công trình thực tế</span>
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                    </a>
                    <div class="nav-dropdown-menu py-1.5">
                        <a href="#cong-trinh-thuc-te" onclick="filterWorks('khach-san')" class="block px-4 py-2 text-xs text-slate-700 hover:bg-slate-50 hover:text-amber-600 font-medium">Khách sạn – Căn hộ – Phòng trọ</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterWorks('biet-thu')" class="block px-4 py-2 text-xs text-slate-700 hover:bg-slate-50 hover:text-amber-600 font-medium">Biệt thự</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterWorks('nha-pho')" class="block px-4 py-2 text-xs text-slate-700 hover:bg-slate-50 hover:text-amber-600 font-medium">Nhà phố</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterWorks('van-phong')" class="block px-4 py-2 text-xs text-slate-700 hover:bg-slate-50 hover:text-amber-600 font-medium">Văn phòng</a>
                    </div>
                </div>

                <!-- Dropdown: Lĩnh vực hoạt động -->
                <div class="nav-dropdown-parent">
                    <a href="#linh-vuc-hoat-dong" class="desktop-nav-link">
                        <span>Lĩnh vực hoạt động</span>
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                    </a>
                    <div class="nav-dropdown-menu py-1.5">
                        <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs text-slate-700 hover:bg-slate-50 hover:text-amber-600 font-medium">Thiết kế Kiến trúc – Nội thất</a>
                        <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs text-slate-700 hover:bg-slate-50 hover:text-amber-600 font-medium">Thi công phần thô</a>
                        <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs text-slate-700 hover:bg-slate-50 hover:text-amber-600 font-medium">Thi công hoàn thiện</a>
                        <a href="#linh-vuc-hoat-dong" class="block px-4 py-2 text-xs text-slate-700 hover:bg-slate-50 hover:text-amber-600 font-medium">Thi công nội thất</a>
                    </div>
                </div>

                <a href="#du-an-da-nang" class="desktop-nav-link">Dự án Đà Nẵng</a>

                <!-- Dropdown: Mẫu thiết kế -->
                <div class="nav-dropdown-parent">
                    <a href="#cong-trinh-thuc-te" class="desktop-nav-link">
                        <span>Mẫu thiết kế</span>
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                    </a>
                    <div class="nav-dropdown-menu py-1.5">
                        <a href="#cong-trinh-thuc-te" onclick="filterWorks('nha-pho')" class="block px-4 py-2 text-xs text-slate-700 hover:bg-slate-50 hover:text-amber-600 font-medium">Mẫu thiết kế nhà phố</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterWorks('biet-thu')" class="block px-4 py-2 text-xs text-slate-700 hover:bg-slate-50 hover:text-amber-600 font-medium">Mẫu thiết kế biệt thự</a>
                        <a href="#cong-trinh-thuc-te" onclick="filterWorks('khach-san')" class="block px-4 py-2 text-xs text-slate-700 hover:bg-slate-50 hover:text-amber-600 font-medium">Mẫu thiết kế nội thất</a>
                    </div>
                </div>

                <!-- Dropdown: Báo giá -->
                <div class="nav-dropdown-parent">
                    <a href="#bao-gia" class="desktop-nav-link">
                        <span>Báo giá</span>
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                    </a>
                    <div class="nav-dropdown-menu py-1.5">
                        <a href="#bao-gia" class="block px-4 py-2 text-xs text-slate-700 hover:bg-slate-50 hover:text-amber-600 font-medium">Báo giá thiết kế kiến trúc</a>
                        <a href="#bao-gia" class="block px-4 py-2 text-xs text-slate-700 hover:bg-slate-50 hover:text-amber-600 font-medium">Báo giá thi công phần thô</a>
                        <a href="#bao-gia" class="block px-4 py-2 text-xs text-slate-700 hover:bg-slate-50 hover:text-amber-600 font-medium">Báo giá thi công hoàn thiện</a>
                        <a href="#bao-gia" class="block px-4 py-2 text-xs text-slate-700 hover:bg-slate-50 hover:text-amber-600 font-medium">Báo giá thi công trọn gói</a>
                    </div>
                </div>

                <a href="#tin-tuc" class="desktop-nav-link">Tin tức</a>
                <a href="#lien-he" class="desktop-nav-link">Liên hệ</a>
            </nav>

            <!-- Nút Menu Mobile (không để nút Gọi ngay trên header) -->
            <button
                id="mobileMenuBtn"
                type="button"
                aria-label="Mở menu điều hướng"
                class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-slate-700 hover:bg-slate-50"
            >
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Mobile Drawer Menu -->
        <div id="mobileMenu" class="hidden lg:hidden bg-white border-t border-slate-200 w-full">
            <div class="site-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-medium">
                <a href="#trang-chu" onclick="closeMobileMenu()" class="py-2.5 text-slate-800 hover:text-amber-600">Trang chủ</a>
                <a href="#gioi-thieu" onclick="closeMobileMenu()" class="py-2.5 text-slate-800 hover:text-amber-600">Giới thiệu</a>
                <a href="#linh-vuc-hoat-dong" onclick="closeMobileMenu()" class="py-2.5 text-slate-800 hover:text-amber-600">Lĩnh vực hoạt động</a>
                <a href="#cong-trinh-thuc-te" onclick="closeMobileMenu()" class="py-2.5 text-slate-800 hover:text-amber-600">Công trình thực tế</a>
                <a href="#du-an-da-nang" onclick="closeMobileMenu()" class="py-2.5 text-slate-800 hover:text-amber-600">Dự án Đà Nẵng</a>
                <a href="#bao-gia" onclick="closeMobileMenu()" class="py-2.5 text-slate-800 hover:text-amber-600">Báo giá thiết kế &amp; thi công</a>
                <a href="#tu-van-bao-gia" onclick="closeMobileMenu()" class="py-2.5 text-slate-800 hover:text-amber-600">Yêu cầu báo giá</a>
                <a href="#tin-tuc" onclick="closeMobileMenu()" class="py-2.5 text-slate-800 hover:text-amber-600">Tin tức &amp; Bài viết</a>
                <a href="#doi-tac" onclick="closeMobileMenu()" class="py-2.5 text-slate-800 hover:text-amber-600">Đối tác</a>
                <a href="#lien-he" onclick="closeMobileMenu()" class="py-2.5 text-slate-800 hover:text-amber-600">Liên hệ &amp; Bản đồ</a>
            </div>
        </div>
    </header>

    <!-- =========================================================
         FLATSOME SECTION 3: 2 BANNER TỰ TRƯỢT KÍCH THƯỚC BẰNG NHAU
         Chữ nằm gọn hoàn toàn bên trong, cách xa viền ảnh trên cả Mobile & Desktop
         ========================================================= -->
    <section id="trang-chu" class="w-full bg-slate-100 py-3 sm:py-4">
        <div class="site-container">
            <div class="banner-viewport rounded-xl shadow-md" id="heroSlider">
                <div class="banner-track" id="bannerTrack">

                    <!-- BANNER 1 -->
                    <div class="banner-slide">
                        <!-- Ảnh nền công trình thực tế -->
                        <img
                            src="https://lh3.googleusercontent.com/d/13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz=w1400"
                            alt="Thi công xây dựng trọn gói TQCONS Đà Nẵng"
                            class="absolute inset-0 w-full h-full object-cover object-center"
                            onerror="handleDriveImgError(this, '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz', 1400)"
                        >
                        <!-- Lớp phủ màu đồng bộ thương hiệu giúp chữ nổi bật và sắc nét -->
                        <div class="absolute inset-0" style="background: linear-gradient(95deg, rgba(9, 38, 69, 0.90) 0%, rgba(14, 58, 102, 0.78) 55%, rgba(9, 38, 69, 0.55) 100%);"></div>

                        <!-- Vùng nội dung an toàn: cách xa 4 viền banner trên cả điện thoại và máy tính -->
                        <div class="relative z-10 w-full px-10 py-10 sm:px-16 sm:py-14 md:px-20 md:py-16 lg:px-24 lg:py-20">
                            <div class="max-w-2xl">
                                <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-amber-400 mb-2 sm:mb-3">
                                    CÔNG TY TNHH XÂY DỰNG TQCONS — ĐÀ NẴNG
                                </p>
                                <h1 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold text-white leading-snug mb-3 sm:mb-4">
                                    THIẾT KẾ &amp; THI CÔNG XÂY DỰNG TRỌN GÓI CHUYÊN NGHIỆP
                                </h1>
                                <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed mb-5 sm:mb-7">
                                    Chuyên xây dựng Nhà phố, Biệt thự, Khách sạn, Căn hộ và Văn phòng tại Đà Nẵng. Cam kết An toàn – Chất lượng – Đúng tiến độ – Chi phí minh bạch.
                                </p>
                                <div class="flex flex-wrap items-center gap-3">
                                    <a href="#tu-van-bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg text-xs sm:text-sm font-semibold text-white transition shadow" style="background-color: var(--brand-accent);">
                                        Nhận báo giá miễn phí
                                    </a>
                                    <a href="#cong-trinh-thuc-te" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg text-xs sm:text-sm font-semibold text-white border border-white/70 hover:bg-white/15 transition">
                                        Xem công trình thực tế
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2 -->
                    <div class="banner-slide">
                        <!-- Ảnh nền dự án Đà Nẵng -->
                        <img
                            src="https://lh3.googleusercontent.com/d/157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT=w1400"
                            alt="Dự án xây dựng tiêu biểu tại Đà Nẵng - TQCONS"
                            class="absolute inset-0 w-full h-full object-cover object-center"
                            onerror="handleDriveImgError(this, '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT', 1400)"
                        >
                        <div class="absolute inset-0" style="background: linear-gradient(95deg, rgba(9, 38, 69, 0.90) 0%, rgba(14, 58, 102, 0.78) 55%, rgba(9, 38, 69, 0.55) 100%);"></div>

                        <!-- Vùng nội dung an toàn: cấu trúc và khoảng cách viền bằng chính xác Banner 1 -->
                        <div class="relative z-10 w-full px-10 py-10 sm:px-16 sm:py-14 md:px-20 md:py-16 lg:px-24 lg:py-20">
                            <div class="max-w-2xl">
                                <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-amber-400 mb-2 sm:mb-3">
                                    KIẾN TẠO KHÔNG GIAN SỐNG BỀN VỮNG — TQCONS.COM
                                </p>
                                <h2 class="text-lg sm:text-2xl md:text-3xl lg:text-4xl font-extrabold text-white leading-snug mb-3 sm:mb-4">
                                    GIẢI PHÁP THI CÔNG PHẦN THÔ &amp; HOÀN THIỆN NỘI THẤT
                                </h2>
                                <p class="text-xs sm:text-sm md:text-base text-slate-100 leading-relaxed mb-5 sm:mb-7">
                                    Đội ngũ kiến trúc sư và kỹ sư giàu kinh nghiệm trực tiếp giám sát tại công trình. Bảo hành kết cấu dài hạn, hỗ trợ tư vấn 24/7 tại 170 Lê Sỹ, Hòa Xuân, Đà Nẵng.
                                </p>
                                <div class="flex flex-wrap items-center gap-3">
                                    <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg text-xs sm:text-sm font-semibold text-white transition shadow" style="background-color: var(--brand-accent);">
                                        Khám phá dự án Đà Nẵng
                                    </a>
                                    <a href="#bao-gia" class="inline-flex items-center justify-center px-5 py-2.5 rounded-lg text-xs sm:text-sm font-semibold text-white border border-white/70 hover:bg-white/15 transition">
                                        Xem bảng báo giá
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút điều hướng slider trái/phải gọn sát mép ngoài vùng chữ -->
                <button
                    type="button"
                    id="prevBanner"
                    aria-label="Banner trước"
                    class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition"
                >
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button
                    type="button"
                    id="nextBanner"
                    aria-label="Banner tiếp theo"
                    class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-9 sm:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center transition"
                >
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Chấm chỉ báo 2 banner -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToSlide(0)" class="banner-dot w-6 h-2 rounded-full bg-amber-400 transition-all" aria-label="Xem banner 1"></button>
                    <button type="button" onclick="goToSlide(1)" class="banner-dot w-2.5 h-2 rounded-full bg-white/55 transition-all" aria-label="Xem banner 2"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 4: DỊCH VỤ TIÊU BIỂU / LĨNH VỰC HOẠT ĐỘNG
         (Đồng bộ danh mục sản phẩm/dịch vụ từ web mẫu tintruongthinh.com)
         ========================================================= -->
    <section id="linh-vuc-hoat-dong" class="py-10 sm:py-14 bg-white">
        <div class="site-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="section-heading text-lg sm:text-2xl font-bold uppercase tracking-tight">
                    Lĩnh Vực Hoạt Động &amp; Dịch Vụ Tiêu Biểu
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    TQCONS cung cấp giải pháp trọn gói từ tư vấn thiết kế kiến trúc đến thi công phần thô, hoàn thiện và nội thất chuẩn kỹ thuật.
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <a href="#tu-van-bao-gia" class="group bg-white border border-slate-200 rounded-xl p-4 sm:p-6 text-center hover:shadow-md hover:border-amber-500 transition flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl flex items-center justify-center mb-3 sm:mb-4 text-white" style="background-color: var(--brand-primary);">
                        <i class="fa-solid fa-compass-drafting text-lg sm:text-xl"></i>
                    </div>
                    <h3 class="text-[13px] sm:text-base font-bold text-slate-800 group-hover:text-amber-600 transition leading-snug">
                        Thiết Kế Kiến Trúc – Nội Thất
                    </h3>
                    <p class="text-[11px] sm:text-xs text-slate-600 mt-2 leading-relaxed">
                        Triển khai hồ sơ kiến trúc, kết cấu, điện nước và phối cảnh 3D tối ưu công năng sử dụng.
                    </p>
                </a>

                <a href="#tu-van-bao-gia" class="group bg-white border border-slate-200 rounded-xl p-4 sm:p-6 text-center hover:shadow-md hover:border-amber-500 transition flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl flex items-center justify-center mb-3 sm:mb-4 text-white" style="background-color: var(--brand-primary);">
                        <i class="fa-solid fa-helmet-safety text-lg sm:text-xl"></i>
                    </div>
                    <h3 class="text-[13px] sm:text-base font-bold text-slate-800 group-hover:text-amber-600 transition leading-snug">
                        Thi Công Phần Thô
                    </h3>
                    <p class="text-[11px] sm:text-xs text-slate-600 mt-2 leading-relaxed">
                        Thi công kết cấu móng, khung bê tông cốt thép, xây tô chuẩn mác vật tư và quy chuẩn kỹ thuật.
                    </p>
                </a>

                <a href="#tu-van-bao-gia" class="group bg-white border border-slate-200 rounded-xl p-4 sm:p-6 text-center hover:shadow-md hover:border-amber-500 transition flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl flex items-center justify-center mb-3 sm:mb-4 text-white" style="background-color: var(--brand-primary);">
                        <i class="fa-solid fa-trowel-bricks text-lg sm:text-xl"></i>
                    </div>
                    <h3 class="text-[13px] sm:text-base font-bold text-slate-800 group-hover:text-amber-600 transition leading-snug">
                        Thi Công Hoàn Thiện
                    </h3>
                    <p class="text-[11px] sm:text-xs text-slate-600 mt-2 leading-relaxed">
                        Ốp lát, sơn nước, chống thấm, lắp đặt cửa, thiết bị điện nước hoàn chỉnh, sắc nét từng chi tiết.
                    </p>
                </a>

                <a href="#tu-van-bao-gia" class="group bg-white border border-slate-200 rounded-xl p-4 sm:p-6 text-center hover:shadow-md hover:border-amber-500 transition flex flex-col items-center">
                    <div class="w-12 h-12 sm:w-14 sm:h-14 rounded-xl flex items-center justify-center mb-3 sm:mb-4 text-white" style="background-color: var(--brand-primary);">
                        <i class="fa-solid fa-couch text-lg sm:text-xl"></i>
                    </div>
                    <h3 class="text-[13px] sm:text-base font-bold text-slate-800 group-hover:text-amber-600 transition leading-snug">
                        Thi Công Nội Thất Trọn Gói
                    </h3>
                    <p class="text-[11px] sm:text-xs text-slate-600 mt-2 leading-relaxed">
                        Sản xuất và lắp đặt nội thất nhà phố, biệt thự, căn hộ, khách sạn, văn phòng bền đẹp hiện đại.
                    </p>
                </a>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 5: GIỚI THIỆU TQCONS & THẾ MẠNH CỦA CHÚNG TÔI
         ========================================================= -->
    <section id="gioi-thieu" class="py-10 sm:py-14" style="background-color: var(--brand-bg-soft);">
        <div class="site-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center mb-10">
                <!-- Cột ảnh giới thiệu thực tế -->
                <div class="lg:col-span-5">
                    <div class="rounded-xl overflow-hidden shadow-md bg-white border border-slate-200">
                        <img
                            src="https://lh3.googleusercontent.com/d/1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR=w1000"
                            alt="Công trình thi công thực tế của CÔNG TY TNHH XÂY DỰNG TQCONS"
                            class="w-full aspect-[4/3] object-cover"
                            onerror="handleDriveImgError(this, '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR', 1000)"
                        >
                    </div>
                </div>

                <!-- Cột nội dung giới thiệu -->
                <div class="lg:col-span-7">
                    <h2 class="section-heading section-heading-left text-lg sm:text-2xl font-bold uppercase mb-4">
                        CÔNG TY TNHH XÂY DỰNG TQCONS
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-3">
                        <strong>CÔNG TY TNHH XÂY DỰNG TQCONS</strong> chuyên Thiết kế – Thi công Xây dựng – Hoàn thiện Nội thất các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê và Văn phòng tại khu vực TP. Đà Nẵng và miền Trung.
                    </p>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-5">
                        Đặt chữ <strong>“TÂM”</strong> và uy tín kỹ thuật lên hàng đầu, mỗi công trình do TQCONS thực hiện đều đảm bảo tiêu chí <strong>AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – CHI PHÍ HỢP LÝ</strong>, giúp khách hàng hoàn toàn an tâm khi bàn giao tổ ấm và dự án đầu tư.
                    </p>

                    <div class="grid grid-cols-2 sm:grid-cols-4 gap-3">
                        <div class="bg-white rounded-lg border border-slate-200 p-3 text-center">
                            <span class="block text-lg sm:text-xl font-extrabold" style="color: var(--brand-primary);">100%</span>
                            <span class="block text-[11px] text-slate-600 mt-0.5">Đúng tiến độ</span>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 p-3 text-center">
                            <span class="block text-lg sm:text-xl font-extrabold" style="color: var(--brand-primary);">5+ Năm</span>
                            <span class="block text-[11px] text-slate-600 mt-0.5">Bảo hành kết cấu</span>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 p-3 text-center">
                            <span class="block text-lg sm:text-xl font-extrabold" style="color: var(--brand-primary);">0đ</span>
                            <span class="block text-[11px] text-slate-600 mt-0.5">Phát sinh vô lý</span>
                        </div>
                        <div class="bg-white rounded-lg border border-slate-200 p-3 text-center">
                            <span class="block text-lg sm:text-xl font-extrabold" style="color: var(--brand-primary);">24/7</span>
                            <span class="block text-[11px] text-slate-600 mt-0.5">Tư vấn miễn phí</span>
                        </div>
                    </div>
                </div>
            </div>

            <!-- 6 Thế mạnh của chúng tôi (theo web mẫu tintruongthinh.com) -->
            <div class="text-center mb-6">
                <h3 class="section-heading text-base sm:text-xl font-bold uppercase">Thế Mạnh Của Chúng Tôi</h3>
            </div>
            <div class="grid grid-cols-2 lg:grid-cols-3 gap-3 sm:gap-5">
                <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5">
                    <div class="w-9 h-9 rounded-lg flex items-center justify-center mb-3 text-amber-600 bg-amber-50">
                        <i class="fa-solid fa-users-gear text-base"></i>
                    </div>
                    <h4 class="text-[13px] sm:text-sm font-bold text-slate-800 mb-1.5 leading-snug">Đội ngũ KTS &amp; Kỹ sư chuyên nghiệp</h4>
                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư, tổ đội thợ lành nghề thi công bài bản và tận tâm.</p>
                </div>

                <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5">
                    <div class="w-9 h-9 rounded-lg flex items-center justify-center mb-3 text-amber-600 bg-amber-50">
                        <i class="fa-solid fa-layer-group text-base"></i>
                    </div>
                    <h4 class="text-[13px] sm:text-sm font-bold text-slate-800 mb-1.5 leading-snug">Cập nhật xu hướng thiết kế hiện đại</h4>
                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Ứng dụng vật liệu bền vững, giải pháp chống nóng, chống thấm và biện pháp thi công tiên tiến.</p>
                </div>

                <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5">
                    <div class="w-9 h-9 rounded-lg flex items-center justify-center mb-3 text-amber-600 bg-amber-50">
                        <i class="fa-solid fa-clipboard-check text-base"></i>
                    </div>
                    <h4 class="text-[13px] sm:text-sm font-bold text-slate-800 mb-1.5 leading-snug">Giám sát tiến độ chuẩn xác</h4>
                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Báo cáo tiến độ và hình ảnh công trường định kỳ để chủ đầu tư dễ dàng theo dõi mọi lúc mọi nơi.</p>
                </div>

                <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5">
                    <div class="w-9 h-9 rounded-lg flex items-center justify-center mb-3 text-amber-600 bg-amber-50">
                        <i class="fa-solid fa-shield-halved text-base"></i>
                    </div>
                    <h4 class="text-[13px] sm:text-sm font-bold text-slate-800 mb-1.5 leading-snug">Bảo hành công trình lâu dài</h4>
                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Chính sách hậu mãi rõ ràng, kiểm tra và hỗ trợ nhanh chóng sau khi bàn giao đưa vào sử dụng.</p>
                </div>

                <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5">
                    <div class="w-9 h-9 rounded-lg flex items-center justify-center mb-3 text-amber-600 bg-amber-50">
                        <i class="fa-solid fa-file-invoice-dollar text-base"></i>
                    </div>
                    <h4 class="text-[13px] sm:text-sm font-bold text-slate-800 mb-1.5 leading-snug">Giá cả hợp lý &amp; minh bạch</h4>
                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Dự toán chi tiết từng hạng mục, chủng loại vật tư rõ ràng, tối ưu ngân sách cho chủ đầu tư.</p>
                </div>

                <div class="bg-white rounded-xl border border-slate-200 p-4 sm:p-5">
                    <div class="w-9 h-9 rounded-lg flex items-center justify-center mb-3 text-amber-600 bg-amber-50">
                        <i class="fa-solid fa-headset text-base"></i>
                    </div>
                    <h4 class="text-[13px] sm:text-sm font-bold text-slate-800 mb-1.5 leading-snug">Hỗ trợ tư vấn miễn phí 24/7</h4>
                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">Tư vấn pháp lý giấy phép xây dựng, phong thủy, công năng và dự toán chi phí hoàn toàn miễn phí.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 6: CÔNG TRÌNH THỰC TẾ THI CÔNG XÂY DỰNG (9 ẢNH THỰC TẾ)
         Danh mục nhỏ gọn, 2 cột trên điện thoại, không tràn hay thiếu tên sản phẩm
         ========================================================= -->
    <section id="cong-trinh-thuc-te" class="py-10 sm:py-14 bg-white">
        <div class="site-container">
            <div class="text-center mb-5 sm:mb-7">
                <h2 class="section-heading text-lg sm:text-2xl font-bold uppercase">
                    Công Trình Thực Tế Thi Công Xây Dựng
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3">
                    Hình ảnh thực tế các công trình do CÔNG TY TNHH XÂY DỰNG TQCONS trực tiếp thiết kế và thi công.
                </p>
            </div>

            <!-- Thanh danh mục lọc: chữ nhỏ gọn, hiển thị đẹp trên cả máy tính và điện thoại -->
            <div class="flex flex-wrap items-center justify-center gap-2 mb-6 sm:mb-8" id="workFilterTabs">
                <button type="button" onclick="filterWorks('all')" data-cat="all" class="cat-tab-btn active">Tất cả</button>
                <button type="button" onclick="filterWorks('khach-san')" data-cat="khach-san" class="cat-tab-btn">Khách sạn – Căn hộ</button>
                <button type="button" onclick="filterWorks('biet-thu')" data-cat="biet-thu" class="cat-tab-btn">Biệt thự</button>
                <button type="button" onclick="filterWorks('nha-pho')" data-cat="nha-pho" class="cat-tab-btn">Nhà phố</button>
                <button type="button" onclick="filterWorks('van-phong')" data-cat="van-phong" class="cat-tab-btn">Văn phòng</button>
            </div>

            <!-- Lưới sản phẩm/công trình: 2 cột trên điện thoại, 3 cột trên máy tính (9 ảnh thực tế đều đẹp) -->
            <div id="worksGrid" class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
                <!-- Nội dung được render tự động bằng JavaScript từ danh sách 9 ảnh Drive thực tế -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 7: DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (10 ẢNH THỰC TẾ)
         ========================================================= -->
    <section id="du-an-da-nang" class="py-10 sm:py-14" style="background-color: var(--brand-bg-soft);">
        <div class="site-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="section-heading text-lg sm:text-2xl font-bold uppercase">
                    Các Dự Án Tiêu Biểu Tại Đà Nẵng
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Tổng hợp các dự án xây dựng nhà ở, biệt thự, căn hộ, khách sạn và công trình dân dụng tiêu biểu TQCONS triển khai tại các quận, khu đô thị Đà Nẵng.
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 5 cột trên máy tính (10 dự án chia 2 hàng đều đẹp) -->
            <div id="danangProjectsGrid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                <!-- Render tự động 10 ảnh dự án Đà Nẵng -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 8: BÁO GIÁ DỊCH VỤ (Theo web mẫu tintruongthinh.com)
         ========================================================= -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-white">
        <div class="site-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="section-heading text-lg sm:text-2xl font-bold uppercase">
                    Báo Giá Thiết Kế &amp; Thi Công Tham Khảo
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3">
                    Đơn giá rõ ràng theo từng hạng mục, hỗ trợ khảo sát mặt bằng và lập dự toán chi tiết miễn phí.
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <div class="border border-slate-200 rounded-xl p-4 sm:p-5 bg-white flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <h3 class="text-[13px] sm:text-base font-bold leading-snug mb-2" style="color: var(--brand-primary);">
                            Báo Giá Thiết Kế Kiến Trúc
                        </h3>
                        <p class="text-base sm:text-lg font-extrabold text-amber-600 mb-3">Từ 120.000đ/m²</p>
                        <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5 mb-4">
                            <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-amber-600 mt-0.5"></i><span>Hồ sơ chi tiết Kiến trúc &amp; Kết cấu</span></li>
                            <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-amber-600 mt-0.5"></i><span>Hệ thống Điện – Nước (M&amp;E)</span></li>
                            <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-amber-600 mt-0.5"></i><span>Phối cảnh 3D mặt tiền &amp; ngoại thất</span></li>
                        </ul>
                    </div>
                    <a href="#tu-van-bao-gia" onclick="prefillQuote('Thiết kế kiến trúc')" class="block text-center py-2 px-3 rounded-lg text-xs font-semibold text-white transition" style="background-color: var(--brand-primary);">
                        Nhận báo giá chi tiết
                    </a>
                </div>

                <div class="border border-slate-200 rounded-xl p-4 sm:p-5 bg-white flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <h3 class="text-[13px] sm:text-base font-bold leading-snug mb-2" style="color: var(--brand-primary);">
                            Báo Giá Thi Công Phần Thô
                        </h3>
                        <p class="text-base sm:text-lg font-extrabold text-amber-600 mb-3">Từ 3.600.000đ/m²</p>
                        <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5 mb-4">
                            <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-amber-600 mt-0.5"></i><span>Vật tư phần thô chính hãng loại 1</span></li>
                            <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-amber-600 mt-0.5"></i><span>Nhân công xây tô, điện nước âm</span></li>
                            <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-amber-600 mt-0.5"></i><span>Kỹ sư giám sát trực tiếp mỗi ngày</span></li>
                        </ul>
                    </div>
                    <a href="#tu-van-bao-gia" onclick="prefillQuote('Thi công phần thô')" class="block text-center py-2 px-3 rounded-lg text-xs font-semibold text-white transition" style="background-color: var(--brand-primary);">
                        Nhận báo giá chi tiết
                    </a>
                </div>

                <div class="border border-slate-200 rounded-xl p-4 sm:p-5 bg-white flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <h3 class="text-[13px] sm:text-base font-bold leading-snug mb-2" style="color: var(--brand-primary);">
                            Báo Giá Thi Công Hoàn Thiện
                        </h3>
                        <p class="text-base sm:text-lg font-extrabold text-amber-600 mb-3">Từ 2.400.000đ/m²</p>
                        <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5 mb-4">
                            <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-amber-600 mt-0.5"></i><span>Ốp lát gạch, đá cầu thang &amp; mặt tiền</span></li>
                            <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-amber-600 mt-0.5"></i><span>Sơn nước nội ngoại thất &amp; trần thạch cao</span></li>
                            <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-amber-600 mt-0.5"></i><span>Lắp đặt cửa, thiết bị vệ sinh &amp; đèn</span></li>
                        </ul>
                    </div>
                    <a href="#tu-van-bao-gia" onclick="prefillQuote('Thi công hoàn thiện')" class="block text-center py-2 px-3 rounded-lg text-xs font-semibold text-white transition" style="background-color: var(--brand-primary);">
                        Nhận báo giá chi tiết
                    </a>
                </div>

                <div class="border border-slate-200 rounded-xl p-4 sm:p-5 bg-white flex flex-col justify-between hover:shadow-md transition">
                    <div>
                        <h3 class="text-[13px] sm:text-base font-bold leading-snug mb-2" style="color: var(--brand-primary);">
                            Báo Giá Thi Công Trọn Gói
                        </h3>
                        <p class="text-base sm:text-lg font-extrabold text-amber-600 mb-3">Từ 5.800.000đ/m²</p>
                        <ul class="text-[11px] sm:text-xs text-slate-600 space-y-1.5 mb-4">
                            <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-amber-600 mt-0.5"></i><span>Chìa khóa trao tay từ A đến Z</span></li>
                            <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-amber-600 mt-0.5"></i><span>Hỗ trợ xin giấy phép xây dựng</span></li>
                            <li class="flex items-start gap-1.5"><i class="fa-solid fa-check text-amber-600 mt-0.5"></i><span>Ưu đãi chi phí thiết kế khi ký trọn gói</span></li>
                        </ul>
                    </div>
                    <a href="#tu-van-bao-gia" onclick="prefillQuote('Thi công trọn gói')" class="block text-center py-2 px-3 rounded-lg text-xs font-semibold text-white transition" style="background-color: var(--brand-accent);">
                        Nhận báo giá chi tiết
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 9: FORM YÊU CẦU & BÁO GIÁ TRANG CHỦ
         ========================================================= -->
    <section id="tu-van-bao-gia" class="py-10 sm:py-14" style="background-color: var(--brand-primary);">
        <div class="site-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                <div class="lg:col-span-5 text-white">
                    <h2 class="text-xl sm:text-2xl font-extrabold uppercase mb-3">
                        Yêu Cầu Tư Vấn &amp; Báo Giá Miễn Phí
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-200 leading-relaxed mb-5">
                        Quý khách vui lòng điền thông tin công trình dự kiến xây dựng. Đội ngũ kỹ sư <strong>CÔNG TY TNHH XÂY DỰNG TQCONS</strong> sẽ liên hệ khảo sát và gửi bảng dự toán chi tiết trong thời gian sớm nhất.
                    </p>
                    <div class="space-y-3 text-xs sm:text-sm text-slate-100">
                        <div class="flex items-start gap-3">
                            <i class="fa-solid fa-location-dot text-amber-400 mt-1"></i>
                            <span><strong>Văn phòng:</strong> 170 Lê Sỹ, Phường Hòa Xuân, TP Đà Nẵng</span>
                        </div>
                        <div class="flex items-center gap-3">
                            <i class="fa-solid fa-phone-volume text-amber-400"></i>
                            <span><strong>Hotline / Zalo:</strong> <a href="tel:0948259979" class="underline hover:text-amber-300 font-semibold">0948.259.979</a></span>
                        </div>
                        <div class="flex items-center gap-3">
                            <i class="fa-solid fa-clock text-amber-400"></i>
                            <span><strong>Giờ làm việc:</strong> Thứ 2 – Thứ 7 (07:30 – 17:30)</span>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-7">
                    <form id="quoteForm" class="bg-white rounded-xl p-5 sm:p-7 shadow-lg">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5 sm:gap-4">
                            <div>
                                <label for="qName" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                                <input id="qName" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-amber-500">
                            </div>
                            <div>
                                <label for="qPhone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại *</label>
                                <input id="qPhone" type="tel" required placeholder="Nhập số điện thoại liên hệ" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-amber-500">
                            </div>
                            <div>
                                <label for="qEmail" class="block text-xs font-semibold text-slate-700 mb-1">Email</label>
                                <input id="qEmail" type="email" placeholder="example@gmail.com" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-amber-500">
                            </div>
                            <div>
                                <label for="qType" class="block text-xs font-semibold text-slate-700 mb-1">Loại công trình</label>
                                <select id="qType" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg bg-white focus:outline-none focus:border-amber-500">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                    <option value="Văn phòng">Văn phòng</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                    <option value="Thiết kế kiến trúc">Thiết kế kiến trúc</option>
                                    <option value="Thi công phần thô">Thi công phần thô</option>
                                    <option value="Thi công hoàn thiện">Thi công hoàn thiện</option>
                                    <option value="Thi công trọn gói">Thi công trọn gói</option>
                                </select>
                            </div>
                            <div>
                                <label for="qBudget" class="block text-xs font-semibold text-slate-700 mb-1">Mức đầu tư dự kiến</label>
                                <select id="qBudget" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg bg-white focus:outline-none focus:border-amber-500">
                                    <option value="Chưa xác định">Chưa xác định</option>
                                    <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                    <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                                    <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                                    <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                </select>
                            </div>
                            <div>
                                <label for="qArea" class="block text-xs font-semibold text-slate-700 mb-1">Diện tích đất / Quy mô tầng</label>
                                <input id="qArea" type="text" placeholder="VD: 5x20m, 3 tầng tại Hòa Xuân" class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-amber-500">
                            </div>
                        </div>

                        <div class="mt-3.5">
                            <label for="qNote" class="block text-xs font-semibold text-slate-700 mb-1">Yêu cầu chi tiết</label>
                            <textarea id="qNote" rows="3" placeholder="Mô tả nhu cầu thiết kế, thi công hoặc thời gian dự kiến khởi công..." class="w-full px-3.5 py-2.5 text-sm border border-slate-300 rounded-lg focus:outline-none focus:border-amber-500"></textarea>
                        </div>

                        <div class="mt-4 flex flex-col sm:flex-row sm:items-center justify-between gap-3">
                            <span class="text-[11px] text-slate-500">Thông tin của quý khách được TQCONS bảo mật tuyệt đối.</span>
                            <button type="submit" class="px-6 py-2.5 rounded-lg text-sm font-bold text-white transition shadow hover:opacity-95 cursor-pointer" style="background-color: var(--brand-accent);">
                                Gửi Yêu Cầu Báo Giá
                            </button>
                        </div>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 10: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ
         ========================================================= -->
    <section id="tin-tuc" class="py-10 sm:py-14 bg-white">
        <div class="site-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="section-heading text-lg sm:text-2xl font-bold uppercase">
                    Tin Tức &amp; Kinh Nghiệm Xây Dựng
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3">
                    Chia sẻ kiến thức thực tế về thiết kế, kết cấu, vật liệu và quy trình thi công xây dựng tại Đà Nẵng.
                </p>
            </div>

            <!-- 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div id="articlesGrid" class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <!-- Render tự động các bài viết -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 11: DANH MỤC CÁC ĐỐI TÁC
         ========================================================= -->
    <section id="doi-tac" class="py-10 sm:py-12" style="background-color: var(--brand-bg-soft);">
        <div class="site-container">
            <div class="text-center mb-6 sm:mb-8">
                <h2 class="section-heading text-lg sm:text-2xl font-bold uppercase">
                    Đối Tác &amp; Nhà Cung Cấp Vật Tư
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3">
                    TQCONS hợp tác cùng các thương hiệu vật liệu xây dựng hàng đầu để đảm bảo chất lượng bền vững cho mọi công trình.
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-6 gap-3 sm:gap-4">
                <!-- Logo đối tác thiết kế SVG gọn nét, không bị lỗi ảnh -->
                <div class="bg-white border border-slate-200 rounded-xl p-4 flex items-center justify-center h-20 hover:shadow-sm transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#0055A5]">THÉP HÒA PHÁT</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-4 flex items-center justify-center h-20 hover:shadow-sm transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#C8102E]">XI MĂNG SÔNG GIANH</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-4 flex items-center justify-center h-20 hover:shadow-sm transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#00338D]">SƠN DULUX</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-4 flex items-center justify-center h-20 hover:shadow-sm transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#0A4D8C]">SƠN JOTUN</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-4 flex items-center justify-center h-20 hover:shadow-sm transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#0066B3]">NHỰA BÌNH MINH</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-4 flex items-center justify-center h-20 hover:shadow-sm transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#D41F26]">CÁP ĐIỆN CADIVI</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-4 flex items-center justify-center h-20 hover:shadow-sm transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#1A1A1A]">TOTO VIỆT NAM</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-4 flex items-center justify-center h-20 hover:shadow-sm transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#B45309]">GỖ AN CƯỜNG</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-4 flex items-center justify-center h-20 hover:shadow-sm transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#00703C]">SIKA VIỆT NAM</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-4 flex items-center justify-center h-20 hover:shadow-sm transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#1D4ED8]">PANASONIC</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-4 flex items-center justify-center h-20 hover:shadow-sm transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#991B1B]">GẠCH ĐỒNG TÂM</span>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-4 flex items-center justify-center h-20 hover:shadow-sm transition">
                    <span class="text-sm sm:text-base font-extrabold tracking-tight text-[#0F766E]">NHÔM XINGFA</span>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 12: BẢN ĐỒ GOOGLE MAP & FANPAGE TRÊN TRANG CHỦ
         ========================================================= -->
    <section id="lien-he" class="py-10 sm:py-14 bg-white">
        <div class="site-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="section-heading text-lg sm:text-2xl font-bold uppercase">
                    Bản Đồ Đường Đi &amp; Fanpage Chính Thức
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3">
                    Kết nối trực tiếp với CÔNG TY TNHH XÂY DỰNG TQCONS tại 170 Lê Sỹ, Phường Hòa Xuân, TP Đà Nẵng.
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6 items-stretch">
                <!-- Cột Google Map (7 cột trên máy tính) -->
                <div class="lg:col-span-7 flex flex-col border border-slate-200 rounded-xl overflow-hidden shadow-sm bg-white">
                    <div class="px-4 py-3 border-b border-slate-200 flex items-center justify-between gap-2" style="background-color: var(--brand-bg-soft);">
                        <div class="flex items-center gap-2 text-xs sm:text-sm font-bold" style="color: var(--brand-primary);">
                            <i class="fa-solid fa-map-location-dot text-amber-600"></i>
                            <span>170 Lê Sỹ, Phường Hòa Xuân, TP Đà Nẵng</span>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=170+L%C3%AA+S%E1%BB%B9,+H%C3%B2a+Xu%C3%A2n,+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-[11px] sm:text-xs font-semibold text-amber-600 hover:underline whitespace-nowrap">
                            Mở bản đồ lớn
                        </a>
                    </div>
                    <div class="w-full h-[300px] sm:h-[360px] flex-1 bg-slate-100">
                        <iframe
                            title="Bản đồ CÔNG TY TNHH XÂY DỰNG TQCONS - 170 Lê Sỹ, Hòa Xuân, Đà Nẵng"
                            src="https://maps.google.com/maps?q=170+L%C3%AA+S%E1%BB%B9,+H%C3%B2a+Xu%C3%A2n,+%C4%90%C3%A0+N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                            allowfullscreen
                        ></iframe>
                    </div>
                </div>

                <!-- Cột Fanpage Facebook trên trang chủ (5 cột trên máy tính) -->
                <div class="lg:col-span-5 flex flex-col border border-slate-200 rounded-xl overflow-hidden shadow-sm bg-white">
                    <div class="px-4 py-3 border-b border-slate-200 flex items-center justify-between gap-2" style="background-color: var(--brand-bg-soft);">
                        <div class="flex items-center gap-2 text-xs sm:text-sm font-bold" style="color: var(--brand-primary);">
                            <i class="fa-brands fa-facebook text-[#1877F2]"></i>
                            <span>Fanpage CÔNG TY TNHH XÂY DỰNG TQCONS</span>
                        </div>
                        <a href="https://www.facebook.com/search/top?q=C%C3%94NG%20TY%20TNHH%20X%C3%82Y%20D%E1%BB%B0NG%20TQCONS" target="_blank" rel="noopener noreferrer" class="text-[11px] sm:text-xs font-semibold text-[#1877F2] hover:underline whitespace-nowrap">
                            Xem trang
                        </a>
                    </div>

                    <!-- Khung Fanpage trực quan hiển thị đẹp ổn định trên mọi trình duyệt -->
                    <div class="p-4 flex-1 flex flex-col justify-between bg-white">
                        <div>
                            <!-- Ảnh bìa Fanpage lấy từ ảnh thực tế thi công -->
                            <div class="relative rounded-lg overflow-hidden h-36 sm:h-40 bg-slate-800">
                                <img
                                    src="https://lh3.googleusercontent.com/d/1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv=w800"
                                    alt="Ảnh bìa Fanpage TQCONS"
                                    class="w-full h-full object-cover opacity-85"
                                    onerror="handleDriveImgError(this, '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv', 800)"
                                >
                                <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/25 to-transparent"></div>
                                <div class="absolute bottom-3 left-3 right-3 flex items-center gap-3">
                                    <div class="w-12 h-12 rounded-lg bg-white p-1 shadow shrink-0 flex items-center justify-center">
                                        <img
                                            src="https://lh3.googleusercontent.com/d/1qUuDypH8KEDmMR92is2nr8m9bxBwtaER=w200"
                                            alt="Avatar Fanpage TQCONS"
                                            class="w-full h-full object-contain"
                                            onerror="handleDriveImgError(this, '1qUuDypH8KEDmMR92is2nr8m9bxBwtaER', 200)"
                                        >
                                    </div>
                                    <div class="text-white min-w-0">
                                        <h3 class="text-sm font-bold leading-tight">CÔNG TY TNHH XÂY DỰNG TQCONS</h3>
                                        <p class="text-[11px] text-slate-200 mt-0.5">Thiết kế &amp; Thi công Xây dựng Đà Nẵng</p>
                                    </div>
                                </div>
                            </div>

                            <!-- Thông tin cập nhật mới từ Fanpage -->
                            <div class="mt-4 space-y-2.5 text-xs text-slate-600">
                                <p class="leading-relaxed">
                                    Cập nhật hình ảnh thi công thực tế hàng ngày tại công trường Hòa Xuân, Cẩm Lệ, Sơn Trà, Ngũ Hành Sơn và toàn TP. Đà Nẵng.
                                </p>
                                <div class="flex items-center gap-2 text-slate-700">
                                    <i class="fa-solid fa-phone text-[#1877F2]"></i>
                                    <span>Hotline tư vấn: <strong>0948.259.979</strong></span>
                                </div>
                                <div class="flex items-center gap-2 text-slate-700">
                                    <i class="fa-solid fa-globe text-[#1877F2]"></i>
                                    <span>Website: <strong>tqcons.com</strong></span>
                                </div>
                            </div>
                        </div>

                        <!-- Nút tương tác Fanpage -->
                        <div class="grid grid-cols-2 gap-2.5 mt-5 pt-4 border-t border-slate-100">
                            <a href="https://www.facebook.com/search/top?q=C%C3%94NG%20TY%20TNHH%20X%C3%82Y%20D%E1%BB%B0NG%20TQCONS" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-2 py-2.5 px-3 rounded-lg text-xs font-semibold text-white bg-[#1877F2] hover:bg-[#1465CC] transition">
                                <i class="fa-brands fa-facebook"></i>
                                <span>Theo dõi Fanpage</span>
                            </a>
                            <a href="https://zalo.me/0948259979" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-2 py-2.5 px-3 rounded-lg text-xs font-semibold text-slate-700 bg-slate-100 hover:bg-slate-200 transition">
                                <i class="fa-solid fa-comments text-[#0068FF]"></i>
                                <span>Nhắn tin tư vấn</span>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FLATSOME SECTION 13: FOOTER (Chuẩn Flatsome 3 cột gọn gàng)
         ========================================================= -->
    <footer class="text-slate-200 pt-10 pb-6" style="background-color: var(--brand-primary-dark);">
        <div class="site-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-7 pb-8 border-b border-white/15">
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5">
                    <div class="flex items-center gap-3 mb-4">
                        <div class="bg-white rounded-lg p-1.5 shrink-0">
                            <img
                                src="https://lh3.googleusercontent.com/d/1qUuDypH8KEDmMR92is2nr8m9bxBwtaER=w300"
                                alt="Logo TQCONS"
                                class="h-9 w-auto object-contain"
                                onerror="handleDriveImgError(this, '1qUuDypH8KEDmMR92is2nr8m9bxBwtaER', 300)"
                            >
                        </div>
                        <div>
                            <h3 class="text-sm sm:text-base font-extrabold text-white">CÔNG TY TNHH XÂY DỰNG TQCONS</h3>
                            <p class="text-xs text-amber-400">Website: tqcons.com</p>
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-amber-400 mt-1"></i>
                            <span>Trụ sở: 170 Lê Sỹ, Phường Hòa Xuân, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone text-amber-400"></i>
                            <span>Hotline / Zalo: <a href="tel:0948259979" class="text-white font-semibold hover:text-amber-300">0948.259.979</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-envelope text-amber-400"></i>
                            <span>Email: info@tqcons.com</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-building text-amber-400"></i>
                            <span>Mã số thuế: 0402106937</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-4">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-2 border-b border-white/15">
                        Lĩnh Vực Hoạt Động
                    </h4>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400 transition">Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400 transition">Thi công phần thô nhà phố, biệt thự</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400 transition">Thi công hoàn thiện công trình</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400 transition">Thi công xây dựng trọn gói Đà Nẵng</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-amber-400 transition">Cải tạo, sửa chữa khách sạn &amp; căn hộ</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục nhanh -->
                <div class="lg:col-span-3">
                    <h4 class="text-sm font-bold text-white uppercase tracking-wide mb-3 pb-2 border-b border-white/15">
                        Danh Mục Trang Chủ
                    </h4>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-300">
                        <li><a href="#cong-trinh-thuc-te" class="hover:text-amber-400 transition">Công trình thực tế</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-amber-400 transition">Dự án tại Đà Nẵng</a></li>
                        <li><a href="#bao-gia" class="hover:text-amber-400 transition">Báo giá thiết kế &amp; thi công</a></li>
                        <li><a href="#tin-tuc" class="hover:text-amber-400 transition">Tin tức xây dựng</a></li>
                        <li><a href="#doi-tac" class="hover:text-amber-400 transition">Đối tác cung cấp</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
                <p>Copyright 2026 © CÔNG TY TNHH XÂY DỰNG TQCONS (tqcons.com). All rights reserved.</p>
                <p>170 Lê Sỹ, Phường Hòa Xuân, TP Đà Nẵng</p>
            </div>
        </div>
    </footer>

    <!-- =========================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE
         Tương thích tối ưu cả Máy tính (góc phải dưới) và Điện thoại (thanh đáy cố định)
         ========================================================= -->
    <!-- Bản Máy tính / Tablet lớn -->
    <div class="hidden md:flex fixed right-4 bottom-6 z-50 flex-col items-end gap-2.5">
        <a
            href="https://zalo.me/0948259979"
            target="_blank"
            rel="noopener noreferrer"
            class="flex items-center gap-2 pl-3 pr-3.5 py-2 rounded-full bg-[#0068FF] hover:bg-[#0055D4] text-white shadow-lg transition text-xs font-bold"
            aria-label="Liên hệ Zalo TQCONS"
        >
            <span class="w-7 h-7 rounded-full bg-white text-[#0068FF] flex items-center justify-center font-extrabold text-[11px]">Zalo</span>
            <span>Chat Zalo</span>
        </a>

        <a
            href="https://www.facebook.com/search/top?q=C%C3%94NG%20TY%20TNHH%20X%C3%82Y%20D%E1%BB%B0NG%20TQCONS"
            target="_blank"
            rel="noopener noreferrer"
            class="flex items-center gap-2 pl-3 pr-3.5 py-2 rounded-full bg-[#1877F2] hover:bg-[#1261C9] text-white shadow-lg transition text-xs font-bold"
            aria-label="Fanpage Facebook TQCONS"
        >
            <span class="w-7 h-7 rounded-full bg-white text-[#1877F2] flex items-center justify-center text-sm"><i class="fa-brands fa-facebook-f"></i></span>
            <span>Facebook</span>
        </a>

        <a
            href="tel:0948259979"
            class="hotline-pulse flex items-center gap-2 pl-3 pr-4 py-2 rounded-full text-white shadow-lg transition text-xs font-bold"
            style="background-color: var(--brand-accent);"
            aria-label="Gọi hotline 0948.259.979"
        >
            <span class="w-7 h-7 rounded-full bg-white text-amber-600 flex items-center justify-center text-sm"><i class="fa-solid fa-phone"></i></span>
            <span>0948.259.979</span>
        </a>
    </div>

    <!-- Bản Điện thoại: Thanh liên hệ nổi bật dưới đáy, chia 3 cột đều không tràn viền -->
    <div class="md:hidden fixed bottom-0 left-0 right-0 z-50 bg-white border-t border-slate-200 shadow-[0_-4px_12px_rgba(0,0,0,0.08)] grid grid-cols-3">
        <a href="https://zalo.me/0948259979" target="_blank" rel="noopener noreferrer" class="flex flex-col items-center justify-center py-2 text-[#0068FF] active:bg-slate-50">
            <span class="text-xs font-extrabold leading-none border border-[#0068FF] rounded px-1.5 py-0.5 mb-1">Zalo</span>
            <span class="text-[11px] font-semibold">Chat Zalo</span>
        </a>
        <a href="https://www.facebook.com/search/top?q=C%C3%94NG%20TY%20TNHH%20X%C3%82Y%20D%E1%BB%B0NG%20TQCONS" target="_blank" rel="noopener noreferrer" class="flex flex-col items-center justify-center py-2 text-[#1877F2] border-x border-slate-100 active:bg-slate-50">
            <i class="fa-brands fa-facebook text-base mb-0.5"></i>
            <span class="text-[11px] font-semibold">Facebook</span>
        </a>
        <a href="tel:0948259979" class="flex flex-col items-center justify-center py-2 text-white active:opacity-90" style="background-color: var(--brand-accent);">
            <i class="fa-solid fa-phone-volume text-base mb-0.5"></i>
            <span class="text-[11px] font-bold">0948.259.979</span>
        </a>
    </div>

    <!-- =========================================================
         MODAL XEM CHI TIẾT ẢNH CÔNG TRÌNH / BÀI VIẾT & THÔNG BÁO
         ========================================================= -->
    <div id="detailModal" class="fixed inset-0 z-[70] hidden items-center justify-center bg-black/70 p-4" onclick="closeDetailModal(event)">
        <div class="bg-white rounded-xl max-w-2xl w-full overflow-hidden shadow-2xl max-h-[90vh] flex flex-col" onclick="event.stopPropagation()">
            <div class="px-4 py-3 border-b border-slate-200 flex items-center justify-between gap-3">
                <h3 id="modalTitle" class="text-sm sm:text-base font-bold text-slate-800 leading-snug"></h3>
                <button type="button" onclick="closeDetailModal()" class="w-8 h-8 rounded-lg hover:bg-slate-100 flex items-center justify-center text-slate-600 shrink-0" aria-label="Đóng">
                    <i class="fa-solid fa-xmark text-lg"></i>
                </button>
            </div>
            <div class="p-4 sm:p-5 overflow-y-auto">
                <div id="modalImgWrap" class="mb-4 rounded-lg overflow-hidden bg-slate-100">
                    <img id="modalImg" src="" alt="" class="w-full max-h-[380px] object-contain mx-auto">
                </div>
                <p id="modalCategory" class="text-xs font-semibold text-amber-600 mb-1.5"></p>
                <p id="modalDesc" class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-4"></p>
                <div class="flex flex-wrap items-center gap-2.5 pt-3 border-t border-slate-100">
                    <a href="tel:0948259979" class="px-4 py-2 rounded-lg text-xs font-semibold text-white" style="background-color: var(--brand-primary);">
                        <i class="fa-solid fa-phone mr-1"></i> Hotline: 0948.259.979
                    </a>
                    <a href="#tu-van-bao-gia" onclick="closeDetailModal()" class="px-4 py-2 rounded-lg text-xs font-semibold text-white" style="background-color: var(--brand-accent);">
                        Yêu cầu báo giá công trình tương tự
                    </a>
                </div>
            </div>
        </div>
    </div>

    <!-- Thông báo Toast (thay thế hoàn toàn alert) -->
    <div id="toastBox" class="fixed top-20 right-4 z-[80] hidden max-w-xs sm:max-w-sm bg-emerald-700 text-white text-xs sm:text-sm font-medium px-4 py-3 rounded-xl shadow-xl">
        <div class="flex items-start gap-2.5">
            <i class="fa-solid fa-circle-check text-base mt-0.5"></i>
            <span id="toastMessage"></span>
        </div>
    </div>

    <!-- =========================================================
         JAVASCRIPT: DỮ LIỆU ẢNH THỰC TẾ, SLIDER, LỌC DANH MỤC, FORM
         ========================================================= -->
    <script>
        /**
         * Hàm tự động dự phòng tải ảnh Google Drive an toàn
         * Thử lần lượt lh3.googleusercontent -> drive.google.com/thumbnail -> drive.google.com/uc -> placeholder
         */
        function handleDriveImgError(img, fileId, width) {
            try {
                const step = parseInt(img.dataset.fallbackStep || '0', 10);
                if (step === 0) {
                    img.dataset.fallbackStep = '1';
                    img.src = `https://drive.google.com/thumbnail?id=${fileId}&sz=w${width}`;
                } else if (step === 1) {
                    img.dataset.fallbackStep = '2';
                    img.src = `https://drive.google.com/uc?export=view&id=${fileId}`;
                } else {
                    img.onerror = null;
                    img.src = `https://placehold.co/${width}x${Math.round(width * 0.75)}/0E3A66/FFFFFF?text=TQCONS`;
                }
            } catch (err) {
                img.onerror = null;
            }
        }

        function getDriveImgUrl(fileId, width = 900) {
            return `https://lh3.googleusercontent.com/d/${fileId}=w${width}`;
        }

        /* =========================================================
           1. DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG TỪ GOOGLE DRIVE
           Phân loại đúng theo danh mục của web mẫu tintruongthinh.com
           ========================================================= */
        const constructionWorks = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Thi Công Phần Thô & Kết Cấu Nhà Phố Hiện Đại',
                category: 'nha-pho',
                categoryName: 'Nhà phố – Thi công phần thô',
                desc: 'Công trình nhà phố do TQCONS thi công phần thô đúng chuẩn mác bê tông, cốt thép và quy trình bảo dưỡng nghiêm ngặt.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                title: 'Thi Công Hoàn Thiện Nhà Phố 3 Tầng Trọn Gói',
                category: 'nha-pho',
                categoryName: 'Nhà phố – Thi công hoàn thiện',
                desc: 'Hạng mục hoàn thiện mặt tiền, ốp lát, sơn nước và hệ thống điện nước đồng bộ cho nhà phố gia đình tại Đà Nẵng.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: 'Thi Công Biệt Thự Hiện Đại Không Gian Mở',
                category: 'biet-thu',
                categoryName: 'Biệt thự – Xây dựng trọn gói',
                desc: 'Biệt thự cao cấp được TQCONS triển khai từ hồ sơ thiết kế kiến trúc đến thi công kết cấu và hoàn thiện ngoại thất.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Thi Công Căn Hộ Cho Thuê & Khách Sạn Mini',
                category: 'khach-san',
                categoryName: 'Khách sạn – Căn hộ – Phòng trọ',
                desc: 'Giải pháp tối ưu số phòng và công năng khai thác cho mô hình căn hộ cho thuê, khách sạn khu vực trung tâm.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                title: 'Thi Công Hệ Khung Bê Tông Cốt Thép & Sàn',
                category: 'nha-pho',
                categoryName: 'Nhà phố – Kết cấu phần thô',
                desc: 'Nghiệm thu thép sàn, cốp pha và đổ bê tông thương phẩm dưới sự giám sát trực tiếp của kỹ sư TQCONS.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Thi Công Hoàn Thiện Nội Thất Biệt Thự Cao Cấp',
                category: 'biet-thu',
                categoryName: 'Biệt thự – Thi công nội thất',
                desc: 'Lắp đặt hoàn thiện trần thạch cao, chiếu sáng, cầu thang và nội thất gỗ đồng bộ theo bản vẽ 3D.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Thiết Kế & Thi Công Tòa Nhà Văn Phòng Hiện Đại',
                category: 'van-phong',
                categoryName: 'Văn phòng – Thi công trọn gói',
                desc: 'Công trình văn phòng làm việc tối ưu ánh sáng tự nhiên, kết cấu vượt nhịp và mặt dựng kính hiện đại.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                title: 'Thi Công Cải Tạo & Hoàn Thiện Khách Sạn Biển',
                category: 'khach-san',
                categoryName: 'Khách sạn – Căn hộ – Phòng trọ',
                desc: 'Thi công hoàn thiện hệ thống phòng nghỉ, sảnh đón tiếp và hạ tầng kỹ thuật đạt chuẩn lưu trú.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                title: 'Thi Công Xây Dựng Nhà Phố Kết Hợp Kinh Doanh',
                category: 'van-phong',
                categoryName: 'Văn phòng – Nhà phố kinh doanh',
                desc: 'Mô hình nhà phố tầng trệt kinh doanh văn phòng kết hợp không gian ở tiện nghi cho gia đình.'
            }
        ];

        /* =========================================================
           2. DỮ LIỆU 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG TỪ GOOGLE DRIVE
           ========================================================= */
        const danangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Nhà Phố Hiện Đại – KĐT Hòa Xuân, Đà Nẵng',
                location: 'Phường Hòa Xuân, TP Đà Nẵng',
                desc: 'Thiết kế và thi công trọn gói nhà phố hiện đại tại khu đô thị sinh thái Hòa Xuân, Đà Nẵng.'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Biệt Thự Phố 2 Mặt Tiền – Nam Hòa Xuân',
                location: 'KĐT Nam Hòa Xuân, Đà Nẵng',
                desc: 'Công trình biệt thự phố thông thoáng, kiến trúc tinh giản và bền vững trước khí hậu miền Trung.'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Tòa Căn Hộ Dịch Vụ – Quận Sơn Trà, Đà Nẵng',
                location: 'Quận Sơn Trà, TP Đà Nẵng',
                desc: 'Thi công căn hộ dịch vụ gần biển Mỹ Khê, tối ưu diện tích khai thác và tiện nghi lưu trú.'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Nhà Phố 3 Tầng – Khu Nam Việt Á, Đà Nẵng',
                location: 'Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Xây dựng phần thô và hoàn thiện trọn gói nhà ở gia đình tại khu dân cư Nam Việt Á.'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Khách Sạn Boutique – Ven Biển Ngũ Hành Sơn',
                location: 'Ngũ Hành Sơn, TP Đà Nẵng',
                desc: 'Dự án thi công xây dựng và hoàn thiện kiến trúc khách sạn du lịch tại khu vực ven biển Đà Nẵng.'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Nhà Phố Gia Đình – Đường Lê Sỹ, Hòa Xuân',
                location: 'Hòa Xuân, Cẩm Lệ, Đà Nẵng',
                desc: 'Công trình thi công chìa khóa trao tay đảm bảo tiến độ nhanh và chất lượng hoàn thiện sắc nét.'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Văn Phòng Công Ty – Quận Hải Châu, Đà Nẵng',
                location: 'Quận Hải Châu, TP Đà Nẵng',
                desc: 'Thiết kế thi công trụ sở văn phòng làm việc hiện đại tại khu vực trung tâm TP Đà Nẵng.'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Biệt Thự Sân Vườn – Khu Phước Lý, Đà Nẵng',
                location: 'Khu Phước Lý, TP Đà Nẵng',
                desc: 'Biệt thự sân vườn kết hợp mảng xanh tự nhiên, giải pháp chống thấm và thông gió hiệu quả.'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Nhà Phố 4 Tầng – Quận Thanh Khê, Đà Nẵng',
                location: 'Quận Thanh Khê, TP Đà Nẵng',
                desc: 'Công trình nhà phố kết hợp ở và cho thuê mặt bằng kinh doanh do TQCONS thi công trọn gói.'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Căn Hộ Cao Cấp – Quận Liên Chiểu, Đà Nẵng',
                location: 'Quận Liên Chiểu, TP Đà Nẵng',
                desc: 'Thi công phần thô, hoàn thiện và nội thất cơ bản cho công trình căn hộ tại Tây Bắc Đà Nẵng.'
            }
        ];

        /* =========================================================
           3. DỮ LIỆU BÀI VIẾT TRANG CHỦ (Theo web mẫu tintruongthinh.com)
           ========================================================= */
        const articlesData = [
            {
                imgId: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Hướng dẫn bảo dưỡng bê tông móng đúng kỹ thuật khi xây nhà',
                date: '15/10/2026',
                excerpt: 'Bảo dưỡng bê tông móng sau khi đổ giúp kết cấu đạt cường độ chuẩn, hạn chế rạn nứt bề mặt và tăng tuổi thọ công trình.',
                content: 'Trong quá trình thi công phần thô, bê tông móng là nền tảng chịu lực quan trọng nhất của toàn bộ ngôi nhà. Sau khi đổ bê tông từ 4 đến 6 giờ, cần tiến hành che phủ giữ ẩm và tưới nước bảo dưỡng đều đặn trong 7 ngày đầu tiên, đặc biệt trong điều kiện thời tiết nắng gió tại Đà Nẵng.'
            },
            {
                imgId: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: '03 nỗi lo lớn nhất khi xây nhà mà chủ đầu tư cần lưu ý',
                date: '08/10/2026',
                excerpt: 'Phát sinh chi phí, chậm tiến độ và chất lượng vật tư không đúng cam kết là 3 vấn đề cần giải quyết ngay từ khâu hợp đồng.',
                content: 'Để tránh phát sinh chi phí và chậm tiến độ khi xây nhà tại Đà Nẵng, chủ đầu tư nên có hồ sơ thiết kế chi tiết trước khi khởi công, bảng dự toán vật tư rõ ràng thương hiệu và lựa chọn nhà thầu có kỹ sư giám sát trực tiếp tại công trình như TQCONS.'
            },
            {
                imgId: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Thiết kế nội thất tối ưu ánh sáng và gió tự nhiên cho nhà phố',
                date: '29/09/2026',
                excerpt: 'Bố trí giếng trời, thông tầng và vật liệu sáng màu giúp không gian nhà phố ống luôn thông thoáng và tiết kiệm điện năng.',
                content: 'Nhà phố thường có chiều ngang hẹp và chiều sâu dài. Việc bố trí giếng trời giữa nhà kết hợp cầu thang thông thoáng, sử dụng cửa kính lấy sáng và gam màu trung tính sẽ mang lại cảm giác rộng rãi và thoải mái cho cả gia đình.'
            },
            {
                imgId: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Kinh nghiệm chuẩn bị hồ sơ xin giấy phép xây dựng tại Đà Nẵng',
                date: '18/09/2026',
                excerpt: 'Tổng hợp giấy tờ cần thiết, mật độ xây dựng và lưu ý khoảng lùi khi xin phép xây dựng nhà ở riêng lẻ tại Đà Nẵng.',
                content: 'Trước khi khởi công xây dựng, chủ đầu tư cần chuẩn bị sổ đỏ, bản vẽ thiết kế xin phép xây dựng theo đúng quy hoạch lộ giới, mật độ và chiều cao tầng của từng khu vực tại Đà Nẵng. Khi ký hợp đồng trọn gói tại TQCONS, khách hàng được hỗ trợ trọn bộ thủ tục xin phép xây dựng.'
            }
        ];

        /* =========================================================
           RENDER DANH SÁCH CÔNG TRÌNH THỰC TẾ (9 ẢNH)
           ========================================================= */
        function renderWorks(category = 'all') {
            const container = document.getElementById('worksGrid');
            if (!container) return;

            const filtered = category === 'all'
                ? constructionWorks
                : constructionWorks.filter(item => item.category === category);

            container.innerHTML = filtered.map(item => `
                <article
                    class="project-card bg-white border border-slate-200 rounded-xl overflow-hidden hover:shadow-md transition cursor-pointer flex flex-col"
                    onclick="openDetailModal('${item.id}', '${escapeHtml(item.title)}', '${escapeHtml(item.categoryName)}', '${escapeHtml(item.desc)}')"
                >
                    <div class="card-img-wrap aspect-[4/3] w-full">
                        <img
                            src="${getDriveImgUrl(item.id, 800)}"
                            alt="${escapeHtml(item.title)}"
                            loading="lazy"
                            class="w-full h-full object-cover"
                            onerror="handleDriveImgError(this, '${item.id}', 800)"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <h3 class="text-[12.5px] sm:text-sm font-bold text-slate-800 leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] sm:text-xs text-slate-500 mt-1.5 leading-snug">
                            ${item.categoryName}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        function filterWorks(category) {
            renderWorks(category);
            document.querySelectorAll('#workFilterTabs .cat-tab-btn').forEach(btn => {
                if (btn.dataset.cat === category) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });
        }

        /* =========================================================
           RENDER 10 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
           ========================================================= */
        function renderDanangProjects() {
            const container = document.getElementById('danangProjectsGrid');
            if (!container) return;

            container.innerHTML = danangProjects.map(item => `
                <article
                    class="project-card bg-white border border-slate-200 rounded-xl overflow-hidden hover:shadow-md transition cursor-pointer flex flex-col"
                    onclick="openDetailModal('${item.id}', '${escapeHtml(item.title)}', '${escapeHtml(item.location)}', '${escapeHtml(item.desc)}')"
                >
                    <div class="card-img-wrap aspect-[4/3] w-full">
                        <img
                            src="${getDriveImgUrl(item.id, 700)}"
                            alt="${escapeHtml(item.title)}"
                            loading="lazy"
                            class="w-full h-full object-cover"
                            onerror="handleDriveImgError(this, '${item.id}', 700)"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="text-[12px] sm:text-[13px] font-bold text-slate-800 leading-snug break-words">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] text-slate-500 mt-1.5 flex items-center gap-1">
                            <i class="fa-solid fa-location-dot text-amber-600 shrink-0"></i>
                            <span class="break-words">${item.location}</span>
                        </p>
                    </div>
                </article>
            `).join('');
        }

        /* =========================================================
           RENDER BÀI VIẾT TRANG CHỦ
           ========================================================= */
        function renderArticles() {
            const container = document.getElementById('articlesGrid');
            if (!container) return;

            container.innerHTML = articlesData.map(item => `
                <article
                    class="project-card bg-white border border-slate-200 rounded-xl overflow-hidden hover:shadow-md transition cursor-pointer flex flex-col"
                    onclick="openDetailModal('${item.imgId}', '${escapeHtml(item.title)}', 'Tin tức xây dựng • ${item.date}', '${escapeHtml(item.content)}')"
                >
                    <div class="card-img-wrap aspect-[16/10] w-full">
                        <img
                            src="${getDriveImgUrl(item.imgId, 700)}"
                            alt="${escapeHtml(item.title)}"
                            loading="lazy"
                            class="w-full h-full object-cover"
                            onerror="handleDriveImgError(this, '${item.imgId}', 700)"
                        >
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <p class="text-[11px] text-slate-400 mb-1">${item.date}</p>
                            <h3 class="text-[12.5px] sm:text-sm font-bold text-slate-800 leading-snug break-words mb-1.5">
                                ${item.title}
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                ${item.excerpt}
                            </p>
                        </div>
                        <span class="inline-block text-[11px] sm:text-xs font-semibold text-amber-600 mt-2.5">
                            Đọc chi tiết →
                        </span>
                    </div>
                </article>
            `).join('');
        }

        function escapeHtml(str) {
            return String(str)
                .replace(/&/g, '&amp;')
                .replace(/"/g, '&quot;')
                .replace(/'/g, '&#39;')
                .replace(/</g, '&lt;')
                .replace(/>/g, '&gt;');
        }

        /* =========================================================
           SLIDER 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT TRÊN ĐIỆN THOẠI
           ========================================================= */
        let currentSlide = 0;
        const totalSlides = 2;
        let sliderTimer = null;

        function updateSlider() {
            const track = document.getElementById('bannerTrack');
            if (!track) return;
            track.style.transform = `translateX(-${currentSlide * 100}%)`;

            const dots = document.querySelectorAll('.banner-dot');
            dots.forEach((dot, idx) => {
                if (idx === currentSlide) {
                    dot.classList.remove('w-2.5', 'bg-white/55');
                    dot.classList.add('w-6', 'bg-amber-400');
                } else {
                    dot.classList.remove('w-6', 'bg-amber-400');
                    dot.classList.add('w-2.5', 'bg-white/55');
                }
            });
        }

        function goToSlide(index) {
            currentSlide = (index + totalSlides) % totalSlides;
            updateSlider();
            resetSliderAutoplay();
        }

        function resetSliderAutoplay() {
            if (sliderTimer) clearInterval(sliderTimer);
            sliderTimer = setInterval(() => {
                currentSlide = (currentSlide + 1) % totalSlides;
                updateSlider();
            }, 5200);
        }

        /* =========================================================
           MODAL CHI TIẾT & FORM BÁO GIÁ (KHÔNG DÙNG ALERT)
           ========================================================= */
        function openDetailModal(imgId, title, category, desc) {
            const modal = document.getElementById('detailModal');
            const img = document.getElementById('modalImg');
            document.getElementById('modalTitle').textContent = title;
            document.getElementById('modalCategory').textContent = category;
            document.getElementById('modalDesc').textContent = desc;

            img.dataset.fallbackStep = '0';
            img.src = getDriveImgUrl(imgId, 1100);
            img.alt = title;
            img.onerror = function () {
                handleDriveImgError(this, imgId, 1100);
            };

            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeDetailModal() {
            const modal = document.getElementById('detailModal');
            modal.classList.add('hidden');
            modal.classList.remove('flex');
        }

        function prefillQuote(typeName) {
            const select = document.getElementById('qType');
            if (select) {
                select.value = typeName;
            }
        }

        function showToast(msg) {
            const box = document.getElementById('toastBox');
            const text = document.getElementById('toastMessage');
            text.textContent = msg;
            box.classList.remove('hidden');
            setTimeout(() => {
                box.classList.add('hidden');
            }, 4500);
        }

        function closeMobileMenu() {
            const menu = document.getElementById('mobileMenu');
            if (menu) menu.classList.add('hidden');
        }

        /* =========================================================
           KHỞI TẠO KHI TẢI TRANG
           ========================================================= */
        document.addEventListener('DOMContentLoaded', function () {
            renderWorks('all');
            renderDanangProjects();
            renderArticles();

            // Khởi động banner tự trượt
            updateSlider();
            resetSliderAutoplay();

            document.getElementById('prevBanner').addEventListener('click', () => goToSlide(currentSlide - 1));
            document.getElementById('nextBanner').addEventListener('click', () => goToSlide(currentSlide + 1));

            // Hỗ trợ vuốt cảm ứng trên điện thoại cho banner
            let touchStartX = 0;
            const heroSlider = document.getElementById('heroSlider');
            heroSlider.addEventListener('touchstart', (e) => {
                touchStartX = e.changedTouches[0].screenX;
            }, { passive: true });

            heroSlider.addEventListener('touchend', (e) => {
                const diff = e.changedTouches[0].screenX - touchStartX;
                if (Math.abs(diff) > 45) {
                    if (diff < 0) goToSlide(currentSlide + 1);
                    else goToSlide(currentSlide - 1);
                }
            }, { passive: true });

            // Toggle menu mobile
            document.getElementById('mobileMenuBtn').addEventListener('click', function () {
                document.getElementById('mobileMenu').classList.toggle('hidden');
            });

            // Xử lý gửi form yêu cầu & báo giá
            document.getElementById('quoteForm').addEventListener('submit', function (e) {
                e.preventDefault();
                const name = document.getElementById('qName').value.trim();
                const phone = document.getElementById('qPhone').value.trim();
                if (!name || !phone) {
                    showToast('Vui lòng nhập đầy đủ họ tên và số điện thoại liên hệ.');
                    return;
                }
                showToast(`Cảm ơn ${name}! TQCONS đã nhận yêu cầu báo giá và sẽ liên hệ qua số ${phone}.`);
                this.reset();
            });
        });
    </script>
</body>
</html>
