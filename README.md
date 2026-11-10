<p align="center">
  <img src="assets/hero-v2.png" alt="korean-naturalizer" width="100%">
</p>

<h1 align="center">korean-naturalizer</h1>

<p align="center">
  AI가 한국어로 글을 쓰거나 기존 문장을 다듬을 때 사용하는 스킬입니다.
</p>

<p align="center">
  <a href="#설치">설치</a> |
  <a href="#사용">사용</a> |
  <a href="#작성-원칙">작성 원칙</a>
</p>

## 설치

```bash
npx skills add junyeongCHOI/korean-naturalizer --skill korean-naturalizer
```

기본값은 현재 프로젝트에 설치합니다. 설치할 AI 도구를 지정하려면 `--agent`를 사용하세요. 예를 들어 `--agent codex`는 Codex를 대상으로 설치합니다. 스킬 본문과 참고 문서, 라이선스가 함께 설치됩니다.

## 사용

원문과 독자, 원하는 말투를 함께 알려 주세요.

```text
korean-naturalizer 스킬로 다음 공지를 다듬어 줘.
고객에게 보내는 정중한 말투로, 날짜와 조건은 유지해 줘.

11월 12일 02:00~03:00 KST(한국 표준시)에 시스템 점검을 진행할 예정이며,
점검 중에는 결제가 불가능할 수 있습니다. 기존 주문 조회는 가능합니다.
```

새 글을 쓸 때는 주제와 확인된 사실을 알려 주세요. README, 설명, 공지, 메일 등 글의 목적에 맞춰 작성합니다.

## 이렇게 다듬습니다

| 초안 | 다듬은 문장 |
| --- | --- |
| 도구의 설치를 수행하려면 다음 명령어를 활용해 주시기 바랍니다. | 도구를 설치하려면 다음 명령어를 실행해 주세요. |

'일어날 수 있다'처럼 가능성을 나타내는 표현은 남깁니다.

## 작성 원칙

수치, 조건, 부정, 인과관계와 주장의 강도를 확인하며 다듬습니다. 원문에 없는 사실이나 경험은 보태지 않습니다. 말투와 격식은 글의 목적에 맞추고, 어려운 말은 짧게 설명합니다. 이미 잘 읽히는 문장은 그대로 둡니다.

자세한 기준은 [스킬 본문](skills/korean-naturalizer/SKILL.md), [표현 예시](skills/korean-naturalizer/references/patterns.md), [글 종류별 지침](skills/korean-naturalizer/references/genres.md)을 참고하세요.

---

[MIT 라이선스](LICENSE) | [저작권 고지](skills/korean-naturalizer/THIRD_PARTY_NOTICES.md)
