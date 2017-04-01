# Quake Mega Team-Fortress CE
#COMPILES and has change team bug

The compiled qwprogs.dat is included in the fortress.zip along with the server config scripts. The server configs are setup to run with any modification, though you may want to change the server name and rcon to somthing. (head kick will cause the server to crash after some time, so it's turned off, because it's useless for a CE server)

unzip fortress.zip -d /mvdsv-0.40/smpmvdsv/

To compile MEGA TEAM FORTRESS (GMQCC is included for raspberry pi and odroid)

git clone git://github.com/graphitemaster/gmqcc.git

cd gmqcc

make

copy the compiled gmqcc into the MegaTF_ClanEdition folder

sudo chmod -R 777 MegaTF_ClanEdition

cd MegaTF_ClanEdition

./gmqcc -std=fteqcc -O3
