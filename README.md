# ansible-macos-hardening-pf-plist

Configures pf with default-drop ingress policy and installs a launchd plist configuration that will enable the pf packet filter.
The ansible role is intended to be cloned and run locally on MacOS High Sierra

```
.
├── README.md
├── ansible.cfg
├── deploy.yml
├── hosts
├── roles
│   └── pfctl_plist
│       ├── files
│       │   ├── com.darkstar
│       │   └── com.darkstar.plist
│       └── tasks
│           └── main.yml
└── run.sh
```

## Example:

```
./run.sh -vvv -C
```
