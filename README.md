# ACLS ROSC 後照護闖關遊戲

> 一款線上互動式 ACLS 教學遊戲,讓學習者在情境闖關中學習心跳停止恢復自發循環(ROSC)後的重症照護。基於 **2025 年 AHA 心肺復甦與緊急心血管照護指引**。

線上遊玩:`https://<你的帳號>.github.io/<repo 名稱>/`(設定 GitHub Pages 後)

---

## 特色

- **七關主線闖關** — 從心律辨識到複雜重症情境,難度漸進
  1. 心律辨識挑戰(VF / pVT / Asystole / PEA / 竇性心律,限時判讀)
  2. 首次 ROSC — 基礎穩定(MAP、升壓藥、SpO₂、PaCO₂、TTM)
  3. 體溫管理的 24 小時
  4. 癲癇危機
  5. H's & T's 可逆原因排查(高血鉀情境)
  6. 致命可逆原因三案例(張力性氣胸、心包填塞、肺栓塞)
  7. STEMI 與血流動力學不穩定
- **即時生命徵象儀表板** — MAP、心律、體溫、SpO₂、RASS 隨決策動態變化,含動態心電圖
- **證據導向回饋** — 每個決策附「為什麼?」證據彈窗,引用 2025 AHA 指引
- **文獻庫** — 真實文獻與 DOI 連結(2025 AHA、TTM2、BOX 等)
- **隨機快速挑戰** — 從題庫隨機抽題的限時快問快答
- **錯題複習/重練** — 自動收集錯題,可針對性重新練習
- **結算分析** — CPC 預後評等、功能恢復曲線、生命徵象趨勢圖
- **可列印成績單** — 含學員姓名/單位、各關得分、徽章,適合院內訓練紀錄
- 全程 SVG 圖示,無 emoji;單一 HTML 檔,可離線使用

## 使用方式

**直接使用:** 下載 `index.html`(或 `acls_game.html`),用任何現代瀏覽器開啟即可,無需網路、無需安裝。

**架設於 GitHub Pages:**

1. 將本專案上傳至一個 GitHub repo(主檔案命名為 `index.html`)。
2. 進入 repo 的 **Settings → Pages**。
3. Source 選擇 `main` 分支、`/ (root)` 目錄,儲存。
4. 約一兩分鐘後即可透過 `https://<你的帳號>.github.io/<repo 名稱>/` 存取。

## 隱私

所有學員姓名、得分、錯題等資料僅暫存於瀏覽器記憶體中,重新整理頁面即清除,**不會上傳至任何伺服器**。

## 免責聲明

本遊戲為**教育模擬用途,非正式認證,亦不可取代臨床判斷或正式指引**。所有臨床決策請依據完整的最新指引與個別病人狀況,並諮詢合格醫療專業人員。內容雖依 2025 AHA 指引撰寫,正式教學使用前建議由臨床專家覆核。

## 參考文獻

1. 2025 AHA Guidelines for CPR & ECC — Part 11: Post-Cardiac Arrest Care. Hirsch KG, et al. *Circulation.* 2025;152(16_suppl_2):S673–S718. doi:10.1161/CIR.0000000000001375
2. 2025 AHA Guidelines for CPR & ECC — Executive Summary. Del Rios M, et al. *Circulation.* 2025;152(16_suppl_2):S284–S312. doi:10.1161/CIR.0000000000001372
3. TTM2 Trial. Dankiewicz J, et al. *N Engl J Med.* 2021;384:2283–2294. doi:10.1056/NEJMoa2100591
4. BOX Trial. Kjaergaard J, et al. *N Engl J Med.* 2022;387:1456–1466. doi:10.1056/NEJMoa2208687
5. Long B, Gottlieb M. Managing the Patient With Return of Spontaneous Circulation. *Am J Emerg Med.* 2025;93:26–36. doi:10.1016/j.ajem.2025.03.039

## 授權

本專案採用 [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/)(姓名標示-非商業)授權,詳見 `LICENSE` 檔。可自由分享與改作於非商業之教育用途,惟須標示來源。
