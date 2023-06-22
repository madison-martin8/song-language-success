# Song Language and Success in the US Music Industry

A personal data science project that aims to see if including non-English-language lyrics in popular music in the US correlates with various measures of success.

## Installation Instructions

This project was completed using R 4.3.0 and R Studio as the editor.

### Packages

-   readr
-   tidyr
-   ggplot2
-   tidyverse
-   dplyr
-   apaTables
-   broom

### Data Sources

-   Spotify
-   Billboard Hot 100 from Billboard
-   Radio Plays from Chartmetric (behind a paywall, but included in the final combined csv here)

## Results

The main finding of this project is that when controlling for audience preference (as evidenced by Spotify streams), songs with non-English lyrics received less support from the music industry in the form of radio plays. Specifically, a multiple linear regression analysis on popular songs in 2020 demonstrated that songs get 19 less radio plays per week for every 1% increase of non-English lyrics, even when controlling for audience popularity and support.

## License

This is a modified form of an original project completed for credit by myself at the University of Chicago in 2021. For the full original project paper, please contact me. - MIT License
