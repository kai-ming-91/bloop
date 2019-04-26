---
id: version-1.2.0-overview
title: Overview
sidebar_label: Overview
original_id: overview
---

IDEs can use bloop to compile, test and run Scala code fast via the [Build Server Protocol
(BSP)](https://github.com/scalacenter/bsp). The protocol allows clients to establish a long-lived
build session to, for example, receive accurate compilation diagnostics in text editors and IDEs.

There are two main IDE integrations:

1. [IntelliJ](ides/intellij.md), the most popular Scala and Java IDE.
2. [Metals](ides/metals.md), a work-in-progress Scala language server that
   supports text editors such as Visual Studio Code, `vim`, Sublime Text and Atom.

These IDE integrations support the following BSP actions:

|                  | Build import | Compile |     Test      |      Run      |
|------------------|--------------|---------|---------------|---------------|
| **IntelliJ BSP** | ✅            | ✅       | ❌ use the CLI | ❌ use the CLI |
| **Metals**       | ✅            | ✅       | ❌ use the CLI | ❌ use the CLI |

