# Diamond Price Prediction

![Diseño sin título](https://github.com/wilsone24/Optimization-Project/assets/118389840/00704de8-ad2e-408e-b2c7-7f3410716ddd)


## Dataset selection

After examining many datasets from which a future model could be derived, we chose this one due to certain variables, such as the quantity of data it contains around 300,000 rows where valuable information can be extracted. This substantial amount of data allows for a more profound, clear, and optimal analysis of the problem. Additionally, it is known that ticket prices at airports pose a problem affecting millions of people every day, creating difficulties, whether economic or otherwise, for those accessing this service. Therefore, its impact on both the economy and the daily lives of individuals makes it a suitable dataset and problem to address. Similarly, the variables included in the dataset are well-known and easy to relate to when analyzing the problem. Finally, the data was collected in real-time through web scraping from a platform called Ease My Trip, a well-known travel agency that is frequently visited by many people daily. Addressing this issue could potentially result in a social benefit for all those individuals who wish to purchase or access this service at some point, enabling them to make the best decisions.

## Our Team

| ![Integrante 1](https://github.com/wilsone24/Optimization-Project/assets/118389840/1ad141ba-4520-4d3e-add6-724df3f272ce)  | ![Integrante 2](https://github.com/wilsone24/Optimization-Project/assets/118389840/92da7de6-a034-40f4-affa-2887ebc5fed3)  |
| --- | --- |
| **Data engineer**  Wilson Estrada Ortega is a student at the universidad del norte in the systems engineering program in seventh semester, graduated from biffi la salle school in 2020, his area of interest is focused on the management of big data, cloud computing and technology sales. He has concomiento in various programming languages but focuses mainly on python and sql for data manipulation. He is passionate about sports and learning new things. The role he will develop in the team will be a data engineer and will be one of the people in charge of data manipulation and data cleaning. | **Data engineer** Yuli Meza, 9th-semester of systems engineering at Universidad del Norte, completed her studies at Nuestra Señora de Lourdes School in 2019. With a profound interest in cybersecurity, she demonstrates proficiency in Java and Python programming languages. Her fascination extends to data analytics, showcasing a versatile skill set. In the team, Yuli plays a vital role as a data engineer, specializing in meticulous data manipulation and cleaning processes. Her diverse interests and skills contribute to the dynamic and collaborative environment within the team. |

| ![Integrante 3](https://github.com/wilsone24/Optimization-Project/assets/118389840/d1a88f04-6a50-42de-9387-6965a03343dd)  | ![Integrante 4](https://github.com/wilsone24/Optimization-Project/assets/118389840/d1a88f04-6a50-42de-9387-6965a03343dd)  |
| --- | --- |
| **Backend engineer** Felipe Benítez, a seventh-semester student at Universidad del Norte, graduated from nuevo colegio del prado, has a keen interest in backend development, databases, and distributed systems. With a passion for crafting robust solutions and learning from existent ones. Outside of the tech realm, Felipe enjoys expressing his creativity through drawing and has a particular fondness for manga. cleaning. | **Frontend engineer** Yordi González, a seventh-semester systems engineering student at Universidad del Norte, graduated from I.E.T.C. Francisco Javier Cisneros at 2020, who has some experience in backend development and database management. Proficient in Python, SQL, and relational databases. Dedicated to designing efficient systems to meet project goals. I am responsible for the visual part of the project emphasizing the user experience. |

## Visualizations

![graphs](https://github.com/wilsone24/Optimization-Project/assets/118389840/b730627f-6528-478d-a752-e4925849b160)


## Observations

Taking into account a first analysis and observing the dataset we can reach the following premises about the possible hypothesis.

- The ticket prices vary significantly between Economy and Business class, with one class having higher average ticket prices than the other.

  - Objective: Explore and assert a significant difference in average ticket prices between Economy and Business class within the airline industry.


- The ticket prices significantly vary depending on the departure and arrival times.

  - Objective: Understand whether specific times of the day contribute to variations in ticket pricing within the context of the airline industry.


- There is a significant correlation between the number of stops and ticket prices.

  - Objective: Determine if there is a significant correlation between the number of stops and ticket prices, aiming to understand if travel convenience influences variations in ticket pricing.

- The duration of the flight significantly impacts ticket prices, indicating a noticeable difference in average ticket prices based on varying flight durations.

  - Objective: Explore how the duration of the flight impacts ticket prices, with the goal of understanding how time spent in transit contributes to variations in ticket pricing.

- The timing of ticket purchase significantly affects ticket prices.

  - Objective: Investigate whether the timing of ticket purchases significantly affects ticket prices, specifically exploring the impact of last-minute ticket purchases on variations in pricing.

- The source and destination significantly influence ticket prices, indicating a substantial difference in average ticket prices when the source and destination are changed.

  - Objective: Explore the influence of source and destination on ticket prices, aiming to understand if changes in these geographical factors contribute to substantial differences in ticket prices.

![Matriz de correlación](https://github.com/wilsone24/Optimization-Project/assets/118389840/cf952684-999a-4dfd-baf5-8bac9e6194fe)

## hypothesis

Taking into account various observations, it is necessary to highlight the hypothesis that the working team has about the dataset.
Flight prices do not depend solely on one variable; instead, they are determined and influenced by multiple variables that collectively impact the price.
This is the hypothesis that we will be developing throughout the model with the aim of identifying which variables have a greater influence on flight prices and in what manner.

