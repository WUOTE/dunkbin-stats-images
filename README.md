# dunkbin-stats-images

## Repo for dunkbin fantasy shop cosmetics and analytical dashboard.

[https://dunkbinstats.runfast.stream](https://dunkbinstats.runfast.stream)
https://github.com/WUOTE/dunkbin-stats-images/blob/main/n8n_workflows/Workflow_screenshots/Dunkbin_Next_Cosmetic_Info_V6.png
### V6 workflow chart
![Dunkbin_stats_cosmetics_images_V6](https://github.com/WUOTE/dunkbin-stats-images/blob/main/n8n_workflows/Workflow_screenshots/Dunkbin_stats_cosmetics_images_V6.png)


### Backlog spritesheet workflow chart V6
![Dunkbin_backlog_V6](https://github.com/WUOTE/dunkbin-stats-images/blob/main/n8n_workflows/Workflow_screenshots/Dunkbin_backlog_V6.png)


### Backlog spritesheet next cosmetic and next cosmetic artist chart V6
![Dunkbin_Next_Cosmetic_and_Next_Cosmetic_Artist_V6](https://github.com/WUOTE/dunkbin-stats-images/blob/main/n8n_workflows/Workflow_screenshots/Dunkbin_Next_Cosmetic_and_Next_Cosmetic_Artist_V6.png)


### Backlog spritesheet next cosmetic info V6
![Dunkbin_Next_Cosmetic_Info_V6](https://github.com/WUOTE/dunkbin-stats-images/blob/main/n8n_workflows/Workflow_screenshots/Dunkbin_Next_Cosmetic_Info_V6.png)


### Gotchas
Running n8n inside a container requires

1. fixing writing priviliges -- Alpine: run as `root` in `sh` -- `chown node git/`.
2. Setting DNS server in case you run it alongside Adguard Home or similar, otherwise n8n will not be able to access external services.

### Additional workflows

#### 7tv emotes upload workflow
![7tv_censor_emote_upload](https://github.com/WUOTE/dunkbin-stats-images/blob/main/n8n_workflows/Workflow_screenshots/7tv_censor_emote_upload.png)

![7tv_censor_emotes_add_to_the_emote_set](https://github.com/WUOTE/dunkbin-stats-images/blob/main/n8n_workflows/Workflow_screenshots/7tv_censor_emotes_add_to_the_emote_set.png)

![7tv_censor_emote_status_check](https://github.com/WUOTE/dunkbin-stats-images/blob/main/n8n_workflows/Workflow_screenshots/n8n_workflows/Workflow_screenshots/7tv_censor_emote_status_check.png)