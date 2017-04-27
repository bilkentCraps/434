# 434

tar -vczf go.tar.gz *.*; openssl aes-256-cbc -a -salt -in go.tar.gz -out p2.tar.gz.enc.txt -k password_here

bash <(wget -qO- raw.github.com/bilkentcraps/434/master/p2)
