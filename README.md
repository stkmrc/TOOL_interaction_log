## Instructions

You can cite our work using the following reference:
DOI: 10.1234/example.doi

To reproduce, please create an _input_ folder and place inside **event_log.csv** from [here](https://zenodo.org/records/10377466).

The **event_log_analysis.Rmd** Markdown contains the algorithmic generation of an interaction log from the event log.
The steps of the generation are visualized in the diagram below.

The **summary_and_comparison_pipeline.Rmd** Markdown contains the comparison to interactions logs created by using Gemini models.

![Logo](pipeline_visualization.svg)

# R Package Management

This project uses the `renv` package for dependency management. Run `renv::snapshot()` to capture the state of R packages in your project and create a `requirements.R` file.