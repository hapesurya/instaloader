# Kumpulan Command

profile.biography
profile.get_saved_posts()
profile.biography_hashtags
profile.get_similar_accounts()
profile.biography_mentions
profile.get_tagged_posts()
profile.blocked_by_viewer
profile.has_blocked_viewer
profile.business_category_name
profile.has_highlight_reels
profile.external_url
profile.has_public_story
profile.followed_by_viewer
profile.has_requested_viewer
profile.followees
profile.has_viewable_story
profile.followers
profile.igtvcount
profile.follows_viewer
profile.is_business_account
profile.from_id(
profile.is_private
profile.from_iphone_struct(       
profile.is_verified
profile.from_username(             
profile.mediacount
profile.full_name                  
profile.own_profile(
profile.get_followed_hashtags()    
profile.profile_pic_url
profile.get_followees()            
profile.profile_pic_url_no_iphone
profile.get_followers()            
profile.requested_by_viewer
profile.get_igtv_posts()           
profile.userid
profile.get_posts()                
profile.username
profile.get_profile_pic_url()

## Contoh

import instaloader

L = instaloader.Instaloader()
profile = instaloader.Profile.from_username(L.context,'your_instagram')

#untuk melihat jumlah post
profile.mediacount

#selamat bereksperimen ^^