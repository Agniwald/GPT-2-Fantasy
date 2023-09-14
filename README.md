# GPT-2-Fantasy
This model was fine-tuned with intention of generating short fantasy stories based on given keywords. You can test this model [here](https://huggingface.co/spaces/egosumkira/GPT2-Fantasy).

## Training data
Training data was parsed from IMDB website and consists of keywords-synopsis pairs. Method of encoding data was inspired from [this repo](https://github.com/minimaxir/gpt-2-keyword-generation).

## Training hyperparameters

The following hyperparameters were used during training:
- optimizer: Adam
- dropout: 0.2
- learning schedule: exponential decay 
- epochs: 4

## Training results

Keywords: time travel, magic, rescue. \
Output: A group of young men find themselves in the middle of a desert, and must band together to save their friend from an evil force bent on destroying his world. But what if they don't trust each other? Is there something that might help them at all costs? Can they break the spell before it's too late? Will they be able to stop this Evil once and for all? Or will they do anything about it? Above all, can they make things right with humanity? And above all, is there some really good magic going on here? What are they trying to do?

### Framework versions

- Transformers 4.29.2
- TensorFlow 2.12.0
- Tokenizers 0.13.3
