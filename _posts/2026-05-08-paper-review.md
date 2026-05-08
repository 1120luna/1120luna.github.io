---
title: "[논문리뷰] Can Personal Health Information Be Secured in LLM? Privacy Attack and Defense in the Medical Domain"
date: 2026-05-08 18:00:00 +0900
categories: [논문, 개인정보 침해, 의료]
tags: [research, Privay attack, Defense, Medical LLM, Personal Health Information]
excerpt: LLM에서 개인 건강 정보는 안전하게 보호될 수 있을까요? 의료 영역에서의 개인정보 침해 및 방어
published: true
---
## 논문 정보
> 제목: Can Personal Health Information Be Secured in LLM? Privacy Attack and Defense in the Medical Domain<br>
> 학회: ACM SIGSAC Conference on Computer and Communications Security (CCS) 2025 (Accepted)<br>
> 저자: Yujin Kang (강유진, 중앙대학교), Eunsun Kim (김은선, 중앙대학교), Yoon-Sik Cho (조윤식, 중앙대학교, 교신저자)<br>
> 키워드: Privay attack(개인정보 침해), Defense(방어), Medical LLM(의료용 대형 언어 모델), Personal Health Information(개인 건강 정보)
<br>

### 논문을 고른 이유
개인정보에 대해서는 평소에 관심이 많아서 논문집에서 개인정보 세션의 논문 중에서 제목만 보고 관심 있는 논문을 찾으려고 하였었다. 그리고 요새 이슈가 대형 언어 모델(LLM)의 정보 유출 위험도 말이 나오고 있고, 민감한 정보인 의료 데이터가 LLM을 통해 어떻게 유출될 수 있는 지 그리고 어떻게 방어하는 것인지 알고 싶어서 이 논을 선정하였다.

### 문제 정의
- LLM의 정보 유출 위험 증가<br>
LLM의 규모가 커지면서 단순히 학습 데이터를 암기하는 것을 넘어, 정보 간의 연관성을 파악해 개인의 속성을 추론하는 능력이 강해지고, 도메인 작업을 위해 비공개 데이터 모델을 미세 조정하는 방식이 주류가 되었으나, 범용 모델보다 학습 데이터를 더 쉽게 암기하고 노출하는 취약점 가진다.
- 기존 연구의 한계와 의료 도메인 특화 민감 정보 연구의 부재<br>
기존의 개인정보 침해 공격 연구들은 주로 개인식별정보의 유출에만 국한되어 있었으며, 의료 분야는 훨씬 더 민감하고 도메인에 특화된 정보들을 다룸에도 불구하고, 의료 LLM을 대상으로 한 도메인 특화 개인정보 유출 위험 조사는 매우 부족한 상황이다.

### 핵심 아이디어

### 앞으로 해볼 것
1. 해당 논문의 저자 연구팀(중앙대학교 산업보안학과/보안융합대학원)이 2024년에 개인정보 유출 문제와 관련하여 발표한 논문인 "한국어 초거대언어모델의 개인정보 유출 양상 분석"이라는 논문을 읽어 볼 것입니다.
2. 1번에서 말한 논문을 정리하여 블로그에 올리는 것을 목표로 해 볼 것입니다.
3. 논문을 읽었을 때, 몰랐던 영어 단어가 너무 많아서 검색한 것이 많았는데, 그것들을 정리해 볼 예정입니다.
