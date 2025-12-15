# CHECKPOINT 4: Recent Discoveries (Dec 13-15, 2025)
## From Latest Conversation Searches

---

## 🆕 NEW SYSTEMS DISCOVERED

### 1. MEGA CLAUDE.md v3.0 System
- Each of 16 sites has ~5,700 line comprehensive CLAUDE.md
- Includes: Full context, MCP config, fallback automation, content workflows
- Created with Python generator script
- Total: ~92,000 lines across all 16 sites

### 2. Systeme.io Browser Automation Training
- Complete skill package (52KB SKILL.md + 22KB STAGEHAND-IMPLEMENTATION.md)
- Covers: Login flows, blog posts, funnels, newsletters, automation rules
- Uses Steel.dev/BrowserUse fallback chain
- Location: /mnt/skills/user/systeme-io-browser-automation/

### 3. Content Source Tagging (A/B Testing)
- ZIMM Pipeline adds: `<!-- content-source:zimm -->`
- Factory workflows add: `<!-- content-source:factory -->`
- Purpose: A/B test content quality between systems
- Goal: Master content, consolidate to best-performing

### 4. Creative Command Center
- 16 DNA files (419KB design intelligence)
- Site-specific design tokens, colors, typography
- Enforces "Modern Tech Picasso" aesthetic
- Prevents generic AI-generated look

---

## 🔧 WORKFLOW FIXES APPLIED (Dec 12-13)

### ZimmWriter Pipeline Fixes
| Workflow | Issue | Fix | Result |
|----------|-------|-----|--------|
| 06 Assembly & Publish | 14% success, "content.replace not function" | Defensive type checking | 100% success |
| 03 Section Writer | String type issues | Type validation | 67% → 100% |
| 04 Enhancement Engine | Object passed instead of string | Type coercion | 75% → 100% |

### Factory Workflow Fixes
| Factory | Issue | Fix |
|---------|-------|-----|
| AI & Tech Factory | 0% success, Invalid URL | Changed Freepik → Runware routing |
| All Factories | UUID bug | `{{ $randomUUID }}` → `={{ $uuid }}` |
| All Factories | Provider mismatch | Standardized to Runware |

### Scheduler Rebuilt
- Was: Parallel execution (caused Cloudflare 524 timeouts)
- Now: Sequential with SplitInBatches (batch size 1)
- Cooldown: 30 seconds between sites
- HTTP timeout: 10 minutes (600000ms)

---

## 📋 WORDPRESS CREDENTIALS DISCOVERED

### Site Registry with App Passwords
| Site | Username | App Password |
|------|----------|--------------|
| smarthomewizards.com | SmartHomeGuru | E2Pe BGoq 7nOd I2eP BbCu BtGm |
| aiinactionhub.com | AIinActionGuru | QLl8 HqRS 6OQk p4uL Rbmx IYE1 |
| aidiscoverydigest.com | AIDiscoveryGuru | 6SH3 Q8jA dQya yF3y NQ78 ZLUN |
| wealthfromai.com | WealthFromAI | s8Jy awIJ Yqew 06XZ OlCI Gdg5 |
| mythicalarchives.com | mytharch | wU8i bIvs cxKh bHzk WqLA k4jM |
| bulletjournals.net | bulletjournals | xjpg 1NVY g1rH WDFj 2xWD S6ww |
| pulsegearreviews.com | PulseGearPro | qwlV aZ9m GZrS wdSX EFPR 6HbD |
| wearablegearreviews.com | WearableGearGuru | G6qG 6SIm 2xJd 8R9P LoEW yjsf |
| smarthomegearreviews.com | SmartHomeGearGuru | m1LO VN9c y3gD 4Jbz NXdR t9XD |
| clearainews.com | ClearAIGuru | 7ht8 aM6j iyba YfTY vfIK 97QF |
| celebrationseason.net | CelebrationPro | 30pN axyI 0q5A qDlV 1c47 L0d6 |
| sprout-and-spruce.com | SproutSpruceGuru | VQhR dNaU NX17 bHDZ 4qXV btsp |

### Default Password
- For sites without specific app password: `Ashlynn.09`
- Create app passwords in WP Admin → Users → Profile → Application Passwords

---

## 🆕 APIs DISCOVERED

### Additional API Keys Found
```yaml
Ideogram: KBcAUNEc8HGqBMIKApZtpN2uavLN1tMiTt0Z3rsIK3eNo_bByDc6MV9etvpZ231Ny1fiVd9LQT1QR9XqsWkHuA
Exa: 04659a4d-8122-4e4c-b5c3-59f754c69317
Runware: D9cbC9LkS1H3s10aMB2qNdEV3bJ56U0p62nSYFCLu5FkpFFPhKIBcqJkAX1H7oJp (alternate)
```

### Older n8n API Key (still referenced)
```yaml
Older Key: eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJzdWIiOiIzNDZkZmIxMS05YmM0LTRkNzAtYTk4ZC03MGFjNWI2YjU1ZjAiLCJpc3MiOiJuOG4iLCJhdWQiOiJwdWJsaWMtYXBpIiwiaWF0IjoxNzY0MzAxMjM0fQ.hmMxhWnOHF_d7wdEI9vjZcfJFbDPYbKoWGCaqWtDFfI
```

---

## 🛠️ SKILLS STATUS (Current Filesystem)

### Installed User Skills (16 total)
```
/mnt/skills/user/
├── affiliate-hunter-agent (127KB)
├── auto-skill-generator (17KB)
├── browser-automation-superagent (24KB)
├── code-standards-checker (13KB)
├── coven-keeper-agent (68KB)
├── credential-vault-manager (39KB)
├── multi-task-orchestrator (34KB)
├── n8n-master-architect (96KB)
├── seo-llm-optimizer-tests (21KB)
├── site-design-auditor (150KB)
├── witchcraft-substack-voice (11KB)
├── wordpress-accessibility-patterns (23KB)
├── wordpress-blocks (15KB)
├── wordpress-core (15KB)
├── wordpress-empire-system (164KB)
├── wordpress-security-patterns (21KB)
└── zimmwriter-control (73KB)
```

### Skills in GitHub but NOT in Filesystem
These may need to be uploaded:
- creative-command-center (16 DNA files)
- site-build-orchestrator
- claudemd-generator
- design-token-factory
- visual-to-code-pipeline
- email-capture-system
- essential-pages-system
- favicon-logo-system
- mcp-discovery-hub
- smart-operator-core
- self-evolution-engine
- knowledge-accumulator
- enhancement-scout

---

## 📊 PERFORMANCE DATA

### n8n Workflow Success Rates (Post-Fix)
| Workflow | Before | After |
|----------|--------|-------|
| 06 Assembly & Publish | 14% | 100% |
| 03 Section Writer | 67% | 100% |
| 04 Enhancement Engine | 75% | 100% |
| 08 Master Orchestrator | 100% | 100% |
| 05 Image Pipeline v2.1 | 100% | 100% |
| Spirituality Factory | 100% | 100% |
| Smart Home Factory | 50% | 100% |
| Fitness Factory | 100% | 100% |
| Lifestyle Factory | 100% | 100% |
| AI & Tech Factory | 0% | 100% |

### Target Output
- 3 articles/day × 16 sites = 48 articles/day
- Achieved through MASTER Scheduler v4.0
- Sequential processing prevents Cloudflare timeouts

---

## 🚧 ISSUES FIXED

### ✅ SmartHomeWizards CSS Issue
- Status: FIXED
- Was: Homepage CSS not rendering on live site
- Solution: Applied through MCP/API updates

### ✅ AIDiscoveryDigest Automation
- Status: FIXED
- Was: Automation troubles with content generation
- Solution: Factory workflow fixes applied

### ✅ n8n Cloudflare Timeouts
- Status: FIXED
- Cause: Parallel processing overwhelmed n8n Cloud
- Solution: Sequential scheduler with 30s cooldowns

---

## 📁 FILE STRUCTURE CONFIRMED

### Claude Code Projects Structure
```
C:\Claude Code Projects\
├── _MASTER-EMPIRE\
├── skills\
├── automation\
├── schemas\
├── templates\
└── [16 site folders]\
    ├── CLAUDE.md           (~5,700 lines MEGA v3.0)
    ├── auto-start-claude.bat
    ├── .mcp\
    │   └── claude_desktop_config.json
    └── .env.template
```

### Installation Script Created
- INSTALL-TO-EXISTING-STRUCTURE.ps1 (PowerShell)
- INSTALL-FIXED.ps1 (corrected version)
- Maps extracted files to existing folder structure

---

## 🔮 SUBSTACK AUTOMATION (Coven Keeper)

### System Components
1. **witchcraft-substack-voice skill** - Voice profile, content creation
2. **coven-keeper-agent skill** - n8n workflows, automation

### Voice Profile
- Extracted from 150+ real comment/response examples
- 11-lane content rotation system for Notes
- Subscriber relationship tracking (stranger → inner_circle)

### Workflows Created
1. Substack Monitor - Check notifications
2. Response Generator - AI responses in authentic voice
3. Daily Digest - Prioritized engagement emails

---

## ✅ CHECKPOINT 4 COMPLETE
*This checkpoint captures discoveries from Dec 13-15, 2025 conversations*
