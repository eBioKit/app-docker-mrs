MRS docker
===================

This docker image is part of the eBioKit 2017 project.

This docker image extends and distributes the following software:

#### MRS

- Based on [MRS project](http://mrs.cmbi.ru.nl/).
- MRS was designed and implemented by Maarten Hekkelman at the CMBI. [Boost Software License - Version 1.0.](https://raw.githubusercontent.com/bgruening/docker-galaxy-stable/master/LICENSE).
- Citation:
> MRS: A fast and compact retrieval system for biological data. Hekkelman M.L., Vriend G.
Nucleic Acids Research 2005 33(Web Server issue):W766-W769; doi:10.1093/nar/gki422. [Link](https://academic.oup.com/nar/article/33/suppl_2/W766/2505577/MRS-a-fast-and-compact-retrieval-system-for?ijkey=1hM9Po54JADYz0b&keytype=ref)

## Running the Container

The container is publicly available as `ebiokit/docker-mrs`. The recommended
method for launching the container is via docker-compose.

## Quickstart

This procedure starts mrs in a standard virtualised environment.

- Install [docker](https://docs.docker.com/engine/installation/) for your system if not previously done.
- `docker run -it -p 18090:18090 ebiokit/docker-mrs`
- MRS will be available at [http://localhost:18090/](http://localhost:18090/)

### Logging In

The default credentials in this image are below. Credentials can be changed in the docker-compose file:

| Credentials |                    |
| ---         | ------------------ |
| Username    | `root` |
| Password    | `123`         |

### About the eBioKit project

The eBioKit is a system running multiple open source web services on an Apple Mac-mini where all databases are stored locally.
This reduces the need for a fast internet connection while giving the users an opportunity to incorporate their data sets in widely used web services.

The eBioKit is developed by the SLU Global Bioinformatics Centre (SGBC), an academic research and educational initiative aimed to build a long-term successful bioinformatics infrastructure facility that serves the Swedish University for Agricultural Sciences (SLU) and life science research communities worldwide.

Find more information at [http://ebiokit.eu](http://ebiokit.eu)  and at the [SGBC](http://sgbc.slu.se/) website.

**Contact** [ebiokit@gmail.com](ebiokit@gmail.com)

<p style="text-align:center">
<img height=100 src="https://avatars0.githubusercontent.com/u/24695838?v=3&s=200">
</p>
