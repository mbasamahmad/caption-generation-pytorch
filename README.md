# Caption Generation Using PyTorch

An image captioning project built in PyTorch on a subset of the Flickr8k dataset. The full walkthrough is in `Solution.ipynb`.

## Contents

| Path | Description |
|---|---|
| `Solution.ipynb` | End-to-end notebook: data loading, preprocessing, model, training and inference (with a Gradio demo) |
| `flickr-8k/text/Flickr8k.token.txt` | Captions (5 per image) |
| `flickr-8k/text/Flickr_8k.{train,dev,test}Images.txt` | Train / dev / test image splits |

## Not included in this repo

These are too large for GitHub and are kept on Google Drive:

- `flickr-8k/images/`: the image files ([Drive folder](https://drive.google.com/drive/folders/1epESpV5SCL-vI9hRoR8HRHX4MSDHxK5p))
- `model_state_34_jan31.pt`: trained model weights, ~711 MB ([Drive file](https://drive.google.com/file/d/178ooO8tfAlMQ24vZucZYB_dR9Gbz77Q0/view))

Download them and place them as follows:

```
flickr-8k/
  images/
  text/
model_state_34_jan31.pt
```

The notebook expects the data at `/usercode/flickr-8k/`; update `img_dir` and `text_dir` if your path differs.
