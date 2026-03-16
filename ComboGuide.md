# 🎮 점수 획득 공식 안내 (Scoring System Guide)

본 게임의 점수는 **[콤보 수]**와 **[스테이지 단계]**에 따라 최종 결정됩니다.  
*Your final score is determined by your **[Combo count]** and the **[Current Stage]**.*

---

## 1. 점수 산출 공식 (Scoring Formula)

* **0콤보 (첫 타격 시):** 스테이지 단계와 무관하게 **10점 고정** *(0 Combo (First hit): Fixed at **10 points**, regardless of the stage.)*

* **1콤보 이상 시:** `(10 + (현재 콤보 × 20)) × (1.0 + (스테이지 단계 × 0.2))`  
  *(1 Combo or higher: `(10 + (Current Combo × 20)) × (1.0 + (Stage Number × 0.2))`)*

---

## 2. 단계별 점수 예시 (Score Examples by Stage)

| Combo | Stage 1 (1.0) | Stage 2 (1.2) | Stage 3 (1.4) |
| :--- | :--- | :--- | :--- |
| **0 Combo** | 10 | 10 | 10 |
| **1 Combo** | 30 | 36 | 42 |
| **2 Combo** | 50 | 60 | 70 |
| **3 Combo** | 70 | 84 | 98 |
| **4 Combo** | 90 | 108 | 126 |

---

## 참고 사항 (Note)

* **0콤보일 때는** 스테이지 배율이 적용되지 않으며, 무조건 **10점**을 획득합니다.  
  *(At 0 combos, the stage multiplier is not applied, and you will always receive 10 points.)*

* **1콤보부터는** 스테이지 단계에 따른 배율이 적용되어 점수가 산출됩니다.  
  *(From 1 combo onwards, the stage multiplier is applied to calculate your score.)
