# ZNC for Docker

Run the [ZNC][] IRC Bouncer in a Docker container.

[ZNC]: http://znc.in

## Running

docker run -d -p 6697:6697 --restart always -v $HOME/.znc:/home/znc/.znc d3vil/znc

