<!DOCTYPE html>
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Ôn tập KHTN 9: Năng lượng và Công - THCS Thủy Phương</title>
    <script src="https://polyfill.io/v3/polyfill.min.js?features=es6"></script>
    <script id="MathJax-script" async src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js"></script>
    <style>
        :root {
            --primary-color: #0f172a;
            --secondary-color: #1d4ed8;
            --light-bg: #f8fafc;
            --white: #ffffff;
            --text-dark: #1e293b;
            --danger: #dc2626;
            --success: #16a34a;
            --warning: #ea580c;
            --vn-red: #da251d;
            --vn-yellow: #ffff00;
            --accent: #7c3aed;
        }

        * { box-sizing: border-box; font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif; margin: 0; padding: 0; }
        body { background-color: var(--light-bg); color: var(--text-dark); min-height: 100vh; display: flex; flex-direction: column; overflow-x: hidden; }

        header { background-color: var(--primary-color); color: var(--white); padding: 1rem; text-align: center; border-bottom: 4px solid var(--secondary-color); position: sticky; top: 0; z-index: 100; }
        header h1 { font-size: 1.2rem; text-transform: uppercase; letter-spacing: 1px; }

        .container { max-width: 900px; margin: 0 auto; padding: 1rem; width: 100%; flex-grow: 1; display: flex; flex-direction: column; }
        .screen { display: none; background: var(--white); padding: 1.5rem; border-radius: 16px; box-shadow: 0 4px 20px rgba(0,0,0,0.08); animation: fadeIn 0.4s ease; border: 1px solid #e2e8f0; }
        .screen.active { display: block; }
        @keyframes fadeIn { from { opacity: 0; transform: translateY(10px); } to { opacity: 1; transform: translateY(0); } }

        /* --- Instruction Overlay --- */
        #instruction-overlay {
            position: fixed; top: 0; left: 0; width: 100%; height: 100%;
            background: rgba(15, 23, 42, 0.98); color: white; z-index: 9999;
            display: none; align-items: center; justify-content: center; padding: 15px;
            backdrop-filter: blur(10px);
        }
        .instruction-content {
            background: rgba(30, 41, 59, 0.9); padding: 2rem; border-radius: 20px;
            max-width: 650px; width: 95%; text-align: center; border: 1px solid rgba(255, 255, 255, 0.2);
            overflow: hidden;
        }
        .instruction-content h2 { color: var(--vn-yellow); margin-bottom: 1.5rem; font-size: 1.8rem; text-transform: uppercase; font-weight: 800; }
        .instruction-content ul { text-align: left; margin-bottom: 2rem; width: 100%; }
        .instruction-content li { 
            margin-bottom: 1rem; 
            font-size: 1.05rem; 
            list-style: none; 
            white-space: nowrap; 
            display: flex;
            align-items: center;
            width: 100%;
            overflow-x: auto; 
            scrollbar-width: none;
        }
        .instruction-content li::-webkit-scrollbar { display: none; }
        .instruction-content li::before { content: "✦"; color: var(--vn-yellow); margin-right: 12px; flex-shrink: 0; }
        .countdown-timer { font-weight: bold; color: var(--vn-yellow); font-size: 2rem; margin-top: 1rem; }

        /* --- UI Elements --- */
        .info-bar { display: flex; justify-content: space-between; align-items: center; background: var(--primary-color); color: white; padding: 0.8rem 1.2rem; border-radius: 12px; margin-bottom: 1.2rem; font-size: 0.9rem; flex-wrap: wrap; gap: 10px; }
        .timer-box { background: rgba(255,255,255,0.15); padding: 0.4rem 0.8rem; border-radius: 8px; font-weight: bold; font-family: monospace; font-size: 1.1rem; min-width: 85px; text-align: center; }
        
        .vn-flag { width: 24px; height: 16px; background: var(--vn-red); position: relative; border: 1px solid white; display: inline-block; vertical-align: middle; margin: 0 4px; flex-shrink: 0; }
        .vn-flag::after { content: "★"; position: absolute; top: 50%; left: 50%; transform: translate(-50%, -50%); color: var(--vn-yellow); font-size: 9px; }

        .question-header { font-size: 1.3rem; font-weight: 800; color: var(--secondary-color); margin-bottom: 0.8rem; padding-bottom: 0.6rem; border-bottom: 2px solid #f1f5f9; display: flex; justify-content: space-between; align-items: center; }
        .question-text { font-size: 1.15rem; line-height: 1.6; margin-bottom: 1.5rem; color: #1e293b; font-weight: 500; text-align: left; }

        .option-item { padding: 1rem; border: 2px solid #f1f5f9; border-radius: 12px; cursor: pointer; margin-bottom: 0.8rem; transition: 0.2s; font-size: 1.05rem; background: #fff; display: flex; align-items: center; gap: 10px; text-align: left; }
        .option-item:hover { background-color: #f8fafc; border-color: #cbd5e1; }
        .option-item.selected { border-color: var(--secondary-color); background-color: #eff6ff; font-weight: 700; box-shadow: 0 4px 10px rgba(29, 78, 216, 0.1); }

        .tf-row { padding: 1rem 0; border-bottom: 1px solid #f1f5f9; }
        .tf-statement { font-size: 1.05rem; margin-bottom: 0.8rem; line-height: 1.5; color: #334155; text-align: left; }
        .tf-buttons { display: flex; gap: 10px; }
        .btn-tf { flex: 1; padding: 0.6rem; border: 2px solid #e2e8f0; border-radius: 10px; cursor: pointer; font-weight: 800; background: #fff; transition: 0.2s; font-size: 0.9rem; }
        .btn-tf.active-true { background: var(--success); color: white; border-color: var(--success); }
        .btn-tf.active-false { background: var(--danger); color: white; border-color: var(--danger); }

        .short-answer-input { width: 100%; padding: 1rem; border: 3px solid #e2e8f0; border-radius: 12px; font-size: 1.4rem; outline: none; text-align: center; font-weight: bold; color: var(--secondary-color); transition: 0.3s; }

        .btn { padding: 0.8rem 1.4rem; border: none; border-radius: 10px; font-weight: bold; cursor: pointer; transition: 0.2s; display: inline-flex; align-items: center; justify-content: center; gap: 8px; font-size: 0.95rem; }
        .btn-primary { background-color: var(--secondary-color); color: white; }
        .btn-star { background-color: var(--accent); color: white; }
        .btn-danger { background-color: var(--danger); color: white; }
        .btn-warning { background-color: var(--warning); color: white; }
        .btn-star.used { opacity: 0.5; cursor: not-allowed; }

        #review-box { margin-top: 1rem; padding: 1.2rem; background: #fff7ed; border-left: 6px solid var(--warning); border-radius: 12px; display: none; animation: slideIn 0.3s ease; text-align: left; }
        @keyframes slideIn { from { opacity: 0; transform: translateX(-15px); } to { opacity: 1; transform: translateX(0); } }
        
        #toast { position: fixed; top: 15px; left: 50%; transform: translateX(-50%); background: var(--success); color: white; padding: 0.8rem 1.5rem; border-radius: 40px; z-index: 10001; display: none; font-weight: bold; box-shadow: 0 8px 20px rgba(0,0,0,0.15); font-size: 0.9rem; }

        /* History Review Cards */
        .history-card { margin-bottom: 2rem; padding: 1.5rem; border: 1px solid #e2e8f0; border-radius: 15px; background: #fff; box-shadow: 0 2px 10px rgba(0,0,0,0.02); text-align: left; }
        .history-q-text { font-weight: 800; margin-bottom: 1rem; color: var(--primary-color); font-size: 1.1rem; line-height: 1.5; }
        .history-option { padding: 1rem; border-radius: 10px; margin-bottom: 0.6rem; border: 2px solid #f1f5f9; font-size: 1rem; display: flex; align-items: center; gap: 10px; }
        .history-option.correct { background-color: #dcfce7; border-color: #22c55e; color: #166534; font-weight: 600; }
        .history-option.wrong { background-color: #fee2e2; border-color: #ef4444; color: #991b1b; }
        .history-explanation { margin-top: 1.5rem; padding: 1.2rem; background: #eff6ff; border-radius: 12px; border-left: 6px solid var(--secondary-color); color: #1e40af; line-height: 1.7; font-size: 0.95rem; }

        footer { background: #f1f5f9; text-align: center; padding: 1rem; font-size: 0.8rem; color: #64748b; border-top: 1px solid #e2e8f0; margin-top: auto; }

        /* ========================================================
           BỔ SUNG CSS MEDIA QUERIES ĐỂ ĐÁP ỨNG MỌI KHUNG HÌNH (RESPONSIVE)
           ======================================================== */
        
        /* Tablet & Mobile chung */
        @media (max-width: 768px) {
            /* Ép các thẻ div dùng inline style grid 2 cột về 1 cột */
            div[style*="grid-template-columns:1fr 1fr"] {
                grid-template-columns: 1fr !important;
            }
            div[style*="display:grid;grid-template-columns:1fr 1fr;gap:1rem;margin-bottom:1.5rem"] {
                grid-template-columns: 1fr !important;
            }
            div[style*="display:grid;grid-template-columns:1fr 1fr;gap:1rem"] {
                grid-template-columns: 1fr !important;
            }
            .info-bar { flex-direction: column; align-items: stretch; text-align: center; }
            .info-bar > div:last-child { justify-content: center; margin-top: 10px; }
            .question-header { flex-direction: column; align-items: flex-start; gap: 8px; }
        }

        /* Mobile nhỏ */
        @media (max-width: 600px) {
            header h1 { font-size: 1.1rem; }
            .container { padding: 0.5rem; }
            .screen { padding: 1rem; border-radius: 12px; }
            .instruction-content { padding: 1.5rem; }
            .instruction-content h2 { font-size: 1.4rem; }
            .instruction-content li { 
                font-size: 0.9rem; 
                white-space: normal; /* Cho phép rớt dòng trên điện thoại */
                align-items: flex-start;
            }
            .instruction-content li::before { margin-top: 2px; }
            .btn { width: 100%; padding: 0.9rem; justify-content: center; }
            .nav-buttons { flex-direction: column; gap: 10px !important; }
            #final-score { font-size: 3.5rem !important; }
            .tf-buttons { flex-direction: column; }
            .option-item { font-size: 0.95rem; padding: 0.8rem; }
            .question-text { font-size: 1.05rem; }
        }
    </style>
</head>
<body>

<header><h1>NĂNG LƯỢNG VÀ CÔNG - KHTN 9</h1></header>
<div id="toast"></div>

<div id="instruction-overlay">
    <div class="instruction-content">
        <h2>THỂ LỆ LUYỆN TẬP</h2>
        <ul>
            <li> Khởi đầu với 6 lá cờ <div class="vn-flag"></div>.</li>
            <li> Mỗi câu đúng nhận 1 lá cờ .</li>
            <li> Sử dụng "Gợi ý tư duy" tốn 2 lá cờ <div class="vn-flag"></div>.</li>
            <li> "Ngôi sao hy vọng": Chỉ ở Phần III, ĐÚNG nhận 4 lá cờ <div class="vn-flag"></div>.</li>
            <li> LƯU Ý: Không được phép quay lại câu trước đó.</li>
        </ul>
        <div class="countdown-timer">Bắt đầu sau: <span id="instr-countdown">10</span> giây</div>
    </div>
</div>

<div class="container">
    <div id="screen-login" class="screen active">
        <h2 style="text-align:center; margin-bottom:1.5rem; color:var(--primary-color); font-weight: 800;">THÔNG TIN NGƯỜI HỌC</h2>
        <div style="margin-bottom:1rem"><label style="display:block;margin-bottom:0.3rem;font-weight:600;font-size:0.9rem">Số báo danh:</label><input type="text" id="input-sbd" style="width:100%;padding:0.8rem;border:2px solid #cbd5e1;border-radius:8px" placeholder="Ví dụ: 011"></div>
        <div style="margin-bottom:1rem"><label style="display:block;margin-bottom:0.3rem;font-weight:600;font-size:0.9rem">Họ và tên:</label><input type="text" id="input-name" style="width:100%;padding:0.8rem;border:2px solid #cbd5e1;border-radius:8px" placeholder="Ví dụ: Nguyễn Chính Việt Anh"></div>
        <div style="display:grid;grid-template-columns:1fr 1fr;gap:1rem;margin-bottom:1.5rem">
            <div><label style="display:block;margin-bottom:0.3rem;font-weight:600;font-size:0.9rem">Lớp:</label><input type="text" id="input-class" style="width:100%;padding:0.8rem;border:2px solid #cbd5e1;border-radius:8px" placeholder="Ví dụ: 9/1"></div>
            <div><label style="display:block;margin-bottom:0.3rem;font-weight:600;font-size:0.9rem">Trường:</label><input type="text" id="input-school" style="width:100%;padding:0.8rem;border:2px solid #cbd5e1;border-radius:8px" placeholder="Ví dụ: THCS Thủy Phương"></div>
        </div>
        <div style="display:grid;grid-template-columns:1fr 1fr;gap:1rem">
            <button class="btn" style="border:2.5px solid var(--secondary-color); color:var(--secondary-color); background: #fff;" onclick="triggerInstructions()">LUYỆN TẬP</button>
            <button class="btn btn-primary" onclick="confirmExam()">KIỂM TRA</button>
        </div>
    </div>

    <div id="screen-game" class="screen">
        <div class="info-bar">
            <div id="user-display"></div>
            <div style="display:flex; gap:12px; align-items:center">
                <div class="timer-box" id="timer">00:00</div>
                <div id="flag-display" style="display:none; font-weight:bold;"><div class="vn-flag"></div> <span id="flag-count">6</span></div>
            </div>
        </div>
        <div id="question-box"></div>
        <div id="review-box">
            <strong style="color:var(--danger); font-size: 0.95rem;">KẾT QUẢ CHƯA ĐÚNG! Hãy lưu ý:</strong>
            <div id="review-content" style="margin-top:0.4rem; font-size:0.95rem; line-height:1.6;"></div>
        </div>
        <div class="nav-buttons" style="display:flex; justify-content:flex-end; margin-top:2rem; gap:10px">
            <button class="btn btn-warning" id="btn-hint" onclick="useHint()" style="display:none">💡 Gợi ý tư duy</button>
            <button class="btn btn-star" id="btn-star" onclick="activateStar()" style="display:none">⭐ Ngôi sao hy vọng</button>
            <button class="btn btn-primary" id="btn-next" onclick="validateAndNext()">Tiếp theo ➜</button>
            <button class="btn btn-danger" id="btn-submit" onclick="showSubmitConfirm()" style="display:none">Nộp bài 🏁</button>
        </div>
    </div>

    <div id="screen-result" class="screen">
        <div style="text-align:center">
            <h2 id="result-header" style="color:var(--primary-color); font-size: 1.5rem; margin-bottom: 0.8rem;"></h2>
            <div style="font-size:5rem; font-weight:900; color:var(--secondary-color); margin:1rem 0" id="final-score">0.0</div>
            <div id="rank-label" style="display: inline-block; padding: 0.6rem 2rem; border-radius: 30px; color: white; font-weight: bold; margin-bottom: 2.5rem; font-size: 1.2rem; text-transform: uppercase;"></div>
            <button class="btn btn-primary" style="width:100%; margin-bottom:1rem; height: 3.5rem; font-size: 1.1rem;" onclick="toggleHistory()">Xem giải thích chi tiết đáp án</button>
            <button class="btn" style="width:100%; border:1px solid #cbd5e1; height: 3.5rem; font-size: 1.1rem; color: #475569;" onclick="location.reload()">Quay lại màn hình chính</button>
        </div>
        <div id="history-area" style="display:none; margin-top:2.5rem; border-top:2px solid #f1f5f9; padding-top:2rem">
            <div id="history-list"></div>
        </div>
    </div>
</div>

<footer>Bản quyền thuộc về Trường THCS Thuỷ Phương, Thành phố Huế</footer>

<script>
    const apiKey = ""; 

    // --- NGÂN HÀNG CÂU HỎI LUYỆN TẬP ---
    const rawMCQ = [
        { id: "Q1", question: "Động năng của một vật phụ thuộc vào những yếu tố nào?", options: ["Khối lượng và vận tốc.", "Khối lượng và độ cao.", "Trọng lượng và vận tốc.", "Lực tác dụng và quãng đường."], correctAnswer: "Khối lượng và vận tốc.", hint: "Năng lượng chuyển động tỉ lệ thuận với khối lượng và bình phương vận tốc.", explanation: "Động năng \\(W_d = \\frac{1}{2}mv^2\\), phụ thuộc vào khối lượng m và vận tốc v." },
        { id: "Q2", question: "Thế năng trọng trường của một vật được tính bằng công thức nào?", options: ["\\(W_t = Ph\\)", "\\(W_t = \\frac{1}{2}mv^2\\)", "\\(W_t = Fs\\)", "\\(W_t = P/t\\)"], correctAnswer:"\\(W_t = Ph\\)", hint: "Năng lượng này phụ thuộc trực tiếp vào độ cao h so với mốc chọn làm thế năng.", explanation: "Thế năng trọng trường \\(W_t = Ph\\)" },
        { id: "Q3", question: "Đơn vị của công cơ học trong hệ SI là gì?", options: ["Joule (J).", "Watt (W).", "Newton (N).", "Pascal (Pa)."], correctAnswer: "Joule (J).", hint: "Đơn vị này mang tên nhà vật lý James Prescott Joule, kí hiệu là chữ J.", explanation: "Đơn vị của công là Joule (J)." },
        { id: "Q4", question: "Đại lượng nào đặc trưng cho tốc độ thực hiện công?", options: ["Công suất.", "Công cơ học.", "Cơ năng.", "Thế năng."], correctAnswer: "Công suất.", hint: "Xác định xem trong cùng 1 giây, máy nào thực hiện được nhiều công hơn.", explanation: "Công suất \\(P = A/t\\) đặc trưng cho tốc độ thực hiện công." },
        { id: "Q5", question: "Cơ năng của một vật bao gồm những thành phần nào?", options: ["Động năng và thế năng.", "Nhiệt năng và động năng.", "Thế năng và hóa năng.", "Điện năng và cơ năng."], correctAnswer: "Động năng và thế năng.", hint: "Cơ năng là tổng các dạng năng lượng cơ học mà vật sở hữu.", explanation: "Cơ năng \\(W = W_d + W_t\\)." },
        { id: "Q6", question: "Khi một vật rơi tự do, đại lượng nào tăng dần (bỏ qua sức cản)?", options: ["Động năng.", "Thế năng.", "Cơ năng.", "Khối lượng."], correctAnswer: "Động năng.", hint: "Khi rơi, độ cao giảm (thế năng giảm) và vận tốc tăng dần.", explanation: "Khi rơi, thế năng chuyển hóa thành động năng, làm vận tốc tăng." },
        { id: "Q7", question: "Lực 20 N kéo vật dịch chuyển 5 m theo phương của lực. Công thực hiện là:", options: ["100 J.", "4 J.", "25 J.", "0,25 J."], correctAnswer: "100 J.", hint: "Áp dụng công thức tính công cơ bản: A = F . s", explanation: "\\(A = 20 \\cdot 5 = 100\\text{ J}.\\)" },
        { id: "Q8", question: "Đơn vị của công suất là gì?", options: ["Watt (W).", "Joule (J).", "Newton (N).", "Mã lực (HP)."], correctAnswer: "Watt (W).", hint: "Kí hiệu đơn vị này là W, thường thấy trên các thiết bị điện tử.", explanation: "Đơn vị SI của công suất là Watt (W)." },
        { id: "Q9", question: "Khi vật lên cao, thế năng trọng trường của nó thay đổi như thế nào?", options: ["Tăng lên.", "Giảm đi.", "Không đổi.", "Bằng không."], correctAnswer: "Tăng lên.", hint: "Thế năng trọng trường tỉ lệ thuận với độ cao h.", explanation: "Vì \\(W_t = Ph\\), h tăng thì \\(W_t\\) tăng." },
        { id: "Q10", question: "Cơ năng được bảo toàn khi nào?", options: ["Bỏ qua ma sát và sức cản.", "Có lực ma sát tác dụng.", "Vật đứng yên.", "Vật đang nóng lên."], correctAnswer: "Bỏ qua ma sát và sức cản.", hint: "Khi không có sự hao phí năng lượng chuyển thành nhiệt năng.", explanation: "Nếu chỉ chịu tác dụng của lực phát động, cơ năng được bảo toàn." },
        { id: "Q11", question: "Một người xách túi thực phẩm đi bộ trên đường nằm ngang, lực kéo của tay có sinh công không?", options: ["Không sinh công.", "Có sinh công dương.", "Có sinh công âm.", "Phụ thuộc vận tốc."], correctAnswer: "Không sinh công.", hint: "Lực nâng có phương thẳng đứng, vuông góc với phương dịch chuyển nằm ngang.", explanation: "Lực vuông góc với phương dịch chuyển thì không sinh công." },
        { id: "Q12", question: "Công suất 1 kW tương ứng với bao nhiêu Watt?", options: ["1000 W.", "100 W.", "10 W.", "10000 W."], correctAnswer: "1000 W.", hint: "Kilo (k) là tiền tố có giá trị bằng một nghìn.", explanation: "1 kW = 1000 W." }
    ];

    const rawTF = [
        { id: "TF1", context: "Xét một quả bóng được ném thẳng đứng lên cao (bỏ qua sức cản không khí).", statements: ["a) Trong quá trình bóng đi lên, động năng giảm dần.", "b) Tại vị trí cao nhất, cơ năng của bóng bằng 0.", "c) Thế năng trọng trường đạt giá trị lớn nhất tại điểm cao nhất.", "d) Động năng chuyển hóa thành thế năng khi bóng đi lên."], correctPattern: [true, false, true, true], hint: "Độ cao tăng làm thế năng tăng; vận tốc giảm làm động năng giảm.", explanation: "b Sai vì tại điểm cao nhất cơ năng được bảo toàn và bằng thế năng cực đại." },
        { id: "TF2", context: "Về các đơn vị và công thức tính Công và Công suất.", statements: ["a) Công suất cho biết công thực hiện trong 1 giây.", "b) Một máy có công suất lớn thì thực hiện công nhanh hơn.", "c) 1 Joule trên giây (J/s) bằng 1 Watt (W).", "d) Công cơ học chỉ xuất hiện khi có lực làm vật dịch chuyển."], correctPattern: [true, true, true, true], hint: "Hãy nhớ định nghĩa P = A/t và điều kiện để có công cơ học.", explanation: "Tất cả các ý đều đúng theo lý thuyết Vật lý 9." },
        { id: "TF3", context: "Sự chuyển hóa năng lượng của con lắc đơn.", statements: ["a) Ở vị trí thấp nhất, động năng đạt cực đại.", "b) Ở vị trí biên (cao nhất), thế năng đạt cực đại.", "c) Cơ năng giảm dần do ma sát với không khí (thực tế).", "d) Động năng tỉ lệ thuận với độ cao của con lắc."], correctPattern: [true, true, true, false], hint: "Vận tốc lớn nhất ở đáy, độ cao lớn nhất ở biên.", explanation: "d Sai vì khi độ cao tăng thì động năng giảm (chuyển hóa thành thế năng)." },
        { id: "TF4", context: "Công cơ học trong đời sống thực tế.", statements: ["a) Vận động viên giữ tạ đứng yên trên cao có sinh công cơ học.", "b) Máy xúc nâng khối đá lên cao có sinh công cơ học.", "c) Lực ma sát sinh công làm hao mòn lốp xe.", "d) Lực càng lớn và quãng đường càng dài thì công càng lớn."], correctPattern: [false, true, true, true], hint: "Công cơ học yêu cầu phải có cả lực và sự dịch chuyển quãng đường s > 0.", explanation: "a Sai vì vật đứng yên (s = 0) nên công thực hiện bằng 0." }
    ];

    const rawShort = [
        { id: "SA1", question: "Tính công thực hiện khi lực 50 N đẩy xe đi được 10 m theo phương của lực (J).", answer: "500", hint: "Tính theo tích số: A = F . s", explanation: "\\(A = 50 \\cdot 10 = 500\\text{ J}.\\)" },
        { id: "SA2", question: "Một máy thực hiện công 3000 J trong 1 phút. Tính công suất của máy (W).", answer: "50", hint: "Công suất P = A / t. Lưu ý đổi 1 phút = 60 giây.", explanation: "\\(P = 3000 / 60 = 50\\text{ W}.\\)" },
        { id: "SA3", question: "Vật khối lượng 2 kg đang chạy với vận tốc 4 m/s. Tính động năng (J).", answer: "16", hint: "Động năng bằng 1/2 nhân khối lượng nhân bình phương vận tốc.", explanation: "\\(W_d = 0,5 \\cdot 2 \\cdot 4^2 = 16\\text{ J}.\\)" },
        { id: "SA4", question: "Vật nặng 1 kg ở độ cao 5 m. Lấy g = 10 m/s². Tính thế năng trọng trường (J).", answer: "50", hint: "Thế năng trọng trường Wt = m . g . h", explanation: "\\(W_t = 1 \\cdot 10 \\cdot 5 = 50\\text{ J}.\\)" }
    ];

    // --- NGÂN HÀNG CÂU HỎI KIỂM TRA ---
    const examMCQ = [
        { id: "EQ1", question: "Vật m = 2 kg rơi từ độ cao 10 m. Bỏ qua sức cản (lấy g = 10). Động năng khi chạm đất là bao nhiêu?", options: ["200 J.", "100 J.", "20 J.", "0 J."], correctAnswer: "200 J.", explanation: "Bảo toàn cơ năng: Động năng cực đại khi chạm đất bằng thế năng cực đại: \\(W_d = Ph = 2 \\cdot 10 \\cdot 10 = 200\\text{ J}.\\)" },
        { id: "EQ2", question: "Một ôtô có công suất 50 kW chuyển động đều với vận tốc 72 km/h. Lực kéo của động cơ là", options: ["2500 N.", "5000 N.", "694 N.", "3600 N."], correctAnswer: "2500 N.", explanation: "\\(v = 72\\text{ km/h} = 20\\text{ m/s}\\). Ta có \\(P = F \\cdot v \\Rightarrow F = P/v = 50000 / 20 = 2500\\text{ N}.\\)" },
        { id: "EQ3", question: "Ném vật m = 500g thẳng đứng lên cao với vận tốc 10 m/s (g = 10). Độ cao cực đại vật đạt được là:", options: ["5 m.", "10 m.", "2,5 m.", "20 m."], correctAnswer: "5 m.", explanation: "Bảo toàn cơ năng: \\(\\frac{1}{2}mv^2 = Ph \\Rightarrow h = \\frac{v^2}{2g} = \\frac{100}{20} = 5\\text{ m}.\\)" },
        { id: "EQ4", question: "Nếu vận tốc của một vật tăng lên 2 lần và khối lượng của nó giảm đi một nửa thì động năng của vật sẽ:", options: ["Tăng 2 lần.", "Không đổi.", "Tăng 4 lần.", "Giảm 2 lần."], correctAnswer: "Tăng 2 lần.", explanation: "Khối lượng m' = m/2, v' = 2v. Khi đó \\(W_d' = \\frac{1}{2} (m/2) (2v)^2 = 2 \\cdot (\\frac{1}{2}mv^2) = 2 W_d\\)." },
        { id: "EQ5", question: "Một thác nước cao 30 m, mỗi giây đổ xuống 10 m³ nước (khối lượng riêng 1000 kg/m³, g=10). Công suất của thác nước là:", options: ["3 MW.", "300 kW.", "30 kW.", "3 W."], correctAnswer: "3 MW.", explanation: "Khối lượng \\(m = 10 \\cdot 1000 = 10000\\text{ kg}\\). Công suất \\(P = \\frac{Ph}{t} = \\frac{10000 \\cdot 10 \\cdot 30}{1} = 3000000\\text{ W} = 3\\text{ MW}.\\)" },
        { id: "EQ6", question: "Tại vị trí động năng bằng 3 lần thế năng, một vật được ném thẳng đứng lên cao có độ cao bằng bao nhiêu phần độ cao cực đại?", options: ["1/4.", "1/3.", "1/2.", "3/4."], correctAnswer: "1/4.", explanation: "Cơ năng \\(W = W_d + W_t = 3W_t + W_t = 4W_t\\). Do \\(W = Ph_{max}\\) và \\(W_t = Ph\\) nên \\(Ph_{max} = 4Ph \\Rightarrow h = h_{max}/4\\)." },
        { id: "EQ7", question: "Một cần cẩu nâng vật nặng 1 tấn lên cao 5 m trong 10 s. Biết hiệu suất của động cơ là 80% (g=10). Công suất toàn phần của động cơ là:", options: ["6250 W.", "5000 W.", "4000 W.", "10000 W."], correctAnswer: "6250 W.", explanation: "Công có ích: \\(A_i = Ph = 1000 \\cdot 10 \\cdot 5 = 50000\\text{ J}\\). Công suất có ích \\(P_i = 5000\\text{ W}\\). Công suất toàn phần \\(P_{tp} = P_i / 0,8 = 6250\\text{ W}.\\)" },
        { id: "EQ8", question: "Công của lực phanh làm một ôtô khối lượng 1 tấn giảm vận tốc từ 20 m/s xuống còn 10 m/s là:", options: ["-150 kJ.", "150 kJ.", "-50 kJ.", "50 kJ."], correctAnswer: "-150 kJ.", explanation: "Độ biến thiên động năng: \\(A = \\Delta W_d = \\frac{1}{2}m(v_2^2 - v_1^2) = 0,5 \\cdot 1000 \\cdot (100 - 400) = -150000\\text{ J} = -150\\text{ kJ}.\\)" },
        { id: "EQ9", question: "Một quả bóng khối lượng 200g rơi từ độ cao 5m xuống đất và nảy lên đến độ cao 3m (g=10). Phần cơ năng đã chuyển hóa thành nhiệt năng là:", options: ["4 J.", "6 J.", "10 J.", "16 J."], correctAnswer: "4 J.", explanation: "Cơ năng hao phí: \\(\\Delta W = W_{t1} - W_{t2} = Ph_1 - Ph_2 = 0,2 \\cdot 10 \\cdot (5 - 3) = 4\\text{ J}.\\)" },
        { id: "EQ10", question: "Động cơ điện có công suất 2 kW dùng để kéo một vật nặng 100 kg lên cao đều (g=10). Vận tốc kéo vật là:", options: ["2 m/s.", "20 m/s.", "0,2 m/s.", "5 m/s."], correctAnswer: "2 m/s.", explanation: "\\(P = F \\cdot v = mg \\cdot v \\Rightarrow v = \\frac{P}{mg} = \\frac{2000}{100 \\cdot 10} = 2\\text{ m/s}.\\)" },
        { id: "EQ11", question: "Hai vật có cùng khối lượng. Vật 1 trượt trên dốc nghiêng không ma sát, vật 2 rơi tự do từ cùng một độ cao. So sánh động năng của hai vật khi chạm đất:", options: ["Bằng nhau.", "Vật 1 lớn hơn.", "Vật 2 lớn hơn.", "Không đủ dữ kiện."], correctAnswer: "Bằng nhau.", explanation: "Theo định luật bảo toàn cơ năng, vì xuất phát từ cùng một độ cao (cùng thế năng) và không có ma sát nên động năng khi chạm đất phải bằng nhau." },
        { id: "EQ12", question: "Dùng mặt phẳng nghiêng dài 4 m để kéo vật nặng 50 kg lên cao 1 m. Nếu lực kéo là 150 N thì độ lớn lực ma sát là bao nhiêu? (Lấy g=10)", options: ["25 N.", "125 N.", "50 N.", "100 N."], correctAnswer: "25 N.", explanation: "Công có ích \\(A_i = 50 \\cdot 10 \\cdot 1 = 500\\text{ J}\\). Công toàn phần \\(A_{tp} = F \\cdot s = 150 \\cdot 4 = 600\\text{ J}\\). Công ma sát \\(A_{ms} = 600 - 500 = 100\\text{ J}\\). Suy ra \\(F_{ms} = \\frac{100}{4} = 25\\text{ N}.\\)" }
    ];

    const examTF = [
        { id: "ETF1", context: "Một vật trượt có ma sát từ đỉnh dốc xuống chân mặt phẳng nghiêng.", statements: ["a) Cơ năng của vật được bảo toàn trong suốt quá trình.", "b) Độ giảm thế năng bằng tổng độ tăng động năng và công của lực ma sát.", "c) Động năng của vật tại chân dốc luôn bằng thế năng tại đỉnh dốc.", "d) Công của trọng lực tác dụng lên vật là một đại lượng dương."], correctPattern: [false, true, false, true], explanation: "a Sai vì có ma sát nên cơ năng không bảo toàn. c Sai vì động năng sẽ nhỏ hơn thế năng ban đầu do mất mát năng lượng." },
        { id: "ETF2", context: "Một thang máy kéo khối lượng 500 kg đi lên đều with vận tốc 2 m/s (g=10).", statements: ["a) Lực kéo của động cơ thang máy phải lớn hơn trọng lượng buồng thang.", "b) Công suất của động cơ thang máy là 10 kW.", "c) Trong 5 giây, động cơ thang máy thực hiện được công là 50000 J.", "d) Nếu thang máy đi lên nhanh dần, lực kéo của động cơ sẽ nhỏ hơn trọng lượng."], correctPattern: [false, true, true, false], explanation: "a Sai vì chuyển động đều nên lực kéo bằng trọng lượng. b Đúng vì \\(P = 5000 \\cdot 2 = 10000\\text{ W}\\). d Sai vì nhanh dần thì lực kéo phải lớn hơn." },
        { id: "ETF3", context: "Hai xe ôtô có khối lượng \\(m_1 = 2m_2\\), chạy with vận tốc \\(v_1 = \\frac{v_2}{2}\\).", statements: ["a) Động năng của hai xe là hoàn toàn bằng nhau.", "b) Nếu hãm phanh with cùng một lực, quãng đường phanh của xe 2 dài gấp đôi xe 1.", "c) Động năng của xe 2 lớn gấp 2 lần động năng của xe 1.", "d) Quán tính của xe 1 lớn gấp 2 lần quán tính của xe 2."], correctPattern: [false, true, true, true], explanation: "a Sai vì \\(W_{d1} = \\frac{1}{2}(2m_2)(v_2/2)^2 = \\frac{1}{4}m_2 v_2^2 = \\frac{W_{d2}}{2}\\). c Đúng." },
        { id: "ETF4", context: "Một vật được ném thẳng đứng lên cao trong không khí (có lực cản).", statements: ["a) Lực cản của không khí sinh công âm trong suốt quá trình chuyển động.", "b) Cơ năng của vật giảm dần theo thời gian do sự hao phí.", "c) Tại điểm cao nhất, gia tốc của vật bằng 0.", "d) Thời gian vật rơi xuống nhỏ hơn thời gian vật ném lên."], correctPattern: [true, true, false, false], explanation: "c Sai vì gia tốc tại điểm cao nhất bằng g hướng xuống. d Sai vì do mất cơ năng, vận tốc rơi giảm, làm thời gian đi xuống lớn hơn." }
    ];

    const examShort = [
        { id: "ESA1", question: "Một máy bơm có công suất 2 kW. Trong 10 phút, máy bơm thực hiện một công là bao nhiêu kJ?", answer: "1200", explanation: "\\(P = 2\\text{ kW} = 2000\\text{ W}. t = 10 \\cdot 60 = 600\\text{ s}. A = 2000 \\cdot 600 = 1200000\\text{ J} = 1200\\text{ kJ}.\\)" },
        { id: "ESA2", question: "Kéo một vật 50 kg lên cao bằng 1 ròng rọc động (lợi 2 lần về lực). Bỏ qua ma sát. Lực kéo tác dụng vào dây là bao nhiêu N?", answer: "250", explanation: "Trọng lượng vật \\(P = 500\\text{ N}\\). Dùng 1 ròng rọc động nên lực kéo giảm một nửa: \\(F = 500/2 = 250\\text{ N}.\\)" },
        { id: "ESA3", question: "Một ôtô nặng 1,5 tấn đang chạy with tốc độ 36 km/h. Tính động năng của ôtô này theo kJ.", answer: "75", explanation: "Vận tốc \\(v = 10\\text{ m/s}\\). \\(W_d = 0,5 \\cdot 1500 \\cdot 10^2 = 75000\\text{ J} = 75\\text{ kJ}.\\)" },
        { id: "ESA4", question: "Vật khối lượng 0,5 kg được ném thẳng lên with vận tốc 10 m/s từ đất. Bỏ qua ma sát (g=10). Ở độ cao bao nhiêu mét thì động năng bằng thế năng?", answer: "2,5", explanation: "Cơ năng \\(W = \\frac{1}{2}mv^2 = 25\\text{ J}\\). Khi \\(W_d = W_t\\) thì \\(W = 2W_t = 2Ph \\Rightarrow 25 = 2 \\cdot 0,5 \\cdot 10 \\cdot h \\Rightarrow h = 2,5\\text{ m}.\\)" }
    ];

    // --- GAME STATE ---
    let state = {
        mode: '', index: 0, questions: [], answers: [],
        flags: 6, totalCorrect: 0, 
        starUsed: false, isStarActive: false, 
        isReviewing: false, timer: null, finished: false, userInfo: {},
        isConfirming: false 
    };

    // --- HÀM TIỆN ÍCH ---
    function shuffleArray(arr) {
        for (let i = arr.length - 1; i > 0; i--) {
            const j = Math.floor(Math.random() * (i + 1));
            [arr[i], arr[j]] = [arr[j], arr[i]];
        }
        return arr;
    }

    // --- LOGIC ĐIỀU KHIỂN ---
    function triggerInstructions() {
        const sbd = document.getElementById('input-sbd').value.trim();
        const name = document.getElementById('input-name').value.trim();
        if(!sbd || !name) { alert("Vui lòng điền đủ thông tin!"); return; }
        
        document.getElementById('instruction-overlay').style.display = 'flex';
        let count = 10;
        const countEl = document.getElementById('instr-countdown');
        const itv = setInterval(() => {
            count--; countEl.innerText = count;
            if(count <= 0) { clearInterval(itv); document.getElementById('instruction-overlay').style.display = 'none'; startGame('practice'); }
        }, 1000);
    }

    function confirmExam() {
        const sbd = document.getElementById('input-sbd').value.trim();
        const name = document.getElementById('input-name').value.trim();
        if(!sbd || !name) { alert("Vui lòng điền đủ thông tin!"); return; }
        
        state.isConfirming = true;
        if(confirm("XÁC NHẬN BÀI KIỂM TRA?\n⚠️ Hệ thống sẽ tự động nộp bài và xử thua nếu bạn rời khỏi trình duyệt hoặc thoát toàn màn hình.")) {
            startGame('exam');
            setTimeout(() => { state.isConfirming = false; }, 1200); 
        } else {
            state.isConfirming = false;
        }
    }

    function startGame(mode) {
        state.userInfo = { 
            sbd: document.getElementById('input-sbd').value, 
            name: document.getElementById('input-name').value, 
            class: document.getElementById('input-class').value, 
            school: document.getElementById('input-school').value 
        };
        state.mode = mode; state.finished = false; state.index = 0; state.flags = 6;
        state.starUsed = false; state.isStarActive = false;

        let poolMCQ = mode === 'practice' ? [...rawMCQ] : [...examMCQ, ...rawMCQ].slice(0, 12);
        let poolTF = mode === 'practice' ? [...rawTF] : [...examTF, ...rawTF].slice(0, 4);
        let poolShort = mode === 'practice' ? [...rawShort] : [...examShort, ...rawShort].slice(0, 4);

        const mcqs = shuffleArray([...poolMCQ]).slice(0, 12).map(q => {
            if(q.options) q.options = shuffleArray([...q.options]); 
            return q;
        });
        const tfs = shuffleArray([...poolTF]).slice(0, 4);
        const shorts = shuffleArray([...poolShort]).slice(0, 4);

        state.questions = [...mcqs, ...tfs, ...shorts];
        state.answers = new Array(20).fill(null);

        document.getElementById('screen-login').classList.remove('active');
        document.getElementById('screen-game').classList.add('active');
        
        document.getElementById('user-display').innerHTML = `<b>${state.userInfo.name.toUpperCase()}</b> | ${mode === 'practice' ? 'LUYỆN TẬP' : 'KIỂM TRA'}`;
        
        if(mode === 'practice') {
            document.getElementById('flag-display').style.display = 'flex';
            document.getElementById('flag-count').innerText = "6";
            document.getElementById('btn-hint').style.display = 'inline-flex';
            document.getElementById('timer').innerText = "TỰ DO";
        } else {
            document.getElementById('flag-display').style.display = 'none';
            document.getElementById('btn-hint').style.display = 'none';
            startGlobalTimer();
            if (document.documentElement.requestFullscreen) {
                document.documentElement.requestFullscreen().catch(() => {});
            }
            setupStrictAntiCheat(); 
        }
        showQuestion(0);
    }

    function showQuestion(idx) {
        state.isReviewing = false;
        state.isStarActive = false;
        state.index = idx;
        const q = state.questions[idx];
        const box = document.getElementById('question-box');
        document.getElementById('review-box').style.display = 'none';
        
        let section = idx < 12 ? "PHẦN I. TRẮC NGHIỆM KHÁCH QUAN DẠNG ĐA LỰA CHỌN" : (idx < 16 ? "PHẦN II. TRẮC NGHIỆM KHÁCH QUAN DẠNG ĐÚNG / SAI" : "PHẦN III. TRẮC NGHIỆM KHÁCH QUAN DẠNG TRẢ LỜI NGẮN");
        let headerHtml = `<div class="question-header"><span>${section}</span><span>CÂU ${idx+1}</span></div>`;
        let contentHtml = `<div class="question-text">${q.question || q.context}</div>`;
        
        if(q.options) {
            contentHtml += `<div class="options-list">` + q.options.map((opt, i) => `
                <div class="option-item ${state.answers[idx] === opt ? 'selected' : ''}" onclick="selectMCQ(${i})">
                    <b>${String.fromCharCode(65+i)}.</b> ${opt}
                </div>`).join('') + `</div>`;
        } else if(q.statements) {
            const curr = state.answers[idx] || [null,null,null,null];
            contentHtml += q.statements.map((s, i) => `
                <div class="tf-row">
                    <div class="tf-statement">${s}</div>
                    <div class="tf-buttons">
                        <button class="btn-tf ${curr[i]===true?'active-true':''}" onclick="selectTF(${i},true)">ĐÚNG</button>
                        <button class="btn-tf ${curr[i]===false?'active-false':''}" onclick="selectTF(${i},false)">SAI</button>
                    </div>
                </div>`).join('');
        } else {
            contentHtml += `<input type="text" class="short-answer-input" id="short-inp" placeholder="Nhập kết quả số..." value="${state.answers[idx] || ''}" oninput="state.answers[${idx}]=this.value">`;
        }

        box.innerHTML = headerHtml + contentHtml;
        MathJax.typeset();
        
        const starBtn = document.getElementById('btn-star');
        if(idx >= 16 && !state.starUsed && state.mode === 'practice') {
            starBtn.style.display = 'inline-flex';
            starBtn.innerText = "⭐ Ngôi sao hy vọng";
            starBtn.className = "btn btn-star";
        } else { starBtn.style.display = 'none'; }

        document.getElementById('btn-next').style.display = idx === 19 ? 'none' : 'inline-flex';
        document.getElementById('btn-submit').style.display = idx === 19 ? 'inline-flex' : 'none';
    }

    function selectMCQ(optIdx) { 
        if(state.isReviewing) return; 
        state.answers[state.index] = state.questions[state.index].options[optIdx]; 
        showQuestion(state.index); 
    }

    function selectTF(i, v) { 
        if(state.isReviewing) return; 
        if(!state.answers[state.index]) state.answers[state.index] = [null,null,null,null]; 
        state.answers[state.index][i] = v; 
        showQuestion(state.index); 
    }

    function validateAndNext() {
        if(state.isReviewing) { changeQuestion(1); return; }
        const q = state.questions[state.index];
        const ans = state.answers[state.index];
        let correctAdd = 0;
        let isFullyCorrect = false;

        if(q.options) {
            isFullyCorrect = (ans === q.correctAnswer);
            correctAdd = isFullyCorrect ? 1 : 0;
        } else if(q.statements) {
            const u = ans || [null,null,null,null];
            let count = 0;
            for(let j=0; j<4; j++) if(u[j] === q.correctPattern[j]) count++;
            isFullyCorrect = (count === 4);
            correctAdd = isFullyCorrect ? 1 : 0; 
        } else {
            isFullyCorrect = (ans||"").toString().trim().replace('.',',') === q.answer.toString().replace('.',',');
            correctAdd = isFullyCorrect ? 1 : 0;
        }

        if(state.mode === 'practice') {
            if(correctAdd > 0) {
                let bonus = correctAdd;
                if(state.isStarActive && isFullyCorrect) bonus = 4;
                state.flags += bonus;
                document.getElementById('flag-count').innerText = Math.round(state.flags); 
                showToast(`Chính xác! Bạn nhận được ${bonus} lá cờ.`);
                changeQuestion(1);
            } else {
                startReview(q.explanation);
            }
        } else {
            changeQuestion(1);
        }
    }

    function startReview(exp) {
        state.isReviewing = true;
        document.getElementById('review-box').style.display = 'block';
        document.getElementById('review-content').innerHTML = exp;
        MathJax.typeset();
    }

    function changeQuestion(dir) {
        if(state.index + dir < 20) {
            showQuestion(state.index + dir);
            window.scrollTo({ top: 0, behavior: 'smooth' });
        }
    }

    // --- CHỐNG GIAN LẬN ---
    function setupStrictAntiCheat() {
        const handleViolation = () => {
            if(state.mode === 'exam' && !state.finished && !state.isConfirming) {
                finishGame(true);
            }
        };
        window.onblur = handleViolation;
        document.onvisibilitychange = () => { if(document.hidden) handleViolation(); };
        document.onfullscreenchange = () => { 
            if(!document.fullscreenElement && state.mode === 'exam' && !state.finished && !state.isConfirming) handleViolation();
        };
    }

    function showSubmitConfirm() { 
        state.isConfirming = true;
        if(confirm("Bạn có chắc chắn muốn nộp bài?")) finishGame(); 
        else state.isConfirming = false;
    }

    function finishGame(isCheat = false) {
        if (state.finished) return;
        state.finished = true; 
        clearInterval(state.timer);
        
        document.getElementById('screen-game').classList.remove('active');
        document.getElementById('screen-result').classList.add('active');

        let score = 0;
        state.questions.forEach((q, i) => {
            const u = state.answers[i];
            if(q.options) { if(u === q.correctAnswer) score += 0.25; }
            else if(q.correctPattern) {
                let c = 0; const user = u || [];
                for(let j=0; j<4; j++) if(user[j] === q.correctPattern[j]) c++;
                if(c===1) score += 0.0625; else if(c===2) score += 0.125; else if(c===3) score += 0.25; else if(c===4) score += 0.5;
            } else { if((u||"").toString().trim().replace('.',',') === q.answer.toString().replace('.',',')) score += 0.5; }
        });

        const finalScore = score.toFixed(1);
        document.getElementById('final-score').innerText = finalScore;
        const header = document.getElementById('result-header');
        const rank = document.getElementById('rank-label');

        if(isCheat) {
            header.innerText = "BÀI LÀM BỊ HỦY DO VI PHẠM";
            header.style.color = "var(--danger)";
            rank.innerText = "XỬ THUA: VI PHẠM QUY CHẾ";
            rank.style.backgroundColor = "var(--danger)";
            alert("PHÁT HIỆN VI PHẠM: Hệ thống đã tự động nộp bài và xử thua do hành động rời màn hình!");
        } else {
            header.innerText = `XIN CHÚC MỪNG ${state.userInfo.name.toUpperCase()}!`;
            let r = score >= 6 ? "XUẤT SẮC" : score >= 5 ? "GIỎI" : score >= 4 ? "KHÁ" : score >= 3 ? "ĐẠT" : "CHƯA ĐẠT";
            rank.innerText = r;
            rank.style.backgroundColor = score >= 4 ? "var(--success)" : (score >= 3 ? "var(--warning)" : "var(--danger)");
        }
        if(document.fullscreenElement) document.exitFullscreen().catch(()=>{});
        window.scrollTo({ top: 0, behavior: 'smooth' });
    }

    function toggleHistory() {
        const area = document.getElementById('history-area');
        area.style.display = 'block';
        const list = document.getElementById('history-list');
        list.innerHTML = "";

        state.questions.forEach((q, i) => {
            const studentAns = state.answers[i];
            let card = document.createElement('div');
            card.className = 'history-card';
            
            let html = `<div class="history-q-text">Câu ${i+1}. ${q.context || q.question}</div>`;

            if(q.options) {
                q.options.forEach((opt, idx) => {
                    let className = 'history-option';
                    if (opt === q.correctAnswer) className += ' correct';
                    if (studentAns === opt && opt !== q.correctAnswer) className += ' wrong';
                    let marker = (studentAns === opt) ? ' <b>(Bạn chọn)</b>' : '';
                    html += `<div class="${className}">${String.fromCharCode(65+idx)}. ${opt}${marker}</div>`;
                });
            } else if(q.statements) {
                const u = studentAns || [null,null,null,null];
                q.statements.forEach((s, idx) => {
                    const isCorrect = u[idx] === q.correctPattern[idx];
                    let icon = isCorrect ? '✅' : '❌';
                    let label = q.correctPattern[idx] ? 'ĐÚNG' : 'SAI';
                    html += `<div style="margin-bottom:0.5rem; font-size:0.95rem; padding: 8px; border-radius: 8px; ${isCorrect ? 'background:#f0fdf4' : 'background:#fef2f2'}">${icon} ${s} -> Đáp án chính xác: <b>${label}</b></div>`;
                });
            } else {
                const isCorrect = (studentAns||"").toString().trim().replace('.',',') === q.answer.toString().replace('.',',');
                html += `<div class="history-option ${isCorrect ? 'correct' : 'wrong'}">Câu trả lời của bạn: ${studentAns || '(Trống)'}</div>`;
                html += `<div style="margin-top:0.5rem; font-weight:bold; color:var(--success)">Đáp án đúng: ${q.answer}</div>`;
            }

            html += `<div class="history-explanation"><b>Giải thích chi tiết:</b> ${q.explanation}</div>`;
            card.innerHTML = html;
            list.appendChild(card);
        });

        MathJax.typeset();
        area.scrollIntoView({ behavior: 'smooth' });
    }

    function useHint() {
        if(state.flags >= 2) { 
            state.flags -= 2; document.getElementById('flag-count').innerText = Math.round(state.flags);
            alert("GỢI Ý TƯ DUY:\n" + (state.questions[state.index].hint || "Hãy xem lại kiến thức cơ bản của bài này."));
        } else { alert("Không đủ cờ để đổi gợi ý!"); }
    }

    function activateStar() {
        if(state.starUsed) return;
        state.isStarActive = true;
        state.starUsed = true;
        document.getElementById('btn-star').className = "btn btn-star used";
        document.getElementById('btn-star').innerText = "⭐ Đã kích hoạt";
        showToast("Đã kích hoạt Ngôi sao hy vọng!");
    }

    function startGlobalTimer() {
        let totalTime = 40 * 60; 
        state.timer = setInterval(() => {
            totalTime--; 
            if(totalTime <= 0) finishGame();
            const m = Math.floor(totalTime / 60); const s = totalTime % 60;
            document.getElementById('timer').innerText = `${m}:${s < 10 ? '0' : ''}${s}`;
        }, 1000);
    }

    function showToast(msg) {
        const t = document.getElementById('toast'); t.innerText = msg; t.style.display = 'block';
        setTimeout(() => t.style.display = 'none', 2500);
    }
</script>
</body>
</html>
