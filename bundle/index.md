---
abstract: This directory contains the playbook to bundle and copy signing certs.
authors: Xander Harris
date: 2024-03-08
title: Cert bundle
---

## Bundle CA Usage

```{code-block} shell
:caption: Bundle the CA certs and copy them to targets

ansible-playbook bundle/site.yml
```

```{index} ca; playbook
```
<!--
### Root CA Playbook

```{literalinclude} site.yml
:language: yaml
:caption: root ca
```

There should be proper comments below this line.
<!--
```{ansible-task}
- include_tasks: ca/site.yml
```
--> -->
