# Kometa Config and Collections

Custom Kometa collection files for Plex movie libraries, covering curated movie sets, Dolby Vision Profile 7, and home theater demos.

## Collections

| File | Collections | How movies are selected |
| --- | --- | --- |
| [Custom collections](custom-collection.yml) | Collections that don't have a traditional franchise in TMDB. | Individual TMDB movie IDs |
| [Dolby Vision FEL and MEL](fel-mel-collection.yml) | **FEL** groups Full Enhancement Layer titles. **MEL** groups Minimum Enhancement Layer titles. | Radarr tags: `fel` and `mel` |
| [Home theater reference collections](reference-audio-video-collection.yml) | **Reference Audio** and **Reference Video** feature picks based on Shane Lee’s reviews. **Ultimate Bass** highlights movies with deep bass. | Dedicated TMDB lists |

## Use with Kometa

Add the YAML files you want to use to the movie library’s `collection_files` in your Kometa configuration. For FEL and MEL, connect Radarr and apply the corresponding tags to your movies. The home theater reference file also defines Radarr item tags for its three collections.
