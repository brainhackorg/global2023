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
      "description": null,
      "color": "ededed"
    },
    {
      "name": "project_development_status:0_concept_no_content",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "project_type:method_development",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "modality:EEG",
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
      "name": "modality:ECOG",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "modality:eye_tracking",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "modality:MEG",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "modality:PET",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "programming:C++",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "programming:R",
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
  "content": "### Title\n\nPsy2R: Developing an R package for better inference in multivariate statistical analysis\n\n### Leaders\n\nKelly Garner Github: @kel-github Mattermost: @kels\r\n\n\n### Collaborators\n\nKevin Bird\r\nMelanie Gleitzman\r\nSonny Li\r\nChristopher Nolan Github: @crnolan Mattermost: @cnolan\n\n### Brainhack Global 2023 Event\n\nBrainhack Australasia\n\n### Project Description\n\nWe consistently use massive data sets across neuroscience and psychology. The routine gathering of big data requires that we are well equipped with tools that allow us to conduct appropriate multivariate statistics.\r\n\r\nMultivariate statistical analysis typically follows a two stage procedure, an omnibus test of the global null hypothesis followed by post-hoc tests of specific effects. It is not well known that under certain circumstances this leads to a drastically inflated rate of type 1 error. It is even less well known that this procedure can also lead to an even lessor known type IV error (incorrect interpretation of a correctly rejected hypothesis)!\r\n\r\nIt is possible to avoid these dragons by using an alternative procedure where all null hypotheses of interest are tested simultaneously. Using this approach ensures that type 1 error rate is controlled at alpha, and that only the correct null hypotheses are tested (which controls type IV error). This procedure can be hairy, and until now only one piece of software provides this method of testing ([PSY](https://www2.psy.unsw.edu.au/psy/)). However, this software is only available for use on windows and cannot be scripted into reproducible workflows.\r\n\r\nOur goal is to build an R package that implements the functions of PSY, and to make this method of statistical inference available to the masses! \n\n### Link to project repository/sources\n\nTBC\n\n### Goals for Brainhack Global\n\n**Milestones**\r\n\r\n1. Implement analyses that can be done in PSY in R [intermediate]\r\n2. Convert R implementation into generalisable functions [intermediate/advanced]\r\n3. Outline the math involved in computing critical values for STP tests under the null hypothesis [advanced]\r\n4. Interpret the PASCAL code that underpins the computation of critical values in PSY [advanced]\r\n5. Investigate the R world for a comprehensive list of packages that share some functionality with PSY [beginner]\r\n6. Test R functions and implement own analysis [beginner]\r\n7. Interpret what you think our R code does, to help us write more readable code [beginner]\r\n8. Document the PSY software functions and write documentation for the new R functions [beginner]\r\n9. Create project management board (e.g. trello) to keep us on track! [beginner]\n\n### Good first issues\n\n1. Implement analyses that can be done in PSY in R\r\n\r\n2. Document existing PSY software functions \r\n\r\n3. Investigate the R world for a comprehensive list of packages that share some functionality with PSY\r\n\r\n4. Create project management board (e.g. trello) to keep us on track!\r\n\r\n5. Create github repo for the project \n\n### Communication channels\n\nhttps://mattermost.brainhack.org/brainhack/channels/psy2r\n\n### Skills\n\n- R: all levels\r\n- stats/math: all levels\r\n- github: all levels\r\n- comp sci: intermediate/advanced\n\n### Onboarding documentation\n\n_No response_\n\n### What will participants learn?\n\nYou'll learn more about statistical analysis of big datasets, collaborative coding using R and github, and hopefully a bit about package development and coding for other users.\n\n### Data to use\n\n_No response_\n\n### Number of collaborators\n\nmore\n\n### Credit to collaborators\n\nProject contributors will be listed on the github repository's README.md\r\n\n\n### Image\n\n![DALL\u00b7E 2023-11-19 14 53 27 - draw me the greek character 'psi' with a capital R beside it in Quentin Blake style watercolour](https://github.com/brainhackorg/global2023/assets/7220723/224e6486-1a5f-4c96-a4a5-579bef546944)\r\n\n\n### Type\n\ncoding_methods, data_management, documentation, method_development\n\n### Development status\n\n0_concept_no_content\n\n### Topic\n\nreproducible_scientific_methods, statistical_modelling\n\n### Tools\n\nother\n\n### Programming language\n\nC++, documentation, `R`, other\n\n### Modalities\n\nbehavioral, DWI, ECOG, EEG, eye_tracking, fMRI, MEG, MRI, PET\n\n### Git skills\n\n1_commit_push\n\n### Anything else?\n\n_No response_\n\n### Things to do after the project is submitted and ready to review.\n\n- [X] Add a comment below the main post of your issue saying: `Hi @brainhackorg/project-monitors my project is ready!`\n- [X] Twitter-sized summary of your project pitch.",
  "project_description": "\n\nWe consistently use massive data sets across neuroscience and psychology. The routine gathering of big data requires that we are well equipped with tools that allow us to conduct appropriate multivariate statistics.\r\n\r\nMultivariate statistical analysis typically follows a two stage procedure, an omnibus test of the global null hypothesis followed by post-hoc tests of specific effects. It is not well known that under certain circumstances this leads to a drastically inflated rate of type 1 error. It is even less well known that this procedure can also lead to an even lessor known type IV error (incorrect interpretation of a correctly rejected hypothesis)!\r\n\r\nIt is possible to avoid these dragons by using an alternative procedure where all null hypotheses of interest are tested simultaneously. Using this approach ensures that type 1 error rate is controlled at alpha, and that only the correct null hypotheses are tested (which controls type IV error). This procedure can be hairy, and until now only one piece of software provides this method of testing ([PSY](https://www2.psy.unsw.edu.au/psy/)). However, this software is only available for use on windows and cannot be scripted into reproducible workflows.\r\n\r\nOur goal is to build an R package that implements the functions of PSY, and to make this method of statistical inference available to the masses! \n\n"
}