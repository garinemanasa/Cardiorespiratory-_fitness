# Cardiorespiratory Fitness

## Project Overview
Cardiorespiratory fitness is determined by the body's ability to consume, transport, and utilize oxygen during dynamic exercise. One of the most popular and widely used methods to measure cardiorespiratory fitness is the maximal oxygen uptake (VO2max) test, which is typically measured during a graded exercise test.

## Dataset Description
The dataset contains cardiorespiratory measurements from graded cycle ergometer exercise testing. It includes data from 18 athletes representing 3 sports: fencing, kayak, and triathlon. Details of the athletes are as follows:
- First 10 athletes: Fencing
- Next 6 athletes: Kayak
- Last 2 athletes: Triathlon

## Dataset Definition
1. **ID**: A unique identifier for each participant in the study.
2. **Age**: The age of the participant in years.
3. **Weight**: The weight of the participant in kilograms.
4. **Height**: The height of the participant in centimeters.
5. **P_vt1**: The power output at the first ventilatory threshold during a graded exercise test.
6. **P_vt2**: The power output at the second ventilatory threshold during a graded exercise test.
7. **Sport**: The type of sport or activity the participant usually engages in.
8. **MaxHR**: The maximal heart rate calculated from the standard formula of 220 – age (in years).
9. **HRmax**: The maximum heart rate achieved by the participant during the graded exercise test.
10. **VO2max_abs**: The absolute value of maximal oxygen uptake (VO2max) measured during the graded exercise test in millilitres of oxygen per minute (mL/min).
11. **Powermax**: The highest power output achieved by the participant during the graded exercise test.
12. **HRrest**: The resting heart rate of the participant prior to the graded exercise test.
13. **Time**: The duration of the graded exercise test in minutes.
14. **Vo2inmL/Kg/min**: The steady-state oxygen uptake during the graded exercise test in millilitres of oxygen per kilogram of body weight per minute.
15. **Vo2inmL/Kg/min/2**: The steady-state oxygen uptake during the last 2 minutes of the graded exercise test in millilitres of oxygen per kilogram of body weight per minute.
16. **ATHR**: The anaerobic threshold heart rate, which is the heart rate at which the body transitions from primarily aerobic to primarily anaerobic metabolism during exercise.

## Tools Used
- **Data Cleaning**: Python
- **Data Analysis**: Tableau

## Data Analysis

![crfVO2](https://github.com/user-attachments/assets/77658d6e-fb14-4417-adad-bbc622b3030c)

- Elite athletes in these sports can have VO2max scores in the range of 50-70 ml/kg/min or higher.
- VO2max% is a measure of aerobic fitness level as a percentage of maximum oxygen uptake capacity.
- Standard deviation of RR interval (SDRR) is a measure of heart rate variability (HRV). Higher HRV, as indicated by a lower standard deviation of RR intervals, suggests better cardiovascular health.
- VO2max less than 35 may indicate low cardiovascular fitness and the inability to perform at a high level for extended periods of time.
- Participant IDs 1, 2, 7, 9, and 14 have low VO2max uptake.
- Participants IDs 17 and 18 have maximum VO2max uptake but are unable to perform for extended periods of time. So we extended our analysis further by calculating Cardiorespiratory Fitness Score.
- Participant IDs 3, 11, 12, 13, and 14 have good scores.
- The remaining participants have low scores, which may be due to factors such as a lack of regular exercise, poor nutrition, inadequate recovery, and other health issues.

## Conclusion
The comprehensive analysis of the athletes' cardiorespiratory data reveals significant differences across sports and individual participants. While triathlon athletes demonstrated the highest VO2max, their endurance capacities varied. A consistent relationship was observed between power output, weight, and heart rate in many participants. Despite variations, a majority of the participants showed room for improvement in their overall cardiovascular fitness, emphasizing the need for personalized training and recovery plans.

[View Interactive Dashboard](https://public.tableau.com/app/profile/manasa.garine/viz/CardioRespiratoryFitness_17422323855140/Story1?publish=yes)

