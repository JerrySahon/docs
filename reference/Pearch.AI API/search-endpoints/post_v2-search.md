---
title: Submit a search query with enhanced parameters (POST)
excerpt: >-
  Enhanced search endpoint with additional parameters for more granular control
  over search behavior.Submit a new search query using POST with JSON body. Uses
  LangGraph for processing with configurable options.This endpoint always
  returns results immediately (synchronous).
api:
  file: psearch-agent API Docs.yaml
  operationId: post_v2-search
hidden: false
icon: 🟢
next:
  pages:
    - title: BOOK A DEMO
      type: link
      url: https://calendly.com/all_pearch/hrachik-and-jerry-15min
---
<Anchor label="**Book a demo**" target="_blank" href="https://calendly.com/all_pearch/hrachik-and-jerry-15min">**Book a demo**</Anchor>` if you don't have a clue what's going on here`

<Cards columns={1}>
  <Card title="Book a demo" href="https://calendly.com/all_pearch/hrachik-and-jerry-15min" icon="fa-democrat" target="_blank">
    if you don't have a clue what's going on here
  </Card>
</Cards>

<br />

\<div id="tinted-cards">
&#x20; \<Cards columns=\{1}>
&#x20;   \<Card
&#x20;     title="Book a demo"
&#x20;     href="https\://calendly.com/all\_pearch/hrachik-and-jerry-15min"
&#x20;     icon="fa-democrat"
&#x20;     target="\_blank"
&#x20;     rel="noopener noreferrer"
&#x20;   \>
&#x20;     if you don't have a clue what's going on here
&#x20;   \</Card>
&#x20; \</Cards>
\</div>

\<style>
/\* красим внешний контейнер карточки (в ReadMe это \<a> или \<div>) \*/
\#tinted-cards :where(a, div)\[class\*="Card" i],
\#tinted-cards :where(a, div)\[class\*="card" i]\{
&#x20; background: #F5F8FF !important;
&#x20; border: 1px solid #E4ECFF !important;
&#x20; border-radius: 12px !important;
&#x20; box-shadow: 0 2px 8px rgba(0,0,0,.04) !important;
}

/\* на всякий: убираем белый фон внутренних обёрток \*/
\#tinted-cards \[class\*="CardBody" i],
\#tinted-cards \[class\*="card\_\_body" i]\{
&#x20; background: transparent !important;
}

/\* ховер \*/
\#tinted-cards :where(a, div)\[class\*="Card" i]:hover\{
&#x20; background: #EAF2FF !important;
&#x20; border-color: #D6E4FF !important;
}
\</style>