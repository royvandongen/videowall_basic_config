# videowall_basic_config
Basic ansible playbook for automated installs of grafana-kiosk on raspberry pi's

The basic installation for Grafana Kiosk was derived from this article: [Grafana.com](https://grafana.com/blog/2019/05/02/grafana-tutorial-how-to-create-kiosks-to-display-dashboards-on-a-tv), combined with the awesome [Grafana Kiosk](https://github.com/grafana/grafana-kiosk) Project.

Basics of the way to setup this repo where given by [Jeff Geerlings Internet-Pi](https://github.com/geerlingguy/internet-pi), Check his awesome work, he is the Ansibel Guru.

Before you start, please rename the inventory and config files, remove the ".example" part of the filename, and while you're at it, make sure the data in the inventory and config files reflect your wanted environment.

After that, from the main directory just run `ansible-playbook main.yml -k`, and enter your SSH Password for access to the systems.

Please note! I have used the Raspberry Pi image builder, at which you can specify some default options like enabling SSH, and setting a username and password. This saved me lots of time. Also, In my personal experience, the Grafana-Kiosk application works best at a Rasbpian Desktop environment. Effort was made to try to get it to work on the lite image, but after some time i decided to stick with the desktop environment.

Have Fun!
