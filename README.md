# Zookeeper BOSH release

```
$ bosh -d zookeeper deploy manifests/zookeeper.yml
$ bosh -d zookeeper run-errand smoke-tests
$ bosh -d zookeeper ssh -c '/var/vcap/jobs/zookeeper/bin/ctl status' -r
```
