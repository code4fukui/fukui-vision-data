# Fukui Vision Survey Data

[日本語](README.ja.md)

This repository contains CSV data and a small visualization app for the Fukui Prefecture Long-Term Vision resident survey results.

Source page: https://www.pref.fukui.lg.jp/doc/seiki/vision2019/pre_questionnaire.html

## Files

- `index.html`: browser-based chart app
- `survey_overview.csv`: survey overview by fiscal year
- `questionnaire_timeseries.csv`: time-series answer data for recurring survey questions

## Data

`survey_overview.csv` covers fiscal years 2019 through 2025, corresponding to Reiwa 1 through Reiwa 7.

`questionnaire_timeseries.csv` includes recurring indicators such as:

- Whether respondents feel glad to have lived in Fukui Prefecture
- Current happiness score
- Sense of having a place to belong in the local community
- Sense of having a place for self-expression or activity
- Attachment and pride in the local community
- Three Work Well-being indicators

## View Locally

Open `index.html` in a browser, or serve the directory locally:

```sh
python3 -m http.server 8765
```

Then open:

```txt
http://localhost:8765/
```

## Notes

Intermediate files such as downloaded PDFs, extracted text, and temporary images are excluded by `.gitignore`.

