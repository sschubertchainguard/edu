---
title: "etcd Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the etcd Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-04-02 00:36:12
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/etcd/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/etcd/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/etcd/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/etcd/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` | April 1st    | `sha256:742846a29224fe9425f683735bd8d5221044629af7abd334c166849480c22744` |
|  `latest`     | March 31st   | `sha256:18ce7ed747c93ec5a88a38a85f374adbb36b1417192137f54579d0418cffcd86` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                      | Last Changed | Digest                                                                    |
|----------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `3.4-dev` `3.4.31-dev`                      | April 1st    | `sha256:8002100268fbbf8c6622cd3bb0477dbfed994bb2d6a1f9bd47b3817ce4b25744` |
|  `latest-dev` `3.5.13-dev` `3.5-dev` `3-dev` | April 1st    | `sha256:d8e51be37804369714f59712467e2a7bc609a1a23d87713163beb859c13ca605` |
|  `3.5.13` `latest` `3.5` `3`                 | March 29th   | `sha256:bf1f4403481cd10f0e3b543954ec0ce18fd795170482361794857866b0a2fba6` |
|  `3.5.12`                                    | March 28th   | `sha256:72161ffc9e1c4662d0642e9616fd5c61023967fd7216d16531466632d0e93f56` |
|  `3.5.12-dev`                                | March 28th   | `sha256:b284c96d56c2492126e7df9530cdccc2462f39422cd363097f835756965b818a` |
|  `3.4` `3.4.31`                              | March 28th   | `sha256:82464453acb14c2f626ec677c5ad224baf997494a504295b0d88c5e0a26e008c` |
|  `3.4.30`                                    | March 18th   | `sha256:68223c6f890df02b29039f7d4587e116be6c7af1e33f153f22bd26de717f0fc4` |
|  `3.4.30-dev`                                | March 18th   | `sha256:bbdd1cd2be3009846b31f572f447c06b82bdeb2ffb9dce582350904e0cb4947e` |

