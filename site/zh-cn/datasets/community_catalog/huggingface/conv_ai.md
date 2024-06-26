# conv_ai

参考：

- [代码](https://github.com/huggingface/datasets/blob/master/datasets/conv_ai)
- [Huggingface](https://huggingface.co/datasets/conv_ai)

## conv_ai

使用以下命令在 TFDS 中加载此数据集：

```python
ds = tfds.load('huggingface:conv_ai/conv_ai')
```

- **说明**：

```
ConvAI is a dataset of human-to-bot conversations labelled for quality. This data can be used to train a metric for evaluating dialogue systems. Moreover, it can be used in the development of chatbots themselves: it contains the information on the quality of utterances and entire dialogues, that can guide a dialogue system in search of better answers.
```

- **许可**：无已知许可
- **版本**：1.0.0
- **拆分**：

拆分 | 样本
:-- | --:
`'train'` | 2778

- **特征**：

```json
{
    "id": {
        "dtype": "int32",
        "id": null,
        "_type": "Value"
    },
    "dialogId": {
        "dtype": "int32",
        "id": null,
        "_type": "Value"
    },
    "context": {
        "dtype": "string",
        "id": null,
        "_type": "Value"
    },
    "users": [
        {
            "userType": {
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
    ],
    "evaluation": [
        {
            "breadth": {
                "dtype": "int32",
                "id": null,
                "_type": "Value"
            },
            "userId": {
                "dtype": "string",
                "id": null,
                "_type": "Value"
            },
            "quality": {
                "dtype": "int32",
                "id": null,
                "_type": "Value"
            },
            "engagement": {
                "dtype": "int32",
                "id": null,
                "_type": "Value"
            }
        }
    ],
    "thread": [
        {
            "evaluation": {
                "dtype": "int32",
                "id": null,
                "_type": "Value"
            },
            "text": {
                "dtype": "string",
                "id": null,
                "_type": "Value"
            },
            "userId": {
                "dtype": "string",
                "id": null,
                "_type": "Value"
            },
            "time": {
                "dtype": "int32",
                "id": null,
                "_type": "Value"
            }
        }
    ]
}
```
