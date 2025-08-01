# 📊 Social Media Analytics

## 🧠 Problem Statement
The rise of social media platforms has brought a wealth of user-generated content and interactions. Businesses and organizations are eager to understand and leverage this data to:
- Improve their marketing strategies
- Understand customer sentiments
- Identify key influencers

The challenge lies in effectively analyzing and interpreting the vast amount of social media data available.

---

## 🎯 Objectives

1. **Data Collection and Storage**  
   Develop a robust database system to store:
   - Social media interactions
   - User profiles
   - Content engagement metrics
   - Network connections

2. **Analytics and Insights**  
   Create SQL queries to:
   - Analyze user engagement patterns  
   - Identify influencers  
   - Measure campaign impact  
   - Perform sentiment analysis  

3. **Optimization and Strategy**  
   Leverage historical data to:
   - Forecast future trends  
   - Optimize content strategies  
   - Tailor marketing to target demographics  

---

## 🗃️ Database Schema

### 1. Users
| Field | Description |
|-------|-------------|
| user_id | Unique identifier for each user |
| username | User's username |
| email | User's email address |
| date_joined | Date the user joined |

### 2. Posts
| Field | Description |
|-------|-------------|
| post_id | Unique post ID |
| user_id | Foreign key (from Users) |
| content | Text of the post |
| post_date | Date of the post |

### 3. Comments
| Field | Description |
|--------|-------------|
| comment_id | Unique comment ID |
| post_id | Foreign key (from Posts) |
| user_id | Foreign key (from Users) |
| comment_text | Comment text |
| comment_date | Date of the comment |

### 4. Likes
| Field | Description |
|--------|-------------|
| like_id | Unique like ID |
| post_id | Foreign key (from Posts) |
| user_id | Foreign key (from Users) |
| like_date | Date of like |

### 5. Followers
| Field | Description |
|--------------------|-------------------------|
| follower_id | Unique ID for each relationship |
| follower_user_id | User who follows |
| following_user_id | User being followed |
| follow_date | Date of follow action |

---

## 📚 SQL Queries

1. Retrieve all posts made by a specific user  
2. Count total comments on a particular post  
3. List users who liked a specific post  
4. Retrieve the most recent post by a user  
5. Count likes on a specific post  
6. Get usernames of users who commented on a post  
7. Retrieve posts by users followed by a specific user  
8. List users who have not made any posts  
9. Count likes given by a specific user  
10. Retrieve posts with more than 10 comments  
11. Find user with the most followers  
12. Users who liked all posts by a specific user  
13. User with the highest total likes on posts  
14. Users with no likes on their posts  
15. Posts with more comments than likes  
16. Users who liked their own posts  
17. Users who commented on posts by users they don’t follow  
18. Posts with likes above average  
19. Users who made at least 2 comments on the same post  
20. Users who liked posts of users they follow  
21. Users who liked every post by a specific user  
22. Post with highest comments for each user  
23. Users commenting on posts by users they follow  
24. Post with the highest number of likes  
25. Users who haven't liked any posts  

---

## 📎 Dataset

👉 **[Click here to download the dataset](#)**  
*Note: If any required feature is missing, add sample data.*

.

---

