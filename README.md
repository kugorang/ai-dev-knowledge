# AI Dev Knowledge

> **English:** A Korean-language knowledge base of practical, hands-on tips, updates and workflows for building apps, web services and games with AI coding tools such as Claude Code, Codex, Cursor, ChatGPT and Grok Bot.

AI로 앱·웹·게임을 개발할 때(클라이언트·서버·아트·기획·QA) 도움이 되는 실전 지식 모음입니다.
Claude Code, OpenAI, Cursor 등 LLM 코딩 도구의 팁·업데이트·워크플로를 정리합니다.

## 누구를 위한 저장소인가
- Claude Code, Codex, Cursor 같은 AI 코딩 도구로 앱·웹·게임을 만드는 개발자(클라이언트·서버)
- AI로 이미지·3D·영상·이펙트를 만드는 아티스트, AI로 리서치와 기획을 하는 기획자, AI로 테스트를 돌리는 QA
- X(트위터) 게시물과 공식 공지를 다 따라가지 않고, 한국어 요약으로 바로 적용할 방법만 확인하고 싶은 사람

## 주제별 색인
도구와 주제별로 항목을 모은 색인은 [topics/](topics/README.md)에 있습니다. 한 항목이 여러 페이지에 나올 수 있고, 각 페이지는 최신순입니다. 괄호 안 숫자는 2026-11-14 기준 항목 수이며, 최신 수치는 [topics/README.md](topics/README.md)에서 확인합니다.

도구별
- [Claude Code](topics/claude-code.md) (101)
- [Codex](topics/codex.md) (46)
- [Cursor](topics/cursor.md) (36)
- [ChatGPT / OpenAI](topics/chatgpt.md) (15)
- [Grok Bot](topics/grok-bot.md) (22)

주제별
- [MCP (Model Context Protocol)](topics/mcp.md) (36)
- [에이전트·스킬 (Agents & Skills)](topics/agents-skills.md) (158)
- [게임·Unity (Game Dev & Unity)](topics/game-unity.md) (27)
- [아트·영상 (Art, 3D & Video)](topics/art.md) (32)

전체 항목은 220개입니다([entries/2026-10.md](entries/2026-10.md) 7개, [entries/2026-11.md](entries/2026-11.md) 185개, [entries/bookmarks.md](entries/bookmarks.md) 28개).

## 형식
- 항목은 월별 파일 `entries/YYYY-MM.md`에 추가된 순서(대체로 날짜순)로 기록합니다.
- 각 항목: 제목 / 도구 / 2~3문장 한국어 요약(직접 작성) / 출처 링크 / 날짜 / 작성자(@원문 작성자 핸들) / 원문 링크(게시물에 달린 GitHub·문서·블로그·체인지로그 등 외부 URL, 없으면 none) / 아카이브(web.archive.org 스냅샷 URL, 실패 시 none)
- 원문(X 게시물 등)은 그대로 옮기지 않고, 요약과 링크만 남깁니다.
- 요약만 읽어도 게시물이 사라져도 따라 할 수 있게 적습니다.

월별 파일의 항목 하나는 다음과 같이 생겼습니다. 제목은 `##` 헤딩이고, 나머지는 이 순서의 목록입니다. 작성자·원문 링크·아카이브는 최근 항목부터 붙어 있어 이전 항목에는 없을 수 있습니다.

```markdown
## 제목
- 도구: Claude Code, Codex
- 날짜: YYYY-MM-DD
- 요약: 2~3문장 한국어 요약
- 출처: https://x.com/...
- 작성자: @원문 작성자 핸들
- 원문 링크: 게시물에 달린 외부 URL 또는 none
- 아카이브: web.archive.org 스냅샷 URL 또는 none
```

## 분류별 모음
- [entries/bookmarks.md](entries/bookmarks.md): Claude Code / Codex / 에이전트 일반·스킬 / 앱·게임·아트. 버전 전용 항목은 Claude 5.5와 GPT-6·GPT-6.1(Astra 포함)만 두고, Opus 4.7·Opus 5·GPT-5처럼 이전 모델에만 해당하는 팁은 빼 두었습니다.
- 북마크 파일은 `## 분류` 아래에 `### 제목` 항목을 두며, 날짜는 게시 시각(KST, UTC+9)까지 적습니다.

## 자주 묻는 질문 (FAQ)

**이 저장소는 무엇인가요?**
AI 코딩 도구로 앱·웹·게임을 만들 때 바로 쓸 수 있는 팁을 한국어로 요약해 모은 지식 저장소입니다. 각 항목은 무엇을 하면 되는지를 2~3문장으로 적고, 출처 링크를 함께 둡니다.

**어떤 도구를 다루나요?**
Claude Code, Codex, Cursor, ChatGPT·OpenAI, Grok Bot을 중심으로 다룹니다. Gemini, Antigravity, Google AI Studio처럼 개발에 쓰이는 다른 AI 도구와 MCP·스킬 같은 공통 주제도 함께 다룹니다.

**얼마나 자주 업데이트되나요?**
보통 하루 두 번, 00:00과 12:00(KST) 무렵에 새 항목이 추가됩니다. 커밋 메시지는 `entries: YYYY-MM-DD HH:MM KST, N items` 형식입니다.

**원문 게시물이 삭제되면 어떻게 하나요?**
요약만 읽어도 따라 할 수 있게 적었으므로 원문이 없어도 내용을 쓸 수 있습니다. 최근 항목에는 가능한 경우 web.archive.org 아카이브 링크도 남겨 둡니다.

**특정 도구나 주제만 모아 보려면 어떻게 하나요?**
[topics/](topics/README.md)의 도구별·주제별 색인 페이지를 엽니다. 각 링크는 `entries/` 파일의 해당 항목 헤딩으로 바로 이동합니다.

**요약 내용은 얼마나 믿을 수 있나요?**
요약은 출처 게시물과 공식 문서를 근거로 직접 작성하지만, 적용하기 전에 출처와 원문 링크로 확인하는 것이 좋습니다. 보도나 제3자 주장, 작성자 측 수치는 제목이나 요약에 그렇다고 밝혀 둡니다.

## 업데이트
매일 새 항목이 추가됩니다. 보통 하루 두 번(00:00·12:00 KST 무렵) 월별 파일에 새 항목이 붙습니다.

## 색인 다시 만들기
`topics/`의 페이지는 [scripts/build-index.py](scripts/build-index.py)가 `entries/`를 읽어 생성하므로 직접 고치지 않습니다. Python 3 표준 라이브러리만 쓰며, 여러 번 실행해도 결과가 같습니다.

```sh
python3 scripts/build-index.py          # topics/ 갱신
python3 scripts/build-index.py --check  # 갱신이 필요하면 종료 코드 1
```

도구 분류는 각 항목의 `도구` 필드로, 주제 분류는 제목과 요약의 키워드로 정합니다. 분류 규칙은 스크립트의 `TOOLS`와 `THEMES`에 있습니다.
