# Defuddle — 페이지를 Markdown으로 변환

**출처:** https://defuddle.md/  
**작성자:** kepano (@stephango)

---

## 개요

어떤 웹페이지든 핵심 콘텐츠를 Markdown으로 변환해주는 도구.

## 사용법

### API
```bash
curl defuddle.md/stephango.com
```
URL 뒤에 아무 경로나 붙이면 해당 페이지를 Markdown + YAML frontmatter로 반환.

### 브라우저 익스텐션
- Obsidian Web Clipper용으로 제작
- 로컬에서 실행 → private 페이지, JS 렌더 페이지도 처리 가능

### 북마클릿
북마크바에 드래그 → 아무 페이지에서 클릭하면 Markdown으로 변환

## 링크

- GitHub: https://github.com/kepano/defuddle
- NPM: https://www.npmjs.com/package/defuddle
- Docs: https://defuddle.md/docs
- Playground: https://defuddle.md/playground

---

## 💡 활용 메모

- refolongs에 새 레퍼런스 추가할 때 콘텐츠 긁어오기 용도로 활용 가능
- Obsidian 연동 → 노트 관리와 연결
- API 방식이라 자동화 파이프라인에 붙이기 쉬움
