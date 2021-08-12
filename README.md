# Auto-minerva

Generate default minerva stories by cycling through avaliable channels

## Install

```
git clone https://github.com/adamjtaylor/auto-minerva
cd auto-minerva
conda create -n auto-minerva
conda activate auto-minerva
while read requirement; do conda install --yes $requirement; done < requirements.txt
```

## Use

In python
Input: image.ome.tif
Returns: json as string

```
story.py image.ome.tif
```

Save a story.json from the command line
```
python story.py image.ome.tif > story.json
```