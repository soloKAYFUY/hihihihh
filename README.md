# hihihihh
sudo apt-get install postgresql-16 postgresql-client-16
Copy
Eski klasterni o’chirib tashlash:
sudo pg_dropcluster --stop 16 main
Copy
Eski klasterni yangilash:
sudo pg_upgradecluster 15 main
Copy
Yangilanmagan eski versiyani o’chirib tashlash:
sudo apt-get remove postgresql-15 postgresql-client-15
