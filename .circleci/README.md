```sh
$ curl -o /usr/local/bin/circleci https://circle-downloads.s3.amazonaws.com/releases/build_agent_wrapper/circleci && chmod +x /usr/local/bin/circleci
```

```sh
$ circleci config validate -c .circleci/config.yml
Receiving latest version of circleci...
INFO: We've built a brand new CLI for CircleCI! Please run 'circleci switch' to upgrade.
.circleci/config.yml is valid
```

```sh
$ circleci build
```
