# docker-collectd

Container with [collectd 5.5](https://collectd.org) based on ubuntu using this [ppa](https://launchpad.net/~rullmann/+archive/ubuntu/collectd)

To run the container: docker run -p 25826:25826/udp -v /var/docker_data/collectd/etc/:/etc/collectd/ -v /var/docker_data/collectd/base:/var/lib/collectd njordr/collectd (Use -v to save data)

In my github repositry ([njordr](https://github.com/njordr/collectd)) you can find a copy of /etc/collectd conf directory
