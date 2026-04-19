# WrittenTest

> 필기 테스트 문제를 복기하고 정리하는 개인 학습 프로젝트

---

## 폴더 구조

```
WrittenTest/
│
├── WrittenTest/              # C# 코드 실험용 콘솔 앱
│   └── Program.cs
│
├── Problems/
│   ├── Private/              # 🔒 실제 기업 필기 복기 (git 제외)
│   │   └── [Company]/
│   │       ├── 1번 문제.md
│   │       └── 2번 문제.md
│   │
│   ├── Public/               # 🌐 연습용 가상 문제 (공개)
│   │   └── YYYY-MM-DD_제목.md
│   │
│   └── TEMPLATE.md           # 문제 파일 템플릿
│
└── .claude/
    └── skills/
        └── clean-code-style/ # C#/Unity 코드 스타일 가이드
```

---

## 문제 타입

| 타입 | 설명 |
|------|------|
| `exam` | 실제 필기 시험에서 복기한 문제 |
| `practice` | Claude Code와 함께 만든 연습 문제 |

---

## 파일 네이밍 규칙

- **Private**: `Problems/Private/[회사명]/N번 문제.md`
- **Public**: `Problems/Public/YYYY-MM-DD_제목.md`
