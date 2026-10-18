# OneUptime Homebrew tap

```bash
brew install oneuptime/tap/oneuptime-infrastructure-agent
```

Then connect the agent to your Server / VM monitor and start it:

```bash
sudo oneuptime-infrastructure-agent configure --secret-key=YOUR_SECRET_KEY --oneuptime-url=https://oneuptime.com
sudo oneuptime-infrastructure-agent start
```

The full guide, including upgrades: [Server / VM Monitor](https://oneuptime.com/docs/monitor/server-monitor).

`Casks/` is written by OneUptime's release workflow: the `publish-infrastructure-agent-homebrew`
job in [OneUptime/oneuptime](https://github.com/OneUptime/oneuptime) commits each release's cask,
which GoReleaser generates. Do not edit it by hand.
