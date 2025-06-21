<!DOCTYPE html>
<html lang="vi" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Báo cáo Toàn cảnh Thị trường Lao động Việt Nam 2024 & Dự báo 2025 - Nghề Nhân sự Việt Nam</title>
    
    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    
    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- Font Awesome for Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" xintegrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />

    <!-- Chart.js for data visualization -->
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>

    <!-- Libraries for PDF export -->
    <script src="https://cdnjs.cloudflare.com/ajax/libs/html2canvas/1.4.1/html2canvas.min.js" xintegrity="sha512-BNaRQnYJYiPSqHHDb58B0yaPfCu+Wgds8Gp/gU33kqBtgNS4tSPHuGibyoVBL5gI9kDXDCe9xuXSC_65p4iLVQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/jspdf/2.5.1/jspdf.umd.min.js"></script>

    <style>
        body {
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc; /* gray-50 */
        }
        .brand-blue { color: #004a8f; }
        .bg-brand-blue { background-color: #004a8f; }
        .hover-bg-brand-blue:hover { background-color: #003b72; }
        
        .report-content h2 {
            scroll-margin-top: 80px;
            font-size: 1.875rem; /* text-3xl */
            font-weight: 700;
            margin-top: 2.5rem;
            margin-bottom: 1.25rem;
            padding-bottom: 0.5rem;
            border-bottom: 2px solid #e5e7eb;
            color: #111827;
        }
        .report-content h3 {
            scroll-margin-top: 80px;
            font-size: 1.5rem; /* text-2xl */
            font-weight: 600;
            margin-top: 2rem;
            margin-bottom: 1rem;
            color: #1f2937;
        }
        .report-content p, .report-content li {
            font-size: 1rem;
            line-height: 1.75;
            color: #374151;
            margin-bottom: 1rem;
        }
        .report-content ul {
            list-style-position: outside;
            padding-left: 1.5rem;
            list-style-type: disc;
        }
        .report-content strong {
            font-weight: 700;
            color: #111827;
        }
        .responsive-table {
            width: 100%;
            margin: 1.5rem 0;
            background-color: white;
            border-radius: 0.5rem;
            overflow: hidden;
            box-shadow: 0 1px 3px 0 rgb(0 0 0 / 0.1), 0 1px 2px -1px rgb(0 0 0 / 0.1);
        }
        .responsive-table .table-header {
            background-color: #f9fafb;
            font-weight: 600;
            display: none;
        }
        @media (min-width: 768px) {
            .responsive-table .table-header {
                display: grid;
            }
        }
        .responsive-table .table-row {
            display: grid;
            grid-template-columns: 1fr;
            border-bottom: 1px solid #e5e7eb;
        }
        .responsive-table .table-row:last-child {
            border-bottom: none;
        }
        .responsive-table .table-cell {
            padding: 0.75rem 1rem;
            display: grid;
            grid-template-columns: 1fr 2fr;
            align-items: center;
            gap: 1rem;
            border-bottom: 1px solid #f3f4f6;
        }
        .responsive-table .table-cell:last-child {
            border-bottom: none;
        }
        .responsive-table .cell-label {
            font-weight: 600;
            color: #4b5563;
        }
        @media (min-width: 768px) {
            .responsive-table .table-row, .responsive-table .table-header {
                grid-template-columns: 2fr repeat(3, 1fr);
            }
            .responsive-table .table-cell {
                display: block;
                border-bottom: none;
            }
            .responsive-table .table-cell:not(:last-child) {
                 border-right: 1px solid #e5e7eb;
            }
            .responsive-table .cell-label {
                display: none;
            }
        }
        .chart-container {
            background-color: #ffffff;
            padding: 1.5rem;
            border-radius: 0.75rem;
            box-shadow: 0 4px 6px -1px rgb(0 0 0 / 0.1), 0 2px 4px -2px rgb(0 0 0 / 0.1);
            margin: 2rem 0;
        }
        .chart-title {
            font-size: 1.125rem;
            font-weight: 600;
            color: #1f2937;
            text-align: center;
            margin-bottom: 1rem;
        }
        .toc a.active {
            color: #004a8f;
            font-weight: 700;
            border-left-color: #004a8f;
        }
    </style>
</head>
<body class="text-gray-800">

    <!-- Header -->
    <header class="bg-white shadow-md sticky top-0 z-40">
        <div class="container mx-auto px-6 py-3 flex justify-between items-center">
            <a href="#" class="flex items-center">
                <img src="https://assets.stickpng.com/images/5847f9cbcef1014c0b5e48c8.png" alt="Nghề Nhân sự Việt Nam Logo" class="h-12 mr-3" onerror="this.onerror=null;this.src='https://placehold.co/150x50/004a8f/ffffff?text=NNS+Logo';">
            </a>
            <nav class="hidden md:flex items-center space-x-6">
                <a href="#summary" class="text-gray-600 hover:text-blue-600 transition duration-300">Tóm tắt</a>
                <a href="#chuong1" class="text-gray-600 hover:text-blue-600 transition duration-300">Chương 1</a>
                <a href="#chuong2" class="text-gray-600 hover:text-blue-600 transition duration-300">Chương 2</a>
                <a href="#chuong3" class="text-gray-600 hover:text-blue-600 transition duration-300">Chương 3</a>
                 <a href="#chuong4" class="text-gray-600 hover:text-blue-600 transition duration-300">Chương 4</a>
                <a href="#contact" class="text-gray-600 hover:text-blue-600 transition duration-300">Liên hệ</a>
            </nav>
            <button id="downloadBtn" class="bg-brand-blue text-white font-bold py-2 px-4 rounded-lg shadow-lg hover-bg-brand-blue transition duration-300 transform hover:scale-105">
                Tải Báo cáo (PDF)
            </button>
        </div>
    </header>

    <!-- Main Content -->
    <div class="container mx-auto px-6 py-8 md:py-12">
        <div class="lg:flex lg:gap-12">
            <!-- Table of Contents (Sidebar) -->
            <aside class="hidden lg:block w-1/4">
                <div class="sticky top-24 toc">
                    <h3 class="font-bold text-lg mb-4">Nội dung báo cáo</h3>
                    <nav id="table-of-contents" class="flex flex-col space-y-2 border-l-2 border-gray-200">
                        <a href="#summary" class="pl-4 py-1 text-gray-600 hover:text-blue-600 border-l-2 border-transparent">Tóm tắt Báo cáo</a>
                        <a href="#chuong1" class="pl-4 py-1 text-gray-600 hover:text-blue-600 border-l-2 border-transparent">Chương 1: Bối cảnh Vĩ mô</a>
                        <a href="#chuong2" class="pl-4 py-1 text-gray-600 hover:text-blue-600 border-l-2 border-transparent">Chương 2: Lực lượng Lao động</a>
                        <a href="#chuong3" class="pl-4 py-1 text-gray-600 hover:text-blue-600 border-l-2 border-transparent">Chương 3: Thất nghiệp & Thiếu việc làm</a>
                        <a href="#chuong4" class="pl-4 py-1 text-gray-600 hover:text-blue-600 border-l-2 border-transparent">Chương 4: Chiến lược & Khuyến nghị</a>
                        <a href="#interaction" class="pl-4 py-1 text-gray-600 hover:text-blue-600 border-l-2 border-transparent">Tương tác & Thảo luận</a>
                    </nav>
                </div>
            </aside>

            <!-- Report Article -->
            <main class="w-full lg:w-3/4">
                <article id="report-content-wrapper" class="bg-white p-6 sm:p-10 rounded-xl shadow-lg">
                    <!-- Report Header -->
                    <div class="flex flex-col sm:flex-row gap-6 items-start mb-8 pb-6 border-b-2 border-gray-200">
                        <img src="https://assets.stickpng.com/images/5847f9cbcef1014c0b5e48c8.png" alt="Nghề Nhân sự Việt Nam Logo" class="h-20 w-auto mx-auto sm:mx-0" onerror="this.onerror=null;this.src='https://placehold.co/208x80/004a8f/ffffff?text=NNS+Logo';">
                        <div class="text-sm text-gray-600 flex-grow text-center sm:text-left">
                            <h2 class="text-lg font-bold brand-blue m-0 p-0 border-0">CÔNG TY CỔ PHẦN NGHỀ NHÂN SỰ VIỆT NAM</h2>
                            <p class="mt-1"><i class="fa-solid fa-location-dot w-4 mr-1"></i>Tầng 5, Tòa nhà ST Moritz, 1014 Phạm Văn Đồng, P. Hiệp Bình Chánh, TP. Thủ Đức, TP. HCM</p>
                            <p class="mt-1"><i class="fa-solid fa-phone w-4 mr-1"></i><a href="tel:+84948013214" class="hover:underline">+84 948 013 214</a></p>
                            <p class="mt-1"><i class="fa-solid fa-envelope w-4 mr-1"></i><a href="mailto:chung@nghenhansu.vn" class="hover:underline">chung@nghenhansu.vn</a></p>
                            <p class="mt-1"><i class="fa-solid fa-globe w-4 mr-1"></i><a href="https://www.nghenhansu.vn" target="_blank" class="hover:underline">www.nghenhansu.vn</a></p>
                        </div>
                    </div>
                    
                    <header class="mb-10 text-center">
                        <h1 class="text-4xl md:text-5xl font-extrabold brand-blue mb-4">
                            BÁO CÁO TOÀN CẢNH THỊ TRƯỜNG LAO ĐỘNG VIỆT NAM 2024 & DỰ BÁO 2025
                        </h1>
                        <p class="text-xl md:text-2xl text-gray-600">Những Con Số Biết Nói</p>
                        <p class="text-sm text-gray-500 mt-2">Được phát hành bởi Nghề Nhân sự Việt Nam (NNS) - Tháng 6, 2025</p>
                    </header>
                    
                    <div class="report-content">
                        <!-- Summary -->
                        <section id="summary">
                            <h3 class="text-xl font-semibold italic text-gray-700 border-l-4 border-blue-500 pl-4 mb-6">Tóm tắt Báo cáo dành cho Lãnh đạo</h3>
                            <p>Báo cáo này cung cấp một bức tranh toàn cảnh, đa chiều về thị trường lao động Việt Nam trong bối cảnh năm 2024 và dự báo cho năm 2025, được xây dựng dựa trên phân tích sâu sắc các dữ liệu kinh tế vĩ mô và thống kê lao động. Mục tiêu của báo cáo là trang bị cho các nhà lãnh đạo và chuyên gia nhân sự một nền tảng thông tin vững chắc để hoạch định chiến lược, vượt qua những thách thức và nắm bắt các cơ hội trong giai đoạn tới.</p>
                            <p class="font-semibold text-gray-800">Những phát hiện cốt lõi của báo cáo tập trung vào bốn điểm chính:</p>
                             <ul class="space-y-3">
                                <li><strong>Nghịch lý Tăng trưởng và "Khoảng trống Lạc quan":</strong> Nền kinh tế Việt Nam ghi nhận những con số tăng trưởng GDP ấn tượng trong Quý I/2025, tạo ra một không khí lạc quan trong nước. Tuy nhiên, điều này lại tương phản rõ rệt với các dự báo thận trọng hơn từ những tổ chức quốc tế uy tín, vốn chịu ảnh hưởng bởi rủi ro từ sự bất ổn của kinh tế toàn cầu. "Khoảng trống" này tạo ra một môi trường hoạt động phức tạp, đòi hỏi các doanh nghiệp phải áp dụng một "chiến lược kép": sẵn sàng cho tăng trưởng nhưng đồng thời phải xây dựng năng lực chống chịu để vượt qua các cú sốc tiềm tàng.</li>
                                <li><strong>Sự Mất cân đối "Lượng và Chất":</strong> Lợi thế cạnh tranh của Việt Nam về một lực lượng lao động dồi dào ("lượng") đang đối mặt với một thách thức chí mạng về trình độ kỹ năng ("chất"). Với hơn 71% lao động chưa qua đào tạo bài bản, một "khoảng trống kỹ năng" khổng lồ đang hình thành. Điều này định nghĩa lại "cuộc chiến giành nhân tài" thành cuộc tìm kiếm số ít ứng viên đủ tiêu chuẩn trong một bể nhân lực còn nông cạn, buộc doanh nghiệp phải chuyển dịch từ tư duy "săn bắn" sang "xây dựng" nhân tài.</li>
                                <li><strong>Báo động về Nhân lực trẻ:</strong> Dù tỷ lệ thất nghiệp chung ở mức thấp đáng mơ ước, tỷ lệ thất nghiệp ở thanh niên và tỷ lệ thanh niên không có việc làm, không đi học, không được đào tạo (NEET) lại ở mức báo động. Đây là một sự lãng phí nguồn lực con người to lớn, một "vết nứt" trong nền tảng nhân lực tương lai và là một rủi ro chiến lược đối với năng lực cạnh tranh quốc gia trong dài hạn.</li>
                                <li><strong>Tính Cấp thiết của việc Tái định vị Chiến lược Nhân sự:</strong> Các phân tích trên cho thấy, vai trò của quản trị nhân sự phải được nâng tầm. Hoạt động Đào tạo & Phát triển (L&D) không còn là chi phí phúc lợi mà là một khoản đầu tư sống còn. Việc xây dựng một lực lượng lao động kiên cường và một thương hiệu nhà tuyển dụng hấp dẫn không còn là lựa chọn, mà là yêu cầu bắt buộc để doanh nghiệp tồn tại và phát triển.</li>
                            </ul>
                        </section>

                        <!-- Chương 1 -->
                        <section id="chuong1">
                            <h2>Chương 1: Bối cảnh Kinh tế Vĩ mô và Nghịch lý Tăng trưởng</h2>
                            <p>Chương này đặt thị trường lao động trong bối cảnh kinh tế rộng lớn hơn, giải mã những tín hiệu trái chiều và cung cấp một lăng kính thực tế để các nhà lãnh đạo nhân sự nhìn nhận các cơ hội và thách thức.</p>
                            
                            <h3>1.1. Đà Phục hồi Kinh tế Việt Nam: Những Con số Ấn tượng</h3>
                            <p>Nền kinh tế Việt Nam đã có một khởi đầu đầy ấn tượng trong năm 2025, thể hiện đà phục hồi mạnh mẽ và vững chắc. Theo số liệu từ Tổng cục Thống kê (TCTK), tổng sản phẩm trong nước (GDP) Quý I/2025 ước tính tăng <strong>6,93%</strong> so với cùng kỳ năm trước. Đây là mức tăng trưởng cao nhất của một quý đầu năm trong suốt giai đoạn 5 năm từ 2020 đến 2025.</p>
                             <p>Động lực tăng trưởng này đến từ sự phục hồi đồng đều ở các khu vực kinh tế trọng điểm. Cụ thể, khu vực dịch vụ ghi nhận mức tăng 7,70%; khu vực công nghiệp và xây dựng tăng 7,42%. Đặc biệt, ngành công nghiệp chế biến, chế tạo, vốn được coi là xương sống của nền kinh tế, tiếp tục khẳng định vai trò đầu tàu với tốc độ tăng trưởng lên đến 9,28%.</p>

                            <h3>1.2. Bối cảnh Toàn cầu và "Cơn gió ngược" từ Bất ổn</h3>
                            <p>Tuy nhiên, bức tranh kinh tế trong nước dù lạc quan nhưng không thể tách rời bối cảnh toàn cầu đầy biến động. Tổ chức Hợp tác và Phát triển Kinh tế (OECD) dự báo tăng trưởng GDP toàn cầu sẽ có xu hướng chậm lại, từ mức 3,2% năm 2024 xuống còn <strong>3,1% năm 2025</strong>. Sự phụ thuộc lớn vào các thị trường xuất khẩu trọng điểm như Mỹ (chiếm 30% tổng kim ngạch) và nguồn nhập khẩu từ Trung Quốc (chiếm 38%) khiến Việt Nam trở nên đặc biệt nhạy cảm với các thay đổi trong chính sách thương mại và sự gián đoạn của chuỗi cung ứng toàn cầu.</p>
                            
                            <div class="chart-container">
                                <h4 class="chart-title">Biểu đồ 1: So sánh Tăng trưởng GDP (%) - Việt Nam & Dự báo Toàn cầu</h4>
                                <canvas id="gdpGrowthChart"></canvas>
                            </div>

                            <h3>1.4. Nghịch lý "Lạc quan Thận trọng": Tăng trưởng Kinh tế và Sự Do dự của Doanh nghiệp</h3>
                            <p>Hệ quả trực tiếp của "Khoảng trống Lạc quan" là một nghịch lý trong hành vi của cả doanh nghiệp và người lao động. Nhiều công ty vẫn đang trong quá trình tái cấu trúc mạnh mẽ, áp dụng tư duy "làm nhiều hơn với ít người hơn" (do more with less). Về phía người lao động, tâm lý chung là tìm kiếm sự ổn định và an toàn, tỷ lệ nghỉ việc tự nguyện có xu hướng giảm không phải vì sự hài lòng tăng lên mà do e ngại rủi ro.</p>

                            <h3>1.5. Định hướng "Chiến lược Kép" cho Lãnh đạo Nhân sự</h3>
                            <p>Đối mặt với bối cảnh này, các nhà lãnh đạo nhân sự cần áp dụng một "chiến lược kép" linh hoạt: <strong>Sẵn sàng cho Tăng trưởng (Growth Readiness)</strong> bằng cách xây dựng các kịch bản nhân sự và nguồn ứng viên tiềm năng; và <strong>Xây dựng Năng lực Chống chịu (Resilience Building)</strong> thông qua việc đầu tư vào giữ chân nhân tài và phát triển kỹ năng đa nhiệm cho đội ngũ cốt lõi.</p>
                        </section>

                        <!-- Chương 2 -->
                        <section id="chuong2">
                            <h2>Chương 2: Giải mã Lực lượng Lao động Việt Nam</h2>
                            <h3>2.1. Quy mô và "Cơ cấu Dân số Vàng"</h3>
                            <p>Việt Nam tiếp tục tận hưởng lợi thế từ thời kỳ "cơ cấu dân số vàng". Theo số liệu Quý I/2025, lực lượng lao động từ 15 tuổi trở lên đạt <strong>52,9 triệu người</strong>, với tỷ lệ tham gia lực lượng lao động ở mức cao là <strong>68,2%</strong>. Tuy nhiên, các phân tích nhân khẩu học cũng cho thấy những dấu hiệu ban đầu của quá trình già hóa dân số đang xuất hiện, đặt ra yêu cầu cấp thiết phải tận dụng tối đa giai đoạn này để tạo ra một bước nhảy vọt về chất lượng.</p>

                            <h3>2.2. "Khoảng trống Kỹ năng" Trầm trọng: Sự Mất cân đối Chí mạng</h3>
                            <p>Đây chính là điểm nghẽn lớn nhất của thị trường. Tỷ lệ lao động đã qua đào tạo có bằng cấp, chứng chỉ trong Quý I/2025 chỉ đạt <strong>28,8%</strong>. Điều này có nghĩa là hơn <strong>71%</strong> lực lượng lao động, tương đương gần 38 triệu người, chưa được đào tạo một cách bài bản. Trong lĩnh vực IT, chỉ khoảng <strong>30%</strong> sinh viên mới tốt nghiệp có thể đáp ứng ngay được yêu cầu công việc mà không cần đào tạo lại.</p>
                            
                            <div class="chart-container">
                                <h4 class="chart-title">Biểu đồ 2: Tỷ lệ Lao động qua Đào tạo tại Việt Nam (Quý I/2025)</h4>
                                <canvas id="skillGapChart"></canvas>
                            </div>

                             <h3>2.3. "Nghịch lý Thiếu-Thừa" (The Scarcity-Abundance Paradox)</h3>
                            <p>Sự chênh lệch giữa quy mô và chất lượng đã tạo ra một nghịch lý: thừa lao động phổ thông, kỹ năng thấp nhưng lại thiếu trầm trọng lao động có kỹ năng cao. Hệ quả là một "sự mất cân đối nghiêm trọng": "lực lượng lao động mà Việt Nam đang có không phải là lực lượng lao động mà Việt Nam cần cho các mục tiêu kinh tế tương lai". Đối với các chuyên gia nhân sự, điều này có nghĩa là "cuộc chiến giành nhân tài" đã trở thành cuộc tìm kiếm "kim đáy bể".</p>

                        </section>
                        
                        <!-- Chương 3 -->
                        <section id="chuong3">
                            <h2>Chương 3: Thất nghiệp và Thiếu việc làm</h2>
                           
                            <h3>3.2. Hồi chuông Báo động từ Tỷ lệ Thất nghiệp Thanh niên và Nhóm NEET</h3>
                            <p>"Tảng băng chìm" thực sự nằm ở nhóm lao động trẻ. Tỷ lệ thất nghiệp của thanh niên (15-24 tuổi) lên tới <strong>7,93%</strong>, cao gấp 3,6 lần tỷ lệ chung. Đặc biệt nghiêm trọng, tỷ lệ thanh niên không có việc làm, không đi học hoặc không được đào tạo (NEET) là <strong>10,4%</strong>, tương đương khoảng 1,35 triệu người trẻ.</p>
                            
                            <h3>3.3. So sánh với Khu vực ASEAN: Việt Nam đang ở đâu?</h3>
                            <p>Để có cái nhìn khách quan, việc so sánh các chỉ số lao động với các quốc gia ASEAN là rất cần thiết. Về mặt tích cực, tỷ lệ thất nghiệp chung của Việt Nam (2,20%) rất cạnh tranh, thấp hơn đáng kể so với Indonesia, Philippines và Malaysia. Tuy nhiên, khi nhìn vào các chỉ số về thanh niên, bức tranh trở nên kém lạc quan hơn, cho thấy một "vết nứt" đáng lo ngại trong nền tảng nhân lực tương lai của quốc gia.</p>
                            
                            <div class="chart-container">
                                <h4 class="chart-title">Biểu đồ 3: So sánh Tỷ lệ Thất nghiệp (%) tại một số nước ASEAN (Dữ liệu gần nhất)</h4>
                                <canvas id="aseanUnemploymentChart"></canvas>
                            </div>
                            
                            <h3>3.4. Bảng Điều khiển Thị trường Lao động Quý I-2025</h3>
                            <div class="responsive-table">
                                <div class="table-header">
                                    <div class="table-cell">Chỉ số</div>
                                    <div class="table-cell">Số liệu (Q1-2025)</div>
                                    <div class="table-cell">So với Quý trước</div>
                                    <div class="table-cell">So với Cùng kỳ năm trước</div>
                                </div>
                                <div class="table-row">
                                    <div class="table-cell"><span class="cell-label">Chỉ số</span><span>Lực lượng lao động (15+)</span></div>
                                    <div class="table-cell"><span class="cell-label">Số liệu</span><span>52,9 triệu người</span></div>
                                    <div class="table-cell"><span class="cell-label">So với Quý trước</span><span>Giảm 230,7 nghìn</span></div>
                                    <div class="table-cell"><span class="cell-label">So với Cùng kỳ</span><span>Tăng 532,0 nghìn</span></div>
                                </div>
                                <div class="table-row bg-gray-50">
                                    <div class="table-cell"><span class="cell-label">Chỉ số</span><span>Lao động có việc làm</span></div>
                                    <div class="table-cell"><span class="cell-label">Số liệu</span><span>51,9 triệu người</span></div>
                                    <div class="table-cell"><span class="cell-label">So với Quý trước</span><span>Giảm 234,0 nghìn</span></div>
                                    <div class="table-cell"><span class="cell-label">So với Cùng kỳ</span><span>Tăng 532,1 nghìn</span></div>
                                </div>
                                <div class="table-row">
                                    <div class="table-cell"><span class="cell-label">Chỉ số</span><span>Tỷ lệ lao động qua đào tạo</span></div>
                                    <div class="table-cell"><span class="cell-label">Số liệu</span><span>28.8%</span></div>
                                    <div class="table-cell"><span class="cell-label">So với Quý trước</span><span class="text-green-600">Tăng 0.2 điểm %</span></div>
                                    <div class="table-cell"><span class="cell-label">So với Cùng kỳ</span><span class="text-green-600">Tăng 1.0 điểm %</span></div>
                                </div>
                                <div class="table-row bg-gray-50">
                                    <div class="table-cell"><span class="cell-label">Chỉ số</span><span>Tỷ lệ lao động phi chính thức</span></div>
                                    <div class="table-cell"><span class="cell-label">Số liệu</span><span>64.3%</span></div>
                                    <div class="table-cell"><span class="cell-label">So với Quý trước</span><span class="text-red-600">Tăng 0.7 điểm %</span></div>
                                    <div class="table-cell"><span class="cell-label">So với Cùng kỳ</span><span class="text-green-600">Giảm 0.5 điểm %</span></div>
                                </div>
                                 <div class="table-row">
                                    <div class="table-cell"><span class="cell-label">Chỉ số</span><span>Tỷ lệ thất nghiệp (độ tuổi LĐ)</span></div>
                                    <div class="table-cell"><span class="cell-label">Số liệu</span><span>2.20%</span></div>
                                    <div class="table-cell"><span class="cell-label">So với Quý trước</span><span class="text-green-600">Giảm 0.02 điểm %</span></div>
                                    <div class="table-cell"><span class="cell-label">So với Cùng kỳ</span><span class="text-green-600">Giảm 0.04 điểm %</span></div>
                                </div>
                                <div class="table-row bg-gray-50">
                                    <div class="table-cell"><span class="cell-label">Chỉ số</span><span>Tỷ lệ thất nghiệp thanh niên (15-24)</span></div>
                                    <div class="table-cell"><span class="cell-label">Số liệu</span><span>7.93%</span></div>
                                    <div class="table-cell"><span class="cell-label">So với Quý trước</span><span class="text-green-600">Giảm 0.03 điểm %</span></div>
                                    <div class="table-cell"><span class="cell-label">So với Cùng kỳ</span><span class="text-green-600">Giảm 0.06 điểm %</span></div>
                                </div>
                            </div>
                        </section>

                        <!-- Chương 4 -->
                        <section id="chuong4">
                             <h2>Chương 4: Tổng hợp Chiến lược và Khuyến nghị</h2>
                             <p>Chương này chuyển hóa các phân tích thành những hành động chiến lược cụ thể, nhằm giúp các nhà lãnh đạo nhân sự không chỉ ứng phó một cách bị động mà còn có thể chủ động định hình tương lai của tổ chức mình.</p>
                             
                            <h3>4.1. Tái định vị vai trò của Đào tạo & Phát triển (L&D)</h3>
                            <p>Hoạt động L&D phải được tái định vị từ một khoản chi phí phúc lợi thành một khoản đầu tư chiến lược. Các mô hình hiệu quả cần áp dụng bao gồm học tập kết hợp (Hybrid Learning), học tập vi mô (Microlearning) và xây dựng văn hóa học tập liên tục.</p>

                            <h3>4.2. Xây dựng Lực lượng Lao động Bền vững và Kiên cường</h3>
                            <p>Tài sản quý giá nhất của tổ chức là một lực lượng lao động kiên cường. Các chiến lược cốt lõi bao gồm phát triển nhân tài nội bộ, luân chuyển công việc, hợp tác sâu rộng với các trường đại học và chú trọng sức khỏe toàn diện của nhân viên.</p>

                            <h3>4.3. Xây dựng Thương hiệu Nhà tuyển dụng Hấp dẫn</h3>
                            <p>Một thương hiệu nhà tuyển dụng mạnh mẽ là vũ khí tối quan trọng. Các xu hướng chính bao gồm chính sách đãi ngộ cạnh tranh, sự linh hoạt (Hybrid Working), văn hóa doanh nghiệp tích cực và lộ trình phát triển sự nghiệp rõ ràng.</p>
                        </section>
                    </div>
                </article>

                <!-- Interaction Section -->
                <section id="interaction" class="mt-8 bg-white p-6 sm:p-10 rounded-xl shadow-lg">
                    <h3 class="text-xl font-bold mb-4 text-center text-gray-800">Báo cáo này có hữu ích không?</h3>
                    <div class="flex flex-col sm:flex-row justify-center items-center gap-4 mb-6">
                        <button id="likeBtn" class="flex items-center justify-center gap-2 w-full sm:w-auto px-6 py-2 bg-blue-50 text-blue-700 font-semibold rounded-lg shadow-md hover:bg-blue-100 transition duration-300">
                            <i class="fa-solid fa-thumbs-up"></i>
                            <span id="likeText">Hữu ích</span>
                        </button>
                        <button id="shareBtn" class="flex items-center justify-center gap-2 w-full sm:w-auto px-6 py-2 bg-gray-100 text-gray-800 font-semibold rounded-lg shadow-md hover:bg-gray-200 transition duration-300">
                            <i class="fa-solid fa-share-nodes"></i>
                            <span>Chia sẻ</span>
                        </button>
                    </div>
                    <div class="border-t pt-6">
                        <h4 class="font-semibold text-gray-800 text-center">Để lại ý kiến hoặc yêu cầu báo cáo mới</h4>
                        <form id="commentForm" class="mt-4 space-y-4">
                            <textarea id="commentText" rows="4" class="w-full p-3 border border-gray-300 rounded-lg focus:ring-2 focus:ring-blue-500 focus:border-blue-500 transition" placeholder="Chúng tôi có thể cải thiện điều gì, hoặc bạn muốn đọc báo cáo về chủ đề nào tiếp theo?"></textarea>
                            <button type="submit" class="w-full bg-brand-blue text-white font-bold py-2.5 px-4 rounded-lg shadow-lg hover-bg-brand-blue transition duration-300">
                                Gửi ý kiến
                            </button>
                        </form>
                    </div>
                </section>
            </main>
        </div>
    </div>
    
    <!-- Footer -->
    <footer id="contact" class="bg-gray-800 text-white mt-12">
        <div class="container mx-auto px-6 py-10">
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div>
                     <img src="https://assets.stickpng.com/images/5847f9cbcef1014c0b5e48c8.png" alt="Logo NNS" class="h-12 mb-4 filter brightness-0 invert" onerror="this.onerror=null;this.src='https://placehold.co/150x50/ffffff/000000?text=NNS+Logo';">
                    <p class="text-gray-400">Tầng 5, Tòa nhà ST Moritz, 1014 Phạm Văn Đồng, P. Hiệp Bình Chánh, TP. Thủ Đức, TP. HCM</p>
                    <p class="text-gray-400 mt-2">Mã số kinh doanh: 0317402332</p>
                </div>
                <div>
                    <h3 class="text-lg font-bold mb-4">Thông tin liên hệ</h3>
                    <ul class="text-gray-400 space-y-2">
                        <li><strong>Điện thoại:</strong> <a href="tel:+84948013214" class="hover:text-blue-400">+84 948 013 214</a></li>
                        <li><strong>Email:</strong> <a href="mailto:chung@nghenhansu.vn" class="hover:text-blue-400">chung@nghenhansu.vn</a></li>
                        <li><strong>Website:</strong> <a href="https://www.nghenhansu.vn" target="_blank" class="hover:text-blue-400">www.nghenhansu.vn</a></li>
                    </ul>
                </div>
                <div>
                    <h3 class="text-lg font-bold mb-4">Kết nối với chúng tôi</h3>
                    <div class="flex space-x-4">
                        <a href="https://www.facebook.com/groups/nghenhansuvietnam" target="_blank" class="text-gray-400 hover:text-white transition text-2xl" aria-label="Facebook"><i class="fab fa-facebook-square"></i></a>
                         <a href="https://www.linkedin.com/company/nghe-nhan-su-viet-nam/" target="_blank" class="text-gray-400 hover:text-white transition text-2xl" aria-label="LinkedIn"><i class="fab fa-linkedin"></i></a>
                    </div>
                </div>
            </div>
            <div class="mt-8 border-t border-gray-700 pt-6 text-center text-sm text-gray-500">
                <p>&copy; <span id="currentYear"></span> CÔNG TY CỔ PHẦN NGHỀ NHÂN SỰ VIỆT NAM. Đã đăng ký Bản quyền.</p>
            </div>
        </div>
    </footer>
    
    <div id="loadingOverlay" class="fixed inset-0 bg-black bg-opacity-70 z-50 flex-col items-center justify-center hidden">
        <div class="w-16 h-16 border-4 border-dashed rounded-full animate-spin border-white"></div>
        <p class="text-white mt-4 text-lg">Đang tạo file PDF, vui lòng chờ...</p>
    </div>
    
    <div id="toast" class="fixed bottom-5 right-5 bg-gray-900 text-white py-2 px-5 rounded-lg shadow-lg opacity-0 transition-opacity duration-300 z-50">
        Đã sao chép liên kết vào clipboard!
    </div>

    <script>
        document.addEventListener('DOMContentLoaded', () => {
            // Set current year
            document.getElementById('currentYear').textContent = new Date().getFullYear();

            // --- Chart Implementations ---
            const brandColor = '#004a8f';

            // Chart 1: GDP Growth
            const gdpCtx = document.getElementById('gdpGrowthChart').getContext('2d');
            new Chart(gdpCtx, {
                type: 'bar',
                data: {
                    labels: ['Tăng trưởng GDP Q1 2025 (VN)', 'Dự báo WB (VN)', 'Dự báo IMF (VN)', 'Dự báo OECD (Toàn cầu)'],
                    datasets: [{
                        label: 'Tăng trưởng GDP (%)',
                        data: [6.93, 5.8, 5.2, 3.1],
                        backgroundColor: ['#22c55e', '#3b82f6', '#facc15', '#14b8a6'],
                        borderRadius: 5
                    }]
                },
                options: { responsive: true, maintainAspectRatio: false, plugins: { legend: { display: false } }, scales: { y: { beginAtZero: true, ticks: { callback: value => value + '%' } } } }
            });

            // Chart 2: Skill Gap
            const skillGapCtx = document.getElementById('skillGapChart').getContext('2d');
            new Chart(skillGapCtx, {
                type: 'doughnut',
                data: {
                    labels: ['Đã qua đào tạo', 'Chưa qua đào tạo'],
                    datasets: [{ data: [28.8, 71.2], backgroundColor: [brandColor, '#e5e7eb'], hoverOffset: 4 }]
                },
                options: { responsive: true, maintainAspectRatio: false, plugins: { legend: { position: 'top' }, tooltip: { callbacks: { label: context => `${context.label}: ${context.raw}%` } } } }
            });

            // Chart 3: ASEAN Unemployment
            const aseanCtx = document.getElementById('aseanUnemploymentChart').getContext('2d');
            new Chart(aseanCtx, {
                type: 'bar',
                data: {
                    labels: ['Việt Nam', 'Malaysia', 'Indonesia', 'Thái Lan', 'Philippines'],
                    datasets: [{ label: 'Tỷ lệ Thất nghiệp (%)', data: [2.20, 3.0, 4.76, 0.89, 4.1], backgroundColor: ['#a855f7', '#3b82f6', '#ef4444', '#22c55e', '#f97316'], borderRadius: 5 }]
                },
                 options: { indexAxis: 'y', responsive: true, maintainAspectRatio: false, plugins: { legend: { display: false } }, scales: { x: { beginAtZero: true, ticks: { callback: value => value + '%' } } } }
            });

            // --- Interaction Logic ---
            const likeBtn = document.getElementById('likeBtn');
            const shareBtn = document.getElementById('shareBtn');
            const toast = document.getElementById('toast');
            const commentForm = document.getElementById('commentForm');

            likeBtn.addEventListener('click', () => {
                likeBtn.classList.toggle('bg-blue-500');
                likeBtn.classList.toggle('text-white');
                likeBtn.classList.toggle('bg-blue-50');
                likeBtn.classList.toggle('text-blue-700');
                document.getElementById('likeText').textContent = likeBtn.classList.contains('bg-blue-500') ? 'Đã thích!' : 'Hữu ích';
            });
            
            shareBtn.addEventListener('click', () => {
                navigator.clipboard.writeText(window.location.href).then(() => {
                    toast.classList.remove('opacity-0');
                    setTimeout(() => toast.classList.add('opacity-0'), 2000);
                }).catch(err => console.error('Lỗi sao chép: ', err));
            });
            
            commentForm.addEventListener('submit', (e) => {
                e.preventDefault();
                const commentText = document.getElementById('commentText');
                if(commentText.value.trim()) {
                    alert('Cảm ơn bạn đã gửi ý kiến! Chúng tôi sẽ xem xét trong thời gian sớm nhất.');
                    commentText.value = '';
                } else {
                    alert('Vui lòng nhập ý kiến của bạn.');
                }
            });

            // --- PDF Generation Logic ---
            const { jsPDF } = window.jspdf;
            const downloadBtn = document.getElementById('downloadBtn');
            const reportElement = document.getElementById('report-content-wrapper');
            const loadingOverlay = document.getElementById('loadingOverlay');

            downloadBtn.addEventListener('click', () => {
                loadingOverlay.classList.remove('hidden');
                loadingOverlay.classList.add('flex');
                
                html2canvas(reportElement, {
                    scale: 2, useCORS: true, windowWidth: reportElement.scrollWidth, windowHeight: reportElement.scrollHeight
                }).then(canvas => {
                    const imgData = canvas.toDataURL('image/png', 1.0);
                    const pdf = new jsPDF({ orientation: 'portrait', unit: 'pt', format: 'a4' });
                    const pdfWidth = pdf.internal.pageSize.getWidth();
                    const pdfHeight = pdf.internal.pageSize.getHeight();
                    const ratio = canvas.width / pdfWidth;
                    const imgHeight = canvas.height / ratio;
                    let heightLeft = imgHeight;
                    let position = 0;

                    pdf.addImage(imgData, 'PNG', 0, position, pdfWidth, imgHeight);
                    heightLeft -= pdfHeight;

                    while (heightLeft > 0) {
                        position -= pdfHeight;
                        pdf.addPage();
                        pdf.addImage(imgData, 'PNG', 0, position, pdfWidth, imgHeight);
                        heightLeft -= pdfHeight;
                    }

                    pdf.save('Bao_cao_Thi_truong_Lao_dong_2024_2025_NNS.pdf');
                    loadingOverlay.classList.add('hidden');
                }).catch(error => {
                    console.error("Lỗi khi tạo PDF: ", error);
                    loadingOverlay.classList.add('hidden');
                    alert("Đã có lỗi xảy ra khi tạo file PDF.");
                });
            });

            // --- Active TOC Link on Scroll ---
            const sections = document.querySelectorAll('section[id]');
            const tocLinks = document.querySelectorAll('#table-of-contents a');

            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        tocLinks.forEach(link => {
                            link.classList.remove('active');
                            if (link.getAttribute('href').substring(1) === entry.target.id) {
                                link.classList.add('active');
                            }
                        });
                    }
                });
            }, { rootMargin: "-50% 0px -50% 0px" });

            sections.forEach(section => {
                observer.observe(section);
            });
        });
    </script>
</body>
</html>
