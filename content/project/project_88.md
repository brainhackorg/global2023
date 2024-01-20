{
  "Title": "Deriving Resting State Networks and Observing their Behavior Across Age",
  "link_to_issue": "https://github.com/brainhackorg/global2023/issues/88",
  "issue_number": 88,
  "labels": [
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
      "name": "topic:ICA",
      "description": "",
      "color": "FBCA04"
    },
    {
      "name": "status:web_ready",
      "description": "",
      "color": "0E8A16"
    },
    {
      "name": "tools:AFNI",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "tools:FSL",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "programming:Matlab",
      "description": "",
      "color": "5319E7"
    },
    {
      "name": "topic:MR_methodologies",
      "description": "",
      "color": "FBCA04"
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
  "content": "### Title\r\n\r\nDeriving Resting State Networks and Observing their Behavior Across Age\r\n\r\n### Leaders\r\n\r\nKimberly Rogge-Obando \r\n\r\n### Collaborators\r\n\r\nTerra Lee\r\n\r\n### Brainhack Global 2023 Event\r\n\r\nBrainHack Vanderbilt\r\n\r\n### Project Description\r\n\r\nSince their discovery, resting state networks have elucidated our understanding of cognitive function such as emotion processing, working memory, and daydreaming. Additionally, a collective of scientists believe resting state networks may be a possible biomarker of mental disorders. However, before we can confirm resting state networks point to a characteristic of mental disorders it is important to model how they change across age. Many studies have identified that age does influence the connectivity of resting state networks however which brain regions within resting state networks change specifically needs to be further understood. The goal of this project is to compare methods of how resting state network information are retrieved and potentially model how they change across age. Anyone is welcome to join and will have the opportunity to learn common practices to derive resting state networks. Individuals are asked to have FSL and Matlab on their computers, but this is not a requirement to join however it may limit their contribution.  \r\n\r\n### Link to project repository/sources\r\n\r\nhttps://drive.google.com/drive/folders/1Gd0Ra4BYukWS39978vVewpwzNDBOE7km?usp=sharing\r\n\r\n### Goals for Brainhack Global\r\n\r\nGoal 1 : Determine if dual regression on matlab gives similar results of FSL dual regression. Level of difficulty 1-2\r\n\r\nTasks to complete goal 1\r\n- [ ] Run ICA Melodic on 1 subjects with 10 components and label the networks , may test component numbers\r\n- [ ] Use current ICA Melodic values and run dual regression on FSL, with one subject\r\n- [ ] Use current ICA Melodic output to run dual regression on MATLAB, save time series and spatial maps with one subject\r\n- [ ] Compare Dual Regression timeseries in FSL and MATLAB, generate figures of comparison and correlation\r\n\r\nGoal 2: Determine how resting state networks change across age. Level of difficulty 3\r\n\r\nTasks to complete goal 2\r\n- [ ] Run dual regression with fslrandomise  option and fslrandomise  separately with age and gender as a covariate and see how these options replicate. Write up the steps for this project.\r\n\r\n\r\n### Good first issues\r\n\r\n1. Download FSL onto your computer and look into FSL melodic and dual_regression\r\nhttps://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FslInstallation\r\n\r\n2. Download Afni on your computer\r\nhttps://afni.nimh.nih.gov/pub/dist/doc/htmldoc/background_install/install_instructs/index.html\r\n\r\n\r\n\r\n### Communication channels\r\n\r\n#rage channel on https://discord.gg/5vy8fTWQ\r\n\r\n### Skills\r\n\r\nNeuroimaging-Beginner\r\nMATLAB-Begninner\r\nFSL-Begninner- Intermediate\r\n\r\nWillingness to contribute to science communication part of the project, creating power point slides etc.\r\n\r\n### Onboarding documentation\r\n\r\n(https://drive.google.com/drive/folders/1Gd0Ra4BYukWS39978vVewpwzNDBOE7km?usp=sharing)\r\n\r\n\r\n### What will participants learn?\r\n\r\nThis project is perfect for beginners in fMRI resting state network analysis. \r\n\r\nThings participants will learn.\r\n\r\n-How to conduct Melodic ICA and eyeball resting state networks\r\n-Derive subject specific resting state network spatial maps and time series\r\n-Use FSL randomise and dual_regression code \r\n-Will learn how to use fsl randomise with co-variates that may transfer over to them investigating resting state networks across age or other variables of interest\r\n-Gain critical skills in team collaboration\r\n\r\n\r\n### Data to use\r\n\r\nWe will use a subset of the NKI -Rockland Sample dataset .\r\n\r\nhttps://fcon_1000.projects.nitrc.org/indi/enhanced/\r\n\r\nNooner et al, (2012). [The NKI-Rockland Sample: A model for accelerating the pace of discovery science in psychiatry.](http://www.ncbi.nlm.nih.gov/pubmed/23087608) Frontiers in neuroscience 6, 152.\r\n\r\n\r\n### Number of collaborators\r\n\r\n4\r\n\r\n### Credit to collaborators\r\n\r\nMembers of this team names will be listed on the code we upload to GitHub. They will also have the opportunity to join our formal NKI-rockland team as were in the process of finishing up a side project that is partially relevant to this project. \r\n\r\n### Image\r\n\r\nLeave this text if you don't have an image yet.\r\n![BrainHack2024Image](https://github.com/brainhackorg/global2023/assets/73260292/29565a4e-65d3-429b-8f76-004cd3d11482)\r\n\r\n\r\n### Type\r\n\r\ncoding_methods\r\n\r\n### Development status\r\n\r\n0_concept_no_content\r\n\r\n### Topic\r\n\r\nMR_methodologies\r\n\r\n### Tools\r\n\r\nAFNI, FSL\r\n\r\n### Programming language\r\n\r\nMatlab, shell_scripting\r\n\r\n### Modalities\r\n\r\nfMRI\r\n\r\n### Git skills\r\n\r\n0_no_git_skills\r\n\r\n### Anything else?\r\n\r\nThis will be a perfect opportunity for beginners using fMRI data! Look forward to meeting you!\r\n\r\n### Things to do after the project is submitted and ready to review.\r\n\r\n- [ ] Add a comment below the main post of your issue saying: `Hi @brainhackorg/project-monitors my project is ready!`\r\n- [ ] Twitter-sized summary of your project pitch.",
  "project_url": "https://drive.google.com/drive/folders/1Gd0Ra4BYukWS39978vVewpwzNDBOE7km?usp=sharing",
  "project_description": "\r\n\r\nSince their discovery, resting state networks have elucidated our understanding of cognitive function such as emotion processing, working memory, and daydreaming. Additionally, a collective of scientists believe resting state networks may be a possible biomarker of mental disorders. However, before we can confirm resting state networks point to a characteristic of mental disorders it is important to model how they change across age. Many studies have identified that age does influence the connectivity of resting state networks however which brain regions within resting state networks change specifically needs to be further understood. The goal of this project is to compare methods of how resting state network information are retrieved and potentially model how they change across age. Anyone is welcome to join and will have the opportunity to learn common practices to derive resting state networks. Individuals are asked to have FSL and Matlab on their computers, but this is not a requirement to join however it may limit their contribution.  \r\n\r\n"
}