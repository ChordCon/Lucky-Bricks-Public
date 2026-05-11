**콤보 모드 (COMBO MODE)**
# 🎮 점수 획득 공식 안내 (Scoring System Guide)

본 게임의 점수는 **[콤보 수]**와 **[스테이지 단계]**에 따라 최종 결정됩니다.  
*The final score is determined by your **[Combo Count]** and the **[Current Stage]**.*

---

## 1. 점수 산출 공식 (Scoring Formula)

*   **0콤보 (첫 타격 시) / 0 Combo (First Hit):** 
    스테이지 단계와 무관하게 **10점 고정**  
    *(Fixed at **10 points**, regardless of the stage.)*

*   **1 ~ 4 콤보 (x20 구간) / 1 to 4 Combos (x20 Zone):** 
    `Score = (10 + (Current Combo × 20)) × (1.0 + (Stage × 0.2))`

*   **5 ~ 9 콤보 (x40 구간) / 5 to 9 Combos (x40 Zone):** 
    `Score = (10 + (Current Combo × 40)) × (1.0 + (Stage × 0.2))`

*   **10콤보 이상 (x60 구간) / 10+ Combos (x60 Zone):** 
    `Score = (10 + (Current Combo × 60)) × (1.0 + (Stage × 0.2))`

---

## 2. 단계별 점수 예시 (Score Examples by Stage)

| Combo | Stage 1 (x1.2) | Stage 2 (x1.4) | Stage 3 (x1.6) | 비고 (Note) |
| :--- | :---: | :---: | :---: | :--- |
| **0 Combo** | 10 | 10 | 10 | 기본 점수 (Base) |
| **1 Combo** | 36 | 42 | 48 | x20 보너스 적용 |
| **4 Combo** | 108 | 126 | 144 | |
| **5 Combo** | 252 | 294 | 336 | x40 보너스 진입 |
| **9 Combo** | 444 | 518 | 592 | |
| **10 Combo** | 732 | 854 | 976 | x60 보너스 진입 |

*(참고: 공식상의 Stage 1은 시스템적으로 1.2배율부터 시작됨을 예시로 표기함)*

---

# 💡 고득점 팁 (Score Tip)

### 1. 콤보의 중요성 (Combo Strategy)

5콤보와 10콤보를 달성하는 순간 점수 증가폭이 **2배, 3배**로 커집니다.  
*(The score multiplier increases significantly once you reach 5 and 10 combos.)*

### 2. 최고 콤보 피날레 (Max Combo Finale)

모든 벽돌을 파괴하여 게임을 클리어하는 순간, **해당 게임 전체에서 기록한 '최고 콤보' 수치만큼 점수가 곱해져** 파격적인 최종 보너스가 지급됩니다.  
*(When you clear the entire game, your final score is multiplied by your **Overall Max Combo** for a massive bonus!)*

### 3. 스테이지 활용 (Stage Advantage)

높은 스테이지에서 고콤보를 유지하면 배율이 중첩되어 비약적인 점수 획득이 가능합니다.  
*(Maintain high combos in later stages to stack multipliers for a massive high score!)*

---

# 🎮 게임 보너스 & 효과 가이드 (Game Bonus & Effect Guide)

본 가이드는 게임 내 아이템 효과와 최종 점수 합산 시 적용되는 보너스 규칙을 설명합니다.  
*This guide explains the item effects and bonus scoring rules applied at the end of each session.*

---

## ⚡ 1. 효과들 (Effects)

각 효과는 **16.67%**의 확률로 등장합니다.  
*Each effect has a **16.67%** chance to appear.*

| ID | Color | Effect (KR) | Effect (EN) |
| :--- | :--- | :--- | :--- |
| 1 | Blue | 공 속도 감소 | Ball speed down |
| 2 | Red | 공 속도 증가 | Ball speed up |
| 3 | Blue | 바 크기 감소 | Bar size down |
| 4 | Red | 바 크기 증가 | Bar size up |
| 5 | Red | 점수 +100 | Score + 100 |
| 6 | Red | 점수 x2 | Score x 2 |

> **Note:** 바 크기나 공 속도가 최소/최대치에 도달하면 해당 효과는 적용되지 않습니다.  
> *Note: Effects do not apply if the limit is already reached.*

---

**숫자 보너스와 컬러 보너스는 효과를 10개 모아야 활성화 됩니다.**  
**Collect 10 effects to activate Number and Color Bonuses.**

---

## 🔢 2. 숫자 보너스 (Number Bonus)

동일한 카테고리 내에서는 **가장 높은 배율** 하나만 적용됩니다.  
*The highest multiplier applies if multiple conditions are met within this category.*

| Bonus Name | Multiplier | Condition (EN) |
| :--- | :---: | :--- |
| **Straight Number** | **x 4.0** | A sequence of 5+ consecutive effects |
| **Quad Combo** | **x 3.5** | Two sets of 4 identical effects |
| **Balanced Combo** | **x 3.0** | Two sets of 3 + Two sets of 2 identical effects |
| **Full Stack** | **x 3.0** | 8+ effects of the same type |
| **Half Stack** | **x 2.5** | 4 to 7 effects of the same type |
| **Triple Combo** | **x 2.0** | Two or more sets of 3 identical effects |
| **Duet Master** | **x 1.5** | Four or more sets of 2 identical effects |
| **Duet Combo** | **x 1.2** | Two or more sets of 2 identical effects |

---

## 🎨 3. 컬러 보너스 (Color Bonus)

특정 색상 계열의 아이템으로만 구성했을 때 추가 배율을 획득합니다.  
*Earn additional multipliers by collecting effects of specific color sets.*

| Bonus Name | Multiplier | Condition (EN) |
| :--- | :---: | :--- |
| **Red Set** | **x 2.0** | ID 2, 4, 5, 6 only (Must include 5 or 6) |
| **Pure Red Set** | **x 2.5** | ID 2, 4 only (Exclude 5, 6) |
| **Blue Set** | **x 3.0** | ID 1, 3 only |

---

## 💡 How to Score Higher

**Tip:** 숫자 보너스와 컬러 보너스는 **중첩(Stackable)**이 가능합니다!  
*Tip: Number bonuses and Color bonuses are **stackable**!*

---
**Lucky Bricks - Your Choice, Your Score!**
