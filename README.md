# sinkhole (Abandoned due to changes in Nomad API)
CLI tool for quickly creating webhooks and event sinks for Hashicorp Nomad agents and clusters.

## UPDATE / Postmortem 💀
Due to [recent changes in Nomad API](https://discuss.hashicorp.com/t/all-documents-related-to-nomad-event-sink-removed/18578), I have decided to abandon this project. I had planned to migrate it to a Typescript CLI tool and flesh it out some more but I didn't end up getting to far with that unfortunately. 

The basic idea of this project was to have a CLI `sinkhole` command that let sysadmins and devops engineers link their Nomad clusters to other services. Using the tool, commands such as the `sinkhole create` command could be used to register event sinks on job fails, deployments or other cluster events. The tool would manage these sinks with your Nomad cluster and let you easily get webhooks for them so they can be linked to other apps such as Slack.

Under the hood this mainly worked by sending api requests to the Nomad agent's API, however the updates to the Nomad API have removed the event sinks entirely. I still learned a fair bit from this project though and am happy I got a chance to play around with it while I could. 

I may try and create something similar in the future since I really like the name sinkhole though.
