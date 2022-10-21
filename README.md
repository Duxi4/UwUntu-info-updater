<!-- SHIELDS LINKS -->
<!--GITHUB STARS-->
[stars-shield]: https://img.shields.io/github/stars/Duxi4/UwUntu-info-updater?style=for-the-badge&logo=Linux&logoColor=C689C6&color=FFABE1
[stars-url]: https://github.com/Duxi4/UwUntu-info-updater/stargazers

<!--UWUNTUOS.SITE-->
[gotoweb-shield]: https://img.shields.io/badge/UwUntu%20Website-hi?style=for-the-badge&logo=Internet%20Explorer&logoColor=C689C6&color=FFABE1
[gotoweb-url]: https://uwuntuos.site

<!--KO-FI-->
[kofi-shield]: https://img.shields.io/badge/Buy%20us%20a%20cofee-KoFi?style=for-the-badge&logo=KoFi&logoColor=C689C6&color=FFABE1
[kofi-url]: https://ko-fi.com/uwuntu

<!-- Tweet about us-->
[tweet-shield]: https://img.shields.io/badge/Tweet%20about%20us-hi?style=for-the-badge&logo=Twitter&logoColor=C689C6&color=FFABE1
[tweet-url]: https://bit.ly/380p4nL

<!--Discord server -->
[discord-shield]:https://img.shields.io/badge/Join%20our%20discord-hi?style=for-the-badge&logo=Discord&logoColor=C689C6&color=FFABE1
[discord-url]:https://discord.gg/US38bG9n8c

<!-- MAIN REPO -->
[github-uwu]:https://img.shields.io/badge/REPO:-UwUntu-hi?style=for-the-badge&logo=GitHub&logoColor=C689C6&color=FFABE1
[UwUntu-url]:https://github.com/Duxi4/UwUntu

<br />
<br />

# UwUntu-info-updater
 
MOVE uwuntu-info-updater TO /usr/bin/uwuntu-info-updater
CHANGE PERMISSIONS TO ALLOW ONLY ROOT TO EDIT THE FOLDER AND THE CONTENT INSIDE

GO TO /lib/systemd/system AND MOVE uwuntu-updater.service
CHANGE PERMISSIONS (rw - r - r) OWNER root (644)

RUN sudo systemctl enable uwuntu-updater.service

IF YOU WANT TO ALLOW ACCESS TO EVERYONE (NOT NECESARY):
EDIT /etc/sudoers WITH visudo
#GRANT ACCESS TO THE UWUNTU INFO UPDATER
ALL    ALL = (root) NOPASSWD: /usr/bin/uwuntu-info-updater/uwuntu-info-updater.sh