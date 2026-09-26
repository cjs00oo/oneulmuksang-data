# oneulmuksang-data

오늘묵상 앱이 읽는 공개 데이터(묵상집 코스 일정 · 성구 참조만).
자동 발행: `oneulmuksang-qt-cron` 의 qt-daily 워크플로가 CloudKit production 을 내보낸다. 손으로 고치지 말 것.

- `v1/plans.json`
- `v1/schedule/{planId}/{YYYY-MM}.json`
