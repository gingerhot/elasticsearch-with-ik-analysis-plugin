# elasticsearch-with-ik-analysis-plugin

Dockerfile for Elasticsearch with IK Analysis plugin.

The Dockerfile base is from: https://github.com/docker-library/elasticsearch , and I add the IK analysis plugin: https://github.com/medcl/elasticsearch-analysis-ik.

* Elasticsearch version: 5.3.0
* IK analysis plugin version: 5.3.0

You can change the verison in Dockerfile to match your requirement:

```bash
ENV ELASTICSEARCH_VERSION 5.3.0
ENV ELASTICSEARCH_DEB_VERSION 5.3.0
```
before make sure the ik plugin version is available.

and just build the image:

```bash
docker build -t give_your_tag_here .
```
