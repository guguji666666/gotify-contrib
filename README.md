# gotify/contrib

Do you want to contribute to the gotify project? Have a look at our [contributing.md](https://github.com/gotify/server/blob/master/CONTRIBUTING.md).

Here you'll find community contributions to the Gotify project.

## Guides

- [CrowdSec Notification Plugin](https://docs.crowdsec.net/docs/notification_plugins/gotify) An example configuration to use Gotify as a notification channel for [CrowdSec](https://github.com/crowdsecurity/crowdsec).
- [cyb3rko/gotify-mtls-setup](https://github.com/cyb3rko/gotify-mtls-setup) A guide for setting up mTLS authentication with Gotify and a proxy.
- [denisgolius/zabbix-to-gotify-alert](https://github.com/denisgolius/zabbix-to-gotify-alert) A guide for sending alerts from [Zabbix](https://www.zabbix.com/) to `gotify/server`.
- [hypervtechnics/gotify-and-caddy-with-systemd](https://gist.github.com/hypervtechnics/9cb28e67aea93cb9b87af5141bc3aa25) Install Gotify with Caddy as reverse proxy and with a systemd service.
- [mrspartak/gotify-dc](https://github.com/mrspartak/gotify-dc) 3 steps deploy with docker-compose `gotify/server` + Nginx.
- [mskian/gotify-apache](https://github.com/mskian/gotify-apache) Install and Configure Gotify without Docker in Apache Server.
- [render-examples/gotify-server](https://github.com/render-examples/gotify-server) A guide to deploying `gotify/server` on [Render](https://render.com).
- [YunoHost-Apps/gotify_ynh](https://github.com/YunoHost-Apps/gotify_ynh) `gotify/server` as package for [YunoHost](https://yunohost.org).

## Libraries

- [ajmcateer/GotifySharp](https://github.com/ajmcateer/GotifySharp) A C# library for interacting with `gotify/server`.
- [caronc/apprise](https://github.com/caronc/apprise) A notification library for almost all popular notification services.
- [ctlove0523/gotify-java-client](https://github.com/ctlove0523/gotify-java-client) A Java library for interacting with `gotify/server`.
- [d-k-bo/python-gotify](https://github.com/d-k-bo/python-gotify) A Python module for interacting with `gotify/server`, also available on [PyPI](https://pypi.org/project/gotify/).
- [hywax/gotify-client](https://github.com/hywax/gotify-client) A JavaScript library for interacting with `gotify/server`.
- [VerifiedJoseph/gotify-api-php](https://github.com/VerifiedJoseph/gotify-api-php) A PHP library for interacting with `gotify/server`.

## Plugins

- [AmamiyaHotaru/GotifyToESPDeerAdapter](https://github.com/AmamiyaHotaru/GotifyToESPDeerAdapter) A plugin for forwarding Gotify messages to MQTT for compatibility with [Deeresp](https://github.com/easychen/pushdeer/tree/main/iot) (Pushdeer's IoT version)
- [anhbh310/gotify2telegram](https://github.com/anhbh310/gotify2telegram) A plugin for forwarding Gotify messages to Telegram through Telegram Bot API.
- [ckocyigit/gotify-authentik-plugin](https://github.com/ckocyigit/gotify-authentik-plugin) A plugin that allows gotify/server to directly receive and process webhooks from [Authentik](https://github.com/goauthentik/authentik). 
- [david-kalmakoff/gotify-smtp-emailer](https://github.com/david-kalmakoff/gotify-smtp-emailer) A plugin for forwarding received messages to email through SMTP
- [elgonlabs/gotify-emailer](https://github.com/elgonlabs/gotify-emailer) A plugin for sending emails for incoming gotify/server messages.
- [eternal-flame-AD/gotify-broadcast](https://github.com/eternal-flame-AD/gotify-broadcast) A plugin for message broadcasts to multiple users.
- [eternal-flame-AD/gotify-webhook-misskey](https://github.com/eternal-flame-AD/gotify-webhook-misskey) A plugin for receiving notification from federated social networking platform [Misskey](https://github.com/misskey-dev/misskey) with multi-user support.
- [LukasKnuth/gotify-slack-webhook](https://github.com/LukasKnuth/gotify-slack-webhook) A plugin to receive Slack Incoming Webhooks in Gotify.
- [marceltransier/gotify-slack](https://github.com/marceltransier/gotify-slack) A plugin for Slack push notifications.
- [MexHigh/Gotify-Postal-Webhooks-Plugin](https://github.com/MexHigh/Gotify-Postal-Webhooks-Plugin) A plugin for receiving and displaying webhooks from the [Postal mail delivery platform](https://github.com/postalserver/postal). Supports all message types.
- [MexHigh/Gotify-Webhooks-Plugin](https://github.com/MexHigh/Gotify-Webhooks-Plugin) A plugin for receiving and displaying generic webhook requests.
- [ocimea/gotify-alertmanager-plugin](https://codeberg.org/ocimea/gotify-alertmanager-plugin)  A plugin that allows gotify/server to directly receive and process webhooks from prometheus/alertmanager. 
- [thomas-maurice/gotify-nats-plugin](https://github.com/thomas-maurice/gotify-nats-plugin) A plugin to receive messages sent through [NATS](https://nats.io/).
- [tystuyfzand/gotify-mqtt](https://github.com/tystuyfzand/gotify-mqtt) A plugin for MQTT message subscriptions (for IoT and others).
- [tystuyfzand/gotify-smtp](https://github.com/tystuyfzand/gotify-smtp) A plugin for SMTP ingest of notifications.

## Tools / Applications

- [4oo4/email2gotify](https://github.com/4oo4/email2gotify) Simple script to redirect mail output (e.g. from postfix) into a `gotify` push notification.
- [a-bali/janitor](https://github.com/a-bali/janitor) Availability monitoring and alerting for IOT devices.
- [ajmcateer/GotifyDesktop](https://github.com/ajmcateer/GotifyDesktop) A cross platform Desktop client `gotify/server`.
- [androidseb25/iGotify-Notification-Assistent](https://github.com/androidseb25/iGotify-Notification-Assistent) An assistent that sends push notifications to iOS devices for incoming `gotify/server` messages.
- [anup92k/gotify_nagios](https://github.com/anup92k/scripts/tree/master/nagios-plugins/gotify_nagios) A Nagios plugin to send notifications via `gotify`.
- [crazy-max/diun](https://github.com/crazy-max/diun) Receive notifications when an image is updated on a Docker registry.
- [cyrinux/imap2gotify](https://github.com/cyrinux/imap2gotify) An email IMAP Idle proxy to `gotify/server`.
- [desbma/gotify-desktop](https://github.com/desbma/gotify-desktop) Small daemon to send desktop notifications
- [diddypod/rotify](https://github.com/diddypod/rotify) Send and view Gotify messages via [rofi](https://github.com/davatorium/rofi).
- [DRuggeri/alertmanager_gotify_bridge](https://github.com/DRuggeri/alertmanager_gotify_bridge) A bridge between Prometheus AlertManager and a Gotify server 
- [eikendev/action-gotify](https://github.com/eikendev/action-gotify) A GitHub action to send notifications via `gotify/server`.
- [Enchufadoo/gotify-fox](https://github.com/Enchufadoo/gotify-fox) A Firefox addon for sending messages to `gotify/server`.
- [gigigig/bedrock-docker-gotify](https://github.com/gigigig/bedrock-docker-gotify) Sends Player Events from Minecraft Bedrock Docker Server to `gotify/server`.
- [immanuelfodor/rocketchat-push-gateway](https://github.com/immanuelfodor/rocketchat-push-gateway) A push gateway for RocketChat to send notifications to `gotify/server`.
- [JakobST1n/RSS-watcher](https://github.com/JakobST1n/RSS-watcher) Periodically checks RSS feeds for new entries, and pushes those to `gotify/server`.
- [kha7iq/pingme](https://github.com/kha7iq/pingme) A CLI tool which provides the ability to send messages to multiple messaging platforms.
- [kisst/gotify-gnome-client](https://github.com/kisst/gotify-gnome-client) A Gotify client for Linux with Gnome desktop
- [LukasKnuth/terraform-provider-gotify](https://github.com/LukasKnuth/terraform-provider-gotify) Setup Gotify using Terraform.
- [mattmckenzy/mail2gotify](https://github.com/MattMckenzy/Mail2Gotify) A stand-alone, hosted SMTP server that relays email notifications to `gotify/server`.
- [methatronc/checker](https://github.com/methatronc/checker) Receive notifications when a running image is updated on the Docker registry.
- [mskian/ssl-expiry-reminder](https://github.com/mskian/ssl-expiry-reminder) SSL Expiry Reminder - Get SSL Expiry Notification remainder Alerts on `gotify/server`.
- [n8n.io/n8n](https://github.com/n8n-io/n8n/tree/master/packages/nodes-base/nodes/Gotify) A Gotify integration for the workflow automation tool [n8n](https://n8n.io/) via the [Gotify node](https://n8n.io/integrations/gotify/).
- [no-go/NotifyRelay](https://github.com/no-go/NotifyRelay) An Android app for relaying almost all Android messages to `gotify/server`. [F-Droid](https://f-droid.org/packages/click.dummer.notify_to_jabber/)
- [ojrivera381/SendGotifyMessage](https://github.com/ojrivera381/SendGotifyMessage) A simple Powershell CLI function for sending messages to `gotify/server`.
- [Ondolin/gotify-matrix-bot](https://github.com/Ondolin/gotify-matrix-bot) A small tool to recive gotify messages in a matrix chat.
- [ppacher/moziot-gotify-addon](https://github.com/ppacher/moziot-gotify-addon) A Mozilla WoT gateway addon to send notifications via `gotify`.
- [rakshazi/desktop2gotify](https://gitlab.com/rakshazi/desktop2gotify) A desktop daemon/cli app that reads notifications from dbus and sends them to your gotify, matrix or webhook server
- [rorpage/gotify-chrome](https://github.com/rorpage/gotify-chrome) A Chrome extension for sending messages to `gotify/server`.
- [schwma/gotify-push](https://github.com/schwma/gotify-push) A Python CLI for sending messages to `gotify/server`.
- [sebw/pushtify](https://github.com/sebw/pushtify) Forward Gotify notifications to Pushover.
- [StewartThomson/Gotify-Ext](https://github.com/StewartThomson/Gotify-Ext) A Browser extension for viewing and managing gotify servers
- [Winify](https://winify.grimore.org/) A Windows (7+) desktop client for receiving notifications from Gotify.
- [ztpnk/gotify-dunst](https://github.com/ztpnk/gotify-dunst) A gotify client for your Linux Desktop
