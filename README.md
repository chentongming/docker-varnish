# docker-varnish

docker run -d --name=varnish-server --link=nignx-server:nginx-server -p 6081:6081 -p6085:6085 -v /home/cc/work/docker-varnish/default.vcl:/etc/varnish/default.vcl:ro image_id
