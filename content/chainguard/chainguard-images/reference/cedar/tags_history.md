---
title: "cedar Image Tags History"
type: "article"
unlisted: true
description: "Image Tags and History for the cedar Chainguard Image"
date: 2023-06-22T11:07:52+02:00
lastmod: 2024-06-26 00:35:03
draft: false
tags: ["Reference", "Chainguard Images", "Product"]
images: []
weight: 700
toc: true
---

{{< tabs >}}
{{< tab title="Overview" active=false url="/chainguard/chainguard-images/reference/cedar/" >}}
{{< tab title="Details" active=false url="/chainguard/chainguard-images/reference/cedar/image_specs/" >}}
{{< tab title="Tags History" active=true url="/chainguard/chainguard-images/reference/cedar/tags_history/" >}}
{{< tab title="Provenance" active=false url="/chainguard/chainguard-images/reference/cedar/provenance_info/" >}}
{{</ tabs >}}

The following tables contains the most recent tags and digests that can be used to pin your Dockerfile to a specific build of this image. Check our guide on [Using the Tag History API](/chainguard/chainguard-images/using-the-tag-history-api/) for information on how to fetch all tags from an image and how to pin your Dockerfile to a specific digest.

Please note that digests and timestamps only change when there is a change to the image, even though images are rebuilt every night. The "Last Changed" column indicates when the image was last modified, and doesn't always reflect the latest build timestamp. For more information about how our reproducible builds work, please refer to [this blog post](https://www.chainguard.dev/unchained/reproducing-chainguards-reproducible-image-builds).

### Public Registry
The Public Registry contains our **Developer Images**, which typically comprise the `latest*` versions of an image.

| Tag (s)       | Last Changed | Digest                                                                    |
|---------------|--------------|---------------------------------------------------------------------------|
|  `latest-dev` | June 24th    | `sha256:2e05ffe35e95ee7aa2b9321d12147c941c796c0467c8d0c012b08b5ead1e20e6` |
|  `latest`     | June 20th    | `sha256:a5b716da81ffd3e0358c067ba9ccb437e54e9ce82c83ac6a50186aab6141fdf6` |


### Private/Dedicated Registry
The Private/Dedicated Registry contains our **Production Images**, which include all versioned tags of an image and special images that are not available in the public registry (including FIPS images and other custom builds).

| Tag (s)                                     | Last Changed | Digest                                                                    |
|---------------------------------------------|--------------|---------------------------------------------------------------------------|
|  `3-dev` `latest-dev` `3.2.1-dev` `3.2-dev` | June 25th    | `sha256:750705f469a13c2c6e3aea0fc0bb68ed19724685920dded2107cb1d6c11fccd6` |
|  `latest` `3.2` `3` `3.2.1`                 | June 20th    | `sha256:da8ff384dace737ebc6885894ebcd23a5fc2d6745eb6fd7472a2d340ff2c628a` |

