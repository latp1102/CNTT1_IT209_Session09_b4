cd /mnt/d/IT209_Devops_Funmentals

mkdir -p Session09/b4

docker volume create easy-volume

docker volume ls

docker run --rm -v easy-volume:/data alpine sh -c "echo 'Luu tru du lieu Docker' > /data/test.txt"

docker run --rm -v easy-volume:/data alpine cat /data/test.txt

docker run --rm -v easy-volume:/data alpine cat /data/test.txt

nano Session09/b4/README.md

cat Session09/b4/README.md
