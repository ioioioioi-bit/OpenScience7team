# Markdown(.md) 작성 규칙 정리

## Markdown이란?
**Markdown**은 간단한 문법으로 문서의 구조(제목, 목록, 강조 등)를 표현할 수 있는  
**경량 마크업 언어**입니다.  
→ `.md` 확장자를 사용하며, GitHub에서는 자동으로 HTML 형태로 렌더링됩니다.  

---

## 기본 문법 요약

| 구분 | 문법 | 예시 | 출력 결과 |
|------|------|------|-----------|
| **제목(Heading)** | `#`, `##`, `###` | `# 제목1`<br>`## 제목2` | 큰 제목, 중간 제목 |
| **굵게(Bold)** | `**텍스트**` | `**중요**` | **중요** |
| **기울임(Italic)** | `*텍스트*` | `*강조*` | *강조* |
| **취소선(Strikethrough)** | `~~텍스트~~` | `~~삭제~~` | ~~삭제~~ |
| **리스트(List)** | `-` 또는 `*` | `- 항목1`<br>`- 항목2` | • 항목1<br>• 항목2 |
| **번호 리스트(Numbered)** | `1.`, `2.` | `1. 첫째`<br>`2. 둘째` | 1. 첫째<br>2. 둘째 |
| **링크(Link)** | `[이름](URL)` | `[GitHub](https://github.com)` | [GitHub](https://github.com) |
| **이미지(Image)** | `![설명](이미지경로)` | `![로고](logo.png)` | 이미지 표시 |
| **인용문(Blockquote)** | `>` | `> 인용문` | > 인용문 |
| **코드(Code)** | `` `코드` `` 또는 ``` 코드블록 ``` | `` `print("Hi")` `` | `print("Hi")` |
| **표(Table)** | `|`로 구분 | `| 항목 | 설명 |` | 표 형태 출력 |


[GitHub 공식 가이드](https://guides.github.com/features/mastering-markdown/)

예시)
# Open Science DB조사 및 실습 (7조)

---
## 발표 장표 다운로드
<a href="Openscience_7team_2025117.pptx" download>발표자료 1차</a>

---
## 1. github
**(1) 나만의 저장소 만들기**  
→ https://github.com 접속 -> log in -> New ropository

<a href="md user guide.md">README.md 작성 방법으로 가기</a>

**(2) 협업하기**  
→ Ropositoryies -> Settings -> Collaborators -> Add people 

**(3) 나만의 키워드로 자료 검색하기**  
예시) “machine learning”이 포함된 Python 코드 중 stars가 1000개 이상인 저장소 찾기

-> machine learning language:python stars:>1000

<img width="250" height="100" alt="image" src="github_image.png" />
