{
  "Title": "Neuronal Spiking Ensembles: Dynamics of Representational Geometry",
  "link_to_issue": "https://github.com/brainhackorg/global2023/issues/93",
  "issue_number": 93,
  "labels": [
    {
      "name": "git_skills:2_branches_PRs",
      "description": "",
      "color": "5B6C2C"
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
      "name": "topic:machine_learning",
      "description": "",
      "color": "FBCA04"
    },
    {
      "name": "topic:PCA",
      "description": "",
      "color": "FBCA04"
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
      "name": "modality:behavioral",
      "description": "",
      "color": "1d76db"
    },
    {
      "name": "topic:neural_decoding",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "topic:single_neuron_models",
      "description": null,
      "color": "ededed"
    },
    {
      "name": "hub:vanderbilt_usa",
      "description": "",
      "color": "0E8A16"
    }
  ],
  "content": "### Title\r\n\r\nNeural Spiking Ensembles: Dynamics of Representational Geometry\r\n\r\n### Leaders\r\n\r\nRichard Song: @richardwsong \r\n\r\n### Collaborators\r\n\r\nKen Rahman: @RahmanKF22\r\nSam Abbaspoor: @SAbbaspoor\r\nKari Hoffman: @perpl_lab\r\n\r\n\r\n### Brainhack Global 2023 Event\r\n\r\nBrainHack Vanderbilt\r\n\r\n### Project Description\r\n\r\nWhat are the meaningful changes in the brain with experience, that allows for adaptive behavior? When we look at the coordinated activity across spiking networks of neuronal ensembles, we see a delicate balance of stability and flexibility, as needed for a system that can both learn and remember. In this project, we present a population of simultaneously-recorded neurons from the non-human primate during learning of a complex sequence memory task, and in sleep afterwards. These data are exceptionally rich for exploration, but also to address three fundamental questions: 1. can we decode behavioral states from the ensemble dynamics, 2. what is the core representational geometry of the ensembles (what factors are best preserved/differentiated in low-dimensional spaces, and how does the geometry constrain the computations and dynamics of the network, and finally, 3. Does the ensemble activity drift with time and experience, and if so, how?\r\n\r\n### Link to project repository/sources\r\n\r\nhttps://github.com/hoffman-lab/BrainHacks24-NeuralManifolds\r\n\r\n### Goals for Brainhack Global\r\n\r\nOur goals for you include: \r\n1) Being able to understand the format of neuronal spiking and the corresponding behavioral data. \r\n2) Use manifold learning techniques (e.g. PCA, tSNE, UMAP, CEBRA) to decode relevant behaviors in complex neural spiking data in low dimensional space. \r\n3) Modify manifold learning hyperparameters to achieve best behavioral decoding ability. \r\n4) Explore changes in single-cell level or behaviors to elucidate mechanisms of representational drift. \r\n\r\n### Good first issues\r\n\r\n1. Experiment on neural manifold creation with using different hyperparameters (e.g. n_neighbors or min_dist in UMAP). Different parameters can greatly change the shape of the manifold and thus can affect the ability to decode different behaviors. Afterwards, consider creating UI to visualize neural manifolds across different hyperparameters. [Here](https://pair-code.github.io/understanding-umap/) is a great example.\r\n2. Parallelize dimensionality reduction across a set of hyperparameters\r\n3. Experiment with which behavioral parameters are most separated in low dimensional space (block type, trial number, time, head position, angular velocity, etc.)\r\n4. Explore characteristics that may be leading to representational drift. How is firing rate of the cells changing across trials and over time? What about accuracy, time to perform the task, or reward received? \r\n5. [Structural Index](https://github.com/PridaLab/structure_index) for Neural Manifolds\r\n\r\n### Communication channels\r\n\r\nmanifold_tuning channel on the discord: https://discord.gg/jbQWFhKn \r\n\r\n### Skills\r\n\r\n- Python and Jupyter Notebook: intermediate/advanced \r\n- Git: intermediate \r\n- Machine Learning: intermediate\r\n- Topological Data Analysis: preferred but not required \r\n\r\n### Onboarding documentation\r\n\r\n_No response_\r\n\r\n### What will participants learn?\r\n\r\nParticipants will gain experience analyzing high dimensional neural spiking data at a population-level using manifold learning in Python. They will work at the cutting-edge of systems neuroscience research, working with novel and groundbreaking data collected on non-human primates. \r\n\r\n### Data to use\r\n\r\n_No response_\r\n\r\n### Number of collaborators\r\n\r\n4\r\n\r\n### Credit to collaborators\r\n\r\nProject contributors are credited on the Readme and major contributors may be considered for coauthorship. \r\n\r\n### Image\r\n\r\n![image](https://github.com/brainhackorg/global2023/assets/14797031/d6de56fc-fd8f-4748-b52c-445f78845edc)\r\n![image](https://github.com/brainhackorg/global2023/assets/14797031/5e47085a-17ea-4458-a86a-822deaac616f)\r\n(Sebastian et al., Nature Neuroscience, 2023) \r\n\r\n### Type\r\n\r\ncoding_methods, pipeline_development, visualization\r\n\r\n### Development status\r\n\r\n1_basic_structure\r\n\r\n### Topic\r\n\r\ndata_visualisation, machine_learning, neural_decoding, PCA, single_neuron_models\r\n\r\n### Tools\r\n\r\nJupyter, other\r\n\r\n### Programming language\r\n\r\nPython\r\n\r\n### Modalities\r\n\r\nother\r\n\r\n### Git skills\r\n\r\n2_branches_PRs\r\n\r\n### Anything else?\r\n\r\n_No response_\r\n\r\n### Things to do after the project is submitted and ready to review.\r\n\r\n- [ ] Add a comment below the main post of your issue saying: `Hi @brainhackorg/project-monitors my project is ready!`\r\n- [ ] Twitter-sized summary of your project pitch.",
  "project_url": "https://github.com/hoffman-lab/BrainHacks24-NeuralManifolds",
  "project_description": "\r\n\r\nWhat are the meaningful changes in the brain with experience, that allows for adaptive behavior? When we look at the coordinated activity across spiking networks of neuronal ensembles, we see a delicate balance of stability and flexibility, as needed for a system that can both learn and remember. In this project, we present a population of simultaneously-recorded neurons from the non-human primate during learning of a complex sequence memory task, and in sleep afterwards. These data are exceptionally rich for exploration, but also to address three fundamental questions: 1. can we decode behavioral states from the ensemble dynamics, 2. what is the core representational geometry of the ensembles (what factors are best preserved/differentiated in low-dimensional spaces, and how does the geometry constrain the computations and dynamics of the network, and finally, 3. Does the ensemble activity drift with time and experience, and if so, how?\r\n\r\n"
}