---
title: "CV"
date: 2024-06-04
draft: false
summary: "All my work experience in one nifty place"
tags: ["cv"]
type: "cv"
---

{{<button href="">}}
Download PDF Version
{{</button>}}  
#

## Who am I?
blah blah about me blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah blah


### Experience
{{< timeline >}}

{{<timelineItem icon="behaviour_interactive_logo" header="Behaviour Interactive" badge="Game Development" subheader="SEPTEMBER 2022 - NOW">}}
    <div>
    <h4>Tools Programmer</h4>
        <ul>
            <li>Contributed to the test automation framework for detecting and fixing gameplay and system issues.</li>
            <li>Implemented support for gameplay automated tests running on PS5 & XSX</li>
            <li>Led the efforts to rewrite the submission tools for game developers to include proper pre-submission validation and a simpler deployment workflow.</li>
            <li>Independently developed an Unreal Engine C++ cheat management tool to aid Dead by Daylight developers and QA in executing dev commands on separate platforms such as the Switch, reducing QA time</li>
        </ul>
    </div>
{{<list limit=3 title=" " where="Description" value="Behaviour">}}
{{</timelineItem>}}

{{<timelineItem icon="unity-game-engine-icon" header="Unity" badge="Engine Development" subheader="Software Developer">}}
    <div>
    <h2>DECEMBER 2020 - JANUARY 2022</h2>
        <ul>
            <li>Refactored the Unity Licensing Server allowing for differing and more extensible license types for enterprise users, such as 1-30 day offline-capable floating licenses.</li>
            <li>Implemented c++ native credential manager access for the Unity Package Manager to enable connecting through a proxy on a closed network.</li>
        </ul>
    </div>
    {{<list limit=3 title=" " where="Description" value="Unity">}}
{{</timelineItem>}}

{{<timelineItem icon="code" header="Scalepad" badge="SAAS" subheader="Software Developer">}}
    <div>
    <h2>APRIL 2019 - DECEMBER 2020</h2>
        <ul>
            <li>Led initiative to design workstation management tool to swap development team from Windows to Linux, enabling > 30-minute workstation setup time.</li>
            <li>Refactored monolithic library into 20 single-responsibility modules for microservices</li>
            <li>Redesigned CI/CD pipelines with Buildkite and Ansible, reducing pipeline time from 30-50 min to 5-10 min</li>
            <li>Infrastructure as code for the deployment of the backend networking architecture using Terraform/Terragrunt and Kubernetes.</li>
        </ul>
    </div>
{{</timelineItem>}}

{{</timeline>}}
  
### Personal projects
Game projects that I've worked on over the years in my spare time. 
{{<list limit=5 title=" " where="Type" value="personal">}}

### Libraries and Tools
Whenever I work on a new project, I try to minimize the amount of code I have to rewrite. 
Over the years, I've built a few libraries that I now reuse whenever I work on a new project! 
{{<list limit=5 title=" " where="Type" value="library">}}