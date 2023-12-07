{
  "Title": "Neurobagel",
  "link_to_issue": "https://github.com/brainhackorg/global2023/issues/75",
  "issue_number": 75,
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
      "name": "project_tools_skills:familiar",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "project_type:coding_methods",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "project_type:documentation",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "tools:BIDS",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "topic:reproducible_scientific_methods",
      "description": "",
      "color": "FBCA04"
    },
    {
      "name": "project_development_status:0_concept_no_content",
      "description": "",
      "color": "D93F0B"
    },
    {
      "name": "git_skills:0_none",
      "description": "",
      "color": "5B6C2C"
    },
    {
      "name": "project_type:method_development",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "modality:EEG",
      "description": "",
      "color": "1d76db"
    },
    {
      "name": "status:web_ready",
      "description": "",
      "color": "0E8A16"
    },
    {
      "name": "modality:behavioral",
      "description": "",
      "color": "1d76db"
    },
    {
      "name": "project_type:data_management",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "tools:Datalad",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "programming:Unix_command_line",
      "description": "",
      "color": "5319E7"
    },
    {
      "name": "hub:montreal_can",
      "description": "",
      "color": "E99695"
    }
  ],
  "content": "### Title \r\n\r\nEnabling subject queries based on longitudinal phenotypic data across datasets\r\n\r\n### Leaders\r\n\r\nSebastian Urchs (@surchs on GitHub/Mattermost)\r\nAlyssa Dai (@alyssaydai on Twitter/GitHub, alyssadai on Mattermost)\r\n\r\n### Collaborators\r\n\r\n_No response_\r\n\r\n### Brainhack Global 2023 Event\r\n\r\nBrainhack Montreal\r\n\r\n### Project Description\r\n\r\n[Neurobagel](https://www.neurobagel.org/) is a tool ecosystem that allows researchers to easily annotate their dataset (both phenotypic and imaging attributes) with standardized terms and provides tools to search for subjects across datasets that have been semantically harmonized.\r\n\r\nFor BrainHack, we have a primary project as well as mini projects available for folks at any level of experience:\r\n\r\n### Primary project: Modeling longitudinal/session-level phenotypic attributes of subjects\r\nFor phenotypic data available in a dataset, Neurobagel currently supports annotation and query of a core set of cross-sectional (subject-level) attributes including age, sex, diagnosis, and cognitive assessment data availability. \r\n\r\nWe want to expand this data model to be able to represent these phenotypic attributes at the _session_ level, with the goal of supporting more sophisticated queries of longitudinal data (e.g., \"I want to find subjects who had Montreal Cognitive Assessment data collected for at least 2 sessions\").\r\n\r\nResources:\r\nTo learn more about the attributes described by our current data model: https://neurobagel.org/dictionaries/\r\nTo see our data model in action: https://github.com/neurobagel/bagel-cli/blob/main/bagel/models.py\r\n\r\n### Mini project 1: Tell us about your needs for sample search and phenotypic data annotation\r\nNeurobagel includes web tools for annotating a dataset (https://annotate.neurobagel.org) subject-level sample search across datasets (https://query.neurobagel.org/). We want to hear about how you are interested in using these tools, specific use cases you may have as someone working with/needing to find samples for studies, replication, etc., and more generally collect challenges data users face that Neurobagel may be able to help with.\r\n\r\nResources:\r\nFor an overview of the current Neurobagel tools and their purposes: https://neurobagel.org/overview/\r\n\r\n### Mini project 2: Try out our tools to help us annotate OpenNeuro datasets!\r\nWe have internally annotated [>340 datasets from OpenNeuro](https://github.com/OpenNeuroDatasets-JSONLD) using our tools, and made them searchable at the subject-level via our web query tool at https://query.neurobagel.org/?node=OpenNeuro. We would like your help in annotating a few of the remaining [OpenNeuroDatasets](https://github.com/OpenNeuroDatasets) using our fully browser-based annotation tool.\r\n\r\nResources:\r\nOur annotation tool: https://annotate.neurobagel.org\r\nTo learn more about the annotation process: https://neurobagel.org/annotation_tool/\r\n\r\n### Link to project repository/sources\r\n\r\nOrganization: https://github.com/neurobagel\r\n\r\nRelevant repos for the project:\r\nhttps://github.com/neurobagel/bagel-cli\r\n\r\n### Goals for Brainhack Global\r\n\r\nSee Project Description!\r\n\r\n### Good first issues\r\n\r\nPlease look for the `good first issue` label (or simply type `is:open label:\"good first issue\"` in the issue filter) in the issue list for any of our repos!\r\n\r\ne.g.,\r\nhttps://github.com/neurobagel/bagel-cli/labels/good%20first%20issue\r\n\r\n### Communication channels\r\n\r\n(To be added)\r\n\r\n### Skills\r\n\r\n### Primary project: Modeling longitudinal/session-level phenotypic attributes of subjects\r\nAny or all of:\r\n- Python\r\n- Bash\r\n- Git/GitHub\r\n- Any knowledge of longitudinal imaging or demographic/clinical data\r\n- BIDS (optional)\r\n\r\n### Mini project 1: Tell us about your needs for sample search and phenotypic data annotation\r\n- Experience working with any neuroimaging dataset, study replication, or phenotypic data wrangling\r\n- **No coding experience required!**\r\n\r\n### \r\nMini project 2: Try out our tools to help us annotate OpenNeuro datasets!\r\n- Experience working with tabular (CSV/TSV) demographic/clinical data\r\n- Nice to have: familiarity with OpenNeuro or BIDS\r\n- **No coding experience required / beginner coders welcome!**\r\n\r\n### Onboarding documentation\r\n\r\n_No response_\r\n\r\n### What will participants learn?\r\n\r\n### Primary project: Modeling longitudinal/session-level phenotypic attributes of subjects\r\n- Python functions\r\n- Data modeling using [Pydantic](https://docs.pydantic.dev/latest/) and classes in Python\r\n- Command-line interfaces in Python\r\n- pyBIDS\r\n- Working with Git repos\r\n\r\n### Mini project 1: Tell us about your needs for sample search and phenotypic data annotation\r\n- Learn about Neurobagel and the world of semantic data harmonization!\r\n\r\n### Mini project 2: Try out our tools to help us annotate OpenNeuro datasets!\r\n- Dataset semantic annotation using Neurobagel\r\n- BIDS\r\n- Working with Git repos\r\n\r\n### Data to use\r\n\r\n_No response_\r\n\r\n### Number of collaborators\r\n\r\n3\r\n\r\n### Credit to collaborators\r\n\r\nWe welcome direct contributions through pull requests, and will eventually employ some organization-level variant of [all-contributors](https://github.com/all-contributors/all-contributors) to credit any contributors on our website: https://neurobagel.org/\r\n\r\n### Image\r\n\r\nLeave this text if you don't have an image yet.\r\n\r\n### Type\r\n\r\ncoding_methods, data_management, method_development\r\n\r\n### Development status\r\n\r\n0_concept_no_content\r\n\r\n### Topic\r\n\r\nreproducible_scientific_methods, other\r\n\r\n### Tools\r\n\r\nBIDS, Datalad\r\n\r\n### Programming language\r\n\r\nPython, unix_command_line, other\r\n\r\n### Modalities\r\n\r\nbehavioral, DWI, EEG, fMRI, MRI, other\r\n\r\n### Git skills\r\n\r\n0_no_git_skills, 1_commit_push, 2_branches_PRs\r\n\r\n### Anything else?\r\n\r\n_No response_\r\n\r\n### Things to do after the project is submitted and ready to review.\r\n\r\n- [ ] Add a comment below the main post of your issue saying: `Hi @brainhackorg/project-monitors my project is ready!`\r\n- [ ] Twitter-sized summary of your project pitch.",
  "project_url": "https://github.com/neurobagelRelevant",
  "project_description": "\r\n\r\n[Neurobagel](https://www.neurobagel.org/) is a tool ecosystem that allows researchers to easily annotate their dataset (both phenotypic and imaging attributes) with standardized terms and provides tools to search for subjects across datasets that have been semantically harmonized.\r\n\r\nFor BrainHack, we have a primary project as well as mini projects available for folks at any level of experience:\r\n\r\n"
}