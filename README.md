# Todo • 간단한 할 일 앱

GitHub Pages에 쉽게 호스팅할 수 있는 가벽은 Todo 앱입니다.

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

## 🚀 GitHub Pages에 배포하는 방법

가장 간단한 방법은 아래 순서대로 진행하는 것입니다.

### 1. 저장소 확인

이 도구를 사용해서 다음 단계만 수행하면 됩니다.

### 2. GitHub Pages 활성화

1. 저장소 페이지(https://github.com/SWBaek/grok-todo) 에서 **Settings** 탭 클릭
2. 왼쪽 메뉴에서 **Pages** 선택
3. **Source** 섹션에서 다음 설정:
   - **Deploy from a branch**
   - Branch: `main`
   - Folder: `/ (root)`
4. **Save** 클릭

### 3. 확인하기

- 몇 초 ~ 1분 정도 기다리면 저장소 상단에 `https://SWBaek.github.io/grok-todo` 링크가 나타납니다.
- 해당 주소로 접속하면 Todo 앱이 실행됩니다.

## 로컬에서 테스트하기

```bash
# 간단히 브라우저에서 열기
# index.html 파일을 더블클릭

# 또는 로컬 서버로 실행 (권장)
npx serve .
# 또는
python -m http.server 8000
```

## 커스터마이징

- 색상 변경: `index.html` 상단의 Tailwind 스크립트나 `indigo-600` 클래스들을 원하는 색상으로 바끄세요.
- 제목 변경: `<h1>` 부분을 수정하세요.
- 초기 샘플 데이터: `loadTodos()` 함수 안에 있는 샘플 데이터를 수정/삭제하세요.

## 라이선스

MIT

---

**만든 사람을 위한 팁**: 이 앱은 완전히 정적 파일 하나(`index.html`)로 구성되어 있어 GitHub Pages, Netlify, Vercel 등 어디에나 쉽게 배포할 수 있습니다.