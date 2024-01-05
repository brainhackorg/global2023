{
  "Title": "The TAPAS PhysIO Toolbox for Physiological Noise Modeling in fMRI",
  "link_to_issue": "https://github.com/brainhackorg/global2023/issues/71",
  "issue_number": 71,
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
      "name": "topic:physiology",
      "description": "",
      "color": "FBCA04"
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
      "name": "status:web_ready",
      "description": "",
      "color": "0E8A16"
    },
    {
      "name": "topic:statistical_modelling",
      "description": "",
      "color": "FBCA04"
    },
    {
      "name": "tools:SPM",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "modality:ECG",
      "description": "",
      "color": "1d76db"
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
      "name": "topic:MR_methodologies",
      "description": "",
      "color": "FBCA04"
    }
  ],
  "content": "### Title\n\nThe TAPAS PhysIO Toolbox for Physiological Noise Modeling in fMRI\n\n### Leaders\n\n- Lars Kasper @mrikasper\r\n- Johanna Bayer @likeajumprope \n\n### Collaborators\n\n- Joram Soch @JoramSoch (for MACS integration)\n\n### Brainhack Global 2023 Event\n\nBrainHack Toronto\n\n### Project Description\n\n_TL;DR: Watch the videos on [PhysIO](https://www.youtube.com/watch?v=rdsk2yhxEVM) and [MACS](https://www.youtube.com/watch?v=yuPiGfqVjCQ&t=6s) to learn about these 2 toolboxes that we are trying to integrate and make more accessible in this Hackathon._\r\n\r\nThe PhysIO Toolbox offers model-based physiological noise correction for functional MRI (fMRI) data, based on peripheral physiological recordings, such as cardiac and respiratory traces (ECG, pulse oximeter, breathing belt). Major noise models, such as RETROICOR, respiratory volume per time (RVT) or heart-rate variability (HRV) modulations of BOLD are supported.\r\n\r\nPhysIO is written in Matlab, but also offered as standalone version via a containerized solution ([Neurodesk](https://www.neurodesk.org/tutorials-examples/tutorials/functional_imaging/physio/)) or web-based processing interface ([CBRAIN](https://cbrain.ca/)). Through its integration as a toolbox in SPM, it both offers interactive operation via the Batch Editor GUI, as well as batch execution within fMRI preprocessing pipelines.\r\n\r\nThrough its more than 10 years of development as part of the Translational Algorithms for Psychiatry-Advancing Science (TAPAS) Software Package, PhysIO has seen many improvements and new releases, but user requests for new features always outnumber our core developer capacity.\r\n\r\nIn this Brainhack, we would like to add two of the most highly-desired features to PhysIO:\r\n\r\n1. Finding the best physiological noise model for your data using [MACS](https://github.com/JoramSoch/MACS)\r\n2. Creating an interactive tutorial of PhysIO in action using Matlab Online and open datasets, for example based on this [prototype code](https://github.com/likeajumprope/PhysIO-Live)\r\n\r\nIf you want to start small, there is also a [user wish list](https://github.com/users/likeajumprope/projects/2/views/2) of changes to the interface and documentation that we would be happy to see implemented.\r\n\n\n### Link to project repository/sources\n\n- Main TAPAS PhysIO Repository: https://github.com/translationalneuromodeling/tapas/\r\n- Main MACS Repository: https://github.com/JoramSoch/MACS\r\n- Current PhysIO Live Demo Prototype: https://github.com/likeajumprope/PhysIO-Live\r\n- Project board of current user (small) wish list: https://github.com/users/likeajumprope/projects/2/views/2\n\n### Goals for Brainhack Global\n\nAll of the following goals are equally worthwhile. We will base our prioritization on user interest and expertise:\r\n\r\n1. [ ] Model Selection of the best Physiological noise model for your data (tracked in [this issue](https://github.com/users/likeajumprope/projects/2/views/2?pane=issue&itemId=7286685))\r\n\r\n- With the large variety of physiological noise models and parameters offered by PhysIO, a [common question](https://gitlab.ethz.ch/physio/physio-doc/-/wikis/FAQ#17-which-models-do-i-have-to-include-in-my-physiological-regressor-matrix-and-which-number-of-regressors-model-order-delays-per-model) for users is which model is right for their data. \r\n- Overly simplistic models might not remove noise effectively, overly complex models, on the other hand, might reduce your sensitivity to detect fMRI activation by removing degrees of freedom in your task model or signal correlated to your task. \r\n- Bayesian model selection is a formal way to compare different modeling choices and select the best model for your data.\r\n- MACS (Model Assessment, Comparison and Selection) is an SPM toolbox offering Bayesian Model Selection for the general linear models (GLMs) used in fMRI analysis.\r\n- In this milestone, we want to complete the following:\r\n    - [x] Identify a suitable multi-subject open fMRI dataset (e.g., on OpenNeuro) with peripheral recordings\r\n    - [x] Run different physiological noise models (GLMs) on multiple subjects\r\n    - [ ] Assess the GLMs for single subjects and the group via MACS\r\n    - [ ] Perform model comparison for a couple of typical models (RETROICOR different orders, plus RVT, plus HRV, different delays RVT/HRV delays)\r\n    - [ ] Write a programmatic interface within PhysIO to call MACS for model assessment/selection\r\n    - [ ] Write a batch editor interface for PhysIO model assessment using MACS\r\n\r\n2. [ ] Interactive Online Tutorial of the PhysIO pipeline with openly available fMRI data (tracked in [this issue](https://github.com/users/likeajumprope/projects/2/views/2?pane=issue&itemId=7286753))\r\n\r\n- We have created a [prototype of this effort](https://github.com/likeajumprope/PhysIO-Live) using \"Matlab Online\". \r\n- There are some barriers to make it a great user experience for your first contact with the PhysIO Toolbox, in particular\r\n    - [ ] the slow initialization because of downloading git submodules from GitHub (including SPM)\r\n    - [ ] the choice of appropriate (good physiological recordings) and small open fMRI datasets, e.g., from [OpenNeuro](https://openneuro.org/search/modality/mri?query=%7B%22modality_selected%22%3A%22MRI%22%7D)\r\n\r\n3. [ ] Fulfilling some PhysIO users' long-standing small, but impactful feature requests from the [wish list](https://github.com/users/likeajumprope/projects/2/views/2), such as\r\n    - [ ] A consistent interface for multiband fMRI data ([this issue](https://github.com/users/likeajumprope/projects/2/views/2?pane=issue&itemId=7286640))\r\n    - [ ] A direct read-in of BIDS scan timing data from `.json` sidecar files, similar to the [CBRAIN](https://doi.org/10.3389/fninf.2023.1251023) implementation\r\n    - [ ] Exporting preprocessed physiological traces and derived measures (heart-rate variability, respiratory volume per time) at base resolution before physiological modeling ([this issue](https://github.com/users/likeajumprope/projects/2/views/2?pane=issue&itemId=7611107))\n\n### Good first issues\n\n - [ ] A consistent interface for multiband fMRI data ([this issue](https://github.com/users/likeajumprope/projects/2/views/2?pane=issue&itemId=7286640)) and this [possible solution](https://github.com/translationalneuromodeling/tapas/issues/236)\r\n - [x]  the choice of an appropriate (good physiological recordings) and small open fMRI dataset for the PhysIO-Live Demo (single subject) and the Model Selection goal, e.g., from [OpenNeuro](https://openneuro.org/search/modality/mri?query=%7B%22modality_selected%22%3A%22MRI%22%7D)\n\n### Communication channels\n\nhttps://mattermost.brainhack.org/brainhack/channels/physio\n\n### Skills\n\n- Matlab: basic (running scripts, navigating the Matlab environment) to advanced (unit testing)\r\n- SPM: none to advanced (Navigating the SPM Results and CheckReg Tools, Batch Editor Programming, Setting up multiple processing pipelines)\r\n- Functional MRI Analysis: basic (GLM) to advanced (Model Comparison, Model Evidence, Bayes factor)\r\n- Open Data Standards/Repositories: BIDS and OpenNeuro\n\n### Onboarding documentation\n\n- PhysIO [README](https://github.com/translationalneuromodeling/tapas/tree/master/PhysIO#readme)\r\n- PhysIO [FAQ](https://gitlab.ethz.ch/physio/physio-doc/-/wikis/FAQ)\r\n- PhysIO [Video](https://www.youtube.com/watch?v=rdsk2yhxEVM)\r\n- MACS [Video](https://www.youtube.com/watch?v=yuPiGfqVjCQ&t=6s)\r\n- TAPAS [CONTRIBUTING](https://github.com/translationalneuromodeling/tapas/blob/master/CONTRIBUTING.md)\n\n### What will participants learn?\n\n- Basics of physiological noise correction in fMRI (RETROICOR, RVT, HRV)\r\n- Basics of model comparison/model selection\r\n- Using PhysIO as a Matlab script, in a GUI, at the Batch Editor Level with SPM\r\n- Using Matlab Online with open-source code and data repositories\n\n### Data to use\n\nTBD (it's one of the tasks)\n\n### Number of collaborators\n\n4\n\n### Credit to collaborators\n\nAs outlined in our TAPAS [CONTRIBUTING](https://github.com/translationalneuromodeling/tapas/blob/master/CONTRIBUTING.md) document, new members shall add themselves to the [Contributor License Agreement](https://github.com/translationalneuromodeling/tapas/blob/master/Contributor-License-Agreement.md) alongside their first pull request contribution to the TAPAS PhysIO Code. This document is also referenced in the PhysIO [README](https://github.com/translationalneuromodeling/tapas/tree/master/PhysIO#readme).\n\n### Image\n\n![AvatarPhysIO](https://github.com/brainhackorg/global2023/assets/13321311/27447c25-63cd-4ab2-9b4e-f14d8adb5b6d)\r\n\n\n### Type\n\ndocumentation, method_development, pipeline_development, visualization\n\n### Development status\n\n1_basic structure\n\n### Topic\n\nbayesian_approaches, data_visualisation, MR_methodologies, physiology, statistical_modelling\n\n### Tools\n\nBIDS, SPM\n\n### Programming language\n\ndocumentation, Matlab\n\n### Modalities\n\nfMRI\n\n### Git skills\n\n1_commit_push\n\n### Anything else?\n\nWe aim at making the project development environment available via Matlab Online or standalone (browser- or container-based, no license required), but if there is specific expertise, we could also aim at full Octave-compatibility of the toolbox.\n\n### Things to do after the project is submitted and ready to review.\n\n- [x] Add a comment below the main post of your issue saying: `Hi @brainhackorg/project-monitors my project is ready!`\n- [x] Twitter-sized summary of your project pitch.",
  "project_url": "https://github.com/translationalneuromodeling/tapas/-",
  "project_description": "\n\n_TL;DR: Watch the videos on [PhysIO](https://www.youtube.com/watch?v=rdsk2yhxEVM) and [MACS](https://www.youtube.com/watch?v=yuPiGfqVjCQ&t=6s) to learn about these 2 toolboxes that we are trying to integrate and make more accessible in this Hackathon._\r\n\r\nThe PhysIO Toolbox offers model-based physiological noise correction for functional MRI (fMRI) data, based on peripheral physiological recordings, such as cardiac and respiratory traces (ECG, pulse oximeter, breathing belt). Major noise models, such as RETROICOR, respiratory volume per time (RVT) or heart-rate variability (HRV) modulations of BOLD are supported.\r\n\r\nPhysIO is written in Matlab, but also offered as standalone version via a containerized solution ([Neurodesk](https://www.neurodesk.org/tutorials-examples/tutorials/functional_imaging/physio/)) or web-based processing interface ([CBRAIN](https://cbrain.ca/)). Through its integration as a toolbox in SPM, it both offers interactive operation via the Batch Editor GUI, as well as batch execution within fMRI preprocessing pipelines.\r\n\r\nThrough its more than 10 years of development as part of the Translational Algorithms for Psychiatry-Advancing Science (TAPAS) Software Package, PhysIO has seen many improvements and new releases, but user requests for new features always outnumber our core developer capacity.\r\n\r\nIn this Brainhack, we would like to add two of the most highly-desired features to PhysIO:\r\n\r\n1. Finding the best physiological noise model for your data using [MACS](https://github.com/JoramSoch/MACS)\r\n2. Creating an interactive tutorial of PhysIO in action using Matlab Online and open datasets, for example based on this [prototype code](https://github.com/likeajumprope/PhysIO-Live)\r\n\r\nIf you want to start small, there is also a [user wish list](https://github.com/users/likeajumprope/projects/2/views/2) of changes to the interface and documentation that we would be happy to see implemented.\r\n\n\n"
}