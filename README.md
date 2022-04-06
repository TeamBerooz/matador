# matador
goot bot


پیش نیاز های سورس:

 sudo apt-get update; sudo apt-get upgrade; sudo apt-get install tmux; sudo apt-get install luarocks; sudo apt-get install screen; sudo apt-get install libreadline-dev libconfig-dev libssl-dev lua5.2 liblua5.2-dev lua-socket lua-sec lua-expat libevent-dev make unzip git redis-server autoconf g++ libjansson-dev libpython-dev expat libexpat1-dev; sudo apt-get update; sudo apt-get install; sudo apt-get install upstart-sysv

و بعد

 wget http://luarocks.org/releases/luarocks-2.2.2.tar.gz;tar zxpf luarocks-2.2.2.tar.gz;cd luarocks-2.2.2 && ./configure; sudo make bootstrap;sudo luarocks install luasocket;sudo luarocks install luasec;sudo luarocks install redis-lua;sudo luarocks install lua-term;sudo luarocks install serpent;sudo luarocks install dkjson;sudo luarocks install lanes;sudo luarocks install Lua-cURL

در صورتی که از قبل پیش نیاز ها نصب بوده نیازی به نصب دوباره نمیباشد.

---------------------------------

آموزش نصب و اجرای سورس به طور کامل :

ابتدا وارد ربات @botfather میشوید و یه ربات api میسازید اینلاینش فعال کنید حتما
سپس رباتس که ساختید (api) توکن دار
فایل را از حالت فشرده خارج کرده و در سرور آپلود کنید
مشخصات خواسته  شده در مسیر زیر را کامل پر کنید

MaTaDoR/bot/Info-Bot.lua

سپس وارد سرور بشید و دستورات زیر را به ترتیب بزنید.                                                                                                                                                              
cd MaTaDoR
chmod +x Run
./Run install
./Run config
./Run logcli

سپس شماره خود را بدون فاصله وارد نمایید.
سپس برای لانچ کردن و راه اندازی هلپر دستور زیر را در سرور وارد کنید

killall screen
killall tmux
cd MaTaDoR
tmux
screen ./Run autocli
از سرور خارج دوباره وارد شوید                                                                                                                                                                                                
cd MaTaDoR
tmux
screen ./Run autoapi

سپس با‌ اکانت ربات cli ، ربات api که ساختید  را استارت کنید.
