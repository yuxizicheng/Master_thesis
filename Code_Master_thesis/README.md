# Understanding Marine Microbial Physiology Under Varying Temperatures and Carbon Sources

This project analyzes how environmental factors, such as temperature and carbon source, affect the physiology and metabolism of marine bacteria.

## Key Features & Analyses

### 1. Growth Rate Analysis
- Developed a **Python pipeline** to process bacterial growth curve data from plate reader experiments (Excel format, thousands of time-point entries).
- The pipeline **cleans and transforms raw data**, plots growth curves, and calculates **maximum growth rates** automatically using a sliding-window approach.
- Fitting empirical growth curve equations revealed how **marine bacterial cellular physiology** responds to environmental changes, providing insights for ecological predictions.

### 2. Metabolite Analysis
- Processed HPLC data (Excel) to track changes in metabolite levels over time, revealing bacterial metabolic preferences.
- Results indicate marine bacteria favor specific carbon sources and temperatures under controlled conditions.

### 3. Cell Size Analysis
- Fluorescent microscopy images were analyzed using **Fiji** to extract cell size measurements.
- Trends in cell growth were quantified under different environmental conditions, highlighting physiological adaptation patterns.

### 4. Chitin Degradation Studies
- Studied 96 marine bacterial strains, including **chitin-digesting strains**.
- Chitin, the second most abundant polysaccharide in oceans (from crustacean shells, shrimp, and zooplankton), serves as a crucial carbon and nitrogen source.
- Chitin-degrading bacteria break down chitin into **N-acetylglucosamine**, sustaining the microbial food web and supporting carbon and nitrogen recycling in marine ecosystems.

### 5. Data Modeling and Statistical Analysis
- Applied **growth curve modeling** (logistic regression with parameter tuning) and statistical analyses to uncover correlations between temperature, carbon sources, growth rate, metabolite excretion, cell size, and chitinase activity.
- Successfully identified underlying physiological trends in marine bacteria under varying environmental conditions.
