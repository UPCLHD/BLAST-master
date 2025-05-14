# Preprocessing from raw data
- The following preprocessing steps can be quite tedious. Please post issues if you cannot run the scripts.

- datasets: [Amazon](http://jmcauley.ucsd.edu/data/amazon/links.html)  
-- Rating file in `Files/Small subsets for experimentation`  
-- Meta files in `Per-category files`, [metadata], [image features]  

There has been an issue with the dataset site lately, 
as it automatically redirects to an updated version of the dataset. 
Keep pressing `ESC` to stop the redirecting action.

## Step by step
1. get item prompt - `python generate_item_review.py`
2. get item profile - `python LLM_generate_item_profile.py`
3. get user prompt - `python genetate_user_prompt.py`
4. get user profile - `python LLM_generate_user_profile.py`
5. Encoding text features - `python item_profile_embeding.py`
6. Encoding image features - `python user_profile_embeding.py`

