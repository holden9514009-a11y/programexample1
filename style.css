/* @import url을 통해 깔끔하고 트렌디한 Pretendard 폰트를 적용합니다 */
@import url("https://cdn.jsdelivr.net/gh/orioncactus/pretendard@v1.3.9/dist/web/static/pretendard.css");

:root {
    --bg-color: #f0f4f8;          /* 부드러운 배경 연청색 */
    --card-bg: #ffffff;           /* 카드 배경 내부 화이트 */
    --text-main: #2d3748;         /* 메인 글자색 (짙은 회색으로 눈을 편안하게) */
    --text-muted: #718096;        /* 부연 설명 글자색 */
    
    /* 포인트 컬러 (소프트 & 파스텔) */
    --primary: #6c5ce7;           /* 부드러운 보라색 (메인 버튼 및 강조) */
    --primary-hover: #5b4bc4;     
    --seat-select: #a29bfe;       /* 좌석 선택 시 (연보라) */
    --success: #00b894;           /* 배정 완료 (싱그러운 민트/그린) */
    --danger: #ff7675;            /* 초기화 버튼 (부드러운 레드) */
    
    --border-radius: 16px;        /* 둥글둥글한 느낌을 주는 라운드 값 */
    --shadow: 0 10px 20px rgba(162, 155, 254, 0.08), 0 3px 6px rgba(0, 0, 0, 0.04);
}

body {
    font-family: 'Pretendard', -apple-system, BlinkMacSystemFont, system-ui, Roboto, sans-serif;
    background-color: var(--bg-color);
    color: var(--text-main);
    margin: 0;
    padding: 30px 20px;
    display: flex;
    flex-direction: column;
    align-items: center;
    min-height: 100vh;
    box-sizing: border-box;
}

h1 {
    font-size: 2rem;
    font-weight: 800;
    color: #4a439f; /* 타이틀에 따뜻한 보라색 가미 */
    margin-bottom: 8px;
    letter-spacing: -0.5px;
}

p {
    color: var(--text-muted);
    font-size: 1rem;
    margin-top: 0;
    margin-bottom: 35px;
    text-align: center;
}

.container {
    display: flex;
    gap: 30px;
    max-width: 1100px;
    width: 100%;
    justify-content: center;
    align-items: flex-start;
}

/* 카드 서식 (입력창 서식과 배치도 감싸는 상자) */
.card {
    background: var(--card-bg);
    padding: 30px;
    border-radius: var(--border-radius);
    box-shadow: var(--shadow);
    flex: 1;
    min-width: 340px;
    border: 1px solid rgba(255, 255, 255, 0.8);
}

/* 교탁/칠판 디자인 */
.teacher-desk {
    width: 60%;
    height: 45px;
    background: linear-gradient(135deg, #74b9ff, #0984e3);
    color: white;
    display: flex;
    align-items: center;
    justify-content: center;
    font-weight: 700;
    font-size: 15px;
    border-radius: 30px; /* 알약 모양으로 부드럽게 */
    margin: 0 auto 30px auto;
    box-shadow: 0 4px 10px rgba(9, 132, 227, 0.2);
    letter-spacing: 2px;
}

/* 5열 6행 그리드 */
.classroom-grid {
    display: grid;
    grid-template-columns: repeat(5, 1fr);
    gap: 12px;
    margin-bottom: 25px;
}

/* 기본 좌석 스타일 */
.seat {
    aspect-ratio: 1.1;
    border: 2px dashed #dfe6e9; /* 기본 상태는 점선으로 부드럽게 */
    border-radius: 12px;
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
    background-color: #fff;
    cursor: pointer;
    transition: all 0.25s cubic-bezier(0.4, 0, 0.2, 1);
}

.seat:hover {
    transform: translateY(-2px);
    border-color: var(--seat-select);
    background-color: #f7f6ff;
}

/* 학생이 지망을 선택했을 때 (그라데이션 효과) */
.seat.selected {
    border-style: solid;
    border-color: var(--primary);
    background: linear-gradient(135deg, #efecff, #e0daff);
    color: var(--primary);
    box-shadow: 0 4px 12px rgba(108, 92, 231, 0.15);
}

.seat-num {
    font-size: 11px;
    color: #b2bec3;
    margin-bottom: 4px;
    font-weight: 500;
}

.student-name {
    font-size: 15px;
    font-weight: 700;
}

/* 입력 폼 서식 */
.form-group {
    margin-bottom: 20px;
}

label {
    display: block;
    margin-bottom: 8px;
    font-weight: 700;
    color: #4a5568;
    font-size: 14px;
}

input[type="text"] {
    width: 100%;
    padding: 14px;
    border: 2px solid #e2e8f0;
    border-radius: 12px;
    box-sizing: border-box;
    font-size: 15px;
    font-family: inherit;
    transition: all 0.2s;
    background-color: #f8fafc;
}

input[type="text"]:focus {
    outline: none;
    border-color: var(--seat-select);
    background-color: #fff;
    box-shadow: 0 0 0 3px rgba(162, 155, 254, 0.2);
}

#selectedSequence {
    font-size: 13px;
    color: var(--primary);
    background: #f1f0ff;
    padding: 10px 12px;
    border-radius: 8px;
    margin-top: 5px;
    line-height: 1.4;
}

/* 버튼 공통 스타일 */
button {
    width: 100%;
    padding: 14px;
    background: var(--primary);
    color: white;
    border: none;
    border-radius: 12px;
    font-size: 16px;
    font-weight: 700;
    cursor: pointer;
    transition: all 0.2s ease;
    box-shadow: 0 4px 12px rgba(108, 92, 231, 0.2);
}

button:hover {
    background: var(--primary-hover);
    transform: translateY(-1px);
    box-shadow: 0 6px 15px rgba(108, 92, 231, 0.3);
}

button:active {
    transform: translateY(1px);
}

/* 초기화 버튼 */
button.reset-btn {
    background: #ffeaa7;
    color: #d63031;
    box-shadow: none;
    margin-top: 15px;
    font-size: 14px;
    padding: 10px;
}
button.reset-btn:hover {
    background: var(--danger);
    color: white;
    box-shadow: 0 4px 12px rgba(255, 118, 117, 0.2);
}

/* 등록된 학생 명단 상자 */
h3 {
    font-size: 16px;
    color: #4a5568;
    margin-top: 25px;
    margin-bottom: 10px;
}

.student-list {
    background-color: #f8fafc;
    border: 1px solid #e2e8f0;
    border-radius: 12px;
    padding: 12px;
    max-height: 180px;
    overflow-y: auto;
}

.student-item {
    padding: 8px 6px;
    border-bottom: 1px solid #edf2f7;
    font-size: 13px;
    color: var(--text-muted);
}
.student-item:last-child {
    border-bottom: none;
}

/* 🎉 최종 배정 완료된 좌석 스타일 (따뜻하고 싱그러운 민트) */
.assigned {
    border-style: solid !important;
    background: linear-gradient(135deg, #e6f9f5, #cdf2eb) !important;
    border-color: var(--success) !important;
    color: #00624e !important;
    box-shadow: 0 4px 10px rgba(0, 184, 148, 0.15);
    animation: popIn 0.4s cubic-bezier(0.175, 0.885, 0.32, 1.275);
}

/* 배정 완료 시 뿅! 하고 나타나는 부드러운 애니메이션 */
@keyframes popIn {
    0% { transform: scale(0.9); opacity: 0.8; }
    100% { transform: scale(1); opacity: 1; }
}

/* 반응형 모바일 대응 */
@media (max-width: 768px) {
    .container {
        flex-direction: column;
    }
    .card {
        width: 100%;
        box-sizing: border-box;
    }
}
