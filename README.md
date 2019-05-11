# ansible-crate
--------------


[![crate.io](https://raw.githubusercontent.com/hos7ein/ansible-crate/dev/pic/CrateDB.jpg)](https://crate.io)  [![ansible](https://raw.githubusercontent.com/hos7ein/ansible-crate/dev/pic/ansible.png)](https://ansible.com) [![docker](https://raw.githubusercontent.com/hos7ein/ansible-crate/dev/pic/docker.png)](https://docker.com)

### Introduction ###
CrateDB is a distributed SQL database management system that integrates a fully searchable document oriented data store. It is open-source, written in Java, based on a shared nothing architecture, and is designed for high scalability and includes components from Facebook Presto, Apache Lucene, Elasticsearch and Netty.
To fast deploy of CrateDB on server/s, I wrote `ansible-crate` project by Ansible. In this project, CrateDB will automatic deploy with Docker.

### Dependency ###
To use `ansible-crate` project you have need some packages for deploying it, in your Ansible machine you need this package:

* ansible


### Deploy ###
To deploy `ansible-crate` project, after clone the project in your Ansible machine, enter your server/s IP address and `node_name` in hosts file:

```
vi hosts
```

After that set information of your environment in variable file:

```
vi group_vars/all
```

Now for run Ansible Playbook you should run the beneath command:

```
ansible-playbook -i hosts main-playbook.yml
```


## Contact

**Project website**: https://github.com/hos7ein/ansible-crate

**Author**: Hossein Aghaie <hossein.a97@gmail.com>

**Twitter**: Hossein Aghaie [@hos7ein](https://twitter.com/hos7ein)


## License

ansible-ocserv source code is available under the GPL-3.0 [License](/LICENSE).
