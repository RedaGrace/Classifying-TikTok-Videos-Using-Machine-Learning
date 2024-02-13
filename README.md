# Classifying TikTok Videos Using Machine Learning

**Overview**

The goal of this project was to create an XGBoost and random forest model to help identify claims and opinions. The final random forest model was performed with 99% accuracy. Based on the model, the video_view_count,	video_like_count,	video_share_count, and video_download_count were most influential in determining whether a TikTok video presents a "claim" or presents an "opinion".

The purpose of this model is to mitigate misinformation in videos on the TikTok platform. With a successful prediction model, TikTok can reduce the backlog of user reports and prioritize them more efficiently.


**Business Understanding**

TikTok users can report videos that they believe violate the platform's terms of service. Because there are millions of TikTok videos created and viewed every day, this means that many videos get reported—too many to be individually reviewed by a human moderator. Analysis indicates that when authors do violate the terms of service, they're much more likely to be presenting a claim than an opinion. Therefore, it is useful to be able to determine which videos make claims and which videos are opinions. Videos that are labeled opinions will be less likely to go on to be reviewed by a human moderator. Videos that are labeled as claims will be further sorted by a downstream process to determine whether they should get prioritized for review. For example, perhaps videos that are classified as claims would then be ranked by how many times they were reported, then the top x% would be reviewed by a human each day.

**Data Understanding**

The data consisted of approximately 19,382 observations and 12 features. Each row represents a distinct TikTok video that presents either a claim or an opinion and the accompanying metadata about that video. The features included information on the video duration, video transcription, views count, likes count, and author-verified status. The bar chart below shows the combination of claim status and verification status.
![]()





TikTok users have the ability to submit reports that identify videos and comments that contain user claims. These reports identify content that needs to be reviewed by moderators. The process generates a large number of user reports that are challenging to consider promptly. 

I am working on the development of a predictive model that can determine whether a video contains a claim or offers an opinion. With a successful prediction model, TikTok can reduce the backlog of user reports and prioritize them more efficiently.
   
Attached:
 - PACE Strategy Document to plan the project that considers the audience members, teammates, key milestones, and overall project goal. The PAC Strategy Document
   * Is relevant to the project goals and related to data science.
   * Demonstrates our understanding and assessment of the business scenario.
   * Communicates the reasoning behind our decisions to pair PACE stages with specific tasks.
     
 - Project proposal for the data team. The project proposal
   * Clearly communicate the overall project goal 
   * Identify key tasks, milestones, and stakeholders
     
 - Python notebooks for each stage of the PACE strategy.

 - Executive summary which will keep our teammates at Automatidata informed of our progress. 
    
**Note**: The story, all names, characters, and incidents portrayed in this project are fictitious. No identification with actual persons (living or deceased) is intended or should be inferred. And, the data shared in this project has been created for pedagogical purposes. 
