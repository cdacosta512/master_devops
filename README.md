# master_devops
This is a repo for building my CICD pipeline. All notes and docs that have been supportive in creating and automating this application pipline will be in this repo. 

A weekly review will be done on this repo so I can make sure its clean and presentable when the time comes. 

Below are my personal notes on what I want to do but many things may change over time. 

------------------------------------------------------------------------------------------------------------------------------------------------

# Master DevOps Project Notes

This will outline my master devops project that will soon be use to interview and show companies that I have skills and knowledge to perform in a devops role.

This document should include:

- Project Ideas
- Outlines
- Technical documentation
- Technical explanation of concepts
- Diagrams
- GitHub Repos of referenced code used
- Potential interview questions
- Running checklist that will cross off various tools that have been learned for resume tracking

---

The plan:

- Use the flask web app counter that we already have locally
- Dissect what it’s doing and what you need to run it in in docker and terraform.
- How can we loop in Ansible
- Can we scale it up? Automatically?
- Can we push it to the cloud? Automatically
- How can we loop in K8
- Can this be done from a single file?
- How can we use Jenkins to test it?
- Create a master repo for this and the only thing that goes here is project material.
- Can we update the web app with additional features?
- How can we build our Jenkins Server with Terraform? Same with Ansible.

---

**Action Items:**

- The application that will be used to run through pipeline:

[https://github.com/alanbchristie/PySimple](https://github.com/alanbchristie/PySimple)

- This is being run with docker / docker compose
- main directory: `/Users/cdacosta/Code/master_devops/PySimple`
    - Commands used to run the app: `docker compose up —build`
