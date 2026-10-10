<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="steelreed-lockup-dark.svg">
    <img src="steelreed-lockup-light.svg" width="320" alt="Steelreed">
  </picture>
</p>

<p align="center"><b>Open-source tools for the parts of your backend nobody is watching.</b></p>

<p align="center"><a href="https://steelreed.com">steelreed.com</a></p>

Steelreed is a small studio in Vietnam. We build developer tools you can run on your own server for
free, and run them for you when you would rather not.

## Projects

| Project | What it does | Status |
|---|---|---|
| [Cronbell](https://steelreed.com/cronbell/) | Monitoring for cron jobs, scheduled tasks and background workers. Add one line to a job and get a message on Telegram, Slack or email when it misses a run, fails or runs too long. Self-hosted with one Docker command. | In development, [early access](https://steelreed.com/cronbell/#access) open |
| [QueryFence](https://steelreed.com/queryfence/) ([GitHub](https://github.com/steelreed/queryfence)) | SQL checks for Java tests. Fails the build when a query your tests run forgets its tenant filter, and names the line that wrote it. | 0.1.0 on Maven Central |

## How we build

- **Self-hosting is the full product.** Nothing is removed from the open-source version to sell the cloud one.
- **When unsure, say so.** A tool that cannot tell whether something is safe reports it.
- **Show the misses too.** We test our tools on real applications and publish the false alarms with the real catches.
- **Small releases, dated changelog.** Every change goes through a pull request and CI.

## Contact

- Security reports: read our [security policy](https://github.com/steelreed/.github/blob/main/SECURITY.md).
- Everything else: hello@steelreed.com
