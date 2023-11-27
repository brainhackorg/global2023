{
  "Title": "behapy: A behavioural neuroscience analysis package for Python",
  "link_to_issue": "https://github.com/brainhackorg/global2023/issues/63",
  "issue_number": 63,
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
      "name": "topic:systems_neuroscience",
      "description": null,
      "color": "ededed"
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
      "name": "project_type:visualisation",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "status:web_ready",
      "description": "",
      "color": "0E8A16"
    },
    {
      "name": "hub:australasia_aus",
      "description": "",
      "color": "FBCA04"
    },
    {
      "name": "modality:behavioral",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "project_type:data_management",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "topic:statistical_modelling",
      "description": null,
      "color": "ededed"
    }
  ],
  "content": "### Title\n\nbehapy: A behavioural neuroscience analysis package for Python\n\n### Leaders\n\nChris Nolan (Mattermost: @cnolan | Mastodon: @cnolan@fediscience.org)\n\n### Collaborators\n\nThomas Burton\r\nKarly Turner\r\nPhil Jean-Richard Dit Bressel\r\nChelsea Goulton\r\nJ Bertran-Gonzalez\r\nLydia Barnes\r\nKelly Garner\n\n### Brainhack Global 2023 Event\n\nBrainhack Australasia\n\n### Project Description\n\nStudies using optic fibres to record real-time fluorescent biosensors in-vivo are now commonplace, yet despite an increasing literature on best practices for analysing such data, there is a surprising lack of fit-for-purpose API-level tooling. This project is a continuing effort to fill this gap by providing flexible Python-based implementations of common normalisation and artefact correction procedures for fluorescent biosensors, along with useful event-based analyses.\r\n\r\nThe goals of this project will extend beyond Brainhack Global 2023, but all are in an effort to create an open-source API and workbench for analysing fibre photometry data in a behavioural neuroscience context. Since Brainhack Global 2022, we have created a basic artefact-rejection workbench, a preprocessing stage and implemented simple linear regression for event-level analysis. This year the goal is to create a method to benchmark normalisation methods by creating data simulation functionality under different assumptions about the sources of recording noise. We are also aiming to outline the steps to including a more comprehensive functional linear mixed effects modelling analysis for event-based analysis, generalise the API to better handle purely behavioural (non-photometry) data, and generally improve the usability of the package.\n\n### Link to project repository/sources\n\nhttps://github.com/crnolan/behapy\n\n### Goals for Brainhack Global\n\n* Create a utility for simulating raw fibre photometry data under a variety of assumptions (for testing the toolkit).\r\n* Add functional linear mixed modelling for event transients analysis (as an alternative to simple linear regression with permutation tests).\r\n* Develop both API-level and tutorial documentation. Docstrings are currently sparse and light on detail, and walkthroughs are virtually non-existent.\r\n* Add import scripts for MedPC datasets, and put together a skeleton framework for event summary and plotting functions.\n\n### Good first issues\n\n1. Check and update installation instructions for behapy package.\r\n2. Document end-user experience for running existing fibre preprocessing workbench on sample data.\r\n3. Establish a configuration format / tool for importing structured MedPC files.\r\n4. Structure the pre-processing interface so as to allow the traces to scale, and interactively compare / select different but reasonable normalisation methods.\n\n### Communication channels\n\nhttps://mattermost.brainhack.org/brainhack/channels/behapy\n\n### Skills\n\nPrimarily, some knowledge of fluorescent biosensor normalisation and analysis procedures will be useful. We'll be predominantly working in Python, but there will be tasks for all levels of Python competency.\r\n\r\nBonus useful skills:\r\n\r\n* Signal processing (we'll be filtering and fitting timeseries data)\r\n* Python interactive visualisation (bokeh / holoviews / panel / seaborn / matplotlib)\r\n* Working knowledge of linear regression and mixed effects models\r\n* BIDS experience - while we won't be attempting to add an official BIDS extension for fibre photometry in this project, we are trying to stay approximately in line with BIDS format\r\n\n\n### Onboarding documentation\n\n_No response_\n\n### What will participants learn?\n\n* Data manipulation in Python (numpy / pandas)\r\n* Signal filtering in Python\r\n* GitHub collaboration techniques\n\n### Data to use\n\nBYO fibre & behavioural data - we'll create a repository of useful examples.\n\n### Number of collaborators\n\nmore\n\n### Credit to collaborators\n\nProject contributors will be listed on the project README.\n\n### Image\n\nLeave this text if you don't have an image yet.\n\n### Type\n\ndata_management, documentation, method_development, pipeline_development, visualization\n\n### Development status\n\n2_releases_existing\n\n### Topic\n\nstatistical_modelling, systems_neuroscience, other\n\n### Tools\n\nBIDS, Jupyter\n\n### Programming language\n\nPython\n\n### Modalities\n\nbehavioral, other\n\n### Git skills\n\n0_no_git_skills, 1_commit_push, 2_branches_PRs\n\n### Anything else?\n\nTopic: behavioural neuroscience\r\nModalities: fibre photometry\n\n### Things to do after the project is submitted and ready to review.\n\n- [x] Add a comment below the main post of your issue saying: `Hi @brainhackorg/project-monitors my project is ready!`\n- [ ] Twitter-sized summary of your project pitch.",
  "project_url": "https://github.com/crnolan/behapy",
  "project_description": "\n\nStudies using optic fibres to record real-time fluorescent biosensors in-vivo are now commonplace, yet despite an increasing literature on best practices for analysing such data, there is a surprising lack of fit-for-purpose API-level tooling. This project is a continuing effort to fill this gap by providing flexible Python-based implementations of common normalisation and artefact correction procedures for fluorescent biosensors, along with useful event-based analyses.\r\n\r\nThe goals of this project will extend beyond Brainhack Global 2023, but all are in an effort to create an open-source API and workbench for analysing fibre photometry data in a behavioural neuroscience context. Since Brainhack Global 2022, we have created a basic artefact-rejection workbench, a preprocessing stage and implemented simple linear regression for event-level analysis. This year the goal is to create a method to benchmark normalisation methods by creating data simulation functionality under different assumptions about the sources of recording noise. We are also aiming to outline the steps to including a more comprehensive functional linear mixed effects modelling analysis for event-based analysis, generalise the API to better handle purely behavioural (non-photometry) data, and generally improve the usability of the package.\n\n"
}