{
  "Title": "PhysioQA",
  "link_to_issue": "https://github.com/brainhackorg/global2023/issues/87",
  "issue_number": 87,
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
      "name": "tools:Jupyter",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "topic:deep_learning",
      "description": "",
      "color": "FBCA04"
    },
    {
      "name": "topic:machine_learning",
      "description": "",
      "color": "FBCA04"
    },
    {
      "name": "topic:physiology",
      "description": "",
      "color": "FBCA04"
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
      "name": "project_development_status:1_basic structure",
      "description": "",
      "color": "D93F0B"
    },
    {
      "name": "project_type:visualisation",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "topic:data_visualisation",
      "description": "",
      "color": "FBCA04"
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
      "name": "programming:Matlab",
      "description": "",
      "color": "5319E7"
    },
    {
      "name": "project_tools_skills:expert",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "hub:vanderbilt_usa",
      "description": "",
      "color": "0E8A16"
    }
  ],
  "content": "### Title\r\n\r\nPhysioQA \r\n\r\n### Leaders\r\n\r\n@RickReddy - Rithwik Guntaka\r\n\r\n### Collaborators\r\n\r\n@rgbayrak - Roza Bayrak\r\n\r\n### Brainhack Global 2023 Event\r\n\r\nBrainHack Vanderbilt\r\n\r\n### Project Description\r\n\r\nWe are working on creating a model that can classify physiological data (respiratory + cardiac) that is associated with fMRI data, so that the end user can determine whether the data is usable, if it needs to be modified to be usable, or if it is simply not usable.\r\n\r\nWhen it comes to using peripheral physiological data in your fMRI data analysis, the quality of the recordings is super important, but let's face it, checking the quality of this data can be a real headache. It usually involves a lot of manual work and you need to know what is real data, what is an artifact. That's why we want to create a nifty deep-learning tool to automate quality assessment! This tool doesn't just check the quality of your data; it also points out any issues and gives you tips on how to fix them. It's like having a friendly expert on your team, making sure your research data is as good as it can be!\r\n\r\n### Link to project repository/sources\r\n\r\nhttps://github.com/brainhack-vandy/projects/blob/main/physioQA.md\r\n\r\n### Goals for Brainhack Global\r\n\r\n- Brainstorm different techniques to increase the classification accuracy of the model\r\n- Modify the MATLAB GUI to be more usable for classifying data\r\n- Potentially, getting data labeled by an expert who is familiar with physiological data\r\n\r\n### Good first issues\r\n\r\nClassification tool (beginner machine learning friendly)\r\n- experimenting with different neural network architectures using keras\r\n- experimenting with feature engineering\r\n- experiment with different hyperparameters for the model\r\n\r\nManual annotation tool\r\n- adding more button functionality to the GUI tool, to allow for more detailed labeling of data\r\n- modify the GUI to select and label certain sections of data\r\n\r\n### Communication channels\r\n\r\n#physioqa channel on https://discord.gg/GyeeVbYC\r\n\r\n### Skills\r\n\r\nHaving any one of these skills would enable an individual to contribute. However, if they have none of these there are onboarding documents that would help them experiment, learn, and contribute regardless.\r\n- Familiarity with Python and Jupyter notebooks\r\n- Familiarity with MATLAB\r\n- Familiarity with physiological data in order to asses its quality\r\n\r\n### Onboarding documentation\r\n\r\n_No response_\r\n\r\n### What will participants learn?\r\n\r\nParticipants will:\r\n- Learn the significance and influence of physiological data in fMRI analysis\r\n- Become familiar with and explore different aspects of ML, and how it can be used for timeseries data\r\n- Learning how to create/modify a GUI to analyze timeseries data using MATLAB toolbox\r\n\r\n### Data to use\r\n\r\nPublic HCP dataset that has physiological data paired with fMRI data.\r\n\r\nhttps://www.humanconnectome.org/study/hcp-young-adult\r\n\r\n### Number of collaborators\r\n\r\n3\r\n\r\n### Credit to collaborators\r\n\r\nCollaborators will be credited on the GitHub site and credited in any paper that results from this project\r\n\r\n### Image\r\n\r\n<img width=\"842\" alt=\"MicrosoftTeams-image (1)\" src=\"https://github.com/brainhackorg/global2023/assets/40832092/29c99dbf-8d4c-4515-bed4-a4cf4b6c5d72\">\r\n\r\n\r\n### Type\r\n\r\nmethod_development, pipeline_development, visualization\r\n\r\n### Development status\r\n\r\n1_basic structure\r\n\r\n### Topic\r\n\r\ndata_visualisation, deep_learning, machine_learning, physiology\r\n\r\n### Tools\r\n\r\nJupyter\r\n\r\n### Programming language\r\n\r\nMatlab, Python\r\n\r\n### Modalities\r\n\r\nfMRI, other\r\n\r\n### Git skills\r\n\r\n0_no_git_skills, 1_commit_push, 2_branches_PRs\r\n\r\n### Anything else?\r\n\r\nother under modalities: physiological data (cardiac + respiration)\r\n\r\n### Things to do after the project is submitted and ready to review.\r\n\r\n- [ ] Add a comment below the main post of your issue saying: `Hi @brainhackorg/project-monitors my project is ready!`\r\n- [ ] Twitter-sized summary of your project pitch.",
  "project_url": "https://github.com/brainhack-vandy/projects/blob/main/physioQA.md",
  "project_description": "\r\n\r\nWe are working on creating a model that can classify physiological data (respiratory + cardiac) that is associated with fMRI data, so that the end user can determine whether the data is usable, if it needs to be modified to be usable, or if it is simply not usable.\r\n\r\nWhen it comes to using peripheral physiological data in your fMRI data analysis, the quality of the recordings is super important, but let's face it, checking the quality of this data can be a real headache. It usually involves a lot of manual work and you need to know what is real data, what is an artifact. That's why we want to create a nifty deep-learning tool to automate quality assessment! This tool doesn't just check the quality of your data; it also points out any issues and gives you tips on how to fix them. It's like having a friendly expert on your team, making sure your research data is as good as it can be!\r\n\r\n"
}