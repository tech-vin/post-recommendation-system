## Task as Follows:
You have to build a Recommendation System, recommendingthe items based on the following.
1. Content Based Filtering
2. Collaborative Filtering

End result should be a system that.
* Recommend posts for the given user.
* Recommend similar posts for the given post

## Dataset Details
### There are 3 files.
* users.csv - <i>Users dataset containing user's details like name, id, gender etc.
* posts.csv - <i>Post dataset containing posts details like title category etc.
* views.csv - <i>Views dataset contains the mapping which user views which post(s).


### Users
- post_id: a unique alphanumeric id of the user (string)
- name: Name of user (string)
- gender: Gender of user (male | female)
- academics:  Education of the use (undergraduate |graduate)

### Posts
- post_id: a unique alphanumeric id of the post (string)
- title: Title of the post (string)
- category: Category of the post (string)
- post_type: Type of the post (blog | artwork | skill| project)

### Views
- user_id: a unique alphanumeric id of the user (string)
- post_id: a unique alphanumeric id of the post (string)
- timestamp: timestamp of when user viewed the post(ISO time format)
