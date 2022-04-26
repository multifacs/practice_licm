# practice_licm

You might need to install packages like build-essential, cpuset and perf. Note that perf is platform-specific.

Installing perf on Ubuntu:
```bash
sudo apt-get install linux-tools-common linux-tools-generic linux-tools-`uname -r`
```
https://askubuntu.com/questions/50145/how-to-install-perf-monitoring-tool

Installing perf on Mint:
Follow the instructions in apt

## Instructions:

Launch every script file

```bash
bash 1-initial-setup
bash 2-disable-licm
bash 3-no-licm-build
bash 4-build-cpp
bash 5-setup-for-benchmarking
bash 6-benchmark
```

Initial setup and no licm build will take up around 30 minutes each
