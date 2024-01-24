{
  "Title": "phys2CVR: a BIDS-compliant python toolbox to compute cerebrovascular reacitvity mapping",
  "link_to_issue": "https://github.com/brainhackorg/global2023/issues/33",
  "issue_number": 33,
  "labels": [
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
      "name": "project_development_status:2_releases_existing",
      "description": "",
      "color": "D93F0B"
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
      "name": "status:web_ready",
      "description": "",
      "color": "0E8A16"
    },
    {
      "name": "project",
      "description": "",
      "color": "B60205"
    },
    {
      "name": "hub:donostia_esp",
      "description": "",
      "color": "0E8A16"
    }
  ],
  "content": "### Title\r\n\r\nphys2CVR: a BIDS-compliant python toolbox to compute cerebrovascular reacitvity mapping\r\n\r\n### Leaders \r\n\r\nStefano Moia \r\n\r\nEmail: s.moia.research@gmail.com\r\nTwitter: @SteMoia\r\nMattermost: @smoia\r\n\r\n### Collaborators\r\n\r\n_No response_\r\n\r\n### Brainhack Global 2023 Event\r\n\r\nBrainhack Donostia\r\n\r\n### Project Description\r\n\r\nphys2cvr is a python toolbox that aims at offering various approaches to compute cerebrovascular mapping, starting from at least a functional MRI hypervolume.\r\n\r\nWhile not the first toolbox to compute CVR out there, I'm aiming at making something easy to adopt, a swiss knife to compute all sorts of maps to image cerebral physiology (*not* to denoise fMRI timeseries, for that you can check [phys2denoise](https://github.com/physiopy/phys2denoise)). phys2cvr should become one of the most complete tools for CVR mapping available, easy to adopt through a CLI (and, if possible, a GUI), with nice reports and plots, and allowing the highest automation through BIDS compliance. No repetition allowed thoough: for all python-based approaches out there, phys2cvr should only act as wrap around.\r\nAll contributions are welcome - and all contributions are recognised via all-contributors guidelines (and authorship on publications).\r\n\r\nThe project is already in advanced beta stage - in fact, I'm aiming at writing and publishing a paper about it. There is a list of to-dos left, that I collected [here](https://docs.google.com/document/d/1MFgwIjM5IaT7RlHtc5vzplPXZi8xaW76Fa-dLzknckA/edit?usp=sharing), before submitting a manuscript.\r\n\r\nIf you want to collaborate, yaih! Feel free to reach out to me, and if you are attending Brainhack Donostia, we can get the party started!\r\n\r\n### Link to project repository/sources\r\n\r\nhttps://github.com/smoia/phys2cvr\r\n\r\n### Goals for Brainhack Global\r\n\r\nGo through this list as much as possible:\r\n\r\nhttps://docs.google.com/document/d/1MFgwIjM5IaT7RlHtc5vzplPXZi8xaW76Fa-dLzknckA/edit?usp=sharing\r\n\r\n### Good first issues\r\n\r\n1. issue one:\r\nadd a code of conduct and a contribution guideline\r\n2. issue two:\r\ncheck that licence is valid in all files\r\n3. issue three:\r\nspellcheck CLI help and docstrings\r\n\r\n### Communication channels\r\n\r\nhttps://mattermost.brainhack.org/brainhack/channels/bhg-phys2cvr\r\n\r\n### Skills\r\n\r\nThe list of todos is long, and each part requires different skills.\r\nIn general, no skill is required, beside good will and interest in CVR mapping.\r\n\r\nIn practice, generally speaking git knowledge is welcome. To touch the code, python knowledge is fairly mandatory. For documentation and other parts, knowing markdown or restructured test would be nice, but not mandatory. \r\n\r\n### Onboarding documentation\r\n\r\n_No response_\r\n\r\n### What will participants learn?\r\n\r\ngit, python, CVR mapping, pre-commit, sphinx based documentation writing, datalad, ...\r\n\r\n### Data to use\r\n\r\n_No response_\r\n\r\n### Number of collaborators\r\n\r\nmore\r\n\r\n### Credit to collaborators\r\n\r\nI follow physiopy's CoC, guidelines, and contribution recognition.\r\n\r\nAll contributions are recognised through all-contributors, all contributors are invited to be authors in outreach activities.\r\n\r\n### Image\r\n\r\nLeave this text if you don't have an image yet.\r\n\r\n### Type\r\n\r\npipeline_development\r\n\r\n### Development status\r\n\r\n2_releases_existing\r\n\r\n### Topic\r\n\r\nphysiology\r\n\r\n### Tools\r\n\r\nBIDS\r\n\r\n### Programming language\r\n\r\nPython\r\n\r\n### Modalities\r\n\r\nfMRI\r\n\r\n### Git skills\r\n\r\n2_branches_PRs\r\n\r\n### Anything else?\r\n\r\n_No response_\r\n\r\n### Things to do after the project is submitted and ready to review.\r\n\r\n- [x] Add a comment below the main post of your issue saying: `Hi @brainhackorg/project-monitors my project is ready!`\r\n- [ ] Twitter-sized summary of your project pitch.",
  "project_url": "https://github.com/smoia/phys2cvr",
  "project_description": "\r\n\r\nphys2cvr is a python toolbox that aims at offering various approaches to compute cerebrovascular mapping, starting from at least a functional MRI hypervolume.\r\n\r\nWhile not the first toolbox to compute CVR out there, I'm aiming at making something easy to adopt, a swiss knife to compute all sorts of maps to image cerebral physiology (*not* to denoise fMRI timeseries, for that you can check [phys2denoise](https://github.com/physiopy/phys2denoise)). phys2cvr should become one of the most complete tools for CVR mapping available, easy to adopt through a CLI (and, if possible, a GUI), with nice reports and plots, and allowing the highest automation through BIDS compliance. No repetition allowed thoough: for all python-based approaches out there, phys2cvr should only act as wrap around.\r\nAll contributions are welcome - and all contributions are recognised via all-contributors guidelines (and authorship on publications).\r\n\r\nThe project is already in advanced beta stage - in fact, I'm aiming at writing and publishing a paper about it. There is a list of to-dos left, that I collected [here](https://docs.google.com/document/d/1MFgwIjM5IaT7RlHtc5vzplPXZi8xaW76Fa-dLzknckA/edit?usp=sharing), before submitting a manuscript.\r\n\r\nIf you want to collaborate, yaih! Feel free to reach out to me, and if you are attending Brainhack Donostia, we can get the party started!\r\n\r\n"
}