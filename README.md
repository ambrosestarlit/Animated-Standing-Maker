# AnimatedStandingMaker v21

## 修正
- OBS音声読み込みでPC全体のDesktop Audioを拾わないよう修正
- `Desktop Audio` / `デスクトップ音声` / `wasapi_output_capture` を自動候補から除外
- OBSに追加した音声ソースを優先して口パク対象にするよう変更
- 候補がない場合はDesktop Audioへフォールバックせず、OBSソース追加を案内

## Discordだけで口パクする場合
OBS側でDiscord専用の音声ソースを作ってください。
Desktop AudioはPC全体の音が混ざるため、自動候補から除外しています。
