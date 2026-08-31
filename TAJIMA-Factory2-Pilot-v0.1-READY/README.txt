TAJIMA 第2工場 PILOT v0.1
- admin.html: 관리페이지
- machine1.html: 1호기 태블릿
- setup.sql: Supabase에 1회 실행
- config.example.js를 config.js로 복사 후 기존 Supabase URL/anon key 입력
- 기존 본사 일정 테이블과 섞이지 않도록 f2_ 테이블로 완전 분리
- 1호기 T01~T80, 공구교환/칩교환/주의/타기계이동
- 제품→품번→공정 등록, 다음 공정 후보 자동 선별, 변동사항 전달
- 관리페이지는 공정/공구 기록과 미해결 경고를 10초마다 갱신
※ 파일럿이라 공개 RLS 정책. 본운영 전 인증/RLS 강화 필요.
