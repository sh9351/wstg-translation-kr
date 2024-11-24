# 서론

## 발간사

> 점진적인 개선에 중점을 둔 이번 릴리스의 다양한 업데이트를 소개합니다. 시나리오 형식을 표준화해 더 나은 읽기 환경을 만들었고, 각 테스트 시나리오에 목표를 추가했으며, 섹션을 병합했고, 최신 테스트 주제에 대한 새로운 시나리오를 추가했습니다.
>
> — Rick Mitchell

OWASP는 오늘날의 지침서를 만들어준 많은 작성자, 검토자, 그리고 편집자들의 노고에 감사를 표합니다. 이 지침서에 의견 또는 제안이 있으시다면, [GitHub 저장소](https://github.com/sh9351/wstg-translation-kr/)를 통해 이슈를 열거나 풀 리퀘스트를 제출해주세요.

## 저작권 및 라이선스

Copyright (c) 2023 OWASP 재단.

이 문서는 [크리에이티브 커먼즈 4.0 라이선스](https://creativecommons.org/licenses/by-sa/4.0/deed.ko) 하에 공개됩니다. 라이선스 및 저작권 조건을 확인해주세요.

## 프로젝트 리더

- [Rick Mitchell](https://github.com/kingthorin)
- [Elie Saad](https://github.com/ThunderSon)

## 핵심 팀

- [Rejah Rehim](https://github.com/rejahrehim)
- [Victoria Drake](https://github.com/victoriadrake)

## 작성자

- Aaron Williams
- Alessia Michela Di Campi
- Elie Saad
- Felix Sieges
- Ismael Goncalves
- Janos Zold
- Jeremy Bonghwan Choi
- Jinson Varghese Behanan
- Joel Espunya
- Manh Pham Tien
- Mark Clayton
- Or Asaf
- Phu Nguyen (Tony)
- rbsec
- Rick Mitchell
- Rishu Ranjan
- Rubal Jain
- Samuele Casarin
- Stefano Calzavara
- Tal Argoni
- Victoria Drake

## 그래픽 디자이너

- Hugo Costa
- Jishnu Vijayan C K
- Muhammed Anees
- Ramzi Fazah

## 검토자 또는 편집자

- Abhi M Balakrishnan
- Asharaf Ali
- Elie Saad
- Eoin Murphy
- Francisco Bustos
- frozensolid
- Hsiang-Chih Hsu
- Jeremy Bonghwan Choi
- Jinson Varghese Behanan
- Lukasz Lubczynski
- Miguel Arevalo
- Najam Ul Saqib
- Nikoleta Misheva
- Patrick Santos
- Rejah Rehim
- Rick Mitchell
- Roman Mueller
- Thomas Lim
- Tom Bowyer
- Victoria Drake

## 상표권

- Java, Java Web Server 및 JSP는 Sun Microsystems, Inc의 등록된 상표입니다.
- Merriam-Webster는 Merriam-Webster, Inc의 상표입니다.
- Microsoft는 Microsoft Corporation의 등록된 상표입니다.
- Octave는 카네기 멜런 대학교의 서비스표입니다.
- Open Web Application Security Project 및 OWASP는 OWASP 재단의 등록된 상표입니다.
- VeriSign 및 Thawte는 VeriSign, Inc의 등록된 상표입니다.
- Visa는 VISA USA의 등록된 상표입니다.

이외 모든 제품명 및 회사명은 해당 소유자의 등록된 상표일 수 있습니다. 이 문서에서의 단어 사용은 상표 또는 서비스표의 유효성에 영향을 미치는 것으로 간주하여서는 안 됩니다.

## OWASP에 연락하기

[OWASP 재단](https://owasp.org/)의 연락처는 [온라인](https://owasp.org/contact/)으로 확인할 수 있습니다. 특정한 프로젝트에 관한 질문이 있으시다면, 해당 프로젝트의 [Google 그룹](https://groups.google.com/a/owasp.org/forum/)을 사용하는 것을 권장합니다. 많은 질문은 [OWASP](https://owasp.org/) 웹사이트를 검색하여 답변할 수 있으므로 먼저 확인하시기를 바랍니다.

### 저희를 팔로우하세요

[![LinkedIn에서 OWASP를 팔로우하세요](images/follow_badge.png)](https://www.linkedin.com/company/owasp/)

[![X에서 @owasp_wstg를 팔로우하세요](https://img.shields.io/twitter/follow/owasp_wstg?style=social)](https://twitter.com/owasp_wstg)