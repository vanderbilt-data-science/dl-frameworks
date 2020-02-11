# dl-frameworks
Overview of deep learning frameworks: PyTorch, TensorFlow, and what comes next

## Slides

See DeepLearningFrameworks.pptx in this repository for a the slides.

## Resources and Links

https://towardsdatascience.com/which-deep-learning-framework-is-growing-fastest-3f77f14aa318

https://www.fast.ai/2019/01/10/swift-numerics/

## Compute Environments

https://colab.research.google.com/ is the simplest way to get started with

https://www.fast.ai/ has guidelines on setting up environments for PyTorch. Remember: virtual environments are your friend. 

### Vanderbilt University ACCRE for GPU Computing

To use ACCRE for GPU computing, you need an ACCRE account.  You can sign up for an ACCRE account [here](https://www.vanderbilt.edu/accre/getting-started/), and make sure to satisfy their class requirements.

Using your VUNetID and password, log onto ACCRE via the [ACCRE portal](https://portal.accre.vanderbilt.edu).  Navigate to the top menu and click on `Interactive Apps`.  From the dropdown menu, choose `Jupter notebook (GPU)`.  Make sure you choose this **GPU** option.  If you're not sure about you may use the defaults here or customize according to your needs:

- **GPU Enabled Slurm Account**: `enter your slurm group here`
- **Number of hours**: `4`
- **Number of requested GPU resources**: `1`
- **GPU Architecture**: `Pascal`
- **Working directory**: `${ACCRE_RUNTIME_DIR}`
- **Python version**: `Python 3.6.3 / Anaconda 5.0.1`
- **Use a virtual environment checkbox**: `uncheck`
- **Python or Conda Virtual Environment**: `leave blank`

Now that you've made your options for your Jupyter work environment click `Launch`.  This will lead you to another page where ACCRE's scheduler (called SLURM) will try to schedule the time and resources you requested in your notebook.  It will go from a `Queued` state to a `Starting` state and finally be ready when the `Connect to Jupyter` button appears.  Click this button when it appears.

**On virtual environments.**  In general, you should use virtual environments when you're developing, since modifying your base environment can result in package clashes for different projects.  If you're interested in using a fast.ai virtual environment, you can modify the settings above with the following:

- **Python version**: `Python 3.6.3 / (GCC/6.4.0-2.28)`
- **Use a virtual environment checkbox**: `check`
- **Python or Conda Virtual Environment**: `/labs/accre_public/pascal/fast.ai.v2`

More information on creating custom virtual environments *using Anaconda* can be found in [the documentation](https://www.vanderbilt.edu/accre/documentation/python/) under **Anaconda** at the bottom.

## More Events

https://www.vanderbilt.edu/datascience/events/data-science-workshops/

## Consults

Sign up for consults with our Data Science team! 

Undergraduates: https://appoint.ly/s/vu-dsi-consult/student-consult

Researchers: https://appoint.ly/s/vu-dsi-consult/student-consult
