# Crawling-Instagram

Aty Lestari Kristanto         1313617013    Ilmu Komputer 2017 <br>

Candra Febrian Tri Pambudi    3145162479    Ilmu Komputer 2016


# Install

1. Pastikan browser Chrome telah ter-install
2. Download <a href="https://sites.google.com/a/chromium.org/chromedriver/">chromedriver</a> dan pindahkan ke dalam folder : <code> ./inscrawler/bin/ </code>
3. Install Selenium : <code> pip install -r requirements.txt </code>
4. <code> cp inscrawler/secret.py.dist inscrawler/secret.py </code>


# Usage

Untuk mengetahui jumlah posting, jumlah followers, jumlah following gunakan :
<code> python crawler.py profile -u cal_foodie -o ./output </code> <br>

Untuk mengetahui like, tag, comment gunakan : 
<code> python crawler.py posts_full -u cal_foodie -n 10 -o ./output --fetch_likers --fetch_likes_plays </code>
