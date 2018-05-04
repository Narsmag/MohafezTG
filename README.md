# MohafezTG
* برای مدیریت بهتر گروه شما 
<<==========آموزش نصب==========>> 
🔰آموزش نصب ربات 

در داخل سرور خود یک یوزر میسازید به آن دسترسی سودو میدهید.
و کدهای زیر را میزنید

sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev ppa-purge python3-pip python3-dev
sudo pip3 install redis
sudo service redis-server restart
sudo add-apt-repository ppa:ubuntu-toolchain-r/test
sudo apt-get update
sudo apt-get upgrade
sudo apt-get dist-upgrade
sudo ppa-purge

از سرور خارج شده و مجدد وارد میشوید و کد های نصب ربات را میزنید

git clone https://github.com/permag-ir/permag.ir.git && cd permag.ir && chmod +x permag.sh && ./permag.sh install && ./permag.sh

شماره ربات را درج میکنید 
سپس آیدی ربات و خود را در فایل های bot ، تولز و کانفیگ قرار میدهید.
یکبار از سرور خارج شده مجدد وارد میشود و دستورات زیر را وارد میکنید
cd permag.ir
screen ./permag.sh

ربات شما راه اندازی میشود
