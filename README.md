
# Duplicate-Safe Incremental Merge and Repair Platform

## Project Overview
A Data Engineering capstone project designed to identify duplicate records, validate incoming data, diagnose data-quality problems, and safely merge records into a trusted database.

## Project Objectives
- Validate incoming data and identify errors.
- Detect exact duplicates using equality matching.
- Detect near-duplicates using Levenshtein Distance.
- Identify possible causes of data-quality problems.
- Apply survivorship and repair rules.
- Quarantine unresolved records.
- Perform incremental MERGE/UPSERT operations.
- Verify processing results through reconciliation.

## Algorithm Used
**Levenshtein Distance Algorithm**

Calculates the minimum number of character insertions, deletions, and substitutions needed to transform one string into another.

A similarity threshold helps identify potential near-duplicates.

## Technologies
- Python
- Pandas
- SQL
- Databricks
- Delta Lake

## Project Workflow
1. Data Ingestion
2. Data Validation
3. Exact Duplicate Detection
4. Near-Duplicate Detection
5. Root-Cause Diagnosis
6. Survivorship and Repair
7. Quarantine Management
8. Incremental MERGE
9. Post-Merge Reconciliation

## Project Status
Capstone Final Review 1

## Future Scope
- Larger dataset evaluation
- Duplicate-detection optimization
- Improved repair mechanisms
- Exploration of machine-learning classifiers
