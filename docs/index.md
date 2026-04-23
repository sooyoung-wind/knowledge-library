---
hide:
  - toc
---

<section class="hero-panel">
  <p class="eyebrow">Knowledge Library</p>
  <h1>차분하고 고급스러운<br>개인 지식 아카이브</h1>
  <p class="lead">
    흩어진 자료를 한곳에 모아, 오래 참고할 문서만 정리해 두는 라이브러리입니다.
    빠르게 훑어보는 메모가 아니라 다시 꺼내 읽을 가치가 있는 가이드와 레퍼런스를 축적합니다.
  </p>
  <div class="hero-actions">
    <a class="button-primary" href="html/gstack-guide.html">첫 문서 읽기</a>
    <a class="button-secondary" href="#collections">컬렉션 보기</a>
  </div>
  <div class="hero-metrics">
    <div>
      <strong>Curated</strong>
      <span>정리된 문서만 보관</span>
    </div>
    <div>
      <strong>Readable</strong>
      <span>웹에서 읽기 좋은 구조</span>
    </div>
    <div>
      <strong>Evergreen</strong>
      <span>계속 확장 가능한 도서관</span>
    </div>
  </div>
</section>

## Welcome

이 사이트는 MkDocs와 GitHub Pages로 운영하는 정적 지식 도서관입니다.  
앞으로 HTML 가이드, Markdown 메모, 프로젝트 리서치, 툴 사용법을 분야별로 차곡차곡 쌓아갈 수 있게 설계했습니다.

<div id="collections" class="card-grid">
  <a class="archive-card archive-card-feature" href="html/gstack-guide.html">
    <span class="archive-kicker">Featured Guide</span>
    <h3>gstack 설명서 및 시작 가이드</h3>
    <p>Garry Tan의 gstack 저장소를 바탕으로 설치, 워크플로, 주요 명령군을 정리한 HTML 가이드입니다.</p>
    <span class="archive-link">문서 열기</span>
  </a>

  <div class="archive-card">
    <span class="archive-kicker">AI Tools</span>
    <h3>AI 도구 컬렉션</h3>
    <p>프롬프트 도구, 에이전트 워크플로, 자동화 툴 사용법을 모아둘 섹션입니다.</p>
  </div>

  <div class="archive-card">
    <span class="archive-kicker">Development</span>
    <h3>개발 노트 아카이브</h3>
    <p>설계 메모, 배포 절차, 디버깅 기록, 프레임워크 가이드를 정리할 공간입니다.</p>
  </div>

  <div class="archive-card">
    <span class="archive-kicker">Research</span>
    <h3>리서치와 비교 문서</h3>
    <p>서비스 비교, 제품 분석, 시장 조사, 실험 결과 요약을 저장하기 좋습니다.</p>
  </div>
</div>

## Library Principles

<div class="principles">
  <div class="principle">
    <h3>정리된 입구</h3>
    <p>문서가 많아져도 첫 화면에서 중요한 흐름과 대표 컬렉션을 바로 찾을 수 있어야 합니다.</p>
  </div>
  <div class="principle">
    <h3>긴 수명의 문서</h3>
    <p>짧은 메모보다 다시 읽을 가치가 있는 설명서와 참고 문서를 우선으로 쌓습니다.</p>
  </div>
  <div class="principle">
    <h3>단순한 운영</h3>
    <p>문서를 추가하고 GitHub에 push 하는 것만으로 라이브러리가 계속 자라도록 구성합니다.</p>
  </div>
</div>

## How To Grow This Library

1. 새 Markdown 문서는 `docs/` 아래 적절한 폴더에 추가합니다.
2. 기존에 만든 단일 HTML 페이지는 `docs/html/` 아래에 넣습니다.
3. `mkdocs.yml`의 `nav`에 링크를 추가합니다.
4. GitHub에 push 하면 GitHub Pages가 자동으로 업데이트됩니다.

## Suggested Structure

```text
docs/
  index.md
  html/
    gstack-guide.html
  ai-tools/
  development/
  research/
  business/
```
