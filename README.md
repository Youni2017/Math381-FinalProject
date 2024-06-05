# THE FORGOTTEN REFRIGERATOR @DM: INCREASING THE EXPOSURE OF PREPARED FOOD

---

## Project Overview

This project addresses the challenge of optimizing the layout of refrigerated items at District Market Alder (DM) to mitigate the impact of long queues during peak hours.

### Background

District Market Alder \(DM\) stands as the quintessential neighborhood grocery store, perfectly suited to meet the needs of the bustling university community. DM offers a wide variety of fresh products, ensuring top\-notch quality and flavor for its customers. Its full\-service deli provides chef\-prepared sides, salads, and hot meals, ideal for those seeking a quick and nutritious eating option. Additionally, DM offers an extensive range of household items, health and beauty products, frozen foods, and a large selection of snacks and cold drinks. Dedicated to providing convenience, exceptional quality, and a pleasurable shopping experience, DM serves as a vital resource for all its patrons. Our community partner, _Kiel Turner_, the General Manager of District Market Alder and Husky Grind Coffee, told us that running the DM dedicated to providing excellent service to students is not an easy task. There are always inevitable challenges encountered during operation.

Our project aims to address the inefficiencies observed during peak hours at DM, particularly focusing on the long queues composed of people waiting to buy the Freshly Prepared Food \(FPF\). These queues often obstruct customers from accessing popular items in the Refrigerator section during the lunch and dinner rush, potentially negatively impacting sales. For example, the frozen prepared food section in Refrigerator 1 \($R_1$\) has consistently been one of the most popular zones at DM . However, due to the layout at DM, $R_1$ is frequently blocked by the line of people queuing at the FPF section.

### Goal

Determine a placement of each item in the 4 refrigerators to increase the quantity of items sold per week by reducing the probability that costumers will be blocked by the line.

---

## Contents

### Data

**Our community partner generously provided the necessary initial data to support the development of our project, including weekly Average Transactions Listed by 30 Min and Sales Report Summary Grouped by Categories, Groups, and Menu Items.**

Initial data:

- `Spring Quarter.csv` \- weekly average transactions listed by 30 min

- `Spring Quarter Sales Category.csv` \- sales report summary 

**Here is the data after our processing:**

Modeling data:

- `Human_Traffic.csv` \- define peak hours

- `Ranks_for_items.csv` \- ranking of all items $t_i$ in 5 refrigerators and the average ranking of the refrigerator $\bar{T}$.
- `R1_config0.csv` \- $R_1$’s Menu Item under configuration $a = 0$.
- `R1_config1.csv` \- $R_1$’s Menu Item under configuration $a = 1$.
- `R2_config1.csv` \- $R_2$’s Menu Item under configuration $a = 1$.
- `R5_config1.csv` \- $R_5$’s Menu Item under configuration $a = 1$.
- `R1_config2.csv` \- $R_1$’s Menu Item under configuration $a = 2$.
- `R2_config2.csv` \- $R_2$’s Menu Item under configuration $a = 2$.
- `R5_config2.csv` \- $R_5$’s Menu Item under configuration $a = 2$.
- `arrangement_config1` \- One feasible way of arranging items

### Program File

Contains the python program that encodes our item placement model.

*  `placement.ipynb` - calculate the specific arrangement of items

---

## Acknowledgements

First, we would like to thank our community partner Kiel Turner for his support. Without him, this project would not have been possible. We appreciate his trust and his generous provision of ample data, which gave us the confidence to complete this project. We also extend our heartfelt gratitude to Prof. Sara Billey for her unwavering guidance, countless feedback sessions, and for witnessing the growth of this project with us. 

Additionally, we are grateful to our TA Tony Zeng for his feedback on our first draft, as well as to the Meany Hall and Center Table groups for their crucial feedback during the peer review phase. Most importantly, we want to thank everyone who provided feedback or encouragement during the poster session. Our deepest gratitude goes to all the aforementioned individuals, whose love and trust made this project better. Your feedback, much like this Refrigerator in our project, will forever remain unforgotten in our hearts.

<hr>

&copy; 2024 Zihan Chen, Young. Z, Kevin Huang, Jiapeng Ni

