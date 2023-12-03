### Project highlights

In the following some of my projects are briefly described:

#### [pkb_client](https://github.com/infinityofspace/pkb_client)

[![Downloads](https://static.pepy.tech/badge/pkb_client)](https://pepy.tech/project/pkb_client) [![Downloads](https://static.pepy.tech/badge/pkb_client/month)](https://pepy.tech/project/pkb_client)

Client for using Porkbun API as CLI and library. I created the project because at the time there was no API client that could interact with the Porkbun API and be used as a basis for further libraries (e.g. certbot). 

#### [certbot_dns_porkbun](https://github.com/infinityofspace/certbot_dns_porkbun)

[![Downloads](https://static.pepy.tech/badge/certbot_dns_porkbun)](https://pepy.tech/project/certbot_dns_porkbun) [![Downloads](https://static.pepy.tech/badge/certbot_dns_porkbun/month)](https://pepy.tech/project/certbot_dns_porkbun)

A DNS plugin for certbot to perform a DNS-01 challenge. Letsencrypt allows you to create a certificate for domains very easily, but there was no DNS plugin for certbot with a domain that uses Porkbun DNS. So I build this project on top of the pkb_client library to add another provider to certbot.

#### [certbot_dns_duckdns](https://github.com/infinityofspace/certbot_dns_duckdns)

[![Downloads](https://static.pepy.tech/badge/certbot_dns_duckdns)](https://pepy.tech/project/certbot_dns_duckdns) [![Downloads](https://static.pepy.tech/badge/certbot_dns_duckdns/month)](https://pepy.tech/project/certbot_dns_duckdns)

A DNS plugin for certbot to perform a DNS-01 challenge. I created this project for the same reason and with the same intention as the certbot_dns_porkbun project.

#### [twitter-bot-type-classification](https://github.com/infinityofspace/twitter-bot-type-classification)

The project was part of a scientific project to classify different types of bots on the Twitter platform using machine learning and to compare the classification performance with existing methods. It was found that current methods, which can only distinguish between bot and non-bot, produce poorer classification results than the method used in this project.

#### [jellyfin_alexa_skill](https://github.com/infinityofspace/jellyfin_alexa_skill)

[![Downloads](https://static.pepy.tech/badge/jellyfin_alexa_skill)](https://pepy.tech/project/jellyfin_alexa_skill) [![Downloads](https://static.pepy.tech/badge/jellyfin_alexa_skill/month)](https://pepy.tech/project/jellyfin_alexa_skill)

A self-hosting Alexa Skill for the media server jellyfin. It allows the playback of media on Alexa devices. I created the project because there is no interface for the connection between Jellyfin and Alexa. I also love self-hosting and wanted to enable the use of Jellyfin on other platforms. In the project I was able to gain a deep knowledge of both platforms and their interfaces.

#### [jellyfin-alexa-plugin](https://github.com/infinityofspace/jellyfin-alexa-plugin)

This native C# Jellyfin plugin is the result of the jellyfin_alexa_skill project and allows a deeper integration of the Alexa Skill into Jellyfin.

#### [argon2](https://github.com/infinityofspace/argon2)

Argon2 is a new password hashing method that allows the parallelization and memory consumption to be adjusted through parameterization. With this project various benchmarks are carried out, such as the influence of multiprocessing and the hash length in comparison to the computing time.

#### [filechain](https://github.com/infinityofspace/filechain)

In this project, the basic idea of a blockchain is used for the use of files as blocks. This allows files to be stored in a decentralized manner. The protocol uses sockets for the exchange.

#### [remote_minerl_env](https://github.com/infinityofspace/remote_minerl_env)

The project resulted from the need to simplify and accelerate the training of an agent in the MineRl challange. The goal of the project is to start the MineRL test environment on any system as a server and to connect the training system as a client. This client-server structure via sockets makes it possible to separate the two systems and thus speed up training and testing.

#### [SfmLearner-Pytorch](https://github.com/infinityofspace/SfmLearner-Pytorch)

This is a fork of SfmLearner for unsupervised learning of depth and ego-motion from video for extracting the movement and depth information of a virtual agent in the mine rl challenge. See the [notebooks](https://github.com/infinityofspace/SfmLearner-Pytorch/tree/master/notebooks) for experiments and results.

---

With love for open source ❤️
