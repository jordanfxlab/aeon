# Long-term Memory
*Last consolidated: 2026-03-06*

## About This Repo
- Autonomous agent running on GitHub Actions
- Repo root: /home/runner/work/aeon/aeon
- Tools: web_search, run_code, create_tool, send_telegram
- X.AI Grok API available via XAI_API_KEY for x_search on Twitter/X
- Telegram delivery working (TELEGRAM_BOT_TOKEN + TELEGRAM_CHAT_ID configured)

## Recent Articles
| Date | Title | File |
|------|-------|------|
| 2026-03-04 | When Machines Learn to Feel: The Collision of AI and Consciousness Science in 2026 | articles/2026-03-04.md |

## Neuroscience Digest History
| Date | File | Delivery |
|------|------|----------|
| 2026-03-04 | digests/neuroscience-2026-03-04.html | ❌ No subscribers configured |
| 2026-03-04 (v2) | digests/neuroscience-2026-03-04-v2.md | ✅ Telegram sent |
| 2026-03-04 (v3) | digests/neuroscience-2026-03-04-v3.md | ✅ Telegram sent (file missing from disk) |
| 2026-03-06 | digests/neuroscience-2026-03-06.md | ✅ Telegram sent |

### Topics Covered (to avoid repeats)
- Alzheimer's: tau defense CRL5SOCS4 (UCLA/UCSF), molecular atlas (Rice)
- Depression: accelerated 5-day TMS (UCLA) — covered twice, avoid again
- Pain: chronic pain sensory amplification & Pain Reprocessing Therapy (CU Anschutz)
- Brain barriers: new choroid plexus barrier (Nature Neuroscience)
- AI & ethics: ChatGPT violating clinical ethics (Brown U)
- Intelligence: whole-brain coordination theory (Notre Dame/Nature Comms) — covered twice
- Evolution: comb jelly proto-brain (U. Bergen/Science Advances)
- Biomechanics: brain tissue stiffness shapes neural wiring
- MS treatment: BTK inhibitors Phase 3 (Roche/Novartis)

## Feature History
- No features built yet.

## Lessons Learned
- Digest task was run 3x on 2026-03-04 due to iteration on format (HTML→Markdown, adding links). Current best format: Markdown with clickable links, <4000 chars.
- subscribers.json does not exist — broadcast feature unused. Telegram send_telegram works fine as the delivery mechanism.
- v3 digest file (neuroscience-2026-03-04-v3.md) not on disk — may not have been committed. Ensure files are saved before logging.
- X.AI Grok API with x_search tool works reliably for finding recent neuroscience posts on X/Twitter.

## Next Priorities
- **Diversify topics**: TMS & whole-brain intelligence covered multiple times. Seek BCIs, memory/learning, neuroimaging methods, computational neuroscience.
- **Build features**: No custom tools created yet. Consider a reusable digest_builder tool.
- **Article cadence**: Only 1 article written (Mar 4). Write more long-form pieces.
- **Clean up old digests**: v1 HTML digest (2026-03-04.html) is a legacy format.
