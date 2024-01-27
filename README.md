# dunkbin-stats-images
[![Fly Deploy](https://github.com/WUOTE/dunkbin-stats-images/actions/workflows/main.yml/badge.svg?branch=main)](https://github.com/WUOTE/dunkbin-stats-images/actions/workflows/main.yml)
## Repo for dunkbin PNGs, GIFs, and analytical dashboard.

[https://dunkbinstats.runfast.stream](https://dunkbinstats.runfast.stream)

### V5 workflow chart
![Dunkbin_stats_cosmetics_images_V5](https://github.com/WUOTE/dunkbin-stats-images/assets/106106310/6d723ded-327e-4123-8771-8a450ae163bd)


### Backlog spritesheet workflow chart V5
![Dunkbin_backlog_V5](https://github.com/WUOTE/dunkbin-stats-images/assets/106106310/48f9516e-7589-436e-a3ba-e55d4df72cca)


### Backlog spritesheet next cosmetic and next cosmetic artist chart V5
![Dunkbin_Next_Cosmetic_and_Next_Cosmetic_Artist_V5](https://github.com/WUOTE/dunkbin-stats-images/assets/106106310/226acceb-58ef-4d93-bf6a-c4a76a9f0850)


### Backlog spritesheet next cosmetic info V5
![Dunkbin_Next_Cosmetic_Info_V5](https://github.com/WUOTE/dunkbin-stats-images/assets/106106310/d1e9bf0b-10e1-4964-97bb-4415e71ed685)


### Gotchas
Running n8n inside a container requires

1. fixing writing priviliges -- Alpine: run as `root` in `sh` -- `chown node git/`.
2. Setting DNS server in case you run it alongside Adguard Home or similar, otherwise n8n will not be able to access external services.
