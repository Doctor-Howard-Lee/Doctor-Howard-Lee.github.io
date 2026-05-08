# Publications Index

> Final published PDFs of Lee CH papers, organised for blog and reference use.
> 本檔為本機索引，**不要上傳到 GitHub**（內含本機路徑）。

---

## ✅ 已完成複製（15 篇）

| 年份 | 角色 | 期刊 | 檔名 |
|---|---|---|---|
| 2025 | corresponding | Antimicrob Agents Chemother | `2025-aac-fn-de-escalation-meta.pdf` |
| 2025 | corresponding | Diabetology Metab Syndr | `2025-dms-ici-type1-diabetes-risk.pdf` |
| 2025 | corresponding | J Cancer Res Pract | `2025-jcrp-palliative-care-tsgh-ten-year.pdf` |
| 2024 | first | Cochrane DSR | `2024-cochrane-cll-maintenance-therapy.pdf` |
| 2022 | corresponding | Postgrad Med J | `2022-pgmj-different-pedagogies-nma.pdf` |
| 2022 | co | J Pers Med | `2022-jpm-digital-chest-tube-drainage.pdf` |
| 2021 | first | J Cancer Res Pract | `2021-jcrp-disseminated-nocardiosis-case-report.pdf` |
| 2021 | co | J Dental Sci | `2021-jds-maxillary-protraction-3d.pdf` |
| 2020 | first | Medicine | `2020-medicine-endocrine-therapy-mbc-nma.pdf` |
| 2020 | corresponding | Critical Care | `2020-critical-care-pav-vs-psv-weaning.pdf` |
| 2020 | co | Scientific Reports | `2020-scientific-reports-hfnc-apneic-oxygenation.pdf` |
| 2019 | corresponding | J Clin Med | `2019-jcm-influenza-vaccines-immunocompromised.pdf` |
| 2019 | corresponding | J Clin Med | `2019-jcm-rrcll-targeted-agents-nma.pdf` |
| 2019 | co | J Clin Med | `2019-jcm-aspirin-dm-primary-prevention.pdf` |
| 2018 | first | Antimicrob Agents Chemother | `2018-aac-fungal-prophylaxis-nma.pdf` |

---

## ⚠️ 0-byte 佔位檔，需手動覆寫（10 篇）

複製過程中 macOS 跟 sandbox 之間的 mount 同步出現死鎖（這是已知問題，跟檔案無關），這 10 個檔在資料夾裡是 0 bytes。請**手動覆寫**：

| 目標檔名（已存在於 docs/publications/） | 來源（本機路徑） |
|---|---|
| `2025-the-breast-abemaciclib-vs-palbociclib.pdf` | `~/Documents/TSGH/Clinical/Paper/Publication/Real-world comparative effectiveness of first-line abemaciclib versus palbociclib.pdf` |
| `2024-blood-sglt2-erythrocytosis-thrombosis.pdf` | `~/Documents/TSGH/Clinical/Paper/Publication/Erythrocytosis and thromboembolic risks  associated with SGLT2 inhibitors in type 2  diabetes/Erythrocytosis and thromboembolic risks   associated with SGLT2 inhibitors in type 2   diabetes.pdf` |
| `2023-cochrane-smm-early-intervention.pdf` | `~/Documents/TSGH/Clinical/Paper/Publication/SMM.pdf` |
| `2021-frontiers-medicine-sbt-weaning-nma.pdf` | `~/Documents/TSGH/Clinical/Paper/Publication/Responding/SBT/Methods of Weaning From Mechanical Ventilation in Adult A Network Meta Analysis.pdf` |
| `2020-plos-one-cll-maintenance-nma.pdf` | `~/Documents/TSGH/Clinical/Paper/Publication/A network meta-analysis of maintenance therapy in chronic lymphocytic leukemia.pdf` |
| `2018-jms-nsclc-brain-metastases-egfr.pdf` | `~/Documents/TSGH/Clinical/Paper/Publication/The clinical outcome of brain metastases in nonsmall cell lung cancer patients.pdf` |
| `2018-oncotarget-sclc-premorbid-bmi.pdf` | `~/Documents/TSGH/Clinical/Paper/Publication/First-author/SCLC/oncotarget-09-24642.pdf` |
| `2017-plos-one-micafungin-vs-azoles.pdf` | `~/Documents/TSGH/Clinical/Paper/Publication/First-author/Febrile neutropenia and micafungin/journal.pone.0180050.pdf` |
| `osimertinib-vs-1st-gen-egfr-tki-nsclc.pdf`（年份待補） | `~/Documents/TSGH/Clinical/Paper/Publication/Osimertinib Versus First-Generation Epidermal Growth Factor Receptor Tyrosine Kinase Inhibitors for Metastatic.pdf` |
| `decompression-sickness-case-report-recovery.pdf`（年份待補） | `~/Documents/TSGH/Clinical/Paper/Publication/First-author/decompression sickness/Complete recovery after severe decompression sickness with multiple organs dysfunction..pdf` |

### 兩種覆寫方式

**A. 用 Finder（最簡單）**

1. 開兩個 Finder 視窗
2. 來源視窗到 `~/Documents/TSGH/Clinical/Paper/Publication/`
3. 目標視窗到 `~/Documents/Blog/docs/publications/`
4. 找到上表來源檔，**先重新命名為對應的目標檔名**（按 Enter 編輯名字），然後拖到目標資料夾
5. 系統問「要取代嗎？」按「取代」覆寫 0-byte 檔

**B. 用終端機（執行下方腳本一次完成）**

打開 Terminal，貼上：

```bash
cd ~/Documents/TSGH/Clinical/Paper/Publication

cp "Real-world comparative effectiveness of first-line abemaciclib versus palbociclib.pdf" \
   ~/Documents/Blog/docs/publications/2025-the-breast-abemaciclib-vs-palbociclib.pdf

cp "Erythrocytosis and thromboembolic risks  associated with SGLT2 inhibitors in type 2  diabetes/Erythrocytosis and thromboembolic risks   associated with SGLT2 inhibitors in type 2   diabetes.pdf" \
   ~/Documents/Blog/docs/publications/2024-blood-sglt2-erythrocytosis-thrombosis.pdf

cp "SMM.pdf" \
   ~/Documents/Blog/docs/publications/2023-cochrane-smm-early-intervention.pdf

cp "Responding/SBT/Methods of Weaning From Mechanical Ventilation in Adult A Network Meta Analysis.pdf" \
   ~/Documents/Blog/docs/publications/2021-frontiers-medicine-sbt-weaning-nma.pdf

cp "A network meta-analysis of maintenance therapy in chronic lymphocytic leukemia.pdf" \
   ~/Documents/Blog/docs/publications/2020-plos-one-cll-maintenance-nma.pdf

cp "The clinical outcome of brain metastases in nonsmall cell lung cancer patients.pdf" \
   ~/Documents/Blog/docs/publications/2018-jms-nsclc-brain-metastases-egfr.pdf

cp "First-author/SCLC/oncotarget-09-24642.pdf" \
   ~/Documents/Blog/docs/publications/2018-oncotarget-sclc-premorbid-bmi.pdf

cp "First-author/Febrile neutropenia and micafungin/journal.pone.0180050.pdf" \
   ~/Documents/Blog/docs/publications/2017-plos-one-micafungin-vs-azoles.pdf

cp "Osimertinib Versus First-Generation Epidermal Growth Factor Receptor Tyrosine Kinase Inhibitors for Metastatic.pdf" \
   ~/Documents/Blog/docs/publications/osimertinib-vs-1st-gen-egfr-tki-nsclc.pdf

cp "First-author/decompression sickness/Complete recovery after severe decompression sickness with multiple organs dysfunction..pdf" \
   ~/Documents/Blog/docs/publications/decompression-sickness-case-report-recovery.pdf

echo "完成。檢查所有檔案大小："
ls -lh ~/Documents/Blog/docs/publications/*.pdf
```

執行完後檢查每個檔案大小應在 200KB～4MB 區間，沒有 0 byte 的就成功了。

---

## 完整引用清單（按年份）

### 2025
- **Lee CH** et al. Real-world comparative effectiveness of first-line abemaciclib vs palbociclib in HR+/HER2− metastatic breast cancer. *The Breast*. 2025. → `2025-the-breast-abemaciclib-vs-palbociclib.pdf`
- Chen YH ... **Lee CH** (corresponding). Efficacy and safety of early antibiotic de-escalation in febrile neutropenia for patients with hematologic malignancy. *Antimicrob Agents Chemother*. 2025;69(4):e01597-24. → `2025-aac-fn-de-escalation-meta.pdf`
- Lin MH ... Chen PH, **Lee CH** (corresponding). Immune checkpoint inhibitor therapy and risk of type 1 diabetes in metastatic cancer patients. *Diabetol Metab Syndr*. 2025;17:377. → `2025-dms-ici-type1-diabetes-risk.pdf`
- Lee HL, Chen PH, Chen JH, Dai MS, Ho CL, **Lee CH** (corresponding). Ten-year experience and evolving of palliative care at a tertiary medical center in Taiwan. *J Cancer Res Pract*. 2025;12(3):69-75. → `2025-jcrp-palliative-care-tsgh-ten-year.pdf`

### 2024
- **Lee CH** et al. Maintenance therapy for chronic lymphocytic leukaemia. *Cochrane Database Syst Rev*. 2024. → `2024-cochrane-cll-maintenance-therapy.pdf`
- Chen YH ... **Lee CH** (corresponding). Effect of SGLT2 inhibitors on erythrocytosis and arterial thrombosis risk in T2DM. *Blood*. 2024;144:5214. → `2024-blood-sglt2-erythrocytosis-thrombosis.pdf`

### 2023
- Chen PH, Jhou HJ, Ho CL, Huang HL, **Lee CH** (corresponding). Early intervention for high-risk smoldering multiple myeloma. *Cochrane Database Syst Rev*. 2023;CD015494. → `2023-cochrane-smm-early-intervention.pdf`

### 2022
- Jhou HJ, Ou-Yang LJ, Lin MH, Chen PH, Ho CL, **Lee CH** (corresponding). Different pedagogies for acquisition of knowledge and skill: a systematic review and network meta-analysis. *Postgrad Med J*. 2022;98(1162):604-9. → `2022-pgmj-different-pedagogies-nma.pdf`
- Chang PC ... **Lee CH** (co), Chang TW. Promising effects of digital chest tube drainage system for pulmonary resection. *J Pers Med*. 2022;12(4):512. → `2022-jpm-digital-chest-tube-drainage.pdf`

### 2021
- Jhou HJ, Chen PH, Ou-Yang LJ, Lin C, Tang SE, **Lee CH** (corresponding). Methods of weaning from mechanical ventilation in adults: a network meta-analysis. *Front Med*. 2021. → `2021-frontiers-medicine-sbt-weaning-nma.pdf`
- Lee WC, Shieh YS, Liao YF, **Lee CH** (co), Huang C. Long-term maxillary 3D changes following maxillary protraction. *J Dent Sci*. 2021;16(1):168-177. → `2021-jds-maxillary-protraction-3d.pdf`
- **Lee CH**, Ho CL, Ye RH. Disseminated nocardiosis coinfection with extrapulmonary tuberculosis in metastatic thymoma: case report. *J Cancer Res Pract*. 2021;8(3):117-122. → `2021-jcrp-disseminated-nocardiosis-case-report.pdf`

### 2020
- **Lee CH**, Chen PH, Lin C, Wang CY, Ho CL. A network meta-analysis of maintenance therapy in CLL. *PLoS One*. 2020;15(1):e0226879. → `2020-plos-one-cll-maintenance-nma.pdf`
- **Lee CH** et al. Endocrine therapies in postmenopausal women with HR+/HER2− advanced breast cancer: NMA. *Medicine*. 2020;99(13):e19618. → `2020-medicine-endocrine-therapy-mbc-nma.pdf`
- Ou-Yang LJ ... **Lee CH** (corresponding). Proportional assist ventilation vs pressure support ventilation for weaning. *Crit Care*. 2020;24(1):556. → `2020-critical-care-pav-vs-psv-weaning.pdf`
- Jhou HJ, Chen PH, Lin C, Yang LY, **Lee CH** (co), Peng CK. High-flow nasal cannula therapy as apneic oxygenation. *Sci Rep*. 2020;10(1). → `2020-scientific-reports-hfnc-apneic-oxygenation.pdf`

### 2019
- Lai JJ, Lin C, Ho CL, Chen PH, **Lee CH** (corresponding). Alternative-dose vs standard-dose trivalent influenza vaccines. *J Clin Med*. 2019;8(5):590. → `2019-jcm-influenza-vaccines-immunocompromised.pdf`
- Chen PH, Ho CL, Lin C, Wu YY, Huang TC, Tu YK, **Lee CH** (corresponding). Treatment outcomes of novel targeted agents in r/r CLL. *J Clin Med*. 2019;8(5):737. → `2019-jcm-rrcll-targeted-agents-nma.pdf`
- Lin MH ... **Lee CH** (co). Low-dose aspirin for primary prevention of CVD in DM. *J Clin Med*. 2019;8(5):609. → `2019-jcm-aspirin-dm-primary-prevention.pdf`

### 2018
- **Lee CH**, Lin C, Ho CL, Lin JC. Primary fungal prophylaxis in hematological malignancy: NMA. *Antimicrob Agents Chemother*. 2018;62(8). → `2018-aac-fungal-prophylaxis-nma.pdf`
- **Lee CH** et al. Premorbid BMI as a prognostic factor in small-cell lung cancer. *Oncotarget*. 2018;9(37):24642. → `2018-oncotarget-sclc-premorbid-bmi.pdf`
- **Lee CH** et al. Clinical outcome of brain metastases in NSCLC with EGFR mutation. *J Med Sci*. 2018;38(6):247-251. → `2018-jms-nsclc-brain-metastases-egfr.pdf`

### 2017
- **Lee CH**, Lin JC, Ho CL, Sun M, Yen WT, Lin C. Efficacy and safety of micafungin vs extensive azoles. *PLoS One*. 2017;12(7):e0180050. → `2017-plos-one-micafungin-vs-azoles.pdf`

### Year/journal pending（年份待補）
- `osimertinib-vs-1st-gen-egfr-tki-nsclc.pdf` — Osimertinib vs first-generation EGFR TKIs for metastatic NSCLC. **可能是引用文獻不是您的論文 — 請確認**。
- `decompression-sickness-case-report-recovery.pdf` — Complete recovery after severe decompression sickness (case report)。

---

最後更新：2026-05-07
