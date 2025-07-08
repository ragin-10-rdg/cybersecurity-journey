# 📊 Risk Matrix Template

## Risk Scoring Formula
**Risk = Likelihood × Impact**

| Likelihood | Description       |
|------------|-------------------|
| 1          | Rare              |
| 2          | Unlikely          |
| 3          | Possible          |
| 4          | Likely            |
| 5          | Almost Certain    |

| Impact | Description             |
|--------|-------------------------|
| 1      | Negligible              |
| 2      | Minor                   |
| 3      | Moderate                |
| 4      | Major                   |
| 5      | Catastrophic            |

## Risk Matrix Table

|            | **Impact: 1** | **2** | **3** | **4** | **5** |
|------------|---------------|-------|-------|-------|-------|
| **L: 5**   | Low           | Med   | High  | High  | Critical |
| **4**      | Low           | Med   | High  | High  | Critical |
| **3**      | Low           | Med   | Med   | High  | High     |
| **2**      | Low           | Low   | Med   | Med   | High     |
| **1**      | Low           | Low   | Low   | Med   | Med      |

## Example Risk Entry

| Risk ID | Description                   | Likelihood | Impact | Risk Score | Mitigation |
|---------|-------------------------------|------------|--------|------------|------------|
| R-001   | Phishing Email Compromise     | 4          | 4      | 16         | 2FA, Training |
