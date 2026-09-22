# 허준범 Portfolio

GitHub Pages로 배포하는 개인 프로젝트 포트폴리오입니다.

프로젝트는 최신 활동부터 시간순으로 구성합니다. 현재는 `2026 프로젝트 보고서 챌린지(Class Project Challenge) · 시스템 SW`, `2026년 1학기 · 인공신경망 / 운영체제`, `2026 겨울학기 · 임베디드 소프트웨어`, `2025년 2학기 · 머신러닝 / 디지털시스템설계`, `2025 한이음 드림업`, `2025년 1학기 · 마이크로프로세서응용` 프로젝트를 담고 있습니다.

## Structure

- `/` — 소개와 대표 프로젝트
- `/projects/` — 전체 프로젝트 목록
- `/projects/cpc-fir-optimization/` — CPC FIR RTL Optimization
- `/projects/seoul-traffic-mlp/` — Seoul Traffic MLP
- `/projects/parallel-spam-classifier/` — Parallel Spam Classifier
- `/projects/dino-jump/` — Dino Jump
- `/projects/cipher-machine/` — Cipher Machine
- `/projects/touch-paintbrush/` — Touch Paintbrush
- `/projects/colored-mnist-classifier/` — Colored MNIST Classifier
- `/projects/reconfigurable-fir-filter/` — Reconfigurable FIR Filter
- `/projects/ai-iot-energy-esg/` — AI · IoT Energy ESG
- `/projects/arm-image-optimization/` — ARM Image Optimization

임베디드 프로젝트 상세 페이지에는 원본 메타데이터와 오디오를 제거하고 웹 재생에 맞게 정리한 시연 영상이 포함되어 있습니다. 각 프로젝트 보고서에서 선별한 설계 도식과 데이터시트 이미지, 실제 소스에 근거한 실행 흐름·인터럽트 구조·모델 성능·RTL 파형·메모리 맵·한계 및 개선 방향을 함께 제공합니다. 머신러닝, 디지털시스템설계, ARM 프로젝트는 정적 이미지와 측정 결과만 제공합니다.

새 프로젝트를 추가할 때는 `projects/<project-slug>/index.html`을 만들고 홈과 프로젝트 목록에 링크를 추가합니다.

## Local preview

정적 파일 서버로 이 디렉터리를 열면 됩니다.

```bash
python -m http.server 4173
```
