---
description: Lets you manually set the video bitrate for screen-shares
---

# \&screensharebitrate

## Aliases

* `&ssbitrate`

## Options

| Value           | Description                             |
| --------------- | --------------------------------------- |
| (integer value) | video bitrate for screen-shares in kbps |

## Details

Lets you manually set the video bitrate for screen-shares in kbps. This is a viewer-side command, and works with scenes link, view links, and guest links.

This specified screen-share bitrate will not count towards the total room or scene bitrate, if those are being used. It also takes priority over most other bitrates parameters, with just a couple exceptions.

## Related

{% content-ref url="../view-parameters/bitrate.md" %}
[bitrate.md](../view-parameters/bitrate.md)
{% endcontent-ref %}