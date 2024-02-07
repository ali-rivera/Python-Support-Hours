*Feel free to explore this document and the linked resources (as well as other documentation on these tools) to help understand how different environments work. I encourage you to come back to it later as you get experience and start to understand more about the differences once you have more experience and context.*

# Tech Stack
To run Python code on your machine you'll need an environment to do so. There are a few options for getting started, each with their Pros and Cons...

## IDE (Integrated Development Environment)
An IDE is an environment on your machine where you can write and execute code, usually with some bells and whistles to improve or optimize the experience. These bells and whistles usually include some type of debugger that helps you identify what and where the problems in your code are, syntax highlighting and auto-completion, easy integration into GitHub... etc. These are held locally on your machine. This [Code Academy] blog post has a nice overview of some popular IDEs and their use cases.

**Pros:** No internet connection needed (usually), lots of helpful features 

**Cons:** Requires set up and management by user, different operating systems (Mac, Windows, Linux) have different nuances 

Examples: [VS Code] (with extensions), [PyCharm]

## Anaconda/Miniconda
[Anaconda] is a distribution that contains Python, the package/dependency/environment manager `conda`, and a large group of packages that you may or (more likely) may not use. It gives you access to [Jupyter] Lab, a popular web-based IDE to run Jupyter Notebook files. It also takes up a lot of disk space (minimum 5 GB free disc space to download and install!)
A smaller version of this is [miniconda], which has Python and `conda` without all the extra stuff you may or (more likely) may not use. You'll want to pair miniconda with an IDE like VS Code.

Looking for more information? This [stackoverflow] comment explains nicely how Anaconda, miniconda, and Conda differ.

**Pros:** Easy to get started (install and go!), includes a package manager

**Cons:** Anaconda needs a lot of disc space & has a lot of extras you probably won't use, need an internet connection to use Jupyter Lab

## Cloud Environments
Cloud-based environments are a hosted virtual machine (which just means that it is a machine in a warehouse somewhere and you access it through the internet) and allow for secure, sharable access to a set environment. This ends up being less work for the user because the coding environment is already set up on the virtual machine, they just have to log in and start using it. 

**Pros:** Consistent, little to no setup for the user, works the same on all (most) machines

**Cons:** Need internet access, requires VM set up by some party, usually time-based access, can be difficult to install new features (unless you have root access)

Examples: [AWS] (Amazon Web Services), [Azure] (Microsoft), [Rivanna] (UVA)

## Google Colab
[Google Colab] is a web service that provides access to a Jupyter Notebook service and free computing resources (with a paid option for more computing power!). You can also get free access to GPU and TPU services (useful for high computational loads like training neural networks) with options to pay to add more if needed. This is entirely web-based so all you need to do is sign-in - no download or install required. 

**Pros:** Easiest set up (login and go!), integrates with your Google Drive, good free options

**Cons:** Harder to integrate GitHub, requires internet connection, difficult to store files unless you mount your Google Drive, have to load the GitHub repo every time you start and new notebook

_____________________________
# Next Steps:
- Decide which option you'd like to use to use. Use the linked documentation to download the necessary software/make accounts.​ *(NOTE: setting up VS Code can be a little involved. This [medium article] is helpful to follow along with)*

- Test that your environment is working by running: `print("Hello world")`




[Code Academy]: https://www.codecademy.com/resources/blog/popular-ides-and-code-editors/
[VS Code]: https://code.visualstudio.com/
[PyCharm]: https://www.jetbrains.com/pycharm/
[Anaconda]: https://www.anaconda.com/
[jupyter]: https://jupyter.org/
[Miniconda]: https://docs.conda.io/en/latest/miniconda.html
[stackoverflow]: https://stackoverflow.com/a/58147674
[Google Colab]: https://colab.google/
[AWS]: https://aws.amazon.com/free/?trk=be77f66f-da84-4f51-9483-df3858616660&sc_channel=ps&s_kwcid=AL!4422!10!71124885882247!71125409442309&ef_id=ffd81f313299198b596f7bd5fc2ac01e:G:s&all-free-tier.sort-by=item.additionalFields.SortRank&all-free-tier.sort-order=asc&awsf.Free%20Tier%20Types=*all&awsf.Free%20Tier%20Categories=*all
[Azure]: https://azure.microsoft.com/en-us/resources/cloud-computing-dictionary/what-is-azure/?ef_id=_k_ca7215648395130e6c8671804d1a3f57_k_&OCID=AIDcmm5edswduu_SEM__k_ca7215648395130e6c8671804d1a3f57_k_&msclkid=ca7215648395130e6c8671804d1a3f57
[Rivanna]: https://www.rc.virginia.edu/userinfo/rivanna/overview/
[medium article]: https://medium.com/the-researchers-guide/how-to-set-up-python-and-visual-studio-code-ide-for-data-science-161c61f76fe3
