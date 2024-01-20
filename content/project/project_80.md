{
  "Title": "Analyzing Numerical Stability in Linear Registration",
  "link_to_issue": "https://github.com/brainhackorg/global2023/issues/80",
  "issue_number": 80,
  "labels": [
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
      "name": "git_skills:0_none",
      "description": "",
      "color": "5B6C2C"
    },
    {
      "name": "status:web_ready",
      "description": "",
      "color": "0E8A16"
    },
    {
      "name": "programming:C++",
      "description": "",
      "color": "5319E7"
    },
    {
      "name": "tools:FSL",
      "description": "",
      "color": "EA1D4E"
    },
    {
      "name": "hub:montreal_can",
      "description": "",
      "color": "0E8A16"
    }
  ],
  "content": "### Title\n\nAnalyzing Numerical Stability in Linear Registration\r\n\n\n### Leaders\n\nYohan Chatelain, Tristan Glatard, Mina Alizadeh, Ines Gonzalez Pepe\r\n\n\n### Collaborators\n\n_No response_\n\n### Brainhack Global 2023 Event\n\nBrainhack Montreal\n\n### Project Description\n\nThis project explores the numerical reliability of the [FSL FLIRT](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FLIRT) linear registration tool.\r\nWe aim to investigate how computational errors can affect the accuracy of this alignment tool.\r\n\r\nIn computers, real numbers are stored with limited precision, leading to tiny inaccuracies known as rounding errors. While often negligible, these errors can accumulate and potentially affect the outcomes in delicate processes like linear registration in neuroimaging.\r\nThis project aims to understand and mitigate these errors to improve the reliability of medical imaging analysis.\r\n\r\nTo evaluate numerical stability, we will employ Monte Carlo Arithmetic (MCA). This technique, a form of stochastic arithmetic, is designed to simulate rounding errors stemming from the finite precision of numbers in computing by using random variables. Tools like [Verificarlo](https://github.com/verificarlo/verificarlo), [Verrou](https://github.com/edf-hpc/verrou), and [Fuzzy](https://github.com/verificarlo/fuzzy) support MCA and are useful in adapting C, C++, FORTRAN, and Python codes for this purpose. Specifically, we'll use Fuzzy-libm, a modified version of libm, which introduces random noise into basic mathematical operations such as exp, log, cos, sin, etc.\r\n\r\n### Project 1: Testing Numerical Stability in FSL FLIRT\r\nWe aim to test FSL FLIRT's stability under varying conditions, including images, degrees of freedom, and optimization parameters. The goal is to understand how these variables impact FSL FLIRT's performance. To do so, we use the Fuzzy-libm tool on FLIRT, experimenting with a range of input parameters. \r\n\r\n### Project 2: Development Assistance for Simplified Algorithm\r\nDeveloping and testing a basic version of a registration algorithm. \r\nThis task is open to those interested in algorithm development and application, especially using SciPy.\r\n\r\n### Project 3: Examining Numerical Rounding Impacts\r\nDelving into how numerical rounding affects accuracy in neuroimaging. The objective is to analyze the computational steps of linear registration to gain a deeper understanding of the numerical behaviour.\r\n\r\nThis project is suitable for participants interested in medical imaging, computational neuroscience, and software development, and is especially relevant for those looking to understand the practical implications of computational inaccuracies in scientific research.\n\n### Link to project repository/sources\n\nGitHub repositories:\r\n- https://github.com/verificarlo/fuzzy\r\n- https://github.com/verificarlo/verificarlo\r\n- https://github.com/edf-hpc/verrou\r\n- https://git.fmrib.ox.ac.uk/fsl/flirt\r\n\r\nDocker images:\r\n- Fuzzy-libm: verificarlo/fuzzy:v0.9.1-lapack\r\n- Fuzzy-python: verificarlo/fuzzy:v0.9.1-lapack-python3.8.5\r\n- Fuzzy-scipy: verificarlo/fuzzy:v0.9.1-lapack-python3.8.5-numpy-scipy\r\n- Verificarlo: verificarlo/verificarlo:latest\r\n- Verrou: https://github.com/edf-hpc/verrou/blob/master/docker/Dockerfile\r\n\n\n### Goals for Brainhack Global\n\n1. Analyze FSL FLIRT numerical stability.\r\n2. Develop a simplified registration algorithm.\r\n3. Address and propose solutions for rounding issues.\r\n\n\n### Good first issues\n\n1. Provide a dataset to run FSL FLIRT on.\r\n2. Provide FSL FLIRT parameters to play with.\r\n3. Set up and run initial tests with FSL FLIRT.\r\n4. Help in the development of the simplified algorithm (SciPy implementation?).\r\n5. Provide metrics to measure numerical stability on perturbed registered images.\r\n\r\n\n\n### Communication channels\n\nhttps://mattermost.brainhack.org/brainhack/channels/numerical-stability-linear-registration\n\n### Skills\n\n- Python: Intermediate to Advanced\r\n- Familiarity with FSL or similar tools: Basic\r\n- Familiarity with stochastic arithmetic: Basic\r\n\n\n### Onboarding documentation\n\n_No response_\n\n### What will participants learn?\n\n- linear registration in neuroimaging\r\n- stochastic arithmetic\r\n- numerical instability metrics\r\n- algorithm development\r\n- collaborative open-source project work.\r\n\n\n### Data to use\n\n_No response_\n\n### Number of collaborators\n\n4\n\n### Credit to collaborators\n\nProject contributors are listed on the project README using [all-contributors github bot](https://github.com/all-contributors/all-contributors).\n\n### Image\n\nLeave this text if you don't have an image yet.\n\n### Type\n\nother\n\n### Development status\n\n0_concept_no_content\n\n### Topic\n\nreproducible_scientific_methods\n\n### Tools\n\nFSL\n\n### Programming language\n\nPython\n\n### Modalities\n\nMRI\n\n### Git skills\n\n0_no_git_skills\n\n### Anything else?\n\n_No response_\n\n### Things to do after the project is submitted and ready to review.\n\n- [x] Add a comment below the main post of your issue saying: `Hi @brainhackorg/project-monitors my project is ready!`\n- [ ] Twitter-sized summary of your project pitch.",
  "project_url": "https://github.com/verificarlo/fuzzy-",
  "project_description": "\n\nThis project explores the numerical reliability of the [FSL FLIRT](https://fsl.fmrib.ox.ac.uk/fsl/fslwiki/FLIRT) linear registration tool.\r\nWe aim to investigate how computational errors can affect the accuracy of this alignment tool.\r\n\r\nIn computers, real numbers are stored with limited precision, leading to tiny inaccuracies known as rounding errors. While often negligible, these errors can accumulate and potentially affect the outcomes in delicate processes like linear registration in neuroimaging.\r\nThis project aims to understand and mitigate these errors to improve the reliability of medical imaging analysis.\r\n\r\nTo evaluate numerical stability, we will employ Monte Carlo Arithmetic (MCA). This technique, a form of stochastic arithmetic, is designed to simulate rounding errors stemming from the finite precision of numbers in computing by using random variables. Tools like [Verificarlo](https://github.com/verificarlo/verificarlo), [Verrou](https://github.com/edf-hpc/verrou), and [Fuzzy](https://github.com/verificarlo/fuzzy) support MCA and are useful in adapting C, C++, FORTRAN, and Python codes for this purpose. Specifically, we'll use Fuzzy-libm, a modified version of libm, which introduces random noise into basic mathematical operations such as exp, log, cos, sin, etc.\r\n\r\n"
}