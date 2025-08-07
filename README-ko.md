# Claude Code Slash Commands

지능형 자동화를 통해 개발을 가속화하는 [Claude Code](https://docs.anthropic.com/en/docs/claude-code)용 Production-ready slash commands입니다.

**52개 명령어**가 다음과 같이 구성되어 있습니다:
- **🤖 Workflows**: 복잡한 작업을 위한 다중 subagent orchestration
- **🔧 Tools**: 특정 작업을 위한 단일 목적 유틸리티

### 🤝 Claude Code Subagents 필요

이 명령어들은 orchestration 기능을 위해 [Claude Code Subagents](https://github.com/wshobson/agents)와 함께 작동합니다.

## 설치

```bash
cd ~/.claude
git clone https://github.com/wshobson/commands.git
git clone https://github.com/wshobson/agents.git  # Subagent orchestration에 필요
```

## 사용 가능한 명령어

- **🤖 Workflows** - 복잡한 작업을 위한 다중 subagents orchestration
- **🔧 Tools** - 특정 작업을 위한 단일 목적 명령어

## 사용법

```bash
/api-scaffold user management with authentication
/security-scan check for vulnerabilities
/feature-development implement chat functionality
```

Claude Code가 context를 기반으로 관련 명령어를 자동으로 제안합니다.

## 🤖 Workflows

복잡한 작업을 위한 다중 subagent orchestration:

### Feature Development
- **[feature-development](workflows/feature-development.md)** - Backend, frontend, testing, deployment subagents가 완전한 기능을 구축
- **[full-review](workflows/full-review.md)** - 다중 review subagents가 포괄적인 코드 분석 제공
- **[smart-fix](workflows/smart-fix.md)** - 이슈를 분석하고 적절한 전문 subagents에게 위임

### Development Processes
- **[git-workflow](workflows/git-workflow.md)** - 브랜치 전략과 PR template을 포함한 효과적인 Git workflows 구현
- **[improve-agent](workflows/improve-agent.md)** - Prompt 최적화를 통한 subagent 성능 향상
- **[legacy-modernize](workflows/legacy-modernize.md)** - 전문 subagents를 사용한 legacy codebase 현대화
- **[ml-pipeline](workflows/ml-pipeline.md)** - 데이터 및 ML 엔지니어링 subagents를 통한 ML pipeline 생성
- **[multi-platform](workflows/multi-platform.md)** - 조정된 subagents로 크로스 플랫폼 앱 구축
- **[workflow-automate](workflows/workflow-automate.md)** - CI/CD, monitoring, deployment workflows 자동화

### Subagent-Orchestrated Workflows
- **[full-stack-feature](workflows/full-stack-feature.md)** - Backend, frontend, mobile subagents를 통한 다중 플랫폼 기능
- **[security-hardening](workflows/security-hardening.md)** - 전문 subagents를 통한 보안 우선 구현
- **[data-driven-feature](workflows/data-driven-feature.md)** - 데이터 과학 subagents를 통한 ML 기반 기능
- **[performance-optimization](workflows/performance-optimization.md)** - 성능 subagents를 통한 end-to-end 최적화
- **[incident-response](workflows/incident-response.md)** - Ops subagents를 통한 production incident 해결

## 🔧 Tools (단일 목적 명령어)

### AI & Machine Learning
- **[ai-assistant](tools/ai-assistant.md)** - Production-ready AI assistants 및 chatbots 구축
- **[ai-review](tools/ai-review.md)** - AI/ML codebases를 위한 전문 review
- **[langchain-agent](tools/langchain-agent.md)** - 최신 패턴으로 LangChain/LangGraph agents 생성
- **[ml-pipeline](tools/ml-pipeline.md)** - MLOps를 포함한 end-to-end ML pipelines 생성
- **[prompt-optimize](tools/prompt-optimize.md)** - 성능과 품질을 위한 AI prompts 최적화

### Architecture & Code Quality
- **[code-explain](tools/code-explain.md)** - 복잡한 코드의 상세한 설명 생성
- **[code-migrate](tools/code-migrate.md)** - 언어, 프레임워크, 버전 간 코드 마이그레이션
- **[refactor-clean](tools/refactor-clean.md)** - 유지보수성과 성능을 위한 코드 리팩터링
- **[tech-debt](tools/tech-debt.md)** - 기술 부채 분석 및 우선순위 지정

### Data & Database
- **[data-pipeline](tools/data-pipeline.md)** - 확장 가능한 데이터 파이프라인 아키텍처 설계
- **[data-validation](tools/data-validation.md)** - 포괄적인 데이터 검증 시스템 구현
- **[db-migrate](tools/db-migrate.md)** - 고급 데이터베이스 마이그레이션 전략

### DevOps & Infrastructure
- **[deploy-checklist](tools/deploy-checklist.md)** - Deployment 구성 및 체크리스트 생성
- **[docker-optimize](tools/docker-optimize.md)** - 고급 컨테이너 최적화 전략
- **[k8s-manifest](tools/k8s-manifest.md)** - Production급 Kubernetes deployments
- **[monitor-setup](tools/monitor-setup.md)** - 포괄적인 모니터링 및 관찰 가능성 설정
- **[slo-implement](tools/slo-implement.md)** - Service Level Objectives (SLOs) 구현
- **[workflow-automate](tools/workflow-automate.md)** - 개발 및 운영 workflows 자동화

### Development & Testing
- **[api-mock](tools/api-mock.md)** - 개발 및 테스트를 위한 현실적인 API mocks 생성
- **[api-scaffold](tools/api-scaffold.md)** - 완전한 구현 스택을 포함한 production-ready API endpoints 생성
- **[test-harness](tools/test-harness.md)** - 프레임워크 감지를 포함한 포괄적인 test suites 생성

### Security & Compliance
- **[accessibility-audit](tools/accessibility-audit.md)** - 포괄적인 접근성 테스트 및 수정
- **[compliance-check](tools/compliance-check.md)** - 규정 준수 보장 (GDPR, HIPAA, SOC2)
- **[security-scan](tools/security-scan.md)** - 자동 수정을 포함한 포괄적인 보안 스캔

### Debugging & Analysis
- **[debug-trace](tools/debug-trace.md)** - 고급 디버깅 및 추적 전략
- **[error-analysis](tools/error-analysis.md)** - 깊은 오류 패턴 분석 및 해결 전략
- **[error-trace](tools/error-trace.md)** - Production 오류 추적 및 진단
- **[issue](tools/issue.md)** - 잘 구조화된 GitHub/GitLab issues 생성

### Dependencies & Configuration
- **[config-validate](tools/config-validate.md)** - 애플리케이션 구성 검증 및 관리
- **[deps-audit](tools/deps-audit.md)** - 보안 및 라이센스에 대한 종속성 감사
- **[deps-upgrade](tools/deps-upgrade.md)** - 프로젝트 종속성 안전한 업그레이드

### Documentation & Collaboration
- **[doc-generate](tools/doc-generate.md)** - 포괄적인 문서 생성
- **[git-workflow](tools/git-workflow.md)** - 효과적인 Git workflows 구현
- **[pr-enhance](tools/pr-enhance.md)** - 품질 검사를 통한 pull requests 개선

### Cost Optimization
- **[cost-optimize](tools/cost-optimize.md)** - 클라우드 및 인프라 비용 최적화

### Onboarding & Setup
- **[onboard](tools/onboard.md)** - 새 팀원을 위한 개발 환경 설정

### Subagent Tools
- **[multi-agent-review](tools/multi-agent-review.md)** - 전문 subagents를 통한 다각도 코드 리뷰
- **[smart-debug](tools/smart-debug.md)** - Debugger와 성능 subagents를 통한 깊은 디버깅
- **[multi-agent-optimize](tools/multi-agent-optimize.md)** - 다중 subagents를 통한 full-stack 최적화
- **[context-save](tools/context-save.md)** - Context-manager subagent를 사용한 프로젝트 컨텍스트 저장
- **[context-restore](tools/context-restore.md)** - 연속성을 위한 저장된 컨텍스트 복원

## 기능

- Production-ready 구현
- Framework 자동 감지
- 보안 모범 사례
- 내장 모니터링 및 테스트
- 명령어들이 완벽하게 함께 작동

## 명령어 개수

**총 52개의 production-ready slash commands**가 다음과 같이 구성되어 있습니다:

### 🤖 Workflows (14개 명령어)

- Feature Development & Review (3개 명령어)
- Development Process Automation (6개 명령어)
- Subagent-Orchestrated Workflows (5개 명령어)

### 🔧 Tools (38개 명령어)

- AI & Machine Learning (5개 명령어)
- Architecture & Code Quality (4개 명령어)
- Data & Database (3개 명령어)
- DevOps & Infrastructure (6개 명령어)
- Development & Testing (3개 명령어)
- Security & Compliance (3개 명령어)
- Debugging & Analysis (4개 명령어)
- Dependencies & Configuration (3개 명령어)
- Documentation & Collaboration (1개 명령어)
- Onboarding & Setup (1개 명령어)
- Subagent-Specific Tools (5개 명령어)

## 사용 예시

### 🤖 Workflow 예시

```bash
# 완전한 기능 구현
/feature-development Add user authentication with OAuth2

# 포괄적인 코드 리뷰
/full-review Review the authentication module

# 스마트 이슈 해결
/smart-fix Fix performance degradation in API response times

# Legacy 시스템 현대화
/legacy-modernize Migrate monolithic Java app to microservices

# 포괄적인 멀티플랫폼 기능 구축
/full-stack-feature User authentication with social login across web and mobile

# 보안 우선 아키텍처 구현
/security-hardening Harden API endpoints and implement zero-trust security model

# 데이터 기반 ML 기능 생성
/data-driven-feature Build recommendation engine with real-time personalization

# 전체 애플리케이션 스택 최적화
/performance-optimization Improve response times and reduce infrastructure costs

# Production incident 대응
/incident-response High CPU usage causing service degradation in production
```

### 🔧 Tool 예시 (단일 목적 명령어)

```bash
# 사용자 관리 API 생성
/api-scaffold user CRUD operations with JWT auth and role-based access

# Microservices 아키텍처 리뷰
/multi-agent-review analyze our microservices for coupling and scalability issues

# LLM 채팅 애플리케이션 최적화
/prompt-optimize reduce latency for customer support chatbot while maintaining accuracy

# 사기 탐지 파이프라인 생성
/data-pipeline real-time fraud detection with feature store and monitoring

# Production 이슈 디버그
/error-trace analyze high memory usage in production pods

# 컨테이너 이미지 보안
/security-scan scan and fix vulnerabilities in Docker images

# API 문서 생성
/doc-generate create OpenAPI docs with examples for REST endpoints

# 새로운 개발자 온보딩
/onboard Setup development environment for React/Node.js project

# 다각도 코드 리뷰
/multi-agent-review Review authentication module

# 깊은 디버깅
/smart-debug Investigate memory leak in production workers

# Full-stack 최적화
/multi-agent-optimize Optimize checkout flow for better conversion

# 프로젝트 컨텍스트 저장
/context-save Save current project state and architectural decisions

# 프로젝트 컨텍스트 복원
/context-restore Load context from last week's sprint
```

## 강화된 명령어

### Security & DevOps

#### [`/security-scan`](tools/security-scan.md)

자동 수정을 포함한 포괄적인 보안 스캔.

- **Multi-Tool 스캔**: Bandit, Safety, Trivy, Semgrep, ESLint Security, Snyk
- **자동 수정**: 일반적인 취약점 자동 수정
- **CI/CD 통합**: GitHub Actions/GitLab CI를 위한 보안 게이트
- **컨테이너 스캔**: 이미지 취약점 분석
- **Secret 탐지**: GitLeaks 및 TruffleHog 통합

#### [`/docker-optimize`](tools/docker-optimize.md)

고급 컨테이너 최적화 전략.

- **스마트 최적화**: 분석하고 개선사항 제안
- **Multi-Stage Builds**: 프레임워크별 최적화된 Dockerfiles
- **최신 도구**: 빠른 빌드를 위한 BuildKit, Bun, UV
- **보안 강화**: Distroless 이미지, non-root 사용자
- **Cross-Command 통합**: /api-scaffold 출력과 연동

#### [`/k8s-manifest`](tools/k8s-manifest.md)

Production급 Kubernetes deployments.

- **고급 패턴**: Pod Security Standards, Network Policies, OPA
- **GitOps Ready**: FluxCD 및 ArgoCD 구성
- **Observability**: Prometheus ServiceMonitors, OpenTelemetry
- **Auto-Scaling**: HPA, VPA, cluster autoscaler configs
- **Service Mesh**: Istio/Linkerd 통합

### Frontend & Data

#### [`/db-migrate`](tools/db-migrate.md)

고급 데이터베이스 마이그레이션 전략.

- **Multi-Database**: PostgreSQL, MySQL, MongoDB, DynamoDB
- **Zero-Downtime**: Blue-green deployments, rolling migrations
- **Event Sourcing**: CDC를 위한 Kafka/Kinesis 통합
- **Cross-Platform**: Polyglot persistence 처리
- **Monitoring**: 마이그레이션 상태 확인 및 롤백

## Workflows와 Tools 결합

실제 강력함은 완전한 개발 주기를 위해 workflows와 tools을 결합하는 것에서 나옵니다:

### 예시: 새로운 기능 구축

```bash
# 1. 다중 subagents로 기능을 구현하는 workflow 사용
/feature-development Add real-time chat feature with WebSocket support

# 2. 특정 개선사항을 위한 tools 사용
/test-harness Add integration tests for WebSocket connections
/security-scan Check for WebSocket vulnerabilities
/docker-optimize Optimize container for WebSocket connections

# 3. 포괄적인 리뷰를 위한 workflow 사용
/full-review Review the entire chat feature implementation
```

### 예시: Legacy 코드 현대화

```bash
# 1. 현대화 workflow로 시작
/legacy-modernize Migrate Express.js v4 app to modern architecture

# 2. 정리를 위한 특정 tools 사용
/deps-upgrade Update all dependencies to latest versions
/refactor-clean Remove deprecated patterns and dead code
/test-harness Ensure 100% test coverage

# 3. 최적화 및 배포
/docker-optimize Create multi-stage production build
/k8s-manifest Deploy with zero-downtime strategy
```

## Command Orchestration 패턴

명령어들은 개별적으로 사용하거나 강력한 패턴으로 결합할 수 있습니다:

### 순차 실행
```bash
# Build → Test → Secure → Deploy pipeline
/api-scaffold user management API
/test-harness comprehensive test suite for user API  
/security-scan check user API for vulnerabilities
/k8s-manifest deploy user API to production
```

### 병렬 분석
```bash
# 동일한 codebase에 대한 다양한 관점
/multi-agent-review comprehensive architecture and code review
/security-scan audit security posture  
/performance-optimization identify and fix bottlenecks
# 그 다음 결과 통합
```

### 반복적 개선
```bash
# 넓게 시작해서 점점 좁혀가기
/feature-development implement payment processing
/security-scan focus on payment security
/compliance-check ensure PCI compliance
/test-harness add payment-specific tests
```

### 도메인 간 통합
```bash
# Frontend + Backend + Infrastructure
/api-scaffold backend payment API
/multi-agent-optimize optimize payment flow performance
/docker-optimize containerize payment service
/monitor-setup payment metrics and alerts
```

## Workflows vs Tools 사용 시기

### 🔀 Workflows & Subagent Tools
- **문제 해결**: 적응적으로 이슈 분석 및 수정
- **다양한 관점**: 전문 subagents 조정
- **복잡한 작업**: 도메인 간 다단계 프로세스
- **알려지지 않은 솔루션**: Subagents가 접근 방식 결정

### 🛠️ 전문화된 Tools
- **인프라 설정**: 환경 구성
- **코드 생성**: 특정 구현 생성
- **분석**: 수정 없이 보고서 생성
- **도메인 작업**: 고도로 전문화된 작업

**예시:**
- "사용자 인증 시스템 구현" → `/feature-development`
- "스택 전반의 성능 이슈 수정" → `/smart-fix`
- "Legacy monolith 현대화" → `/legacy-modernize`

### 🔧 Tools 사용 시기:
- **특정 전문성 필요** - 하나의 도메인에서 명확하고 집중된 작업
- **정확한 제어 원함** - 특정 구현 세부사항을 지시하고 싶을 때
- **수동 workflow의 일부** - 기존 프로세스에 통합
- **깊은 전문성 필요** - 전문가 수준의 구현이 필요할 때
- **기존 작업 기반 구축** - 이전 결과물 개선이나 정제

**예시:**
- "Kubernetes manifest 생성" → `/k8s-manifest`
- "보안 취약점 스캔" → `/security-scan`
- "API 문서 생성" → `/doc-generate`

## Command 형식

Slash commands는 간단한 markdown 파일로:
- 파일명이 명령어 이름이 됩니다 (예: `api-scaffold.md` → `/api-scaffold`)
- 파일 내용이 호출될 때 실행되는 prompt/instructions입니다
- 사용자 입력을 위해 `$ARGUMENTS` placeholder를 사용합니다

## 모범 사례

### Command 선택
- **Claude Code가 자동으로 제안하도록 하기** - 컨텍스트를 분석하고 최적의 명령어 선택
- **복잡한 작업에는 workflows 사용** - Subagents가 다중 도메인 구현 조정
- **집중된 작업에는 tools 사용** - 대상 개선을 위한 특정 명령어 적용

### 효과적인 사용
- **포괄적인 컨텍스트 제공** - 기술 스택, 제약사항, 요구사항 포함
- **전략적으로 명령어 연결** - Workflows → Tools → 정제
- **이전 출력 기반 구축** - 명령어들은 함께 작동하도록 설계됨

## 기여하기

1. `workflows/` 또는 `tools/`에 `.md` 파일 생성
2. lowercase-hyphen-names 사용
3. 사용자 입력을 위해 `$ARGUMENTS` 포함

## 문제 해결

**명령어를 찾을 수 없음**: 파일이 `~/.claude/commands/`에 있는지 확인

**Workflows가 느림**: 정상 - 다중 subagents를 조정하기 때문

**일반적인 출력**: 기술 스택에 대한 더 구체적인 컨텍스트 추가

**통합 이슈**: 파일 경로와 명령어 순서 확인

## 성능 팁

**Command 선택:**
- **Workflows**: 복잡한 기능을 위한 다중 subagent 조정
- **Tools**: 특정 작업을 위한 단일 목적 작업
- **간단한 편집**: Main agent와 함께 유지

**최적화:**
- 알려진 문제에는 tools로 시작
- 처음부터 상세한 요구사항 제공
- 이전 명령어 출력 기반 구축
- Workflows가 완료되기 전까지 수정하지 않기

### 새로운 Workflow 추가:
- Subagent orchestration과 위임 로직에 집중
- 어떤 전문 subagents를 어떤 순서로 사용할지 명시
- Subagents 간 조정 패턴 정의

### 새로운 Tool 추가:
- 완전하고 production-ready한 구현 포함
- 명확한 섹션과 실행 가능한 출력으로 콘텐츠 구조화
- 예시, 모범 사례, 통합 지점 포함

## 더 알아보기

- [Claude Code Documentation](https://docs.anthropic.com/en/docs/claude-code)
- [Slash Commands Documentation](https://docs.anthropic.com/en/docs/claude-code/slash-commands)
- [Subagents Documentation](https://docs.anthropic.com/en/docs/claude-code/sub-agents)
- [Claude Code GitHub](https://github.com/anthropics/claude-code)
- [Claude Code Subagents Collection](https://github.com/wshobson/agents) - 이 명령어들에서 사용하는 전문 subagents