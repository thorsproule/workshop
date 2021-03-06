## Geospatial Data Methods for Tracking Migration in the Caribbean After a Natural Disaster

### By Thor Sproule

#### Introduction	

When natural disasters strike in developing countries, there is a substantial amount of migration away from impacted areas. There are several factors that influence the movement patterns of affected citizens. Different economic and social elements play a role in how a person will move following a disaster. Because of this movement, it becomes increasingly difficult to find dispersed persons and provide them with any kind of aid. By finding suitable methods to accurately track various populations, locations and migration habits can be tracked, as well as, improving upon the distribution of aid efforts.	

In the context of the Caribbean, these methods play an important role. The Caribbean is a hot spot that is plagued by natural disasters such as hurricanes or earthquakes and these natural disasters affect much of the population. Because of all these disasters, many people are forced to migrate to other places in the Caribbean or to countries like the United States. Using cell phone data allows for Caribbean citizens’ movements to be tracked in an easy fashion. To better understand the movements of the population, the radius of gyration can be used to discover how many of the Caribbean people move. The radius of gyration measures the sequence of which cell phone towers a person goes by in order to calculate that person’s trajectory. Along with the radius of gyration, we can also use a Twitter Streaming Application Programming Interface to see the movement of people by using geotagged Twitter data. The Streaming API calculates movement pre- disaster and compares it to the location of tweets following the disaster. 

Throughout my research I am asking how different demographics in the Caribbean move in response to natural disasters. The methods I am using will allow for me to analyze the movement of Caribbean people. These methods are used to see where people move in a daily routine and then can be compared to movements after a natural disaster which would differ from their normal movements. I also believe that my research falls more into the category of an exploratory inquiry. I feel that this type is appropriate because I have focused on how the process of tracking migration has developed. I have also come up with sub- questions to my research such as how can we gather cell phone data from older generations of people who are less adept at or less likely to use technology. 

#### Method 1: Radius of Gyration	

In Lu et al. the radius of gyration is used in calculating the movement of Haitian people following the 2010 earthquake there. The radius of gyration is helpful in determining the movements of people because it calculates the trajectory of a person based on their proximity to certain cell towers.

 ![img](https://lh5.googleusercontent.com/nWzM4Gp8QDLN3ccJmIJ2u6bWTKiRrVFLOe2_BL53hHau6l27iyvPyq24hEc3t76Y5CdR1AfAIW-_X3RJ8FM3DtWbJ73DNOgcQgY58J6UbOi7I-LWvKU70aRGVKWsXv_qFF8_4SnZ)

By using this formula we know that t is the sequence of how a person visits each cell tower and that r(t) is t’s location. Once we know the locations and patterns of a person, their daily movement can be easily tracked. With this formula, we can see that a person who stays within a small area of space, even though they travel a long distance within that small area, will have a small radius of gyration. So in a stable environment, people would tend to follow the same trajectories as normal and it becomes easy to predict where they are moving. This information is useful because an increase in the radius of gyration shows that a person is traveling away from their normal movement patterns. In the context of Lu et al. we see that the average radius of gyration for Haitian people increased immediately following the earthquake. 

![img](https://lh5.googleusercontent.com/rXfvG81ez0iIZFxYtaJv2VkxiIHlRINRdRuNooSElOoaKQIstsrdfftUtxFg7B9-a_Jhuge-apxsOBmRH5gT7iDr73UXK6J4CNxi0Y8XAzoO8wGpBMjlSo350FcRROXRKVj7DX6j)

This graph shows the distributions of the radii of gyration for the time after the earthquake. We can see that the average radius of gyration is higher in the spring which was immediately after the earthquake. However, even with this increased radius of gyration, the authors determined that the movement of the people was still able to be predicted with accuracy (Lu, 2012).

#### Method 2: Twitter Streaming Application Programming Interface (API)	

The second method comes from Martin et al.’s research on using geotagged Twitter data to track the movement of Puerto Rican people following Hurricane Maria. In order for the data to be accurate, it had to be determined who was a citizen of Puerto Rico. By using location data, a user's home can be inferred from the median area of their tweets. Once Puerto Rican people are determined, the system reviews whether or not the accounts are active. After all the information on the accounts is gathered, tweets that have been geotagged are marked and the locations before and after the hurricane were taken into account.

![img](https://lh4.googleusercontent.com/RbZO7tJWI9RYKp9ktTb-LycFYKMyre0F6w8JV_dLx22nM-Xz0DIz1Dbfr3vEe6kJG07ivDdT5C6eY84NzjvhjlPuGViP-JPfwDJu2e-cnoWef5eZoTzFc-GtCBf3qv-_8l1sBGJC) 

By identifying the locations of Puerto Rican residents before the hurricane allows us to better track their migration after the hurricane. Using Twitter profiles also allows us to see the demographics of the population and better predict the habits and patterns different types of people make in response to a disaster. Things like age, race, and gender are easily found in profiles and helps to determine the population being studied. The authors conclude by saying that they believe that this method is best suited for complementing other methods to improve upon the accuracy as well as provide information much faster (Martin, 2020). 

#### Conclusion	

Throughout my research I have found that these two different methods are in fact similar. The radius of gyration and the streaming API are both used to help determine a person’s normal routine movements as well as how their movements change in response to a disaster. Both of these methods also deal with cell phones and CDR data so a correlation exists there. As already stated, the streaming API is thought to be more of a complementary method which could be used to complement the radius of gyration. Using these two methods together could enhance the speed and accuracy of tracking migration following a disaster. By improving upon these factors, Caribbean countries could make distributing aid more successful. I still believe that the problem with using a majority of methods and data dealing with cell phones is that there is a bias towards younger people. In Martin et al. it is even explicitly shown that the data corresponds with younger people. I still feel that the gap in my research is that there is not all encompassing data for all the different demographics.

#### References

Lu, X., Bengtsson, L., Holme, P. (2012). *Predictability of Population Displacement after the 2010 Haiti Earthquake*. Proceedings of the National Academy of Sciences. https://www.pnas.org/content/pnas/early/2012/06/11/1203882109.full.pdf 

Martin, Y., Cutter, S.L., Li, Z., Mitchell, J., Emrich, C. (2020). *Using Geotagged Tweets to Track Population Movements to and from Puerto Rico after Hurricane Maria*. Springer Nature. [https://link.springer.com/epdf/10.1007/s11111-020-00338-6?author_access_token=yQHVeJlHoW20V71pw1uqiPe4RwlQNchNByi7wbcMAY6hhwok6UPmiYCULDHi5nCOC9-zbS_ruSEbrdXP-I0aAsIkqkuYgYZd4v1BkXV0SYZQCf9wYdiWoeuRlpwMTdDMhOGlhrcHvbjT8sM_FTKw1A%3D%3](
