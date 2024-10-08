# covost2

参考：

- [代码](https://github.com/huggingface/datasets/blob/master/datasets/covost2)
- [Huggingface](https://huggingface.co/datasets/covost2)

## en_de

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/en_de')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 15531
`'train'` | 289430
`'validation'` | 15531

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## en_tr

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/en_tr')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 15531
`'train'` | 289430
`'validation'` | 15531

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## en_fa

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/en_fa')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 15531
`'train'` | 289430
`'validation'` | 15531

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## en_sv-SE

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/en_sv-SE')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 15531
`'train'` | 289430
`'validation'` | 15531

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## en_mn

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/en_mn')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 15531
`'train'` | 289430
`'validation'` | 15531

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## en_zh-CN

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/en_zh-CN')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 15531
`'train'` | 289430
`'validation'` | 15531

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## en_cy

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/en_cy')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 15531
`'train'` | 289430
`'validation'` | 15531

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## en_ca

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/en_ca')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 15531
`'train'` | 289430
`'validation'` | 15531

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## en_sl

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/en_sl')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 15531
`'train'` | 289430
`'validation'` | 15531

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## en_et

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/en_et')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 15531
`'train'` | 289430
`'validation'` | 15531

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## en_id

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/en_id')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 15531
`'train'` | 289430
`'validation'` | 15531

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## en_ar

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/en_ar')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 15531
`'train'` | 289430
`'validation'` | 15531

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## en_ta

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/en_ta')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 15531
`'train'` | 289430
`'validation'` | 15531

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## en_lv

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/en_lv')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 15531
`'train'` | 289430
`'validation'` | 15531

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## en_ja

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/en_ja')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 15531
`'train'` | 289430
`'validation'` | 15531

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## fr_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/fr_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 14760
`'train'` | 207374
`'validation'` | 14760

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## de_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/de_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 13511
`'train'` | 127834
`'validation'` | 13511

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## es_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/es_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 13221
`'train'` | 79015
`'validation'` | 13221

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## ca_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/ca_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 12730
`'train'` | 95854
`'validation'` | 12730

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## it_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/it_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 8951
`'train'` | 31698
`'validation'` | 8940

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## ru_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/ru_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 6300
`'train'` | 12112
`'validation'` | 6110

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## zh-CN_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/zh-CN_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 4898
`'train'` | 7085
`'validation'` | 4843

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## pt_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/pt_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 4023
`'train'` | 9158
`'validation'` | 3318

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## fa_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/fa_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 3445
`'train'` | 53949
`'validation'` | 3445

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## et_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/et_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 1571
`'train'` | 1782
`'validation'` | 1576

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## mn_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/mn_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 1759
`'train'` | 2067
`'validation'` | 1761

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## nl_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/nl_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 1699
`'train'` | 7108
`'validation'` | 1699

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## tr_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/tr_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 1629
`'train'` | 3966
`'validation'` | 1624

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## ar_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/ar_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 1695
`'train'` | 2283
`'validation'` | 1758

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## sv-SE_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/sv-SE_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 1595
`'train'` | 2160
`'validation'` | 1349

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## lv_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/lv_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 1629
`'train'` | 2337
`'validation'` | 1125

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## sl_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/sl_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 360
`'train'` | 1843
`'validation'` | 509

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## ta_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/ta_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 786
`'train'` | 1358
`'validation'` | 384

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## ja_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/ja_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 684
`'train'` | 1119
`'validation'` | 635

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## id_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/id_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 844
`'train'` | 1243
`'validation'` | 792

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```

## cy_en

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:covost2/cy_en')
```

- **说明**：

```
CoVoST 2, a large-scale multilingual speech translation corpus covering translations from 21 languages into English and from English into 15 languages. The dataset is created using Mozilla’s open source Common Voice database of crowdsourced voice recordings.

Note that in order to limit the required storage for preparing this dataset, the audio
is stored in the .mp3 format and is not converted to a float32 array. To convert, the audio
file to a float32 array, please make use of the `.map()` function as follows:


python
import torchaudio

def map_to_array(batch):
    speech_array, _ = torchaudio.load(batch["file"])
    batch["speech"] = speech_array.numpy()
    return batch

dataset = dataset.map(map_to_array, remove_columns=["file"])
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'test'` | 690
`'train'` | 1241
`'validation'` | 690

- **特征**：

```json
{
    "client_id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "file": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "sentence": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "translation": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "id": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    }
}
```
