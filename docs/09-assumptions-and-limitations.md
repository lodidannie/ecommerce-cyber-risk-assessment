# 09 - Assumptions and Limitations

## No Formal Matrix
The source does not define the rule that converts likelihood and impact into an overall rating.

## Rating Inconsistencies
- Data breach: Medium likelihood / High impact -> Medium
- Application exploitation: Medium / High -> High
- Denial of service: Medium / Medium -> High
- Insider threat: Low / High -> Low

The repository preserves these values instead of inventing a new scoring rule.

## Data Quality
The insider-threat row labels its threat source as External. That conflict is flagged, not silently corrected.

## Residual Risk
No formal control-effectiveness testing is provided.

## Quantitative Model
The CBA does not document how initial monetary exposure was derived.

## Technical Validation
No penetration test, configuration assessment, vulnerability scan, log review, or evidence-based control test is included.
