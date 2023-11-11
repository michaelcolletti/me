## Creating Infrastructure Worlds with Terraform

_I don't know exactly how I heard of Terraform for the first time, but I can say without a doubt the first time I saw it, it was mind-blowing. I was working in infrastructure, but not th current kind. This was the enterprisey, vended, legacy stacks and enviroments that are ardous, filled with tech debt and in being so an opportunity ground for consulting. Watching from afar in the 2000s-10s It would take months and years to do dc consolidation. Within code I could declaratively build my worlds, just me and create any infrastructure easily just from a text file. Holy S*&t!_

## Temporal Challange of Ephemeral State: Change and Discovery

The coolest part of IaC is that when used adaptively around existing legacy infrastructure, the imperative mode of execution dies hard; the very hard edges around changing how infrastructure state is understood, nevermind managed. Do I change ouur collective config and push out the changes or do I ssh to the box and fix immediately. There's a temporal challange: how does one understand the migration estate, real-time, in totality at a fairly high  degree of granularity while not having speed or performance degraded by operational challanges of maintaining the means of achieving this. 


## Time State and Consistancy 
I've adopted Terraform as a mode of creation to solve problems around the domain because it is so fast and adaptable AND can be threaded in existing infrastructures with substantial value gains. 


## The Junction of Other HashiCorp Stack Products

- Packer as a build tool can establish sanity in th build cycle, making 'build sheets' a thing that has been vastly improved. This is all viable and acheivable and making the configuarion management more easily managed with version control is a great first step. 
- Consul can deliver an understanding and provide a way to achieve cloud-like ambitions whilst still bound in DC legacy infra. 

## Journey Towards Certification

- Being in love with Terraform I created a site for others to get resources, enjoy and derive benefit from. 
- Visit: [https://michaelcolletti.github.io/terraform-certification](https://michaelcolletti.github.io/terraform-certification)

