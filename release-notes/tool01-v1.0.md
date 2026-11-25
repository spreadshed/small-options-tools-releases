# Tool 1: Covered Call Evaluator & Log v1.0

A free spreadsheet that checks a covered call before you sell it, then logs every leg and tracks your P/L.

**Download:** [tool01-covered-call-evaluator-log-v1.0.xlsx](https://github.com/spreadshed/small-options-tools-releases/releases/download/tool01-v1.0/tool01-covered-call-evaluator-log-v1.0.xlsx)

**What's inside**
- **Evaluator:** type in a trade from your broker and get two verdicts: assignment risk (PASS / WARN / FAIL) and trade quality (GO / CAUTION / NO-GO). Checks: delta, earnings before expiration, calls covered by shares, bid/ask spread. It also flags inputs that can't all be right, like an expiration before the trade date.
- **Trade Log:** one row per leg (Sell to Open, Buy to Close, Expired, Assigned, Rolled) for up to 1,000 legs. Position IDs, P/L and status fill in automatically.
- **Summary:** total, realized and open P/L, win rate, money in and out, activity.
- **Example:** a filled-in log with two made-up trades.

**How to open:** Excel, Google Sheets (Drive → New → File upload, then open with Google Sheets) or LibreOffice Calc. Formulas only, no macros.

Free for noncommercial use under the PolyForm Noncommercial License 1.0.0. Educational tool, not financial advice.

SHA-256: `e83cc60478298953370982ff6b7b21e4a6632edc82baeadd51ff56e39c08ea07`
