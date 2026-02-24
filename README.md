# dunkbin-stats-images

## Repo for dunkbin fantasy shop cosmetics and analytical dashboard.

### V8 workflow for the next cosmetic in the dunkbin

![Dunkbin_Next_Cosmetic_Info_V8](n8n_workflows/Workflow_screenshots/Dunkbin_Next_Cosmetic_Info_V8.png)

### V8 workflow chart

![Dunkbin_stats_cosmetics_images_V8](n8n_workflows/Workflow_screenshots/Dunkbin_stats_cosmetics_images_V8.png)

### Backlog spritesheet workflow chart V8

![unkbin_backlog_V8](n8n_workflows/Workflow_screenshots/Dunkbin_backlog_V8.png)

### Backlog spritesheet next cosmetic and next cosmetic artist chart V9

![Dunkbin_Next_Cosmetic_and_Next_Cosmetic_Artist_V9](n8n_workflows/Workflow_screenshots/Dunkbin_Next_Cosmetic_and_Next_Cosmetic_Artist_V9.png)

### Backlog spritesheet next cosmetic info V8

![Dunkbin_Next_Cosmetic_Info_V8](n8n_workflows/Workflow_screenshots/Dunkbin_Next_Cosmetic_Info_V8.png)

### Dunkbinstats build trigger V1

![Dunkbinstats_build_trigger_V1](n8n_workflows/Workflow_screenshots/Dunkbinstats_build_trigger_V1.png)

### Error Workflow

![Errow Workflow](n8n_workflows/Workflow_screenshots/Error_workflow.png)

### Additional workflows

#### 7tv emotes upload workflow

![7tv_censor_emote_upload](n8n_workflows/Workflow_screenshots/7tv_censor_emote_upload.png)

![7tv_censor_emotes_add_to_the_emote_set](n8n_workflows/Workflow_screenshots/7tv_censor_emotes_add_to_the_emote_set.png)

![7tv_censor_emote_status_check](n8n_workflows/Workflow_screenshots/7tv_censor_emote_status_check.png)

### Gotchas

Running n8n inside a container requires

1. fixing writing priviliges -- Alpine: run as `root` in `sh` -- `chown node git/`.
2. Setting DNS server in case you run it alongside Adguard Home or similar, otherwise n8n will not be able to access external services.
3. GitHub credentials: use the classic token (as per n8n's docs).
