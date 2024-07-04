# Install and load the writexl package
if (!require("writexl")) install.packages("writexl")
library(writexl)

# Create the data frame with questions and sources
data <- data.frame(
  Question = c(
    "What are the primary green coffee bean exporting countries?",
    "Which countries have the highest production and export volumes of green coffee beans?",
    "What are the import/export policies for green coffee beans in these countries?",
    "Are there trade agreements or tariffs that influence import/export ease between these countries and the US?",
    "What are the average export prices of green coffee beans from these countries?",
    "Which countries are known for competitive pricing or aggressive marketing strategies?"
  ),
  Source = c(
    "FAOSTAT, International Coffee Organization (ICO)",
    "FAOSTAT, International Coffee Organization (ICO)",
    "USDA Foreign Agricultural Service (FAS), World Bank, International Trade Centre (ITC)",
    "USDA Foreign Agricultural Service (FAS), World Bank, International Trade Centre (ITC)",
    "International Coffee Organization (ICO), Trading Economics",
    "International Coffee Organization (ICO), Trading Economics"
  )
)
