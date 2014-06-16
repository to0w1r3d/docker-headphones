README:

Headphones: (https://github.com/rembo10/)

______________

git clone git@github.com:to0w1r3d/docker-headphones

cd docker-headphones

docker build -t headphones .

______________

VOLUME /data

VOLUME /torrents

VOLUME /downloads

VOLUME /music

____________


docker run -d -h your_host_name -v /your_music_location:/music -v /your_downloads_location:/downloads -v /your_torrents_location:/torrents -v /your_data_location:/data -p 8181:8181 headphones
