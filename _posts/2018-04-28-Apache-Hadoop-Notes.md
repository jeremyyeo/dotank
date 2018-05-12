---
layout: post
title:  "Apache Hadoop Notes"
categories: bigdata apache hadoop
---

A brief introduction to Apache Hadoop.

# Core Hadoop Architecture

## HDFS

A HDFS cluster comprises of:
- NameNode (one or two for High Availability)
    * master service of HDFS.
    * determines and maintains how the chunks of data are distributed across the DataNodes.
    * metadata only (actual data reside in DataNodes).
- DataNode (as many as you want per cluster)

YARN resource manager:


# Deploying Hadoop

