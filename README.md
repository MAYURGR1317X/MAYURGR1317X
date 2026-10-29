# MAYURGR1317X

Project-local install of the [Day Trader skill pack](https://github.com/Jakeschincariol/day-trader-skill)
(v2.0.0, commit `3d0f4ef`, MIT; see `.claude/skills/LICENSE-day-trader-skill`).

The 11 skills live in `.claude/skills/` and show up in Claude Code as plain slash commands:
`/trader-scanner`, `/trader-news`, `/trader-entry`, `/trader-exit`, `/trader-timemachine`,
`/trader-risk`, `/trader-budget`, `/trader-broker`, `/trader-alerts`, `/trader-analyst`, `/trader-pelosi`.

Working files land in `trader/`. The SEC tools need `"sec_user_agent": "Your Name you@example.com"`
in `trader/config.json` or the `SEC_USER_AGENT` environment variable. Python 3.8+, no dependencies.

`.claude/settings.json` keeps every order-placing or order-cancelling broker tool (Alpaca and Robinhood)
on "ask", so Claude must get your approval for each call. Paper trading is the default. Not financial advice.
