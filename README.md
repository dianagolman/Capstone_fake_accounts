# Capstone_fake_accounts
This is my independent project. The project was part of Springboard training program. 
I wanted to solve a common problem reported by many social media users in my previous research projects and was also identified in the media.
The model selected predicts whether an account is fake or not. The model was evaluated for accuracy and prediction abilities. Hopefully, this best model
will be applied in the industry as a solution for apps and social networks' common problems. A client might want to build a system that will use the model 
for identifying accounts using their activity features. 



The features that were used in this model selection:
pic           	Picture availability | Value 0 if the user has no profile picture, or 1 if has
link             	Link availability | Value 0 if the user has no external URL, or 1 if has
cap_zero_per  Percentage (0.0 to 1.0) of captions that has almost zero (<=3) length
no_image_per  Percentage (0.0 to 1.0) of non-image media. There are three types of 
                                    media on an Instagram post, i.e. image, video, carousel
loc_tag            Percentage (0.0 to 1.0) of posts tagged with location

class               2-class User classes : r (real/authentic user), f (fake user / bought  
                        followers)
posts_a           Number of total posts that the user has ever posted-trimmed
flw_a  		Number of followers-trimmed
flg_a   		Number of following-trimmed
likes_a            Engagement rate (ER) is commonly defined as (num likes) divide by (num 
                       media) divide by (num followers)- trimmed
hash_a            Average number of hashtags used in a post- trimmed
cap_avg_a        The average number of character of captions in media- trimmed
comment_r_a    Similar to ER like, but it is for comments- trimmed
post_interval_a   Number of total posts that the user has ever posted- trimmed.


