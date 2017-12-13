# Servus
_(it's a working title)_

The goal of this project is to implement the additional services 
needed for a stand alone sensor deployment on an isolated network segment.
The goal is to implement the core infrastructure services to enable
deployment of [RockNSM](http://rocknsm.io), [CAPESstack](http://capestack.io),
and similar projects by meeting the prerequisite needs on baremetal and
possibly appliances, as needed.

## Project Layout

```
ansible/   # Contains ansible playbooks and roles
contrib/   # Contains additional project-related tools/scripts
docs/      # Contains project documentation written in markdown for mkdocs
tools/     # Contains scripts that aid the usage of servus
tests/     # Contains code/scripts that will aid in testing servus functionality
```

_This layout was adapted from [kolla-ansible](https://github.com/openstack/kolla-ansible)_


