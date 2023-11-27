{
  "Title": "Launchcontainers:  A Python tool for launching containerized analysis on HPC",
  "link_to_issue": "https://github.com/brainhackorg/global2023/issues/44",
  "issue_number": 44,
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
      "color": "20CF02"
    },
    {
      "name": "modality:fMRI",
      "description": "",
      "color": "20CF02"
    },
    {
      "name": "modality:MRI",
      "description": "",
      "color": "20CF02"
    },
    {
      "name": "programming:documentation",
      "description": "",
      "color": "347C53"
    },
    {
      "name": "programming:Python",
      "description": "",
      "color": "347C53"
    },
    {
      "name": "project_development_status:2_releases_existing",
      "description": null,
      "color": "ededed"
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
      "name": "hub:donostia_esp",
      "description": "",
      "color": "FBCA04"
    }
  ],
  "content": "### Title\r\n\r\nLaunchcontainers: A Python tool for launching containerized analysis on HPC \r\n\r\n\r\n### Leaders\r\n\r\nYongning Lei\r\n\r\nemail: t.lei@bcbl.eu\r\n\r\n### Collaborators\r\n\r\n_No response_\r\n\r\n### Brainhack Global 2023 Event\r\n\r\nBrainhack Donostia\r\n\r\n### Project Description\r\n\r\nLaunchcontainers is a Python-based program built to automatically launch containerlized MRI processing pipelines. This program takes one config.ymal file, one container.json file, and one subject-session-list.txt file as inputs. Using 1 line of bash command, it will automatically send jobs to HPC clusters regarding your computing demands.\r\n\r\nThis program is well-suited for multi-subject, multi-scan datasets. And it will save a lot of time if you need analysis your entire dataset with different parameters multiple times.\r\n\r\nIn future versions, we are trying to add more functionality to this repository so that you can launch all the MRI data analysis pipelines such as Heudiconv, fMRIprep, pRF pipelines and etc. Please keep track of this repo and if you have any questions or suggestions, don't hesitate to contact Gari: [garikoitz@gmail.com](mailto:garikoitz@gmail.com) and Tiger: [t.lei@bcbl.eu](mailto:yongninglei@gmail.com)\r\n\r\n\r\n### Link to project repository/sources\r\n\r\nhttps://github.com/garikoitz/launchcontainers\r\n\r\n### Goals for Brainhack Global\r\n\r\n- Let more people get to know the advantages of using containers to process MRI data to improve the data availability and reproducibility\r\n- Let beginner level users get familiar with the UNIX operation and git operation\r\n- Add new features to launchcontainer so that it supports more MRI processing pipeline (ie. HeuDiconv, fMRIprep, PRF-analyze)\r\n- Make a better documentation on the project Wiki\r\n\r\n### Good first issues\r\n\r\n1. issue one:\r\nhttps://github.com/garikoitz/launchcontainers/issues/28\r\n2. issue two:\r\nhttps://github.com/garikoitz/launchcontainers/issues/32\r\n\r\n### Communication channels\r\n\r\nhttps://mattermost.bcbl.eu/bhdonostia/channels/launchcontainer\r\n\r\n### Skills\r\n\r\n- Python intermediate\r\n- Unix intermediate\r\n\r\n\r\n\r\n### Onboarding documentation\r\n\r\nhttps://docs.google.com/document/d/1XMmMpp3w7i2o8wVyHv_kUgoTgYVJ7n-qvgIQilfEBEU/edit?usp=sharing\r\n\r\n### What will participants learn?\r\n\r\n- How to use Unix to run python script, navigate to directory, and edit files.\r\n- How to use git to collaborate with other's, create branch to fix issues, pull-request\r\n- How to use launchcontainers to launch DWI pipeline on SGE, SLURM and local machine\r\n\r\n\r\n### Data to use\r\n\r\nI will prepare the converted nifti DWI scan folder in BIDS format and zipped it for use\r\n\r\n### Number of collaborators\r\n\r\n3\r\n\r\n### Credit to collaborators\r\n\r\nProject contributers will be listed in the launchcontainer repo\r\n\r\n### Image\r\n\r\n![Launchcontainer logo](https://github.com/brainhackorg/global2023/assets/48440236/776ecfbb-f775-4942-b1cf-77cf89add43a)\r\n\r\n### Type\r\n\r\ndocumentation coding_methods\r\n\r\n### Development status\r\n\r\n2_releases_existing\r\n\r\n### Topic\r\n\r\nreproducible_scientific_methods\r\n\r\n### Tools\r\n\r\nBIDS\r\n\r\n### Programming language\r\n\r\nPython\r\n\r\n### Modalities\r\n\r\nDWI\r\n\r\n### Git skills\r\n\r\n1_commit_push, 2_branches_PRs\r\n\r\n### Anything else?\r\n\r\n_No response_\r\n\r\n### Things to do after the project is submitted and ready to review.\r\n\r\n- [X] Add a comment below the main post of your issue saying: `Hi @brainhackorg/project-monitors my project is ready!`\r\n- [x] Twitter-sized summary of your project pitch.",
  "project_url": "https://github.com/garikoitz/launchcontainers",
  "project_description": "\r\n\r\nLaunchcontainers is a Python-based program built to automatically launch containerlized MRI processing pipelines. This program takes one config.ymal file, one container.json file, and one subject-session-list.txt file as inputs. Using 1 line of bash command, it will automatically send jobs to HPC clusters regarding your computing demands.\r\n\r\nThis program is well-suited for multi-subject, multi-scan datasets. And it will save a lot of time if you need analysis your entire dataset with different parameters multiple times.\r\n\r\nIn future versions, we are trying to add more functionality to this repository so that you can launch all the MRI data analysis pipelines such as Heudiconv, fMRIprep, pRF pipelines and etc. Please keep track of this repo and if you have any questions or suggestions, don't hesitate to contact Gari: [garikoitz@gmail.com](mailto:garikoitz@gmail.com) and Tiger: [t.lei@bcbl.eu](mailto:yongninglei@gmail.com)\r\n\r\n\r\n"
}