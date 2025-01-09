﻿this is the like of published documentation of youtubeApi = https://documenter.getpostman.com/view/39867665/2sAYQUptZY 

# YouTube-Inspired API  

A MongoDB-based API for managing users, videos, comments, playlists, and subscriptions in a YouTube-like platform.  

---

## **MongoDB Collections**  
1. **Users**: Stores user profiles and channel details.  
2. **Videos**: Manages video data.  
3. **Comments**: Tracks comments on videos.  
4. **Playlists**: Stores user-created playlists.  
5. **Subscriptions**: Tracks user subscriptions.  

---

## **Tasks for MongoDB Initialization**  
Run the following commands to populate the database:  

### **Users Collection**  
```javascript
db.users.insertMany([...]); // Example data provided in the full documentation
