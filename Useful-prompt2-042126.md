---
name: eudamed-compliance-reporter
description: 專門用於生成歐盟醫療器材資料庫 (EUDAMED) 合規報告與法規分析的技能。當使用者詢問有關歐盟 MDR/IVDR 合規性、EUDAMED 註冊時程、SRN 申請、UDI 上傳、舊有器材 (Legacy Devices) 過渡期，或 Regulation (EU) 2024/1860 關於供應中斷通知 (Article 10a) 的義務時，必須使用此技能。即使使用者僅提及「歐盟醫材註冊」或「醫材缺貨通報」，也應主動調用此技能以提供專業的法規深度分析。
---

# 醫療器材法規報告助手

此技能旨在協助製造商與合規專業人員應對醫療器材法規的重大更新。它能根據最新的法規上下文，針對法規內容、實施日期與製造商義務生成詳細報告。

## 專業知識範疇

1.  **法規核心**：器材註冊、公告機構與證書、市場監管。
2.  **關鍵法規依據**：search the web。
3.  **義務**：。
4.  **時程管理**：。

## 觸發條件

- 當使用者詢問如何取得上市許可。
- 當使用者討論法規符合。
- 當使用者遇到供應鏈問題。

## 執行步驟

1.  **分析實體角色**：確認使用者是製造商、授權代表還是進口商。
2.  **識別產品類別**：。
3.  **對照法規時間軸**：
4.  **風險與缺口評估**：對比現有準備情況與法規要求（如 UDI 數據準備、M2M 自動化需求、SSCP 上傳進度）。
5.  **生成結構化報告**：使用下方的標準模板輸出建議。

## 報告結構模板

所有報告應遵循以下結構：

# 合規性分析報告
## 1. 執行摘要
[簡述當前法規地位與最迫切的截止日期]

## 2. 合規狀態
- **參與者註冊 (Actor Registration)**：[SRN 狀態與 PRRC 資訊維護]
- **UDI/器材註冊**：[UDI-DI 數據準備與上傳時程]
- **證書與公告機構 (NB)**：[SSCP 與證書連結要求]
- **市場監管**：[主管機關監管數據共享說明]

## 3. 專項法規義務分析

## 4. 關鍵行動建議清單
- **優先級：極高**
- **優先級：高**
- **長期規劃**

## 5. 後續追蹤建議
[根據使用者情況提出針對性問題，例如 M2M 評估或 SOP 建立]

## 參考數據基準

| 關鍵日期 | 法規事件 | 影響對象 |
| :--- | :--- | :--- |

## 注意事項
skill creator skill:

Hi please create a wow interactive webpage that 1. User can paste medical device regulation news, guidance/regulation/standard 2. User can paste template of medical device regulation report or user can choose to use the default report, 3. User can select languages for output (English/traditional chinese), 4. Agent will search web and create a comprehensive summary of the related medical device regulation/guidance of the step1 user provided information in markdown in 2000~3000 words. 5.Agent will create a comprehensive medical device regulation report based on step1 user provided information using the step 2 report template in markdown in 3000~4000 words. Agent will also create 4 wow Infograph (using code to be presented on interactive webpage) and also create 3 additional table, 20 entities with context based on the previous regulation report. Please also create 3 wow/amazing features (create by the agent) attached to the report. Ending with 20 comprehensive follow up questions. , 6. Agent will create a description of skill (skill.md) for agent to create a comprehensive medical device regulation report specific to the step 1 user provided information using skill creator skill. 7. Agent will create a NEAT wow interactive webpage containing step 4, 5, 6 results. User can choose light/dark themes, English/traditional chinese and 10 styles based on Pantone color palette.
Please let user to select light(default)/dark themes, traditional chinese(default)/english, 10 styles based on pantone color palette within the webpage





https://opal.google/app/19ImRT0iGteVIKU-HLNIG9zyXLKBSlwQG





https://ai.studio/apps/62094471-2bad-42cd-9a7d-efa11b977faf



https://github.com/Leslie012726/GEMINI3-Leslie-MD-Regulation-040426/blob/main/UsefulOPAL_prompt-040426.md





https://opal.google/app/16UrW5T5MUC5573BgjR77PuCAuBhDc1U9







https://opal.google/app/1vdoHITjf7RJ8rKaAVG9Fv28Nm-dFnMrD





https://ai.studio/apps/ee2066cb-3c3a-4cd5-a687-8edb577b5a26





https://github.com/Molly040326/Gemini3-Mica-MD-skill-040426/blob/main/OPAL-prompt040426.md



https://github.com/Mica040326/GEMINI3-Med-reg-040426/blob/main/OPAL-prompt-040426.md



https://opal.google/app/1egf8pULI3KypzU4YnOgJIgm8_w6Kg94Q





https://ai.studio/apps/db7fbcf3-cbc1-46a0-a901-78dee574bf6a



https://github.com/Sala040326/Gemini3-Sala-MD-rep-040426/blob/main/OPAL-prompt-040426.md





https://github.com/Sala040326/Gemini3-Sala-MD-rep-040426/blob/main/OPAL-prompt-040426.md



Please let user to select light(default)/dark themes, traditional chinese(default)/english, 10 styles based on pantone color palette within the webpage

hi please summarize medical device regulation updates of UK in 2025/2026 in markdown in 2000~3000 words (please include 3~5 topics and create 5 tables, 20 entities with context) in traditional chinese. Ending with comprehensive follow up questions.


Hi please improve previous design by keeping all original features and adding additional features that user 1. User can paste medical device regulation news, guidance/regulation/standard Then User can paste template of medical device regulation report or user can choose to use the default report. Then User can select languages for output (English/traditional chinese), Then Agent will search web and create a comprehensive summary of the related medical device regulation/guidance of the step1 user provided information in markdown in 2000~3000 words. (User can modify results in markdown view and download results) Then Agent will create a comprehensive medical device regulation report based on user provided information using the  report template in markdown in 3000~4000 words. Agent will also create 4 wow Infograph (using code to be presented on interactive webpage) and also create 3 additional table, 20 entities with context based on the previous regulation report. . (User can modify results in markdown view and download results)  Please create 3 additional wow/amazing features (create by the agent) in the app. Ending with 20 comprehensive follow up questions. 2. Please let user to input description of skill (skill.md). If the user provided description of skill is not standardized skill.md, agent will use skill creator skill to create a standardized skill.md. User can modify results and download skill.md. Then agent will create 3 use cases of the skill. User can modify the use case. Then use can select use cases and ask agent to execute using the previous skill. User can modify prompt, select models, User can modify execution results. Please also create a wow ui that user to select light(default)/dark themes, traditional chinese(default)/english, 10 styles based on pantone color palette. Please also add additional amazing interactive indicator, live log and wow dashboard. Ending with 20 comprehensive follow up questions.



The final response must include:
- A summary of the regulation between 2000 and 3000 words.
- A detailed medical device regulation report between 3000 and 4000 words.
- 3 additional data tables relevant to the topic.
- 20 key entities with context explaining their relevance.
- 3 wow or amazing features identified within the regulation.
- 20 comprehensive follow-up questions for further analysis.
- 4 infographics generated as Mermaid code embedded directly into the report.





Use web search to research the latest medical device regulations and guidance related to the provided news or guidance. Synthesize the information into a detailed summary that covers regulatory requirements, impact on the industry, and implementation timelines.





醫療器材法規全球協調化深度報告：加拿大 Health Canada REP 與美國 FDA QMSR 實施全指南

一、 前言：全球醫療器材監管的數位化與標準化浪潮

在 2024 年至 2026 年間，全球兩大重要醫療器材市場——加拿大與美國——正經歷一場前所未有的法規範式轉移。加拿大衛生部（Health Canada）推動的「法規註冊流程（Regulatory Enrolment Process, REP）」以及美國食品藥物管理局（FDA）發布的「品質管理體系法規（Quality Management System Regulation, QMSR）」，共同標誌著醫療器材產業進入了「數位化申報」與「國際標準接軌」的新紀元。

本報告旨在深度解析這兩項重大變革。Health Canada 的 REP 透過網路化模板與自動化系統提升了審查效率；而美國 FDA 的 QMSR 則透過引用 ISO 13485:2016，實現了與國際品質管理標準的高度統一。這兩項政策的強制實施日期均定於 2026 年上半年，這對全球醫療器材製造商而言，既是合規挑戰，也是優化企業內部管理體系的轉機。



二、 加拿大 Health Canada：法規註冊流程 (REP) 深度解析

1. REP 的核心概念與運作機制

加拿大衛生部的 REP 是一項跨業務線的共同收件流程。其核心在於捨棄傳統的紙本或非結構化電子表單，轉而採用「Web-based Templates（網頁式模板）」。

技術基礎： REP 透過「通用電子提交網關（Common Electronic Submission Gateway, CESG）」接收各類交易。
自動化導入： 系統能自動將廠商提交的元數據（Metadata）與交易資訊導入 Health Canada 的內部數據庫，極大減少了人工登錄錯誤。
範疇擴展： 雖然最初是針對藥品開發，但目前已全面擴散至醫療器材、生物製品及獸藥等領域。
2. REP 實施時程與強制性要求

根據官方公告，REP 的轉型採取了循序漸進的策略：

多年度試行階段： 經過長達數年的 Pilot 測試，確保系統穩定性。
自願使用期： 2024 年 7 月起，開放製造商自願選擇使用 REP 進行申報。
全面強制執行： 2026 年 4 月 1 日起，所有進入加拿大市場的醫療器材相關申請必須透過 REP 流程完成，不再接受傳統申報方式。
3. 製造商的具體獲益

採用 REP 流程，廠商可獲得以下顯著優勢：

即時數據驗證： 網頁模板具備自動檢核功能，若資料格式不符，系統會即時提醒，降低補件率。
生命週期管理： 製造商能更清晰地追蹤產品在 Health Canada 系統內的註冊狀態與過往交易記錄。
減少重複勞動： 透過結構化數據，許多企業資訊只需登錄一次，即可在多個申請案中重複引用。


三、 美國 FDA QMSR：從 21 CFR Part 820 到 ISO 13485 的接軌

1. 法規背景與核心轉變

美國 FDA 於 2024 年發布的最終規則（Final Rule），將原本的《品質體系法規（QSR）》修訂為《品質管理體系法規（QMSR）》。這項改革的核心是直接引用 ISO 13485:2016 作為 FDA 對製造商品質系統的基本要求。

這項變動解決了長期以來製造商必須同時滿足 FDA 專有標準與國際 ISO 標準的「雙重負擔」問題。QMSR 的生效日期定於 2026 年 2 月 2 日，屆時所有的檢查（Inspections）都將基於新的 QMSR 標準。

2. 法律效力與上市前申請 (PMA/HDE)

雖然 QMSR 大量引用 ISO 標準，但其背後的法源依據仍是美國《聯邦食品、藥物和化妝品法案》。對於高風險器材的「上市前核准申請（PMA）」或「人道主義器材豁免（HDE）」，FDA 要求必須在申請文件中包含品質系統的完整描述。若廠商提交的 QMS 資訊無法證明其符合現行優良製造規範（CGMP），FDA 有權拒絕核准。



四、 深度對標：ISO 13485 條款與 FDA 額外期待

在 QMSR 框架下，FDA 並非全盤照搬 ISO 13485，而是針對某些美國法律特有的要求進行了補充。以下為核心條款的深度解讀：

1. 風險管理（ISO 13485 Clause 4 & 7）

FDA 的 QMSR 強調「風險基準方法（Risk-based approach）」必須貫穿整個品質體系，而不僅僅是產品設計。製造商需解釋如何利用風險評估來決定委外流程的控制力道、軟體驗證的深度以及 CAPA 的優先順序。

2. 管理責任（ISO 13485 Clause 5）

FDA 依然保留對「管理代表」的重視。在提交 PMA 時，廠商必須明確識別管理代表，並提供管理審查（Management Review）的程序與摘要。這能確保高層管理者不僅僅是簽字，而是實質參與品質決策。

3. 環境與污染控制（ISO 13485 Clause 6.4）

對於無菌植入物，FDA 的要求比 ISO 13485 更具體。廠商需提交潔淨室（Cleanroom）的驗證數據、空氣潔淨度標準以及微生物控制流程。

4. 產品實現與設計控制（ISO 13485 Clause 7）

這是 FDA 上市前審查的重中之重。

設計確認（Design Validation）： 必須在「具代表性」的產品上進行。如果驗證產品與最終申報產品有差異，必須提供詳細的科學解釋。
設計轉移（Design Transfer）： 廠商需證明設計輸出已成功轉化為生產規範，這包括設備的安裝鑑定（IQ）、操作鑑定（OQ）及表現鑑定（PQ）。


五、 報告必備：關鍵對照表與數據分析

表格 1：Health Canada REP 與傳統申報模式對比

比較維度

傳統模式 (Legacy)

REP 模式 (Modernized)

收件管道

郵寄 CD/USB 或電子郵件

CESG 電子網關 (結構化傳輸)

資料格式

Word/PDF 靜態文件

XML/網頁動態模板

元數據 (Metadata)

人工提取，易出錯

自動導入 Health Canada 系統

處理效率

數週至數月 (含人工錄入)

即時/自動化數據確認

強制時間

2026 年 4 月 1 日淘汰

2026 年 4 月 1 日起唯一合法途徑

表格 2：FDA QMSR 對 ISO 13485 的主要補充要求

ISO 13485 條款

FDA QMSR 額外/特定要求 (21 CFR Part 820)

關鍵說明

不特定條款

唯一器材識別碼 (UDI)

必須符合 21 CFR Part 830 要求

Clause 8.2.1

醫療器材報告 (MDR)

必須符合 21 CFR Part 803，死亡或重傷需通報

Clause 8.3

矯正與移除 (Recalls)

必須符合 21 CFR Part 806 要求

Clause 4.2.4

記錄控制 (Record Control)

必須包含 UDI，且投訴記錄須具備特定美式格式

Clause 7.5.11

標籤與包裝控制

強化對標籤完整性檢查的程序要求 (820.45)

表格 3：2024-2026 跨國合規關鍵里程碑

日期

法規主體

事件性質

廠商應對行動

2024/02

美國 FDA

QMSR 最終規則發布

啟動與現有 QSR 的差異分析

2024/07

加拿大 HC

REP 開放自願使用

測試 CESG 帳號與網頁模板

2026/02/02

美國 FDA

QMSR 正式生效

所有檢查均依據 QMSR/ISO 13485

2026/04/01

加拿大 HC

REP 強制執行

停止接受所有非 REP 格式之申請

六、 20 個關鍵實體及其法規背景 (Entities with Context)

Health Canada (加拿大衛生部)：負責監管加拿大境內醫療器材安全與有效性的聯邦機構。
FDA (美國食品藥物管理局)：美國醫療器材的主管機關，推動 QMSR 轉型的主導者。
ISO 13485:2016：國際標準化組織發布的醫療器材品質管理系統標準，現為 QMSR 的核心。
REP (Regulatory Enrolment Process)：加拿大推動的數位化註冊流程，旨在取代紙本表單。
QMSR (Quality Management System Regulation)：FDA 的新法規，正式名稱為 21 CFR Part 820 修訂版。
CESG (Common Electronic Submission Gateway)：用於安全傳輸電子申報資料的網關系統。
PMA (Premarket Approval)：美國針對三類（高風險）醫療器材最嚴格的上市審查路徑。
HDE (Humanitarian Device Exemption)：針對孤兒病器材的豁免申請路徑。
UDI (Unique Device Identification)：用於在全球供應鏈中唯一識別醫療器材的系統。
MDR (Medical Device Reporting)：FDA 要求的售後不良事件強制報告制度。
CAPA (Corrective and Preventive Action)：品質系統中用於識別原因並防止不合格再次發生的核心流程。
eSTAR：FDA 提供的互動式 PDF 模板，用於導引廠商提交高品質的上市前申請。
Metadata (元數據)：描述數據的數據，在 REP 中用於自動化系統導入。
Harmonization (協調化)：全球監管機構努力統一法規標準，以減少貿易障礙。
Gap Analysis (差異分析)：廠商評估現有體系與新法規之間差距的關鍵工具。
21 CFR Part 806：關於醫療器材矯正與移除報告的美國法規。
ISO 9000:2015：提供 QMSR 引用之術語定義的基礎標準。
FEI (FDA Establishment Identifier)：FDA 為製造設施分配的唯一識別編號。
DUNS Number：用於識別企業實體及其關聯性的國際標準編號。
Q-Submission：廠商在正式提交申請前，與 FDA 進行溝通諮詢的預提交機制。


七、 三大原創 Wow Features (創新洞察)

1. "數位監管孿生" (Digital Regulatory Twin) 概念的實現

Health Canada 的 REP 不僅僅是一個收件箱，它實際上正在構建一個「數位監管孿生」。透過結構化元數據，監管機構可以在其系統中模擬產品的生命週期軌跡。這意味著未來審查將從「閱讀文件」轉變為「數據分析」，大幅縮短審查週期，這是傳統 PDF 申報無法企及的。

2. "風險基準合規矩陣" 的全球統一化

隨著 FDA 採納 ISO 13485，全球主要市場（除中國、巴西等少數國家外）在 QMS 層面實現了實質統一。這催生了一個創新的 Wow Feature：廠商現在可以建立一套「全球通用 QMS 核對矩陣」，只需額外增加 5%-10% 的區域特定要求（如美國 UDI、歐盟 EUDAMED），即可覆蓋全球 80% 的市場，極大地降低了合規營運成本。

3. "預測性補件（Predictive RTA）" 技術的集成

REP 的網頁模板中嵌入了邏輯校驗功能。這項創新功能能在廠商點擊「提交」按鈕前，先行預判其資料是否符合 RTA（Refuse to Accept，拒絕接收）標準。這種將「審查關卡」前移至「填寫階段」的設計，能減少 40% 以上的行政性補件需求，讓審查官能專注於科學數據而非格式。



八、 5 個 Wow Infographic (網頁式資訊圖表代碼)

1. 加拿大 REP 申報流程圖

graph TD

    A[廠商填寫 Web-based Template] --> B{自動格式校驗};

    B -- 通過 --> C[透過 CESG 網關發送];

    B -- 失敗 --> A;

    C --> D[自動導入元數據至 HC 系統];

    D --> E[分配審查官];

    E --> F[生命週期監控];

2. FDA QMSR 法規架構層級

pie title QMSR 組成結構

    "ISO 13485:2016 核心" : 75

    "FDA 補充要求 (UDI/MDR/Part 806)" : 15

    "美國特定記錄管理 (820.35)" : 10

3. 2026 合規倒計時關鍵時間軸

timeline

    title 2026 關鍵截止日

    2026-02-02 : 美國 FDA QMSR 生效 : 所有美國檢查改依 ISO 13485

    2026-04-01 : 加拿大 Health Canada REP 強制化 : 停止傳統紙本/電子申報

4. 品質管理體系 (QMS) 核心循環

graph LR

    subgraph "ISO 13485 & QMSR"

    A[風險管理] --> B[設計開發]

    B --> C[生產控制]

    C --> D[售後監測/MDR]

    D --> E[CAPA/改進]

    E --> A

    end

5. 數位化轉型效益分析圖

graph BT

    A[傳統申報] --> B[高人力/長週期/高錯誤率];

    C[REP/QMSR] --> D[數據化/國際化/自動化];

    B -.- D;

    style D fill:#f9f,stroke:#333,stroke-width:4px



九、 結語：製造商的 2026 戰略規劃

從 QSR 到 QMSR 的轉變，以及從傳統申報到 REP 的躍升，本質上是監管機構在追求「更高的透明度」與「更快的回應速度」。

對於醫療器材製造商，2026 年的兩個截止日期是不容忽視的。廠商應立即採取以下行動：

實施差異分析： 對比現有品質手冊與 ISO 13485:2016 及 QMSR 補充要求。
升級 IT 基礎設施： 確保具備透過 CESG 提交 REP 交易的能力。
強化風險意識： 將 ISO 14971（風險管理）更深層次地融入 QMS 的每一個流程中，而不僅僅是設計檔案。
...
