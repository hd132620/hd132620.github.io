# 이은찬 | AI 연구개발자 포트폴리오

AI 연구개발자 이은찬의 포트폴리오 웹사이트입니다.

## 🚀 배포

이 프로젝트는 GitHub Pages를 통해 자동으로 배포됩니다.

### 배포 방법

1. **GitHub 저장소 생성**
   - GitHub에서 새 저장소를 생성합니다
   - 저장소 이름: `username.github.io` (username은 GitHub 사용자명)

2. **코드 업로드**
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   git branch -M main
   git remote add origin https://github.com/username/username.github.io.git
   git push -u origin main
   ```

3. **GitHub Pages 설정**
   - 저장소 설정 → Pages
   - Source: "GitHub Actions" 선택
   - 자동으로 배포가 시작됩니다

4. **배포 확인**
   - `https://username.github.io`에서 사이트 확인

## 🛠️ 로컬 개발

```bash
# 의존성 설치
npm install

# 개발 서버 실행
npm start
```

## 📁 프로젝트 구조

```
azure_page/
├── public/          # 정적 파일
│   ├── index.html   # 메인 페이지
│   └── robots.txt   # 검색엔진 설정
├── server.js        # Express 서버 (로컬 개발용)
├── package.json     # 프로젝트 설정
└── .github/         # GitHub Actions 설정
    └── workflows/
        └── deploy.yml
```

## 🔧 기술 스택

- HTML5
- CSS3
- JavaScript
- Express.js (로컬 개발용)
- GitHub Pages (배포)

## 📝 라이선스

ISC License 