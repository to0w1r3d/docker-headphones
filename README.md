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


docker run -d -h hostname -v /hostdata:/data -v /hosttorrents:/torrents -v /hostdownloads:/downloads -v /hostmusiclibrary:/music -p 8181:8181 headphones

