# Wardrobe Analytics via Airtable

I track what I wear every day in an Airtable database. This is a quick Jupyter notebook to generate some basic stats and visualizations. The tables themselves are neither complete nor 100% clean data because I set it up and populate it manually, but it's good enough to get an idea of what I've actually been wearing.

Airtable's interface is actually really great and you could get the info that this notebook currently provides in their app, but the idea is to eventually expand this to do more interesting things.

## Setup

Well, this really only works if you've got the exact same schema as me. But in case you want to do something similar:

1. Set airtable environment variables `AIRTABLE_KEY` and `AIRTABLE_BASE_ID`.

2. Install conda

3. Create environment (install dependencies)

```
conda env create -f environment.yml
source activate airtable
pip install -r requirements.txt # installs airtable library
```

4. Run the notebook in your browser with the command `jupyter notebook`

5. Wonder why you have so many clothes and only wear the same 10 things
