# Google Spreadsheets Homework

## 1. Google Spreadsheets Sharing Link
* https://docs.google.com/spreadsheets/d/1OGa1_E5hYq8oPfSYQY0b7jXz9HQgGnwYd0nz68H-ns4/edit?usp=sharing
---

## 2. 3 Useful Keyboard Shortcuts & Reasons
1. **`Ctrl` + `c` / `Ctrl` + `v` (복사 및 붙여넣기)**
   * **이유:** 데이터와 공식을 빠르게 복사하여 다른 셀에 적용할 수 있어 작업 시간을 대폭 단축시켜 줍니다.
2. **`Ctrl` + `z` (실행 취소)**
   * **이유:** 실수로 데이터를 삭제하거나 공식을 잘못 입력했을 때 이전 상태로 쉽게 되돌릴 수 있어 매우 유용합니다.
3. **`F4` (참조 유형 전환)**
   * **이유:** 공식을 입력할 때 상대 참조와 절대 참조(`$A$1`)를 수동으로 `$`를 입력하지 않고 빠르게 전환할 수 있어 편리합니다.

---

## 3. Absolute Reference Formula Example & Explanation
* **공식 예시:** `=A2 * $B$1`

### 설명 (Explanation)
* **`A2` (상대 참조):** 공식을 아래나 옆으로 복사할 때 셀 위치에 따라 행과 열 번호가 자동으로 변합니다. (예: `A3`, `A4`로 변경)
* **`$B$1` (절대 참조):** 열 문자(`B`)와 행 번호(`1`) 앞에 `$` 기호가 붙어 있어, 공식을 다른 셀로 복사하더라도 참조하는 위치가 **`B1` 셀로 고정**됩니다.
* **사용 목적:** 고정된 비율(예: 세율, 환율, 할인율 등)이 들어있는 특정 셀을 계속 참조하여 계산해야 할 때 사용합니다.
실습 완료 일시: 2026-11-09
