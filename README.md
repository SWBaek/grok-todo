# Todo • 간단한 할 일 앱

GitHub Pages에 쉽게 호스팅할 수 있는 가벼운 Todo 앱입니다.

## ✨ 주요 기능

- 할 일 추가 (Enter 키 지원)
- 완료 체크 / 토글
- 인라인 편집 (텍스트 클릭)
- 삭제
- 전체 / 미완료 / 완료 필터
- 남은 할 일 개수 표시
- 완료된 항목 일괄 삭제
- **드래그 앤 드롭으로 순서 변경**
- localStorage로 브라우저에 자동 저장
- 반응형 + 깔끔한 UI (Tailwind CSS)

## 🚀 지금 바로 사용하기

**라이브 데모**: https://SWBaek.github.io/grok-todo  (Pages 활성화 후)

## GitHub Pages 활성화 방법 (마지막 단계)

1. https://github.com/SWBaek/grok-todo 접속
2. 상단 **Settings** 탭 클릭
3. 왼쪽 사이드바에서 **Pages** 선택
4. 다음 설정으로 변경 후 Save:
   - Source: **Deploy from a branch**
   - Branch: `main`
   - Folder: `/ (root)`
5. 저장 후 30초~1분 기다리면 `https://SWBaek.github.io/grok-todo` 에서 앱을 볼 수 있습니다.

## 로컬에서 테스트하기

```bash
# 브라우저에서 직접 열기
index.html 파일 더블클릭

# 추천: 로컬 서버
npx serve .
# 또는
python -m http.server 8000
```

## 커스터마이징

- 색상: `indigo-600` 등을 원하는 Tailwind 색상으로 교체
- 제목: HTML의 `<h1>` 수정
- 초기 데이터: `loadTodos()` 함수의 샘플 todos 배열 수정

## 라이선스

MIT

---

완전한 정적 사이트(`index.html` 하나)라서 Netlify, Vercel 등에도 바로 배포 가능합니다.