# Probot settings 

Changes GitHub repository settings from a file. Uses [this probot app](https://github.com/probot/settings). 

# Usage 

* Make sure the [Settings GitHub App](https://github.com/apps/settings) is installed on your repository. 
* Create file `.github/settings.yml` in your repository. 
* In this file, refer to one of the shareable config files and override anything if you wish:

```yml
_extends: probot-configs:settings/default.yaml
```

> Learn more about [probot shareable configs](https://probot.github.io/docs/best-practices/#store-configuration-in-the-repository)

