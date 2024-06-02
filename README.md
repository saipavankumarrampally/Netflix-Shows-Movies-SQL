# Netflix-Shows-Movies-SQL

Tools Used: Excel, Oracle SQL, Power BI



Business Problem: Netflix wants to gather useful insights on their shows and movies for their subscribers through their datasets. The issue is, they are working with too much data (approximately 82k rows of data combined) and are unsure how to effectively analyze and extract meaningful insights from it. They need a robust and scalable data analytics solution to handle the vast amount of data and uncover valuable patterns and trends.

How I Plan On Solving the Problem: In helping Netflix gather valuable insights from their extensive movies and shows dataset, I will be utilizing SQL and a data visualization tool like Tableau to extract relevant information, and conduct insightful analyses. By leveraging SQL's functions, I can uncover key metrics such as viewer ratings, popularity trends, genre preferences, and viewership patterns. Once the data has been extracted and prepared, I will leverage Tableau to present the findings. This will allow for interactive exploration of the data, enabling stakeholders at Netflix to gain actionable insights through visually appealing charts, graphs, and interactive visualizations. I plan on creating a dynamic dashboard in Tableau that enables users to delve into specific movie genres, viewer demographics, or geographical regions.


## Questions I Wanted To Answer From the Dataset:

### 1. What were the top 10 movies according to IMDB score?
![ray-so-export](https://github.com/saipavankumarrampally/Netflix-Shows-Movies-SQL/assets/48781737/194c5174-6dad-437a-9da4-7d47e858fd16)

### 2. What were the top 10 shows according to IMDB score?
![ray-so-export (1)](https://github.com/saipavankumarrampally/Netflix-Shows-Movies-SQL/assets/48781737/abfd6545-96d1-47c9-8e83-890e7a7ff6d4)

### 3. What were the bottom 10 movies according to IMDB score?
![ray-so-export (2)](https://github.com/saipavankumarrampally/Netflix-Shows-Movies-SQL/assets/48781737/6ceec0c0-d1e7-40d2-80cf-7533400bbfd4)

### 4. What were the bottom 10 shows according to IMDB score?
![ray-so-export (3)](https://github.com/saipavankumarrampally/Netflix-Shows-Movies-SQL/assets/48781737/ea86c208-1806-481a-a65a-ceaf93183657)

### 5. What were the average IMDB and TMDB scores for shows and movies?
![ray-so-export (4)](https://github.com/saipavankumarrampally/Netflix-Shows-Movies-SQL/assets/48781737/a9eb932c-51db-4d49-b2f6-c780359f6499)

### 6. What were the 5 most common age certifications for movies?
![ray-so-export (5)](https://github.com/saipavankumarrampally/Netflix-Shows-Movies-SQL/assets/48781737/c3417834-7ab9-4a93-8a78-3ad5bc3a1569)

### 7. What were the top 3 most common genres in movies and shows?
![ray-so-export (6)](https://github.com/saipavankumarrampally/Netflix-Shows-Movies-SQL/assets/48781737/f094800d-36da-40c4-8030-eef0d139be90)

### 8. Production countries with the most movies and shows?
![ray-so-export (7)](https://github.com/saipavankumarrampally/Netflix-Shows-Movies-SQL/assets/48781737/3c0ef8dd-eaaa-4952-acb4-f717ca28306e)

### 9. What are top 10 shows with most seasons?
![ray-so-export (8)](https://github.com/saipavankumarrampally/Netflix-Shows-Movies-SQL/assets/48781737/80f6d535-8bca-4a7d-817f-84d32f674fdf)

### 10. Calculating the average runtime of movies and TV shows?
![ray-so-export (9)](https://github.com/saipavankumarrampally/Netflix-Shows-Movies-SQL/assets/48781737/91fa5c66-c476-47c2-8229-5ca3ee6ec6c4)

By analyzing the frequency of genres, we can gain a better understanding of the content that dominates the platform and the preferences of its audience. Starting with movies, the first query reveals the top 10 most common genres. Comedy emerges as the most popular genre with a total of 384 movies, reflecting its widespread appeal. Following closely behind are documentation with 230 movies and drama with 224 movies, indicating the significance of these genres in Netflix's movie collection. Combinations of genres also feature prominently, with comedy + documentation and comedy + drama occupying the fourth and fifth positions respectively. The presence of drama + romance, drama + comedy, and comedy + romance further emphasizes the audience's likeness for movies that blend multiple genres. These findings highlight the diverse range of movie genres available on Netflix and the platform's commitment to catering to a wide array of preferences.

Shifting the focus, the second query presents the top 10 most common genres for shows. Reality takes the lead with 113 shows, showcasing the popularity of this genre among Netflix viewers. Drama follows closely behind with 104 shows. Comedy and documentation also emerge as prevalent genres with 100 shows each. Similar to movies, combinations of genres such as comedy + drama and drama + romance are present, indicating viewer interest in multi-genre shows.

Combining the results from both movies and shows, the third query provides an overview of the top three most common genres overall. Comedy takes the lead with a total of 484 entries, reaffirming its position as a very popular genre among Netflix subscribers. Documentation follows closely behind with 329 entries, reflecting the popularity of informative content. Finally, drama secures the third spot with 328 entries. Overall, these findings shed light on the genres that dominate Netflix's library, showcasing the platform's efforts to cater to a diverse range of viewer preferences.

Conclusion
By exploring various aspects of the dataset, a comprehensive understanding of Netflix's content landscape was gained. The analysis revealed the top 10 and bottom 10 movies and shows based on their IMDB scores, which highlighted the titles that garnered high praise and those that received lower ratings. This information can assist viewers in making informed choices and highlight areas for potential improvement in content quality. The examination of movies and shows distributed across different decades showed significant shifts in content availability over time. Notably, the dataset showcased a substantial increase in offerings from the 2000s onwards, emphasizing Netflix's commitment to featuring newer content that resonates with current trends and audience preferences.

Age certifications played a crucial role in the dataset, impacting both the average IMDB scores and the distribution of movies and shows. The analysis revealed audience preferences for specific age certifications, with TV-14 garnering the highest average score, suggesting its high popularity among viewers. Furthermore, the different age certifications also showed the diverse range of content available on Netflix. Finally, the exploration of the most common genres in Netflix's library provided insights into viewer preferences and content distribution. Comedy emerged as the dominant genre across both movies and shows, followed by documentation and drama. Combinations of genres were also frequent, highlighting the audience's appreciation for multi-genre content.






