---
title: Basics
weight: 10
menu:
  notes:
    name: Basics
    identifier: notes-saltstack-basics
    parent: notes-saltstack
    weight: 10
---

<!-- Salt Keys -->
{{< note title="Salt Keys">}}
Check status of SSH keys

```
salt-key -L
```

Accept key
```
salt-key -a <name>
```

Accept all keys
```
salt-key -A
```
{{< /note >}}

<!-- Salt Paths -->
{{< note title="Salt Paths">}}
`/etc/` `/opt/` `/srv/var/salt/`
{{< /note >}}
