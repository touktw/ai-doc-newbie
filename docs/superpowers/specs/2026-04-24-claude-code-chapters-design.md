# Claude Code 챕터 추가 설계 (06~08)

## 개요

기존 5단계 가이드를 마친 완전 입문자를 대상으로, Claude Code를 Cursor와 함께 활용하는 방법을 안내하는 챕터 3개를 추가한다.

## 독자

- 앞의 01~05 단계를 완료한 입문자
- 개발 지식 없음, Claude Code가 무엇인지 모름
- 맥북 + Node.js 설치 완료 상태 (02단계에서 처리)

## 인증 방식

- API 키 없음
- claude.ai 웹 가입 후 `claude login` (브라우저 OAuth)

## 이미지 정책

- 이미지 없음
- UI 위치는 텍스트로 명확하게 설명

---

## 파일 구조

```
06.Claude-Code-시작하기.md
07.터미널로-Claude-Code-사용하기.md
08.Cursor에서-Claude-Code-사용하기.md
```

README 목차에 3개 항목 추가.

---

## 06. Claude Code 시작하기

**목적:** Claude Code가 뭔지 이해하고, 설치 및 로그인까지 완료

### 섹션 구성

1. **Claude Code란?** — 기술 용어 없이 한 문단으로 설명 ("터미널에서 AI와 대화하며 코드를 수정하는 도구")
2. **claude.ai 가입** — 웹 가입 단계별 안내 (텍스트만)
3. **Node.js 확인** — `node --version` 실행 (02단계 완료자는 이미 됨)
4. **Claude Code 설치** — `npm install -g @anthropic-ai/claude-code`
5. **로그인** — `claude login` → 브라우저 인증 흐름 설명
6. **설치 확인** — `claude --version` 출력 확인

---

## 07. 터미널로 Claude Code 사용하기

**목적:** 터미널에서 Claude Code를 실행하고, 할 일 앱에 새 기능을 추가하는 실습 완료

### 섹션 구성

1. **터미널에서 프로젝트 폴더 열기** — `cd ~/Desktop/my-todo-app` (cd 명령어 간단 설명 포함)
2. **Claude Code 실행** — `claude` 입력 후 대화창 시작
3. **실습: 완료된 항목 수 표시 기능 추가** — AI에게 요청하는 예시 프롬프트 포함
4. **결과 확인** — 브라우저에서 Live Server로 확인
5. **종료** — `exit` 또는 `Ctrl+C`
6. **FAQ** — 흔한 오류 2~3개

---

## 08. Cursor에서 Claude Code 사용하기

**목적:** Cursor 안에서 Claude Code 확장을 설치하고, 플러그인으로 할 일 앱에 새 기능을 추가하는 실습 완료

### 섹션 구성

1. **Claude Code 확장 설치** — Cursor 확장 탭에서 "Claude Code" 검색 → 설치 (텍스트로 위치 안내)
2. **Claude Code 패널 열기** — 실행 방법 안내
3. **실습: 전체 삭제 버튼 추가** — AI에게 요청하는 예시 프롬프트 포함
4. **결과 확인** — 브라우저에서 확인
5. **Cursor AI vs Claude Code 차이** — 한 줄 비교 ("Cursor AI는 에디터 내 빠른 수정, Claude Code는 대화형 작업에 강함")
6. **FAQ**

---

## 톤 & 스타일

- 기존 챕터와 동일: 친근한 한국어, 기술 용어 최소화
- 명령어는 코드 블록으로
- 각 챕터 하단에 이전/다음 챕터 링크

## README 업데이트

목차에 추가:
```
6. [Claude Code 시작하기](06.Claude-Code-시작하기.md)
7. [터미널로 Claude Code 사용하기](07.터미널로-Claude-Code-사용하기.md)
8. [Cursor에서 Claude Code 사용하기](08.Cursor에서-Claude-Code-사용하기.md)
```
