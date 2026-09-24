<div align="center">

# 7sh1d0w7x

### Linux Systems · Cybersecurity · Tooling · AI

**I build open-source tools that tell you what is actually wrong.**

Freelance software & systems developer · Timișoara, Romania

[![GitHub](https://img.shields.io/badge/GitHub-zShaD0w7x-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/zShaD0w7x)
[![flagship](https://img.shields.io/badge/flagship-linux--doctor-3fb950?style=flat-square&logo=linux&logoColor=white)](https://github.com/zShaD0w7x/linux-doctor)
[![last commit](https://img.shields.io/github/last-commit/zShaD0w7x/linux-doctor?style=flat-square&label=last%20commit&labelColor=0d1117&color=2f81f7)](https://github.com/zShaD0w7x/linux-doctor)

</div>

---

## SYSTEM PROFILE

```text
$ whoami
7sh1d0w7x

$ cat /etc/profile.d/role
freelance software & systems developer

USER      7sh1d0w7x
LOCATION  Timișoara, Romania
ROLE      Freelance software & systems developer
FOCUS     Linux · systems · cybersecurity · developer tooling · automation
STATUS    Building linux-doctor — open-source system diagnostics
```

---

## ABOUT

I'm a freelance software & systems developer from **Timișoara, Romania**. Most of my work happens close to the system: Linux internals, diagnostics, automation, and the tooling that makes a machine explainable.

I'm drawn to problems where the visible behaviour hides the cause — a service that *"sometimes"* fails, a machine that's *"slow"*, a package that breaks on exactly one distribution. Patching the symptom is the easy part. The interesting work is building the instrument that shows what is actually happening, in a way a human can read.

That preference shapes how I build: inspect before changing, keep the core read-only where possible, and treat output as a product — not a debug dump.

---

## ENGINEERING PHILOSOPHY

| Principle | In practice |
| --- | --- |
| **Evidence first** | Measure before assuming. Report what the system actually says, not what it should have said. |
| **Read-only by default** | Diagnostics should not silently modify the machine they inspect. |
| **Test what you ship** | If it matters, automate the verification. Reliability is a build step, not an intention. |
| **Explain, don't obscure** | Clear output beats clever implementation — the result should be understandable without reading the source. |
| **One engine, many interfaces** | Keep the core reusable and the front-ends thin: CLI, Web and Desktop are views, not rewrites. |

---

## CURRENTLY BUILDING

### 🩺 linux-doctor

> **What is actually wrong with this machine?**

A read-only Linux diagnostic toolkit. It inspects a running system, scores its health, and reports what changed since the last run — from a single diagnostic engine exposed through three interfaces.

| | |
| --- | --- |
| **Diagnostics** | 49+ checks |
| **Health score** | 0–100 |
| **Change detection** | Run-over-run diff |
| **Findings** | Actionable fixes |
| **Tests** | 600+ automated |
| **Interfaces** | CLI · Web · Desktop |
| **Packaging** | npm · AUR · OBS · deb · rpm · AppImage |
| **Design** | Read-only by default |
| **License** | GPL-3.0 |

One diagnostic engine, multiple interfaces — built to be understood, not just executed.

**[→ Explore linux-doctor](https://github.com/zShaD0w7x/linux-doctor)**

---

## TECH STACK

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white) ![Rust](https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white) ![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black) ![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![Lua](https://img.shields.io/badge/Lua-2C2D72?style=flat-square&logo=lua&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logoColor=white)

**Systems**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Fedora](https://img.shields.io/badge/Fedora-51A2DA?style=flat-square&logo=fedora&logoColor=white) ![CLI tooling](https://img.shields.io/badge/CLI_tooling-30363D?style=flat-square&logoColor=white) ![packaging](https://img.shields.io/badge/packaging-30363D?style=flat-square&logoColor=white)

**Web**

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Node.js](https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white) ![APIs](https://img.shields.io/badge/APIs-30363D?style=flat-square&logoColor=white)

**Tooling & Infrastructure**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) ![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white) ![CI/CD](https://img.shields.io/badge/CI%2FCD-30363D?style=flat-square&logoColor=white)

**Security**

![Linux security](https://img.shields.io/badge/Linux_security-30363D?style=flat-square&logoColor=white) ![system analysis](https://img.shields.io/badge/system_analysis-30363D?style=flat-square&logoColor=white) ![automation](https://img.shields.io/badge/automation-30363D?style=flat-square&logoColor=white)

---

## SELECTED WORK

| Project | Purpose | Status |
| --- | --- | --- |
| 🩺 **[linux-doctor](https://github.com/zShaD0w7x/linux-doctor)** | Linux diagnostics & system health | Active — flagship |
| 🔐 **Security tooling** | Experiments around system security | In progress |
| ⚙️ **Developer tooling** | Automation, utilities & workflows | In progress |

More projects are gradually moving from experiments → usable software.

---

## EXPLORING

- 🐧 Linux system internals
- 🔐 Cybersecurity & defensive tooling
- ⚙️ Automation and developer tooling
- 🤖 AI-assisted development
- 📦 Cross-distribution packaging
- 🧪 Software testing & reliability

---

## ACTIVITY

[![followers](https://img.shields.io/github/followers/zShaD0w7x?style=flat-square&label=followers&labelColor=0d1117&color=2f81f7)](https://github.com/zShaD0w7x?tab=followers)
[![repositories](https://img.shields.io/badge/repositories-browse-3fb950?style=flat-square&logo=github&logoColor=white)](https://github.com/zShaD0w7x?tab=repositories)

Most of it lands in **[linux-doctor](https://github.com/zShaD0w7x/linux-doctor)**.

---

## CONTACT

| | |
| --- | --- |
| **GitHub** | [@zShaD0w7x](https://github.com/zShaD0w7x) |
| **Location** | Timișoara, Romania |

Open to open-source collaborations, Linux tooling, automation and security work.

---

```text
$ whoami
7sh1d0w7x

$ cat /etc/motto
understand the system
then build the tool
```

<sub>Built with curiosity, Linux and an unreasonable amount of terminal tabs.</sub>
