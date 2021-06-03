# Pull Map Tiles Into Jupyter Notebook

<img src="./tileoverlay_folium.gif" alt="panning map tiles with temperature overlay" width="80%" height="auto">

**The IPython Notebook accompanies a tutorial article for rendering weather data layers on top of base map tiles with folium.**

The repository includes a `requirements.txt` file with the necessary packages. However, if your environemt is setup to run IPython kernels, the only package to install is `folium`.

```
pip3 install folium
```

## API Key

The notebook calls the [Tomorrow.io](https://www.tomorrow.io/) weather API. You'll have to add the API key to the cell where the `apikey` variable is initialized.

**IMPORTANT**

Your API key is not secure when it's hardcoded into the cell (i.e. this notebook). Make sure the notebook is private and that your code is not submitted to a repository with your API exposed.
