# 성남청운교회 웹사이트

## 로컬 개발

### Python HTTP 서버 사용 (권장)
```bash
python3 -m http.server 8000
```

그 다음 브라우저에서 `http://localhost:8000` 접속

### npm 사용
```bash
npm run dev
```

## Vercel 배포

### 방법 1: Vercel CLI 사용

1. Vercel CLI 설치 (처음 한 번만):
```bash
npm install -g vercel
```

2. 프로젝트 디렉토리에서 배포:
```bash
vercel
```

3. 프로덕션 배포:
```bash
vercel --prod
```

### 방법 2: GitHub 연동 (권장)

1. GitHub에 저장소 생성 및 푸시
2. [Vercel](https://vercel.com) 접속 후 로그인
3. "New Project" 클릭
4. GitHub 저장소 선택
5. 설정 확인 후 "Deploy" 클릭

Vercel이 자동으로 `vercel.json` 설정을 인식하고 배포합니다.

### 방법 3: 드래그 앤 드롭

1. [Vercel](https://vercel.com) 접속 후 로그인
2. 프로젝트 폴더를 드래그하여 업로드
3. 자동으로 배포됩니다

## 기술 스택

- 순수 HTML5
- CSS3 (반응형 디자인)
- Vanilla JavaScript
- Lottie 애니메이션
- 마우스 인터랙티브 Light Ray 효과

## 특징

- ✨ 마우스를 따라가는 동적 light ray 효과
- 📱 모바일 최적화 반응형 디자인
- 🎨 Lottie 애니메이션 통합
- ⚡ 빠른 로딩 속도
- 🎯 깔끔한 UI/UX

