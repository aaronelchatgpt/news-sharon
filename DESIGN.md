---
version: beta
name: sharon-daily-hot
description: A refined, feminine daily-briefing surface. Warm ivory canvas, rose accents, serif display headings and generous whitespace. Built for a single reader (Sharon) who consumes ten curated stories each morning with voice and PDF. Calm, editorial, never loud.
colors:
  canvas: "#fbf8f4"
  paper: "#ffffff"
  ink: "#2a2422"
  ink-soft: "#3a2f2b"
  body: "#5c534d"
  muted: "#a3968d"
  rose: "#b76e79"
  rose-soft: "#f6e9ea"
  rose-line: "#e6cfd1"
  gold: "#b99a6b"
  hairline: "#eee4dc"
typography:
  display-xl:
    fontFamily: "Georgia, Songti SC, Noto Serif SC, serif"
    fontSize: 36px
    fontWeight: 400
    lineHeight: 1.25
    letterSpacing: 4px
  display-md:
    fontFamily: "Georgia, Songti SC, Noto Serif SC, serif"
    fontSize: 21px
    fontWeight: 400
    lineHeight: 1.3
    letterSpacing: 3px
  kicker:
    fontFamily: "-apple-system, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: 9.5px
    fontWeight: 700
    lineHeight: 1.4
    letterSpacing: 5px
  greeting:
    fontFamily: "-apple-system, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: 13px
    fontWeight: 400
    lineHeight: 1.7
    letterSpacing: 1.5px
  date:
    fontFamily: "-apple-system, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: 10.5px
    fontWeight: 400
    lineHeight: 1.5
    letterSpacing: 3px
  item-title:
    fontFamily: "-apple-system, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: 16px
    fontWeight: 700
    lineHeight: 1.65
    letterSpacing: 0.3px
  item-desc:
    fontFamily: "-apple-system, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: 12.5px
    fontWeight: 400
    lineHeight: 1.85
    letterSpacing: 0
  rank:
    fontFamily: "Georgia, Songti SC, serif"
    fontSize: 19px
    fontWeight: 400
    lineHeight: 1.2
    letterSpacing: 0
  tag:
    fontFamily: "-apple-system, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: 9.5px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 1.5px
  hot:
    fontFamily: "-apple-system, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: 10px
    fontWeight: 400
    lineHeight: 1.4
    letterSpacing: 1px
  button:
    fontFamily: "-apple-system, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: 11.5px
    fontWeight: 600
    lineHeight: 1
    letterSpacing: 1.5px
  footnote:
    fontFamily: "-apple-system, PingFang SC, Microsoft YaHei, sans-serif"
    fontSize: 11px
    fontWeight: 400
    lineHeight: 2
    letterSpacing: 0.5px
rounded:
  sm: 8px
  md: 12px
  lg: 16px
  pill: 9999px
spacing:
  xxs: 4px
  xs: 8px
  sm: 12px
  md: 16px
  lg: 24px
  xl: 32px
  section: 38px
components:
  page-shell:
    backgroundColor: "{colors.canvas}"
    maxWidth: 680px
    padding: 44px 24px 64px
    margin: 0 auto
  header:
    textAlign: center
    paddingBottom: 26px
    borderBottom: "1px solid {colors.hairline}"
  kicker-label:
    textColor: "{colors.rose}"
    typography: "{typography.kicker}"
    textTransform: uppercase
  page-title:
    textColor: "{colors.ink-soft}"
    typography: "{typography.display-xl}"
    margin: 14px 0 10px
  greeting-line:
    textColor: "{colors.body}"
    typography: "{typography.greeting}"
  date-line:
    textColor: "{colors.muted}"
    typography: "{typography.date}"
    marginTop: 10px
  media-card:
    backgroundColor: "{colors.paper}"
    border: "1px solid {colors.hairline}"
    rounded: "{rounded.lg}"
    padding: 12px 14px
    display: flex
    alignItems: center
    gap: 12px
    boxShadow: "0 10px 28px rgba(58, 40, 32, 0.05)"
    margin: 24px auto 0
  audio-player:
    flex: 1
    height: 36px
    minWidth: 0
  pdf-button:
    backgroundColor: "{colors.rose-soft}"
    textColor: "{colors.rose}"
    border: "1px solid {colors.rose-line}"
    rounded: "{rounded.pill}"
    padding: 9px 14px
    typography: "{typography.button}"
    textDecoration: none
    whiteSpace: nowrap
  pdf-button-hover:
    backgroundColor: "{colors.rose-line}"
    textColor: "{colors.ink-soft}"
  section:
    marginTop: "{spacing.section}"
  section-header:
    display: flex
    alignItems: center
    gap: 12px
  section-title:
    textColor: "{colors.ink-soft}"
    typography: "{typography.display-md}"
    margin: 0
  section-rule:
    flex: 1
    height: 1px
    backgroundColor: "{colors.hairline}"
  section-meta:
    textColor: "{colors.muted}"
    fontSize: 9.5px
    letterSpacing: 2px
  item-list:
    listStyle: none
    margin: 6px 0 0
    padding: 0
  item-row:
    display: flex
    gap: 16px
    padding: 18px 0
    borderBottom: "1px solid {colors.hairline}"
  item-row-last:
    borderBottom: 0
  item-rank:
    flex: "0 0 26px"
    textColor: "{colors.rose}"
    typography: "{typography.rank}"
    opacity: 0.75
    paddingTop: 1px
  item-body:
    minWidth: 0
  item-title:
    textColor: "{colors.ink}"
    typography: "{typography.item-title}"
  item-desc:
    textColor: "{colors.body}"
    typography: "{typography.item-desc}"
    marginTop: 6px
  item-meta:
    marginTop: 8px
    display: flex
    gap: 6px
    alignItems: center
    flexWrap: wrap
  source-tag:
    textColor: "{colors.muted}"
    typography: "{typography.tag}"
    border: "1px solid {colors.hairline}"
    rounded: "{rounded.pill}"
    padding: 2px 8px
    backgroundColor: "{colors.paper}"
  hot-value:
    textColor: "{colors.gold}"
    typography: "{typography.hot}"
  footer:
    marginTop: 40px
    paddingTop: 18px
    borderTop: "1px solid {colors.hairline}"
    textColor: "{colors.muted}"
    typography: "{typography.footnote}"
    textAlign: center
rules:
  - One accent color only. Rose marks rank numbers, the kicker and the PDF button. Never color item titles.
  - Gold is reserved for hot values. Never use it for text, borders or backgrounds.
  - Serif for display, ranking numbers and section titles; humanist sans for everything else.
  - Maximum one shadow on the page (the media card). Lists and rows use hairline rules, never boxes.
  - Keep 5 items per section. If fewer than 5 real matches exist, show fewer — never pad with unrelated stories.
  - Title and body are separated by a full stop in the voice script; the page never truncates the title.
  - The media card always sits directly under the date, above the first section, never elsewhere.
  - Whitespace is content. Section gap 38px, row padding 18px, line-height 1.65+ for Chinese text.
  - All body copy is Chinese by default; keep the English kicker as a quiet editorial signal.
accessibility:
  - Body text on canvas must stay at or above 4.5:1 contrast; muted text is for metadata only.
  - Touch targets (PDF button, audio controls) at least 36px tall.
  - Never rely on color alone to convey rank or hot values; the number and unit are always present.
content:
  sections:
    - name: 明星热点
      count: 5
      intent: celebrity news only; skip politics, finance and general society
    - name: 小红书热词
      count: 5
      intent: lifestyle, beauty, photography, gadgets; label the source honestly
  voice:
    - Read the title, then the body, with an 800ms pause after each title.
    - Close with 以上是为您定制的全球早报，祝您今天愉快，万事顺心。 only for the daily briefing; this page uses its own closing line.
