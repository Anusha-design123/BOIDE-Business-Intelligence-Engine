# BOIDE File Structure

```text
BOIDE/
|-- app.py
|-- README.md
|-- PROJECT_STRUCTURE.md
|-- requirements.txt
|-- BOIDE_Diagrams_Document.md
|-- BOIDE_Diagrams_Word_Friendly.rtf
|-- majorp.docx
|-- generate_boide_presentation_with_methodology.ps1
|-- generate_boide_review_ppt.ps1
|-- generate_boide_summary_pdf.ps1
|
|-- assets/
|   `-- style.css
|
|-- data/
|   |-- olist_customers_dataset.csv
|   |-- olist_geolocation_dataset.csv
|   |-- olist_orders_dataset.csv
|   |-- olist_order_items_dataset.csv
|   |-- olist_order_payments_dataset.csv
|   |-- olist_order_reviews_dataset.csv
|   |-- olist_products_dataset.csv
|   |-- olist_sellers_dataset.csv
|   `-- product_category_name_translation.csv
|
|-- output/
|   |-- boide_app_summary.html
|   |-- BOIDE_App_Summary.pdf
|   |-- BOIDE_Design_Implementation_First_Review.pdf
|   |-- BOIDE_Design_Implementation_First_Review.pptx
|   |-- BOIDE_Project_Presentation.pdf
|   `-- BOIDE_Project_Presentation.pptx
|
|-- pages/
|   |-- __init__.py
|   |-- 1_Overview.py
|   |-- 2_Product_analysis.py
|   |-- 3_Forecasting.py
|   |-- 4_Segmentation.py
|   |-- 5_Anomaly_Detection.py
|   |-- 6_AI_Insights.py
|   |-- 7_Digital_Twin.py
|   |-- 8_Reports.py
|   |-- 9_Methodology.py
|   `-- 10_Data_Preview.py
|
|-- tests/
|   |-- __init__.py
|   `-- test_boide.py
|
|-- uml/
|   |-- class_diagram.png
|   |-- component_diagram.png
|   |-- data_flow.png
|   |-- decision_flow.png
|   |-- sequence_diagram.png
|   `-- Data-Driven Decision-2026-03-27-151150.png
|
|-- utils/
|   |-- __init__.py
|   |-- data_loader.py
|   |-- decision_panel.py
|   |-- forecasting_model.py
|   |-- simulation.py
|   |-- ui.py
|   `-- mini_llm/
|       |-- __init__.py
|       |-- context_builder.py
|       |-- engine.py
|       |-- rules.py
|       `-- scorer.py
|
`-- tmp_pptx_inspect/
```

## Folder Purpose

- `assets/`: Global styling used by the Streamlit UI.
- `data/`: Source datasets used across every analytics module.
- `output/`: Generated exports, PDFs, HTML summaries, and presentation files.
- `pages/`: Streamlit multipage views for each BOIDE workflow step, including reports, methodology, and data preview.
- `tests/`: Test suite covering data, logic, scoring, and integration flow.
- `uml/`: Diagrams for architecture, data flow, sequence flow, and design review.
- `utils/`: Shared business logic and UI helper modules.
- `utils/mini_llm/`: Rule-based explainable AI insight engine.
- `tmp_pptx_inspect/`: Temporary working directory for presentation generation and inspection.
