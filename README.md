# Hospital Data Warehouse

The project focuses on building a **Hospital Data Warehouse** to address challenges in hospital operations, particularly those faced by nursing staff.

## Project Overview

This project aims to improve operational efficiency at Services Hospital Lahore by developing a centralized data system for managing patient care, resource allocation, and hospital workflows.

### Key Objectives:
- Streamline patient data access.
- Enhance real-time resource availability.
- Improve cross-departmental coordination.
- Optimize staff scheduling and resource management.
- Enable data-driven decision-making through advanced analytics.

## Table of Contents
1. [Introduction](#introduction)
2. [Challenges](#challenges)
3. [Proposed Solution](#proposed-solution)
4. [Data Overview](#data-overview)
5. [Technical Details](#technical-details)
6. [Final Outcomes](#final-outcomes)
7. [Usage](#usage)
8. [License](#license)

---

## Introduction

**Services Hospital Lahore** is one of the largest public healthcare facilities in Lahore, Pakistan, providing services to thousands of patients daily. The hospital faces challenges in managing high patient loads, fragmented data systems, and manual workflows.

---

## Challenges

1. Lack of integrated data systems leading to fragmented patient records.
2. Overburdened resources and staff due to high patient loads.
3. Inefficiencies in patient flow and resource allocation.
4. Manual reporting processes causing delays and errors.

---

## Proposed Solution

The proposed **Hospital Data Warehouse** leverages modern data warehousing and data mining techniques to:
- Integrate data from disparate sources (EHR, pharmacy, lab systems).
- Provide a unified view of patient care and hospital operations.
- Automate workflows and enhance data-driven decision-making.

---

## Data Overview

Key datasets utilized include:
- **Patients Dataset:** Details on admissions, discharges, and treatments.
- **Nurses Dataset:** Information on nurse shifts, training, and workload.
- **Medications Dataset:** Prescription and administration records.
- **Department Data:** Bed capacity, resource allocation, and workload.

---

## Technical Details

1. **Conceptual Modeling:**
   - Fact and dimension tables for hospital operations.
![fact tables](https://github.com/user-attachments/assets/a0be113f-9342-4243-bfeb-8b48af50356e)
![final sheet](https://github.com/user-attachments/assets/9056eb92-7a4f-4887-a4d4-f6d8156fa45f)
2. **ETL Process:**
   - Extract data from multiple hospital systems.
   - Transform data to clean, integrate, and enrich information.
   - Load data into a centralized warehouse.
![knime workflow](https://github.com/user-attachments/assets/c073490e-ad38-454e-88fe-a65582bacb45)
3. **Data Mining with KNIME:**
   - Workflows for data cleaning, transformation, and pattern recognition.
   - Decision tree models for classification tasks.
![decision tree](https://github.com/user-attachments/assets/874bb198-fb4e-4d0a-bcb3-fdae70056746)
4. **Visualization with Power BI:**
   - Interactive dashboards for resource allocation, patient flow, and workload analysis.
![medication](https://github.com/user-attachments/assets/2b8119c5-e6c0-4932-a6d9-00f553b415d6)
![nurse and patient per care type](https://github.com/user-attachments/assets/dc36467d-28b9-4bfb-8802-6630a4abe073)
![patient and bed capacity by department](https://github.com/user-attachments/assets/e04f85e9-5f59-4937-84f3-8a46d430bb40)
![patient and nurse by department](https://github.com/user-attachments/assets/c375cd10-9a07-49b9-8b51-de4f06a206e1)
![patient and nurse by shift](https://github.com/user-attachments/assets/5e03adda-bf8c-41fc-97bd-258931e5f62b)
![bed capacity required by hospital](https://github.com/user-attachments/assets/359719eb-371f-492b-8fb2-bc6d4f4a43a6)

---

## Final Outcomes

1. **Staff Allocation:**
   - Improved nurse-to-patient ratios.
   - Optimized shift schedules.
2. **Resource Optimization:**
   - Balanced bed capacity across departments.
   - Efficient medication management.
3. **Long-Term Planning:**
   - Predictive analytics for demand forecasting.
   - Streamlined cross-departmental coordination.

---

## Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/moaviamahmood/hospital-data-warehouse.git
