# 盛欣網絡 ＆ 盛碁網絡科技
## 營運協同與治理標準化計畫 (Operational Collaboration & Governance Standardization Program)
### Repository: `ISO_DM` (ISO Document Management)

> **線上互動式 Kick-off 戰情首頁**：[https://howardliao.github.io/ISO_DM/](https://howardliao.github.io/ISO_DM/)  
> **架構規劃**：Howard Liao Ph.D.  
> **文管中心 (DCC) 負責人**：  
> - 財務 文管主責：**玉霜**  
> - 技術 文管主責：**翊庭**  
> - 人事・總務 文管主責：**芮郗**  
> **適用對象**：全體營運與職能團隊 (管理部、客服部、財務部、技術部、美術部、MIS 等)

---

## 核心治理理念

- **單一事實來源 (Single Source of Truth, SSOT)**：所有重要業務、技術與管理資訊在 Google Shared Drive 擁有唯一受控落點。
- **聊天可討論，系統才是依據 (24 小時回填原則)**：釘釘、Email 為溝通與即時通知管道；凡涉及承諾、排程、規格異動、款項折扣、重大決策，24 小時內必回填至正式系統 (工單 / Decision Log / 簽核)。
- **賦予承接端明確退件權**：交接先定標準，資訊不全（缺重現步驟、缺尺寸文案、無核准簽章）承接端有權直接退件。
- **無咎復盤 (Blameless Postmortem) 與流程改善認列**：專注防呆機制與自動化改善，將優質 Runbook 與 SOP 沉澱列入績效認列。

---

## 落地工具鏈五步法

```
釘釘 / Email ───► tldraw ───► diagrams.net ───► Google Docs ───► Google Drive
(即時溝通通知)   (工作坊草圖)   (跨部門泳道圖)    (程序書發布)    (Shared Drive SSOT)
```

1. **釘釘 / Email**：日常通知、提醒與緊急協調（不作唯一正式憑據）。
2. **tldraw**：線上白板進行跨部門訪談，用彩色便利貼梳理真實卡點與等待點（紅色標記高風險）。
3. **diagrams.net**：繪製跨部門泳道圖與 SOP 圖，原始 `.drawio` 檔直接保存在 Google Drive。
4. **Google Docs**：發布正式程序書與操作指導書，嵌入流程圖、RACI 矩陣與表單連結。
5. **Google Shared Drive**：組織受控文件庫，集中保存檔案資產，不受人員異動影響。

---

## 五大核心端到端流程 (E2E Flows)

- **[F-01] 客戶案件到結案** (客服部主責)：問題分級、SLA 響應、跨部門派工與結案驗收。
- **[F-02] 需求評估到交付驗收** (PM / 技術部主責)：需求規格、美術素材、驗收條件 (AC) 與版本交付。
- **[F-03] 版本變更到上線發布** (技術部主責)：變更申請、UAT 測試、Rollback 回滾方案與維運監控。
- **[F-04] 報價對帳到收款核銷** (財務部主責)：俱樂部房卡批銷、開桌服務費核銷、折讓簽核與發票憑證。
- **[F-05] 人員生命週期與 IT 服務** (管理部 / MIS 主責)：到職配置、異動審核、離職當日準時停權。

---

## 目錄結構

```text
ISO_DM/
├── index.html                  # 互動式 Kick-off 官方戰情網頁 (GitHub Pages 進入點)
├── governance_kickoff.html     # 互動網頁獨立備份檔
├── .nojekyll                   # 繞過 GitHub Pages Jekyll 處理
└── README.md                   # 專案總綱說明文件
```
