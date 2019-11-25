---
title: "Versioning"
teaching: 0
exercises: 0
questions:
- "What is a version control system?"
- "Are you keeping track and logs of your analysis?"
objectives:
- "First learning objective. (FIXME)"
keypoints:
- "A version control system allows users to keep track of changes in your Data or Process"
---

{% include links.md %}

> ## Version control system
> A version control system allows users to keep track of changes in your Data or Process
{: .callout}

Are you keeping track of any versions or logs made by the software in use?

Make sure you have a copy of every step you have completed and if possible, version numbers for the program you are using and any libraries. Programs change over time and this can alter your results if someone asks to replicate your work post publication.

## Never make alterations to your raw data files

Instead, make a copy of the raw data files and keep them somewhere safe (like [Research Vault](https://research-storage.griffith.edu.au/){:target="_blank"}). That way, if you need to redo your work or you find an error earlier in your workflow, you have an original baseline to start from.

## Write down versions of analysis software

Write down the versions of analysis software (like SPSS or NVIVO etc) AND hardware (MRI machines etc). Your documentation is a great place for this, but even just in your lab notebook will work.

### Random Number Generator

If you are using random numbers in your research, save your random seed generator number as part of your working data. This way, you can later reproduce your results.

> ## Beginner
> Copy your raw data to a cloud storage solution such as Research Vault for safe keeping. 
{: .challenge}

> ## Intermediate
> If you are using a workflow program (Galaxy, KNIME, a virtual lab like [EcoCloud](https://ecocloud.org.au/){:target="_blank"} or 
> [TINKER Humanities,Arts and Social Science Virtual Lab](https://tinker.edu.au/){:target="_blank"}, you can copy your workflow and save 
> it as part of your documentation. Write the date that you ran the workflow if versions of the software are not available. 
{: .challenge}

> ## Advanced 1
> If you are writing scripts (R/Python/Matlab etc), use Git.
>
Note:
Griffith has a gitlab version you can use for private repositories. Also record the version of R/Python/Matlab, the operating system you are using and the version numbers of any library you are using.<br/>If you are using the HPC, also record the version of any modules you used there. 
{: .challenge}

> ## Advanced 2
> If you’ve heard of Docker or Singularity and you are interested, come talk to hacky hour/eResearch Services
{: .challenge}

## External Resources
* [Reproducible research in Git ](https://nbis-reproducible-research.readthedocs.io/en/latest/git/){:target="_blank"}
* [What is git](https://opensource.com/resources/what-is-git){:target="_blank"}
* [Reproducibility in SPSS](https://andrewpwheeler.wordpress.com/2012/03/20/making-a-reproducible-example-in-spss/){:target="_blank"}
* [Learn Software Carpentry in Git](http://swcarpentry.github.io/git-novice){:target="_blank"}
* [Git for Scientists](https://milesmcbain.github.io/git_4_sci/){:target="_blank"}
* [The Turing Way Version Control](https://the-turing-way.netlify.com/version_control/version_control.html){:target="_blank"}

