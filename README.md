<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH TƯ VẤN XÂY DỰNG VÀ THƯƠNG MẠI DỊCH VỤ HƯNG BÌNH - hungbinh.com.vn</title>
    <meta name="description" content="Công ty TNHH Tư vấn Xây dựng và Thương mại Dịch vụ Hưng Bình chuyên Tư vấn - Thiết kế - Thi công trọn gói Nhà phố, Biệt thự, Khách sạn, Căn hộ, Văn phòng tại Đà Nẵng. Hotline: 0903.176.334">
    
    <!-- Open Graph / Thumbnail Logo khi chia sẻ link hungbinh.com.vn -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://hungbinh.com.vn/">
    <meta property="og:site_name" content="hungbinh.com.vn">
    <meta property="og:title" content="CÔNG TY TNHH TƯ VẤN XÂY DỰNG VÀ THƯƠNG MẠI DỊCH VỤ HƯNG BÌNH">
    <meta property="og:description" content="Chuyên Thiết kế Kiến trúc - Thi công Xây dựng trọn gói - Nội thất Nhà phố, Biệt thự, Căn hộ, Khách sạn tại TP. Đà Nẵng. Đ/c: K12/H35/06/01 Trường Sơn, P. Cẩm Lệ, TP Đà Nẵng. ĐT: 0903.176.334">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk&sz=w1200">
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'%3E%3Crect width='100' height='100' rx='16' fill='%230d2745'/%3E%3Cpath d='M20 75V30L42 18V75H20Z' fill='%23d4942a'/%3E%3Cpath d='M48 75V38L80 24V75H48Z' fill='%23ffffff'/%3E%3Crect x='26' y='45' width='50' height='8' fill='%23d4942a'/%3E%3C/svg%3E">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Inter & Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&family=Montserrat:wght@600;700;800&display=swap" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        hbNavy: '#0d2745',
                        hbBlue: '#153e6b',
                        hbGold: '#d4942a',
                        hbGoldLight: '#f3b344',
                        hbGray: '#f5f7fa'
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                        heading: ['Montserrat', 'sans-serif']
                    },
                    maxWidth: {
                        'flatsome': '1500px'
                    }
                }
            }
        }
    </script>

    <style>
        /* Chống tràn viền tuyệt đối và không lệch sang phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            scroll-behavior: smooth;
            font-family: 'Inter', sans-serif;
            color: #1e293b;
            background-color: #ffffff;
        }

        /* Khung chuẩn 1500px cho UX Builder Flatsome trên máy tính */
        .ux-container {
            width: 100%;
            max-width: 1500px;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }
        @media (min-width: 1024px) {
            .ux-container {
                padding-left: 20px;
                padding-right: 20px;
            }
        }

        /* Tối ưu thanh danh mục máy tính: chữ nhỏ gọn, nằm trên 1 hàng (hoặc xuống hàng 2 nguyên cụm), tuyệt đối không gãy chữ */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: flex-end;
            gap: 2px 6px;
        }
        .desktop-nav-item {
            white-space: nowrap;
            font-size: 12px;
            font-weight: 600;
            letter-spacing: -0.01em;
            padding: 6px 8px;
            border-radius: 6px;
            color: #0d2745;
            transition: all 0.2s ease;
            line-height: 1.2;
        }
        @media (min-width: 1280px) {
            .desktop-nav-item {
                font-size: 12.5px;
                padding: 7px 10px;
            }
        }
        .desktop-nav-item:hover, .desktop-nav-item.active {
            color: #d4942a;
            background-color: rgba(212, 148, 42, 0.08);
        }

        /* Tiêu đề section kiểu Flatsome (Title Divider) */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: center;
            gap: 14px;
            margin-bottom: 8px;
        }
        .flatsome-section-title::before,
        .flatsome-section-title::after {
            content: "";
            flex: 1;
            max-width: 100px;
            height: 2px;
            background-color: #d4942a;
        }

        /* Tên sản phẩm không bao giờ bị cắt chữ hay tràn ra ngoài */
        .product-title-full {
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            line-height: 1.4;
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(212, 148, 42, 0.7); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(212, 148, 42, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(212, 148, 42, 0); }
        }
        .pulse-btn {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body class="bg-white text-slate-800 antialiased">

    <!-- =====================================================================
         TOP BAR FLATSOME (Thông tin công ty, Địa chỉ, SĐT, Website, Facebook)
         ===================================================================== -->
    <div class="bg-hbNavy text-white text-[11px] sm:text-xs py-2 border-b border-hbGold/30">
        <div class="ux-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <span class="font-semibold text-hbGoldLight">
                    <i class="fa-solid fa-building mr-1"></i>MST: 0402300370 - CÔNG TY TNHH TVXD & TMDV HƯNG BÌNH
                </span>
                <span class="hidden md:inline-flex items-center text-slate-200">
                    <i class="fa-solid fa-location-dot text-hbGold mr-1.5"></i>K12/H35/06/01 Trường Sơn, Phường Cẩm Lệ, TP Đà Nẵng
                </span>
            </div>
            <div class="flex items-center gap-3 ml-auto">
                <a href="tel:0903176334" class="hover:text-hbGoldLight transition font-semibold">
                    <i class="fa-solid fa-phone-volume text-hbGold mr-1"></i>0903.176.334
                </a>
                <span class="text-slate-500">|</span>
                <a href="https://hungbinh.com.vn" class="hover:text-hbGoldLight transition hidden sm:inline">
                    <i class="fa-solid fa-globe text-hbGold mr-1"></i>hungbinh.com.vn
                </a>
                <span class="text-slate-500 hidden sm:inline">|</span>
                <a href="https://www.facebook.com/sinh.dang.van.604746/" target="_blank" rel="noopener noreferrer" class="hover:text-hbGoldLight transition inline-flex items-center gap-1">
                    <i class="fa-brands fa-facebook text-blue-400"></i>
                    <span>FB Đặng Văn Sinh</span>
                </a>
            </div>
        </div>
    </div>

    <!-- =====================================================================
         HEADER FLATSOME (Logo mới gọn nhỏ + Danh mục 1 hàng, KHÔNG để nút gọi ngay)
         ===================================================================== -->
    <header class="sticky top-0 z-40 bg-white/95 backdrop-blur shadow-sm border-b border-slate-200">
        <div class="ux-container py-2.5 flex items-center justify-between gap-3">
            
            <!-- LOGO MỚI THIẾT KẾ GỌN NHỎ (Màu Navy & Vàng Đồng Kiến Trúc) -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group focus:outline-none">
                <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-hbNavy flex items-center justify-center shadow-sm border border-hbGold/60 shrink-0">
                    <svg class="w-6 h-6 sm:w-7 sm:h-7" viewBox="0 0 100 100" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <!-- Biểu tượng kiến trúc HB Hưng Bình -->
                        <path d="M16 82V26L42 14V82H16Z" fill="#d4942a"/>
                        <path d="M48 82V34L84 20V82H48Z" fill="#ffffff"/>
                        <rect x="24" y="48" width="52" height="9" rx="2" fill="#d4942a"/>
                        <rect x="56" y="40" width="8" height="8" fill="#0d2745"/>
                        <rect x="68" y="40" width="8" height="8" fill="#0d2745"/>
                        <rect x="56" y="62" width="8" height="10" fill="#0d2745"/>
                        <rect x="68" y="62" width="8" height="10" fill="#0d2745"/>
                        <path d="M10 84H90" stroke="#d4942a" stroke-width="5" stroke-linecap="round"/>
                    </svg>
                </div>
                <div class="leading-tight">
                    <div class="font-heading font-extrabold text-hbNavy text-sm sm:text-base tracking-tight">
                        HƯNG BÌNH <span class="text-hbGold font-bold text-xs sm:text-sm">CONS</span>
                    </div>
                    <div class="text-[9.5px] sm:text-[10.5px] text-slate-500 font-medium">
                        Tư Vấn Xây Dựng & TMDV
                    </div>
                </div>
            </a>

            <!-- MENU DANH MỤC MÁY TÍNH (Viết liền trên 1 hàng hoặc xuống hàng 2 nguyên mục, chữ nhỏ gọn, không gãy chữ) -->
            <nav class="hidden lg:block flex-1" aria-label="Menu chính">
                <ul class="desktop-nav-list">
                    <li><a href="#trang-chu" class="desktop-nav-item active">TRANG CHỦ</a></li>
                    <li><a href="#gioi-thieu" class="desktop-nav-item">GIỚI THIỆU</a></li>
                    <li><a href="#linh-vuc-hoat-dong" class="desktop-nav-item">LĨNH VỰC HOẠT ĐỘNG</a></li>
                    <li><a href="#cong-trinh-thuc-te" class="desktop-nav-item" onclick="filterCategory('all')">CÔNG TRÌNH THỰC TẾ</a></li>
                    <li><a href="#cong-trinh-thuc-te" class="desktop-nav-item" onclick="filterCategory('khach-san-can-ho')">KHÁCH SẠN - CĂN HỘ</a></li>
                    <li><a href="#cong-trinh-thuc-te" class="desktop-nav-item" onclick="filterCategory('biet-thu')">BIỆT THỰ</a></li>
                    <li><a href="#cong-trinh-thuc-te" class="desktop-nav-item" onclick="filterCategory('nha-pho')">NHÀ PHỐ</a></li>
                    <li><a href="#cong-trinh-thuc-te" class="desktop-nav-item" onclick="filterCategory('van-phong-noi-that')">VĂN PHÒNG - NỘI THẤT</a></li>
                    <li><a href="#du-an-da-nang" class="desktop-nav-item">DỰ ÁN ĐÀ NẴNG</a></li>
                    <li><a href="#bang-bao-gia" class="desktop-nav-item">BÁO GIÁ</a></li>
                    <li><a href="#doi-tac" class="desktop-nav-item">ĐỐI TÁC</a></li>
                    <li><a href="#tin-tuc" class="desktop-nav-item">TIN TỨC</a></li>
                    <li><a href="#lien-he-map" class="desktop-nav-item">LIÊN HỆ</a></li>
                </ul>
            </nav>

            <!-- NÚT MỞ MENU ĐIỆN THOẠI (Không để nút gọi ngay trên header để tránh tràn viền) -->
            <button id="mobileMenuBtn" type="button" onclick="toggleMobileMenu()" class="lg:hidden p-2 rounded-lg text-hbNavy hover:bg-slate-100 border border-slate-200 focus:outline-none" aria-label="Mở danh mục">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- THANH DANH MỤC NHANH TRÊN ĐIỆN THOẠI (Cuộn ngang gọn đẹp) -->
        <div class="lg:hidden bg-slate-50 border-t border-slate-200 overflow-x-auto no-scrollbar">
            <div class="flex items-center gap-1.5 px-3 py-1.5 whitespace-nowrap text-[11px] font-semibold text-hbNavy">
                <a href="#gioi-thieu" class="px-2.5 py-1 rounded bg-white border border-slate-200">Giới thiệu</a>
                <a href="#cong-trinh-thuc-te" onclick="filterCategory('khach-san-can-ho')" class="px-2.5 py-1 rounded bg-white border border-slate-200">Khách sạn - Căn hộ</a>
                <a href="#cong-trinh-thuc-te" onclick="filterCategory('biet-thu')" class="px-2.5 py-1 rounded bg-white border border-slate-200">Biệt thự</a>
                <a href="#cong-trinh-thuc-te" onclick="filterCategory('nha-pho')" class="px-2.5 py-1 rounded bg-white border border-slate-200">Nhà phố</a>
                <a href="#cong-trinh-thuc-te" onclick="filterCategory('van-phong-noi-that')" class="px-2.5 py-1 rounded bg-white border border-slate-200">Văn phòng - Nội thất</a>
                <a href="#du-an-da-nang" class="px-2.5 py-1 rounded bg-white border border-slate-200">Dự án Đà Nẵng</a>
                <a href="#bang-bao-gia" class="px-2.5 py-1 rounded bg-white border border-slate-200">Báo giá</a>
                <a href="#tin-tuc" class="px-2.5 py-1 rounded bg-white border border-slate-200">Tin tức</a>
            </div>
        </div>

        <!-- DRAWER MENU ĐIỆN THOẠI ĐẦY ĐỦ -->
        <div id="mobileMenuDrawer" class="hidden lg:hidden bg-white border-t border-slate-200 px-4 py-3 shadow-lg">
            <div class="grid grid-cols-2 gap-2 text-xs font-semibold text-hbNavy">
                <a href="#trang-chu" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-hbGold/10"><i class="fa-solid fa-house text-hbGold mr-1.5"></i>Trang chủ</a>
                <a href="#gioi-thieu" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-hbGold/10"><i class="fa-solid fa-building text-hbGold mr-1.5"></i>Giới thiệu</a>
                <a href="#linh-vuc-hoat-dong" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-hbGold/10"><i class="fa-solid fa-compass-drafting text-hbGold mr-1.5"></i>Lĩnh vực hoạt động</a>
                <a href="#cong-trinh-thuc-te" onclick="filterCategory('all'); toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-hbGold/10"><i class="fa-solid fa-city text-hbGold mr-1.5"></i>Công trình thực tế</a>
                <a href="#cong-trinh-thuc-te" onclick="filterCategory('khach-san-can-ho'); toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-hbGold/10"><i class="fa-solid fa-hotel text-hbGold mr-1.5"></i>Khách sạn - Căn hộ</a>
                <a href="#cong-trinh-thuc-te" onclick="filterCategory('biet-thu'); toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-hbGold/10"><i class="fa-solid fa-landmark text-hbGold mr-1.5"></i>Biệt thự</a>
                <a href="#cong-trinh-thuc-te" onclick="filterCategory('nha-pho'); toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-hbGold/10"><i class="fa-solid fa-house-chimney text-hbGold mr-1.5"></i>Nhà phố</a>
                <a href="#cong-trinh-thuc-te" onclick="filterCategory('van-phong-noi-that'); toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-hbGold/10"><i class="fa-solid fa-couch text-hbGold mr-1.5"></i>Văn phòng - Nội thất</a>
                <a href="#du-an-da-nang" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-hbGold/10"><i class="fa-solid fa-map-location-dot text-hbGold mr-1.5"></i>Dự án Đà Nẵng</a>
                <a href="#bang-bao-gia" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-hbGold/10"><i class="fa-solid fa-file-invoice-dollar text-hbGold mr-1.5"></i>Báo giá xây dựng</a>
                <a href="#doi-tac" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-hbGold/10"><i class="fa-solid fa-handshake text-hbGold mr-1.5"></i>Đối tác</a>
                <a href="#tin-tuc" onclick="toggleMobileMenu()" class="p-2 rounded bg-slate-50 hover:bg-hbGold/10"><i class="fa-solid fa-newspaper text-hbGold mr-1.5"></i>Tin tức</a>
            </div>
        </div>
    </header>

    <!-- =====================================================================
         BANNER SLIDER TỰ TRƯỢT (2 SLIDE KÍCH THƯỚC BẰNG NHAU)
         Thiết kế RIÊNG ảnh banner Máy Tính và ảnh banner Điện Thoại
         để chữ nhỏ gọn nằm trọn bên trong ảnh, tuyệt đối không tràn viền!
         ===================================================================== -->
    <section id="trang-chu" class="relative w-full bg-hbNavy overflow-hidden">
        <div class="ux-container py-3">
            <div class="relative w-full rounded-xl overflow-hidden shadow-md bg-hbNavy">
                
                <!-- ================= SLIDE 1 ================= -->
                <div class="banner-slide block transition-opacity duration-700" data-slide="0">
                    
                    <!-- BANNER 1 - GIAO DIỆN MÁY TÍNH (Chiều cao cố định 420px đồng nhất) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[420px] w-full bg-gradient-to-r from-[#0a1f38] via-[#12335a] to-[#0d2745] relative overflow-hidden px-10">
                        <!-- Nội dung chữ gọn trong khung trái -->
                        <div class="col-span-7 z-10 pr-6">
                            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-hbGold/20 border border-hbGold text-hbGoldLight text-xs font-semibold mb-3">
                                <span>HƯNG BÌNH CONSTRUCTION - HUNGBINH.COM.VN</span>
                            </div>
                            <h1 class="font-heading font-extrabold text-white text-2xl lg:text-3xl leading-snug mb-3">
                                CÔNG TY TNHH TƯ VẤN XÂY DỰNG VÀ THƯƠNG MẠI DỊCH VỤ <span class="text-hbGoldLight">HƯNG BÌNH</span>
                            </h1>
                            <p class="text-slate-200 text-xs lg:text-sm leading-relaxed mb-4 max-w-xl">
                                Chuyên Tư vấn – Thiết kế Kiến trúc – Thi công trọn gói Nhà phố, Biệt thự, Khách sạn, Căn hộ, Văn phòng tại Đà Nẵng. Cam kết: <strong class="text-hbGoldLight">An Toàn – Chất Lượng – Tiến Độ – Tận Tâm</strong>.
                            </p>
                            <div class="flex flex-wrap items-center gap-4 text-xs text-slate-200 bg-white/10 p-3 rounded-lg border border-white/15 max-w-xl">
                                <div><i class="fa-solid fa-location-dot text-hbGold mr-1.5"></i>K12/H35/06/01 Trường Sơn, Phường Cẩm Lệ, TP Đà Nẵng</div>
                                <div><i class="fa-solid fa-phone text-hbGold mr-1.5"></i>Hotline: <strong class="text-white">0903.176.334</strong></div>
                            </div>
                        </div>
                        <!-- Khung ảnh thực tế bên phải trên máy tính -->
                        <div class="col-span-5 z-10 grid grid-cols-2 gap-2.5 h-[340px]">
                            <div class="rounded-lg overflow-hidden border-2 border-hbGold/60 h-full">
                                <img src="https://drive.google.com/thumbnail?id=1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk&sz=w1000" 
                                     onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk=w1000';"
                                     alt="Công trình Hưng Bình Đà Nẵng 1" class="w-full h-full object-cover">
                            </div>
                            <div class="grid grid-rows-2 gap-2.5 h-full">
                                <div class="rounded-lg overflow-hidden border border-white/30 h-full">
                                    <img src="https://drive.google.com/thumbnail?id=1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW&sz=w1000"
                                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW=w1000';"
                                         alt="Công trình Hưng Bình Đà Nẵng 2" class="w-full h-full object-cover">
                                </div>
                                <div class="rounded-lg overflow-hidden border border-white/30 h-full">
                                    <img src="https://drive.google.com/thumbnail?id=1PjtEF4hlMU_42b438GmEQhYZTba75kRJ&sz=w1000"
                                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1PjtEF4hlMU_42b438GmEQhYZTba75kRJ=w1000';"
                                         alt="Công trình Hưng Bình Đà Nẵng 3" class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 1 - GIAO DIỆN ĐIỆN THOẠI RIÊNG BIỆT (Chiều cao 330px đồng nhất, chữ nhỏ gọn nằm trọn trong khung) -->
                    <div class="block md:hidden h-[330px] w-full relative bg-[#0c2340] overflow-hidden flex flex-col justify-between p-4">
                        <div class="grid grid-cols-2 gap-2 h-[135px] w-full shrink-0">
                            <img src="https://drive.google.com/thumbnail?id=1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk=w800';"
                                 alt="Xây dựng Hưng Bình" class="w-full h-full object-cover rounded-lg border border-hbGold/50">
                            <img src="https://drive.google.com/thumbnail?id=1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW=w800';"
                                 alt="Thi công Hưng Bình" class="w-full h-full object-cover rounded-lg border border-hbGold/50">
                        </div>
                        <div class="bg-hbNavy/95 border border-hbGold/40 rounded-lg p-3 text-center my-auto">
                            <div class="text-[10px] font-bold text-hbGoldLight uppercase tracking-wider mb-1">
                                HUNGBINH.COM.VN - XÂY DỰNG TRỌN GÓI ĐÀ NẴNG
                            </div>
                            <h2 class="font-heading font-bold text-white text-[13px] leading-snug mb-1.5">
                                CÔNG TY TNHH TƯ VẤN XÂY DỰNG & TMDV HƯNG BÌNH
                            </h2>
                            <p class="text-[11px] text-slate-200 leading-tight mb-1.5">
                                Thiết kế Kiến trúc – Thi công Nhà phố, Biệt thự, Căn hộ, Văn phòng
                            </p>
                            <div class="text-[10.5px] text-hbGoldLight font-semibold">
                                Đ/c: K12/H35/06/01 Trường Sơn, P. Cẩm Lệ, Đà Nẵng | ĐT: 0903.176.334
                            </div>
                        </div>
                    </div>
                </div>

                <!-- ================= SLIDE 2 ================= -->
                <div class="banner-slide hidden transition-opacity duration-700" data-slide="1">
                    
                    <!-- BANNER 2 - GIAO DIỆN MÁY TÍNH (Chiều cao cố định 420px bằng hệt Slide 1) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center h-[420px] w-full bg-gradient-to-r from-[#102a49] via-[#0d2745] to-[#173b66] relative overflow-hidden px-10">
                        <div class="col-span-7 z-10 pr-6">
                            <div class="inline-flex items-center gap-2 px-3 py-1 rounded-full bg-hbGold/20 border border-hbGold text-hbGoldLight text-xs font-semibold mb-3">
                                <span>GIẢI PHÁP KIẾN TRÚC & THI CÔNG TOÀN DIỆN</span>
                            </div>
                            <h2 class="font-heading font-extrabold text-white text-2xl lg:text-3xl leading-snug mb-3">
                                KIẾN TẠO TỔ ẤM BỀN VỮNG – TIÊU CHUẨN KỸ THUẬT CAO TẠI <span class="text-hbGoldLight">ĐÀ NẴNG</span>
                            </h2>
                            <p class="text-slate-200 text-xs lg:text-sm leading-relaxed mb-4 max-w-xl">
                                Đội ngũ Kiến trúc sư, Kỹ sư giàu kinh nghiệm trực tiếp giám sát từ phần móng, phần thô đến hoàn thiện nội thất. Minh bạch vật tư – Báo giá rõ ràng – Bảo hành dài hạn.
                            </p>
                            <div class="grid grid-cols-3 gap-3 max-w-lg text-center">
                                <div class="bg-white/10 rounded-lg p-2.5 border border-white/15">
                                    <div class="text-hbGoldLight font-bold text-sm">Thiết Kế 3D</div>
                                    <div class="text-[11px] text-slate-200">Tối ưu công năng</div>
                                </div>
                                <div class="bg-white/10 rounded-lg p-2.5 border border-white/15">
                                    <div class="text-hbGoldLight font-bold text-sm">Thi Công Chuẩn</div>
                                    <div class="text-[11px] text-slate-200">Đúng tiến độ 100%</div>
                                </div>
                                <div class="bg-white/10 rounded-lg p-2.5 border border-white/15">
                                    <div class="text-hbGoldLight font-bold text-sm">Bảo Hành Tận Tâm</div>
                                    <div class="text-[11px] text-slate-200">Hỗ trợ 24/7</div>
                                </div>
                            </div>
                        </div>
                        <div class="col-span-5 z-10 grid grid-cols-2 gap-2.5 h-[340px]">
                            <div class="rounded-lg overflow-hidden border-2 border-hbGold/60 h-full">
                                <img src="https://drive.google.com/thumbnail?id=1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA&sz=w1000"
                                     onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA=w1000';"
                                     alt="Dự án Hưng Bình Đà Nẵng 4" class="w-full h-full object-cover">
                            </div>
                            <div class="grid grid-rows-2 gap-2.5 h-full">
                                <div class="rounded-lg overflow-hidden border border-white/30 h-full">
                                    <img src="https://drive.google.com/thumbnail?id=1ng7_50Be4LsQqNa28KBn8rSCicz40ir9&sz=w1000"
                                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1ng7_50Be4LsQqNa28KBn8rSCicz40ir9=w1000';"
                                         alt="Dự án Hưng Bình Đà Nẵng 5" class="w-full h-full object-cover">
                                </div>
                                <div class="rounded-lg overflow-hidden border border-white/30 h-full">
                                    <img src="https://drive.google.com/thumbnail?id=1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS&sz=w1000"
                                         onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS=w1000';"
                                         alt="Dự án Hưng Bình Đà Nẵng 6" class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2 - GIAO DIỆN ĐIỆN THOẠI RIÊNG BIỆT (Chiều cao 330px đồng nhất) -->
                    <div class="block md:hidden h-[330px] w-full relative bg-[#0f2b4c] overflow-hidden flex flex-col justify-between p-4">
                        <div class="grid grid-cols-2 gap-2 h-[135px] w-full shrink-0">
                            <img src="https://drive.google.com/thumbnail?id=1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA=w800';"
                                 alt="Công trình thực tế Hưng Bình" class="w-full h-full object-cover rounded-lg border border-hbGold/50">
                            <img src="https://drive.google.com/thumbnail?id=1ng7_50Be4LsQqNa28KBn8rSCicz40ir9&sz=w800"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1ng7_50Be4LsQqNa28KBn8rSCicz40ir9=w800';"
                                 alt="Hoàn thiện nội thất Hưng Bình" class="w-full h-full object-cover rounded-lg border border-hbGold/50">
                        </div>
                        <div class="bg-hbNavy/95 border border-hbGold/40 rounded-lg p-3 text-center my-auto">
                            <div class="text-[10px] font-bold text-hbGoldLight uppercase tracking-wider mb-1">
                                UY TÍN – CHẤT LƯỢNG – ĐÚNG TIẾN ĐỘ
                            </div>
                            <h2 class="font-heading font-bold text-white text-[13px] leading-snug mb-1.5">
                                THIẾT KẾ & THI CÔNG NHÀ TRỌN GÓI TẠI ĐÀ NẴNG
                            </h2>
                            <p class="text-[11px] text-slate-200 leading-tight mb-1.5">
                                Miễn phí tư vấn khảo sát – Báo giá minh bạch – Bảo hành dài hạn
                            </p>
                            <div class="text-[10.5px] text-hbGoldLight font-semibold">
                                Hotline/Zalo: 0903.176.334 – Website: hungbinh.com.vn
                            </div>
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Banner Slider -->
                <button type="button" onclick="changeSlide(-1)" class="absolute left-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/40 hover:bg-hbGold text-white flex items-center justify-center transition z-20" aria-label="Slide trước">
                    <i class="fa-solid fa-chevron-left text-xs"></i>
                </button>
                <button type="button" onclick="changeSlide(1)" class="absolute right-2 top-1/2 -translate-y-1/2 w-8 h-8 rounded-full bg-black/40 hover:bg-hbGold text-white flex items-center justify-center transition z-20" aria-label="Slide tiếp">
                    <i class="fa-solid fa-chevron-right text-xs"></i>
                </button>

                <!-- Chấm chỉ báo Slide -->
                <div class="absolute bottom-2.5 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button type="button" onclick="goToSlide(0)" class="slide-dot w-6 h-2 rounded-full bg-hbGold transition-all" aria-label="Slide 1"></button>
                    <button type="button" onclick="goToSlide(1)" class="slide-dot w-2 h-2 rounded-full bg-white/60 transition-all" aria-label="Slide 2"></button>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION LĨNH VỰC HOẠT ĐỘNG (Theo mẫu tintruongthinh.com: Thiết kế - Thi công - Nội thất)
         ===================================================================== -->
    <section id="linh-vuc-hoat-dong" class="py-10 bg-hbGray border-b border-slate-200">
        <div class="ux-container">
            <div class="text-center mb-7">
                <div class="flatsome-section-title">
                    <h2 class="font-heading font-extrabold text-hbNavy text-lg sm:text-2xl uppercase">
                        LĨNH VỰC HOẠT ĐỘNG CHÍNH
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600">
                    Giải pháp đồng bộ từ Tư vấn – Thiết kế Kiến trúc đến Thi công Phần thô & Hoàn thiện Nội thất
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm hover:border-hbGold transition text-center">
                    <div class="w-12 h-12 mx-auto mb-3 rounded-xl bg-hbNavy text-hbGoldLight flex items-center justify-center text-xl">
                        <i class="fa-solid fa-compass-drafting"></i>
                    </div>
                    <h3 class="font-heading font-bold text-hbNavy text-xs sm:text-base mb-1.5 product-title-full">
                        Thiết Kế Kiến Trúc – Nội Thất
                    </h3>
                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                        Thiết kế mặt bằng công năng, phối cảnh 3D nhà phố, biệt thự, căn hộ, văn phòng hợp phong thủy.
                    </p>
                </div>

                <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm hover:border-hbGold transition text-center">
                    <div class="w-12 h-12 mx-auto mb-3 rounded-xl bg-hbNavy text-hbGoldLight flex items-center justify-center text-xl">
                        <i class="fa-solid fa-trowel-bricks"></i>
                    </div>
                    <h3 class="font-heading font-bold text-hbNavy text-xs sm:text-base mb-1.5 product-title-full">
                        Thi Công Phần Thô
                    </h3>
                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                        Thi công nền móng, kết cấu bê tông cốt thép, xây tô đúng tiêu chuẩn kỹ thuật xây dựng Việt Nam.
                    </p>
                </div>

                <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm hover:border-hbGold transition text-center">
                    <div class="w-12 h-12 mx-auto mb-3 rounded-xl bg-hbNavy text-hbGoldLight flex items-center justify-center text-xl">
                        <i class="fa-solid fa-paint-roller"></i>
                    </div>
                    <h3 class="font-heading font-bold text-hbNavy text-xs sm:text-base mb-1.5 product-title-full">
                        Thi Công Hoàn Thiện Trọn Gói
                    </h3>
                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                        Ốp lát, sơn bả, trần thạch cao, cửa nhôm kính, hệ thống điện nước M&E chìa khóa trao tay.
                    </p>
                </div>

                <div class="bg-white rounded-xl p-4 sm:p-5 border border-slate-200 shadow-sm hover:border-hbGold transition text-center">
                    <div class="w-12 h-12 mx-auto mb-3 rounded-xl bg-hbNavy text-hbGoldLight flex items-center justify-center text-xl">
                        <i class="fa-solid fa-couch"></i>
                    </div>
                    <h3 class="font-heading font-bold text-hbNavy text-xs sm:text-base mb-1.5 product-title-full">
                        Thi Công Nội Thất & Cải Tạo
                    </h3>
                    <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                        Sản xuất lắp đặt nội thất gỗ, cải tạo nâng tầng, sửa chữa nhà ở, khách sạn, mặt bằng kinh doanh.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION GIỚI THIỆU & 6 THẾ MẠNH (Theo cấu trúc tintruongthinh.com)
         ===================================================================== -->
    <section id="gioi-thieu" class="py-12 bg-white border-b border-slate-200">
        <div class="ux-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center mb-10">
                <div class="lg:col-span-7">
                    <div class="text-xs font-bold text-hbGold uppercase tracking-wider mb-1">
                        VỀ CHÚNG TÔI - HUNGBINH.COM.VN
                    </div>
                    <h2 class="font-heading font-extrabold text-hbNavy text-xl sm:text-2xl mb-4 leading-snug">
                        CÔNG TY TNHH TƯ VẤN XÂY DỰNG VÀ THƯƠNG MẠI DỊCH VỤ HƯNG BÌNH
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-3">
                        <strong>HƯNG BÌNH</strong> chuyên Tư vấn – Thiết kế – Xây dựng – Nội thất các công trình <strong>Khách sạn, Biệt thự, Căn hộ, Văn phòng, Nhà phố</strong> tại TP. Đà Nẵng và khu vực miền Trung. Với tiêu chí <em>“Nhà ở Gia đình – Tiêu chuẩn Công trình”</em>, chúng tôi luôn mang đến trải nghiệm chuyên nghiệp, minh bạch và tận tâm cho Quý Khách hàng.
                    </p>
                    <p class="text-xs sm:text-sm text-slate-700 leading-relaxed mb-4">
                        Đặt chữ <strong>“TÂM”</strong> và chữ <strong>“TÍN”</strong> lên hàng đầu để mỗi công trình khi bàn giao đều đạt chuẩn: <strong>“AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – SỰ HÀI LÒNG CỦA KHÁCH HÀNG”</strong>.
                    </p>
                    <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 bg-hbGray p-4 rounded-xl border border-slate-200 text-xs">
                        <div><strong class="text-hbNavy">Tên doanh nghiệp:</strong> Công ty TNHH Tư vấn Xây dựng và Thương mại Dịch vụ Hưng Bình</div>
                        <div><strong class="text-hbNavy">Mã số thuế:</strong> 0402300370</div>
                        <div><strong class="text-hbNavy">Đại diện pháp luật:</strong> Ông Đặng Văn Sinh</div>
                        <div><strong class="text-hbNavy">Hotline/Zalo:</strong> 0903.176.334</div>
                        <div class="sm:col-span-2"><strong class="text-hbNavy">Địa chỉ trụ sở:</strong> K12/H35/06/01 Trường Sơn, Phường Cẩm Lệ, TP Đà Nẵng</div>
                    </div>
                </div>

                <div class="lg:col-span-5 grid grid-cols-2 gap-3">
                    <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm h-48 sm:h-56">
                        <img src="https://drive.google.com/thumbnail?id=1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3=w1000';"
                             alt="Hình ảnh thực tế Hưng Bình" class="w-full h-full object-cover">
                    </div>
                    <div class="rounded-xl overflow-hidden border border-slate-200 shadow-sm h-48 sm:h-56">
                        <img src="https://drive.google.com/thumbnail?id=1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF=w1000';"
                             alt="Thi công thực tế Hưng Bình" class="w-full h-full object-cover">
                    </div>
                </div>
            </div>

            <!-- 6 Thế mạnh của Hưng Bình (Giống mẫu Tín Trường Thịnh) -->
            <div class="grid grid-cols-2 md:grid-cols-3 gap-3 sm:gap-5">
                <div class="p-4 rounded-xl bg-hbGray border border-slate-200">
                    <div class="text-hbGold text-lg mb-1"><i class="fa-solid fa-user-check"></i></div>
                    <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">1. Đội ngũ KTS, Kỹ sư chuyên nghiệp</h3>
                    <p class="text-[11px] sm:text-xs text-slate-600">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư hiện trường và thợ lành nghề lâu năm tại Đà Nẵng.</p>
                </div>
                <div class="p-4 rounded-xl bg-hbGray border border-slate-200">
                    <div class="text-hbGold text-lg mb-1"><i class="fa-solid fa-layer-group"></i></div>
                    <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">2. Cập nhật xu hướng thiết kế mới</h3>
                    <p class="text-[11px] sm:text-xs text-slate-600">Ứng dụng giải pháp thông gió, lấy sáng tự nhiên và vật liệu xây dựng bền bỉ với khí hậu miền Trung.</p>
                </div>
                <div class="p-4 rounded-xl bg-hbGray border border-slate-200">
                    <div class="text-hbGold text-lg mb-1"><i class="fa-solid fa-clipboard-check"></i></div>
                    <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">3. Giám sát tiến độ chuẩn xác</h3>
                    <p class="text-[11px] sm:text-xs text-slate-600">Báo cáo hình ảnh/video nghiệm thu từng giai đoạn thi công để Chủ đầu tư theo dõi mọi lúc mọi nơi.</p>
                </div>
                <div class="p-4 rounded-xl bg-hbGray border border-slate-200">
                    <div class="text-hbGold text-lg mb-1"><i class="fa-solid fa-shield-halved"></i></div>
                    <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">4. Bảo hành công trình lâu dài</h3>
                    <p class="text-[11px] sm:text-xs text-slate-600">Chế độ hậu mãi tận tâm, bảo hành kết cấu dài hạn và hỗ trợ kiểm tra định kỳ nhanh chóng.</p>
                </div>
                <div class="p-4 rounded-xl bg-hbGray border border-slate-200">
                    <div class="text-hbGold text-lg mb-1"><i class="fa-solid fa-scale-balanced"></i></div>
                    <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">5. Chi phí hợp lý – Không phát sinh</h3>
                    <p class="text-[11px] sm:text-xs text-slate-600">Dự toán bóc tách chi tiết từng hạng mục vật tư, cam kết đúng chủng loại đã ký kết.</p>
                </div>
                <div class="p-4 rounded-xl bg-hbGray border border-slate-200">
                    <div class="text-hbGold text-lg mb-1"><i class="fa-solid fa-headset"></i></div>
                    <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">6. Hỗ trợ tư vấn miễn phí 24/7</h3>
                    <p class="text-[11px] sm:text-xs text-slate-600">Khảo sát thực tế tận nơi tại Đà Nẵng và tư vấn phương án thiết kế, xin phép xây dựng miễn phí.</p>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION DANH MỤC SẢN PHẨM & CÔNG TRÌNH THỰC TẾ (18 ẢNH GOOGLE DRIVE)
         - Chữ danh mục ở trang chủ nhỏ gọn, đẹp trên máy tính & điện thoại
         - Sản phẩm chia 2 cột trên điện thoại, 4 cột trên máy tính
         - KHÔNG để nhãn dán đè lên ảnh
         - Tên sản phẩm hiển thị đầy đủ 100%, không bị cắt hay tràn chữ
         ===================================================================== -->
    <section id="cong-trinh-thuc-te" class="py-12 bg-hbGray border-b border-slate-200">
        <div class="ux-container">
            <div class="text-center mb-6">
                <div class="flatsome-section-title">
                    <h2 class="font-heading font-extrabold text-hbNavy text-lg sm:text-2xl uppercase">
                        DANH MỤC SẢN PHẨM & CÔNG TRÌNH THỰC TẾ
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600">
                    Hình ảnh thực tế 100% từ hồ sơ thi công và thiết kế của Công ty Xây dựng Hưng Bình
                </p>
            </div>

            <!-- Thanh nút lọc danh mục nhỏ gọn, viết liền không gãy chữ -->
            <div class="flex flex-wrap items-center justify-center gap-1.5 sm:gap-2 mb-7">
                <button type="button" onclick="filterCategory('all')" data-cat-btn="all" class="cat-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold whitespace-nowrap bg-hbNavy text-white border border-hbNavy transition">
                    Tất cả (18)
                </button>
                <button type="button" onclick="filterCategory('khach-san-can-ho')" data-cat-btn="khach-san-can-ho" class="cat-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold whitespace-nowrap bg-white text-hbNavy border border-slate-300 hover:border-hbGold transition">
                    Khách sạn – Căn hộ – Phòng trọ
                </button>
                <button type="button" onclick="filterCategory('biet-thu')" data-cat-btn="biet-thu" class="cat-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold whitespace-nowrap bg-white text-hbNavy border border-slate-300 hover:border-hbGold transition">
                    Biệt thự
                </button>
                <button type="button" onclick="filterCategory('nha-pho')" data-cat-btn="nha-pho" class="cat-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold whitespace-nowrap bg-white text-hbNavy border border-slate-300 hover:border-hbGold transition">
                    Nhà phố
                </button>
                <button type="button" onclick="filterCategory('van-phong-noi-that')" data-cat-btn="van-phong-noi-that" class="cat-filter-btn px-3 py-1.5 rounded-lg text-xs font-semibold whitespace-nowrap bg-white text-hbNavy border border-slate-300 hover:border-hbGold transition">
                    Văn phòng & Thi công Nội thất
                </button>
            </div>

            <!-- LƯỚI 18 SẢN PHẨM / CÔNG TRÌNH THỰC TẾ (2 cột trên điện thoại, 4 cột trên máy tính, KHÔNG nhãn dán) -->
            <div id="productGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-3 sm:gap-5">
                
                <!-- 1. File ID: 1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="nha-pho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk', 'Thi Công Nhà Phố Hiện Đại 3 Tầng Mặt Tiền Thoáng Đãng')">
                        <img src="https://drive.google.com/thumbnail?id=1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk=w1000';"
                             alt="Thi Công Nhà Phố Hiện Đại 3 Tầng Mặt Tiền Thoáng Đãng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Thi Công Nhà Phố Hiện Đại 3 Tầng Mặt Tiền Thoáng Đãng
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Nhà phố | Thiết kế & Thi công trọn gói
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 2. File ID: 1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="nha-pho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW', 'Mẫu Nhà Phố Lệch Tầng Kết Hợp Không Gian Xanh Đà Nẵng')">
                        <img src="https://drive.google.com/thumbnail?id=1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1tHGEqsuxKkCkoDofSK_nE70LBMIvGuVW=w1000';"
                             alt="Mẫu Nhà Phố Lệch Tầng Kết Hợp Không Gian Xanh Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Mẫu Nhà Phố Lệch Tầng Kết Hợp Không Gian Xanh Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Nhà phố | Kiến trúc & Hoàn thiện
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 3. File ID: 1PjtEF4hlMU_42b438GmEQhYZTba75kRJ -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="biet-thu">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1PjtEF4hlMU_42b438GmEQhYZTba75kRJ', 'Thiết Kế & Thi Công Biệt Thự Phố 2 Mặt Tiền Sang Trọng')">
                        <img src="https://drive.google.com/thumbnail?id=1PjtEF4hlMU_42b438GmEQhYZTba75kRJ&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1PjtEF4hlMU_42b438GmEQhYZTba75kRJ=w1000';"
                             alt="Thiết Kế & Thi Công Biệt Thự Phố 2 Mặt Tiền Sang Trọng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Thiết Kế & Thi Công Biệt Thự Phố 2 Mặt Tiền Sang Trọng
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Biệt thự | Thi công trọn gói
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 4. File ID: 1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="khach-san-can-ho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA', 'Tòa Nhà Căn Hộ Cho Thuê & Khách Sạn Mini Hiện Đại')">
                        <img src="https://drive.google.com/thumbnail?id=1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA=w1000';"
                             alt="Tòa Nhà Căn Hộ Cho Thuê & Khách Sạn Mini Hiện Đại"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Tòa Nhà Căn Hộ Cho Thuê & Khách Sạn Mini Hiện Đại
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Khách sạn – Căn hộ – Phòng trọ
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 5. File ID: 1ng7_50Be4LsQqNa28KBn8rSCicz40ir9 -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="biet-thu">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1ng7_50Be4LsQqNa28KBn8rSCicz40ir9', 'Biệt Thự Nghỉ Dưỡng Sân Vườn Phong Cách Hiện Đại')">
                        <img src="https://drive.google.com/thumbnail?id=1ng7_50Be4LsQqNa28KBn8rSCicz40ir9&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1ng7_50Be4LsQqNa28KBn8rSCicz40ir9=w1000';"
                             alt="Biệt Thự Nghỉ Dưỡng Sân Vườn Phong Cách Hiện Đại"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Biệt Thự Nghỉ Dưỡng Sân Vườn Phong Cách Hiện Đại
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Biệt thự | Thiết kế & Thi công
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 6. File ID: 1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="nha-pho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS', 'Thi Công Phần Thô & Hoàn Thiện Nhà Phố Khu Đô Thị Hòa Xuân')">
                        <img src="https://drive.google.com/thumbnail?id=1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS=w1000';"
                             alt="Thi Công Phần Thô & Hoàn Thiện Nhà Phố Khu Đô Thị Hòa Xuân"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Thi Công Phần Thô & Hoàn Thiện Nhà Phố Khu Đô Thị Hòa Xuân
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Nhà phố | Thi công thực tế
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 7. File ID: 1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3 -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="khach-san-can-ho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3', 'Công Trình Căn Hộ Dịch Vụ Cao Cấp Kết Hợp Kinh Doanh')">
                        <img src="https://drive.google.com/thumbnail?id=1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1stTZuL2puyTkD_2WrDXjg2Yz2NAYyHV3=w1000';"
                             alt="Công Trình Căn Hộ Dịch Vụ Cao Cấp Kết Hợp Kinh Doanh"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Công Trình Căn Hộ Dịch Vụ Cao Cấp Kết Hợp Kinh Doanh
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Khách sạn – Căn hộ – Phòng trọ
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 8. File ID: 1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="van-phong-noi-that">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF', 'Hoàn Thiện Nội Thất Phòng Khách & Bếp Liền Kề Hiện Đại')">
                        <img src="https://drive.google.com/thumbnail?id=1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF=w1000';"
                             alt="Hoàn Thiện Nội Thất Phòng Khách & Bếp Liền Kề Hiện Đại"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Hoàn Thiện Nội Thất Phòng Khách & Bếp Liền Kề Hiện Đại
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Văn phòng & Thi công Nội thất
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 9. File ID: 1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="nha-pho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi', 'Nhà Phố 3 Tầng 1 Tum Phong Cách Tối Giản Tại Quận Cẩm Lệ')">
                        <img src="https://drive.google.com/thumbnail?id=1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi=w1000';"
                             alt="Nhà Phố 3 Tầng 1 Tum Phong Cách Tối Giản Tại Quận Cẩm Lệ"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Nhà Phố 3 Tầng 1 Tum Phong Cách Tối Giản Tại Quận Cẩm Lệ
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Nhà phố | Xây nhà trọn gói
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 10. File ID: 1A271daJ-s3V5Ws6LRrcDIJ9-Il34FXLq -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="biet-thu">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1A271daJ-s3V5Ws6LRrcDIJ9-Il34FXLq', 'Biệt Thự Mái Thái Kết Hợp Sân Vườn Rộng Rãi Thoáng Mát')">
                        <img src="https://drive.google.com/thumbnail?id=1A271daJ-s3V5Ws6LRrcDIJ9-Il34FXLq&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1A271daJ-s3V5Ws6LRrcDIJ9-Il34FXLq=w1000';"
                             alt="Biệt Thự Mái Thái Kết Hợp Sân Vườn Rộng Rãi Thoáng Mát"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Biệt Thự Mái Thái Kết Hợp Sân Vườn Rộng Rãi Thoáng Mát
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Biệt thự | Tư vấn & Thi công
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 11. File ID: 1G5cVihRDvTKhbx_tNG5uDoSQtvzc0TTt -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="khach-san-can-ho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1G5cVihRDvTKhbx_tNG5uDoSQtvzc0TTt', 'Thiết Kế Thi Công Khu Phòng Trọ Cao Cấp & Căn Hộ Studio')">
                        <img src="https://drive.google.com/thumbnail?id=1G5cVihRDvTKhbx_tNG5uDoSQtvzc0TTt&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1G5cVihRDvTKhbx_tNG5uDoSQtvzc0TTt=w1000';"
                             alt="Thiết Kế Thi Công Khu Phòng Trọ Cao Cấp & Căn Hộ Studio"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Thiết Kế Thi Công Khu Phòng Trọ Cao Cấp & Căn Hộ Studio
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Khách sạn – Căn hộ – Phòng trọ
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 12. File ID: 1fqJikC677z_7x28XQaAx3VQD7zqWtiUy -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="van-phong-noi-that">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1fqJikC677z_7x28XQaAx3VQD7zqWtiUy', 'Thiết Kế & Thi Công Trụ Sở Văn Phòng Công Ty Kết Hợp Showroom')">
                        <img src="https://drive.google.com/thumbnail?id=1fqJikC677z_7x28XQaAx3VQD7zqWtiUy&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1fqJikC677z_7x28XQaAx3VQD7zqWtiUy=w1000';"
                             alt="Thiết Kế & Thi Công Trụ Sở Văn Phòng Công Ty Kết Hợp Showroom"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Thiết Kế & Thi Công Trụ Sở Văn Phòng Công Ty Kết Hợp Showroom
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Văn phòng & Thi công Nội thất
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 13. File ID: 1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="nha-pho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x', 'Thi Công Kết Cấu Phần Thô Nhà Phố Đảm Bảo Tiêu Chuẩn Kỹ Thuật')">
                        <img src="https://drive.google.com/thumbnail?id=1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x=w1000';"
                             alt="Thi Công Kết Cấu Phần Thô Nhà Phố Đảm Bảo Tiêu Chuẩn Kỹ Thuật"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Thi Công Kết Cấu Phần Thô Nhà Phố Đảm Bảo Tiêu Chuẩn Kỹ Thuật
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Nhà phố | Thi công phần thô
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 14. File ID: 11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="van-phong-noi-that">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ', 'Thi Công Nội Thất Gỗ Công Nghiệp Cao Cấp Phòng Ngủ Master')">
                        <img src="https://drive.google.com/thumbnail?id=11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/11oZAhO2AsbGFYm1pdsPS5Vtgkd9IP2yZ=w1000';"
                             alt="Thi Công Nội Thất Gỗ Công Nghiệp Cao Cấp Phòng Ngủ Master"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Thi Công Nội Thất Gỗ Công Nghiệp Cao Cấp Phòng Ngủ Master
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Văn phòng & Thi công Nội thất
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 15. File ID: 1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="nha-pho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw', 'Hoàn Thiện Mặt Tiền Nhà Phố Ốp Đá Tự Nhiên Kết Hợp Lam Gỗ')">
                        <img src="https://drive.google.com/thumbnail?id=1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw=w1000';"
                             alt="Hoàn Thiện Mặt Tiền Nhà Phố Ốp Đá Tự Nhiên Kết Hợp Lam Gỗ"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Hoàn Thiện Mặt Tiền Nhà Phố Ốp Đá Tự Nhiên Kết Hợp Lam Gỗ
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Nhà phố | Thi công hoàn thiện
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 16. File ID: 1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="biet-thu">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK', 'Cải Tạo & Nâng Cấp Biệt Thự Gia Đình Sang Trọng Tại Đà Nẵng')">
                        <img src="https://drive.google.com/thumbnail?id=1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1QcvBpsk1aY6aHVHIVrZs9ALP17TUWfkK=w1000';"
                             alt="Cải Tạo & Nâng Cấp Biệt Thự Gia Đình Sang Trọng Tại Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Cải Tạo & Nâng Cấp Biệt Thự Gia Đình Sang Trọng Tại Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Biệt thự | Cải tạo & Hoàn thiện
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 17. File ID: 1TWxo6uXoJMty8Qsbu4z8HFR5TeLvWph1 -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="khach-san-can-ho">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1TWxo6uXoJMty8Qsbu4z8HFR5TeLvWph1', 'Thi Công Trọn Gói Căn Hộ Dịch Vụ Cho Thuê Gần Biển Đà Nẵng')">
                        <img src="https://drive.google.com/thumbnail?id=1TWxo6uXoJMty8Qsbu4z8HFR5TeLvWph1&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1TWxo6uXoJMty8Qsbu4z8HFR5TeLvWph1=w1000';"
                             alt="Thi Công Trọn Gói Căn Hộ Dịch Vụ Cho Thuê Gần Biển Đà Nẵng"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Thi Công Trọn Gói Căn Hộ Dịch Vụ Cho Thuê Gần Biển Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Khách sạn – Căn hộ – Phòng trọ
                            </p>
                        </div>
                    </div>
                </div>

                <!-- 18. File ID: 1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ -->
                <div class="product-card bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm hover:shadow-md transition flex flex-col" data-category="van-phong-noi-that">
                    <div class="aspect-[4/3] w-full overflow-hidden bg-slate-100 cursor-pointer" onclick="openLightbox('1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ', 'Hoàn Thiện Không Gian Nội Thất Văn Phòng Làm Việc Chuyên Nghiệp')">
                        <img src="https://drive.google.com/thumbnail?id=1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ&sz=w1000"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1nv_lSxn0mu-71NGKss3abLOuEMcB-bkQ=w1000';"
                             alt="Hoàn Thiện Không Gian Nội Thất Văn Phòng Làm Việc Chuyên Nghiệp"
                             class="w-full h-full object-cover hover:scale-105 transition duration-300" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                                Hoàn Thiện Không Gian Nội Thất Văn Phòng Làm Việc Chuyên Nghiệp
                            </h3>
                            <p class="text-[11px] text-slate-500 product-title-full">
                                Danh mục: Văn phòng & Thi công Nội thất
                            </p>
                        </div>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION DANH MỤC CÁC DỰ ÁN Ở ĐÀ NẴNG (Ngoài trang chủ, chia 2 cột mobile)
         ===================================================================== -->
    <section id="du-an-da-nang" class="py-12 bg-white border-b border-slate-200">
        <div class="ux-container">
            <div class="text-center mb-7">
                <div class="flatsome-section-title">
                    <h2 class="font-heading font-extrabold text-hbNavy text-lg sm:text-2xl uppercase">
                        DỰ ÁN TIÊU BIỂU TẠI TP. ĐÀ NẴNG
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600">
                    Các công trình thực tế do Hưng Bình tư vấn, thiết kế và thi công tại các quận Cẩm Lệ, Hải Châu, Sơn Trà, Ngũ Hành Sơn, Liên Chiểu
                </p>
            </div>

            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <div class="bg-hbGray rounded-xl overflow-hidden border border-slate-200 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi&sz=w800"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1cmI83UnySYJ5Zt1I8A0kB0n94W4XgXgi=w800';"
                             alt="Dự án Nhà Phố Phường Cẩm Lệ Đà Nẵng" class="w-full h-full object-cover" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4">
                        <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                            Dự Án Nhà Phố 3 Tầng Đường Trường Sơn – Quận Cẩm Lệ, Đà Nẵng
                        </h3>
                        <p class="text-[11px] text-slate-600 product-title-full">
                            Quy mô: 5x20m (3 tầng) | Hạng mục: Thiết kế & Thi công trọn gói
                        </p>
                    </div>
                </div>

                <div class="bg-hbGray rounded-xl overflow-hidden border border-slate-200 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS&sz=w800"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1m0Hxp_Pf-urM1DxMd9GP-iuahuQfiznS=w800';"
                             alt="Dự án Khu Đô Thị Hòa Xuân Đà Nẵng" class="w-full h-full object-cover" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4">
                        <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                            Dự Án Nhà Phố Hiện Đại Khu Đô Thị Nam Hòa Xuân – Đà Nẵng
                        </h3>
                        <p class="text-[11px] text-slate-600 product-title-full">
                            Quy mô: 5x22m | Hạng mục: Thi công phần thô & Hoàn thiện nội thất
                        </p>
                    </div>
                </div>

                <div class="bg-hbGray rounded-xl overflow-hidden border border-slate-200 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA&sz=w800"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA=w800';"
                             alt="Dự án Căn hộ Sơn Trà Đà Nẵng" class="w-full h-full object-cover" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4">
                        <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                            Dự Án Căn Hộ Cho Thuê 5 Tầng Quận Sơn Trà – TP. Đà Nẵng
                        </h3>
                        <p class="text-[11px] text-slate-600 product-title-full">
                            Quy mô: 12 căn hộ dịch vụ | Hạng mục: Tư vấn thiết kế & Thi công
                        </p>
                    </div>
                </div>

                <div class="bg-hbGray rounded-xl overflow-hidden border border-slate-200 flex flex-col">
                    <div class="aspect-[4/3] w-full overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1PjtEF4hlMU_42b438GmEQhYZTba75kRJ&sz=w800"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1PjtEF4hlMU_42b438GmEQhYZTba75kRJ=w800';"
                             alt="Dự án Biệt thự Ngũ Hành Sơn Đà Nẵng" class="w-full h-full object-cover" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4">
                        <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1 product-title-full">
                            Dự Án Biệt Thự Gia Đình 2 Mặt Tiền Quận Ngũ Hành Sơn – Đà Nẵng
                        </h3>
                        <p class="text-[11px] text-slate-600 product-title-full">
                            Quy mô: 280m2 sàn | Hạng mục: Chìa khóa trao tay & Sân vườn
                        </p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION BẢNG BÁO GIÁ THAM KHẢO & FORM YÊU CẦU BÁO GIÁ TRANG CHỦ
         (Lấy theo danh mục Báo giá của web mẫu tintruongthinh.com)
         ===================================================================== -->
    <section id="bang-bao-gia" class="py-12 bg-hbNavy text-white">
        <div class="ux-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
                
                <!-- Cột trái: 4 Gói Báo Giá Xây Dựng (Chia 2 cột trên điện thoại) -->
                <div class="lg:col-span-7">
                    <div class="text-xs font-bold text-hbGoldLight uppercase tracking-wider mb-1">
                        MINH BẠCH – CHI TIẾT – RÕ RÀNG VẬT TƯ
                    </div>
                    <h2 class="font-heading font-extrabold text-white text-xl sm:text-2xl mb-5">
                        BẢNG BÁO GIÁ DỊCH VỤ THIẾT KẾ & THI CÔNG HƯNG BÌNH
                    </h2>

                    <div class="grid grid-cols-2 gap-3 sm:gap-4">
                        <div class="bg-white/10 border border-white/15 rounded-xl p-4">
                            <div class="text-hbGoldLight text-xs font-bold uppercase mb-1">Gói 01</div>
                            <h3 class="font-bold text-white text-xs sm:text-base mb-2 product-title-full">
                                Báo Giá Thiết Kế Kiến Trúc & Nội Thất
                            </h3>
                            <div class="text-hbGoldLight font-extrabold text-sm sm:text-lg mb-2">
                                120.000đ – 180.000đ/m²
                            </div>
                            <ul class="text-[11px] sm:text-xs text-slate-200 space-y-1">
                                <li>• Hồ sơ kiến trúc, kết cấu, điện nước</li>
                                <li>• Phối cảnh 3D mặt tiền & nội thất</li>
                                <li>• Giảm 100% phí thiết kế khi thi công trọn gói</li>
                            </ul>
                        </div>

                        <div class="bg-white/10 border border-white/15 rounded-xl p-4">
                            <div class="text-hbGoldLight text-xs font-bold uppercase mb-1">Gói 02</div>
                            <h3 class="font-bold text-white text-xs sm:text-base mb-2 product-title-full">
                                Báo Giá Thi Công Phần Thô & Nhân Công Hoàn Thiện
                            </h3>
                            <div class="text-hbGoldLight font-extrabold text-sm sm:text-lg mb-2">
                                3.500.000đ – 3.900.000đ/m²
                            </div>
                            <ul class="text-[11px] sm:text-xs text-slate-200 space-y-1">
                                <li>• Vật tư chuẩn: Thép Hòa Phát, Xi măng Sông Gianh</li>
                                <li>• Nhân công xây tô, ốp lát, lắp đặt điện nước</li>
                                <li>• Bảo hành kết cấu công trình lên đến 5 năm</li>
                            </ul>
                        </div>

                        <div class="bg-white/10 border border-white/15 rounded-xl p-4">
                            <div class="text-hbGoldLight text-xs font-bold uppercase mb-1">Gói 03</div>
                            <h3 class="font-bold text-white text-xs sm:text-base mb-2 product-title-full">
                                Báo Giá Thi Công Hoàn Thiện Công Trình
                            </h3>
                            <div class="text-hbGoldLight font-extrabold text-sm sm:text-lg mb-2">
                                2.200.000đ – 3.200.000đ/m²
                            </div>
                            <ul class="text-[11px] sm:text-xs text-slate-200 space-y-1">
                                <li>• Gạch ốp lát, đá cầu thang, trần thạch cao</li>
                                <li>• Sơn nước Dulux/Jotun, cửa nhôm Xingfa</li>
                                <li>• Thiết bị vệ sinh Inax/Toto chính hãng</li>
                            </ul>
                        </div>

                        <div class="bg-white/10 border border-hbGold rounded-xl p-4">
                            <div class="text-hbGoldLight text-xs font-bold uppercase mb-1">Gói 04 - Phổ biến</div>
                            <h3 class="font-bold text-white text-xs sm:text-base mb-2 product-title-full">
                                Báo Giá Xây Nhà Trọn Gói (Chìa Khóa Trao Tay)
                            </h3>
                            <div class="text-hbGoldLight font-extrabold text-sm sm:text-lg mb-2">
                                5.500.000đ – 6.800.000đ/m²
                            </div>
                            <ul class="text-[11px] sm:text-xs text-slate-200 space-y-1">
                                <li>• Miễn phí xin giấy phép xây dựng & hồ sơ thiết kế</li>
                                <li>• Trọn gói từ móng đến hoàn thiện vào ở ngay</li>
                                <li>• Cam kết không phát sinh chi phí ngoài hợp đồng</li>
                            </ul>
                        </div>
                    </div>
                </div>

                <!-- Cột phải: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ (Theo mẫu tintruongthinh.com) -->
                <div class="lg:col-span-5 bg-white text-slate-800 rounded-xl p-5 sm:p-6 shadow-lg border-2 border-hbGold">
                    <div class="text-center mb-4">
                        <span class="inline-block px-3 py-0.5 rounded-full bg-hbGold/15 text-hbNavy font-bold text-[11px] mb-1">
                            HỖ TRỢ KHẢO SÁT TẬN NƠI TẠI ĐÀ NẴNG
                        </span>
                        <h3 class="font-heading font-extrabold text-hbNavy text-base sm:text-xl">
                            ĐĂNG KÝ YÊU CẦU & NHẬN BÁO GIÁ MIỄN PHÍ
                        </h3>
                    </div>

                    <form id="quoteForm" onsubmit="submitQuoteForm(event)" class="space-y-3 text-xs sm:text-sm">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block font-semibold text-hbNavy mb-1">Họ và tên *</label>
                                <input type="text" id="qName" required placeholder="Nhập họ tên Quý khách" class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:border-hbGold focus:outline-none">
                            </div>
                            <div>
                                <label class="block font-semibold text-hbNavy mb-1">Số điện thoại / Zalo *</label>
                                <input type="tel" id="qPhone" required placeholder="Ví dụ: 0903176334" class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:border-hbGold focus:outline-none">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block font-semibold text-hbNavy mb-1">Loại công trình</label>
                                <select id="qType" class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:border-hbGold focus:outline-none bg-white">
                                    <option value="Nhà phố">Nhà phố</option>
                                    <option value="Khách sạn – Căn hộ cho thuê – Phòng trọ">Khách sạn – Căn hộ – Phòng trọ</option>
                                    <option value="Biệt thự">Biệt thự</option>
                                    <option value="Văn phòng">Văn phòng</option>
                                    <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                </select>
                            </div>
                            <div>
                                <label class="block font-semibold text-hbNavy mb-1">Mức đầu tư dự kiến</label>
                                <select id="qBudget" class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:border-hbGold focus:outline-none bg-white">
                                    <option value="Dưới 1 tỷ">Dưới 1 tỷ</option>
                                    <option value="Từ 1 - 2 tỷ" selected>Từ 1 - 2 tỷ</option>
                                    <option value="Từ 2 - 3 tỷ">Từ 2 - 3 tỷ</option>
                                    <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                    <option value="Cần tư vấn dự toán">Cần tư vấn dự toán chi tiết</option>
                                </select>
                            </div>
                        </div>

                        <div>
                            <label class="block font-semibold text-hbNavy mb-1">Địa điểm xây dựng & diện tích đất (nếu có)</label>
                            <input type="text" id="qNote" placeholder="VD: Lô 5x20m tại Cẩm Lệ, Đà Nẵng - xây 3 tầng..." class="w-full px-3 py-2 rounded-lg border border-slate-300 focus:border-hbGold focus:outline-none">
                        </div>

                        <button type="submit" class="w-full py-3 rounded-lg bg-hbGold hover:bg-hbGoldLight text-hbNavy font-heading font-extrabold text-xs sm:text-sm uppercase tracking-wide transition shadow">
                            <i class="fa-solid fa-paper-plane mr-1.5"></i>GỬI YÊU CẦU TƯ VẤN & BÁO GIÁ NGAY
                        </button>

                        <div id="quoteSuccessMsg" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs leading-relaxed"></div>
                    </form>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION DANH MỤC ĐỐI TÁC ĐỒNG HÀNH
         ===================================================================== -->
    <section id="doi-tac" class="py-10 bg-white border-b border-slate-200">
        <div class="ux-container">
            <div class="text-center mb-6">
                <div class="flatsome-section-title">
                    <h2 class="font-heading font-extrabold text-hbNavy text-lg sm:text-2xl uppercase">
                        ĐỐI TÁC & THƯƠNG HIỆU VẬT TƯ CHÍNH HÃNG
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600">
                    Hưng Bình cam kết sử dụng 100% vật tư chính hãng từ các nhà sản xuất uy tín hàng đầu Việt Nam
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3">
                <div class="p-3.5 rounded-xl bg-hbGray border border-slate-200 flex flex-col items-center justify-center text-center">
                    <div class="font-heading font-extrabold text-hbNavy text-sm sm:text-base">HÒA PHÁT</div>
                    <div class="text-[11px] text-slate-500">Thép xây dựng</div>
                </div>
                <div class="p-3.5 rounded-xl bg-hbGray border border-slate-200 flex flex-col items-center justify-center text-center">
                    <div class="font-heading font-extrabold text-hbNavy text-sm sm:text-base">SÔNG GIANH</div>
                    <div class="text-[11px] text-slate-500">Xi măng chất lượng cao</div>
                </div>
                <div class="p-3.5 rounded-xl bg-hbGray border border-slate-200 flex flex-col items-center justify-center text-center">
                    <div class="font-heading font-extrabold text-hbNavy text-sm sm:text-base">DULUX / JOTUN</div>
                    <div class="text-[11px] text-slate-500">Sơn ngoại & nội thất</div>
                </div>
                <div class="p-3.5 rounded-xl bg-hbGray border border-slate-200 flex flex-col items-center justify-center text-center">
                    <div class="font-heading font-extrabold text-hbNavy text-sm sm:text-base">INAX & TOTO</div>
                    <div class="text-[11px] text-slate-500">Thiết bị vệ sinh</div>
                </div>
                <div class="p-3.5 rounded-xl bg-hbGray border border-slate-200 flex flex-col items-center justify-center text-center">
                    <div class="font-heading font-extrabold text-hbNavy text-sm sm:text-base">PANASONIC</div>
                    <div class="text-[11px] text-slate-500">Thiết bị điện & chiếu sáng</div>
                </div>
                <div class="p-3.5 rounded-xl bg-hbGray border border-slate-200 flex flex-col items-center justify-center text-center">
                    <div class="font-heading font-extrabold text-hbNavy text-sm sm:text-base">AN CƯỜNG</div>
                    <div class="text-[11px] text-slate-500">Gỗ nội thất cao cấp</div>
                </div>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Theo mẫu tintruongthinh.com)
         ===================================================================== -->
    <section id="tin-tuc" class="py-12 bg-hbGray border-b border-slate-200">
        <div class="ux-container">
            <div class="text-center mb-7">
                <div class="flatsome-section-title">
                    <h2 class="font-heading font-extrabold text-hbNavy text-lg sm:text-2xl uppercase">
                        TIN TỨC & KINH NGHIỆM XÂY DỰNG
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600">
                    Cập nhật kiến thức thiết kế, kỹ thuật thi công và cẩm nang xây nhà trọn gói tại Đà Nẵng
                </p>
            </div>

            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-5">
                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x&sz=w800"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1ImsuD--QivYj4IV9Nx10yzvXfmuRmZ8x=w800';"
                             alt="Hướng dẫn bảo dưỡng bê tông móng đúng cách" class="w-full h-full object-cover" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1.5 product-title-full">
                                Hướng Dẫn Kỹ Thuật Bảo Dưỡng Bê Tông Móng Đúng Cách Khi Xây Nhà
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Trong quá trình xây dựng công trình, bê tông móng đóng vai trò quyết định độ bền vững và chống thấm nứt...
                            </p>
                        </div>
                    </div>
                </article>

                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF&sz=w800"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1-JeFJVOKB9-b8SOJFIxqa-Mk9ctbIraF=w800';"
                             alt="Tâm lý học không gian nội thất" class="w-full h-full object-cover" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1.5 product-title-full">
                                Tâm Lý Học Không Gian: Nội Thất Tác Động Đến Hành Vi Gia Đình Như Thế Nào?
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Cách bố trí ánh sáng tự nhiên, thông gió và màu sắc nội thất giúp mang lại năng lượng tích cực cho tổ ấm...
                            </p>
                        </div>
                    </div>
                </article>

                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk&sz=w800"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk=w800';"
                             alt="03 nỗi lo lớn nhất khi xây nhà" class="w-full h-full object-cover" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1.5 product-title-full">
                                03 Nỗi Lo Lớn Nhất Khi Xây Nhà Mà Chủ Đầu Tư Cần Biết Để Tránh Phát Sinh
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Giải pháp kiểm soát ngân sách dự toán, lựa chọn vật tư phần thô và giám sát tiến độ thi công hiệu quả...
                            </p>
                        </div>
                    </div>
                </article>

                <article class="bg-white rounded-xl overflow-hidden border border-slate-200 shadow-sm flex flex-col">
                    <div class="aspect-[16/10] w-full overflow-hidden">
                        <img src="https://drive.google.com/thumbnail?id=1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw&sz=w800"
                             onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1ugKZwI_07LD42SRgLweM-PeRQt9-01Lw=w800';"
                             alt="Thủ tục xin giấy phép xây dựng Đà Nẵng" class="w-full h-full object-cover" loading="lazy">
                    </div>
                    <div class="p-3 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="font-bold text-hbNavy text-xs sm:text-sm mb-1.5 product-title-full">
                                Quy Trình Xin Giấy Phép Xây Dựng Nhà Phố Tại Cẩm Lệ, Đà Nẵng Mới Nhất
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-600 leading-relaxed">
                                Hồ sơ pháp lý, mật độ xây dựng, chiều cao tầng và các lưu ý quan trọng trước khi khởi công xây dựng...
                            </p>
                        </div>
                    </div>
                </article>
            </div>
        </div>
    </section>

    <!-- =====================================================================
         SECTION ĐƯA FACEBOOK VÀ GOOGLE MAP RA NGOÀI TRANG CHỦ
         - Địa chỉ: K12/H35/06/01 Trường Sơn, Phường Cẩm Lệ, TP Đà Nẵng
         - Facebook: https://www.facebook.com/sinh.dang.van.604746/
         - SĐT: 0903.176.334
         ===================================================================== -->
    <section id="lien-he-map" class="py-12 bg-white border-b border-slate-200">
        <div class="ux-container">
            <div class="text-center mb-7">
                <div class="flatsome-section-title">
                    <h2 class="font-heading font-extrabold text-hbNavy text-lg sm:text-2xl uppercase">
                        KẾT NỐI FACEBOOK & BẢN ĐỒ GOOGLE MAPS TRỤ SỞ
                    </h2>
                </div>
                <p class="text-xs sm:text-sm text-slate-600">
                    Địa chỉ: K12/H35/06/01 Trường Sơn, Phường Cẩm Lệ, TP Đà Nẵng – Hotline/Zalo: 0903.176.334
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                
                <!-- Khung kết nối Facebook chính thức ngoài trang chủ -->
                <div class="lg:col-span-5 bg-hbGray rounded-xl p-5 border border-slate-200 flex flex-col justify-between">
                    <div>
                        <div class="flex items-center gap-3 mb-4 pb-3 border-b border-slate-200">
                            <div class="w-12 h-12 rounded-full bg-[#1877F2] text-white flex items-center justify-center text-2xl shrink-0">
                                <i class="fa-brands fa-facebook-f"></i>
                            </div>
                            <div>
                                <div class="text-[11px] font-bold text-[#1877F2] uppercase">KẾT NỐI TRỰC TIẾP TRÊN FACEBOOK</div>
                                <h3 class="font-heading font-bold text-hbNavy text-sm sm:text-base">
                                    Đặng Văn Sinh – Xây Dựng Hưng Bình
                                </h3>
                                <div class="text-xs text-slate-500">Cập nhật nhật ký thi công công trình thực tế tại Đà Nẵng</div>
                            </div>
                        </div>

                        <div class="grid grid-cols-3 gap-2 mb-4">
                            <img src="https://drive.google.com/thumbnail?id=1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk&sz=w500"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1WXZir1faPl2Gxd0A0boytWMP8O-6b3hk=w500';"
                                 alt="Ảnh Facebook Hưng Bình 1" class="w-full h-20 object-cover rounded-lg border border-slate-200">
                            <img src="https://drive.google.com/thumbnail?id=1PjtEF4hlMU_42b438GmEQhYZTba75kRJ&sz=w500"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1PjtEF4hlMU_42b438GmEQhYZTba75kRJ=w500';"
                                 alt="Ảnh Facebook Hưng Bình 2" class="w-full h-20 object-cover rounded-lg border border-slate-200">
                            <img src="https://drive.google.com/thumbnail?id=1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA&sz=w500"
                                 onerror="this.onerror=null;this.src='https://lh3.googleusercontent.com/d/1m7VasLcMXKPk2-mSVgIdO3USOnbaZ_KA=w500';"
                                 alt="Ảnh Facebook Hưng Bình 3" class="w-full h-20 object-cover rounded-lg border border-slate-200">
                        </div>

                        <div class="space-y-2 text-xs text-slate-700 bg-white p-3.5 rounded-lg border border-slate-200 mb-4">
                            <div><i class="fa-solid fa-building text-hbGold mr-2"></i><strong>Đơn vị:</strong> CÔNG TY TNHH TƯ VẤN XÂY DỰNG VÀ THƯƠNG MẠI DỊCH VỤ HƯNG BÌNH</div>
                            <div><i class="fa-solid fa-location-dot text-hbGold mr-2"></i><strong>Địa chỉ:</strong> K12/H35/06/01 Trường Sơn, Phường Cẩm Lệ, TP Đà Nẵng</div>
                            <div><i class="fa-solid fa-phone text-hbGold mr-2"></i><strong>Điện thoại / Zalo:</strong> <a href="tel:0903176334" class="font-bold text-hbNavy">0903.176.334</a></div>
                            <div><i class="fa-solid fa-globe text-hbGold mr-2"></i><strong>Website:</strong> hungbinh.com.vn</div>
                        </div>
                    </div>

                    <div class="flex flex-wrap gap-2.5">
                        <a href="https://www.facebook.com/sinh.dang.van.604746/" target="_blank" rel="noopener noreferrer" class="flex-1 py-2.5 px-4 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs text-center transition">
                            <i class="fa-brands fa-facebook mr-1.5"></i>XEM TRANG FACEBOOK CHÍNH THỨC
                        </a>
                        <a href="https://zalo.me/0903176334" target="_blank" rel="noopener noreferrer" class="py-2.5 px-4 rounded-lg bg-hbNavy hover:bg-hbBlue text-white font-bold text-xs text-center transition">
                            <i class="fa-solid fa-comment-dots text-hbGoldLight mr-1"></i>Chat Zalo
                        </a>
                    </div>
                </div>

                <!-- Khung Bản đồ Google Map ngoài trang chủ -->
                <div class="lg:col-span-7 rounded-xl overflow-hidden border border-slate-300 shadow-sm bg-slate-100 flex flex-col">
                    <div class="bg-hbNavy text-white px-4 py-2.5 flex flex-wrap items-center justify-between gap-2 text-xs">
                        <div>
                            <i class="fa-solid fa-map-pin text-hbGold mr-1.5"></i>
                            <strong>Vị trí Google Maps:</strong> K12/H35/06/01 Trường Sơn, Phường Cẩm Lệ, TP Đà Nẵng
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=K12%2FH35%2F06%2F01+Tr%C6%B0%E1%BB%9Dng+S%C6%A1n%2C+C%E1%BA%A9m+L%E1%BB%87%2C+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-hbGoldLight hover:underline font-semibold">
                            Mở chỉ đường lớn <i class="fa-solid fa-arrow-up-right-from-square ml-1"></i>
                        </a>
                    </div>
                    <div class="w-full h-[320px] sm:h-[360px]">
                        <iframe 
                            title="Bản đồ Công ty TNHH Tư vấn Xây dựng và Thương mại Dịch vụ Hưng Bình"
                            src="https://maps.google.com/maps?q=Đường%20Trường%20Sơn,%20Cẩm%20Lệ,%20Đà%20Nẵng&t=&z=15&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =====================================================================
         FOOTER FLATSOME (Đầy đủ thông tin pháp lý, danh mục, liên hệ)
         ===================================================================== -->
    <footer class="bg-[#081a30] text-slate-300 pt-10 pb-20 lg:pb-10 border-t-4 border-hbGold text-xs sm:text-sm">
        <div class="ux-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-8 pb-8 border-b border-slate-700/70">
                
                <!-- Cột 1: Thông tin công ty -->
                <div class="lg:col-span-5">
                    <div class="flex items-center gap-3 mb-3">
                        <div class="w-9 h-9 rounded-lg bg-hbNavy flex items-center justify-center border border-hbGold shrink-0">
                            <span class="font-heading font-extrabold text-hbGoldLight text-sm">HB</span>
                        </div>
                        <div class="font-heading font-extrabold text-white text-sm sm:text-base">
                            CÔNG TY TNHH TƯ VẤN XÂY DỰNG VÀ THƯƠNG MẠI DỊCH VỤ HƯNG BÌNH
                        </div>
                    </div>
                    <ul class="space-y-2 text-xs text-slate-300">
                        <li><i class="fa-solid fa-location-dot text-hbGold w-5"></i><strong>Địa chỉ:</strong> K12/H35/06/01 Trường Sơn, Phường Cẩm Lệ, TP Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone text-hbGold w-5"></i><strong>Hotline / Zalo:</strong> <a href="tel:0903176334" class="text-hbGoldLight font-bold">0903.176.334</a></li>
                        <li><i class="fa-solid fa-hashtag text-hbGold w-5"></i><strong>Mã số thuế:</strong> 0402300370</li>
                        <li><i class="fa-solid fa-globe text-hbGold w-5"></i><strong>Website:</strong> <a href="https://hungbinh.com.vn" class="hover:text-hbGoldLight">hungbinh.com.vn</a></li>
                        <li><i class="fa-brands fa-facebook text-hbGold w-5"></i><strong>Facebook:</strong> <a href="https://www.facebook.com/sinh.dang.van.604746/" target="_blank" rel="noopener noreferrer" class="hover:text-hbGoldLight break-all">facebook.com/sinh.dang.van.604746</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3">
                    <h4 class="font-heading font-bold text-white uppercase text-xs sm:text-sm mb-3 pb-1.5 border-b border-hbGold/40 inline-block">
                        Lĩnh Vực Hoạt Động
                    </h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-hbGoldLight transition">• Thiết kế Kiến trúc – Nội thất</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-hbGoldLight transition">• Thi công phần thô trọn gói</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-hbGoldLight transition">• Thi công hoàn thiện nhà ở</a></li>
                        <li><a href="#linh-vuc-hoat-dong" class="hover:text-hbGoldLight transition">• Sản xuất & Thi công nội thất</a></li>
                        <li><a href="#bang-bao-gia" class="hover:text-hbGoldLight transition">• Báo giá xây nhà trọn gói Đà Nẵng</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục công trình -->
                <div class="lg:col-span-4">
                    <h4 class="font-heading font-bold text-white uppercase text-xs sm:text-sm mb-3 pb-1.5 border-b border-hbGold/40 inline-block">
                        Danh Mục Công Trình Thực Tế
                    </h4>
                    <ul class="grid grid-cols-2 gap-2 text-xs">
                        <li><a href="#cong-trinh-thuc-te" onclick="filterCategory('khach-san-can-ho')" class="hover:text-hbGoldLight transition">• Khách sạn – Căn hộ</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterCategory('biet-thu')" class="hover:text-hbGoldLight transition">• Biệt thự hiện đại</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterCategory('nha-pho')" class="hover:text-hbGoldLight transition">• Nhà phố Đà Nẵng</a></li>
                        <li><a href="#cong-trinh-thuc-te" onclick="filterCategory('van-phong-noi-that')" class="hover:text-hbGoldLight transition">• Văn phòng – Nội thất</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-hbGoldLight transition">• Dự án tại Cẩm Lệ</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-hbGoldLight transition">• Dự án tại Hòa Xuân</a></li>
                    </ul>
                </div>

            </div>

            <div class="pt-5 text-center text-[11px] text-slate-400">
                Copyright © 2026 <strong>CÔNG TY TNHH TƯ VẤN XÂY DỰNG VÀ THƯƠNG MẠI DỊCH VỤ HƯNG BÌNH</strong> (hungbinh.com.vn). All rights reserved.
            </div>
        </div>
    </footer>

    <!-- =====================================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE)
         Tương thích hoàn hảo trên cả máy tính và điện thoại, không gây tràn viền
         ===================================================================== -->
    <div class="fixed bottom-4 right-3 sm:right-5 z-50 flex flex-col items-end gap-2.5">
        
        <!-- Nút Facebook nổi -->
        <a href="https://www.facebook.com/sinh.dang.van.604746/" target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-700 text-white px-3.5 py-2 rounded-full shadow-lg border border-white/30 transition"
           title="Facebook Hưng Bình">
            <i class="fa-brands fa-facebook-f text-sm"></i>
            <span class="text-xs font-bold">Facebook</span>
        </a>

        <!-- Nút Zalo nổi -->
        <a href="https://zalo.me/0903176334" target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-600 text-white px-3.5 py-2 rounded-full shadow-lg border border-white/30 transition"
           title="Chat Zalo 0903.176.334">
            <span class="font-extrabold text-xs bg-white text-[#0068ff] px-1.5 py-0.5 rounded">Zalo</span>
            <span class="text-xs font-bold">0903.176.334</span>
        </a>

        <!-- Nút Hotline nổi -->
        <a href="tel:0903176334"
           class="pulse-btn flex items-center gap-2 bg-hbGold hover:bg-hbGoldLight text-hbNavy px-4 py-2.5 rounded-full shadow-xl border-2 border-white transition"
           title="Gọi ngay 0903.176.334">
            <i class="fa-solid fa-phone-volume text-sm"></i>
            <span class="text-xs sm:text-sm font-heading font-extrabold">0903.176.334</span>
        </a>
    </div>

    <!-- =====================================================================
         MODAL PHÓNG TO XEM ẢNH THỰC TẾ CÔNG TRÌNH
         ===================================================================== -->
    <div id="lightboxModal" class="fixed inset-0 z-50 hidden bg-black/85 flex items-center justify-center p-4" onclick="closeLightbox()">
        <div class="relative max-w-4xl w-full bg-white rounded-xl overflow-hidden shadow-2xl" onclick="event.stopPropagation()">
            <div class="flex items-center justify-between px-4 py-3 bg-hbNavy text-white">
                <h4 id="lightboxCaption" class="font-bold text-xs sm:text-sm pr-4">Hình ảnh thực tế công trình Hưng Bình</h4>
                <button type="button" onclick="closeLightbox()" class="w-8 h-8 rounded-full bg-white/15 hover:bg-hbGold flex items-center justify-center text-white">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div class="bg-slate-900 flex items-center justify-center max-h-[75vh] overflow-hidden">
                <img id="lightboxImg" src="" alt="Công trình thực tế Hưng Bình" class="max-w-full max-h-[75vh] object-contain">
            </div>
        </div>
    </div>

    <!-- =====================================================================
         JAVASCRIPT ĐIỀU KHIỂN SLIDER, LỌC DANH MỤC, FORM BÁO GIÁ
         ===================================================================== -->
    <script>
        // 1. Tự động trượt 2 Banner (5 giây / lần)
        let currentSlide = 0;
        const slides = document.querySelectorAll('.banner-slide');
        const dots = document.querySelectorAll('.slide-dot');

        function showSlide(index) {
            currentSlide = (index + slides.length) % slides.length;
            slides.forEach((slide, i) => {
                if (i === currentSlide) {
                    slide.classList.remove('hidden');
                    slide.classList.add('block');
                } else {
                    slide.classList.remove('block');
                    slide.classList.add('hidden');
                }
            });
            dots.forEach((dot, i) => {
                if (i === currentSlide) {
                    dot.classList.add('w-6', 'bg-hbGold');
                    dot.classList.remove('w-2', 'bg-white/60');
                } else {
                    dot.classList.remove('w-6', 'bg-hbGold');
                    dot.classList.add('w-2', 'bg-white/60');
                }
            });
        }

        function changeSlide(step) {
            showSlide(currentSlide + step);
        }

        function goToSlide(index) {
            showSlide(index);
        }

        setInterval(() => {
            changeSlide(1);
        }, 5000);

        // 2. Bật/tắt menu trên điện thoại
        function toggleMobileMenu() {
            const drawer = document.getElementById('mobileMenuDrawer');
            drawer.classList.toggle('hidden');
        }

        // 3. Lọc sản phẩm / công trình thực tế theo danh mục
        function filterCategory(category) {
            const cards = document.querySelectorAll('.product-card');
            const buttons = document.querySelectorAll('.cat-filter-btn');

            buttons.forEach(btn => {
                if (btn.getAttribute('data-cat-btn') === category) {
                    btn.classList.add('bg-hbNavy', 'text-white', 'border-hbNavy');
                    btn.classList.remove('bg-white', 'text-hbNavy', 'border-slate-300');
                } else {
                    btn.classList.remove('bg-hbNavy', 'text-white', 'border-hbNavy');
                    btn.classList.add('bg-white', 'text-hbNavy', 'border-slate-300');
                }
            });

            cards.forEach(card => {
                const cardCat = card.getAttribute('data-category');
                if (category === 'all' || cardCat === category) {
                    card.classList.remove('hidden');
                    card.classList.add('flex');
                } else {
                    card.classList.remove('flex');
                    card.classList.add('hidden');
                }
            });
        }

        // 4. Mở / Đóng ảnh phóng to
        function openLightbox(driveId, caption) {
            const modal = document.getElementById('lightboxModal');
            const img = document.getElementById('lightboxImg');
            const cap = document.getElementById('lightboxCaption');

            img.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w1600';
            img.onerror = function() {
                this.onerror = null;
                this.src = 'https://lh3.googleusercontent.com/d/' + driveId + '=w1600';
            };
            cap.textContent = caption;
            modal.classList.remove('hidden');
        }

        function closeLightbox() {
            document.getElementById('lightboxModal').classList.add('hidden');
        }

        // 5. Xử lý gửi Form Yêu cầu & Báo giá trên trang chủ
        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const type = document.getElementById('qType').value;
            const budget = document.getElementById('qBudget').value;
            const note = document.getElementById('qNote').value.trim();

            const msgBox = document.getElementById('quoteSuccessMsg');
            msgBox.classList.remove('hidden');
            msgBox.innerHTML = '<strong>Đã ghi nhận yêu cầu báo giá của Quý khách ' + name + ' (' + phone + ')!</strong><br>' +
                'Hạng mục: <strong>' + type + '</strong> – Mức đầu tư: <strong>' + budget + '</strong>' +
                (note ? '<br>Ghi chú: ' + note : '') +
                '<br>Bộ phận Kỹ thuật Hưng Bình (Hotline/Zalo: <strong>0903.176.334</strong>) sẽ liên hệ tư vấn ngay.';
        }
    </script>
</body>
</html>
