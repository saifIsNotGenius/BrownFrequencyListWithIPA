# Brown Corpus Frequency List with American Pronunciation

This project is an enhanced version of the classic Brown Corpus frequency list, now including American English pronunciation for each word.

## 📚 What is the Brown Corpus?

The Brown Corpus is a widely-used collection of American English text samples from 1961, annotated and categorized for linguistic analysis. It includes over one million words and is frequently used in computational linguistics and natural language processing.

## 🔤 What's New in This Version?

- ✅ Frequency list based on the original Brown Corpus  
- ✅ Added American English pronunciation for each entry (IPA format)  
- ✅ Clean CSV format for easy parsing and integration into language learning or NLP tools  

## 📁 File Structure

BrownFrequencyListWithIPA/

├── brown_frequency_with_pronunciation.csv

├── README.md

- `brown_frequency_with_pronunciation.csv`: The main data file containing:  
  - `word`: the word form   
  - `pronunciation`: American IPA transcription  

## 📦 How to Use

You can load the CSV using Python, Excel, or any tool that supports comma-separated values.  
Here’s a quick example in Python using pandas:

```python
import pandas as pd

df = pd.read_csv('brown_frequency_with_pronunciation.csv')
print(df.head())
```

## 💡 Use Cases

- Language learning applications  
- Pronunciation training tools  
- Linguistic research  
- Speech synthesis or recognition systems  

## 📝 License

This project is open source and available under the [MIT License](https://github.com/saifIsNotGenius/BrownFrequencyListWithIPA/blob/main/LICENSE).

---

Feel free to contribute or fork the project!
