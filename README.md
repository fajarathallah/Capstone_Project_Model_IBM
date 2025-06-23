<div align = 'center'>

  # Capstone Project - Data Classification and Summarization using Model IBM granite
</div>

## 📑: Project Overview

Penggunaan LLM seperti ChatGPT, Gemini, dll, telah menyulitkan identifikasi apakah sebuah teks ditulis oleh AI atau manusia. Permasalahan ini dapat menimbulkan resiko etika, penyebaran disinformasi, hingga kepercayaan terhadap keaslian konten.

Dilakukan pengklasifikasi yang mampu membedakan teks buatan manusia dan AI hingga membuat kesimpulan berfokus apa yang membedakan antara teks buatan AI dengan manusia

Pendekatan yang dilakukan adalah klasifikasi dan kesimpulan gaya penulisan teks dengan menggunakan model IBM Granite via Replicate di Google Collab melalui teknik prompting 

## 🔗: Raw Dataset Link

Dataset merupakan dataset yang bersifat open public yang bisa diakses melalui link ini:
https://www.kaggle.com/datasets/shanegerami/ai-vs-human-text/data

## 👓: Insight & findings

| Labelling	    | granite_pred	| style_analysis                |
|:--------------|:--------------|:------------------------------|
| Human	        | Human     	  | AI. The text is.....          |
| AI generated	| Human	        | AI. The text is classified... |
| AI generated	| Human	        | AI. The text is written...    |

Model belum baik dalam klasifikasi tulisan. Kecurigaan muncul diantara prompting yang kurang tepat, atau parameter yang belum Optimal.

Sedangkan untuk gaya penulisan,
1. AI :
- Menggunakan bahasa yang formal
- Sering memakai singkatan, ejaan, atau kode-kode tertentu
- Terkesan tidak natural dan tidak bernuansa

2. Human :
- Sering memuat pengalaman pribadi, dan sudut pandang subjektif.
- Argumen yang seimbang, disertai contoh

## 🤖: AI Support Explanation

Model IBM Granite digunakan untuk melakukan klasifikasi apakah text dibuat oleh AI atau Human dan juga, model digunakan untuk melakukan summarize dari 30 sample apa saja perbedaan gaya penulisan AI dan Human
