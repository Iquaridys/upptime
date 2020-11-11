# [![Upptime](https://raw.githubusercontent.com/upptime/upptime.js.org/master/static/img/logo.svg)](https://upptime.js.org)

<!--start: description-->

Upptime (https://upptime.js.org) is the open-source uptime monitor and status page, powered entirely by GitHub Actions and Issues.

<!--end: description-->

[![Uptime CI](https://github.com/koj-co/upptime/workflows/Uptime%20CI/badge.svg)](https://github.com/koj-co/upptime/actions?query=workflow%3A%22Uptime+CI%22)
[![Response Time CI](https://github.com/koj-co/upptime/workflows/Response%20Time%20CI/badge.svg)](https://github.com/koj-co/upptime/actions?query=workflow%3A%22Response+Time+CI%22)
[![Graphs CI](https://github.com/koj-co/upptime/workflows/Graphs%20CI/badge.svg)](https://github.com/koj-co/upptime/actions?query=workflow%3A%22Graphs+CI%22)
[![Static Site CI](https://github.com/koj-co/upptime/workflows/Static%20Site%20CI/badge.svg)](https://github.com/koj-co/upptime/actions?query=workflow%3A%22Static+Site+CI%22)
[![Summary CI](https://github.com/koj-co/upptime/workflows/Summary%20CI/badge.svg)](https://github.com/koj-co/upptime/actions?query=workflow%3A%22Summary+CI%22)

## [📈 Live Status](https://demo.upptime.js.org): <!--live status--> **🟨 Partial outage**

<!--start: status pages-->
<!-- This summary is generated by Upptime (https://github.com/upptime/upptime) -->
<!-- Do not edit this manually, your changes will be overwritten -->

| URL                                             | Status  | History                                                                                                | Response Time                                                                         | Uptime                                                                                                                                                                                                                     |
| ----------------------------------------------- | ------- | ------------------------------------------------------------------------------------------------------ | ------------------------------------------------------------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| [Google](https://www.google.com)                | 🟩 Up   | [google.yml](https://github.com/upptime/upptime/commits/master/history/google.yml)                     | <img alt="Response time graph" src="./graphs/google.png" height="20"> 86ms            | [![Uptime 100.00%](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fupptime%2Fupptime%2Fmaster%2Fapi%2Fgoogle%2Fuptime.json)](https://demo.upptime.js.org/history/google)                     |
| [Wikipedia](https://en.wikipedia.org)           | 🟩 Up   | [wikipedia.yml](https://github.com/upptime/upptime/commits/master/history/wikipedia.yml)               | <img alt="Response time graph" src="./graphs/wikipedia.png" height="20"> 151ms        | [![Uptime 100.00%](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fupptime%2Fupptime%2Fmaster%2Fapi%2Fwikipedia%2Fuptime.json)](https://demo.upptime.js.org/history/wikipedia)               |
| [Internet Archive](https://archive.org)         | 🟩 Up   | [internet-archive.yml](https://github.com/upptime/upptime/commits/master/history/internet-archive.yml) | <img alt="Response time graph" src="./graphs/internet-archive.png" height="20"> 544ms | [![Uptime 100.00%](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fupptime%2Fupptime%2Fmaster%2Fapi%2Finternet-archive%2Fuptime.json)](https://demo.upptime.js.org/history/internet-archive) |
| [Hacker News](https://news.ycombinator.com)     | 🟩 Up   | [hacker-news.yml](https://github.com/upptime/upptime/commits/master/history/hacker-news.yml)           | <img alt="Response time graph" src="./graphs/hacker-news.png" height="20"> 328ms      | [![Uptime 100.00%](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fupptime%2Fupptime%2Fmaster%2Fapi%2Fhacker-news%2Fuptime.json)](https://demo.upptime.js.org/history/hacker-news)           |
| [Broken Site](https://thissitedoesnotexist.com) | 🟥 Down | [broken-site.yml](https://github.com/upptime/upptime/commits/master/history/broken-site.yml)           | <img alt="Response time graph" src="./graphs/broken-site.png" height="20"> 0ms        | [![Uptime 0.00%](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fupptime%2Fupptime%2Fmaster%2Fapi%2Fbroken-site%2Fuptime.json)](https://demo.upptime.js.org/history/broken-site)             |
| Secret Site                                     | 🟩 Up   | [secret-site.yml](https://github.com/upptime/upptime/commits/master/history/secret-site.yml)           | <img alt="Response time graph" src="./graphs/secret-site.png" height="20"> 50ms       | [![Uptime 100.00%](https://img.shields.io/endpoint?url=https%3A%2F%2Fraw.githubusercontent.com%2Fupptime%2Fupptime%2Fmaster%2Fapi%2Fsecret-site%2Fuptime.json)](https://demo.upptime.js.org/history/secret-site)           |

<!--end: status pages-->

<!--start: docs-->

_This README is also available in [🇧🇷 Brazilian Portuguese](./README.pt-br.md)_

## ⭐ How it works

- GitHub Actions is used as an uptime monitor
  - Every 5 minutes, a workflow visits your website to make sure it's up
  - Response time is recorded every 6 hours and committed to git
  - Graphs of response time are generated every day
- GitHub Issues are used for incident reports
  - An issue is opened if an endpoint is down
  - People from your team are assigned to the issue
  - Incidents reports are posted as issue comments
  - Issues are locked so non-members cannot comment on them
  - Issues are closed automatically when your site comes back up
  - Slack notifications are sent on updates
- GitHub Pages are used for the status website
  - A simple, beautiful, and accessible PWA is generated
  - Built with Svelte and Sapper
  - Fetches data from this repository using the GitHub API

[![Screenshot of status website](https://raw.githubusercontent.com/upptime/upptime.js.org/master/static/img/screenshot-status.png)](https://upptime.js.org)

## 💝 Who's using Upptime

<!-- start: readme-repos-list -->
<!-- This list is auto-generated using koj-co/readme-repos-list -->
<!-- Do not edit this list manually, your changes will be overwritten -->
[![upptime/.github](https://images.weserv.nl/?url=avatars0.githubusercontent.com%2Fu%2F72692977%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://upptime.js.org)
[![phg98/upptime](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F12092302%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://demo.upptime.js.org)
[![gwanryo/upptime](https://images.weserv.nl/?url=avatars0.githubusercontent.com%2Fu%2F9062624%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.jmm.kr)
[![kong67/status](https://images.weserv.nl/?url=avatars2.githubusercontent.com%2Fu%2F2015787%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://upptime.github.io/upptime)
[![amblerkr/upptime](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F67187038%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.ambler.kr/)
[![derekjc/uptime](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F6804504%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://derekjc.github.io/uptime)
[![godong9/gdgo](https://images.weserv.nl/?url=avatars0.githubusercontent.com%2Fu%2F1950670%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://godong9.github.io/gdgo)
[![theleetax/uptime](https://images.weserv.nl/?url=avatars0.githubusercontent.com%2Fu%2F61379531%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.theleetax.com)
[![tadacodes/tada-uptime](https://images.weserv.nl/?url=avatars2.githubusercontent.com%2Fu%2F1444318%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://tada.wtf)
[![SOLPLPARTY/upptime](https://images.weserv.nl/?url=avatars2.githubusercontent.com%2Fu%2F37937762%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.solpl.party)
[![bbonkr/uptime](https://images.weserv.nl/?url=avatars0.githubusercontent.com%2Fu%2F3590545%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://uptime.bbon.me)
[![fullprofile/status_monitor](https://images.weserv.nl/?url=avatars2.githubusercontent.com%2Fu%2F20567415%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.waypath.io)
[![jjeaby/mew](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F32763196%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://jjeaby.github.io/mew)
[![OswaldLabsOpenSource/status](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F21421587%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.oswaldlabs.com)
[![ffsh/uptime](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F36672151%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.freifunk-suedholstein.de)
[![JonathanTreffler/status](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F28999431%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://JonathanTreffler.github.io/status)
[![Melangebox/status](https://images.weserv.nl/?url=avatars2.githubusercontent.com%2Fu%2F74049849%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.melangebox.com)
[![9min/upptime](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F12682061%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://9min.github.io/upptime)
[![picchiosat/HBLink-Uptime](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F8112062%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://uptime.hblink.it)
[![ludicroushq/upptime](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F40924967%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://uptime.ludicroushq.com)
[![brianjhanson/upptime-test](https://images.weserv.nl/?url=avatars0.githubusercontent.com%2Fu%2F1843073%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://upptime.brianhanson.net)
[![hada-io/upptime](https://images.weserv.nl/?url=avatars0.githubusercontent.com%2Fu%2F63682122%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://upptime.hada.io)
[![cubi-io/upptime](https://images.weserv.nl/?url=avatars0.githubusercontent.com%2Fu%2F73463162%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://upptime.cubi.so)
[![jeyraof/otzil-upptime](https://images.weserv.nl/?url=avatars0.githubusercontent.com%2Fu%2F2032880%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.otzil.com)
[![cocktail-lucas/cocktail-upptime](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F68220332%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://uptime.cocktailfunding.io)
[![kt-chelsea/status](https://images.weserv.nl/?url=avatars0.githubusercontent.com%2Fu%2F73645078%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://kt-chelsea.github.io/status)
[![classtinginc/upptime](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F25532257%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://upptime.classting.com)
[![jtprog/status.jtprog.ru](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F8199112%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.jtprog.ru)
[![chowdhary-org/status](https://images.weserv.nl/?url=avatars0.githubusercontent.com%2Fu%2F68894094%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://chowdhary-org.github.io/status/)
[![koj-co/status](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F65495851%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.koj.co)
[![Cleverclip/status](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F60980904%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://cleverclip.github.io/status/)
[![vidurb/status.vidur.dev](https://images.weserv.nl/?url=avatars0.githubusercontent.com%2Fu%2F7872957%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.vidur.dev)
[![intakefoods/status.intakefoods.kr](https://images.weserv.nl/?url=avatars0.githubusercontent.com%2Fu%2F15935353%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.intakefoods.kr)
[![mapeaks/mapeaks.github.io](https://images.weserv.nl/?url=avatars2.githubusercontent.com%2Fu%2F63757001%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://mapeaks.github.io)
[![coinsambacom/upptime](https://images.weserv.nl/?url=avatars2.githubusercontent.com%2Fu%2F69856662%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.coinsamba.com)
[![AnandChowdhary/status](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F2841780%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://anandchowdhary.github.io/status/)
[![arkk4/services.arkk4.com](https://images.weserv.nl/?url=avatars2.githubusercontent.com%2Fu%2F55327209%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://services.arkk4.com)
[![sebastianroming/status.webmonkey.io](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F200112%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.webmonkey.io)
[![armand1m-development/status](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F63721165%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.armand1m.dev)
[![r2fresh/chelsea](https://images.weserv.nl/?url=avatars2.githubusercontent.com%2Fu%2F329343%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://r2fresh.github.io/chelsea)
[![p1ass/status](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F30015728%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.p1ass.com)
[![rmateu/statuspage](https://images.weserv.nl/?url=avatars2.githubusercontent.com%2Fu%2F879149%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.mateu.me)
[![AiLingGo/mew](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F63590151%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://AiLingGo.github.io/mew)
[![dlunch/upptime](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F1371509%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://upptime.dlunch.net/)
[![Shulert/status](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F73318797%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.shulert.com)
[![Cravemob/mog-status](https://images.weserv.nl/?url=avatars0.githubusercontent.com%2Fu%2F3124637%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://mog-status.elchronicle.io)
[![EnsembleTravelGroup/EnsembleTravelUpptime](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F6980232%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.ensembletravel.com)
[![kspbot/uptime](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F72540124%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.ksp.wtf)
[![nhammond101/upptime](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F456479%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.happypengu.in)
[![bagiduid/uptime](https://images.weserv.nl/?url=avatars2.githubusercontent.com%2Fu%2F72654797%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.bagidu.id)
[![baealex/upptime](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F35596687%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.blex.me)
[![M17-Project/upptime](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F70443931%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://uptime.m17.link)
[![eartharoid-bot/status](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F73784129%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.eartharoid.me)
[![stethoscope-js/status](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F71249357%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://stethoscope-js.github.io/status/)
[![belhyun/yonsei-upptime](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F895026%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://belhyun.github.io/yonsei-upptime)
[![butteryoon/liveseeyou](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F1392084%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://butteryoon.github.io/liveseeyou)
[![mikesprague/skydark-status](https://images.weserv.nl/?url=avatars3.githubusercontent.com%2Fu%2F560705%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.skydark.app/)
[![humanscape/service-status](https://images.weserv.nl/?url=avatars0.githubusercontent.com%2Fu%2F38031863%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.humanscape.io)
[![mue/status](https://images.weserv.nl/?url=avatars2.githubusercontent.com%2Fu%2F58658585%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.muetab.com)
[![wakatime/statuspage](https://images.weserv.nl/?url=avatars1.githubusercontent.com%2Fu%2F4814844%3Fv%3D4&h=50&w=50&fit=cover&mask=circle&maxage=7d)](https://status.wakatime.com)
<!-- end: readme-repos-list -->

## 👩‍💻 [Documentation](https://upptime.js.org)

1. [How it works](https://upptime.js.org/docs)
1. [Getting started](https://upptime.js.org/docs/get-started)
1. [Configuration](https://upptime.js.org/docs/configuration)
1. [Triggers](https://upptime.js.org/docs/triggers)
1. [Notifications](https://upptime.js.org/docs/notifications)
1. [Badges](https://upptime.js.org/docs/badges)
1. [Packages](https://upptime.js.org/docs/packages)
1. [Contributing](https://upptime.js.org/docs/contributing)

### Concepts

#### Issues as incidents

When the GitHub Actions workflow detects that one of your URLs is down, it automatically opens a GitHub issue ([example issue #15](https://github.com/koj-co/upptime/issues/15)). You can add incident reports to this issue by adding comments. When your site comes back up, the issue will be closed automatically as well.

<table>
  <tr>
    <td>
      <img alt="Screenshot of GitHub issue" src="https://raw.githubusercontent.com/upptime/upptime.js.org/master/static/img/screenshot-issue.png">
    </td>
    <td>
      <img alt="Screenshot of incident page" src="https://raw.githubusercontent.com/upptime/upptime.js.org/master/static/img/screenshot-incident.png">
    </td>
  </tr>
</table>

#### Commits for response time

Four times per day, another workflow runs and records the response time of your websites. This data is commited to GitHub, so it's available in the commit history of each file ([example commit history](https://github.com/koj-co/upptime/commits/master/history/wikipedia.yml)). Then, the GitHub API is used to graph the response time history of each endpoint and to track when a site went down.

<table>
  <tr>
    <td>
      <img alt="Screenshot of GitHub commits" src="https://raw.githubusercontent.com/upptime/upptime.js.org/master/static/img/screenshot-history.png">
    </td>
    <td>
      <img alt="Screenshot of live status" src="https://raw.githubusercontent.com/upptime/upptime.js.org/master/static/img/screenshot-live-status.png">
    </td>
  </tr>
</table>
<!--end: docs-->

## 📄 License

- Code: [MIT](./LICENSE) © [Koj](https://koj.co)
- Data in the `./history` directory: [Open Database License](https://opendatacommons.org/licenses/odbl/1-0/)

<!--start: logo-->
<p align="center">
  <a href="https://koj.co">
    <img width="44" alt="Koj" src="https://kojcdn.com/v1598284251/website-v2/koj-github-footer_m089ze.svg">
  </a>
</p>
<p align="center">
  <sub>An open source project by <a href="https://koj.co">Koj</a>. <br> <a href="https://koj.co">Furnish your home in style, for as low as CHF175/month →</a></sub>
</p>
<!--end: logo-->
