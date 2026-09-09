*This project has been created as part of the 42 curriculum by \<lming-ha>*

---

# NetPractice

## Table of Contents

- [Description](#description)
- [Instructions](#instructions)
  - [Executing/Running The Training Interface](#executingrunning-the-training-interface)
  - [Exporting Configurations](#exporting-configurations)
  - [Submission Requirements](#submission-requirements)
- [Resources](#resources)
  - [Concepts](#concepts)
  - [AI Usage](#ai-usage)
- [Submission Details](#submission-details)

<br>

---

# Description

> NetPractice is a hands-on networking project from **[42 School](https://www.42network.org)** designed to introduce essential computer networking fundamentals.

This general practical exercise features **10 progressive levels** that teach through interactive problem-solving to  master:


- [TCP/IP addressing](#tcpip-addressing)
- [subnet masks](#subnet-masks)
- [default gateways](#default-gateways)
- [routing](#routing)
- [OSI layers](#osi-layers)

by troubleshooting and configuring non-functioning network diagrams in a browser-based training that provides practical experience in network administration, which helps in real-world system administration and networking challenges.
> Examples include learning how to configure IP addresses, connect devices through a router, and understand the role of a gateway within a network.

<br>

---

# Instructions

> Due to technical design and security constraints on various web browsers, it is required to use a local web server to deliver NetPractice’s web pages.

> **If you cloned this repo** and don't mind practicing on a **possible deprecated version**, the extracted files (`version 1.9`) should be in the `net_practice.1.9/net_practice` folder and so you can skip the following steps.

1. Download the **latest** `net_practice.{version-number}.tgz` file in the [42 project page](https://projects.intra.42.fr/projects/netpractice) ***if you are an active 42 cadet***.
   > If you're not an active 42 cadet, there is a `net_practice.1.9.tgz` at the root of this repository. Although it may be deprecated as it is in version 1.9.
2. Extract the files into the repository root. This should create a `net_practice.{version-number}/net_practice`.

## Executing/Running The Training Interface

1. In the **folder with the extracted files**, run the `run.sh` file.

   ***Assuming** you extracted the files at the **repository root** without assigning it a name:*

   ```bash
   cd net_practice.1.9/net_practice
   ./run.sh
   ```

2. This shell script will launch a web server and open your preferred web browser to the dedicated page.

   *The terminal you launched the `./run.sh` command in should have **something like** this initial output (the port may be different from the given example):*

   ```bash
   Netpractice server is starting. Open your web browser with URL: http://localhost:49152
   Type Ctrl-C to shutdown the server.
   Serving HTTP on 0.0.0.0 port 49152 (http://0.0.0.0:49152/) ...
   ```

   > **If the `run.sh` script does not function properly**, you can access the project manually: first run `python3 -m http.server 49242` *(you may change the port number)* which **only outputs the last line of the previous terminal snippet**

3. This interface **should** automatically open in that web browser:

   ![NetPractice Homepage](assets/NetPractice-homepage.png)

   **If the page did not open automatically**, try opening the page **manually** through the provided URL by either:
   > navigating to the URL with **(ctrl + click) when hovering** on top of the URL in the terminal output

   **OR** *(**Especially** if you ran it manually with the python command)***:**
   > In your web browser navigate to the URL **with the chosen port number** like: [`http://localhost:49242`](http://localhost:49242).

## Exporting Configurations

At the **top of your window** in the exercises, you will see a button named **[Get my config]**:

![Get My Config](assets/GetMyConfigHover.png)

Click on it to download your configuration whenever you need to.

## Submission Requirements

> Refer to the header **[Submission Details](#submission-details)**.

> Before moving to the next level, don’t forget to export your configuration using the **[Get my config]** button so you can add it to the repository.

After exporting the configuration file:

1. Place the exported file at the **repository root**.
2. Ensure the file is included in the repository before submission.

<br>

---

# Resources

| Resource                                                                                                                              |                                                                    Credit                                                                     | Purpose                                       |
| ------------------------------------------------------------------------------------------------------------------------------------- | :-------------------------------------------------------------------------------------------------------------------------------------------: | --------------------------------------------- |
| [Subject PDF](en.subject.pdf)                                                                                                         |               [![42 School](https://img.shields.io/badge/42_School-000000?logo=42&logoColor=white)](https://www.42network.org)                | Project requirements and objectives           |
| [Free CCNA v1.1 200-301 \| Complete Course](https://youtube.com/playlist?list=PLxbwE86jKRgMpuZuLBivzlM8s2Dk5lXBQ&si=aLRmLDhJQE63_6Ah) | [![Jeremy's IT Lab](https://img.shields.io/badge/Jeremy's_IT_Lab-FF0000?logo=youtube&logoColor=white)](https://www.youtube.com/@JeremysITLab) | Primary reference for the networking topics   |
| [Writing on GitHub](https://docs.github.com/en/get-started/writing-on-github)                                                         |           [![GitHub Docs](https://img.shields.io/badge/GitHub_Docs-181717?logo=github&logoColor=white)](https://docs.github.com/en)           | Markdown formatting guide for the `README.md` |

---

## AI Usage

AI was used as a **supplementary learning** and **clarification tool** during this project.

I used AI to:

- ✅ Ask questions about concepts encountered in the provided resources *(requesting the exact section/line/timestamp for verification)*
- ✅ Clarify concepts that were difficult to understand.
- ✅ Explore hypothetical situations that were not covered in the provided resources.
- ✅ Perform a first layer of double-checking and verification of my work.
- ❌ Generate or solve the project's exercises.
- ❌ Write the content of the `README.md`.

All NetPractice exercises and the `README.md` were completed and configured **manually** by me.

---

## Concepts

<br>

---

# Submission Details

As stated from the [![Static Badge](https://img.shields.io/badge/Subject_PDF-Readme_Requirements-white)](en.subject.pdf):
> 10 exported configuration files (one per level) must be placed at the repository root
