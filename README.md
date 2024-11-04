# `F#` 배워보기

> `.NET`을 기반으로 서비스를 만들 수 있는 방법 중 함수형 언어의 특징을 살펴볼 수 있는 `F#`의 문법을 학습하는 과정을 짧게 소개하는 영상/기사에 활용된 저장소입니다. 학습용이라서 업무에 활용하실 때는 문법 및 관례 등을 고려해서 참고하세요.

## 준비사항

- `.NET SDK` >= 8.0
- `VSCode` >= 1.95

### `.NET` 설치

- Windows 사용자 분들은 [VS2022](https://visualstudio.microsoft.com/vs/)를 사용해서 `.NET` 관련 SDK를 설치하시면 됩니다.
- Linux(혹은 Ubuntu)의 경우 [Linux에 .NET 설치 문서]<https://learn.microsoft.com/en-us/dotnet/core/install/linux?WT.mc_id=DOP-MVP-5001859)를> 참고하세요.

```bash
sudo apt install dotnet-sdk-8.0
```

- macOS의 경우 Intel/ARM 버전에 따라 [다운로드 문서](https://dotnet.microsoft.com/ko-kr/download/dotnet/8.0?WT.mc_id=DOP-MVP-5001859)에서 자신의 하드웨어에 맞는 SDK를 설치하세요. 가능하면 `brew`를 사용하시면 `.NET`을 [손쉽게 설치](https://formulae.brew.sh/cask/dotnet)할 수 있습니다.

```bash
brew install --cask dotnet
```

### VSCode에서 `F#` 관련 설정

VSCode에서 아래 확장을 설치해주세요.

- [Ionide for F#](http://ionide.io/)
- [Polyglot Notebooks](https://github.com/dotnet/interactive)
