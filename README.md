## 환경 설정 (OpenAI 키)

1. `.env.example`를 복사해 `.env`를 만듭니다.
   ```bash
   cp .env.example .env
   ```
2. `.env` 안의 `OPENAI_API_KEY`에 발급받은 키를 채워 넣습니다.
3. 필요하면 `OPENAI_BASE_URL`, `OPENAI_ORG_ID`를 주석 해제 후 값으로 설정합니다.

`.gitignore`에 `.env`가 등록되어 있어 키가 커밋되지 않습니다.
