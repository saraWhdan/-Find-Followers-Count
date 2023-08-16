# Find Followers Count


Problem Link: [Find Followers Count](https://leetcode.com/problems/find-followers-count/description/?envType=study-plan-v2&envId=top-sql-50)

## Solution

```sql
SELECT user_id, COUNT(*) AS followers_count
FROM Followers
GROUP BY user_id;
