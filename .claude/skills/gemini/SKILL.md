---
name: gemini
description: Delegate prompts to Google Gemini CLI
---

# Gemini CLI Skill

Google Gemini CLI를 사용하여 작업을 수행합니다.

## 1. 사용 가능한 모델

### 1.1. CLI가 제공하는 모델

- `gemini-3.0-pro-preview` **기본 모델**

## 2. 사용 방법

CLI를 비대화형 모드로 실행하며, YOLO 모드(`--yolo`)를 사용하여 모든 작업을 자동으로 승인할 수 있습니다. 프롬프트는 위치 인자로 전달합니다.

### 예시

```bash
# 기본 사용
gemini "여기에 프롬프트 입력" --yolo

# 모델 지정 사용
gemini "여기에 프롬프트 입력" --model "gemini-1.5-pro" --yolo
