# IPTV Custom Panel

![IPTV_Panel](logo.png "Logo")

Now, in the world there are many users that watch IPTV live channels. In future, the number of the users will be increased.
This project implements IPTV system that is stable, secure and non-blocking.

![IPTV_Panel_Introduction](introduction.png)
=======
This project is  system  that huge users can watch many live streams, movies and serieses.   

### Includes Technology

* FFMPEG
* Load balancing using multiple servers
* Cron job for managing streams
* Processing VOD and live stream in PHP

### Template Structure

| Location             |  Content                                   |
|----------------------|--------------------------------------------|
| `/crons`             | Cron Job Scripts                           |
| `/ffmpegs`           | FFMPEG binary file                         |
| `/streamcodes`       | Php loadbalancer code                      |

## Prerequisites

Before getting started you should have installed the following:

- [X] > PHP 7.0
- [X] > Nginx 1.10
- [X] > Mysql 5.7

