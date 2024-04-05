
# Group 3 MIST 4610 Group Project 1

# Team Member Names:
Ellis Barton  
Lucas Hoffmann  
Jackson Kelley  
Fumi Ogundare

# Project Overview:

Our team has developed a comprehensive Soccer Club Management System aimed at enhancing the club's efficiency, performance, and reputation across various facets, including player management, team operations, financial tracking, facility utilization, community engagement, fan interaction, and marketing activities. This system serves as a robust tool for decision-making, resource allocation, and strategic planning within the organization.

# Problem Description

Our client is a professional soccer club competing in a top-tier league, aiming to enhance its performance, operational efficiency, and fan engagement to maintain competitiveness and achieve long-term success. The club boasts a rich history and a dedicated fan base but recognizes the need to modernize its operations and leverage data-driven insights to stay ahead in the highly competitive sports industry.

## Challenges:

### Player Performance Management: 

The club needs a system to track player performance metrics, injuries, and fitness levels to optimize training regimes, player selections, and tactics for each match.

### Match Scheduling and Venue Management: 

Efficient scheduling of matches and allocation of facilities is crucial for maximizing revenue, minimizing conflicts, and ensuring an optimal matchday experience for fans.

### Financial Tracking and Revenue Generation: 

Accurate tracking of team finances, revenue sources, and expenses is essential for effective budgeting, financial planning, and revenue generation strategies.

### Fan Engagement and Marketing: 

The club aims to deepen fan engagement through targeted marketing campaigns, fan interaction initiatives, and community outreach programs to build loyalty and support.

### Coaching Staff and Recruitment: 

Effective management of coaching staff and recruitment processes is vital for talent identification, development, and team cohesion.

## Objectives:

Develop a comprehensive Sports Club Management System that integrates player management, match scheduling, financial tracking, fan engagement, and coaching staff management functionalities.

Implement a robust data model to capture key entities such as players, matches, coaching staff, facilities, scouting, recruitment, fan engagement activities, and finances.

Provide querying capabilities to extract valuable insights regarding player performance, injury tracking, match scheduling, revenue generation, marketing effectiveness, and contract management.

Ensure the system is user-friendly, scalable, and adaptable to the club's evolving needs and technological advancements.

## Expected Outcomes:

Improved player performance through data-driven insights and optimized training programs.


Enhanced matchday experiences for fans through efficient scheduling and venue management.


Increased revenue streams and financial sustainability through effective financial tracking and revenue generation strategies.


Strengthened fan engagement and loyalty through targeted marketing campaigns and community outreach initiatives.


Enhanced recruitment processes and coaching staff management for talent identification and team cohesion.


By addressing these challenges and objectives, our Sports Club Management System will empower our client to streamline operations, optimize performance, and achieve sustainable success in the competitive world of professional soccer.

# Database Name: 

al_Group_21482_G3


# The Data Model:

![image](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/047d877d-afe8-412c-ab97-93e59a613fca)

This data model facilitates the efficient management of all aspects of the club, including player performance, team operations, financial management, facility utilization, community engagement, fan interaction, and marketing activities. It allows for better decision-making, resource allocation, and strategic planning to enhance the overall performance and reputation of the club.

# Relationships:  

# Players:

Players to Players_has_Matches: This shows a many-to-many relationship via an associative entity, meaning that players can participate in many matches, and each match can involve many players.


Players to Medical Records: a one-to-one relationship, as each player would have a unique medical record.


Players to Scouting and Recruitment: a one-to-many relationship, as each scout can be linked to many players.


# Matches:

Matches to Players_has_Matches: Many-to-many with players, as explained earlier.


Matches to Team Finances: A one-to-many relationship where one match can be related to multiple financial records.


Matches to Fan Engagement: a one-to-many relationship; one match could have multiple fan engagement activities.


Matches to marketing and Promotions_has_Matches: A many-to-many relationship with marketing and promotions campaigns.


Matches to Coaching Staff_has_Matches: This implies that coaching staff can be associated with many matches and vice versa, hence a many-to-many relationship.


# Coaching Staff to Coaching Staff_has_Matches:

Many-to-many relationships, as explained earlier.


# Facilities:

Facilities to Matches: a one-to-many relationship, indicating that one facility can host multiple matches.


Facilities to marketing and Promotions_has_Matches: Indicates a many-to-many relationship through the associative entity.


# marketing and Promotions:


# marketing and Promotions to marketing and Promotions_has_Matches: 

Many-to-many relationship as mentioned.

# Scouting and Recruitment:

Scouting and Recruitment to Players: As mentioned before, a one-to-many relationship.

# Youth Academy:

Youth Academy to Players: Suggesting that players can be a part of a youth academy, a one-to-many relationship.


# Data Dictionary:

![Players](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/83ec25bf-bed7-4f1a-b133-e64758d8f073)

![Coaching Staff](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/b7b75186-4396-4303-9792-126ed2756317)

![Matches](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/e5fd5767-877e-45eb-a4ef-8271af44f7f7)

![Medical Records](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/28030e18-b52c-46bd-aee2-8d204a1a0e09)

![Youth Acaademy](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/353f350d-1d13-461f-95bb-3c5bce94ceb2)

![Scouting and Recruitment](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/a6fc6eba-3054-4e5f-b1ed-c6c1afe1993f)

![Facilities](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/90eb1644-fbc4-4122-aeaa-cb8f9d6d1fa0)

![Fan Engagement](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/5bc4a4de-56c2-4394-bdf7-db8dedd7c5c6)

![Team Finances](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/bd677da7-4903-4ed3-a6d3-34feb528dbd3)

![Community Outreach](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/8a400825-8c2b-40d8-9646-116b78d35fe7)

![Coaching StaffMatches ](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/f164bde1-5def-43ea-bf77-18dd19ae444c)

![Player Match](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/9c10192b-e89e-4fc1-b565-bf030867405d)

![Marketing Promotions ](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/9cdb1a38-7dab-426d-aa78-30e0f34b65f5)

![Screenshot 2024-04-04 162622](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/bcf2d63d-340d-40fe-9a38-b846c90ddf62)

![Marketing Matches](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/93f1e339-33cf-4a2e-a353-be6bf5dc5d8d)


# Queries: 

![QueryDictionary](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/620c9bb0-dc20-451e-82dd-268eed35849d)

1. Query 1 retrieves the names and ages of players who have participated in matches and emerged victorious.

![image](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/5b59a5f1-d441-4e91-a4af-2c20ae88bccb)

Overall, Query 1 plays a crucial role in understanding player performance, shaping strategic decisions, and enriching the experience for both professionals and fans of the sport.

----------------------------------------------------------------------------------------------------------------

2. Query 2 lists the player's name, injury description, and the fitness

![image](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/79fad339-e26b-4fd4-a0f8-449596e2226c)

Overall, Query 2 plays a critical role in the holistic management of player health and performance, supporting injury prevention, rehabilitation, and informed decision-making within the sports organization.


----------------------------------------------------------------------------------------------------------------

3. Query 3 lists the Match Date of all the home games. 

![image](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/e9266bed-003f-4bcc-8c47-c2512b8faf45)

Overall, Query 3 plays a vital role in the operational, marketing, and strategic aspects of managing home games within a sports organization, ensuring effective planning, engagement, and success both on and off the field.



------------------------------------------------------------------------------------------------------------------

4. Query 4 lists the average age of all the players based on Nationality

![image](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/bddb89af-8b23-460d-a5c1-00a62b29307c)


Overall, Query 4 plays a crucial role in talent management, team composition, strategic planning, market analysis, competitive benchmarking, and performance analysis within a sports organization. It provides valuable data-driven insights that inform decision-making and drive success both on and off the field.

-------------------------------------------------------------------------------------------------------------------

5. Query 5 lists the Player’s name and counts the matches listed as the number of Matches played.

![image](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/a87f0dde-c54b-44a4-b51b-3b02f6db170d)

Overall, Query 5 plays a crucial role in player management, fan engagement, performance analysis, historical tracking, and media/marketing efforts within a sports organization. It showcases the achievements of top-performing players, fosters fan connection and loyalty, and informs strategic decision-making to drive success both on and off the field.

---------------------------------------------------------------------------------------------------------------

6. Query 6 lists the position, the number of matches that were wins

![image](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/f2d8964e-4546-435e-9464-3c4b978a264b)

Overall, Query 6 plays a crucial role in strategic planning, player development, tactical adjustments, performance evaluation, recruitment decisions, and fan engagement within a sports organization. It provides valuable data-driven insights that help teams optimize their chances of winning matches and achieving success on the field.

---------------------------------------------------------------------------------------------------------------

7. Query 7 lists the Revenue source and the sum of the amount as the total.

![image](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/7941067c-b0ce-4141-90f7-cb6c5974a7ce)

Overall, Query 7 plays a crucial role in financial management, strategic planning, performance evaluation, and stakeholder communication within a sports organization. It provides valuable insights into revenue generation and sustainability, supporting informed decision-making and driving long-term success.

---------------------------------------------------------------------------------------------------------------

8. Query 8 lists the amount of marketing campaigns for the individual matches whose opponents have “City” in their name.

![image](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/aff5c71e-6fe8-40e4-957d-afcc236a2e62)

Overall, Query 8 plays a crucial role in targeted marketing, fan engagement, revenue generation, competitor analysis, brand visibility, and data-driven decision-making within a sports organization. It helps maximize the impact of marketing efforts, foster fan connections, and drive success both on and off the field, particularly for matches against opponents with "City" in their name.


-----------------------------------------------------------------------------------------------------------------


9. Query 9 lists the players' names and positions, along with their contract start and end dates.

![image](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/ec0d1ac7-dd8f-4d88-a97b-0f454b8a023a)

Overall, Query 9 plays a crucial role in contract management, roster planning, salary cap compliance, player development, transfer negotiations, performance evaluation, and compliance within a sports organization. It provides valuable data-driven insights that inform strategic decision-making and ensure effective management of player contracts and positions across the organization.

----------------------------------------------------------------------------------------------------------------

10. Query 10 evaluates which players play best at away games by showing the amount of wins or draws they have achieved in away games.

![image](https://github.com/Jkelley7399/Project-1-Group-3/assets/158102955/da7fb37f-61b2-4dc3-947a-a486f377a7e6)

Overall, Query 10 plays a crucial role in player performance analysis, strategic player selection, opponent analysis, team confidence, fan engagement, data-driven decision-making, and player development within a sports organization. It provides valuable insights that inform strategic decision-making and drive success in away games, ultimately contributing to the team's overall performance and competitiveness.

------------------------------------------------------------------------------------------------------------------

# Final Deliverable:

The Soccer Club Management System developed by our team represents a significant milestone in optimizing the club's operations and fostering its growth and success. With its intuitive interface, robust data model, and powerful querying capabilities, the system empowers club administrators, coaches, and stakeholders to make informed decisions, streamline processes, and drive performance improvements across all aspects of club management.

## Benefits:

Enhanced Decision-Making: Access to comprehensive data and analytics empowers club stakeholders to make informed decisions regarding player selection, match scheduling, resource allocation, and strategic planning.

Improved Performance: By tracking player performance, injuries, and fitness levels, the system enables coaches to optimize training programs, tactics, and team compositions to enhance on-field performance and results.

Efficient Operations: Streamlined processes for match scheduling, facility management, scouting, recruitment, and financial tracking ensure efficient club operations and resource utilization.

Enhanced Fan Engagement: Through targeted marketing campaigns, fan interaction initiatives, and community outreach programs, the system helps foster stronger connections with fans, driving loyalty and support for the club.

Financial Management: Accurate tracking of team finances, revenue sources, and expenses enables effective budgeting, financial planning, and revenue generation strategies to ensure the club's long-term sustainability and growth.


