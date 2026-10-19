# Evaluation Data Documentation

## 1. Risk-category test cases

Files:
- risk_test_cases.csv
- baseline_results.json
- retrieval_baseline_results.csv

The three files contain the same ten case IDs (TC01–TC10).
The cases cover four internally assigned categories:
Low Risk (3), Moderate Risk (3), High Risk (2), and Ambiguous (2).

The baseline contains 7 exact matches out of 10 cases (70%).
This is a descriptive result on a small test set, not evidence of
clinical validity or generalization.

## 2. Safety-rule test cases

Files:
- heldout_evaluation_cases.csv
- additional_evaluation_cases.csv

These files contain 16 and 20 cases, respectively. Previous rule
revisions were informed by inspecting these cases. Therefore, the
reported results must not be described as independent evaluation.

## 3. Provenance and limitations

The repository documentation and inspected JSON/CSV records do not
identify an original public dataset, source URL, collection method,
annotation procedure, or independent annotators.

The original provenance of these cases remains unverified. Do not
describe them as publicly sourced, clinically validated, or
representative of adolescents unless supporting documentation is found.

The labels are experimental categories, not clinical assessments.
The examples are currently suitable for software debugging and
exploratory functional testing only.

## 4. Recommended next steps

1. Trace the original source and labeling process, if possible.
2. Record the source, license, inclusion criteria, and annotation
   method for any external evaluation data.
3. Keep development examples separate from a genuinely independent
   evaluation set.
4. Report category-level metrics and limitations, not accuracy alone.
5. Do not use the system to diagnose or independently manage a crisis.
