# The 29-Year Streak Ends: A Data-Driven Autopsy of VfL Wolfsburg's Relegation

## Objective
This project evaluates the finishing efficiency of Bundesliga teams over five seasons (2021/22 – 2025/26), investigating the systemic decay that led to VfL Wolfsburg's relegation.

## Methodology
* **Framework:** Google Data Analytics Professional Certificate (Ask, Prepare, Process, Analyze, Share, Act).
* **Metric:** Expected Goals (xG) vs. Actual Goals.
* **Data Provenance:** Understat.

## Key Findings
* VfL Wolfsburg ranked **9th out of 13** core Bundesliga clubs in 5-year finishing efficiency.
* The team operated with a chronic negative xG differential, indicating a structural inability to convert high-probability chances rather than sudden misfortune.
<img width="1502" height="902" alt="summary_table" src="https://github.com/user-attachments/assets/cc9529cc-7508-4f9c-a370-4a013dccf26f" />

## Limitations & Future Scope
* **Scope of Analysis:** This project specifically isolates attacking finishing efficiency (Goals vs. xG) as a primary indicator of systemic decay.
* **Defensive Metrics:** Relegation is a multi-faceted failure. This analysis does not currently evaluate defensive performance, such as Expected Goals Against (xGA) or Goalkeeper Prevented Goals. 
* **Future Work:** A subsequent iteration of this dashboard will incorporate defensive metrics to provide a holistic view of the Expected Points (xPTS) differential.

## Reproducibility
To run this analysis locally:
1. Clone this repository: `git clone https://github.com/YourUsername/bundesliga-xg-analysis.git`
2. Install dependencies: `pip install -r requirements.txt`
3. Execute the notebook in the `notebooks/` directory.

## License
MIT License. See `LICENSE` for more information.
