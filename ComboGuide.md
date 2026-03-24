# 🎮 점수 획득 공식 안내 (Scoring System Guide)

본 게임의 점수는 **[콤보 수]**와 **[스테이지 단계]**에 따라 최종 결정됩니다.  
*The final score is determined by your **[Combo Count]** and the **[Current Stage]**.*

---

## 1. 점수 산출 공식 (Scoring Formula)

* **0콤보 (첫 타격 시) / 0 Combo (First Hit):** 스테이지 단계와 무관하게 **10점 고정** *(Fixed at **10 points**, regardless of the stage.)*

* **1 ~ 4 콤보 (x20 구간) / 1 to 4 Combos (x20 Zone):** `(10 + (현재 콤보 × 20)) × (1.0 + (스테이지 단계 × 0.2))`  
  *(Formula: `(10 + (Current Combo × 20)) × (1.0 + (Stage × 0.2))`)*

* **5 ~ 9 콤보 (x40 구간) / 5 to 9 Combos (x40 Zone):** `(10 + (현재 콤보 × 40)) × (1.0 + (스테이지 단계 × 0.2))`  
  *(Formula: `(10 + (Current Combo × 40)) × (1.0 + (Stage × 0.2))`)*

* **10콤보 이상 (x60 구간) / 10+ Combos (x60 Zone):** `(10 + (현재 콤보 × 60)) × (1.0 + (스테이지 단계 × 0.2))`  
  *(Formula: `(10 + (Current Combo × 60)) × (1.0 + (Stage × 0.2))`)*

---

## 2. 단계별 점수 예시 (Score Examples by Stage)

| Combo | Stage 1 (x1.0) | Stage 2 (x1.2) | Stage 3 (x1.4) | 비고 (Note) |
| :--- | :---: | :---: | :---: | :--- |
| **0 Combo** | 10 | 10 | 10 | **기본 점수 (Base Score)** |
| **1 Combo** | 30 | 36 | 42 | **x20 보너스 적용 (x20 Bonus Applied)** |
| **4 Combo** | 90 | 108 | 126 | |
| **5 Combo** | **210** | **252** | **294** | **x40 보너스 진입 (Enter x40 Bonus)** |
| **9 Combo** | 370 | 444 | 518 | |
| **10 Combo** | **610** | **732** | **854** | **x60 보너스 진입 (Enter x60 Bonus)** |

---

## 💡 고득점 팁 (Score Tip)

1. **콤보의 중요성 (Combo Strategy)**:  
   5콤보와 10콤보를 달성하는 순간 점수 증가폭이 **2배, 3배**로 커집니다.  
   *(The score multiplier increases **2x or 3x** once you reach 5 and 10 combos.)*

2. **최고 콤보 피날레 (Max Combo Finale)**:
   게임 내 모든 벽돌을 파괴하여 클리어할 때, 해당 게임 전체에서 기록한 '최고 콤보' 수치만큼 점수가 곱해져 최종 보너스가 지급됩니다.
   *(When you clear the entire game, your final score is multiplied by your Overall Max Combo for a massive bonus!) *

3. **스테이지 활용 (Stage Advantage)**:  
   높은 스테이지에서 고콤보를 유지하면 배율이 중첩되어 비약적인 점수 획득이 가능합니다.  
   *(Maintain high combos in later stages to stack multipliers for a massive high score!)*
