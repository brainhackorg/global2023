{
  "Title": "The evolution of Nipype into Pydra",
  "link_to_issue": "https://github.com/brainhackorg/global2023/issues/61",
  "issue_number": 61,
  "labels": [
    {
      "name": "git_skills:1_commit_push",
      "description": "",
      "color": "5B6C2C"
    },
    {
      "name": "git_skills:2_branches_PRs",
      "description": "",
      "color": "5B6C2C"
    },
    {
      "name": "modality:DWI",
      "description": "",
      "color": "1d76db"
    },
    {
      "name": "modality:fMRI",
      "description": "",
      "color": "1d76db"
    },
    {
      "name": "modality:MRI",
      "description": "",
      "color": "1d76db"
    },
    {
      "name": "programming:documentation",
      "description": "",
      "color": "5319E7"
    },
    {
      "name": "programming:Python",
      "description": "",
      "color": "5319E7"
    },
    {
      "name": "project_development_status:2_releases_existing",
      "description": "",
      "color": "D93F0B"
    },
    {
      "name": "project_tools_skills:familiar",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "project_type:documentation",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "topic:reproducible_scientific_methods",
      "description": "",
      "color": "FBCA04"
    },
    {
      "name": "project_type:pipeline_development",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "project_type:method_development",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "status:web_ready",
      "description": "",
      "color": "0E8A16"
    },
    {
      "name": "Project",
      "description": "",
      "color": "B60205"
    },
    {
      "name": "git_skills:3_continuous_integration",
      "description": "",
      "color": "5B6C2C"
    },
    {
      "name": "project_tools_skills:comfortable",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "tools:AFNI",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "tools:ANTs",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "tools:DIPY",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "tools:FieldTrip",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "tools:fMRIPrep",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "tools:Freesurfer",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "tools:FSL",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "tools:MNE",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "tools:MRtrix",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "tools:Nipype",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "tools:SPM",
      "description": "",
      "color": "EA1D4E"
    }
  ],
  "content": "### Title\r\n\r\nThe evolution of Nipype into Pydra\r\n\r\n### Leaders\r\n\r\nTom Close (GH+MM: @tclose) and Arkiev D'Souza (GH: @arkiev MM:  adsouza)\r\n\r\n### Collaborators\r\n\r\nDorota Jarecka (GH: @djarecka MM: dorota), Chris Markiewicz (GH: @effigies, MM: markiewicz), Yibei Chen (GH: @yibeichan MM: yibeichen), Ghislain Vaillant (GH+MM: @ghisvail) and Satra Ghosh (GH+MM: @satra)\r\n\r\n### Brainhack Global 2023 Event\r\n\r\nBrainhack Australasia\r\n\r\n### Project Description\r\n\r\n[Nipype](https://nipype.readthedocs.io/) is a Python library that provides a uniform interface to existing neuroimaging software and facilitates interaction between these packages within a single workflow. It forms the basis of widely-used pipelines such as [C-PAC](https://fcp-indi.github.io/) and [fMRIPrep](https://fmriprep.org/).\r\n\r\nDespite Nipype's success and longevity, some limitations of its design have become apparent over time. In particular,\r\n\r\n- the complexity of designing new task interfaces\r\n- inability to run workflow nodes in separate software containers\r\n- inability to split/join workflow nodes over lists generated at execution time\r\n- difficulty following the workflow construction syntax due to the separation of nodes and connections\r\n\r\nTherefore, at the 2018 OHBM BrainHack in Singapore, a number of Nipype's core developers sat down to start planning a rewritten 2nd generation, which eventually turned into [Pydra](https://pydra.readthedocs.io/en/latest/).\r\n\r\nIn the intervening years, Pydra has matured into a fully functioning alternative to Nipype that is almost ready for production. However, it is missing the large library of tool interfaces that have been developed for Nipype over the years. Therefore, the [Nipype2Pydra](https://github.com/nipype/nipype2pydra) conversion tool has been developed to semi-automatically convert existing Nipype interfaces into Pydra syntax. Separate repositories/packages have been created for each toolkit implemented in Nipype, containing YAML specifications to guide the conversion process (e.g. [pydra-freesurfer](https://github.com/nipype/pydra-freesurfer)).\r\n\r\nIn this hackathon, we aim to work through the semi-converted interfaces and complete the conversion process by editing corresponding the YAML specs. Starting off with some of the most popular toolkits, we will hopefully be able to build up enough of a library of interfaces to allow popular Nipype workflows to be ported across to Pydra.\r\n\r\nPlease read the [contribution guide](https://github.com/nipype/pydra/blob/master/CONTRIBUTING.md) for tips on getting started and our policies on acknowledging contributions.\r\n\r\n### Link to project repository/sources\r\n\r\n- https://github.com/nipype/pydra\r\n- https://github.com/nipype/nipype2pydra\r\n\r\n### Goals for Brainhack Global\r\n\r\n- Convert as many interfaces from Nipype to Pydra as possible\r\n- Complete the Nipype2Pydra workflow converter\r\n\r\n### Good first issues\r\n\r\nTODO\r\n\r\n\r\n### Communication channels\r\n\r\nhttps://mattermost.brainhack.org/brainhack/channels/nipype\r\n\r\n### Skills\r\n\r\nRequired: Some Python\r\nNice to have: experience working with neuroimaging toolkits (e.g. FSL, ANTs) but not essential\r\nRecommended: Reasonably comfortable with git\r\n\r\n### Onboarding documentation\r\n\r\nhttps://github.com/nipype/pydra/blob/master/CONTRIBUTING.md\r\n\r\n### What will participants learn?\r\n\r\n* How to design Pydra interfaces\r\n* Gain familiarity with neuroimaging toolkits\r\n\r\n### Data to use\r\n\r\nThis project is not focused on any specific dataset. We will be typically using dummy datasets and sample datasets from [OpenNeuro](https://openneuro.org/), e.g. [ds000114](https://openneuro.org/datasets/ds000114).\r\n\r\n### Number of collaborators\r\n\r\nmore\r\n\r\n### Credit to collaborators\r\n\r\nProject collaborators are listed in the projects' Zenodo reference\r\n\r\n### Image\r\n\r\nLeave this text if you don't have an image yet.\r\n\r\n### Type\r\n\r\ndocumentation, method_development, pipeline_development\r\n\r\n### Development status\r\n\r\n2_releases_existing\r\n\r\n### Topic\r\n\r\nreproducible_scientific_methods\r\n\r\n### Tools\r\n\r\nAFNI, ANTs, DIPY, FieldTrip, fMRIPrep, Freesurfer, FSL, MNE, MRtrix, Nipype, SPM\r\n\r\n### Programming language\r\n\r\nPython\r\n\r\n### Modalities\r\n\r\nDWI, fMRI, MRI\r\n\r\n### Git skills\r\n\r\n1_commit_push, 2_branches_PRs, 3_continuous_integration\r\n\r\n### Anything else?\r\n\r\n_No response_\r\n\r\n### Things to do after the project is submitted and ready to review.\r\n\r\n- [ ] Add a comment below the main post of your issue saying: `Hi @brainhackorg/project-monitors my project is ready!`\r\n- [ ] Twitter-sized summary of your project pitch.",
  "project_url": "https://github.com/nipype/pydra-",
  "project_description": "\r\n\r\n[Nipype](https://nipype.readthedocs.io/) is a Python library that provides a uniform interface to existing neuroimaging software and facilitates interaction between these packages within a single workflow. It forms the basis of widely-used pipelines such as [C-PAC](https://fcp-indi.github.io/) and [fMRIPrep](https://fmriprep.org/).\r\n\r\nDespite Nipype's success and longevity, some limitations of its design have become apparent over time. In particular,\r\n\r\n- the complexity of designing new task interfaces\r\n- inability to run workflow nodes in separate software containers\r\n- inability to split/join workflow nodes over lists generated at execution time\r\n- difficulty following the workflow construction syntax due to the separation of nodes and connections\r\n\r\nTherefore, at the 2018 OHBM BrainHack in Singapore, a number of Nipype's core developers sat down to start planning a rewritten 2nd generation, which eventually turned into [Pydra](https://pydra.readthedocs.io/en/latest/).\r\n\r\nIn the intervening years, Pydra has matured into a fully functioning alternative to Nipype that is almost ready for production. However, it is missing the large library of tool interfaces that have been developed for Nipype over the years. Therefore, the [Nipype2Pydra](https://github.com/nipype/nipype2pydra) conversion tool has been developed to semi-automatically convert existing Nipype interfaces into Pydra syntax. Separate repositories/packages have been created for each toolkit implemented in Nipype, containing YAML specifications to guide the conversion process (e.g. [pydra-freesurfer](https://github.com/nipype/pydra-freesurfer)).\r\n\r\nIn this hackathon, we aim to work through the semi-converted interfaces and complete the conversion process by editing corresponding the YAML specs. Starting off with some of the most popular toolkits, we will hopefully be able to build up enough of a library of interfaces to allow popular Nipype workflows to be ported across to Pydra.\r\n\r\nPlease read the [contribution guide](https://github.com/nipype/pydra/blob/master/CONTRIBUTING.md) for tips on getting started and our policies on acknowledging contributions.\r\n\r\n"
}