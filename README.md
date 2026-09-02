> # ⚠️ DEPRECATED
>
> This OCP **search skill** is deprecated and unmaintained. OCP search skills
> (`OVOSCommonPlaybackSkill` + `@ocp_search`) are replaced by **MediaProvider**
> plugins loaded in-process by the
> [`ovos-ocp-pipeline-plugin`](https://github.com/OpenVoiceOS/ovos-ocp-pipeline-plugin),
> which dispatches search to them — the replacement is
> [`ovos-media-provider-youtube`](https://github.com/OpenVoiceOS/ovos-media-provider-youtube).
> The package is published, but it only does anything once the OCP pipeline's
> MediaProvider dispatch is the default search path — installing it does not
> replace this skill under the legacy OCP/`ovos-audio` stack. `ovos-media` is
> a separate component (the player daemon) and is not involved in search.
>
> - **How MediaProviders work / how to migrate:** https://github.com/OpenVoiceOS/ovos-media/blob/dev/docs/media-providers.md
> - **Base-class deprecation:** [ovos-workshop#423](https://github.com/OpenVoiceOS/ovos-workshop/pull/423)
>
> This skill keeps working until the OCP pipeline's MediaProvider dispatch
> becomes the default search path and this repository is archived.

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
