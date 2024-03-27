This is a repository with some tutorial jupyter notebooks that demonstrate access to data on OPeNDAP servers.


<span style='font-family:serif'> <font size="7.5"><span style='color:#0066CC'><ins>Workflow Begins</ins><span style='color:black'>


<span style='font-family:serif'> <font size="4.5"> To navigate through this notebook, create and activate the conda environment with the necessary dependencies. This assumes the user has mamba installed in their computing environment.

```bash
$ mamba create -n opendap_tutorials -c conda-forge python=3.10 matplotlib pydap xarray cartopy jupyterlab
$ mamba activate opendap_tutorials
```

<span style='font-family:serif'> <font size="4.5"> The first line makes sure that all required packages are installed, while the second activates such environment so that any subsequent manipulation makes use of those packages. 

<span style='font-family:serif'> <font size="4.5"> When you're ready, on the command line do:

```bash
$ jupyterlab
```
