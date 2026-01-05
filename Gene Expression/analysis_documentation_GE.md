# Scientific Question: Which genes show differential expression between Condition A and Condition B?

- **Data Description** - RNA-seq count matrix - Samples collected under
two experimental conditions - No time-to-event component

- **Preprocessing Steps**
  - Removal of low-count genes
  -  Library size
normalization
  - Log transformation for exploratory analysis

- **Statistical Approach**
   - Exploratory data analysis (PCA, clustering)
   - Differential expression testing using appropriate statistical models
   -  Multiple testing correction (FDR)

- **Assumptions**
   - Samples are independent
    - Counts adequately reflect gene expression
   - No major batch effects remain after QC

- **Outputs**
   - List of differentially expressed genes
   - Visualization of expression patterns
  - Summary tables for downstream interpretation

- **Limitations**
   - Limited sample size
  - Exploratory nature of the analysis
  - Results require biological validation
