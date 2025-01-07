# Bayesian Approach to Modeling Melanocytic Nevus Development in Colorado

This repository contains the R code and technical report for a project using Bayesian modeling techniques to asses the effect of nevus (mole) counts across different demographic and phenotypic subgroups in Colorado. The project objective was to conduct the necessary analyses and then write up a technical report to inform evidence-based decision making about effective components for comprehensive interventions, particularly for children approaching adolescence, when their responsibility for preventive behaviors increases.

## Data Source

This dataset contains the following variables:

| Variable/Field Name              | Description                                                   | Attributes/Labels                                                      |
|----------------------------------|---------------------------------------------------------------|------------------------------------------------------------------------|
| `Respondent Code Number`         | Unique identifier for each respondent                         | ID number                                                             |
| `oca2 status`                    | Genetic status for OCA2 gene                                  | `0` = gg, `1` = ga, `2` = aa, `9` = missing                          |
| `gender`                         | Gender of the respondent                                      | `1` = Female, `2` = Male                                              |
| `Hispanic`                       | Hispanic ethnicity status                                     | `0` = No, `1` = Yes                                                   |
| `molecount2004`                  | Number of moles recorded in 2004                              | Numeric                                                               |
| `molecount2005`                  | Number of moles recorded in 2005                              | Numeric                                                               |
| `molecount2006`                  | Number of moles recorded in 2006                              | Numeric                                                               |
| `molecount2007`                  | Number of moles recorded in 2007                              | Numeric                                                               |
| `molecount2008`                  | Number of moles recorded in 2008                              | Numeric                                                               |
| `eyecolor`                       | Eye color of the respondent                                   | `1` = blue/green/combo, `2` = light/dark brown, `3` = hazel           |
| `baseskincolor`                  | Skin color based on a continuous score                        | Higher values indicate darker skin                                    |
| `haircolor`                      | Hair color of the respondent                                  | `1` = blonde, `2` = red, `3` = brown, `4` = black                    |
| `number vacs birth thru 2005`    | Total number of waterside vacations from birth through 2005   | Numeric                                                               |
| `number vacs birth thru 2006`    | Total number of waterside vacations from birth through 2006   | Numeric                                                               |
| `number vacs birth thru 2007`    | Total number of waterside vacations from birth through 2007   | Numeric                                                               |

## Notes
- **Missing Data:** Values marked as `9` in `oca2 status` indicate missing data.
- **Skin Color Scale:** The `baseskincolor` variable uses a continuous scale where higher values correspond to darker skin tones.

This data dictionary is provided to help users understand the structure and meaning of the variables in the dataset.


## Tools and Technologies

The analyses and graphs were created using R and RStudio.

## Outputs

The technical report is available in PDF format and is designed for a scientifically knowledgeable public health official. The report includes descriptive statistics, graphical representations of the data, and statistical analyses of the relationships between different variables related to nevus (mole) counts.

## Instructions

To run the R code used in this project, clone the repository and open the CO_Nevus.RMD file in RStudio. The code is organized into code chunks to follow the format of the final report.

## Contributing

If you find any issues or have suggestions for improving this project, please submit an issue or pull request.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

