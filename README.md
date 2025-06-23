# Tiny-thumos-14

`Tiny-thumos-14` is a small video action recognition dataset, consisting of a selection of videos from the **THUMOS-14** dataset. This dataset is suitable for action recognition tasks and aims to provide a lightweight resource for researchers and developers for testing and experimentation.


## Dataset Contents

The dataset consists of several video clips, each associated with action annotations. The detailed information about the dataset is as follows:

* **Subsets**: `validation` and `training` (each subset contains up to 10 videos)
* **Video format**: Each video is in `.mp4` format.
* **Annotation Information**: Each video has a corresponding annotation file, which includes the action label and the time segment during which the action occurs.

## Dataset Structure

The dataset structure is as follows:

```plaintext
Tiny-thumos-14
├─multithumos
│  └─annotations          # Contains annotation files for the dataset
└─video                   # Contains video data (downloaded from Google Drive)
```
