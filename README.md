# Awesome Taiwan MCP 🇹🇼

讓 AI 助理（Claude、ChatGPT、Cursor…）懂台灣的 MCP 伺服器清單：法律、健保、假日、交通、台股、天氣。
*A curated list of MCP servers for Taiwan-specific data.*

**標記說明 / Legend**

| 標記 | 意思 |
|---|---|
| ☁️ 遠端 | 有公開網址，貼上就能用，不用裝東西 / hosted URL, nothing to install |
| 🏠 本機 | 要在自己電腦上用 `npx` / `uvx` / Docker 跑 / runs locally |
| 🔓 免金鑰 | 不用申請帳號或 API key / no key needed |
| 🔑 需金鑰 | 要自己去申請 API key（通常免費） / bring your own key |
| 🔐 OAuth | 連線時自動授權，不用自己申請 key / auto OAuth sign-in |

同一分類內依名稱字母排序，不代表推薦順序。
*Entries are alphabetical within each category; order is not a ranking.*

> 連結於 2026-11-04 檢查。

## 目錄
- [法律 Law](#法律-law)
- [醫療與健保 Health](#醫療與健保-health)
- [生活：假日、發票、彩券 Daily life](#生活假日發票彩券-daily-life)
- [求職 Jobs](#求職-jobs)
- [交通 Transport](#交通-transport)
- [台股與財經 Stocks & finance](#台股與財經-stocks--finance)
- [公司與政府採購 Business & procurement](#公司與政府採購-business--procurement)
- [天氣 Weather](#天氣-weather)
- [教育 Education](#教育-education)
- [綜合開放資料 Multi-domain open data](#綜合開放資料-multi-domain-open-data)

---

## 法律 Law

- [aa0101181514/tw-legal-rag](https://github.com/aa0101181514/tw-legal-rag) ☁️ 🏠 🔐 — 2,270 萬筆裁判書、函釋、憲法法庭裁判的語意搜尋，附引用查核；遠端連線走自動 OAuth，免申請 key。
  *Semantic search over 22M+ Taiwan court rulings with citation checking; remote `https://tlr.dr-legal.com.tw/mcp`.*
- [aa0101181514/tw-patent-mcp](https://github.com/aa0101181514/tw-patent-mcp) 🏠 — 查詢智慧財產局 GPSS 與歐洲專利局專利資料，使用 `uvx`。
  *Search TIPO GPSS and EPO patents with `uvx`.*
- [law24tw/tw-legal-calc](https://github.com/law24tw/tw-legal-calc) 🏠 🔓 — 提供利息、資遣費、特休等 20 種法律試算。
  *Twenty legal calculators covering interest, severance and annual leave.*
- [lawchat-oss/mcp-taiwan-legal-db](https://github.com/lawchat-oss/mcp-taiwan-legal-db) 🏠 🔓 — 查司法院判決和全國法規資料庫。
  *Judicial Yuan rulings + national law database.*
- [legaltechtw/taiwan-law-mcp](https://github.com/legaltechtw/taiwan-law-mcp) ☁️ 🏠 🔓 — 查證法規、裁判、釋憲和立法歷程，有公開遠端網址。
  *Laws, rulings, constitutional interpretations and legislative history; remote `https://legaltech.org.tw/mcp`.*

- [pass-and-prosper/twlawexam-mcp](https://github.com/pass-and-prosper/twlawexam-mcp) 🏠 — 查詢律師與司法官考古題 1,940 題，使用 `uvx`。
  *Search 1,940 past bar and judicial examination questions with `uvx`.*
- [RegAI-tw/regai-legal-mcp](https://github.com/RegAI-tw/regai-legal-mcp) ☁️ 🔑 — 唯讀查詢法規條文與裁判。
  *Read-only legal provisions and court rulings; remote `https://mcp.regai.tw/mcp`.*

## 醫療與健保 Health

- [healthymind-tech/Taiwan-Health-MCP](https://github.com/healthymind-tech/Taiwan-Health-MCP) 🏠 🔓 — ICD-10、SNOMED CT、LOINC、TFDA 藥品、FHIR TW Core 驗證、臨床計算。
  *Taiwan medical coding, TFDA drugs and FHIR TW Core (public remote endpoint currently down).*
- [masalu0105-gif/taiwan-laboratory-mcp](https://github.com/masalu0105-gif/taiwan-laboratory-mcp) ☁️ 🏠 — 查詢疾管署檢體送驗規定與檢驗醫學開放資料。
  *Taiwan CDC specimen submission rules and laboratory medicine open data; remote `https://lab.masalulab.com/mcp`.*
- [minhsuan0/taiwan-pt-mcp](https://github.com/minhsuan0/taiwan-pt-mcp) 🏠 🔓 — 查證物理治療實證、臨床指引與台灣相關法規，使用 `npx taiwan-pt-mcp`。
  *Physical therapy evidence, clinical guidelines and Taiwan regulations; run `npx taiwan-pt-mcp`.*
- [shin13/opentaimed](https://github.com/shin13/opentaimed) 🏠 — 查詢食藥署藥品資訊，使用 `uvx taiwan-fda-mcp`。
  *TFDA drug information; run `uvx taiwan-fda-mcp`.*
- [tatsuju/opdstar-nhi-mcp](https://github.com/tatsuju/opdstar-nhi-mcp) ☁️ — 健保核刪代碼、ICD-10 對應處置、審查指標與健保文件搜尋。
  *Taiwan NHI rejection codes, ICD-10 mappings and audit indicators.*

- [trionnemesis/healthcare-opendata-mcp](https://github.com/trionnemesis/healthcare-opendata-mcp) 🏠 — 將政府採購與健保開放資料存入 SQLite 查詢。
  *Query government procurement and NHI open data stored in SQLite.*

## 生活：假日、發票、彩券 Daily life

- [coseto6125/mcp-taiwan-price-compare](https://github.com/coseto6125/mcp-taiwan-price-compare) 🏠 — 比較 Coupang、momo 與 PChome 商品價格。
  *Compare prices across Coupang, momo and PChome.*
- [imsyuan/taiwan-holidays](https://github.com/imsyuan/taiwan-holidays) ☁️ 🏠 — 計算上班日、補班與連假，並規劃請假。
  *Calculate working days and optimize leave around holidays and make-up workdays; remote `https://mcp.tw-holidays.gooliya.com/mcp`.*
- [Life Info MCP](https://mcprush.com/panda198271/life-info-mcp) ☁️ 🔓 — 連假與補班、彩券開獎與對獎、統一發票。沒有公開原始碼。
  *Holidays, lottery results and receipt lottery; remote `https://tw-life-info.panda198271.workers.dev/mcp` (no public source).*
- [lis186/taiwan-holiday-mcp](https://github.com/lis186/taiwan-holiday-mcp) 🏠 🔓 — 國定假日、補班日、颱風假停班停課查詢。`npx`
  *Holidays, make-up workdays and typhoon day-off status.*
- [mdata-group/invoice-mcp](https://github.com/mdata-group/invoice-mcp) ☁️ 🔑 — 查詢自己的電子發票，需有發票存摺帳號。
  *Query your e-invoices; needs a 發票存摺 e-invoice passbook account; remote `https://mdata-mcp.invos.com.tw/invoice/mcp`.*
- [panda2143/taiwan-mcp-tools](https://github.com/panda2143/taiwan-mcp-tools) ☁️ 🔓 — 小型繁中資料集工具：2027 連假、機車規格、AI 名詞等。
  *Small zh-TW datasets (2027 holidays, scooter specs, AI glossary); remote `https://penguindriver.com/mcp`.*
- [ycsmiley/formosa-mcp](https://github.com/ycsmiley/formosa-mcp) ☁️ 🏠 🔓 — 統一發票對獎、台股上市＋上櫃盤後行情、新北／臺北／臺中垃圾車時刻、計畫性停水停電、高鐵／台鐵時刻表與臺鐵即時資料；遠端網址免金鑰，本機版 `npx -y formosa-mcp`，本機鐵路須自備 TDX 金鑰。揭露：作者本人
  *Receipt lottery checking, TWSE/TPEx after-hours quotes, garbage truck schedules in New Taipei, Taipei and Taichung, planned water and power outages, THSR/TRA timetables and real-time TRA data; keyless remote `https://formosa-mcp.ycsmiley.workers.dev/mcp`, local `npx -y formosa-mcp`, and local rail requires a TDX key.*

## 求職 Jobs

- [a7512cs/104-mcp-server](https://github.com/a7512cs/104-mcp-server) 🏠 — 非官方 104 人力銀行職缺與公司搜尋，使用 `npx -y mcp-server-104`。
  *Unofficial 104 job and company search; run `npx -y mcp-server-104`.*
- [HsuanC0921/tw-jobs-mcp](https://github.com/HsuanC0921/tw-jobs-mcp) 🏠 — 唯讀查詢 104 職缺、公司與薪資，使用 `uvx tw-jobs-mcp`。
  *Read-only 104 job, company and salary search; run `uvx tw-jobs-mcp`.*

## 交通 Transport

- [amangeldievkuu/tdx-taiwan-mcp](https://github.com/amangeldievkuu/tdx-taiwan-mcp) 🏠 🔑 — 非官方 TDX：YouBike、公車到站等，需自備 TDX Client ID/Secret。
  *Unofficial TDX server (YouBike, bus); bring your own TDX keys.*
- [physictim/thsrc_mcp](https://github.com/physictim/thsrc_mcp) 🏠 — 高鐵查詢小工具（2025-08 後未更新）。
  *Small THSR lookup tool (not updated since Aug 2025).*
- [tdx-mcp（npm）](https://www.npmjs.com/package/tdx-mcp) 🏠 🔑 — 台鐵、高鐵車站、即時看板與每日時刻表，需 TDX 金鑰。
  *TRA/THSR stations, live boards and timetables; needs TDX keys.*
- [tdxmotc/MCP](https://github.com/tdxmotc/MCP) ☁️ 🔑 — 交通部 TDX 官方 MCP，資料最完整；需 TDX 會員金鑰。
  *Official MCP from Taiwan's MOTC TDX platform; needs a TDX member key.*

## 台股與財經 Stocks & finance

- [amplify-lab/summa-tw-accounting](https://github.com/amplify-lab/summa-tw-accounting) ☁️ — 台灣會計、稅務、薪資問答助手。
  *Taiwan accounting, tax and payroll assistant; remote `https://mcp.summa.com.tw/mcp`.*
- [asgard-ai-platform/mcp-tdcc](https://github.com/asgard-ai-platform/mcp-tdcc) 🏠 — 提供 8 個工具查詢集保結算所開放資料。
  *Eight tools for Taiwan Depository & Clearing Corporation open data.*
- [gentoobreaking/tw-quant-mcp](https://github.com/gentoobreaking/tw-quant-mcp) 🏠 — 量化用：盤中 1 分 K、盤後籌碼、基本面、期權，資料來自 TWSE/TPEx/MOPS。
  *Intraday 1-min bars, chips, fundamentals and options for quant work (Go).*
- [hulan-bebe/taiwan-stock-mcp](https://github.com/hulan-bebe/taiwan-stock-mcp) 🏠 🔓 — 用英文查台股官方資料，`uvx taiwan-stock-mcp`。
  *English access to official Taiwan stock data, no key.*
- [pipeworx-io/mcp-taiwan-stocks](https://github.com/pipeworx-io/mcp-taiwan-stocks) ☁️ 🔓 — 台股行情，免金鑰。
  *Keyless Taiwan equities; remote via `https://gateway.pipeworx.io/mcp`.*
- [SmartyJohnway/tw-market-live-data-intelligence](https://github.com/SmartyJohnway/tw-market-live-data-intelligence) 🏠 — 本機台股觀察清單與可追溯的資料查詢。
  *Local-first TWSE/TPEx evidence workbench with watchlists.*
- [supra126/taiwan-payroll](https://github.com/supra126/taiwan-payroll) 🏠 🔓 — 勞健保、勞退、二代健保補充保費、扣繳稅額計算。
  *Taiwan statutory payroll calculations.*
- [taux-io/twse-mcp](https://github.com/taux-io/twse-mcp) ☁️ 🔓 — 證交所開放資料：個股、ETF、140+ 資料集。
  *TWSE open data: quotes, ETFs, 140+ datasets; remote `https://twse-mcp.taux.io/mcp`.*
- [TW-Market-Data/tw-market-data-mcp](https://github.com/TW-Market-Data/tw-market-data-mcp) ☁️ 🔑 — 台股上市櫃行情託管服務，repo 只有文件。
  *Hosted TWSE and TPEx market data; remote `https://mcp.twmarketdata.com/mcp`.*
- [twjackysu/TWSEMCPServer](https://github.com/twjackysu/TWSEMCPServer) ☁️ 🏠 🔓 — 整合證交所、櫃買中心、期交所 OpenAPI 與部分即時報價。
  *TWSE, TPEx and TAIFEX OpenAPI data plus some real-time quotes; remote `https://TW-Stock-MCP-Server.fastmcp.app/mcp`.*
- [ycsmiley/formosa-mcp](https://github.com/ycsmiley/formosa-mcp) ☁️ 🏠 🔓 — 見上方「生活」分類（同一個伺服器）。揭露：作者本人
  *See Daily life above (same server).*

## 公司與政府採購 Business & procurement

- [h30190/SearchProcurementTenders-crawler.Ver](https://github.com/h30190/SearchProcurementTenders-crawler.Ver) 🏠 — 以爬蟲直接查詢政府電子採購網標案（2026-02 後未更新）。
  *Crawls Taiwan's government e-procurement site for tenders (not updated since Feb 2026).*
- [pipeworx-io/mcp-taiwan-companies](https://github.com/pipeworx-io/mcp-taiwan-companies) ☁️ 🔓 — 查詢經濟部公司登記資料，包括統一編號與資本額。
  *Ministry of Economic Affairs company registration data, including business IDs and capital; remote `https://gateway.pipeworx.io/taiwan-companies/mcp`.*
- [pipeworx-io/mcp-taiwan-procurement](https://github.com/pipeworx-io/mcp-taiwan-procurement) ☁️ 🔓 — 查詢政府電子採購網標案。
  *Search government e-procurement tenders; remote `https://gateway.pipeworx.io/taiwan-procurement/mcp`.*
- [trionnemesis/g0VMCP](https://github.com/trionnemesis/g0VMCP) 🏠 — 搜尋政府採購標案並分析時間軸。
  *Search government procurement tenders and analyze timelines.*

## 天氣 Weather

- [gary2376/cwa-mcp-server](https://github.com/gary2376/cwa-mcp-server) 🏠 🔑 — 中央氣象署資料，需自備 CWA 授權碼，`uvx`。
  *CWA weather data; bring your own CWA key.*
- 另見下方 [dragonheart8787/opendata-mcp](#綜合開放資料-multi-domain-open-data)（天氣、地震、空品）。

## 教育 Education

- [yyu0310/nccu-course-mcp](https://github.com/yyu0310/nccu-course-mcp) 🏠 — 查詢政治大學課程。
  *Search National Chengchi University courses.*

## 綜合開放資料 Multi-domain open data

- [dragonheart8787/opendata-mcp](https://github.com/dragonheart8787/opendata-mcp) ☁️ 🔓 — 一個網址查天氣、地震、空品、交通；公開 demo 服務，作者建議長期使用要自架並自備金鑰。
  *Weather, quakes, air quality and transport in one gateway; public demo at `https://opendata-mcp.dragonheartliu1440.workers.dev/mcp`.*
- [funtuan/mcp-server-taiwan-gov-data](https://github.com/funtuan/mcp-server-taiwan-gov-data) ☁️ 🔓 — 搜尋政府資料開放平臺資料集（SSE 連線）。
  *Search data.gov.tw datasets; remote SSE `https://tw-gov-data-mcp.funtuan.workers.dev/sse`.*
- [kewelin/taiwan-data-mcp](https://github.com/kewelin/taiwan-data-mcp) 🏠 🔓 — 查詢實價登錄、公司與 165 反詐騙資料，使用 `npx -y taiwan-data-mcp`。
  *Property transactions, company information and 165 anti-fraud data; run `npx -y taiwan-data-mcp`.*
- [MackinHung/taiwan-mcp-platform](https://github.com/MackinHung/taiwan-mcp-platform) 🏠 — 39 個政府資料 MCP 伺服器的集合與市集。
  *Marketplace of 39 Taiwan government-data MCP servers.*

---

## 收錄標準 Inclusion criteria

1. **跟台灣有關**：資料或用途以台灣為主（不收「通達信 TDX」等同名但無關的工具）。
2. **連得上**：GitHub repo 或遠端網址要能打開；壞掉 30 天會移除。
3. **有說明**：README 至少寫清楚怎麼安裝或連線、要不要金鑰。
4. **沒封存**：已 archived 的 repo 不收；超過一年沒更新會加註。
5. **誠實標示**：遠端／本機、要不要金鑰都要標對；沒有公開原始碼的服務要註明。
6. **資料來源合法**：使用政府開放資料的，應依授權標示來源（例如「資料來源：交通部中央氣象署」）。

*Taiwan-focused, reachable, documented, not archived, honestly labelled, and properly attributed.*

## 怎麼貢獻 Contributing

1. 開一個 Pull Request，在對的分類裡**依字母順序**加一行。
2. 格式：`- [擁有者/名稱](連結) 標記 — 一句中文說明。` 下一行用斜體寫一句英文。
3. 遠端服務請把網址寫在英文那行，用反引號包起來。
4. 如果是你自己的專案，請在說明加上「揭露：作者本人」。
5. 一個 PR 只加一個項目，方便審查。

發現連結壞掉、標記錯誤？直接開 Issue 就好。

## 授權 License

[CC0 1.0](https://creativecommons.org/publicdomain/zero/1.0/)
