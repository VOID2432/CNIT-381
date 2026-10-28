# CNIT-381
Weekly labs for CNIT 381

## Week 1
Created the repository , configured Git, cloned it locally, and made my first commit.

## Week 2
Practiced team Git collaboration with a partner: feature branches, pull
requests, code review, and resolving a merge conflict on a shared network
inventory site.

## Week 3
Containerized a duplicate-IP checker with Docker and published the image to Docker Hub.

## Week 4
Built a network config pipeline: an intent file plus a generator, containerized,
with CI/CD that regenerates and validates the configs on every change.

## Week 5
Called the GitHub REST API from Python to read my repo and create an issue.

## Week 6
**What I built:** A Python checker for our IP address plan, packaged in
Docker, run by GitHub Actions on every push, that opens a GitHub issue
through the API when the plan has errors.
**Repo:** https://github.com/VOID2432/ip-plan-check

## Week 8: OSPF by Hand, Then Automated
What I did: configured OSPF manually, ran a provided playbook that automated it,
and wrote my own playbook to back up the configs. What I learned: I learned how to create Ansible playbooks and add commands to them to automate network configuration.

## Week 9: Build a Network and Automate It End to End 
What I built: a CML topology (2 routers, a switch, and an Ubuntu control node), bootstrapped the devices by hand, then used Ansible to configure loopbacks, EIGRP, a login banner, and to back up all devices. What I learned: How to write playbooks to configure multiple network devices.
