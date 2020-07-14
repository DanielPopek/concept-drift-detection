# Concept drift detection 

The attached .csv files in the /data folder contain 10,000 instances of numeric values ​​from certain distributions - each file comes from a different generator.

The aim of this project was to elaborate a method of indicating concept drfit point 
## Assumptions

1.  Like in data streams it is not possible to remember the whole string - it is possible to remember only part of it (e.g. windows) or to sum it up in a different way 
2. Development of a mechanism that detects concept drift, and more specifically suggests that new instances begin to come from a different distribution and inform the user about this fact (with additional information at which element it was detected

The mechanism should be one - each of the three files should be parsed with it.

## Outcomes
- The Page-Hinkley algorithm seems to be the best
- In some cases, combined ADWIN and Page-Hinkley algorithms achieve better results, sometimes worse than Page-Hinkley
- Detection of distribution list leader change seems to be too sensitive
- Leaderboard change detection seems to give satisfactory results
- Detection of an increase in the error of the top distributions from the list seems to be too insensitive to changes

