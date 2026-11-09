# greet-release

명령행 인수로 받은 이름에 인사말을 출력하는 프로그램이다.

## 설치와 실행

```bash
uv sync --locked
uv run --locked python greet.py Hee
uv run --locked pytest -q greet.py
```

## 버전 전략

유의적 버전(Semantic Versioning)을 따른다.
