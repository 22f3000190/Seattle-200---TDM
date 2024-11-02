###ABOUT THE PROJECT
- This script scrapes GitHub users in Seattle with over 200 followers and their repositories.
- It processes user and repository data, cleans company names, and saves the information in CSV format.
- The code uses Python and the GitHub API to retrieve up-to-date information.

### **How the Data Was Scraped**
I used the GitHub API's search and users endpoints. The code retrieves users with the search query 'location:Seattle followers:>200'. For each user, it fetches their profile details and up to 500 repositories using paginated requests.

### **Interesting Finding**
The most surprising discovery was that a significant number of high-profile developers in Seattle work at startups or have no public affiliation, which suggests a trend towards independent work or small-scale companies.

### **Recommendation for Developers**
Based on the analysis, it's crucial to maintain well-documented repositories with active wiki pages and projects. Repositories with clear documentation and collaboration features tend to attract more attention from the community.
