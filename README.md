# Sentiment Analysis of Consumer Reviews of Amazon Products

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
The code was tested using Python version 3.9. 
For other necessary libraries please use requirements.txt
```bash
pip install -r requirements.txt
```
Please download the data from Kaggle [here](https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products)
## Project Motivation<a name="motivation"></a>

This project works with [Amazon Reviews Data](https://www.kaggle.com/datasets/datafiniti/consumer-reviews-of-amazon-products) and focusses on:
1.	Sentiment Analysis using Large Language Model (LLM)
2.	Fine-Tuning the Large Language Model
3.	Data Augmentation using Back-Translation technique
4.	Data Balancing (working with imbalanced Dataset)
    -	Random Oversampling 
    -	Weighted Loss




## File Descriptions <a name="files"></a>

```bash
sentiment-analysis-llm/
├── amazon reviews sentiment analysis.ipynb        # the notebook with data augmentation, data balancing, sentiment analysis and fine-tuning using (HuggingFace)
├── README.md              # readme file
├── requirements.txt       # all necessary libraries
├── Emoticon.py            # dictionary with emojis as a symbol with the text description 

```


## Results<a name="results"></a>

The main findings of the code can be found at the post:

"Sentiment Analysis of Customer Product Reviews using Large Language Model (LLM)" available [here](https://eneuburg.medium.com/large-language-model-llm-a-sentiment-analysis-with-customer-product-reviews-a56885593d70).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
 

Must give credit to Kaggle for providing the data. 



###### Copyright (C) 2024 February
###### TO THE FULLEST EXTENT PERMITTED UNDER APPLICABLE LAW, THE CODE COMPONENTS ARE PROVIDED BY THE AUTHORS, COPYRIGHT HOLDERS, CONTRIBUTORS, LICENSORS, “AS IS”.

######  DISCLAIMED ARE ANY REPRESENTATIONS OR WARRANTIES OF ANY KIND, WHETHER ORAL OR WRITTEN, WHETHER EXPRESS, IMPLIED, OR ARISING BY STATUTE, CUSTOM, COURSE OF DEALING, OR TRADE USAGE, INCLUDING WITHOUT LIMITATION THE IMPLIED WARRANTIES OF TITLE, MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, AND NON-INFRINGEMENT.
######  IN NO EVENT WILL THE COPYRIGHT OWNER, CONTRIBUTORS, LICENSORS BE LIABLE FOR ANY DIRECT, INDIRECT, INCIDENTAL, SPECIAL, EXEMPLARY, OR CONSEQUENTIAL DAMAGES (INCLUDING, BUT NOT LIMITED TO, PROCUREMENT OF SUBSTITUTE GOODS OR SERVICES; LOSS OF USE, DATA, OR PROFITS; OR BUSINESS INTERRUPTION). HOWEVER, CAUSED AND ON ANY THEORY OF LIABILITY, WHETHER IN CONTRACT, STRICT LIABILITY, OR TORT (INCLUDING NEGLIGENCE OR OTHERWISE) ARISING IN ANY WAY OUT OF THE USE OF THE CODE COMPONENTS, EVEN IF ADVISED OF THE POSSIBILITY OF SUCH DAMAGE. 


