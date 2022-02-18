# Description

This is a minimal example to demonstrate how Maven snapshot dependency handling in RenovateBot could be improved.

## Snapshot dependency `http3-client`

### Current behavior

no PR is created

### Expected behavior

As `pinDigests` is enabled, it would be nice if the snapshot dependency version `11.0.9-SNAPSHOT`
was replaced by the latest actual artifact (currently `11.0.9-20220217.001318-7`, see
[https://oss.sonatype.org/service/local/repositories/jetty-snapshots/content/org/eclipse/jetty/http3/http3-client/11.0.9-SNAPSHOT/maven-metadata.xml]()).

## Pinned, outdated snapshot dependency `http3-server`

### Current behavior

no PR is created

### Expected behavior

The currently used version `11.0.9-20220208.001317-1` is outdated. It should be updated to the most
recent version (currently `11.0.9-20220217.001318-7`, see [https://oss.sonatype.org/service/local/repositories/jetty-snapshots/content/org/eclipse/jetty/http3/http3-server/11.0.9-SNAPSHOT/maven-metadata.xml]()).