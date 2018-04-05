# Procedure to get an assessment into TAF

To make this task easier, and to measure the progress towards the goal, we
divide it into many small steps.

Fifteen steps to get the 'core assessment' into TAF:

<br>

**Part A: Get model to run**

1. Contact stock coordinator
2. Get files (data, model) and earlier reports
3. Run model

**Part B: Examine the analysis**

4. Check that data and results resemble earlier reports
5. Explore input: data types, files, etc.
6. Identify minimal set of files to run the assessment

**Part C: Data script**

7. Read data files
8. Preprocess data
9. Write TAF files

**Part D: Input and model scripts**

10. Prepare model input
11. Run model
12. Document dependencies, especially non-CRAN packages

**Part E: Output script**

13. Get N at age, F at age
14. Construct summary table: Rec, SSB, Fbar, etc.
15. Write TAF files

<br>

## Ways to extend the 'core assessment'

**Part X: Start from disaggregated data**
- Get data files with disaggregated data
- Revise data.R to read those files
- Filter, smooth, aggregate, etc. to create aggregated data

**Part Y: Report script**
- Produce formatted tables that look like earlier reports
- Produce figures that look like earlier reports

**Part Z: TAF forecast**
- If forecast is simple, script it in report_forecast.R
- If complex, create separate analysis: data, input, etc.