# 현대엘리베이터 AX 교육 자료

GitHub Pages로 그대로 게시할 수 있는 정적 사이트입니다. 빌드 과정은 없습니다.

```
index.html                 첫 화면 (두 과정 안내)
course1/index.html         과정 1 · Gemini Enterprise 실전 활용 (일반 임직원)
course1/img/               화면 캡처
course1/downloads/         실습 데이터팩, 실전 노하우 KIT (PDF·DOCX·XLSX)
course2/index.html         과정 2 · GCP 엔지니어 실무 (AI·데이터 개발자)
course2/img/
course2/downloads/         실습 저장소 he2-labs v2, 실습 데이터팩
.nojekyll                  Jekyll 처리 끄기
```

## 게시 방법
1. 이 폴더 전체를 저장소 루트에 올립니다.
2. Settings → Pages → Build and deployment → Source: Deploy from a branch, Branch: main / (root) → Save
3. 몇 분 뒤 `https://<계정>.github.io/<저장소>/` 에서 열립니다.

교재의 내려받기 버튼은 `downloads/` 폴더의 파일로 연결됩니다. 파일을 바꿀 때는 같은 이름으로 덮어쓰면 됩니다.
저장소를 비공개로 두면 GitHub Pages 공개 범위는 요금제 설정을 따릅니다. 고객 공유 범위를 먼저 확인하세요.
모든 실습 데이터는 교육용 가상 데이터입니다.
