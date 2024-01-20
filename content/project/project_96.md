{
  "Title": "fMRI-EEG Preprocessing QA",
  "link_to_issue": "https://github.com/brainhackorg/global2023/issues/96",
  "issue_number": 96,
  "labels": [
    {
      "name": "git_skills:1_commit_push",
      "description": "",
      "color": "5B6C2C"
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
      "name": "project_type:documentation",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "project_type:pipeline_development",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "git_skills:0_none",
      "description": "",
      "color": "5B6C2C"
    },
    {
      "name": "project_development_status:1_basic structure",
      "description": "",
      "color": "D93F0B"
    },
    {
      "name": "modality:EEG",
      "description": "",
      "color": "1d76db"
    },
    {
      "name": "tools:Brainstorm",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "topic:connectome",
      "description": "",
      "color": "FBCA04"
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
      "name": "tools:FSL",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "tools:SPM",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "programming:Matlab",
      "description": "",
      "color": "5319E7"
    },
    {
      "name": "programming:Unix_command_line",
      "description": "",
      "color": "5319E7"
    },
    {
      "name": "programming:shell_scripting",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "hub:vanderbilt_usa",
      "description": "",
      "color": "0E8A16"
    }
  ],
  "content": "### Title\r\n\r\nfMRI-EEG Preprocessing QA\r\n\r\n### Leaders\r\n\r\n@s_goodale23 - Sarah Goodale \r\n\r\n### Collaborators\r\n\r\n_No response_\r\n\r\n### Brainhack Global 2023 Event\r\n\r\nBrainHack Vanderbilt\r\n\r\n### Project Description\r\n\r\nWe are working on developing a QA pipeline for simultaneously collected fMRI-EEG data so that the user can determine whether the data is denoised and clean enough for further analyses. \r\n\r\nPreprocessing is a critical step in neuroimaging analysis, laying the foundation for accurate and meaningful scientific discoveries. We need help configuring a pipeline to quality check for multiple datasets. This project will allow attendees with or without experience handling fMRI/EEG data to get a chance to work with what we call the \"raw data\". Working on a QC pipeline includes devising visuals of what the data looks like at various stages to make sure that the preprocessing is working as you expected and the data collected is good quality for future analyses. Toolboxes used include AFNI, FSL, ANTs, chronux, etc. \r\n\r\n\r\n### Link to project repository/sources\r\n\r\nhttps://github.com/goodalse2019/fMRI-EEG_preproc_QA_VUBrainHack\r\n\r\n### Goals for Brainhack Global\r\n\r\n- Brainstorm different QA checks that will best represent what we are looking for in the data\r\n- Learn more about the importance of various QA in fMRI and EEG data and how to best interpret our data\r\n- Code an automatic pipeline to implement our QA checks and outputs an html or pdf of the figures/results\r\n\r\n### Good first issues\r\n\r\n1. issue one: organizing and deciding on best QA for both fMRI and EEG modalities \r\n2. issue two: experimenting with toolboxes to get various plots or figures for the QA step of interest \r\n3. issue three: develop an outline of a script that will output a clean, clear, and easy to use pdf or html of QA figures\r\n\r\n\r\n### Communication channels\r\n\r\n#fmri-eeg-preproc channel on BrainHack Vanderbilt Discord\r\n\r\n### Skills\r\n\r\nFamiliarity in working with fMRI and/or EEG data will help but is not necessary to join the project!\r\n- FSL: basics\r\n- AFNI: basics\r\n- MATLAB: basics\r\n- bash: basics\r\n\r\n### Onboarding documentation\r\n\r\n_No response_\r\n\r\n### What will participants learn?\r\n\r\nParticipants will:\r\n\r\n- Learn how to read and interact with fMRI and EEG data from the raw unprocessed stage to the final analysis ready data\r\n- Enhance their understanding of the most helpful toolboxes associated with neuroimaging and gain a foundational knowledge in using and implementing command line versions of their functions\r\n- Learn how to develop and implement a pre-processing pipeline for both datatypes in MATLAB and/or bash\r\n\r\n### Data to use\r\n\r\nPublic HCP dataset for deidentified fMRI data (https://www.humanconnectome.org/study/hcp-young-adult).\r\n\r\nPreviously collected and deidentified EEG data from a home collected data where pieces have been made publicly available on https://github.com/neurdylab/fMRIAlertnessDetection. \r\n\r\n### Number of collaborators\r\n\r\n3\r\n\r\n### Credit to collaborators\r\n\r\nCollaborators will be credited on the GitHub site documentation for any users who are interested in downloading and using this project's QA pipeline. \r\n\r\n### Image\r\n\r\nLeave this text if you don't have an image yet.\r\n\r\n### Type\r\n\r\npipeline_development, visualization\r\n\r\n### Development status\r\n\r\n1_basic structure\r\n\r\n### Topic\r\n\r\nother\r\n\r\n### Tools\r\n\r\nAFNI, ANTs, FSL, SPM, other\r\n\r\n### Programming language\r\n\r\nMatlab, Python, shell_scripting, unix_command_line\r\n\r\n### Modalities\r\n\r\nEEG, fMRI\r\n\r\n### Git skills\r\n\r\n0_no_git_skills, 1_commit_push\r\n\r\n### Anything else?\r\n\r\nother under topic: pre-processing, quality analysis \r\n\r\n### Things to do after the project is submitted and ready to review.\r\n\r\n- [x] Add a comment below the main post of your issue saying: `Hi @brainhackorg/project-monitors my project is ready!`\r\n- [ ] Twitter-sized summary of your project pitch.",
  "project_url": "https://github.com/goodalse2019/fMRI-EEG_preproc_QA_VUBrainHack",
  "project_description": "\r\n\r\nWe are working on developing a QA pipeline for simultaneously collected fMRI-EEG data so that the user can determine whether the data is denoised and clean enough for further analyses. \r\n\r\nPreprocessing is a critical step in neuroimaging analysis, laying the foundation for accurate and meaningful scientific discoveries. We need help configuring a pipeline to quality check for multiple datasets. This project will allow attendees with or without experience handling fMRI/EEG data to get a chance to work with what we call the \"raw data\". Working on a QC pipeline includes devising visuals of what the data looks like at various stages to make sure that the preprocessing is working as you expected and the data collected is good quality for future analyses. Toolboxes used include AFNI, FSL, ANTs, chronux, etc. \r\n\r\n\r\n"
}