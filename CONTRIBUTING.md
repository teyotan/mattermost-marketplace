# Contributing

Thank you for your interest in contributing! Join the [**Plugin Marketplace channel**](https://community.mattermost.com/core/channels/plugins-marketplace) on the Mattermost community server for discussion about this plugin.

## Reporting Issues

If you think you found a bug within the Marketplace code, [please use the GitHub issue tracker](https://github.com/mattermost/mattermost-marketplace/labels/issues/new) on this repository to open an issue. Bugs in the Marketplace in-product experience should be reported on the [Mattermost Server repository](https://github.com/mattermost/mattermost-server/issues/new). Please report bugs within specific plugin on their respective issue trackers.

## Community Plugin

To add your plugin to the Marketplace, please open [an issue using this template](https://github.com/mattermost/mattermost-marketplace/issues/new?template=add_plugin.md). To update your plugin, please also open an issue [using this template](https://github.com/mattermost/mattermost-marketplace/issues/new?template=update_plugin.md).

### Playbook

The following is a playbook for use by Mattermost core committers.

#### New plugin

JIRA template:
  - [PM](https://mattermost.atlassian.net/browse/MM-22224)
  - [Dev](https://mattermost.atlassian.net/browse/MM-22221)
  - [Security](https://mattermost.atlassian.net/browse/MM-22225)
  - [QA](https://mattermost.atlassian.net/browse/MM-22223)

After a new plugin has been submitted, the assignee of the issue posts the following message:
```
## Process checklist
- [ ] Request review, create JIRA tickets, and link them here:
    - PM:
    - Dev:
    - Security:
    - QA:
- [ ] Create a private fork under the Mattermost organization
- [ ] Cut plugin release
- [ ] Add release to Marketplace
- [ ] Reach out on [Marketing Channel](https://community-release.mattermost.com/private-core/channels/marketing) to tweet about the plugin.
) to tweet about the plugin
- [ ] Work with `@hanna.park` regarding swag
```

#### Update plugin

JIRA template:
  - [PM](https://mattermost.atlassian.net/browse/MM-22228)
  - [Dev](https://mattermost.atlassian.net/browse/MM-22222)
  - [Security](https://mattermost.atlassian.net/browse/MM-22226)
  - [QA](https://mattermost.atlassian.net/browse/MM-22227)

After an update for an existing plugin has been submitted, the assignee of the issue posts the following message:
```
## Process checklist
- [ ] Request review and create JIRA tickets and link them here:
    - PM:
    - Dev:
    - Security:
    - QA:
- [ ] Update fork
- [ ] Cut plugin release
- [ ] Add release to Marketplace
```