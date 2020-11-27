cp sqlite3 /usr/bin
chmod 777 sqlite3
cp libsqlite3.so.0.8.6 /usr/lib
cd /usr/lib
ln -s libsqlite3.so.0.8.6 libsqlite3.so.0
ln -s libsqlite3.so.0.8.6 libsqlite3.so
vi /etc/init.d/rcS
最后一行加上  /yaokongqi/udp_92 &
cp ./server.db /yaokongqi
