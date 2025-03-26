# 사이버보안 문서 관리 Git 실습 - 브랜치 관리

이 저장소는 사이버보안과 학생들이 Git 브랜치 관리 전략과 릴리스 버전 관리를 학습하기 위한 실습 자료를 제공합니다.

## 실습 목표
- Git 브랜치 생성 및 관리 방법 습득
- 태그(Tag)를 이용한 버전 관리 이해
- 릴리스 노트 작성 및 GitHub Release 기능 활용
- 브랜치 병합(Merge) 및 충돌 해결 경험
- 소프트웨어 개발 생명주기에 맞는 브랜치 전략 적용

## 사용 방법
1. 이 저장소를 자신의 계정으로 포크(Fork)하세요
2. 포크한 저장소를 로컬에 클론(Clone)하세요
3. [실습 지시사항](./assignment-02.md)에 따라 과제를 수행하세요
4. 변경사항을 커밋하고 푸시하세요
5. 각 버전별 태그와 릴리스 노트를 작성하세요
6. 제출 기한까지 Pull Request를 생성하여 제출하세요

## 수업 자료
[4주차 수업 자료](https://gamma.app/docs/Git--msuglst588e6fed)

## 저장소 구조
```
SecurityDocs/                     # 보안 문서 저장소
├── Policies/                     # 정책 문서 폴더
│   ├── password_policy.md        # 패스워드 정책
│   └── access_control_policy.md  # 접근 통제 정책
├── Procedures/                   # 절차 문서 폴더
│   ├── incident_response.md      # 보안 사고 대응 절차
│   └── vulnerability_assessment.md  # 취약점 평가 절차
├── Templates/                    # 템플릿 폴더
│   └── security_report.md        # 보안 보고서 템플릿
└── Checklists/                   # 체크리스트 폴더
    └── security_audit.md         # 보안 감사 체크리스트
```

## 평가 기준
- 브랜치 및 태그 관리의 정확성
- 커밋 메시지의 명확성
- 릴리스 노트의 품질과 전문성
- 문서 내용의 완성도와 일관성
- 브랜치 병합 및 충돌 해결 능력
- 제출 기한 준수

## 주요 개념
- **브랜치(Branch)**: 독립적인 작업 공간
- **태그(Tag)**: 특정 커밋에 대한 참조 포인트
- **릴리스(Release)**: 소프트웨어 배포 단위
- **병합(Merge)**: 브랜치 간 변경사항 통합

## 문의 사항
과제 수행 중 질문이 있으면 Teams 채팅을 통해 문의하세요.

# 사이버보안 문서 관리 프로젝트

이 저장소는 사이버보안 관련 문서(정책, 절차, 가이드라인, 템플릿, 체크리스트)를 관리하기 위한 중앙 저장소입니다. Git 버전 관리와 브랜치 관리 실습을 위해 사용됩니다.

## 저장소 구조

- **Policies/** - 보안 정책 문서
  - password_policy.md - 패스워드 정책
  - access_control_policy.md - 접근 통제 정책
- **Procedures/** - 보안 절차 문서
  - incident_response.md - 보안 사고 대응 절차
  - vulnerability_assessment.md - 취약점 평가 절차
  - backup_recovery.md - 백업 및 복구 절차
- **Templates/** - 문서 템플릿
  - security_report.md - 보안 보고서 템플릿
  - incident_report.md - 보안 인시던트 보고서 템플릿
- **Checklists/** - 보안 체크리스트
  - security_audit.md - 보안 감사 체크리스트
- **Guidelines/** - 보안 가이드라인
  - secure_coding.md - 보안 코딩 가이드라인

## 버전 이력

- v1.0 - 초기 안정 버전
- v2.0-alpha - 확장된 문서 세트 포함 알파 버전
- v2.0-beta - 향상된 인시던트 대응 기능 포함 베타 버전
- v2.0 - 완성된 2.0 최종 버전

## 사용 방법

이 저장소의 문서는 마크다운 형식으로 제공되며, 조직의 요구에 맞게 사용자 정의할 수 있습니다. 각 문서는 버전 관리되어 변경 이력을 추적할 수 있습니다.

## 라이선스

이 프로젝트는 MIT 라이선스에 따라 제공됩니다. 자세한 내용은 LICENSE.md 파일을 참조하세요.