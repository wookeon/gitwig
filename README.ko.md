<p align="center">
  <img src="./assets/gitwig-icon.png" alt="Gitwig 앱 아이콘" width="128">
</p>

# Gitwig

[English](./README.md) | 한국어

**브랜치가 많은 작업자를 위한 macOS Git 클라이언트.**

Gitwig는 저장소 히스토리, 작업 중인 변경사항, 브랜치, 리모트, 프로필, GitHub 계정 맥락을 하나의 조용한 데스크톱 작업 공간에 모읍니다.

Gitwig는 오픈소스가 아닌 무료 배포 소프트웨어입니다. 첫 공개 릴리스는 `0.0.1`로 준비 중입니다.

[다운로드](https://github.com/wookeon/gitwig/releases) | [릴리스 노트](./changelog/README.ko.md) | [이슈 제보](https://github.com/wookeon/gitwig/issues) | [오픈소스 고지](./THIRD_PARTY_NOTICES.md)

## Git을 더 조용하게, 더 선명하게

Gitwig는 macOS에서 Git 저장소의 흐름을 빠르게 이해하고 안전하게 조작하기 위한 데스크톱 클라이언트입니다.

브랜치가 많고, 변경사항이 쌓이고, 커밋 히스토리가 길어질수록 Git은 점점 "무엇이 어디에 있는지"를 확인하는 도구가 됩니다. Gitwig는 그 확인 비용을 줄이는 데 집중합니다. 지금 작업 중인 변경사항, 브랜치의 위치, 리모트와의 차이, 커밋의 맥락을 한 화면에서 이어서 볼 수 있게 만듭니다.

## 이런 분에게 맞습니다

- 터미널 Git은 익숙하지만, 저장소 상태를 시각적으로 확인하고 싶은 개발자
- 브랜치, stash, tag, submodule, conflict 작업을 자주 오가는 macOS 사용자
- 개인 프로젝트와 업무 프로젝트의 Git 작성자 정보와 계정을 분리해서 쓰고 싶은 사람
- GitHub Desktop보다 더 깊은 Git 흐름을 보고 싶지만, IDE 안에 갇히고 싶지는 않은 사람

## 첫 공개 릴리스에서 제공하는 것

**저장소 흐름을 한눈에 봅니다.**  
커밋 히스토리, 브랜치 흐름, 머지 요약, 작업 트리, 스테이징 영역을 한 화면에서 확인합니다. 긴 히스토리는 스크롤을 따라 자연스럽게 이어 불러오며, 중요한 브랜치와 커밋 해시가 안정적으로 보이도록 정리했습니다.

**변경사항을 자신 있게 다룹니다.**  
파일과 hunk 단위 stage/unstage, syntax-highlighted diff, 파일별 history/blame, `.gitignore` 규칙 추가, 충돌 파일 편집과 continue/abort/skip 흐름을 지원합니다.

**브랜치와 리모트를 실제 작업 흐름에 맞게 다룹니다.**  
checkout, merge, rebase, cherry-pick, revert, reset, fetch, pull, push, upstream 설정, rejected push 복구까지 데스크톱에서 이어서 처리할 수 있습니다.

**프로필로 작업 맥락을 분리합니다.**  
Gitwig 프로필마다 커밋 작성자 이름과 이메일, GitHub 계정 상태, 최근 저장소, 사이드바와 파일 트리 확장 상태를 분리합니다. 개인 작업과 업무 작업을 같은 앱 안에서 구분해 사용할 수 있습니다.

**실무 Git 작업을 첫 버전부터 포함합니다.**  
stash, tag, remote tag 삭제, submodule add/update/sync/open, conflict resolution을 첫 공개 릴리스부터 사용할 수 있습니다.

## 시작하기

1. Gitwig를 실행하고 프로필을 만듭니다.
2. 필요하다면 GitHub 계정을 연결합니다. 인증 정보는 macOS Keychain에 저장됩니다.
3. 저장소를 열거나 새로 clone합니다.
4. 히스토리와 변경사항을 확인하고, 필요한 파일만 stage합니다.
5. 커밋을 만들고 push합니다.

## 다운로드

첫 공개 릴리스는 GitHub Releases를 통해 배포할 예정입니다.

- 다운로드: [GitHub Releases](https://github.com/wookeon/gitwig/releases)
- 첫 공개 버전: `0.0.1`
- 요구사항: macOS 26.0 이상

아직 첫 릴리스 전이므로, Release 페이지에 다운로드 파일이 없을 수 있습니다.

## 피드백과 이슈 제보

요구사항, 기능 요청, 개선 제안, 버그 제보, 호환성 관련 질문은 [GitHub Issues](https://github.com/wookeon/gitwig/issues)에 남겨주세요.

버그를 제보할 때는 Gitwig 버전, macOS 버전, 문제가 발생한 Git 작업, 재현 절차, 기대한 결과, 실제 결과를 함께 적어주시면 확인이 빠릅니다. 저장소 URL, 접근 토큰, 비공개 커밋 내용, 고객 정보, 민감한 로그는 공개 이슈에 올리지 마세요.

## 배포와 라이선스

Gitwig는 무료로 사용할 수 있는 비오픈소스 소프트웨어입니다. 공식 GitHub Releases에서 제공하는 원본 앱만 신뢰하세요.

- 소스 코드는 이 저장소에서 제공하지 않습니다.
- 앱, 아이콘, 브랜드, 문서, 배포 패키지에 대한 권리는 저작권자에게 있습니다.
- 포함된 오픈소스 구성요소는 각 프로젝트의 라이선스를 따릅니다.

자세한 내용은 [`LICENSE`](./LICENSE)와 [`THIRD_PARTY_NOTICES.md`](./THIRD_PARTY_NOTICES.md)를 확인하세요.

## 개인정보

Gitwig는 로컬 저장소를 사용자의 Mac에서 직접 읽고 조작합니다. GitHub 계정 연결은 OAuth device flow를 사용하며, 인증 정보는 macOS Keychain에 저장됩니다.
