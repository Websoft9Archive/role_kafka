Ansible Role: Kafka
=========

This role is for you to install **Kafka**  

If you want this role to support more applications, you can [**submit Issues**](https://github.com/websoft9dev/role_kafka/issues/new/choose) for us.

## Requirements

Make sure these requirements need before the installation:

| **Items**      | **Details** |
| ------------------| ------------------|
| Operating system | CentOS7.x, Ubuntu18.04,Ubuntu20.04. AmazonLinux2 |
| Python version | Python2,Python3  |
| Python components |  requests, docker-compose  |
| Runtime | JDK |

## Related roles

This Role does not depend on other role variables in syntax, but it depend on other role before:

```
roles:
  - { role: role_common }
  - { role：role_jdk }
```


## Variables

The main variables of this Role and how to use them are as follows:

| **Items**      | **Details** | **Format**  | **Need to assignment** |
| ------------------| ------------------|-----|-----|
| kafka_version | "2.7.0" | String | No |
| kafka_jmx_port | 9988 | String| No |

## Example

```
kafka_version: "2.7.0"
kafka_jmx_port: "9988"  
```

## Resources

* [Documentation](https://support.websoft9.com/docs/kafka)
* [Deploy by Image](https://apps.websoft9.com/kafka)
* [Deploy by Script](https://github.com/websoft9/ansible-kafka)


## License

[LGPL-3.0](/License.md), Additional Terms: It is not allowed to publish free or paid image based on this repository in any Cloud platform's Marketplace.

Copyright (c) 2016-present, Websoft9

## FAQ

#### Can I install web-based GUI from this repository?

No
