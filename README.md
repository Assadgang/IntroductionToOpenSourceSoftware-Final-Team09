# Research-WebAppStreamlitCSV

> 2025년 2학기 오픈소스SW의이해[01] - 09팀 프로젝트  
> **Repositorie Radar(레포지토리 자동 분석 서비스)**

## Preview

![Preview](Preview.png)

---

## 프로젝트 소개

Repositorie Radar는 GitHub 저장소를 자동으로 분석하여 **프로젝트 구조·핵심 코드·환경설정 정보를 빠르게 파악하도록 도와주는 웹 기반 분석 서비스입니다.**
오픈소스 프로젝트를 처음 접할 때 느끼는 진입장벽—방대한 파일 구조, 복잡한 코드 흐름, 부족한 문서—를 해소하기 위해 개발되었습니다.

사용자가 GitHub 저장소 URL을 입력하면, Repositorie Radar는 저장소를 클론한 뒤 다음 정보를 자동 분석해 제공합니다:

* **파일 트리 구조 시각화**
  프로젝트 전체 구조를 한눈에 파악할 수 있도록 정리·시각화합니다.

* **핵심 파일 및 엔트리 포인트 탐지**
  실행 흐름(예: main, index, app 파일)과 중요한 모듈을 자동으로 식별합니다.

* **환경 설정 자동 분석**
  requirements.txt, package.json 등 환경 구성 파일을 감지하고 설치 가이드를 자동 제공해줍니다.

* **의존성 및 코드 관계 분석**
  import/require 분석을 기반으로 주요 모듈 간 관계도를 생성합니다.

* **문서·이슈 분석 (부가 기능)**
  README 품질 분석과 GitHub 이슈 요약을 제공하여 프로젝트 이해도를 높입니다.

Repositorie Radar는 **Streamlit 기반 인터페이스**를 활용하여 누구나 쉽게 저장소를 입력하고 분석 결과를 시각적으로 확인할 수 있도록 구현되었습니다.
오픈소스 입문자, 신규 기여자, 코드 리뷰어, 리서처에게 특히 유용한 도구입니다.

## 팀원 소개

| 이름 | 역할 | 담당 | GitHub |
|------|------|------------|---------|
| 김민준 | 팀장 | 아키텍처 | [minjunkim0205](https://github.com/minjunkim0205) |
| 안현서 | 팀원 | API | [han183536-ux](https://github.com/han183536-ux) |
| 김민태 | 팀원 | API | [Assadgang](https://github.com/Assadgang) |
| 김재욱 | 팀원 | 디자인 | [Gplexs](https://github.com/Gplexs) |

> 위 링크는 팀원 각자의 GitHub 프로필로 연결됩니다

---

## 환경 설정 (최초1회)

> Python 3.13.5  
> .venv 가상환경 생성  
> pip install -r requirements.txt  

---

## 메모(무시 해도 됩니다)

> pip freeze > requirements.txt
