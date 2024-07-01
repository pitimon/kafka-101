# kafka-101
 KRaft

[UUID Gen](https://sleeplessbeastie.eu/2021/10/22/how-to-generate-kafka-cluster-id/)
```
./bin/kafka-storage.sh random-uuid

cat /proc/sys/kernel/random/uuid | tr -d '-' | base64 | cut -b 1-22

```