# Changelog

## [**Next release**](https://github.com/netdata/netdata/tree/HEAD)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.23.1...HEAD)

**Merged pull requests:**

- Bring code owner for missing directory [\#9465](https://github.com/netdata/netdata/pull/9465) ([thiagoftsm](https://github.com/thiagoftsm))
- Read the prefix option from instance config sections [\#9463](https://github.com/netdata/netdata/pull/9463) ([vlvkobal](https://github.com/vlvkobal))
- Fix a coverity defect [\#9462](https://github.com/netdata/netdata/pull/9462) ([vlvkobal](https://github.com/vlvkobal))
- Fix the exporting engine unit tests [\#9460](https://github.com/netdata/netdata/pull/9460) ([vlvkobal](https://github.com/vlvkobal))
- Wrap header definitions in compilation conditions [\#9458](https://github.com/netdata/netdata/pull/9458) ([candrews](https://github.com/candrews))
- Fixes error in Swagger Documentation [\#9417](https://github.com/netdata/netdata/pull/9417) ([underhood](https://github.com/underhood))
- Added missing caps letters [\#9379](https://github.com/netdata/netdata/pull/9379) ([Jiab77](https://github.com/Jiab77))
- Fixed typo in the streaming readme [\#9378](https://github.com/netdata/netdata/pull/9378) ([Jiab77](https://github.com/Jiab77))
- ipfs-plugin: change HTTP method to make it compatible with ipfs 0.5.0+ [\#9248](https://github.com/netdata/netdata/pull/9248) ([RubenKelevra](https://github.com/RubenKelevra))
- UrlService add support get headers [\#9236](https://github.com/netdata/netdata/pull/9236) ([vsc55](https://github.com/vsc55))
- Add infiniband monitoring to collector proc.plugin [\#9091](https://github.com/netdata/netdata/pull/9091) ([Saruspete](https://github.com/Saruspete))

## [v1.23.1](https://github.com/netdata/netdata/tree/v1.23.1) (2020-07-01)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.23.0...v1.23.1)

**Merged pull requests:**

-  Fix the unittest execution [\#9445](https://github.com/netdata/netdata/pull/9445) ([thiagoftsm](https://github.com/thiagoftsm))
- Fix children version on stream [\#9438](https://github.com/netdata/netdata/pull/9438) ([thiagoftsm](https://github.com/thiagoftsm))
- Disallow dimensions and chart being obsolete and archived simultaneously. [\#9436](https://github.com/netdata/netdata/pull/9436) ([mfundul](https://github.com/mfundul))
- Fix internal registry  [\#9434](https://github.com/netdata/netdata/pull/9434) ([thiagoftsm](https://github.com/thiagoftsm))
- Fixed duplicate alarm ids in health-log.db [\#9428](https://github.com/netdata/netdata/pull/9428) ([stelfrag](https://github.com/stelfrag))
- Correct virtualization detection in system-info.sh [\#9425](https://github.com/netdata/netdata/pull/9425) ([Ferroin](https://github.com/Ferroin))
- Stop reading from /proc/sys/kernel/osrelease at trailing newline [\#9374](https://github.com/netdata/netdata/pull/9374) ([sjuxax](https://github.com/sjuxax))
- Show cgroups/containers ran by Kubelet without access to Kubernetes cluster information [\#9321](https://github.com/netdata/netdata/pull/9321) ([cakrit](https://github.com/cakrit))

## [v1.23.0](https://github.com/netdata/netdata/tree/v1.23.0) (2020-06-25)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.22.1...v1.23.0)

**Merged pull requests:**

- Fix Coverity Defect CID 304732 [\#9402](https://github.com/netdata/netdata/pull/9402) ([amoss](https://github.com/amoss))
- update synology.md [\#9400](https://github.com/netdata/netdata/pull/9400) ([pkrasam](https://github.com/pkrasam))
- Added OpenSSL to list of dependencies for Netdata Cloud. [\#9398](https://github.com/netdata/netdata/pull/9398) ([Ferroin](https://github.com/Ferroin))
- Fix missing host variables on stream [\#9396](https://github.com/netdata/netdata/pull/9396) ([thiagoftsm](https://github.com/thiagoftsm))
- Fix a bug in the simple exporting connector [\#9389](https://github.com/netdata/netdata/pull/9389) ([vlvkobal](https://github.com/vlvkobal))
- Fixes the race-hazard in streaming during the shutdown sequence [\#9370](https://github.com/netdata/netdata/pull/9370) ([amoss](https://github.com/amoss))
- Fixed ACLK shutdown sequence [\#9367](https://github.com/netdata/netdata/pull/9367) ([underhood](https://github.com/underhood))
- Improved error handling and recovery during compaction and metadata log replay [\#9354](https://github.com/netdata/netdata/pull/9354) ([stelfrag](https://github.com/stelfrag))
- Add guide for troubleshooting with eBPF metrics [\#9352](https://github.com/netdata/netdata/pull/9352) ([joelhans](https://github.com/joelhans))
- dashboard v1.0.14\_2 [\#9350](https://github.com/netdata/netdata/pull/9350) ([jacekkolasa](https://github.com/jacekkolasa))
- Revert "Override linker and include paths for static builds." [\#9343](https://github.com/netdata/netdata/pull/9343) ([Ferroin](https://github.com/Ferroin))
- installer: update go.d.plugin version to v0.19.2 [\#9340](https://github.com/netdata/netdata/pull/9340) ([ilyam8](https://github.com/ilyam8))
- Get netdata execution path early to avoid user permission issues [\#9339](https://github.com/netdata/netdata/pull/9339) ([mfundul](https://github.com/mfundul))
- Fix issues on ebpf.plugin [\#9333](https://github.com/netdata/netdata/pull/9333) ([thiagoftsm](https://github.com/thiagoftsm))
- Remove Gentoo from CI [\#9327](https://github.com/netdata/netdata/pull/9327) ([prologic](https://github.com/prologic))
- Fixed invalid memory access [\#9326](https://github.com/netdata/netdata/pull/9326) ([stelfrag](https://github.com/stelfrag))
- Add support for persistent metadata [\#9324](https://github.com/netdata/netdata/pull/9324) ([stelfrag](https://github.com/stelfrag))
- Change streaming terminology to parent-child in the code [\#9323](https://github.com/netdata/netdata/pull/9323) ([amoss](https://github.com/amoss))
- Fix check for remote write header in unit tests [\#9318](https://github.com/netdata/netdata/pull/9318) ([vlvkobal](https://github.com/vlvkobal))
- Adds missing files for streaming changes into cmake build [\#9316](https://github.com/netdata/netdata/pull/9316) ([underhood](https://github.com/underhood))
- apps\_groups.conf: add agent-service-discovery [\#9315](https://github.com/netdata/netdata/pull/9315) ([ilyam8](https://github.com/ilyam8))
- Change streaming terminology to parent/child in docs [\#9312](https://github.com/netdata/netdata/pull/9312) ([joelhans](https://github.com/joelhans))
- Added dummy `--enable-ebpf` flag to avoid breaking updates. [\#9310](https://github.com/netdata/netdata/pull/9310) ([Ferroin](https://github.com/Ferroin))
- installer: update go.d.plugin version to v0.19.1 [\#9309](https://github.com/netdata/netdata/pull/9309) ([ilyam8](https://github.com/ilyam8))
- Correct the repo in the docs for CentOS 8. [\#9308](https://github.com/netdata/netdata/pull/9308) ([Ferroin](https://github.com/Ferroin))
- Fix consistency of kubernetes cgroup names [\#9303](https://github.com/netdata/netdata/pull/9303) ([cakrit](https://github.com/cakrit))
- Fix remote write HTTP header [\#9302](https://github.com/netdata/netdata/pull/9302) ([vlvkobal](https://github.com/vlvkobal))
- minor copy edits [\#9298](https://github.com/netdata/netdata/pull/9298) ([MeganBishopMoore](https://github.com/MeganBishopMoore))
- Fix crash in \#9291 [\#9297](https://github.com/netdata/netdata/pull/9297) ([amoss](https://github.com/amoss))
- Add frontmatter to Matrix notifications doc [\#9295](https://github.com/netdata/netdata/pull/9295) ([joelhans](https://github.com/joelhans))
- installer: update go.d.plugin version to v0.19.0 [\#9294](https://github.com/netdata/netdata/pull/9294) ([ilyam8](https://github.com/ilyam8))
- dashboard\_info.js: ebpf: fix close code block [\#9293](https://github.com/netdata/netdata/pull/9293) ([ilyam8](https://github.com/ilyam8))
- Add guide to exporting metrics to Graphite [\#9285](https://github.com/netdata/netdata/pull/9285) ([joelhans](https://github.com/joelhans))
- update\_apps\_groups: Bring imunify and lsphp to apps groups [\#9284](https://github.com/netdata/netdata/pull/9284) ([thiagoftsm](https://github.com/thiagoftsm))
- Adds metrics for ACLK performance and status [\#9269](https://github.com/netdata/netdata/pull/9269) ([underhood](https://github.com/underhood))
- Fix Coverity defects 359164, 359165 and 358989. [\#9268](https://github.com/netdata/netdata/pull/9268) ([amoss](https://github.com/amoss))
- Move/refactor docs to accomodate new Guides section on Learn [\#9266](https://github.com/netdata/netdata/pull/9266) ([joelhans](https://github.com/joelhans))
- Cleanup of main README and registry doc [\#9265](https://github.com/netdata/netdata/pull/9265) ([joelhans](https://github.com/joelhans))
- Fixed handling of OpenSSL on CentOS/RHEL by bundling a static copy and selecting a configuration directory at install time. [\#9263](https://github.com/netdata/netdata/pull/9263) ([Ferroin](https://github.com/Ferroin))
- Fix frontmatter in circular\_buffer README [\#9262](https://github.com/netdata/netdata/pull/9262) ([joelhans](https://github.com/joelhans))
- Doc: Add missing slash [\#9257](https://github.com/netdata/netdata/pull/9257) ([oneoneonepig](https://github.com/oneoneonepig))
- Fixes documentation ambiguity leading into issue \#8239 [\#9255](https://github.com/netdata/netdata/pull/9255) ([underhood](https://github.com/underhood))
- Add new exporting "home base" document [\#9246](https://github.com/netdata/netdata/pull/9246) ([joelhans](https://github.com/joelhans))
- Add a random offset to the update script when running non-interactively. [\#9245](https://github.com/netdata/netdata/pull/9245) ([Ferroin](https://github.com/Ferroin))
- Add CI check for building against LibreSSL [\#9216](https://github.com/netdata/netdata/pull/9216) ([prologic](https://github.com/prologic))
- Gap-detection and slew [\#9214](https://github.com/netdata/netdata/pull/9214) ([amoss](https://github.com/amoss))
- Update eBPF to use kernel-collector version 0.4.0. [\#9212](https://github.com/netdata/netdata/pull/9212) ([Ferroin](https://github.com/Ferroin))
- Add link to kernel docs for ftrace [\#9211](https://github.com/netdata/netdata/pull/9211) ([Steve8291](https://github.com/Steve8291))
- fix small typo [\#9205](https://github.com/netdata/netdata/pull/9205) ([Steve8291](https://github.com/Steve8291))
- Update apps.plugin documentation and dashboard.info [\#9199](https://github.com/netdata/netdata/pull/9199) ([thiagoftsm](https://github.com/thiagoftsm))
- fix compilation for older systems [\#9198](https://github.com/netdata/netdata/pull/9198) ([ktsaou](https://github.com/ktsaou))
- Support for matrix notifications [\#9196](https://github.com/netdata/netdata/pull/9196) ([okias](https://github.com/okias))
- Clean type\_name in exporting connector instance configuration [\#9188](https://github.com/netdata/netdata/pull/9188) ([vlvkobal](https://github.com/vlvkobal))
- Fixed cmake build affected by \#9074 [\#9186](https://github.com/netdata/netdata/pull/9186) ([stelfrag](https://github.com/stelfrag))
- Fix exporting unit tests [\#9183](https://github.com/netdata/netdata/pull/9183) ([vlvkobal](https://github.com/vlvkobal))
- Fix missing ebpf packaging files from dist archive [\#9182](https://github.com/netdata/netdata/pull/9182) ([prologic](https://github.com/prologic))
- cov\_358988: Remove coverity bug [\#9180](https://github.com/netdata/netdata/pull/9180) ([thiagoftsm](https://github.com/thiagoftsm))
- Integration between eBPF and Apps [\#9178](https://github.com/netdata/netdata/pull/9178) ([thiagoftsm](https://github.com/thiagoftsm))
- Improve dbengine docs for streaming setups [\#9177](https://github.com/netdata/netdata/pull/9177) ([joelhans](https://github.com/joelhans))
- Really prevent overwriting netdata.conf on static installs. [\#9174](https://github.com/netdata/netdata/pull/9174) ([Ferroin](https://github.com/Ferroin))
- Remove knatsakis and ncmans from CODEOWNERS for the agent. [\#9173](https://github.com/netdata/netdata/pull/9173) ([Ferroin](https://github.com/Ferroin))
- Added health check functionality to our Docker images. [\#9172](https://github.com/netdata/netdata/pull/9172) ([Ferroin](https://github.com/Ferroin))
- Remove the experimental label from the exporting engine documentation [\#9171](https://github.com/netdata/netdata/pull/9171) ([vlvkobal](https://github.com/vlvkobal))
- Fix reliability of kickstart/kickstart-static64 with checksums sometimes failing [\#9165](https://github.com/netdata/netdata/pull/9165) ([prologic](https://github.com/prologic))
- Revert "Introduce a random sleep in the Netdata updater" [\#9161](https://github.com/netdata/netdata/pull/9161) ([prologic](https://github.com/prologic))
- Fixed bug in accepting empty lines in parser [\#9158](https://github.com/netdata/netdata/pull/9158) ([stelfrag](https://github.com/stelfrag))
- Fixed coverity warning \(CID 358971\) [\#9157](https://github.com/netdata/netdata/pull/9157) ([stelfrag](https://github.com/stelfrag))
- Update README.md [\#9151](https://github.com/netdata/netdata/pull/9151) ([stephenrauch](https://github.com/stephenrauch))
- fix typo in step-03.md [\#9150](https://github.com/netdata/netdata/pull/9150) ([waybeforenow](https://github.com/waybeforenow))
- eBPF modular [\#9148](https://github.com/netdata/netdata/pull/9148) ([thiagoftsm](https://github.com/thiagoftsm))
- Fix error \> emerge openssl-devel [\#9141](https://github.com/netdata/netdata/pull/9141) ([vsc55](https://github.com/vsc55))
- Revert "Fix macOS builds building and linking against openssl" [\#9137](https://github.com/netdata/netdata/pull/9137) ([prologic](https://github.com/prologic))
- Fix docs CI to handle absolute links between docs [\#9132](https://github.com/netdata/netdata/pull/9132) ([joelhans](https://github.com/joelhans))
- Check update interval for exporting connector instance [\#9131](https://github.com/netdata/netdata/pull/9131) ([vlvkobal](https://github.com/vlvkobal))
- Add CI for our Static Netdata builds \(which kickstart-static64 uses\) [\#9130](https://github.com/netdata/netdata/pull/9130) ([prologic](https://github.com/prologic))
- Fix paths to trigger docs CI workflow [\#9128](https://github.com/netdata/netdata/pull/9128) ([joelhans](https://github.com/joelhans))
- Remove the unused Dockerfile.docs and associated Docker Hub image [\#9126](https://github.com/netdata/netdata/pull/9126) ([prologic](https://github.com/prologic))
- Send anonymous statistics from backends and exporting engine [\#9125](https://github.com/netdata/netdata/pull/9125) ([vlvkobal](https://github.com/vlvkobal))
- Fix buffer splitting in the Kinesis exporting connector [\#9122](https://github.com/netdata/netdata/pull/9122) ([vlvkobal](https://github.com/vlvkobal))
- Update the kernel-collector version to v0.2.0 [\#9118](https://github.com/netdata/netdata/pull/9118) ([prologic](https://github.com/prologic))
- Dynamic memory cleanup for Pub/Sub exporting connector [\#9112](https://github.com/netdata/netdata/pull/9112) ([vlvkobal](https://github.com/vlvkobal))
- Package: obsoletes conflicting EPEL packages \(\#6879 \#8784\) [\#9108](https://github.com/netdata/netdata/pull/9108) ([Saruspete](https://github.com/Saruspete))
- Add support for eBPF for Netdata static64 \(kickstart-static64.sh\) [\#9104](https://github.com/netdata/netdata/pull/9104) ([prologic](https://github.com/prologic))
- Exporting cleanup [\#9098](https://github.com/netdata/netdata/pull/9098) ([thiagoftsm](https://github.com/thiagoftsm))
- Introduce a random sleep in the Netdata updater [\#9079](https://github.com/netdata/netdata/pull/9079) ([prologic](https://github.com/prologic))
- New alarms \(exporting and Backend\) [\#9075](https://github.com/netdata/netdata/pull/9075) ([thiagoftsm](https://github.com/thiagoftsm))
- Implement new incremental parser [\#9074](https://github.com/netdata/netdata/pull/9074) ([stelfrag](https://github.com/stelfrag))
- OpenTSDB and TLS [\#9068](https://github.com/netdata/netdata/pull/9068) ([thiagoftsm](https://github.com/thiagoftsm))
- Added required bundle for libuuid on ClearLinux. [\#9060](https://github.com/netdata/netdata/pull/9060) ([Ferroin](https://github.com/Ferroin))
- Add notes/known issues section to installation page [\#9053](https://github.com/netdata/netdata/pull/9053) ([joelhans](https://github.com/joelhans))
- Missing error aws [\#9048](https://github.com/netdata/netdata/pull/9048) ([thiagoftsm](https://github.com/thiagoftsm))
- Change backends to exporting engine in general documentation pages [\#9045](https://github.com/netdata/netdata/pull/9045) ([vlvkobal](https://github.com/vlvkobal))
- Missing checks exporting [\#9034](https://github.com/netdata/netdata/pull/9034) ([thiagoftsm](https://github.com/thiagoftsm))
- Move nc backend [\#9030](https://github.com/netdata/netdata/pull/9030) ([thiagoftsm](https://github.com/thiagoftsm))
- Fixes enable/start of netdata service in debian package [\#9005](https://github.com/netdata/netdata/pull/9005) ([MrFreezeex](https://github.com/MrFreezeex))
- Update step-10.md [\#9000](https://github.com/netdata/netdata/pull/9000) ([Jelmerrevers](https://github.com/Jelmerrevers))
- Fix suid bits on plugin for debian packaging [\#8996](https://github.com/netdata/netdata/pull/8996) ([MrFreezeex](https://github.com/MrFreezeex))
- Fix incorrect issue link URL in install-required-packages.sh [\#8911](https://github.com/netdata/netdata/pull/8911) ([prologic](https://github.com/prologic))
- Improve PR Guidelines for Developers and Contributors. [\#8809](https://github.com/netdata/netdata/pull/8809) ([prologic](https://github.com/prologic))
- Remove old docs generation tooling [\#8783](https://github.com/netdata/netdata/pull/8783) ([prologic](https://github.com/prologic))

## [v1.22.1](https://github.com/netdata/netdata/tree/v1.22.1) (2020-05-12)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.22.0...v1.22.1)

**Merged pull requests:**

- Fix the latency issue on the ACLK and suppress the diagnostics [\#8992](https://github.com/netdata/netdata/pull/8992) ([amoss](https://github.com/amoss))
- Fixed bundling of React dashboard in DEB and RPM packages. [\#8988](https://github.com/netdata/netdata/pull/8988) ([Ferroin](https://github.com/Ferroin))
- Restore old semantics of "netdata -W set" command [\#8987](https://github.com/netdata/netdata/pull/8987) ([mfundul](https://github.com/mfundul))
- Added JSON-C packaging fils to make dist. [\#8986](https://github.com/netdata/netdata/pull/8986) ([Ferroin](https://github.com/Ferroin))
- Remove check for old alarm status \(CID 358436\) [\#8978](https://github.com/netdata/netdata/pull/8978) ([stelfrag](https://github.com/stelfrag))
- Remove UNUSED word from flood protection documentation [\#8964](https://github.com/netdata/netdata/pull/8964) ([mfundul](https://github.com/mfundul))
- Docs: Update with go-live claiming and ACLK information \(\#8859\) [\#8960](https://github.com/netdata/netdata/pull/8960) ([prologic](https://github.com/prologic))
- Docs: Fix internal links and remove obsolete admonitions [\#8946](https://github.com/netdata/netdata/pull/8946) ([joelhans](https://github.com/joelhans))
- Fix shutdown via netdatacli with musl C library [\#8931](https://github.com/netdata/netdata/pull/8931) ([mfundul](https://github.com/mfundul))

## [v1.22.0](https://github.com/netdata/netdata/tree/v1.22.0) (2020-05-11)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.21.1...v1.22.0)

**Merged pull requests:**

- Updates main copyright and links for the year 2020 [\#8937](https://github.com/netdata/netdata/pull/8937) ([zack-shoylev](https://github.com/zack-shoylev))
- Docs: Add custom label to collectors frontmatter to fix sidebar titles [\#8936](https://github.com/netdata/netdata/pull/8936) ([joelhans](https://github.com/joelhans))
- Fix missing NETDATA\_STOP\_CMD in netdata-installer.sh [\#8897](https://github.com/netdata/netdata/pull/8897) ([prologic](https://github.com/prologic))
- Update Running-behind-nginx.md [\#8880](https://github.com/netdata/netdata/pull/8880) ([slavaGanzin](https://github.com/slavaGanzin))
- Added docmentation about workaround for clang build errors. [\#8867](https://github.com/netdata/netdata/pull/8867) ([Ferroin](https://github.com/Ferroin))
- correct typo [\#8861](https://github.com/netdata/netdata/pull/8861) ([carehart](https://github.com/carehart))
- Fix command name for getting postfix queue [\#8857](https://github.com/netdata/netdata/pull/8857) ([ghasrfakhri](https://github.com/ghasrfakhri))
- Fix kickstart error removing old cron symlink [\#8849](https://github.com/netdata/netdata/pull/8849) ([prologic](https://github.com/prologic))
- Fixed bundling of dashboard in binary packages. [\#8844](https://github.com/netdata/netdata/pull/8844) ([Ferroin](https://github.com/Ferroin))
- Add CI check for building against LibreSSL [\#8842](https://github.com/netdata/netdata/pull/8842) ([prologic](https://github.com/prologic))
- Removed old function call in netdata-installer.sh [\#8824](https://github.com/netdata/netdata/pull/8824) ([Ferroin](https://github.com/Ferroin))
- Fix build and add bundle-dashbaord.sh to dist\_noinst\_DATA [\#8823](https://github.com/netdata/netdata/pull/8823) ([prologic](https://github.com/prologic))
- Docs: Add instructions to persist metrics and restart policy [\#8813](https://github.com/netdata/netdata/pull/8813) ([joelhans](https://github.com/joelhans))
- Fix typo in netdata-installer [\#8811](https://github.com/netdata/netdata/pull/8811) ([adamwolf](https://github.com/adamwolf))
- health: fix mdstat `failed devices` alarm [\#8794](https://github.com/netdata/netdata/pull/8794) ([ilyam8](https://github.com/ilyam8))
- dashboard v0.4.18 [\#8786](https://github.com/netdata/netdata/pull/8786) ([jacekkolasa](https://github.com/jacekkolasa))
- fix\_lock: Add the missing lock [\#8780](https://github.com/netdata/netdata/pull/8780) ([thiagoftsm](https://github.com/thiagoftsm))
- Added JSON-C dependency handling to instlal and packaging. [\#8776](https://github.com/netdata/netdata/pull/8776) ([Ferroin](https://github.com/Ferroin))
- TTL headers [\#8760](https://github.com/netdata/netdata/pull/8760) ([amoss](https://github.com/amoss))
- web/gui/demo2.html: Silence Netlify's mixed content warnings [\#8759](https://github.com/netdata/netdata/pull/8759) ([knatsakis](https://github.com/knatsakis))
- dashboard v.0.4.17: [\#8757](https://github.com/netdata/netdata/pull/8757) ([jacekkolasa](https://github.com/jacekkolasa))
- Docs: Add Docker instructions to claiming [\#8755](https://github.com/netdata/netdata/pull/8755) ([joelhans](https://github.com/joelhans))
- Fixed issue in `system-info.sh`regarding the parsing of `lscpu` output. [\#8754](https://github.com/netdata/netdata/pull/8754) ([Ferroin](https://github.com/Ferroin))
- Use a prefix for the old dashboard. [\#8752](https://github.com/netdata/netdata/pull/8752) ([Ferroin](https://github.com/Ferroin))
- Additional cases for the thread exit fix [\#8750](https://github.com/netdata/netdata/pull/8750) ([amoss](https://github.com/amoss))
- health/portcheck: remove no-clear-notification option [\#8748](https://github.com/netdata/netdata/pull/8748) ([ilyam8](https://github.com/ilyam8))
- packaging/docker/{build,publish}.sh: Simplify scripts. Support only single ARCH [\#8747](https://github.com/netdata/netdata/pull/8747) ([knatsakis](https://github.com/knatsakis))

## [v1.21.1](https://github.com/netdata/netdata/tree/v1.21.1) (2020-04-13)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.21.0...v1.21.1)

## [v1.21.0](https://github.com/netdata/netdata/tree/v1.21.0) (2020-04-06)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.20.0...v1.21.0)

## [v1.20.0](https://github.com/netdata/netdata/tree/v1.20.0) (2020-02-21)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.19.0...v1.20.0)

## [v1.19.0](https://github.com/netdata/netdata/tree/v1.19.0) (2019-11-27)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.18.1...v1.19.0)

## [v1.18.1](https://github.com/netdata/netdata/tree/v1.18.1) (2019-10-18)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.18.0...v1.18.1)

## [v1.18.0](https://github.com/netdata/netdata/tree/v1.18.0) (2019-10-10)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.17.1...v1.18.0)

## [v1.17.1](https://github.com/netdata/netdata/tree/v1.17.1) (2019-09-12)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.17.0...v1.17.1)

## [v1.17.0](https://github.com/netdata/netdata/tree/v1.17.0) (2019-09-03)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.16.1...v1.17.0)

## [v1.16.1](https://github.com/netdata/netdata/tree/v1.16.1) (2019-07-31)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.16.0...v1.16.1)

## [v1.16.0](https://github.com/netdata/netdata/tree/v1.16.0) (2019-07-08)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.15.0...v1.16.0)

## [v1.15.0](https://github.com/netdata/netdata/tree/v1.15.0) (2019-05-22)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.14.0...v1.15.0)

## [v1.14.0](https://github.com/netdata/netdata/tree/v1.14.0) (2019-04-18)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.14.0-rc0...v1.14.0)

## [v1.14.0-rc0](https://github.com/netdata/netdata/tree/v1.14.0-rc0) (2019-03-30)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.13.0...v1.14.0-rc0)

## [v1.13.0](https://github.com/netdata/netdata/tree/v1.13.0) (2019-03-14)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.2...v1.13.0)

## [v1.12.2](https://github.com/netdata/netdata/tree/v1.12.2) (2019-02-28)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.1...v1.12.2)

## [v1.12.1](https://github.com/netdata/netdata/tree/v1.12.1) (2019-02-21)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.0...v1.12.1)

## [v1.12.0](https://github.com/netdata/netdata/tree/v1.12.0) (2019-02-06)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.0-rc3...v1.12.0)

## [v1.12.0-rc3](https://github.com/netdata/netdata/tree/v1.12.0-rc3) (2019-01-17)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.0-rc2...v1.12.0-rc3)

## [v1.12.0-rc2](https://github.com/netdata/netdata/tree/v1.12.0-rc2) (2019-01-03)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.0-rc1...v1.12.0-rc2)

## [v1.12.0-rc1](https://github.com/netdata/netdata/tree/v1.12.0-rc1) (2018-12-19)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.12.0-rc0...v1.12.0-rc1)

## [v1.12.0-rc0](https://github.com/netdata/netdata/tree/v1.12.0-rc0) (2018-12-06)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.11.1...v1.12.0-rc0)

## [v1.11.1](https://github.com/netdata/netdata/tree/v1.11.1) (2018-11-22)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.11.0...v1.11.1)

## [v1.11.0](https://github.com/netdata/netdata/tree/v1.11.0) (2018-11-02)

[Full Changelog](https://github.com/netdata/netdata/compare/v1.10.0...v1.11.0)



\* *This Changelog was automatically generated by [github_changelog_generator](https://github.com/github-changelog-generator/github-changelog-generator)*
