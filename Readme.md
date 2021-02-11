### MLPerf results visualizer for Training/HPC v0.7

Create a copy of `mlperf_results_paths.json.template` at `mlperf_results_paths.json` with valid paths to the results repos, set up the Python virtual env 

```
python3 -m venv venv; source venv/bin/activate; pip install --upgrade pip; pip install -r requirements.txt
```

and run the `MLPerfResultsVisualizer.ipynb` in Jupyter (the benchmark to visualize can be chosen on the top of the notebook). 

Currently supported benchmarks include `Training-v0.7/ResNet` and `HPC-v0.7/{Cosmoflow,DeepCAM}` (note that for ResNet the results repo at https://github.com/lukasgd/training_results_v0.7 must be used). The notebook with figures for a specific benchmark can be found in the corresponding branch.

For 3d visualization run `MLPerfResultsVisualizer.ipynb` in `jupyter notebook` and comment out the line starting with `%%script ...`
