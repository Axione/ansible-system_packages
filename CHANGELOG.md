# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/)
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [3.2.0](https://github.com/lotusnoir/ansible-system_packages/compare/3.1.0...3.2.0) - 2025-11-26

### Commits

- update main to include success flag at the end to be able to monitor last playbook run [`14a7618`](https://github.com/lotusnoir/ansible-system_packages/commit/14a76186c169536118bac49dfe4f2cda8b300451)

## [3.1.0](https://github.com/lotusnoir/ansible-system_packages/compare/3.0.0...3.1.0) - 2025-11-18

### Commits

- fix molecule test image for rhel8 [`f4a6032`](https://github.com/lotusnoir/ansible-system_packages/commit/f4a60326d965641d9939adeac00515eafc35034b)
- add oraclelinux10 support + lint and core fixes [`63b1b54`](https://github.com/lotusnoir/ansible-system_packages/commit/63b1b546d2a31342cff17077edf388c60b65417b)

## [3.0.0](https://github.com/lotusnoir/ansible-system_packages/compare/2.0.0...3.0.0) - 2025-10-29

### Commits

- fix new package name for debian13 [`0882a85`](https://github.com/lotusnoir/ansible-system_packages/commit/0882a85396561212c79db5c848655bb48a98782b)
- update core, molecule + gitlab-ci [`e0b7a03`](https://github.com/lotusnoir/ansible-system_packages/commit/e0b7a0315d2f251cc47ba299f44ecc20261ccae5)
- fix lint [`002e8af`](https://github.com/lotusnoir/ansible-system_packages/commit/002e8afa3a417b52c4f055a861f06ad2783c6159)
- fix molecule paralelism and little updates [`956d8a0`](https://github.com/lotusnoir/ansible-system_packages/commit/956d8a0b8426cc973405e60d0849fdff01093834)
- add support for ubuntu24 [`eb60013`](https://github.com/lotusnoir/ansible-system_packages/commit/eb600137fdafd6442cb8a88de3968ca4f2fc2001)
- add version on molecule play image to maintain support on old release [`d5b4ed2`](https://github.com/lotusnoir/ansible-system_packages/commit/d5b4ed230d1df10ade91a65e513ca34df6ef55a0)
- update molecule [`6dc22ef`](https://github.com/lotusnoir/ansible-system_packages/commit/6dc22ef4d117f97d39ae97541619b6941651a1c0)
- add redhat 9 to default supported distrib [`11fc8d4`](https://github.com/lotusnoir/ansible-system_packages/commit/11fc8d4349e6e6a43d1ebfa16d8bce267f84be4f)
- add redhat 8 to default supported distrib [`2692ec9`](https://github.com/lotusnoir/ansible-system_packages/commit/2692ec9a70f32a886bbef6734b5af61987ec9996)
- sort testing distrib to avoid random changes [`483cc28`](https://github.com/lotusnoir/ansible-system_packages/commit/483cc288fd74cb8a06a4e96b993086df42d832ba)

## [2.0.0](https://github.com/lotusnoir/ansible-system_packages/compare/1.1.0...2.0.0) - 2023-09-25

### Commits

- update vars [`9075d7d`](https://github.com/lotusnoir/ansible-system_packages/commit/9075d7de3e3b36ab616b565246425eecf233d690)
- update readme + precommit + include vars [`2436d80`](https://github.com/lotusnoir/ansible-system_packages/commit/2436d80d019dbe09249efed5199a1b6848274ea5)
- change import tasks to include in order to support facts on name [`8c98d98`](https://github.com/lotusnoir/ansible-system_packages/commit/8c98d9877610308e553494172b1b7b0c40afec7d)

## [1.1.0](https://github.com/lotusnoir/ansible-system_packages/compare/1.0.0...1.1.0) - 2023-06-14

### Commits

- add debian12 support [`8f56429`](https://github.com/lotusnoir/ansible-system_packages/commit/8f56429236068da6dd7a7394754ee602af8a0394)

## [1.0.0](https://github.com/lotusnoir/ansible-system_packages/compare/0.3.0...1.0.0) - 2023-03-23

### Commits

- add code of conduc and small changes [`8e46d2f`](https://github.com/lotusnoir/ansible-system_packages/commit/8e46d2fad72ddab7e6f20509d478eb567c135bb7)
- add precommit for lint [`5932b14`](https://github.com/lotusnoir/ansible-system_packages/commit/5932b14d618f826ace49ef1799df81d0d56fdd4b)
- fix checks [`b5a150e`](https://github.com/lotusnoir/ansible-system_packages/commit/b5a150e70ea25b70ba06f4a4f40af707dc73dc29)
- add new molecule all scenario [`cababcd`](https://github.com/lotusnoir/ansible-system_packages/commit/cababcd19daa81d77d1d6ec2a876afe4ede3e1f2)
- fix molecule idempotence [`f373f9e`](https://github.com/lotusnoir/ansible-system_packages/commit/f373f9e442fba1e716838d9d606ade7be01769cf)
- split distro for molecule tests on ci [`acf9639`](https://github.com/lotusnoir/ansible-system_packages/commit/acf963952ff95dd44ba87451543361313a3a3323)
- update checks and Readme [`1ec2224`](https://github.com/lotusnoir/ansible-system_packages/commit/1ec2224d6fb09c966c0597dd3e302e4afea2b7f4)
- no packages by default [`dfd45fb`](https://github.com/lotusnoir/ansible-system_packages/commit/dfd45fb452c2fe02da7f18bfdb3d8a7279157d58)
- remove verify [`031a498`](https://github.com/lotusnoir/ansible-system_packages/commit/031a498f3b297e352f2ec4b1498da88c1d4f3675)
- add package cracklib-runtime on debian [`25f4846`](https://github.com/lotusnoir/ansible-system_packages/commit/25f484692267a255d175e2ca6e1067d68652d555)

## [0.3.0](https://github.com/lotusnoir/ansible-system_packages/compare/0.2.0...0.3.0) - 2022-07-01

### Commits

- minor: add oracleLinux7 support [`136a4dd`](https://github.com/lotusnoir/ansible-system_packages/commit/136a4dd7c040775910adb18a43b02bb52046434a)
- minor: add oracleLinux support + little fixes [`8a9123e`](https://github.com/lotusnoir/ansible-system_packages/commit/8a9123e447ddf86e92c1ad264a12592a709377d0)

## [0.2.0](https://github.com/lotusnoir/ansible-system_packages/compare/0.1.1...0.2.0) - 2022-06-02

### Commits

- minor: add ubuntu 22 molecule test + fix lint [`2157c07`](https://github.com/lotusnoir/ansible-system_packages/commit/2157c072e4789045d9fd907cbdae232e5017437d)
- fix: remove unsupported centos8 + minor fixes [`456e6e8`](https://github.com/lotusnoir/ansible-system_packages/commit/456e6e885c625f86f042adb48f4db6bf6f0e22fa)
- fix: fix function warning + add centos/rhel base repo [`69ba6c9`](https://github.com/lotusnoir/ansible-system_packages/commit/69ba6c948f125a77eb87cdd467d5fbd223f4d5d7)

## [0.1.1](https://github.com/lotusnoir/ansible-system_packages/compare/0.1.0...0.1.1) - 2021-11-18

### Commits

- fix: Changes on README + molecule container names [`5d5966b`](https://github.com/lotusnoir/ansible-system_packages/commit/5d5966b08181410dfa0bcbb9112cee598fd5caa5)

## 0.1.0 - 2021-11-16

### Commits

- fix: add role name on molecule container names to avoid concurrent conflict on runners [`c278b34`](https://github.com/lotusnoir/ansible-system_packages/commit/c278b342016c46c4a2435de8b8d40c792cc5bc93)
- fix vars [`5415f9a`](https://github.com/lotusnoir/ansible-system_packages/commit/5415f9a9ac41b749a12890d0cb91bb61301a9716)
