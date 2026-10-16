# erin-mml-converter
Mabinogi Mobile MML converter

## Claude Code: MarkItDown

이 저장소에는 [MarkItDown](https://github.com/microsoft/markitdown) MCP 서버가 설정되어 있습니다 (`.mcp.json`).
Claude Code가 PDF, Word, Excel, PowerPoint, HTML, 이미지 등 다양한 파일을 Markdown으로 변환할 수 있습니다.

- 필요 조건: [`uv`](https://docs.astral.sh/uv/) (`uvx`로 `markitdown-mcp`를 자동 실행)
- 제공 도구: `convert_to_markdown(uri)` — `file:`, `http:`, `https:`, `data:` URI 지원
- CLI로 직접 사용: `uvx --from 'markitdown[all]' markitdown 파일.pdf > 파일.md`
