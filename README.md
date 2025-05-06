# Research-Spending

## Cleaning & Processing Steps

1. **Raw Data Conversion & Translation**  
   - Translated German column headers and table content to English (`Translated data.csv`)
   - Removed text rows pertaining to additional information, empty cells, and malformed headers

2. **Dataset Splitting and Normalization**  
   - Extracted GDP and public spending values into separate files  
     (`Data Cleaned for GDP.csv`, `Data Cleaned for public spending.csv`)  
   - Normalized values for GDP and public spending separately  
     (`Data Cleaned for GDP - normalized.csv`, `Data Cleaned for public spending - normalized.csv`)

3. **Restructuring & Transposition**  
   - Built long-form tables for Tableau ingestion  
     - `Final Long Form Table.csv` includes spending figures by year and category  
     - `Percentages long form table.csv` Isolates spending as percentage of GDP for visualization purposes

---

## Visualization Output

The final dashboard was created using **Tableau Public** and includes:
- R&D expenditure trends by funding source (commercial, federal, state, nonprofit)
- Average funding share as pie chart
- Spending as % of GDP benchmarked against EU's 3% policy goal
- Annotations highlighting key findings

**Dashboard:** [(https://public.tableau.com/app/profile/manas.singh5881/viz/ResearchSpending_17416989394450/ResearchSpending)]  
**Repository includes**: All cleaned datasets, intermediate files, and processing outputs

---

## Key Takeaways

- Germany has steadily increased its scientific R&D spending since 2000
- Commercial sector is the dominant contributor (~55%)
- Germany met or exceeded the 3% GDP R&D benchmark in recent years

---

## Tools Used

- Excel (for cleaning, translations, normalization)
- Tableau Public (for dashboard)
- Manual validation of totals and restructuring

---

## Notes

This project involved heavy manual cleanup due to:
- German-language source tables
- Inconsistent formats, row breaks, and extraneous text
- Locale-specific CSV quirks (decimal commas, semicolon delimiters)

“Comma-separated” is apparently a flexible suggestion.

---
