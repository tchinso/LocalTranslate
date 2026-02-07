여기 있는 txt 파일들은 ezTransXP 문법으로 작성된 번역 사전 지정 파일이야.
ezTransXP 는 인공지능이 아닌 rule-based 번역기야.
여기 있는 사전 파일들을 기반으로 브라우저 상에서 동작하는 웹 번역기를 만들거임.
우선 지금 있는 그대로 쓰기는 힘드니까 사전으로 쓸 수 있는 형태로 가공해야돼.

### 만들 사전 파일들 

step01_pre_filter_base: 전처리 토글/옵션과 기본 전처리 규칙(Pre Filters) 정의 파일입니다. 이건 이미 만들었어.

step02_pre_filter_custom: 미인식 문자 치환 등 커스텀 전처리 규칙과 확장 문자 변환(반각 가타카나 등) 규칙입니다. 이건 이미 만들었어

step03_pre_filter_personal: 개인용 전처리 교정/정규화 규칙입니다.

step04_userdict_required: 필터링에 필요한 더미 명사/접두·접미 등 필수 기반 사용자 사전입니다.

step05_userdict_core: 감동사·상용어구 등 핵심 사용자 사전 항목입니다.

step06_userdict_names: 인명/고유명사 중심의 이름 사전(공용/개인용)입니다.

step07_userdict_custom: 커스텀 사용자 사전 항목(패턴 기반 사용자 규칙 포함)입니다.

step08_userdict_personal: 개인용 사용자 사전(범주 표기 VBl/VBp/VHn 포함)입니다.

step09_priority_and_skip_layer: 우선 처리 사용자 사전, 단순 후커 사전, 그리고 SkipLayer 규칙을 묶었습니다.

step10_post_filter_and_notes: 후처리(Post Filters) 규칙 + 사용자/개인 후처리 보정 + 변경 내역/수정 목록 참고 파일입니다.



