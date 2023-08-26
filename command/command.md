# Kumpulan Command

profile.biography #print biography nya
profile.get_saved_posts() #harus login - dapetin saved post nya
profile.biography_hashtags #print hashtag yg ada di bio
profile.get_similar_accounts()
profile.biography_mentions
profile.get_tagged_posts()
profile.blocked_by_viewer
profile.has_blocked_viewer
profile.business_category_name #categori akun bisnis IG nya
profile.has_highlight_reels
profile.external_url #url pada bio
profile.has_public_story
profile.followed_by_viewer
profile.has_requested_viewer
profile.followees #jumlah mengikuti
profile.has_viewable_story
profile.followers #jumlah followernya
profile.igtvcount
profile.follows_viewer
profile.is_business_account
profile.from_id(
profile.is_private
profile.from_iphone_struct(       
profile.is_verified
profile.from_username(             
profile.mediacount
profile.full_name #full name nya      
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