# Dataset

<code> python crawler.py profile -u cal_foodie -o./output </code><br>
<code> crawler.py <code> = file untuk menjalankan code <br>
  
Untuk mendapatkan data yang dibutuhkan dari user :<br>
<code> user_data = data["entry_data"]["ProfilePage"][0]["graphql"]["user"] </code><br>


Untuk mendapatkan jumlah postingan, jumlah follower, jumlah following gunakan : <br>
<code> "post_num": user_data["edge_owner_to_timeline_media"]["count"] </code> <br>
<code> "follower_num": user_data["edge_followed_by"]["count"] </code> <br>
<code> "following_num": user_data["edge_follow"]["count"] </code> <br>
