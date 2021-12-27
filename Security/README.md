# Security Dataset

## Anomaly Detection

### DAD

> DAD is a semi-synthetic and labeled dataset consisting of seven days network activity with attacks spread over five days. It has three different types of anomalies: duplication, interception and modification on the MQTT message.

**From:** Centre for Information and Communications Technology Research (CITIC)

**Publish date:** 2020.07.22

**Paper:** [[sensors](https://www.mdpi.com/1424-8220/20/13/3745)] **Annotated Dataset for Anomaly Detection in a Data Center with IoT Sensors**

**Project page:** [[Github](https://github.com/dad-repository/dad)]

**Download:** 

- [[Github](https://github.com/dad-repository/dad)]
- **Type:** csv, xml, pcap.

| Date           | Description                                                  |
| -------------- | ------------------------------------------------------------ |
| Monday 21st    | there is no attacks                                          |
| Tuesday 22nd   | some packets have been removed, so packets are not labeled as attack |
| Wednesday 23rd | a modification of packets is made between 4h and 6h          |
| Thursday 24th  | insertion of packets in less than 5 minutes at 3h            |
| Friday 25th    | a mix of interception, duplication and modification is done at 6h and between the 14-16h |
| Saturday 26th  | a mix of interception, duplication and modification is done at 6h and between the 14-16h |
| Sunday 27th    | there is no attacks                                          |



## References

1. 

