# PicCrop AI ✂️

이미지를 업로드하여 손쉽게 확대, 축소, 자르기를 수행하고 Google Gemini API를 이용해 이미지를 분석받을 수 있는 웹 애플리케이션입니다.

## 주요 기능
- 이미지 파일 업로드
- 영역 선택 및 이미지 자르기 (Crop)
- 이미지 확대 / 축소 / 회전 / 초기화
- 편집된 이미지 PNG 다운로드
- Gemini API 연동 이미지 AI 분석 (`api/generate.js`)

## Vercel 배포 방법

1. 이 저장소를 GitHub에 업로드합니다.
2. [Vercel](https://vercel.com) 로그인 후 **Add New Project**를 선택합니다.
3. GitHub 저장소를 가져옵니다 (Import).
4. **Environment Variables** 설정 항목에 다음 환경 변수를 추가합니다:
   - **Key**: `GEMINI_API_KEY`
   - **Value**: 발급받은 Google Gemini API Key
5. **Deploy** 버튼을 누르면 배포가 완료됩니다.