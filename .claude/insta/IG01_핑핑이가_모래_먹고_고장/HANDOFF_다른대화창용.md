# 클로이 인스타 — 다른 대화창 전달용

## 1. 오늘 게재할 이미지 (IG01 확정본)

- 이미지: https://d8j0ntlcm91z4.cloudfront.net/user_3HA9UC6vECHnwup9ttpS6UIs9yy/hf_20260929_004756_cb44be19-40ea-4715-b8d2-4e317b2eeed6.png
- 장면: 저녁 라운지. 담요 덮고 소파에서 잠든 클로이, 무릎 위 하트 눈 핑핑, 핑핑 머리 위 분홍 빛(다음 편 떡밥)
- 생성: 힉스필드 회사 계정(ultra) · gpt_image_2 / medium / 2k · 3:4 (1744×2336) · job `cb44be19-40ea-4715-b8d2-4e317b2eeed6`
- 게재 전: 위아래 각 78px 잘라 4:5 → 1080×1350 · "AI 정보" 라벨 켜기
- 카드 문구(선택, 하단): 오늘은 일 안 해. 너랑 쉴 거야.

### 피드 멘션

```
오늘은 여기까지. 핑핑이랑 같이 쉬는 중이에요 🩷

탐사 다녀와서 핑핑이가 모래를 먹었거든요.
귀 안쪽까지 싹 털어 줬더니
[지직—] → [삐빅!] 다 나았대요 🤖

근데 저 잠든 사이에… 핑핑이 머리 위에 뭐가 떠 있었어요? ✨


That's it for today. Resting with Ping-Ping 🩷

Ping-Ping ate some sand on our exploration trip.
I brushed every grain out of its ears,
[bzzt—] → [beep-beep!] and it's all better 🤖

But while I was asleep… what was floating above Ping-Ping's head? ✨

@오포인트공식계정

#클로이 #ChloeAventis #핑핑 #PingPing #오포인트 #OPoint #타르시스 #제12탐사대 #탐사일지 #로봇수리 #aiart
```

## 2. 이미지 가이드 — 셀카 금지 (2026-09-29 상은님 지시)

- **셀카 금지.** 클로이가 폰을 들고 찍는 구도, 카메라를 보는 구도 모두 쓰지 않는다
- 모든 이미지는 **관찰자 시점의 시네마틱 스틸**. 아무도 카메라를 보지 않는다
- 사진마다 **이야기가 있는 장면**을 담는다: 무슨 일이 일어났는지 한 장만 봐도 보이게
- 캐러셀(최대 3장)은 **장마다 시점을 다르게**: 와이드(상황) · 탑뷰/접사(디테일) · 미디엄(감정)
- 장마다 위치나 시간대도 바꿔서 시작 → 중간 → 끝으로 읽히게 한다
- 프롬프트 STYLE 문장 고정: `photoreal cinematic still from a slice-of-life film, observed from a distance; nobody looks at the camera`
- 피드 그리드도 셀카 얼굴이 이어지지 않게: 와이드 상황 → 핑핑 클로즈업 → 광물·소품 순으로 돌린다

## 3. 고정 규칙 요약

- 등장: 클로이 + 핑핑만. 팀장(바렌 토르카)은 화면 밖(홀로그램 명령서로만)
- 클로이: 실내복(분홍 재킷) 레퍼런스 `char_o4_chloe`만. suit 금지
- 핑핑: 공식 표정만(사랑=하트 눈, 무표정, 슬픔, 분노, 체념, 노려보기). 사람 말 안 함
- 이미지 생성 기본값: gpt_image_2 / medium / 2k / 3:4 (다른 모델은 상은님이 말할 때만)
- 힉스필드는 회사 계정(ultra, `3c86addd-ee92-4062-92ea-e13c162099af`)에서만. 무료 계정은 워터마크 → 생성 금지
- 회사 계정 레퍼런스 media_id (gpt_image_2는 medias role = `image`)
  - 클로이 `1457b7d4-9d62-41c9-b594-513f3ba17de1`
  - 핑핑 `49dfbb7e-adf6-4afa-86b2-e38209f8c353`
  - 라운지 `4ea05507-8568-4992-baf8-2dd7c744979b`
  - 담요 `28b5c60c-ce81-4a43-a469-cf775d8b5b12`
- 멘션: 한글 → 엔터 두 번 → 영문 → @멘션 → 해시태그. 클로이 1인칭, 이모지 언어별 3개 이내
- 시점 설정: 모래폭풍 오기 전. 폭풍 얘기 금지
- 보고: 슬랙 상은님 DM

## 4. 남은 일

1. 오포인트 공식 인스타 계정 핸들 → 멘션 `@` 자리
2. 인스타 게재는 수동 (4:5 트리밍, AI 정보 라벨)
3. 다음 편 IG02 기획 (episode-bank.md 후보에서 3편 규칙 확인)

## 5. 전체 자료

- 스킬 폴더: `.claude/skills/opoint-chloe-insta/` (함께 보내는 zip과 동일)
- GitHub: sangeun1000/opoint-preview-5a26d2 · 브랜치 `claude/eager-heisenberg-yef9hx`
