---
author-meta:
- Taylor Reiter
- C. Titus Brown
- N. Tessa Pierce
bibliography:
- content/manual-references.json
date-meta: '2020-05-24'
header-includes: '<!--

  Manubot generated metadata rendered from header-includes-template.html.

  Suggest improvements at https://github.com/manubot/manubot/blob/master/manubot/process/header-includes-template.html

  -->

  <meta name="dc.format" content="text/html" />

  <meta name="dc.title" content="Streamlining data-intensive biology with workflow systems" />

  <meta name="citation_title" content="Streamlining data-intensive biology with workflow systems" />

  <meta property="og:title" content="Streamlining data-intensive biology with workflow systems" />

  <meta property="twitter:title" content="Streamlining data-intensive biology with workflow systems" />

  <meta name="dc.date" content="2020-05-24" />

  <meta name="citation_publication_date" content="2020-05-24" />

  <meta name="dc.language" content="en-US" />

  <meta name="citation_language" content="en-US" />

  <meta name="dc.relation.ispartof" content="Manubot" />

  <meta name="dc.publisher" content="Manubot" />

  <meta name="citation_journal_title" content="Manubot" />

  <meta name="citation_technical_report_institution" content="Manubot" />

  <meta name="citation_author" content="Taylor Reiter" />

  <meta name="citation_author_institution" content="Department of Population Health and Reproduction, University of California, Davis" />

  <meta name="citation_author_orcid" content="0000-0002-7388-421X" />

  <meta name="twitter:creator" content="@ReiterTaylor" />

  <meta name="citation_author" content="C. Titus Brown" />

  <meta name="citation_author_institution" content="Department of Population Health and Reproduction, University of California, Davis" />

  <meta name="citation_author_orcid" content="0000-0001-6001-2677" />

  <meta name="twitter:creator" content="@ctitusbrown" />

  <meta name="citation_author" content="N. Tessa Pierce" />

  <meta name="citation_author_institution" content="Department of Population Health and Reproduction, University of California, Davis" />

  <meta name="citation_author_orcid" content="0000-0002-2942-5331" />

  <meta name="twitter:creator" content="@saltyscientist" />

  <link rel="canonical" href="https://bluegenes.github.io/2020-gep/" />

  <meta property="og:url" content="https://bluegenes.github.io/2020-gep/" />

  <meta property="twitter:url" content="https://bluegenes.github.io/2020-gep/" />

  <meta name="citation_fulltext_html_url" content="https://bluegenes.github.io/2020-gep/" />

  <meta name="citation_pdf_url" content="https://bluegenes.github.io/2020-gep/manuscript.pdf" />

  <link rel="alternate" type="application/pdf" href="https://bluegenes.github.io/2020-gep/manuscript.pdf" />

  <link rel="alternate" type="text/html" href="https://bluegenes.github.io/2020-gep/v/165dd4e261e7dfc28ab08325856a74cfb1197f30/" />

  <meta name="manubot_html_url_versioned" content="https://bluegenes.github.io/2020-gep/v/165dd4e261e7dfc28ab08325856a74cfb1197f30/" />

  <meta name="manubot_pdf_url_versioned" content="https://bluegenes.github.io/2020-gep/v/165dd4e261e7dfc28ab08325856a74cfb1197f30/manuscript.pdf" />

  <meta property="og:type" content="article" />

  <meta property="twitter:card" content="summary_large_image" />

  <link rel="icon" type="image/png" sizes="192x192" href="https://manubot.org/favicon-192x192.png" />

  <link rel="mask-icon" href="https://manubot.org/safari-pinned-tab.svg" color="#ad1457" />

  <meta name="theme-color" content="#ad1457" />

  <!-- end Manubot generated metadata -->'
keywords:
- sequencing
- bioinformatics
- workflows
- open access
lang: en-US
manubot-clear-requests-cache: false
manubot-output-bibliography: output/references.json
manubot-output-citekeys: output/citations.tsv
manubot-requests-cache-path: ci/cache/requests-cache
title: Streamlining data-intensive biology with workflow systems
...






<small><em>
This manuscript
([permalink](https://bluegenes.github.io/2020-gep/v/165dd4e261e7dfc28ab08325856a74cfb1197f30/))
was automatically generated
from [bluegenes/2020-gep@165dd4e](https://github.com/bluegenes/2020-gep/tree/165dd4e261e7dfc28ab08325856a74cfb1197f30)
on May 24, 2020.
</em></small>

## Authors



+ **Taylor Reiter**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-7388-421X](https://orcid.org/0000-0002-7388-421X)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [taylorreiter](https://github.com/taylorreiter)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [ReiterTaylor](https://twitter.com/ReiterTaylor)<br>
  <small>
     Department of Population Health and Reproduction, University of California, Davis
     · Funded by Grant XXXXXXXX
  </small>

+ **C. Titus Brown**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0001-6001-2677](https://orcid.org/0000-0001-6001-2677)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [ctb](https://github.com/ctb)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [ctitusbrown](https://twitter.com/ctitusbrown)<br>
  <small>
     Department of Population Health and Reproduction, University of California, Davis
     · Funded by Moore Foundation GBMF4551
  </small>

+ **N. Tessa Pierce**<br>
    ![ORCID icon](images/orcid.svg){.inline_icon}
    [0000-0002-2942-5331](https://orcid.org/0000-0002-2942-5331)
    · ![GitHub icon](images/github.svg){.inline_icon}
    [bluegenes](https://github.com/bluegenes)
    · ![Twitter icon](images/twitter.svg){.inline_icon}
    [saltyscientist](https://twitter.com/saltyscientist)<br>
  <small>
     Department of Population Health and Reproduction, University of California, Davis
     · Funded by NSF 1711984
  </small>



## Abstract {.page_break_before}

As both sequencing technologies and data have proliferated, the bottleneck of biological sequence analysis has shifted from data generation to analysis.
Fortunately, analysis tools and techniques have evolved to cope with this ever-increasing flood of data.
Reliable and user-friendly workflow systems and software management have emerged to facilitate interrogation of many thousands of samples.
Driven and adopted by the open source scientific community, workflow systems improve reproducibility and sharing in data-intensive biology.
When combined with standardization of protocols for fundamental steps like quality control, researchers can spend less time rewriting common analyses and more time examining biological intricacies of their data.
While adoption of these tools can both facilitate and expedite reproducible data analysis, knowledge of and training in these techniques is still lacking.
Here, we provide a series of tips, tools, and "good enough" practices for leveraging workflow systems to streamline biological analysis.


## Author Summary {.page_break_before}

In this paper, we present our guide for workflow-enabled biological sequence data analysis, developed through our own teaching, training and analysis. We recognize that this is currently biased towards our own use cases and experiences, but we hope to engage in robust discussion with the open source community to build a comprehensive resource.
Our main goal is to accelerate scientists conducting sequence analyses into organized workflow practices that benefit their own research while also facilitating open and reproducible science.


## Introduction
*(draft)*

Sequencing data are now widely available for species across the tree of life, and new sequencing data continues to be generated at an incredible rate [@url:https://www.ncbi.nlm.nih.gov/sra/docs/sragrowth/].
The wealth of information present in high-throughput sequencing data has already revolutionized our understanding of the diversity and function of organisms and communities, building basic understanding from ecosystems to human health.

As sequencing analysis has matured over the past decade, several papers have presented "best" or "good enough" practices for computational biological analyses [@doi:10.1371/journal.pbio.1001745; @doi:10.1371/journal.pbio.1002303; @doi:10.1371/journal.pcbi.1005510].
These recommendations have both helped build consensus and fueled additional tool and workflow development.
Since the latest paper in 2017 [@doi:10.1371/journal.pcbi.1005510], key advancements in workflow scripting, software management, and tools that handle biological data at scale have vastly increased the power of analysis management.
In particular, the emergence of bioinformatics-focused workflow systems has empowered biologists to analyze biological data at scale.

Biological analyses often span hundreds of steps and involve a myriad of decisions ranging from small-scale tool and parameter choices to larger-scale decisions around computational experimental design and statistical analyses.
These analyses not only rely upon code written by the user, but on software, its dependencies, and the compute infrastructure and operating system on which the code is executed. 
Historically, this has led to a lack of interoperability of pipelines and compute systems and difficulties with reproducibility [@doi:10.1038/s41587-020-0439-x]. 
A rich community of workflow management systems has matured over the last decade, ushering in advances across workflow systems that are tailored to the needs of specific communities [@doi:10.1016/j.future.2017.05.041].
Modern workflow sytems separate analysis code written by the user from software and compute infrastructure, but manage and integrate both pieces [@doi:10.1038/s41587-020-0439-x].
This approach improves interoperability and therefore repeatability of workflows encoded in workflow sytems.
Further, convergence on rule-based workflow specification means code is inherently modular and easily transferable between projects [@doi:10.1007/s00778-005-0153-9; @doi:10.1016/j.future.2017.05.041].
This means the upfront cost of specifying a workflow in a system is mitigated as this code is reused, leading to faster time-to-insight [@doi:10.1016/j.future.2017.05.041; @doi:10.1007/s41019-017-0050-4].
In concert, sharing of data analysis lessons and workflows has created a critical mass of analysis code now openly available for research and training, including that done by nonprofit organizations such as the Carpentries [@doi:10.2218/ijdc.v10i1.351].
This code can be easily reused and modified to accomodate advances in bioinformatics across diverse workflow system applications, further improving efficiency [@doi:10.1007/s41019-017-0050-4].

Taken together, modern workflow management systems enable fully-contained workflows to be automated, scaleable, robust to software updates, and executable across platforms.
These workflow systems have quickly become the workhorses of modern bioinformatics, empowering researchers to execute dozens of analysis tools in a systematic manner across all experimental samples.

In our experiences with both research and training, workflow systems have greatly reduced the barrier to entry for data analysis at scale and opened the door to end-to-end reproducibility.
Here, we present some tools, strategies, and "good enough" practices for leveraging workflow systems to streamline data-intensive biology and to enhance the documentation, automation and reproducibility of your science.


## Workflows facilitate data-intensive biology

Sequence analyses require researchers to build workflows that include multiple analytic tools and execute them in a systematic manner across all experimental samples.
These workflows commonly produce hundreds to thousands of intermediate files and require incremental changes as experimental insights demand tool and parameter modifications.
Managing these steps can be both time-consuming and error-prone, even when automated using scripting languages (e.g. bash).

The emergence and maturation of workflow systems designed with bioinformatic challenges in mind has revolutionized computing in data intensive biology [@doi:10.1038/s41592-018-0046-7].
Workflow systems contain powerful infrastructure for workflow management that can coordinate runtime behavior, self-monitor progress and resource usage, and compile reports documenting the results of a workflow (**Figure @fig:workflow**).
These features ensure that the steps for data analysis are documented and repeatable from start to finish.
When paired with proper software management, fully-contained workflows are scaleable, robust to software updates, and executable across platforms, meaning they will likely still execute the same set of commands with little investment by the user in weeks, months, or years from the time of writing.

![**Workflow Systems** Bioinformatic workflow systems have built-in functionality that facilitates and simplifies running analysis pipelines.
**A. Samples** Workflow systems enable you to use the same code to run each step on each sample. Samples can be easily added if the analysis expands.
**B. Software Management** Integration with software management tools (e.g. conda, singularity, docker) can automate software installation for each step.
**C. Branching, F. Ordering, G. Parallelization** Workflow systems ensure
tasks are executed in the correct order for each sample file, and can automatically execute independent steps in parallel.
**D. Standard Steps** Many steps are now considered "standard" (e.g. quality control). Workflow languages keep all information for a step together and can be written to enable you to remix and reuse individual steps across pipelines.
**E. Rerun as necessary** Workflow systems keep track of which steps executed properly and on which samples, and allow you to rerun failed steps (or additional steps) rather than re-executing the entire workflow.
**H. Reporting** Workflow languages enable comprehensive reporting on workflow execution and resource utilization by each tool.
**I. Portability** Analyses written in workflow languages (with integrated software management) can be run across computing systems without changes to code.](images/workflow_figure.svg){#fig:workflow}

To properly direct a workflow, workflow systems need to encode information about the relationships between workflow steps.
In practice, this means that each analysis step must specify the input (or types of inputs) needed for that step, and the output (or types of outputs) being produced.
This structure results in several added benefits, beyond those mentioned above.
First, workflows become self-documented; the directed graph produced by workflow systems can be exported and visualized, producing a graphical representation of the relationships between all steps in a pipeline (see **Figure @fig:sgc_workflow**).
Next, workflows are more likely to be fully enclosed without undocumented steps that are executed by hand, meaning analyses are more likely to be reproducible.
Finally, each step becomes a self-contained unit that can be used and re-used across multiple analysis workflows, so scientists can spend less time implementing standard steps, and more time on their specific research questions.
In sum, the internal scaffolding provided by workflow systems helps build analyses that are generally better documented, repeatable, transferable, and scalable.


#### Getting started with workflows

**Using workflows without learning workflow systems** While the benefits of encoding a workflow in a workflow system are immense, the learning curve associated with implementing complete workflows in a new syntax can be daunting.
It is possible to obtain the benefits of workflow systems without learning a workflow system.
Websites like Galaxy, Cavatica, and EMBL-EBI MGnify offer online portals in which users build workflows around publicly-available or user-uploaded data [@doi:10.1093/nar/gky379; @doi:10.14694/EDBK_175029; @doi:10.1093/nar/gkz1035].
On the command line, many research groups have used workflow systems to build user-friendly pipelines that do not require learning or working with the underlying workflow software.
These tools are specified in an underlying workflow language, but are packaged in a user-friendly command-line script that coordinates and executes the workflow.
Rather than writing each workflow step, the user can specify data and parameters in a configuration file to customize the run.
Some examples include the nf-core RNA-seq pipeline [@url:https://github.com/nf-core/rnaseq/; @doi:10.1038/s41587-020-0439-x], the ATLAS metagenome assembly and binning pipeline [@url:https://github.com/metagenome-atlas/atlas; @doi:10.1101/737528], the Sunbeam metagenome analysis pipeline [@url:https://github.com/sunbeam-labs/sunbeam; @doi:10.1186/s40168-019-0658-x], and two from our own lab, the Elvers *de novo* transcriptome and differential expression pipeline [@url:https://github.com/dib-lab/elvers], and dammit eukaryotic transcriptome annotation pipeline [@url:https://github.com/dib-lab/dammit].
These tools allow users to take advantage of the benefits of workflow software without needing to invest in curating and writing their own pipeline. They are designed to execute a series of standard steps, and provide varying degrees of customizability.

**Choosing a workflow system**
At this time, there are several scriptable workflow systems that offer similar benefits for data intensive biology.
Each has it own strengths, meaning each software will meet an individuals computing goals differently (see **Table @tbl:workflows**).
Our lab has adopted Snakemake, in part due to its similarity and integration with Python, its flexibility for building and testing new analyses in different languages, and its intuitive integration with software management tools (SEE SECTION XXX)[@doi:10.1093/bioinformatics/bts480].
Software like Nextflow and Common Workflow Language require slightly more infrastructure, but in return, scale much better to pipelines with hundreds of thousands of steps and support containerization more rigidly, making them ideal for production-level pipelines [@doi:10.1038/nbt.3820; @doi:10.6084/m9.figshare.3115156.v2].
Language-specific workflow systems, such as ROpenSci's Drake [@doi:10.21105/joss.00550], are limited in the scope of tasks they can execute, but are powerful within their language and easier to integrate if comfortable in that language.

|Workflow System | Documentation | Example Workflow | Tutorial |
|----------------|---------------|------------------|------------------|
| Snakemake | https://snakemake.readthedocs.io/ | https://github.com/snakemake-workflows/chipseq | https://snakemake.readthedocs.io/en/stable/tutorial/tutorial.html |
| Nextflow | https://www.nextflow.io/ | https://github.com/nf-core/sarek | https://www.nextflow.io/docs/latest/getstarted.html |
| Common workflow language | https://www.commonwl.org/ | https://github.com/EBI-Metagenomics/pipeline-v5 | https://www.commonwl.org/user_guide/02-1st-example/index.html |
| Workflow description language | https://openwdl.org/ | https://github.com/gatk-workflows/gatk4-data-processing |  https://support.terra.bio/hc/en-us/articles/360037127992--1-howto-Write-your-first-WDL-script-running-GATK-HaplotypeCaller |
Table: Popular bioinformatics workflow systems, documentation, example workflows, and tutorials.
While we have linked to general tutorials, there may be more relevant tutorials online for your field.
Not all workflow systems are not necessarily exclusive entities: some workflow systems can translate workflows between languages or run tools or tasks written in other languages.
{#tbl:workflows}


The best workflow system to adopt may be the one with a strong and accessible local or online community in your field, somewhat independent of your computational needs.
The availability of field-specific data analysis code for reuse and modification, as well as community support for new users can facilitate the adoption process.
Fortunately, the standardized syntax required by workflow systems, combined with widespread adoption in the open science community, has resulted in a proliferation of open access workflow-system code for routine analysis steps [@doi:10.1007/978-1-4939-9074-0_24, @doi:10.1038/s41587-020-0439-x; @doi:10.21105/joss.00352].
At the same time, consensus approaches for data analysis are emerging, further encouraging reuse of existing code [@doi:10.1186/s13059-016-0881-8; @doi:10.1038/nbt.3935; @doi:10.15252/msb.20188746; @doi:10.1016/j.margen.2016.04.012; @doi:10.1038/s41579-018-0029-9].

The [Getting started developing workflows](### getting-started-developing-workflows) section contains strategies for modifying and developing workflows for your own analyses.

### Wrangling Scientific Software

Analysis workflows rely on multiple software packages to generate final results.
These tools are heterogeneous in nature: written by researchers working in different coding languages, with varied approaches to software design and optimization, and often for specific analysis goals.
Each program has a number of other programs it depends upon to function ("dependencies"), and as software changes over time to meet research needs, the results may change, even when run with identical parameters.
As a result, it is critical to take an organized approach to installing, managing, and keeping track of software and software versions.
To meet this need, most workflow managers integrate with software management systems like conda, singularity, and docker [@url:https://conda.io; @doi:10.1038/s41592-018-0046-7; @doi:10.1371/journal.pone.0177459; @doi:10.5555/2600239.2600241].

Software management systems perform some combination of software installation, management, and packaging that alleviate problems that arise from dependencies and that facilitate documentation of software versions.
On many systems, system-wide software management is overseen by system administrators, who ensure commonly-used and requested software is installed into a "module" system available to all users.
Unfortunately, this system does not lend itself well for exploring new workflows and software, as researchers do not have permission to install software themselves.
The Conda package manager has emerged as a leading software installation and management solution, largely because it handles both cluster permission and version conflict issues with a user-based software environment system, and features a straightforward "recipe" system which simplifies the process of making new software installable (**Figure @fig:conda_figure**).
Conda enables lightweight software installation and can be used with the same commands across platforms.
Alternatively, container solutions like docker and singularity allow for for the entire computational environment to be captured and distributed, including the operating system.
This ensures that an environment is completely reproducible, and is common for production workflows.

![**The conda package and environment manager simplifies software installation and management.**
**A. Conda Recipe Repositories** Each program distributed via Conda has a "recipe" describing all software dependencies needed for Conda installation (each of which must also be installable via conda). These are stored and managed in separate "channels", some of which specialize (e.g. "bioconda" specializes in bioinformatic software, "r" specializes in R language packages) [@doi:10.1038/s41592-018-0046-7]. **B. Use Conda Environments to Avoid Installation Conflicts**  Conda does not require root
privileges for software installation, thus enabling use by researchers working on shared cluster systems. However, even user-based software installation can encounter dependency conflicts. For example, you might need to use python2 to install and run a program (e.g. older scripts written by members of your lab), while also using snakemake to execute your workflows (requires python>=3.5). By installing each program into an isolated "environment" that contains only the software required to run that
program, you can ensure all programs will run without issue. Using small, separate environments for your software and building many simple environments to accommodate different steps in your workflow also reduces the amount of time it takes conda to resolve dependency conflicts between different software tools ("solve" an environment). Conda virtual environments can be created and installed either on the command line, or via an environment YAML file, as shown. In this case, the environment file
also specifies which Conda channels to search and download programs from. When specified in a YAML file, conda environments are easily transferable between computers and operating systems. Further, because the version of each package installed in an environment is recorded, workflow reproducibility is enhanced. Although portions of conda may be superceded by alternative solutions [@url:https://github.com/QuantStack/mamba], this model of software installation and management will likely
remain.](images/conda_figure.svg){#fig:conda_figure height=8in}

#### Getting started with software management

Workflow systems provide seamless integration with software management tools.
Each workflow requires different specification for initiation of software management, but typically requires about one additional line of code per step using software. 
If the software management tool is installed locally, the workflow will automatically download and install the specified environment or container and use it for specified step.

While package managers and containers greatly increase reproducibility, there are a number of ways to test software before (or without ever) needing to worry about installation.
Some software packages are available as web-based tools and through a series of data upload and parameter specifications, allow the user to interact with a tool that is running on a back-end server.
This approach is ideal for testing a tool prior to installation to determine whether it produces an appropriate or useful output on your data.
Integrated development environments like PyCharm and RStudio can also manage software installation for language-specific tools.
In our experience, the complete solution for using scientific software involves a combination of conda with these tools for developing new analyses, as well as workflow-integrated software management via conda, singularity, or docker for executing full workflows on many samples.


## Workflow-Based Project Management

Project management, including the strategies and decisions used to keep a project organized, documented, functional, and shareable, is foundational to any research program.
Clear organization and management is a learned skill that takes time to implement.
Workflow systems both simplify and improve computational project management, but even workflows that are fully specified in workflow systems require additional investment to stay organized and documented.

### Systematically document your workflows

Pervasive documentation facilitates transparency in computing and makes the goals and results of a workflow clear. 
This increases reusability of a workflow and provides context for biological insights derived from an analysis.
To achieve this purpose, documentation is necessary for all parts of a workflow and includes things like file names, folder organization, commented and clear code, and accompanying explanatory documents. 
While good documentation can be generated by the user alone, workflow systems are self-documenting to a degree, with each analysis step (and parameters) and the links between those steps completely specified. 
The simplest way to document your code, then, is to include as much of it as possible within the automated workflow framework.
For other parts of the workflow, including data analysis decisions and file organization, we discuss workflow-compatible strategies below.

#### Use consistent, self-documenting names

Using consistent and descriptive identifiers for your files, scripts, variables, workflows, projects, and even manuscripts helps keep your projects organized and interpretable for yourself and collaborators.
For workflow systems, this strategy can be implemented by tagging output files with a descriptive identifier for each analysis step, either in the filename or by placing output files within a descriptive output folder.
For example, the file shown in **Figure {@fig:filenaming}** has been preprocessed with a quality control trimming step.
For large workflows, placing results from each step of your analysis in isolated, descriptive folders can be essential for keeping your project workspace clean and organized.

![Consistent and informative file naming improves organization and interpretability. It is useful to keep unique sample identification in the filename, often with a metadata file explaining the meaning of each unique descriptor. For analysis scripts, it can help to implement a numbering scheme, where the name of first file in the analysis begins with "00", the next with "01", etc. For output files, it can help to add a short, unique identifier to output files processed with each analysis step. This particular file is a RADsequencing fastq file of a fish species that has been preprocessed with a fastq quality trimming tool (courtesy of Shannon Joslin).](images/filenaming.svg){#fig:filenaming}

#### Store workflow metadata with the workflow

Developing biological analysis workflows can involve hundreds of small decisions: What parameters work best for each step?
Why did you use a certain reference file for annotation as compared with other available files?
How did you finally manage to get around the program or installation error?
All of these pieces of information contextualize your results and may be helpful when sharing your findings.
Keeping information about these decisions in an intuitive and easily accessible place helps you find it when you need it.
To capitalize on the utility of version control systems described below, it is most useful to store this information in plain text files.
Each main directory should include notes on the data or scripts contained within, so that a collaborator could look into the directory and understand what to find there (especially since that "collaborator" is likely to be you, a few months from now!).
Code itself can contain documentation - you can include comments with the reasoning behind algorithm choice or include a link to the seqanswers post that helped you decide how to shape your differential expression analysis.
Larger pieces of information can be kept in "README" or notes documents kept alongside your code and other documents.
For example, a GitHub repository documenting the reanalysis of the Marine Microbial Eukaryote Transcriptome Sequencing Project uses a README alongside the code to document the workflow and digital object identifiers for data products [@url:https://github.com/dib-lab/dib-MMETSP; @doi:10.1093/gigascience/giy158].
While this particular strategy cannot be automated, it is critical for interpreting the final results of your workflow.

#### Document data and analysis exploration using computational notebooks

Computational notebooks allow users to combine narrative, code, and code output (e.g. visualizations) in a single location, enabling the user to conduct analysis and visually assess the results in a single file (see **Figure @fig:nb_figure**).
These notebooks allow for fully documented iterative analysis development, and are particularly useful for data exploration and developing visualizations prior to integration into a workflow or as a report generated by a workflow that can be shared with collaborators.

![**Examples of computational notebooks.** Computational notebooks allow the user to mix text, code, and results in one document.
**A** A shows an RMarkdown document viewed in the RStudio integrated development environment, while **B** shows a rendered HTML file produced by knitting the RMarkdown document [@url:https://rmarkdown.rstudio.com/].
**C** A Jupyter Notebook, where code, text, and results are rendered inline as each code chunk is executed [@doi:10.3233/978-1-61499-649-1-87].
The second grey chunk is a raw markdown chunk with text that will be rendered inline when executed.
Both notebooks generate a histogram of a metadata feature, number of generations, from a long-term evolution experiment with *Escherichia coli* [@doi:10.1038/nature18959].
Computational notebooks facilitate sharing by packaging narrative, code, and visualizations together.
Computational notebooks can be packaged with tools like Binder [@doi:10.25080/Majora-4af1f417-011].
Binder makes a GitHub repository executable, using package management systems and docker to build reproducible and executable software environments specified in the repository.
Binders can be shared with collaborators (or students in a classroom setting), and analysis and visualization can be ephemerally reproduced or altered from the code provided in computational notebooks.  
](images/nb_figure.png){#fig:nb_figure}


#### Visualize your workflow

Visual representations can help illustrate the connections in a workflow and improve the readability and reproducibility of your project. At the highest level, flowcharts that detail relationships between steps of a workflow can help provide big-picture clarification, especially when the pipeline is complicated.
For individual steps, a graphical representation of the output can show the status of the project or provide insight on additional analyses that should be added. For example, **Figure {@fig:sgc_workflow}** illustrates a workflow visualization modified from a graph produced by the workflow software Snakemake [@doi:10.1101/462788].

![A directed acyclic graph (DAG) that illustrates connections between all steps of a sequencing data analysis workflow. Each box represents a step in the workflow, while lines connect sequential steps.
The DAG shown in this figure illustrates a real bioinformatics workflow and was generated by modifying the default Snakemake workflow DAG [@doi:10.1101/462788].
The colors represent arms of the workflow that achieve a final result, such as a multiple sequence alignment of a protein of interest.
While the workflow is complex, it is coordinated by a workflow system, alleviating the need for a user to manage file interdependencies.](images/hu_dag.png){#fig:sgc_workflow}

### Version control your project

As your project develops, version control allows you to keep track of changes over time.
You may already do this in some ways, perhaps with frequent hard drive backups or by manually saving different versions of the same file  - e.g. by appending the date to a script name or appending "version_1" or "version_FINAL" to a manuscript draft.
For computational workflows, using version control systems such as Git or Mercurial can be used to keep track of all changes over time, even across multiple systems, scripting languages, and project contributors (see **Figure {@fig:version_control}**).
If a key piece of a workflow inexplicably stops working, good version control can allow you to rewind in time and identify differences from when the pipeline worked to when it stopped working.

![**Version Control** Version control systems (e.g. Git, Mercurial) work by storing incremental differences in files from one saved version ("commit") to the next. To visualize the differences between each version, text editors such as Atom and online services such as GitHub, GitLab and Bitbucket use red highlight to denote deletions, and green highlighting to denote additions. In this trivial example, a typo in version 1 (in red) was corrected (green). These systems are extremely useful for code and manuscript development, as it is possible to return to the snapshot of any saved version. This means that version control systems save you from accidental deletions, preserve code you thought you no longer needed, and preserve a record of project changes over time.](images/version_control.svg){#fig:version_control}

Version control systems also facilitate code and data availability and reproducibility for publication.
For example, to preserve the version of code that produced published results, you can create a "release", a snapshot of the current code and files in a GitHub repository.
You can then generate a digital object identifier (DOI) for that release using Zenodo and make it available to reviewers and beyond (see "sharing" section, below).

### Share your workflow and analysis code

Sharing your workflow code with collaborators, peer reviewers, and scientists seeking to use a similar method can foster discussion and review of your analysis.
Sticking to a clear documentation strategy, using a version control system, and packaging your code in notebooks or as a workflow prepare them to be easily shared with others.
To go one step further, you can package your code with a tool like Binder, Whole Tale, or Shiny apps, which run the code on cloud computers in environments identical to those in which the original computation was performed (**Figure @fig:nb_figure**, **Figure @fig:interactiveviz**) [@doi:10.25080/Majora-4af1f417-011; @doi:10.1016/j.future.2017.12.029].
These tools substantially reduce overhead associated with interacting with someones code base and data, and in doing so, make it fast and easy to rerun portions of the analysis, check accuracy, or even tweak the analysis to produce new results. If you choose to share your code and workflows publicly, you will also help contribute to the growing resource of biological analyses available for your chosen workflow system.

![Interactive vizualizations facilitate sharing and repeatability.
**A** Interactive vizualization dashboard in the Pavian Shiny app for metagenomic analysis [@url:https://fbreitwieser.shinyapps.io/pavian/; @doi:10.1093/bioinformatics/btz715].
Shiny allows you to build interactive web pages using R code.
Data is manipulated  by R code in real-time in a web page, producing analysis and visualizations of a data set.
Shiny apps can contain user-specifiable parameters, allowing a user to control visualizations or analyses. As seen above, sample "PT1" is selected, and taxonomic ranks class and order are excluded.
Shiny apps allow collaborators who may or may not know R to modify R visualizations to fit their interests.
**B** Plotly heatmap of transcriptional profiling in human brain samples [@url:https://plotly.com/python/v3/ipython-notebooks/bioinformatics/#4-heatmap-of-gene-expression].
Hovering over a cell in the heatmap displays the sample names from the x and y axis, as well as the intensity value.
Plotting tools like plotly and vega-lite produce single interactive plots that can be shared with collaborators or integrated into websites [@url:https://plotly.com/; @doi:10.1109/TVCG.2016.2599030].
Interactive visualizations are also helpful in exploratory data analysis.
](images/interactive_viz.png){#fig:interactiveviz}


### Getting started developing workflows

In our experience, the best way to have your workflow system work _for_ you is to include as much of your analysis as possible within the automated workflow framework, use self-documenting names, include analysis visualizations, and keep rigorous documentation alongside your workflow that enables you to understand each decision and entirely reproduce any manual steps. 
Some of the tools discussed above will inevitably change over time, but these principles apply broadly and will help you design clear, well-documented, and reproducible analyses. 
Ultimately, you'll need to experiment with strategies that work for you -- what is most important is to develop a clear set of strategies and implement them tenaciously. 
Below, we provide a few practical strategies to try as you begin developing your own workflows.

**Start with working code**
Starting workflow development with functioning code provides a reliable workflow framework free of syntax errors, allowing the user to customize and tailor the workflow to their data while minimizing cognitive load.
Workflow tutorials and code sharing websites like GitHub, GitLab, and Bitbucket have many publicly available workflows.
If a workflow is available through Binder, you can test and experiment with workflow modification on Binder's cloud system without needing to install a workflow manager or software management tool [@doi:10.25080/Majora-4af1f417-011].
When building a workflow for the first time, selecting an example workflow with sample data can help verify the analysis works.
**Table @tbl:workflows** provides links to official repositories containing tutorials and example biological analysis workflows.

**Test with subsampled data**
While a workflow may run on test data, this is not a guarantee it will run on all data.
After verifying your chosen example workflow is functional, try running it with your own data or some public data related to your species or condition of interest.
Trying the workflow on a small subset of the data first can save time, energy, and computational resources.
For example, if working with FASTQ data, you can subsample the first million lines of a file (first 250k reads) by running:

`head -n 1000000 FASTQ_FILE.fq > test_fastq.fq`

While there are many more sophisticated ways to subsample reads, this technique should be sufficient for testing each step of a workflow prior to running your full dataset.

**Document your process** 
Writing documentation in plain text allows your note files to be saved under version control along with your workflow. 
We recommend using Markdown language for your notes so they can include helpful headings, code formatting, and embedded images. 
While there are many text editors to choose from, editors with visual formatting previewing such as Hackmd or Atom render previews of text written in Markdown [@url:https://hackmd.io/, @url:https://atom.io/], as do webservices like GitHub.

**Develop your workflow**
We recommend iteratively modifying and adding workflow steps to meet your data analysis needs. 
This strategy allows you to find and fix mistakes on small sections of the workflow. 
Working with subsampled data while building new steps can make development more efficient. 
Tutorials and tool documentation are useful companions during development; as with any language, remembering workflow-specific syntax takes time and practice.

**Back up early and often**
As you write new code, back up your changes in an online repository such as GitHub, GitLab, or Bitbucket.
These services support both drag-and-drop and command line interaction.
Data backup will be discussed in the next section, [Data and resource management for workflow-enabled biology](## data-and-resource-management-for-workflow-enabled-biology).

**Scale up your workflow**
Bioinformatic tools vary in the resources they require: some analysis steps are compute-intensive, other steps are memory intensive, and still others will have large intermediate storage needs.
If using high-performance computing system or the cloud, you will need to request resources for running your pipeline, often provided as a simultaneous execution limit or purchased by your research group on a cost-per-compute basis.
Workflow systems provide built-in tools to monitor resource usage for each step.
Running a complete workflow on a single sample with resource monitoring enabled generates an estimate of computational resources needed for each step. 
These estimates can be used to set appropriate resource limits for each step when executing the workflow on your remaining samples.

**Find a community and ask for help when you need it**
Local users groups are helpful communities when learning a workflow language.
When you are first learning, help from more advanced users can save you hours of frustration.
After you've progressed, providing that same help to new users can help you cement the syntax in your mind and tackle more advanced uses.
If no local community is available, there are online forums related to workflow languages.
These workflow systems have been enthusiastically adopted by the open science community, and as a consequence, there is a critical mass of tutorials and open access code, code discussion on forums and via social media, particularly twitter.
Be respectful of people's time and energy: post in the relevant workflow forums only when you have hit a stopping point you are unable to work through.


## Data and resource management for workflow-enabled biology

Advancements in sequencing technologies have greatly increased the volume of data available for biological query [@url:https://www.ncbi.nlm.nih.gov/sra/docs/sragrowth/].
Workflow systems, by virtue of automating many of the time-intensive project management steps traditionally required for data-intensive biology, can increase our capacity for data analysis.
However, conducting biological analyses at this scale requires a coordinated approach to data and computational resource management.
Below, we provide recommendations for data acquisition, management, and quality control that have become especially important as the scale of data has increased.

### Managing large-scale datasets

Experimental design, finding or generating data, and quality control cannot yet be automated but are quintessential parts of data intensive biology.
There is no substitute for taking the time to properly design your analysis, identify appropriate data, and conduct sanity checks on your files.
While these tasks are not automatable, many tools and databases can aid in these processes.

*maybe link: Many of these considerations are addressed in a data carpentry lesson (https://datacarpentry.org/organization-genomics/).*

#### Look for appropriate publicly-available data

With vast amounts of sequencing data already available in public repositories, it is often possible to begin investigating your research question by seeking out publicly available data.
In some cases, these data will be sufficient to conduct your entire analysis.
In others cases, particularly for biologists conducting novel experiments, these data can inform decisions about sequencing type, depth, and replication, and can help uncover potential pitfalls before they cost valuable time and resources.

Most journals now require data for all manuscripts to be made accessible, either at publication or after a short moratorium.
Further, the FAIR (findable, accessible, interoperable, reusable) data movement has improved the data sharing ecosystem for data-intensive biology [@doi:10.1038/sdata.2016.18; @doi:10.1093/nar/gkx1097; @doi:10.1128/AEM.01444-19; @doi:10.1186/s13059-018-1491-4; @doi:10.1016/j.molp.2018.07.005; @doi:10.1038/s41586-019-1238-8; @doi:10.1038/s41586-019-1238-8; @doi:10.1093/nar/gky995].
You can find relevant sequencing data either by starting from the "data accessibility" sections of papers relevant to your research or by directly searching for your organism, environment, or treatment of choice in public data portals and repositories.
The International Nucleotide Sequence Database Collaboration (INSDC), which includes the Sequence Read Archive (SRA), European Nucleotide Archive (ENA), and DataBank of Japan (DDBJ) is the largest repository for raw sequencing data [@doi:10.1093/nar/gkv1323].
Additional curated databases focus on processed data instead, such as gene expression in the Gene Expression Omnibus (GEO) [@doi:10.1093/nar/30.1.207].
Organism-specific databases such as **Wormbase** (*Caenorhabditis elegas*) specialize on curating and integrating sequencing and other data associated with a model organism [@doi:10.1093/nar/gkz920].
The SRA, ENA, and DDBJ no longer accept raw sequencing data from large consortia projects, so data from these efforts are often hosted in consortia-specific databases such as those hosted by the Tara Ocean Foundation [@doi:10.1038/sdata.2015.23].
Unlike the SRA and associated databases which are centralized and searchable, databases overseen by consortia often require domain-specific knowledge and have unique download and authentication protocols.
Finally, rather than focusing on certain data types or organisms, some repositories are designed to hold any data and metadata associated with a specific project or manuscript (e.g. Open Science Framework, Dryad, Zenodo [@doi:10.5195/JMLA.2017.88]).

#### Consider analysis when generating your own data

If generating your own data, proper experimental design and planning are essential.
For cost-intensive sequencing data, there are a range of decisions about experimental design and sequencing (including sequencing type, sequencing depth per sample, and biological replication) that impact your ability to properly address your research question.
These considerations will be different for different types of sequence analysis.
While we have curated a series of domain-specific references that may be useful as you go about designing your experiment (see **Table @tbl:seq_resources**), conducting discussions with experienced bioinformaticians and statisticians, **prior to beginning your experiments** if possible, is the best way to ensure you will have sufficient statistical power to detect effects.
Given the resources invested in collecting samples for sequencing, it's important to build in a buffer to preserve your experimental design in the face of unexpected laboratory or technical issues.
Once generated, it is always a good idea to have multiple independent backups of raw sequencing data, as it typically cannot be easily regenerated if lost to computer failure or other unforeseeable events.

|  Sequencing type | Resources |
| --- | --- |
|  RNA-sequencing | [@doi:10.1186/s13059-016-0881-8; @doi:10.1261/rna.058339.116; @doi:10.1261/rna.046011.114] |
|  Metagenomic sequencing | [@doi:10.1038/nbt.2235; @doi:10.1038/nbt.3935; @doi:10.1016/j.tim.2018.11.003]|
|  Amplicon sequencing | [@doi:10.7554/eLife.46923; @doi:10.1371/journal.pone.0124671; @doi:10.1038/nbt.3981] |
|  Microbial isolate sequencing | [@doi:10.1038/srep08747] |
|  Eurkaryotic genome sequencing |  |
|  Whole-genome resequencing | [@doi:10.1111/mec.14264] |
|  Rad seq |  |
|  Chip seq |  |
|  ATAC seq |  |
|  single cell RNA-seq | [@doi:10.1186/s13059-016-0927-y; @doi:10.1186/s13073-017-0467-4] |
|  ? |  |

Table: References for experimental design and considerations for common sequencing chemistries. {#tbl:seq_resources}

As your experiment progresses, keep track of as much information as possible: dates and times of sample collection, storage, and extraction, sample names, aberrations that occurred during collection, kit lot used for extraction, and any other sample measurements you might be able to obtain (temperature, location, metabolite concentration, name of collector, etc).
This metadata allows you to keep track of your samples, to control for batch effects that may arise from unintended batching during sampling or experimental procedures and makes the data you collect reusable for future applications and analysis by yourself and others.
Wherever possible, follow the standard guidelines for formatting data for scientific computing to limit downstream processing and simplify analyses requiring these metadata (see: [@doi:10.1371/journal.pcbi.1005510]).

### Getting started with sequencing data

#### Protect valuable data

Other than the workflow itself, raw data are the most important files associated with a workflow as they cannot regenerated if accidentally altered or deleted.
Keeping a read-only copy of raw data alongside a workflow as well multiple backups protects your data from accidents and computer failure. 
This also removes the imperative of storing intermediate files as these can be easily regenerated by the workflow.

When sharing or storing files and results, data version control keeps track of differences in files such as changes from tool parameters or versions.
The version control tools discussed in the [Workflow-based project management](## workflow-based-project-management) section are primarily designed to handle small files, but version control and backup repositories also exist for larger files and datasets.

The Open Science Framework (OSF; [@doi:10.5195/JMLA.2017.88]) is a free service that provides powerful collaboration and sharing tools, provides built-in version control, integrates with other storage and version control repositories, guarantees data preservation, and enables you to keep projects private until they are ready to share. Like other services geared towards data sharing, OSF also enables generation of a digital object identifier (doi) for each project.
While other services such as Git Large File Storage (LFS), Figshare [@url:https://figshare.com/], Zenodo [@url:https://zenodo.org/], and the Dryad Digital Repository [@url:https://datadryad.org/] each provide important services for sharing and version control, OSF provides the most comprehensive set of free tools for managing data storage and backup.
As free tools often limit the size of files that can be stored, a number of cloud backup and storage services are also available for purchase or via university contract, including Google Drive, Box, Dropbox, Amazon Web Services, and Backblaze. Full computer backups can be conducted to these storage locations with tools like rclone [@doi:10.1111/2041-210X.12550].

#### Ensure data integrity during transfers

If you're working with publicly-available data, you may be able to work on a compute system where the data are already available, circumventing time and effort required for downloading and moving the data.
Databases such as the Sequence Read Archive (SRA) are now available on commercial cloud computing systems, and open source projects such as Galaxy enable import and work on SRA sequence files directly from a web browser [@doi:10.1093/nar/gky379; @url:https://www.ncbi.nlm.nih.gov/sra/docs/sra-cloud/].
Ongoing projects such as the NIH Common Fund Data Ecosystem aim to develop a data portal to make NIH Common Fund data, including biomedical sequencing data, more findable, accessible, interoperable, and reusable (FAIR).

In most cases, you'll still need to transfer some data - either downloading raw data or transferring important intermediate and results files for backup and sharing (or both).
Transferring compressed files (gzip, bzip2, BAM/CRAM, etc.) can improve transfer speed and save space, and checksums can be used to to ensure file integrity after transfer (see **Figure @fig:checksum**). 

![**Use Checksums to ensure file integrity** Checksum programs (e.g. md5, sha256) encode file size in a single value known as a "checksum". For any file, this value will be identical across platforms when calculated using the same checksum program. When transferring files, calculate the value of the checksum prior to transfer, and then again after transfer. If the value is not identical, there was an error introduced during transfer (e.g. file truncation, etc). Checksums are often provided alongside publicly available files, so that you can verify proper download. Tools like Rsync and Rclone that automate file transfers use checksums internally to verify that files were transferred properly, and some GUI file transfer tools (e.g. cyberduck) can assess checksums when they are provided [@doi:10.1111/2041-210X.12550, @url:https://cyberduck.io/].
](images/checksum.svg){#fig:checksum height=2.5in}

#### Perform quality control at every step

The quality of your input data has a major impact on the quality of the output results, no matter whether your workflow analyzes six samples or 600 samples.
Assessing data at every analysis step can reveal problems and errors early, before they waste valuable time and resources.
Using quality control tools that provide metrics and visualizations can help you assess your datasets, particularly as the size of your input data scales up.
However, data from different species or sequencing types can produce different quality control results.
You are ultimately the single most effective quality control tool that you have, so it is important to critically assess each metric to determine those that are relevant for your particular data.

**Look at your files**
Quality control can be as simple as looking at the first few and last few lines of input and output data files, or checking the size of those files (see **Table @tbl:bash_commands**).
To develop an intuition for what proper inputs and outputs look like for a given tool, it is often helpful to first run the test example or data that is packaged with the software.
Comparing these input and output file formats to your own data can help identify and address inconsistencies.

|  command | function | example |
| --- | --- | --- |
|  ls -lh | list files with information in a human-readable format | ls -lh \*fastq.gz |
|  head | print the first 6 lines of a file to standard out | head samples.csv |
|  tail | print the last 6 lines of a file to standard out | tail samples.csv |
|  less | show the contents of a file in a scrollable screen | less samples.csv |
|  zless | show the contents of a gzipped file in a scrollable screen | zless sample1.fastq.gz |
|  wc -l | count the number of lines in a file | wc -l ecoli.fasta |
|  cat | print a file to standard out | cat samples.csv |
|  grep | find matching text and print the line to standard out | grep ">" ecoli.fasta |
|  cut | cut columns from a table | cut -d"," -f1 samples.csv |
Table: Some bash commands are useful to quickly explore the contents of a file. By using these commands, the user can detect common formatting problems or other abnormalities. {#tbl:bash_commands}

**Visualize your data**
Visualization is another powerful way to pick out unusual or unexpected patterns.
Although large abnormalities may be clear from looking at files, others may be small and difficult to find.
Visualizing raw sequencing data with FastQC (**Figure {@fig:multiqc}A**) and processed sequencing data with tools like the Integrative Genome Viewer and plotting tabular results files using python or R can make aberrant or inconsistent results easier to track down [@url:https://www.bioinformatics.babraham.ac.uk/projects/fastqc/; @doi:10.1093/bib/bbs017].

![**Visualizations produced by MultiQC.**
**A** MultiQC summary of FastQC Per Sequence GC Content for 1905 metagenome samples. FastQC provides quality control measurements and visualizations for raw sequencing data, and is a near-universal first step in sequencing data analysis because of the insights it provides  [@url:https://www.bioinformatics.babraham.ac.uk/projects/fastqc/; @doi:10.1093/bib/bbs017].
FastQC measures and summarizes 10 quality metrics and provides recommendations for whether the sample is within an acceptable quality range.
Not all metrics readily apply to all sequencing data types. For example, while multiple GC peaks might be concerning in whole genome sequencing of a bacterial isolate, we would expect a non-normal distrubtion for some metagenome samples that contain organisms with diverse GC content.
Samples like this can be seen in red in this figure.
**B** MultiQC summary of Salmon *quant* reads mapped per sample for RNA-seq samples [@doi:10.1038/nmeth.4197]. MultiQC finds and automatically parses log files from other tools and generates a combined report and parsed data tables that include all samples. MultiQC currently supports 88 tools. In this figure, we see that MultiQC summarizes the number of reads mapped and percent of reads mapped, two values that are reported in the Salmon log files.
](images/multiqc.svg){#fig:multiqc}

**Pay attention to warnings and log files**
Many tools generate log files or messages while running.
These files contain information about the quantity, quality, and results from the run, or error messages about why a run failed.
Inspecting these files can be helpful to make sure tools ran properly and consistently, or to debug failed runs.
Parsing and visualizing log files with a tool like MultiQC can improve interpretability of program-specific log files (**Figure @fig:multiqc** [@doi:10.1093/bioinformatics/btw354]).

**Look for common biases in sequencing data**
Biases in sequencing data originate from experimental design, methodology, sequencing chemistry, or workflows, and are helpful to target specifically with quality control measures.
The exact biases in a specific data set or workflow will vary greatly between experiments.
For example, PCR duplicates can cause problems in libraries that underwent an amplification step, and often need to be removed prior to downstream analysis [@doi:10.1038/nrg3788; @doi:10.1038/srep25533; @doi:10.1086/BBLv227n2p146; @doi:10.1186/s12864-018-4933-1; @doi:10.1186/s13059-014-0420-4].

**Check for contamination**
Contamination can arise during sample collection, nucleotide extraction, library prepartion, or through sequencing spike-ins like PhiX, and could change data interpretation if not removed [@doi:10.1073/pnas.1510461112; @doi:10.1073/pnas.1600338113; @doi:10.1186/1944-3277-10-18].
Libraries sequenced with high concentrations of free adapters or with low concentration samples may have increased barcode hopping, leading to contamination between samples [@doi:10.1111/1755-0998.13009].

**Consider the costs and benefits of stringent quality control for your data**
Good quality data is essential for good downstream analysis.
However, stringent quality control can sometimes do more harm than good.
For example, depending on sequencing depth, stringent quality trimming of RNA-sequencing data may reduce isoform discovery [@doi:10.3389/fgene.2014.00013].
To determine what issues are most likely to plague your specific data set, it can be helpful to find recent publications using a similar experimental design, or to speak with experts at a sequencing core.

Because sequencing data and applications are so diverse, there is no one-size-fits-all solution for quality control.
It is important to think critically about the patterns you expect to see given your data and your biological problem, and consult with technical experts whenever possible.

### Securing and managing appropriate computational resources

Independent of workflows, sequence analysis requires access to computing systems with adequate storage and analysis power for your data.
For some smaller-scale datasets, local desktop or even laptop systems can be sufficient, especially if using tools that implement data-reduction strategies such as minhashing [@doi:10.1186/s40168-019-0653-2].
However, larger projects require additional computing power, or may be restricted to certain operating systems (e.g. linux).
For these projects, solutions range from research-focused high performance computing systems to research-integrated commercial analysis platforms.
Both research-only and  and commercial clusters provide avenues for research and educational proposals to enable access to their computing resources (see **Table @tbl:computational_resources**).
In preparing for data analysis, be sure to allocate sufficient computational resources and funding for storage and analysis, including large intermediate files and resources required for personnel training.

|  Cloud Provider | Standard Model | Limits |
| --- | --- | --- |
|  Amazon Web Services | Paid |  |
|  Bionimbus Protected Data Cloud | Research allocation | users with eRA commons account |
|  Cyverse Atmosphere | Free with limits | storage and compute hours |
|  EGI federated cloud | Access by contact | European partner countries |
|  Galaxy | Free with storage limits | data storage limits |
|  Google Cloud Platform | Paid |  |
|  Google Colab | Free | computational notebooks, no resource guaruntees |
|  Microsoft Azure | Paid |  |
|  NSF XSEDE | Research allocation | USA researchers or collaborators |
|  Open Science Data Cloud | Research allocation |  |
|  Wasabi | Paid | data storage solution only |
Table: **Research cloud resources** Cloud provider indicates the name of the cloud, standard model indicates the most common route toward using the cloud, and limitations indicates limitations in access or services provided by the cloud. {#tbl:computational_resources}

### Getting started with resource management

As the scale of data increases, the resources required for analysis can balloon. Bioinformatic workflows can be long-running, require high-memory systems, or involve intensive file manipulation. Some of the strategies below may help you manage computational resources for your project.

**Apply for research units if eligible**
There are a number of cloud computing services that offer grants providing computing resources to data-intensive researchers (**Table {@tbl:computational_resources}**). In some cases, the resources provided may be sufficient to cover your entire analysis.

**Develop on a local computer when possible**
Since workflows transfer easily across systems, it can be useful to develop individual analysis steps on a local laptop.
If the analysis tool will run on your local system, test the step with subsampled data, such as that created in the "Getting started developing workflows" section.
Once working, the new workflow component can be run at scale on a larger computing system.
Workflow system tool resource usage reporting can help determine the increased resources needed to execute the workflow on larger systems. 
For researchers without access to free or granted computing resources, this strategy can save significant cost.

**Gain quick insights using sketching algorithms**
Understanding the basic structure of data, the relationship between samples, and the approximate composition of each sample can very helpful at the beginning of data analysis, and can often drive analysis decisions in different directions than those originally intended.
Although most bioinformatics workflows generate these types of insights, there are a few tools that do so rapidly, allowing the user to generate quick hypotheses that can be further tested by more extensive, fine-grained analyses.
Sketching algorithms work with compressed approximate representations of sequencing data and thereby reduce runtimes and computational resources.
These approximate representations retain enough information about the original sequence to recapitulate the main findings from many exact but computationally intensive workflows.
Most sketching algorithms estimate sequence similarity in some way, allowing you to gain insights from these comparisons.
For example, sketching algorithms can be used to estimate all-by-all sample similarity which can be visualized as a Principle Component Analysis or a multidimensional scaling plot, or can be used to build a phylogenetic tree with accurate topology.
Sketching algorithms also dramatically reduce the runtime for comparisons against databases (e.g. all of GenBank), allowing users to quickly compare their data against large public databases.
Sketching algorithms have been reviewed in-depth by Rowe [@doi:10.1186/s40168-019-0653-2].

**Use the right tools for your question**
RNA-seq analysis approaches like differential expression or transcript clustering rely on transcript or gene counts.
Many tools can be used to generate these counts by quantifying the number of reads that overlap with each transcript or gene.
For example, tools like STAR and HISAT2 produce alignments that can be post-processed to generate per-transcript read counts [@doi:10.1093/bioinformatics/bts635; @doi:10.1038/s41587-019-0201-4].
However, these tools generate information-rich output, specifying per-base alignments for each read.
If you are only interested in counts per read, quasi-mapping tools produce the minimum information necessary for read quantification, thereby reducing the time and resources needed to generate and store read count information [@doi:10.1093/bioinformatics/btw277].


## Troubleshooting: how to help yourself and when to get help

If you have tried the strategies above and are having trouble with your workflow, it's time to ask for help.
The first point of attack is always to Google the error, including any identifying error message or code, the program name, and if necessary, the type of data you're running.
There are a vast array of online resources for bioinformatic help ranging from question sites such as Stack Overflow and BioStars, to personal or academic blogs or even tutorials and lessons written by experts in the field [@doi:10.1371/journal.pcbi.1002216].
In most cases, the error you've encountered has been encountered many times before, and often the solution is readily available.
If you can't find any solutions in the relevant search results, it's time to escalate.
If the error is with a specific program, it's best to post on that program's help or issue location (e.g. GitHub Issues), or google group mailing list.
Often the authors of your software will post their preferred location for answering questions and solving errors related to their program.
Be sure to include the relevant details of your error, including terminal output and the version of the software you are using.
 If your error or question is more general, such as asking about program choice or workflows, Stack Overflow is a good choice.
First, search through related topics to ensure your question has not already been answered.
If it hasn't, make a post to a relevant section, and be sure to include all relevant information in your post - type of data you have, approaches you've tried already, relevant error message, etc.

While there is lots of help available online, there's no substitute for local communities where you can get help working with your data and learning to troubleshoot.
Many people around you may be experiencing similar issues and finding it difficult to find appropriate help.
Developing a local bioinformatics community, either via seminar series or meetup sessions for data analysis, can also help in both improving and expanding your work in this area.
Once you establish a local community, it may also be useful to set up a local online sites (e.g. discourse) for group troubleshooting.
While this may seem like just a local version of Stack Overflow, the local, member-only nature can help create a safe and collaborative online space for troubleshooting problems often encountered by your local bioinformatics community.
The benefit to beginners is clear: learning the best way to post questions and the important parts of errors, while getting their questions answered so they can move forward in their research.
However, intermediate users may find these communities most useful, as they can also accelerate their own troubleshooting skills by helping others solve issues that they have already struggled through.
While it can be helpful to have some experts available to help answer questions or to know when to escalate to Stack Overflow or other communities, a collaborative community of practice with members at all experience levels can help all its members move their science forward faster.


## Conclusion

Bioinformatics-focused workflow systems have revolutionized data-intensive biology, and enabled biologists to cope with the massive scale of data now becoming available.
Workflow-integrated software management tools remove tool installation as a barrier to data exploration and analysis, and free biologists to less time rewriting common analysis steps, and spend more time on interesting biological questions.
With a few directed strategies for project, data, and resource management, these workflow systems can quickly streamline bioinformatic analyses and reduce the time to insight.
We hope the tips contained here will enable more biologists take advantage of workflow-enabled data-intensive biology.


### Acknowledgements

thanks!

### Competing Interests

|Author|Competing Interests|Last Reviewed|
|---|---|---|

### Author Contributions

|Author|Contributions|
|---|---|


## References {.page_break_before}

<!-- Explicitly insert bibliography here -->
<div id="refs"></div>
