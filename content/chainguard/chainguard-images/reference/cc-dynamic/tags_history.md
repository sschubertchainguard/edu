---
title: "cc-dynamic Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the cc-dynamic Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-04-02 00:36:12
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/cc-dynamic/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/cc-dynamic/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/cc-dynamic/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/cc-dynamic/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` | April 1st    | `sha256:46e850e339b026064989344c1e4ed523e89569290792233cc82621f63f2471ef` |
|  `latest`     | March 28th   | `sha256:9b93a1fe57d938233e73cff66787d11c0d24ebdc8046937c580a41a39508bb2a` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                        | Last Changed | Digest                                                                    |
|------------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `13-dev` `13.2.0-dev` `13.2-dev` `latest-dev` | March 28th   | `sha256:1d4ca1c98ca727c47788c0fe73205e947c3a8638c0d422d7f7dcbfc0f9556a17` |
|  `13.2` `13` `13.2.0` `latest`                 | March 28th   | `sha256:a8f62e0edbf1f5036564368a3f279c2f96920e167a44100824f89b1cfa9a47c8` |

