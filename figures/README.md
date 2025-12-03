# PSL Intensity Analysis Report

## Analysis Overview
- Date: 2025-12-03
- Author: Terence Makuvise
- Data file: psl_data.csv
- Total observations: 24
- Total subjects: 12

## Statistical Methods
1. **One-way ANOVA** for each site (infection, distant)
2. **Tukey HSD** post-hoc tests for genotype comparisons
3. **Mixed ANOVA** for genotype × site interactions
4. **Bonferroni-corrected** pairwise comparisons
5. **Statistical assumptions checking** (normality, homogeneity, outliers)

## Key Files Generated

### Visualizations
1. `psl_main_effects.png` - Main effects with 95% CIs and Tukey HSD
2. `psl_genotype_comparisons.png` - Per-site genotype comparisons
3. `psl_paired_analysis.png` - Paired measurements analysis
4. `psl_comprehensive_dashboard.png` - All results in one figure

### Data Tables
1. `psl_analysis_tables.xlsx` - All statistical tables in Excel format
2. `descriptive_statistics.csv` - Descriptive statistics
3. `pairwise_genotype_site_results.csv` - Pairwise comparisons
4. `mixed_anova_results.csv` - Mixed ANOVA results
5. `statistical_assumptions.csv` - Assumptions checking results

### Publication-ready Outputs
1. `descriptive_stats_latex.txt` - LaTeX table for manuscript
2. `analysis_metadata.json` - Complete analysis metadata

## How to Use This Analysis
1. Check `analysis_metadata.json` for complete analysis details
2. Use figures for presentations/publications
3. Reference tables for statistical results
4. Review assumptions checking for statistical validity

## Statistical Notes
- All p-values < 0.05 considered statistically significant
- Effect sizes (η²) interpreted as: <0.01 trivial, <0.06 small, <0.14 medium, ≥0.14 large
- 95% confidence intervals shown on all plots
- Bonferroni correction applied for multiple comparisons

## Contact
For questions about this analysis, contact: Terence Makuvise
