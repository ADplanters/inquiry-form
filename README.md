# 📩 Customer Inquiry Form (고객 문의 및 DB 수집 페이지)

잠재 고객의 문의를 접수하고, 고객 정보(Lead DB)를 수집하기 위한 웹 프로젝트입니다.

## ✨ 주요 기능
- **고객 문의 폼(Inquiry Form)**: 이름, 연락처(이메일/전화번호), 회사명, 문의 내용 입력 및 유효성 검사
- **고객 DB 저장**: 접수된 문의 데이터를 데이터베이스에 안전하게 기록
- **접수 완료 안내**: 폼 제출 후 사용자에게 접수 완료 메시지/알림 제공

## 🛠 사용 기술 (Tech Stack)
- **Frontend**: `[예: HTML/CSS/JavaScript, React, Next.js 등]`
- **Backend / DB**: `[예: Node.js, Supabase, Firebase, Google Sheets 연동 등]`
- **Deployment**: `[예: Vercel, Netlify, GitHub Pages 등]`

## 🚀 실행 방법 (Getting Started)

1. 저장소 복제 (Clone)
```bash
git clone [원격 저장소 URL]
```

2. 프로젝트 폴더로 이동
```bash
cd [프로젝트 폴더명]
```

3. 패키지 설치 및 실행 *(정적 HTML/CSS 프로젝트라면 이 단계는 생략하세요)*
```bash
npm install
npm run dev
```

## 📂 폴더 구조
```text
├── index.html        # 메인 문의 폼 페이지
├── style.css         # 스타일시트
├── script.js         # 폼 유효성 검사 및 데이터 전송 로직
└── README.md         # 프로젝트 설명서
```

## 📝 참고 및 추후 개선 사항
- [ ] 스팸 방지(reCAPTCHA 등) 적용
- [ ] 문의 접수 시 관리자 이메일/슬랙 알림 연동
