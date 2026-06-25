> # ⚠️ DEPRECATED
>
> This OCP **search skill** is deprecated and unmaintained. OCP search skills
> (`OVOSCommonPlaybackSkill` + `@ocp_search`) are replaced by **MediaProvider
> plugins** in the [`ovos-media`](https://github.com/OpenVoiceOS/ovos-media) stack:
>
> - **How MediaProviders work / how to migrate:** https://github.com/OpenVoiceOS/ovos-media/blob/dev/docs/media-providers.md
> - **Base-class deprecation:** [ovos-workshop#423](https://github.com/OpenVoiceOS/ovos-workshop/pull/423)
> - **Replacement:** [`ovos-media-provider-youtube`](https://github.com/OpenVoiceOS/ovos-media-provider-youtube)
>
> This repository will be archived.

# <img src='./ui/ytube.jpg' width='50' height='50' style='vertical-align:bottom'/> Simple Youtube Skill

simple youtube skill for better-cps

## About

search youtube by voice!

this skill can be configured as a fallback matcher for play queries, you can set `self.settings["fallback_mode"] = True`
and returned results will have lower confidence, other skills should take precedence most of the time

built on top of [youtube_searcher](https://github.com/HelloChatterbox/youtube_searcher)

![](./gui.png)
![](./gui2.png)

## Examples

* "play rob zombie"
* "play freezing moon with dead on vocals"
* "play programming music mix"
* "play center of all infinity album"

## Credits

JarbasAl

## Category

**Entertainment**

## Tags

- video
- youtube
- common play
- music
