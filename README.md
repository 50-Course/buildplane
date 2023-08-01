# buildplane
One-stop open-source cloud deployment tool

# User story

_What are some tools (open source or PaaS like Vercel) for a zero-config or interactive wizard method of deploying/Dockerizing almost any web app full-stack repository? At a minimum, run dev tasks in yarn/npm/etc since those are standardized.
 It should also be feasible to automatically detect not all but many common full-stack deployment configuration tasks.
For example detect that the app server is expecting a MongoDB and spin one up using defaults or by scanning code/readme. Of course it won't succeed in every case, but 80% is good enough.
The goal is to pick any recently-updated web app repository on Git Hub and get it fully up and running in minutes, ready to hack on._

# What is build BuildPlane?

I once worked on a little deployment script for generic pipelines. The goal of `build-plane` is to create an easy on-cloud deployment tool for popular, taking off about 35% of solo developers, teams, and business ops pain of a rigorous deployment process.


# Roadmap

- [ ] Support deployment to popular platforms; Vercel, Heroku, DigitalOcean, Render, Azure, and Amazon Web Services
- [ ] Utilize intelli-sense to scan repositories for special configurations files and automatically determine build type
- [ ] Support GitHub and GitLab platforms

This is not an exhaustive roadmap - and very much an envisioned roadmap, call it version `1.0` 
