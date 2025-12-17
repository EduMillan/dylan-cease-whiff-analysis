# Dylan Cease (2024): Pitch Usage and Whiff% Analysis

## Objective
This project analyzes the pitch repertoire of Dylan Cease during the 2024 MLB season, with a focus on identifying which pitches generate the highest rate of swings and misses (Whiff%) and how pitch effectiveness relates to usage.

## Data
- Source: MLB Statcast (Baseball Savant)
- Accessed via: pybaseball
- Season analyzed: 2024
- Pitcher: Dylan Cease

## Methodology
1. Downloaded pitch-by-pitch Statcast data for the 2024 season.
2. Classified swings and whiffs using official Statcast pitch descriptions.
3. Calculated:
   - Whiff% by pitch type
   - Usage (%) by pitch type
4. Visualized the relationship between pitch usage and whiff rate to evaluate pitch dominance versus situational effectiveness.

## Results
- The slider (SL) generated the highest Whiff% in Dylan Cease’s pitch mix during the 2024 season.
- The slider combines a high Whiff% with significant usage, indicating it functions as a primary put-away pitch rather than a situational offering.
- The four-seam fastball (FF) shows higher usage with a lower Whiff%, suggesting a setup role within the pitch mix.
- The curveball (CU) provides additional swing-and-miss value in more specific contexts.

## Conclusion
During the 2024 season, Dylan Cease’s slider emerged as the most effective pitch in terms of generating swings and misses. The combination of high effectiveness and meaningful usage suggests that a substantial portion of Cease’s success is driven by the quality and execution of this pitch, while the rest of the repertoire plays complementary roles within his overall pitching strategy.

## Tools
- Python
- pandas
- matplotlib
- pybaseball

## Visualization
![Pitch Usage vs Whiff%](figures/usage_vs_whiff_2024.png)
