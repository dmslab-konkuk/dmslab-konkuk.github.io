---
layout: page
title: Research
---

## "Agentic AI 기술은 미래 시스템의 패러다임을 선도합니다." <div class="switch"><input id="langToggle" class="check-toggle check-toggle-round-flat" type="checkbox" checked><label for="langToggle"></label><span class="on">EN</span><span class="off">KO</span></div>

<style>
.switch {
  position: relative;
  display: inline-block;
  margin-left: 20px;
  vertical-align: middle;
}

.check-toggle {
  position: absolute;
  margin-left: -9999px;
  visibility: hidden;
}

.check-toggle + label {
  display: block;
  position: relative;
  cursor: pointer;
  outline: none;
  user-select: none;
}

.check-toggle-round-flat + label {
  padding: 2px;
  width: 60px;
  height: 30px;
  background-color: #dddddd;
  border-radius: 20px;
}

.check-toggle-round-flat + label:before,
.check-toggle-round-flat + label:after {
  display: block;
  position: absolute;
  content: "";
}

.check-toggle-round-flat + label:before {
  top: 2px;
  left: 2px;
  bottom: 2px;
  right: 2px;
  background-color: #fff;
  border-radius: 20px;
  transition: background 0.4s;
}

.check-toggle-round-flat + label:after {
  top: 4px;
  left: 4px;
  bottom: 4px;
  width: 22px;
  background-color: #dddddd;
  border-radius: 52px;
  transition: margin 0.4s, background 0.4s;
}

.check-toggle-round-flat:checked + label:after {
  margin-left: 30px;
  background-color: #008CBA;
}

.switch .on,
.switch .off {
  position: absolute;
  top: 8px;
  font-size: 12px;
  font-weight: bold;
  color: #666;
}

.switch .on {
  right: 8px;
}

.switch .off {
  left: 8px;
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const toggle = document.getElementById('langToggle');
  const currentPath = window.location.pathname;
  
  // 현재 페이지가 한국어 버전인지 확인
  if (currentPath.includes('index_ko')) {
    toggle.checked = true;
  }
  
  toggle.addEventListener('change', function() {
    if (this.checked) {
      // 한국어로 전환
      if (currentPath.includes('index.md') || currentPath.endsWith('/recruit/')) {
        window.location.href = currentPath.replace(/\/$/, '') + '/index_ko/';
      } else if (currentPath.includes('index.html')) {
        window.location.href = currentPath.replace('index.html', 'index_ko');
      }
    } else {
      // 영어로 전환
      if (currentPath.includes('index_ko.md')) {
        window.location.href = currentPath.replace('index_ko', 'index');
      }
    }
  });
});
</script>
건국대학교 KADA는 4차 산업혁명 시대의 핵심인 차세대 에어 모빌리티(Air Mobility)와 지능형 무인 이동체 분야를 선도하는 대학중점연구소를 포함한 다수의 국책과제를 수행하는 연구소입니다. 
본 채용은 KADA 연구소의 참여 연구그룹인 건국대학교 컴퓨터공학부의 DMS Lab(지도교수: 민덕기)에서 진행하며, 저희는 KADA의 비전을 AI/Cloud 기술로 실현하는 역할을 담당하고 있습니다. DMS Lab은 Agentic AI 기술과 Cloud 기반의 디지털 트윈 플랫폼 기술을 연구하고 있고, 복잡한 환경에서 다수의 무인기가 스스로 판단하고 인간과 유기적으로 협력하는 유무인 복합 시스템과 혼자 지내는 실버들의 벗과 헬스케어를 담당하는 Care Assistant 시스템 개발을 위한 차세대 AI 기술을 개발하는 국책연구과제 및 Bio-Generative AI 기술을 이용한 신약개발 연구를 수행하고 있습니다.
미래 Agentic AI 기술을 함께 개척해나갈, 세계 최고 수준의 연구에 도전할 열정적인 연구교수 또는 박사후연구원을 모집합니다.

### 1. 모집 분야
- 에이전틱 AI (Agentic AI) 기술 및 다양한 적용 분야
- 1. Multi-Agent Distributed Collaborative Agentic AI Framework
- 2. Multi-Model Context Perception and Navigation
- 3. Situation Understanding and Reasoning and Decision Making
- 4. Knowledge Construction, Inference and GraphRAG
- 5. Intelligent UAM(Urban Air Mobility) Digital Twin 
- 6. Intelligent Car Assistant Robot and Environment
- 7. Multi-Agent MUM-T(Manned-Unmanned Teaming) based on Agentic AI
- 8. Autonomous MLOps on Hybrid Cloud Platform with Agentic AIOps Tech.
- 9. Automated Disease-Drug Linkage and Optimization Using Bio-Generative AI
- 10. Various Applications of Deep Learning and Deep Reinforcement Learning

### 2. 주요 업무
1. 상기 주제에서 SCIE급 국제 저널 논문을 주도적으로, 공동협력으로 게재
2. 시뮬레이션과 현장 실험을 연계한 연구 프로토타입 설계 및 구현
3. 대학원생 지도 및 해외 공동연구 수행
4. 경쟁력 있는 연구비 제안서 작성

### 3. 지원 자격
- 필수 요건
- 컴퓨터 공학 또는 관련 분야 박사 학위 소지자 (2025년 8월 임용 전 취득 예정자 포함)
- AI/머신러닝 분야에 대한 깊이 있는 연구 경험 및 AI 프레임워크 활용 능력
- 우대 요건
- 에이전틱 AI, 대규모 언어 모델(LLM), 딥러닝/강화학습(RL) 관련 연구경험자
- 유무인 협력, 로보틱스, 자율주행, 디지털 트윈, 지능로봇 관련 프로젝트 유경험자
- AI 분야 최상위 학회 논문 게재 실적 또는 우수 연구 실적 보유자
- 분산/병렬 컴퓨팅, 클라우드 네이티브 환경 개발 경험자

### 4. 근무 조건
- 최초 계약 2년, 성과 및 예산에 따라 연장 가능
- 연봉은 대학 규정을 따르며 협의 가능
- 교내 전용 사무실, GPU 서버 지원, 국내외 유수 학회 참가비 지원

### 5. 제출 서류(단일 PDF)
1. 연구 적합성을 설명하는 자기소개서
2. 전체 연구 실적/경력/능력이 포함된 이력서(CV)
3. 향후 2년 연구 계획서(2쪽 이내)
4. 추천인 2인의 연락처

### 6. 채용 절차 및 일정
- 1차 접수 마감: 2025년 7월 25일 
- 서류 합격 통보: 2025년 7월 28일 저녁
- 오프라인 면접: 2025년 7월 29일부터 8월 1일까지
- 면접 합격 통보: 2025년 8월 3일
- 근무 시작 예정일: 2025년 8월 4일 이후 가능한 빠른 시점

### 7. 접수 방법 및 문의
- 단일 PDF 파일을 (dkmin@konkuk.ac.kr)로 제출
- 이메일 제목: \[Agentic AI for KU Recruitment] 성명, 소속
- 문의: 건국대학교 컴퓨터공학부 민덕기 교수 (dkmin@konkuk.ac.kr)