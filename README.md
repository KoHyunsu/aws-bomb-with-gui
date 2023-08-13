# aws-bomb-with-gui

### 💥 클릭 한 번으로 당신의 AWS 리소스를 싹 삭제해 드립니다 💥


> [!NOTE]
> 본 프로그램은 [aws-nuke](https://github.com/rebuy-de/aws-nuke.git) 를 바탕으로 제작되었습니다.

## 사전준비
1. [TAURI 공식 안내서](https://tauri.app/ko/v1/guides/getting-started/prerequisites) 를 참고하여 Rust와 의존성 소프트웨어를 설치합니다.
2. 
    (Windows) /src-tauri/external/aws-nuke-x86_64-pc-windows-msvc.zip 의 압축을 해제합니다.

    (MacOS) /src-tauri/external/aws-nuke-darwin-arm64.tar.gz 의 압축을 해제합니다.

## 개발환경
```(shell)
cd aws-bomb-with-gui
npm install
cargo tauri dev
```

## 배포환경
```(shell)
cd aws-bomb-with-gui
npm install
cargo tauri build
```
빌드가 완료되면 /target/bundle 경로 내에 완성된 프로그램이 저장됩니다.

## 문제해결
만약 cargo tauri dev 또는 cargo tauri build 명령이 제대로 동작하지 않는다면
프로젝트 루트 경로 기준, .next, out, target을 삭제하고 재시도해볼 것을 권장드립니다.