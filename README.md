Identifying Influencers | Reddit Dataset 📈📊
============

[![](https://img.shields.io/badge/Made_with-Python3-blue?style=for-the-badge&logo=python)]()
[![](https://img.shields.io/badge/Made_with-networkx-blue?style=for-the-badge&logo=networkx)]()
[![](https://img.shields.io/badge/Made_with-matplotlib-blue?style=for-the-badge&logo=matplotlib)]()
[![](https://img.shields.io/badge/Made_with-pandas-blue?style=for-the-badge&logo=pandas)]()
[![](https://img.shields.io/badge/ide-jupyter-blue?style=for-the-badge&logo=jupyter)]()

## Project description
The Reddit Dataset contains discussion and non-discussion based threads from Reddit which we collected in May 2018. Nodes are Reddit users who participate in a discussion and links are replies between them.

## Dataset
reddit_threads.zip

### Properties
- Number of graphs: 203,088
- Directed: No.
- Node features: No.
- Edge features: No.
- Graph labels: Yes. Binary-labeled.
- Temporal: No.

### The Task

To find who’s the top 3 Influencers in the entire discussion
- You can decide what an influencer means
- Find at least one interesting insight you can derive from the dataset
- State all your assumptions clearly.

---

## Local installation:

### Creating the virtual environment

Create a new virtual environment to run the file using the following command:

`python3 -m venv <name of the environment>`

### Activating the environment

We will now activate the environment using:

`source <name>/bin/activate`

Note: when activated, the name of the environment appears in the parenthesis before username (or some other form.)

### Installing packages on the virtual environment

As long as the environment is active, pip will install packages in the currently active virtual environment. Navigate to the right directory containing the requirements file to install the dependencies using:

`pip3 install -r requirements.txt`

### Deactivating the environment

To deactivate the environment just type:

`deactivate`

### Adding the virtual environment to JuPyter notebook
`
Run the following when the environment is activated:

`python3 -m ipykernel install --user --name=<name>`

where <name> is the name of the environment.

When you open the Jupyter notebook, you should be able to select the environment.

### Removing the environment

To remove the virtual environment from JuPyter notebook, just run

`jupyter-kernelspec uninstall <name>`