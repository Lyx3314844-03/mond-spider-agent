<p align="center">
  <img src="docs/banner.png" alt="Mond Spider Agent" width="100%">
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Frameworks-Go%20%7C%20Python%20%7C%20Java%20%7C%20Rust-7b2fff?style=for-the-badge" alt="Frameworks">
  <img src="https://img.shields.io/badge/AI%20Engines-23%20Subsystems-ff006e?style=for-the-badge" alt="AI Engines">
  <img src="https://img.shields.io/badge/JS%20Reverse-8%20AST%20Passes-00ff88?style=for-the-badge" alt="JS Reverse">
  <img src="https://img.shields.io/badge/Benchmark-23%2F23%20Passed-ffbe0b?style=for-the-badge" alt="Benchmark">
  <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge" alt="License">
</p>

---

## What is Mond Spider Agent?

A **self-evolving AI crawler platform** that orchestrates **4 native frameworks** (Go, Python, Java, Rust) through **23 intelligent subsystems** and a full **JS reverse engineering suite** — capable of defeating obfuscation, tracing encrypted signatures, intercepting runtime crypto, and decompiling WASM modules, all triggered automatically.

```
                    ┌─────────────────────────────────────────┐
                    │         Mond Spider Agent               │
                    │    SuperAgent — 23 AI Subsystems        │
                    └──────────────────────┬──────────────────┘
                                           │
          ┌───────────┬───────────┬────────┼────────┬────────────┬────────────┐
          ▼           ▼           ▼        ▼        ▼            ▼            ▼
      GoSpider    PySpider   JavaSpider RustSpider  Apify   BrowserAgent  JS Reverse
       (Go)      (Python)     (Java)    (Rust)   (Actors)  (Playwright)   (MCP)
```

---

## Why Mond Spider Agent?

### vs. Traditional Crawlers (Scrapy, Puppeteer, Selenium)

| Capability | Traditional | Mond Spider Agent |
|------------|------------|-------------------|
| Multi-framework | Single runtime | 4 native frameworks + Apify actors |
| Anti-bot handling | Manual configuration | Auto-detection + auto-evasion |
| JS reverse engineering | None | 8 AST passes + hook engine + WASM |
| Signature tracing | Manual reverse | Automatic taint + slice analysis |
| Self-improvement | None | 23 AI subsystems with evolution loop |
| Cross-domain learning | None | Automatic strategy transfer |
| Code synthesis | None | LLM generates new crawler modules |
| Knowledge accumulation | Per-session | Persistent graph across all crawls |

### vs. AI Crawlers (Crawl4AI, Firecrawl, Jina)

| Capability | AI Crawlers | Mond Spider Agent |
|------------|------------|-------------------|
| Framework diversity | Usually 1 runtime | Go + Python + Java + Rust |
| Reverse engineering | LLM-only | AST + Hook + Taint + WASM pipeline |
| Obfuscation handling | Prompt-based | 8 deterministic Babel passes |
| Runtime interception | None | 7-category hook engine |
| WASM support | None | Binary parser + decompiler |
| Evolution | Fine-tuning | Genetic algorithm + metacognition |
| Autonomous goals | None | Self-directed exploration |

---

## What Can It Crawl? — Full Target Coverage

### Social Media & Content Platforms

| Platform | What You Get | Key Challenge Solved |
|----------|-------------|---------------------|
| **抖音 / TikTok** | 视频列表、评论、用户资料、直播数据 | X-Bogus / X-Khronos 签名逆向，自动回放 |
| **小红书** | 笔记、评论、用户画像、商品数据 | 加密签名参数追踪 + WASM 模块解析 |
| **快手** | 短视频、直播、电商数据 | X-Sign 自动追踪 + Hook 引擎拦截 |
| **微博** | 帖子、评论、热搜、用户关系 | 反爬绕过 + 翻页自动处理 |
| **Instagram** | 帖子、Story、Reels、评论、粉丝 | GraphQL API 签名绕过 |
| **Twitter / X** | 推文、用户时间线、搜索结果 | API 令牌自动获取 + 速率管理 |
| **YouTube** | 视频元数据、评论、字幕、推荐 | InnerTube API 签名绕过 |
| **Bilibili** | 视频、弹幕、评论、UP 主数据 | Wbi 签名自动生成 |
| **知乎** | 问答、文章、用户、热榜 | 加密 Cookie + 反爬绕过 |
| **LinkedIn** | 职位、公司、个人资料 | 登录态管理 + 反检测浏览器 |

### E-Commerce & Price Intelligence

| Platform | What You Get | Key Challenge Solved |
|----------|-------------|---------------------|
| **淘宝 / 天猫** | 商品详情、价格、评论、店铺数据 | 签名参数 + Token 自动刷新 |
| **京东** | 商品、价格监控、评论分析 | API 签名逆向 + 反爬绕过 |
| **拼多多** | 商品列表、价格、销量 | 加密请求参数追踪 |
| **Amazon** | 商品信息、价格、BSR、评论 | 反机器人检测 + 验证码绕过 |
| **Shopee / Lazada** | 东南亚电商数据 | 多地区 API 签名适配 |
| **Shopify 商店** | 任意 Shopify 店铺数据 | 结构化 API 自动发现 |
| **1688 / Alibaba** | 供应商、批发价格、MOQ | 登录态 + 分页处理 |

### Search Engines & Data Aggregation

| Target | What You Get | Key Challenge Solved |
|--------|-------------|---------------------|
| **Google Search** | 搜索结果、SERP 特征、关键词排名 | 反检测 + 代理轮换 + 验证码处理 |
| **Baidu** | 搜索结果、百科、知道 | JS 渲染 + Cookie 管理 |
| **Bing** | 搜索结果、图片、新闻 | SPA 渲染处理 |
| **Google Maps** | 商家信息、评论、坐标 | 大量分页 + 速率控制 |
| **Google Scholar** | 论文、引用、作者 | 反爬 + 验证码 |
| **App Store / Google Play** | App 排名、评论、下载量 | 结构化数据提取 |

### Protected / Anti-Bot Sites

| Protection System | How It's Defeated |
|-------------------|-------------------|
| **Cloudflare** (Challenge / Turnstile) | CloakBrowser 隐身模式 + 指纹匹配 + 行为模拟 |
| **Akamai Bot Manager** | Hook 引擎拦截传感器数据 + 签名回放 |
| **DataDome** | 自适应浏览器策略 + AI 指纹选择 |
| **PerimeterX / HUMAN** | 行为模拟 + 反检测浏览器 + Cookie 生成 |
| **GeeTest 验证码** | Hook 拦截验证参数 + WASM 分析 |
| **reCAPTCHA v2/v3** | 行为模拟 + 分数优化 + 第三方服务对接 |
| **hCaptcha** | 浏览器指纹 + 行为模式匹配 |
| **自定义 WAF** | ReverseOrchestrator 自动分析 → 选择最优逆向流水线 |

### Enterprise & Structured Data

| Target Type | Examples | Approach |
|------------|----------|----------|
| **REST API** | 任意 RESTful 服务 | 自动发现端点 + 签名回放 + 速率管理 |
| **GraphQL API** | GitHub, Shopify, Medium | Introspection 查询 + 自动字段发现 |
| **WebSocket** | 实时数据流、聊天、股票行情 | WS 协议拦截 + Hook 捕获消息 |
| **gRPC / Protobuf** | 微服务 API | Protobuf 消息自动推断 + 序列化/反序列化 |
| **登录保护站点** | SaaS 后台、会员系统 | Cookie/Token 管理 + 会话保持 |
| **分页 / 无限滚动** | 任意列表页面 | 自动翻页检测 + 滚动模拟 |
| **文件下载** | PDF、Excel、图片、视频 | 多格式解析 + 流式下载 |
| **暗网 / .onion** | Tor 隐藏服务 | SOCKS5 代理 + Tor 网络集成 |

### Specific Data Types You Can Extract

```
文本数据        结构化数据        多媒体          元数据
─────────      ──────────      ──────         ──────
文章/新闻       表格/列表         图片URL          SEO 指标
评论/帖子       价格/库存         视频/音频流       页面性能
用户资料        排名/评分         文件/文档         API 端点
搜索结果        时间序列          直播流           站点地图
翻译内容        关系图谱          截图/快照         技术栈指纹
```

### Real-World Use Cases

| Use Case | How Mond Spider Agent Helps |
|----------|---------------------------|
| **竞品价格监控** | 定时爬取电商平台价格变动，自动绕过反爬，价格异常告警 |
| **舆情分析** | 多平台社交媒体数据采集，评论情感分析，热点追踪 |
| **SEO 排名追踪** | 批量 Google/Bing 搜索结果采集，关键词排名变化监控 |
| **数据标注/AI 训练** | 大规模结构化数据提取，自动清洗，格式标准化输出 |
| **市场研究** | 跨平台商品/服务数据采集，趋势分析，竞品功能对比 |
| **学术研究** | 论文/引用数据采集，学术社交网络分析 |
| **安全审计** | API 签名强度评估，反爬策略有效性测试 |
| **内容聚合** | 多源内容采集、去重、结构化输出到数据库或 API |

---

## Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/Lyx3314844-03/mond-spider-agent.git
cd mond-spider-agent/spider

# 2. Install dependencies
pip install -r requirements.txt
cd js_reverse_mcp && npm install && cd ..

# 3. Configure API key
export OPENAI_API_KEY="sk-xxx"   # or use local model via config/

# 4. Run
python -m mond_agent.super_agent --url "https://target-site.com"

# 5. Run with full reverse engineering pipeline
python -m mond_agent.super_agent --url "https://target-site.com" --reverse auto
```

<details>
<summary>Framework-specific usage</summary>

```bash
# GoSpider — high-throughput crawling
cd gospider && go run main.go --url "https://target-site.com"

# JavaSpider — distributed crawling with Redis scheduler
cd javaspider && mvn exec:java -Dexec.mainClass="com.mond.Spider"

# RustSpider — memory-safe high-performance crawling
cd rustspider && cargo run -- --url "https://target-site.com"

# Apify Cloud Actors
python -m mond_agent.super_agent --url "https://target-site.com" --engine apify
```

</details>

---

## Architecture Overview

### 4 Native Crawler Frameworks

| Framework | Language | Strengths | Key Features |
|-----------|----------|-----------|--------------|
| **GoSpider** | Go | Raw throughput, concurrency | goroutine-based parallelism, low memory, fast startup |
| **PySpider** | Python | Flexibility, ecosystem | Playwright/Scrapling/CloakBrowser, Node.js reverse bridge |
| **JavaSpider** | Java | Enterprise scale | Redis-backed scheduler, distributed worker pool, fault tolerance |
| **RustSpider** | Rust | Safety + speed | Zero-cost abstractions, memory-safe, monitor center + API server |

Each framework runs as an independent subprocess, managed by a unified **Adapter Layer** that handles health checks, process lifecycle, and browser strategy fallback.

### Browser Strategy Fallback

When native crawlers encounter JS-rendered pages, the adapter layer transparently falls back to headless browsers:

| Strategy | Engine | Use Case |
|----------|--------|----------|
| `playwright` | Chromium (Playwright) | General JS rendering, SPA crawling |
| `scrapling` | Scrapling + StealthFetcher | Anti-detection browser automation |
| `cloakbrowser` | CloakBrowser | Heavy anti-bot evasion (Cloudflare, DataDome) |
| `auto` | AI-selected | Picks the best strategy based on site fingerprint |

---

## 23 AI Subsystems

### Core — Crawl Execution & Intelligence

> The foundation that every crawl depends on.

| Engine | What It Does |
|--------|-------------|
| **AgenticLoop** | 6-phase cycle: Plan → Critic → Execute → Self-Heal → Evolve → Reflect |
| **KnowledgeGraph** | Entity-relation graph, cross-crawl knowledge accumulation |
| **SmartCache** | Content fingerprinting + change detection + predictive recrawl |
| **SelectorSynthesis** | Auto-generated CSS/XPath selectors with LLM-assisted repair |
| **AntiDetection** | Fingerprint rotation, human behavior simulation, risk scoring |

### Coordination — Multi-Agent Swarm

> Multiple specialized agents working together.

| Engine | What It Does |
|--------|-------------|
| **MultiAgentCoordinator** | Role-based task distribution across crawl agent swarm |
| **Planner** | Multi-step goal decomposition and task planning |
| **Critic** | Output quality validation and self-critique |
| **RepairAgent** | Automatic failure diagnosis and self-healing |

### Evolution — Self-Improvement

> The system gets smarter over time.

| Engine | What It Does |
|--------|-------------|
| **StrategyEvolution** | Genetic-algorithm driven optimization with A/B testing |
| **ExperienceStore** | Persistent experience database from past crawls |
| **WorldModel** | Causal reasoning about site architecture, anti-bot, API conventions |
| **CuriosityEngine** | Proactive exploration of unknown sites for new patterns |
| **TransferLearning** | Cross-domain strategy migration via fingerprint similarity |
| **DeepMetacognition** | Capability gap analysis, learning plateau detection |
| **AutonomousGoalSetter** | Self-directed goal generation for recursive improvement |
| **FreeCodeSynthesis** | LLM-driven Python module generation with AST validation + sandbox |

### Reverse Engineering — JS Anti-Bot Defeat

> Automatically triggered when crawl encounters protection.

| Engine | What It Does |
|--------|-------------|
| **ASTDeobfuscator** | 8 Babel AST passes to deobfuscate JS |
| **HookEngine** | 7-category runtime interception (crypto/network/storage/random/time/DOM/WASM) |
| **SignatureTracer** | Taint analysis + program slicing → auto Python replay |
| **WasmReverse** | Pure-Python WASM binary parser + decompiler + JS wrapper gen |
| **ReverseOrchestrator** | Unified dispatcher selecting optimal reverse pipeline |

### Integration

| Engine | What It Does |
|--------|-------------|
| **MondAgent API** | High-level API for external integration and orchestration |

---

## Super Run: The Intelligent Crawl Pipeline

`SuperAgent.super_run(url)` executes the full 8-stage pipeline:

```
Step 1: SmartCache Lookup          → Cache hit? Return cached result
Step 2: StrategyEvolution           → Best strategy from genetic algorithm
Step 3: WorldModel Prediction       → Predict anti-bot, rendering mode, rate limits
Step 4: TransferLearning            → Reuse strategies from similar domains
Step 5: AntiDetection               → Rotate fingerprint, inject human behavior
Step 6: AgenticLoop Execution       → Plan → Critic → Execute → Self-Heal → Evolve → Reflect
        ├── 6a: Failure?            → RepairAgent auto-diagnosis
        ├── 6b: Still failing?      → MultiAgentCoordinator swarm fallback
        └── 6c: 403/Blocked?        → ReverseOrchestrator auto-trigger
Step 7: KnowledgeGraph Update       → Extract entities, update cross-crawl knowledge
Step 8: Strategy Fitness + Evolution → Score performance, trigger genetic evolution
```

---

## Self-Evolution Loop

Mond Spider Agent is not just a crawler — it is a **self-improving system**:

```
┌──────────────────────────────────────────────────────────┐
│                 AutonomousGoalSetter                      │
│  Discovers capability gaps → generates exploration goals  │
└──────────────┬────────────────────────────┬──────────────┘
               │ proactive goals             │ passive tasks
               ▼                            ▼
┌────────────────────────┐     ┌──────────────────────────┐
│    CuriosityEngine     │     │      AgenticLoop         │
│  Explores unknown sites│     │  Plan→Critic→Execute→    │
│                        │     │  SelfHeal→Evolve→Reflect │
└────────────┬───────────┘     └────────────┬─────────────┘
             │ exploration results           │ task results
             ▼                              ▼
┌──────────────────────────────────────────────────────────┐
│                     WorldModel                            │
│  Causal model: site architecture, anti-bot, API          │
│  conventions, rate-limit behavior                        │
└──────────────┬────────────────────────────┬──────────────┘
               │ causal predictions          │ domain model
               ▼                            ▼
┌──────────────────────────┐   ┌────────────────────────────┐
│   TransferLearning       │   │   DeepMetacognition         │
│  Cross-domain migration  │   │  "Why can't I learn X?"    │
└──────────────────────────┘   └────────────────────────────┘
               │                            │
               ▼                            ▼
┌──────────────────────────┐   ┌────────────────────────────┐
│  FreeCodeSynthesis       │   │  Feedback → GoalSetter     │
│  LLM generates new       │   │  (recursive improvement)   │
│  crawler modules         │   │                            │
└──────────────────────────┘   └────────────────────────────┘
```

---

## Reverse Engineering — Deep Dive

### ASTDeobfuscator: 8 Babel Passes

| Pass | Technique | What It Solves |
|------|-----------|----------------|
| **String Concat** | `"a" + "b"` → `"ab"` | String splitting obfuscation |
| **Boolean If** | `if(true){...}` → `{...}` | Dead conditional branches |
| **Constant Fold** | `0xa + 0xb` → `21`, `!![]` → `true` | Constant expression obfuscation |
| **String Array** | `_0xabc[0x12]` → literal string | obfuscator.io string array encoding |
| **Dead Code** | Remove unreachable branches | `if(false){...}` and dead paths |
| **Identifier Rename** | `_0x1a2b3c` → semantic names | Hex-encoded identifier renaming |
| **Control Flow** | Flatten `switch` state machines | Control flow flattening |
| **Anti-Debug** | Strip `debugger` statements | Anti-debugging traps |

**Obfuscator Fingerprints Detected**: obfuscator.io, javascript-obfuscator, sojson, jsjiami, packer, and 7 more.

### HookEngine: Runtime Interception

| Category | Intercepted APIs | Intelligence |
|----------|-----------------|--------------|
| **Crypto** | `crypto.subtle.*`, `CryptoJS.*`, `forge.*` | Algorithm, key material, IV/nonce |
| **Network** | `fetch`, `XMLHttpRequest`, `axios` | Signature param locations, header injection |
| **Storage** | `localStorage`, `sessionStorage`, `cookie` | Token/state source identification |
| **Random** | `Math.random`, `crypto.getRandomValues` | Random seed tracing |
| **Time** | `Date.now`, `performance.now` | Timestamp dependency mapping |
| **DOM** | `document.querySelector*`, `getElementById` | DOM-dependent logic identification |
| **WASM** | `WebAssembly.instantiate*` | Automatic WASM module capture |

### SignatureTracer: 5-Stage Pipeline

```
1. Hook Point Identification    →  Find fetch()/XHR/axios call sites
2. Parameter Slicing            →  Backward slice from target param
3. Taint Analysis               →  Trace data flow to sink
4. Generation Function Extract  →  Isolate signing function
5. Python Translation           →  LLM-assisted JS→Python with verification
```

**Supported**: X-Sign, X-Bogus, X-Khronos, X-Gorgon, X-Helios, X-Ladon, X-Argus, sign, signature, token, and arbitrary custom parameters.

### WasmReverse: WebAssembly Analysis

| Capability | Description |
|------------|-------------|
| **Binary Parsing** | LEB128 decoding, full section parsing |
| **Export Analysis** | Exported functions with type signatures |
| **String Extraction** | String literal recovery from data sections |
| **Signature Detection** | Crypto/signature function heuristics |
| **JS Wrapper Gen** | JavaScript glue code for Node.js WASM calls |

### ReverseOrchestrator: Unified Pipeline

```
Page Analysis → Obfuscator Detection → Anti-Bot Classification
                    │                          │
                    ▼                          ▼
            ┌───────────────┐          ┌───────────────┐
            │ obfuscator.io │          │   Cloudflare  │
            │ js-obfuscator │          │   Akamai      │
            │ sojson        │          │   DataDome    │
            └───────┬───────┘          └───────┬───────┘
                    │                          │
                    ▼                          ▼
         ASTDeobfuscator              HookEngine + Runtime
         (8 Babel passes)             Interception
                    │                          │
                    └──────────┬───────────────┘
                               ▼
                    SignatureTracer
                    (taint + slice → Python replay)
                               │
                               ▼
                    FreeCodeSynthesis
                    (register replay module for reuse)
```

---

## Benchmark — 23/23 Passed

| Test Suite | Tests | Status |
|------------|-------|--------|
| **ASTDeobfuscator** | string concat, boolean if, constant fold, string array, dead code, identifier rename, control flow, anti-debug | **8/8** |
| **HookEngine** | profile build, crypto, network, events, trace export, script gen, category filter, stack trace, context metadata, multi-category | **10/10** |
| **SignatureTracer** | MD5 header, SHA256 query, HMAC body | **3/3** |
| **WasmReverse** | export analysis (3 modules), string extraction, JS wrapper gen | **5/5** |

| Component | Check | Result |
|-----------|-------|--------|
| Go (gospider) | `go vet ./...` | Clean |
| Java (javaspider) | `mvn compile` | Clean |
| Rust (rustspider) | `cargo check` | Clean |
| Python (all modules) | 32/32 imports | Clean |

---

## Technology Stack

| Layer | Technologies |
|-------|-------------|
| **Crawler Frameworks** | Go, Python, Java, Rust |
| **AI / LLM** | OpenAI API, local model support, LLM-driven code synthesis |
| **Browser Automation** | Playwright, Scrapling, CloakBrowser |
| **JS Reverse Engineering** | Babel AST, Node.js bridge |
| **WASM Analysis** | Pure-Python binary parser with LEB128 decoding |
| **Anti-Detection** | Fingerprint rotation, human behavior simulation, proxy |
| **Knowledge Systems** | Entity-relation graph, experience store, cross-domain transfer |
| **Evolution** | Genetic algorithm, fitness scoring, A/B testing, autonomous goals |
| **Deployment** | Docker, Kubernetes, standalone, Apify cloud actors |

---

## Project Structure

```
spider/
├── mond_agent/                    # ← AI SuperAgent — the brain
│   ├── super_agent.py             #   Entry point: super_run() orchestrates everything
│   ├── agentic_loop.py            #   Core execution cycle
│   ├── knowledge_graph.py         #   Cross-crawl knowledge
│   ├── smart_cache.py             #   Intelligent caching
│   ├── multi_agent.py             #   Swarm coordination
│   ├── anti_detection.py          #   Fingerprint + behavior
│   ├── selector_synthesis.py      #   Auto CSS/XPath
│   ├── strategy_evolution.py      #   Genetic algorithm
│   ├── world_model.py             #   Causal site modeling
│   ├── curiosity_engine.py        #   Proactive exploration
│   ├── transfer_learning.py       #   Cross-domain migration
│   ├── free_code_synthesis.py     #   LLM code generation
│   ├── deep_metacognition.py      #   Self-analysis
│   ├── autonomous_goals.py        #   Self-directed goals
│   └── adapters/                  #   ← calls the 4 frameworks below
│       ├── go_adapter.py          #     ──→ gospider/
│       ├── py_adapter.py          #     ──→ pyspider/
│       ├── java_adapter.py        #     ──→ javaspider/
│       ├── rust_adapter.py        #     ──→ rustspider/
│       └── apify_adapter.py       #     ──→ Apify cloud
│
├── js_reverse_mcp/                # ← JS Reverse Engineering — triggered by adapters
│   ├── ast_deobfuscator.py        #   8 Babel AST passes
│   ├── hook_engine.py             #   Runtime JS hook injection
│   ├── signature_tracer.py        #   Taint + slice tracing
│   ├── wasm_reverse.py            #   WASM binary analysis
│   ├── orchestrator.py            #   ← called by mond_agent when 403/blocked
│   └── benchmark/                 #   23 benchmark tests
│
├── gospider/                      # Go crawler (called by go_adapter)
├── pyspider/                      # Python crawler (called by py_adapter)
│   └── node_reverse/              #   Node.js reverse bridge
├── javaspider/                    # Java crawler (called by java_adapter)
├── rustspider/                    # Rust crawler (called by rust_adapter)
│
├── config/                        # API keys, engine selection, browser strategy
├── deploy/                        # Docker, K8s, Apify deployment configs
├── examples/                      # Usage examples and presets
└── docs/                          # Documentation and assets
```

**Call flow**: `super_agent.py` → `adapters/` → framework subprocess → on 403/blocked → `js_reverse_mcp/orchestrator.py` → reverse pipeline → `free_code_synthesis.py` (generate replay module)

---

## Contact / 联系方式

<p align="center">
  <img src="https://img.shields.io/badge/WeChat-3314844-07C160?style=for-the-badge&logo=wechat&logoColor=white" alt="WeChat">
  <img src="https://img.shields.io/badge/GitHub-Lyx3314844--03-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</p>

<table align="center">
<tr>
<td align="center">

**微信 WeChat**: `3314844`

</td>
</tr>
</table>

---

## License

MIT License. See [LICENSE](LICENSE) for details.

---

<p align="center">
  <sub>Built with Go, Python, Java, Rust, Node.js, Babel, Playwright, and a lot of AI.</sub>
</p>
