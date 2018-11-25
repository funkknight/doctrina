# doctrina

## Background
I have found that Classroom instruction and Video/Text training materials don't work for me.  I had one professor tell me, long ago, that I am someone that works from the "inside out". Meaning that I have to process information to get it, vs an "outside in" person who could just take information at face value and move on.

Heh, I guess you can say I trust nothing and no one.

In an effort to learn various cloud technologies on a deeper level I am going to create a software project that will force me to learn multiple cloud technologies.  The end result will likely not be a useful product. 

## The Project

Doctrina, latin for learning, is the name of the overall project.  The product will be called (/scampers away...) illudo-cv (Mock CV).

illudo-cv will be a resume management site. It's based off of an idea and research I did many, many moons ago when I was fed up with job sites such as Monster and Careerbuilder.  The market has definately changed since then, but it's enough of an idea to get me where I want to go with my cloud education.

## illudo-cv

Advanced resume creation and management.  Currently Resumes are treated like freeform documents.  Each iteration, say for different job postings, is a totally different document.  But why?  With all the standards available today, with the advent of AI, etc why are we still treating resumes in such an unstructred way? 

### Features
- Resumes are stored in a structred format.
- Stylesheets can be applied to produce various resume layouts
- Hiring staff can apply their own styling to normalize their searches
- Bullet points on resumes can be linked to the job description (also structred) to help Hiring staff process applicants faster, and help Job seekers to stand out.
- Advanved search capabilities due to nomalized data.


### System design/components

This highlevel design may not make sense.  That's fine.  It's just for me to learn.

- 12 factor app
- Cloud agnostic
    + AWS
    + Azure
- Scale across clouds
- Network Presentation layer
- Segment shared services. Have add-on services (VPCs) that can route in
- Metrics
- Logging
- Chatbots
- RDBMS for everything except some randome reason to have a nosql database
- Tools
    + Terraform
    + Packer?
    + Ansible







