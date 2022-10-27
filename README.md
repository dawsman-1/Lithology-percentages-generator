# Lithology-percentages-generator
Generates lithology percentages per formation/ stratigraphic zone for drilled wells for input to 1D basin models

### Web app:

Deployed as an interactive web application on Heroku cloud application platform: https://lithology-percent-generator.herokuapp.com/ (may not work after 28/11/2022, see alternative link below)

Alternative Hugging Face app: https://huggingface.co/spaces/dawsond/lithology-percentages-generator

Web app created using Mercury: https://github.com/mljar/mercury

### Docker deployment:

Run the following commands via terminal from within the cloned repository:

```python
docker build -t lithology-generator:latest .
```

```python
docker run --rm -it -p 8888:8888 lithology-generator:latest
```
