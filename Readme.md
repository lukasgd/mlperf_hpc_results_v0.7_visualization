### MLPerf HPC v0.7 results visualization

Create a copy of `mlperf_results_paths.json.template` at `mlperf_results_paths.json` with valid paths to the results repos, set up the Python virtual env 

```
python3 -m venv venv; source venv/bin/activate; pip install --upgrade pip; pip install -r requirements.txt
```

and run the `MLPerfResultsVisualizer.ipynb` in Jupyter (the benchmark to visualize can be chosen on the top of the notebook). 

Currently supported benchmarks include`HPC-v0.7/{Cosmoflow,DeepCAM}`. The notebook with figures for a specific benchmark can be found in the corresponding branch.
