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
    }
  ],
  "content": "### Title\n\nPhysioQA\n\n### Leaders\n\n@RickReddy - Rithwik Guntaka\n\n### Collaborators\n\n@rgbayrak - Roza Bayrak\n\n### Brainhack Global 2023 Event\n\nBrainHack Vanderbilt\n\n### Project Description\n\nWe are working on creating a model that can classify physiological data (respiratory + cardiac) that is associated with fMRI data, so that the end user can determine whether the data is usable, if it needs to be modified to be usable, or if it is simply not usable.\r\n\r\nWhen it comes to using peripheral physiological data in your fMRI data analysis, the quality of the recordings is super important, but let's face it, checking the quality of this data can be a real headache. It usually involves a lot of manual work and you need to know what is real data, what is an artifact. That's why we want to create a nifty deep-learning tool to automate quality assessment! This tool doesn't just check the quality of your data; it also points out any issues and gives you tips on how to fix them. It's like having a friendly expert on your team, making sure your research data is as good as it can be!\n\n### Link to project repository/sources\n\nhttps://github.com/brainhack-vandy/projects/physioQA\n\n### Goals for Brainhack Global\n\n- Brainstorm different techniques to increase the classification accuracy of the model\r\n- Modify the MATLAB GUI to be more usable for classifying data\r\n- Potentially, getting data labeled by an expert who is familiar with physiological data\n\n### Good first issues\n\nClassification tool (beginner machine learning friendly)\r\n- experimenting with different neural network architectures using keras\r\n- experimenting with feature engineering\r\n- experiment with different hyperparameters for the model\r\nManual annotation tool\r\n- adding more button functionality to the GUI tool, to allow for more detailed labeling of data\r\n- modify the GUI to select and label certain sections of data\n\n### Communication channels\n\n#physioqa channel on https://discord.gg/GyeeVbYC\n\n### Skills\n\nHaving any one of these skills would enable an individual to contribute. However, if they have none of these there are onboarding documents that would help them experiment, learn, and contribute regardless.\r\n- Familiarity with Python and Jupyter notebooks\r\n- Familiarity with MATLAB\r\n- Familiarity with physiological data in order to asses its quality\n\n### Onboarding documentation\n\n_No response_\n\n### What will participants learn?\n\nParticipants will:\r\n- Learn the significance and influence of physiological data in fMRI analysis\r\n- Become familiar with and explore different aspects of ML, and how it can be used for timeseries data\r\n- Learning how to create/modify a GUI to analyze timeseries data using MATLAB toolbox\n\n### Data to use\n\nPublic HCP dataset that has physiological data paired with fMRI data.\r\n\r\nhttps://www.humanconnectome.org/study/hcp-young-adult\n\n### Number of collaborators\n\n3\n\n### Credit to collaborators\n\nCollaborators will be credited on the GitHub site and credited in any paper that results from this project\n\n### Image\n\n<img width=\"842\" alt=\"MicrosoftTeams-image (1)\" src=\"https://github.com/brainhackorg/global2023/assets/40832092/29c99dbf-8d4c-4515-bed4-a4cf4b6c5d72\">\r\n\n\n### Type\n\nmethod_development, pipeline_development, visualization\n\n### Development status\n\n1_basic structure\n\n### Topic\n\ndata_visualisation, deep_learning, machine_learning, physiology\n\n### Tools\n\nJupyter\n\n### Programming language\n\nMatlab, Python\n\n### Modalities\n\nfMRI, other\n\n### Git skills\n\n0_no_git_skills, 1_commit_push, 2_branches_PRs\n\n### Anything else?\n\nother under modalities: physiological data (cardiac + respiration)\n\n### Things to do after the project is submitted and ready to review.\n\n- [ ] Add a comment below the main post of your issue saying: `Hi @brainhackorg/project-monitors my project is ready!`\n- [ ] Twitter-sized summary of your project pitch.",
  "project_url": "https://github.com/brainhack-vandy/projects/physioQA",
  "project_description": "\n\nWe are working on creating a model that can classify physiological data (respiratory + cardiac) that is associated with fMRI data, so that the end user can determine whether the data is usable, if it needs to be modified to be usable, or if it is simply not usable.\r\n\r\nWhen it comes to using peripheral physiological data in your fMRI data analysis, the quality of the recordings is super important, but let's face it, checking the quality of this data can be a real headache. It usually involves a lot of manual work and you need to know what is real data, what is an artifact. That's why we want to create a nifty deep-learning tool to automate quality assessment! This tool doesn't just check the quality of your data; it also points out any issues and gives you tips on how to fix them. It's like having a friendly expert on your team, making sure your research data is as good as it can be!\n\n"
}