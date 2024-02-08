# gp-winner-modified

Code was forked from [https://github.com/younader/Vesuvius-Grandprize-Winner].

Please download the [weights](https://drive.google.com/drive/folders/1rn3GMOvtJRMBHOxVhWFVSY6IVI6xUnYp)
and place the file in this folder.

```
# Install requirements
python -m pip install -r requirements.txt

# Do inference, modify segment_path so that it points to *.volpkg/paths
python inference_timesformer.py \
	--segment_id 20231210121321 20231221180251 \
	--segment_path ../../dl.ash2txt.org/full-scrolls/Scroll1.volpkg/paths \
	--model_path timesformer_wild15_20230702185753_0_fr_i3depoch=12.ckpt \
	--out_path output
```
