release: jupyter nbextension install --py --sys-prefix widgetsnbextension
release: jupyter nbextension enable --py --sys-prefix widgetsnbextension

release: jupyter nbextension install --py --sys-prefix bqplot
release: jupyter nbextension enable --py --sys-prefix bqplot

web: voila --port=$PORT --no-browser notebooks/bqplot.ipynb
