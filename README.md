---

# ansible-linux-redis

<img src="https://www.ansible.com/hubfs/2016_Images/Assets/Ansible-Mark-Large-RGB-Pool.png?hsLang=en-us" width="10%" height="10%" alt="Ansible logo" align="right"/>
<img src="https://avatars1.githubusercontent.com/u/1529926?s=400&v=4" width="11%" height="11%" alt="Redis logo" align="right"/>

[![Build Status](https://travis-ci.org/autobuilder/ansible-linux-redis.svg?branch=master)](https://github.com/autobuilder/ansible-linux-redis)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg?style=flat)](https://opensource.org/licenses/Apache-2.0)
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/autobuilder/ansible-linux-redis/issues)

![Platform](https://img.shields.io/badge/platform-ubuntu-dd4814.svg?style=flat) 
![Platform](https://img.shields.io/badge/platform-centos-932279.svg?style=flat)

Ansible role for install [Redis][redisio]

---

### Requirements:

* None

### Dependencies:

* None

---

### Variables:

| Variable Name        | Default Vaule                      | Description                 |
|:---------------------|:-----------------------------------|:----------------------------|
|redis_port            | ```6379```                         | Redis port to use           |
|redis_bind_interface  | ```127.0.0.1```                    | Redis IP address to bind to |

---

### Example Playbook:

```yaml
- hosts: servers
  roles:
    - ansible-linux-redis
```

---

### Test Automation:

Automated tests run with [Kitchen-CI][kitchenci] and [Ansible Lint][ansiblelint].
Tested platforms are the below linux-based distros:

* Ubuntu 16.04
* Ubuntu 18.04
* Centos 7

---

#### License:

This project is made available under the terms of the [Apache-2.0][apache2].

See the [LICENSE][license] file that accompanies this distribution for the full text of the license.

---

#### Author Information:

[AutoBuilder][autobuilder]

[redisio]: https://redis.io
[kitchenci]: https://kitchen.ci
[apache2]: https://www.apache.org/licenses/LICENSE-2.0.html
[license]: https://github.com/autobuilder/ansible-linux-redis/blob/master/LICENSE
[autobuilder]: https://github.com/autobuilder
[ansiblelint]: https://docs.ansible.com/ansible-lint/