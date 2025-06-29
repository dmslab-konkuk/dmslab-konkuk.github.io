---
layout: page
title: Research
---

## "Agentic AI technology leads the paradigm of future systems." <div class="switch"><input id="langToggle" class="check-toggle check-toggle-round-flat" type="checkbox"><label for="langToggle"></label><span class="on">EN</span><span class="off">KO</span></div>

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
      if (currentPath.includes('index_ko')) {
        window.location.href = currentPath.replace('index_ko', 'index');
      }
    }
  });
});
</script>

Konkuk University's KADA is a research institute that conducts numerous national research projects, including university-focused research institutes leading the fields of next-generation Air Mobility and intelligent unmanned vehicles, which are core to the Fourth Industrial Revolution era.
This recruitment is conducted by the DMS Lab (PI: Professor Dugki Min) in the Department of Computer Science and Engineering at Konkuk University, which is a participating research group of the KADA research institute. We are responsible for realizing KADA's vision through AI/Cloud technologies. The DMS Lab researches Agentic AI technology and cloud-based digital twin platform technology, and conducts national research projects to develop next-generation AI technologies for manned-unmanned complex systems where multiple UAVs make autonomous decisions and organically cooperate with humans in complex environments, Care Assistant systems that serve as companions and healthcare providers for elderly individuals living alone, and drug discovery research using Bio-Generative AI technology.

We are recruiting passionate research professors or postdoctoral researchers who will pioneer future Agentic AI technology together and challenge world-class research.

### 1. Recruitment Areas
- Agentic AI technology and various application fields
  1. Multi-Agent Distributed Collaborative Agentic AI Framework
  2. Multi-Model Context Perception and Navigation
  3. Situation Understanding and Reasoning and Decision Making
  4. Knowledge Construction, Inference and GraphRAG
  5. Intelligent UAM (Urban Air Mobility) Digital Twin
  6. Intelligent Care Assistant Robot and Environment
  7. Multi-Agent MUM-T (Manned-Unmanned Teaming) based on Agentic AI
  8. Autonomous MLOps on Hybrid Cloud Platform with Agentic AIOps Tech.
  9. Automated Disease-Drug Linkage and Optimization Using Bio-Generative AI
  10. Various Applications of Deep Learning and Deep Reinforcement Learning

### 2. Main Responsibilities
1. Leading and collaboratively publishing SCIE-level international journal papers on the above topics
2. Designing and implementing research prototypes linking simulation and field experiments
3. Supervising graduate students and conducting international collaborative research
4. Writing competitive research grant proposals

### 3. Qualifications
Required:
- PhD degree in Computer Science or related fields (including those expected to obtain by August 2025 appointment)
- In-depth research experience in AI/machine learning fields and proficiency in AI frameworks
Preferred:
- Research experience in Agentic AI, Large Language Models (LLM), Deep Learning/Reinforcement Learning (RL)
- Experience in manned-unmanned cooperation, robotics, autonomous driving, digital twin, intelligent robot projects
- Publication record in top-tier AI conferences or excellent research achievements
- Experience in distributed/parallel computing and cloud-native environment development

### 4. Employment Conditions
- Initial contract: 2 years, extendable based on performance and budget
- Annual salary follows university regulations and is negotiable
- On-campus dedicated office, GPU server support, domestic and international conference participation support

### 5. Required Documents (Single PDF)
1. Cover letter explaining research suitability
2. CV including complete research achievements/career/capabilities
3. 2-year research plan (within 2 pages)
4. Contact information for 2 references

### 6. Recruitment Process and Schedule
- First application deadline: July 25, 2025
- Document screening results notification: Evening of July 28, 2025
- In-person interview: July 29 to August 1, 2025
- Interview results notification: August 3, 2025
- Expected start date: Earliest possible date after August 4, 2025

### 7. Application Method and Inquiries
- Submit single PDF file to: dkmin@konkuk.ac.kr
- Email subject: [Agentic AI for KU Recruitment] Name, Affiliation
- Inquiries: Professor Min Deok-gi, Department of Computer Science and Engineering, Konkuk University (dkmin@konkuk.ac.kr)