# Games Metrics

Each game features unique, game-specific metrics meticulously crafted to enhance your training experience. These metrics are conveniently accessible in your dashboard for detailed analysis. In this section, we'll delve into these metrics and shed light on how they were gathered, offering valuable insights into your performance.

### Shared Metrics

**Heart Rate Monitoring:** Utilizing ANT+ connectivity, we seamlessly integrate heart rate monitoring across all games. Our in-house tool effortlessly detects and connects to compatible heart rate belts, eliminating the need for manual setup.

**Calorie Calculation:** Tracking calorie expenditure is paramount for gauging trainee progress. We prioritize this metric and implement a formula based on weight, height, age, and Basal Metabolic Rate (BMR) to ensure accurate calorie estimations.

$$

(Men) Calories/Minute
= \left( (Age \times 0.2017) - (Weight \times 0.09036) + (Heart Rate
\times 0.6309) - 55.0969 \right) \times Time /
4.184Calories/Minute=((Age×0.2017)−(Weight×0.09036)+(HeartRate×0.6309)−55.0969)×Time/4.184

$$

$$

(Women) Calories/Minute
= \left( (Age
\times 0.074) - (Weight \times 0.05741) + (Heart Rate \times 0.4472)
- 20.4022 \right) \times Time /
4.184Calories/Minute=((Age×0.074)−(Weight×0.05741)+(HeartRate×0.4472)−20.4022)×Time/4.184

$$

<aside>
💡 Reference:
Mifflin, M. D., St Jeor, S. T., Hill, L. A., Scott, B. J., Daugherty, S. A., & Koh, Y. O. (1990). A new predictive equation for resting energy expenditure in healthy individuals. The American J

</aside>

**Exercise Duration:** A fundamental metric shared across all games, exercise time is imported from the initial dashboard request. This metric is segmented to reflect the structure of the exercise session, including set durations, rest periods, and cooldowns.

**Heart Rate Trends:** Continuously monitoring heart rate over time, we capture data to generate insightful graphs. These visualizations allow for analysis of heart rate fluctuations during exercise, aiding in pinpointing moments of increased intensity or effort.

[**Target Heart Rate Zone](https://www.trainerplan.co/en/heart-rate-zones-calculator/):** To optimize training effectiveness, we track the target heart rate zone provided by the dashboard. This metric helps users gauge their exertion level and ensure they are working within the desired intensity range for optimal results.