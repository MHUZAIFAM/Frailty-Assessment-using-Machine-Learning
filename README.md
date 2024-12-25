# Frailty-Assessment-using-Machine-Learning
Applying Machine Learning Algorithms on Frailty Assessment Data
There are 6 total Tests, each test performed three times
- Seated Forward Bend Test
- Functional Reach Test
- Grip Strength Test
- Walking Speed Test
- Timed Up and Go Test
- Standing on One Leg with Eye Open Test


## Seated Forward Bend Stretch (Flexibility)

### Age-Specific Averages and Flexibility Labels
| Age (years) | Male (cm) | Female (cm) | Flexibility Labels                    |
|-------------|-----------|-------------|---------------------------------------|
| 60-64       | 37.9      | 41.68       | > Average: Good Flexibility <br> < Average: Reduced Flexibility |
| 65-69       | 37.68     | 40.67       | > Average: Good Flexibility <br> < Average: Reduced Flexibility |
| 70-74       | 36.03     | 39.77       | > Average: Good Flexibility <br> < Average: Reduced Flexibility |
| 75-79       | 34.81     | 37.93       | > Average: Good Flexibility <br> < Average: Reduced Flexibility |

### Best Reading
- **Best Reading**: Maximum reading recorded during the test.

### Advice
- If flexibility is reduced, consider flexibility improvement exercises.

## Functional Reach Test (Balance)

### Balance Assessment and Risk Levels
| Measured Distance (cm) | Risk Level         |
|-------------------------|--------------------|
| >30                    | Pass              |
| 25-30                  | Pass              |
| 20-25                  | Moderate Risk     |
| <20                    | High Risk         |
| <18.5                  | High Risk         |
| <15                    | High Risk         |

### Guidelines
- **Pass**: Measured distance is greater than 30 cm or between 25-30 cm, indicating good balance.
- **Moderate Risk**: Measured distance is between 20-25 cm, suggesting the need for balance improvement exercises.
- **High Risk**: Measured distance is below 20 cm, indicating a significant risk of balance issues.
- **Recommendation**: Consider immediate intervention for balance and stability training if in the high-risk range.


## Grip of Hand (Strength)

### Age-Specific Averages and Strength Labels
| Age (years) | Male (kg) | Female (kg) | Strength Labels                    |
|-------------|-----------|-------------|------------------------------------|
| 60-64       | 42.85     | 26.31       | > Average: Good Muscle Strength <br> < Average: Low Muscle Strength |
| 65-69       | 39.98     | 25.20       | > Average: Good Muscle Strength <br> < Average: Low Muscle Strength |
| 70-74       | 37.36     | 23.82       | > Average: Good Muscle Strength <br> < Average: Low Muscle Strength |
| 75-79       | 35.07     | 22.49       | > Average: Good Muscle Strength <br> < Average: Low Muscle Strength |

### Best Reading
- **Best Reading**: The highest strength recorded during the test.

### Advice
- If muscle strength is low, consider strength training exercises to improve hand grip.

## Walking Speed at 5-Meter Walk (Ability to Walk)
| Time (s)   | Status                                      |
|------------|---------------------------------------------|
| <=5        | Normal                                      |
| >5         | Unable to cross the crosswalk              |
| >=6.2      | High Risk of Fall                          |

**Minimum Reading**: The shortest time recorded during the test.

## Time Up and Go (Ability to Move)
| Time (s)   | Status                                      |
|------------|---------------------------------------------|
| <11        | Normal                                      |
| >=11       | Musculoskeletal Disability                 |
| >=13.5     | Risk of Fall                               |
| >=30       | Assistance Required for Daily Activities   |

**Minimum Reading**: The shortest time recorded during the test.

## Standing on One Leg with Eyes Open (Equilibrium Ability)
| Age (years) | Target Time (s) | Risk Levels                                    |
|-------------|-----------------|------------------------------------------------|
| 60-79       | 70              | <20: Risk of Fall <br> <15: Risk of Locomotor Instability |
| 80+         | 10              | <20: Risk of Fall <br> <15: Risk of Locomotor Instability |

**Best Reading**: Maximum time recorded during the test.
