{
  "Title": "Psy2R: Developing an R package for better inference in multivariate statistical analysis",
  "link_to_issue": "https://github.com/brainhackorg/global2023/issues/60",
  "issue_number": 60,
  "labels": [
    {
      "name": "git_skills:1_commit_push",
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
      "name": "hub:australasia_aus",
      "description": "",
      "color": "E99695"
    },
    {
      "name": "modality:behavioral",
      "description": "",
      "color": "1d76db"
    },
    {
      "name": "modality:ECOG",
      "description": "",
      "color": "1d76db"
    },
    {
      "name": "modality:eye_tracking",
      "description": "",
      "color": "1d76db"
    },
    {
      "name": "modality:MEG",
      "description": "",
      "color": "1d76db"
    },
    {
      "name": "modality:PET",
      "description": "",
      "color": "1d76db"
    },
    {
      "name": "programming:C++",
      "description": "",
      "color": "5319E7"
    },
    {
      "name": "programming:R",
      "description": "",
      "color": "5319E7"
    },
    {
      "name": "project_type:data_management",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "topic:statistical_modelling",
      "description": "",
      "color": "FBCA04"
    }
  ],
  "content": "### Title\r\n\r\nPsy2R: Developing an R package for better inference in multivariate statistical analysis\r\n\r\n### Leaders\r\n\r\nKelly Garner Github: @kel-github Mattermost: @kels\r\n\r\n\r\n### Collaborators\r\n\r\nKevin Bird,  \r\nMelanie Gleitzman,  \r\nSonny Li,  \r\nChristopher Nolan Github: @crnolan Mattermost: @cnolan\r\n\r\n### Brainhack Global 2023 Event\r\n\r\nBrainhack Australasia\r\n\r\n### Project Description\r\n\r\nWe consistently use massive data sets across neuroscience and psychology. The routine gathering of big data requires that we are well equipped with tools that allow us to conduct appropriate multivariate statistics.\r\n\r\nMultivariate statistical analysis typically follows a two stage procedure, an omnibus test of the global null hypothesis followed by post-hoc tests of specific effects. It is not well known that under certain circumstances this leads to a drastically inflated rate of type 1 error. It is even less well known that this procedure can also lead to an even lessor known type IV error (incorrect interpretation of a correctly rejected hypothesis)!\r\n\r\nIt is possible to avoid these dragons by using an alternative procedure where all inferences are derived from simultaneous confidence intervals (SCIs) on contrasts of interest. This approach provides interval inferences on effect sizes and it also ensures that the familywise type 1 error rate associated with directional inferences (the inferences usually derived from tests of null hypotheses) is controlled at alpha. One piece of software (PSY) can produce SCIs appropriate for planned analyses (where contrasts are defined independently of the data) and for more flexible analyses where contrasts are defined on a post hoc basis. However, this software is only available for use on windows and cannot be scripted into reproducible workflows.\r\n\r\nOur goal is to build an R package that implements the functions of PSY, and to make this method of statistical inference available to the masses! \r\n\r\n### Link to project repository/sources\r\n\r\nTBC\r\n\r\n### Goals for Brainhack Global\r\n\r\n**Milestones**\r\n\r\n1. Implement analyses that can be done in PSY in R [intermediate]\r\n2. Convert R implementation into generalisable functions [intermediate/advanced]\r\n3. Outline the math involved in computing critical values for STP tests under the null hypothesis [advanced]\r\n4. Interpret the PASCAL code that underpins the computation of critical values in PSY [advanced]\r\n5. Investigate the R world for a comprehensive list of packages that share some functionality with PSY [beginner]\r\n6. Test R functions and implement own analysis [beginner]\r\n7. Interpret what you think our R code does, to help us write more readable code [beginner]\r\n8. Document the PSY software functions and write documentation for the new R functions [beginner]\r\n9. Create project management board (e.g. trello) to keep us on track! [beginner]\r\n\r\n### Good first issues\r\n\r\n1. Implement analyses that can be done in PSY in R\r\n\r\n2. Document existing PSY software functions \r\n\r\n3. Investigate the R world for a comprehensive list of packages that share some functionality with PSY\r\n\r\n4. Create project management board (e.g. trello) to keep us on track!\r\n\r\n5. Create github repo for the project \r\n\r\n### Communication channels\r\n\r\nhttps://mattermost.brainhack.org/brainhack/channels/psy2r\r\n\r\n### Skills\r\n\r\n- R: all levels\r\n- stats/math: all levels\r\n- github: all levels\r\n- comp sci: intermediate/advanced\r\n\r\n### Onboarding documentation\r\n\r\n_No response_\r\n\r\n### What will participants learn?\r\n\r\nYou'll learn more about statistical analysis of big datasets, collaborative coding using R and github, and hopefully a bit about package development and coding for other users.\r\n\r\n### Data to use\r\n\r\n_No response_\r\n\r\n### Number of collaborators\r\n\r\nmore\r\n\r\n### Credit to collaborators\r\n\r\nProject contributors will be listed on the github repository's README.md\r\n\r\n\r\n### Image\r\n\r\n![DALL\u00b7E 2023-11-19 14 53 27 - draw me the greek character 'psi' with a capital R beside it in Quentin Blake style watercolour](https://github.com/brainhackorg/global2023/assets/7220723/224e6486-1a5f-4c96-a4a5-579bef546944)\r\n\r\n\r\n### Type\r\n\r\ncoding_methods, data_management, documentation, method_development\r\n\r\n### Development status\r\n\r\n0_concept_no_content\r\n\r\n### Topic\r\n\r\nreproducible_scientific_methods, statistical_modelling\r\n\r\n### Tools\r\n\r\nother\r\n\r\n### Programming language\r\n\r\nC++, documentation, `R`, other\r\n\r\n### Modalities\r\n\r\nbehavioral, DWI, ECOG, EEG, eye_tracking, fMRI, MEG, MRI, PET\r\n\r\n### Git skills\r\n\r\n1_commit_push\r\n\r\n### Anything else?\r\n\r\n_No response_\r\n\r\n### Things to do after the project is submitted and ready to review.\r\n\r\n- [X] Add a comment below the main post of your issue saying: `Hi @brainhackorg/project-monitors my project is ready!`\r\n- [X] Twitter-sized summary of your project pitch.",
  "project_description": "\r\n\r\nWe consistently use massive data sets across neuroscience and psychology. The routine gathering of big data requires that we are well equipped with tools that allow us to conduct appropriate multivariate statistics.\r\n\r\nMultivariate statistical analysis typically follows a two stage procedure, an omnibus test of the global null hypothesis followed by post-hoc tests of specific effects. It is not well known that under certain circumstances this leads to a drastically inflated rate of type 1 error. It is even less well known that this procedure can also lead to an even lessor known type IV error (incorrect interpretation of a correctly rejected hypothesis)!\r\n\r\nIt is possible to avoid these dragons by using an alternative procedure where all inferences are derived from simultaneous confidence intervals (SCIs) on contrasts of interest. This approach provides interval inferences on effect sizes and it also ensures that the familywise type 1 error rate associated with directional inferences (the inferences usually derived from tests of null hypotheses) is controlled at alpha. One piece of software (PSY) can produce SCIs appropriate for planned analyses (where contrasts are defined independently of the data) and for more flexible analyses where contrasts are defined on a post hoc basis. However, this software is only available for use on windows and cannot be scripted into reproducible workflows.\r\n\r\nOur goal is to build an R package that implements the functions of PSY, and to make this method of statistical inference available to the masses! \r\n\r\n"
}