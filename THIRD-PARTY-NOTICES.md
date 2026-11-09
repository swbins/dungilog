# 둥이로그 — 서드파티 고지 · 상표 (Third-Party Notices)

둥이로그 자체 코드는 무료로 배포하는 비공개 소프트웨어입니다(All rights reserved — 실행 파일만 배포, 소스는 공개하지 않음).
실행 파일(DungiLog.exe · DungiLog.app)에는 아래 오픈소스가 함께 들어갑니다. 각 구성 요소는 자기 라이선스를 따르며,
빌드할 때 그 라이선스 전문을 함께 묶습니다 — 앱 **설정 → 고지 · 개인정보** 에서 볼 수 있습니다.

| 구성 요소 | 라이선스 | 비고 |
|---|---|---|
| Python 런타임 · 표준 라이브러리 | PSF License 2.0 | 함께 들어가는 OpenSSL(Apache-2.0) · libffi(MIT) · zlib(zlib) · bzip2 · xz(공개) · SQLite(퍼블릭 도메인) 고지 포함 |
| Pillow | MIT-CMU (HPND) | 함께 들어가는 libjpeg-turbo(IJG · BSD-3) · libpng(PNG) · libtiff · libwebp(BSD-3) · FreeType(FreeType License 를 고름) · Little CMS(MIT) · OpenJPEG(BSD-2) · HarfBuzz(MIT) 등 — 전문은 Pillow 의 LICENSE 에 모두 있음 |
| pi-heif (아이폰 HEIC 사진 읽기) | BSD-3-Clause · 묶인 libheif 1.18 · libde265 1.0 은 **LGPLv3** | 읽기 전용(인코더 x265 없음). 따로 된 DLL 로 들어가 바꿔 끼울 수 있음. 소스: https://github.com/strukturag/libheif · https://github.com/strukturag/libde265 · LGPL·GPL 전문 함께 묶음 |
| PyInstaller 부트로더 | GPL-2.0 + 부트로더 예외(배포 허용) | https://github.com/pyinstaller/pyinstaller/blob/develop/COPYING.txt |

외부 글꼴·스크립트(CDN)는 쓰지 않습니다 — 화면은 PC 에 깔린 글꼴만 쓰고, QR 그리기·오르골 소리는 직접 만든 코드입니다.
AI 프로그램(Ollama · Claude Code · Codex · Gemini CLI)은 둥이로그에 들어 있지 않습니다. 쓰려면 사용자가 직접 설치합니다.
「무료 AI 고르기」의 추천 모델(gemma4:e4b · gemma4:e2b, Apache-2.0)도 앱에 묶지 않습니다 — 사용자가 고르면 이 PC 의 Ollama 가 직접 받습니다.
Ollama 가 없는 PC 에서는 사용자가 「받기」를 누를 때 앱이 llama.cpp 의 llama-server(MIT, © The ggml authors, github.com/ggml-org/llama.cpp)와
구글 공식 Gemma 4 QAT 모델 파일(Apache-2.0, huggingface.co/google)을 받아 이 PC 안에서만 돌립니다. llama.cpp 라이선스 전문은 licenses/llama.cpp-LICENSE.txt 에 있습니다(윈도우 배포 zip 에는 빠져 있어서).

## 상표

Claude 와 Claude Code 는 Anthropic, PBC 의 상표입니다. ChatGPT · Codex 는 OpenAI, Gemini 는 Google LLC,
Ollama 는 Ollama Inc., 네이버 블로그 · 카페 · 검색광고는 NAVER Corp., Instagram 은 Meta, TikTok 은 ByteDance 의 상표입니다.
둥이로그는 이 회사들과 제휴 · 보증 관계가 없는 독립 제품이며, 이 이름들은 함께 쓸 수 있는 도구 · 글을 올릴 곳을 설명하려고만 씁니다.

DungiLog is an independent product and is not affiliated with, endorsed by, or sponsored by Anthropic, OpenAI, Google,
Ollama, NAVER, Meta, or ByteDance.
