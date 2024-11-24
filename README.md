# OWASP 웹 보안 테스트 지침서 (한국어 번역판 - 번역 중)

[![기여 환영](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/sh9351/wstg-translation-kr/issues)
[![OWASP 프로젝트](https://img.shields.io/badge/owasp-flagship-brightgreen.svg)](https://owasp.org/projects/)
[![X 팔로우](https://img.shields.io/twitter/follow/owasp_wstg?style=social)](https://x.com/owasp_wstg)

[![크리에이티브 커먼즈 라이선스](https://licensebuttons.net/l/by-sa/4.0/88x31.png)](https://creativecommons.org/licenses/by-sa/4.0/deed.ko "CC BY-SA 4.0")

오픈 웹 애플리케이션 보안 프로젝트® (OWASP®) 웹 보안 테스트 지침서 (WSTG)의 공식 저장소에 오신 것을 환영합니다. WSTG는 웹 애플리케이션 및 웹 서비스의 보안을 테스트하기 위한 포괄적인 지침서입니다. 보안 전문가와 헌신적인 기여자들의 노력으로 만들어진 WSTG는 전 세계의 모의침투 테스터 및 조직에서 사용하는 모범 사례 체계를 제공합니다.

현재 릴리스 버전 5.0을 작성하고 있습니다. 최신 문서를 [GitHub](https://github.com/sh9351/wstg-translation-kr/tree/master/document)에서 읽을 수 있습니다.

가장 최신의 안정된 릴리스를 원하신다면, [릴리스 버전 4.2(영문)](https://github.com/OWASP/wstg/releases/tag/v4.2)를 확인하세요. [온라인](https://owasp.org/www-project-web-security-testing-guide/v42/)으로도 확인하실 수 있습니다.

- [WSTG 시나리오 인용하기](#wstg-시나리오-인용하기)
 - [링크](#링크)
- [기여, 기능 요청 및 피드백](#기여-기능-요청-및-피드백)
- [소통](#소통)
- [프로젝트 리더](#프로젝트-리더)
- [핵심 팀](#핵심-팀)
- [번역](#번역)

## WSTG 시나리오 인용하기

각각의 시나리오는 `WSTG-<카테고리>-<번호>`의 형식을 갖고 있습니다. 여기서 '카테고리'는 테스트 또는 취약점의 종류를 나타내는 영어 대문자 4자이고, '번호'는 01부터 99까지의 두 자리 숫자입니다. 예를 들자면, `WSTG-INFO-02`는 두 번째 정보 수집 테스트입니다.

식별자는 버전에 따라 달라질 수 있기에, 다른 문서, 보고서, 또는 도구는 `WSTG-<버전>-<카테고리>-<번호>`의 형식을 사용하는 것이 바람직합니다. 여기서 '버전'은 온점을 제거한 버전 태그입니다. 예를 들자면, `WSTG-v42-INFO-02`는 버전 4.2의 두 번째 정보 수집 테스트입니다.

식별자가 `<버전>`을 나타내지 않는다면, 웹 보안 테스트 지침서의 최신 버전을 가리키는 것으로 보아야 합니다. 이는 지침서가 수정되면서 문제가 되기에, 작성자 또는 개발자는 버전을 표시해야 합니다.

### 링크

웹 보안 테스트 지침서의 링크는 시간이 지나며 변화할 `stable` 또는 `latest` 릴리스 대신 버전을 사용해야 합니다. 버전이 표기된 링크는 변하지 않는 것이 프로젝트 팀의 의도입니다. 예를 들자면, `https://owasp.org/www-project-web-security-testing-guide/v42/4-Web_Application_Security_Testing/01-Information_Gathering/02-Fingerprint_Web_Server.html`과 같은 링크를 사용해야 합니다. 여기서 `v42`는 버전 4.2를 나타냅니다.

## 기여, 기능 요청 및 피드백

저희는 계속해서 기여자들을 찾고 있습니다! 시작하려면, [기여 지침서](CONTRIBUTING.md)를 읽어보세요.

처음이신가요? [첫 기여자들을 위한 GitHub의 추천(영문)](https://github.com/OWASP/wstg/contribute)을 읽어보세요.

이 프로젝트는 많은 헌신적인 기여자들의 도움 덕분에 가능합니다. 누구나 크고 작게 도움을 줄 수 있습니다. 여러분이 도움을 줄 수 있는 몇 가지 방법입니다.

- 현재 문서를 읽고 오탈자 혹은 문법적 오류를 수정해주세요.
- [번역](CONTRIBUTING.md#translation) 작업에 기여해주세요.
- 열린 이슈를 고치기 위한 풀 리퀘스트를 제출해주세요.
- 개선의 가능성을 알리기 위해 새로운 이슈를 열어주세요.

기여하는 방법에 대해 알고 싶으시다면, [기여 지침서](CONTRIBUTING.md)를 읽어보세요.

기여자는 [프로젝트의 작성자, 검토자 또는 편집자 목록](document/1-Frontispiece/README.md)에 등재됩니다.

## 소통

Slack에서 저희와 소통하실 수 있습니다.

1. [여기](https://owasp.org/slack/invite)에서 OWASP 재단 Slack에 참여하세요.
2. 이 프로젝트의 채널, [#testing-guide(영문)](https://app.slack.com/client/T04T40NHX/CJ2QDHLRJ)에 참여하세요.

질문과 아이디어 제안 모두 환영합니다.

X에서 [@owasp_wstg](https://twitter.com/owasp_wstg)를 팔로우하세요.

또한 저희의 [Google 그룹](https://groups.google.com/a/owasp.org/forum/#!forum/testing-guide-project)에 가입하세요.

## 프로젝트 리더

- [Rick Mitchell](https://github.com/kingthorin)
- [Elie Saad](https://github.com/ThunderSon)

## 핵심 팀

- [Rejah Rehim](https://github.com/rejahrehim)
- [Victoria Drake](https://github.com/victoriadrake)

## 번역

- [한국어](https://github.com/sh9351/wstg-translation-kr)
- [Portuguese-BR](https://github.com/doverh/wstg-translations-pt)
- [Russian](https://github.com/andrettv/WSTG/tree/master/WSTG-ru)
- [French](https://github.com/clallier94/wstg-translation-fr)
- [Persian (Farsi)](https://github.com/whoismh11/owasp-wstg-fa)

### 한국어 번역
현재 [sh9351](https://github.com/sh9351)이 문서를 번역하고 있습니다. 아직까지는 초안 단계입니다.
#### 2024. 11. 25.
문서 번역을 시작했습니다. README, 머리말, 서론을 번역하였습니다. 프로젝트의 양을 깨닫고 너무 큰 일을 벌였나 후회합니다.

---

Open Web Application Security Project 및 OWASP는 OWASP 재단의 등록된 상표입니다.