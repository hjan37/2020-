# Korean Election Research Classification Dataset (N=363)

이 저장소는 2020년 이후 한국 학술지 및 학위논문으로 발표된 선거 관련 연구 363편의 주제 분류 목록을 GitHub에서 열람·공유하기 쉽도록 정리한 데이터셋입니다.

## Files

| Path | Description |
|---|---|
| `data/election_research_363.csv` | GitHub/분석용 CSV. 영문 snake_case 컬럼명 사용 |
| `data/election_research_363_ko.csv` | 원자료 컬럼명을 유지한 한국어 CSV |
| `data/election_research_363.json` | 레코드 단위 JSON |
| `data/summary_by_topic.csv` | 14개 주제 분류별 요약 통계 |
| `data/summary_by_framework.csv` | Mozaffar-Schedler 프레임워크별 요약 통계 |
| `data/source_original.xlsx` | 원본 Excel 파일 |
| `docs/CODEBOOK.md` | 변수 설명 및 분류 기준 요약 |

## Dataset Summary

- Total records: **363**
- Unit of analysis: one election-related journal article or graduate thesis/dissertation
- Main classification: 14 topic categories
- Framework classification: Mozaffar-Schedler electoral governance framework

## Topic Distribution

| Rank | Topic | Count | % |
|---:|---|---:|---:|
| 1 | 선거제도 및 제도개혁 | 132 | 36.4 |
| 2 | 선거법제 및 법적 쟁점 | 56 | 15.4 |
| 3 | 전자투표 및 기술혁신 | 37 | 10.2 |
| 4 | 투표방식 및 참여확대 | 27 | 7.4 |
| 5 | 정당 및 후보자 공천 | 18 | 5.0 |
| 6 | 선거관리기관 제도론 | 18 | 5.0 |
| 7 | 선거보도 및 미디어 | 18 | 5.0 |
| 8 | 현장 선거행정 | 12 | 3.3 |
| 9 | 유권자 행태 및 투표참여 | 11 | 3.0 |
| 10 | 정치적 대표성 | 10 | 2.8 |
| 11 | 참정권 및 시민참여 | 9 | 2.5 |
| 12 | 지방선거 및 교육감 선거 | 6 | 1.7 |
| 13 | 민주시민교육 및 정치교육 | 5 | 1.4 |
| 14 | 선거운동 및 캠페인 | 4 | 1.1 |

## Mozaffar-Schedler Framework Distribution

| Framework | Count | % |
|---|---:|---:|
| 규칙 제정(Rule Making) | 164 | 45.2 |
| 규칙 적용(Rule Application) | 12 | 3.3 |
| 규칙 판정(Rule Adjudication) | 56 | 15.4 |
| 맥락 연구(Contextual) | 131 | 36.1 |

## Notes

- `m_s_framework_original`은 원본 Excel 파일의 값을 보존한 열입니다.
- `m_s_framework_normalized`는 논문 본문 표 기준에 맞춰 14개 주제 분류를 4개 영역으로 재매핑한 열입니다.
- `summary_by_topic.csv`의 누적비율은 반올림 오차를 고려하여 마지막 행을 100.0으로 정리했습니다.

## Recommended Citation

논문·보고서에서 활용할 경우, 연구자에 연락 후 사용허락을 득하시길 바랍니다. hjan37@gmail.com
## License

라이선스는 아직 지정하지 않았습니다. GitHub에 공개하기 전, 재사용 허용 범위에 따라 `LICENSE` 파일을 추가하세요.
