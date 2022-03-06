# TEST PLAN :

## Table no: High level test plan
|Test ID | Description |  Input   |   Exp O/P   |   
|:-------|:------------|:-----------|:------------|
| HLR1 | ex: If available balance is greater then 15 rupes | 15 | Arduino turn on the electricity of home or office by using relay.|
| HLR2 | ex: If balance is less then 15 rupes | 15 |  ARDUINO Sends SMS to user phone regarding low balance alaret & requesting to rechargesoon. |
| HLR3 | ex: if balance is less than 5 rupes | 5 | ARDUINO turn off,and power cut due to low balance.|

## Table no: Low level test plan

|Test ID|	Description|	 Input | Exp O/P |
|:-----|:------------|:---------|:--------|
| LLR1 | if balance is low | 0 |  ARDUINO turn off ,power cut due to low balance|

