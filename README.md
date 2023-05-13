# Text Summarization Using python

This is a pytorch based application which extracts the important text form a given paragraph and presents the whole summary in minimal text. We use the Hugging face models using transformers and finetune the model on our desired dataset.

## Steps Used

1. Load the data form s3
2. Load the tokenizer and the model along with pre-trained weights.
3. Create custom dataset and dataloader using pytorch lightning
4. Create custom finetuner using pytorch lightning
5. Finetune the model using GPU
5. Create an flask based application


## 🧑‍💻 How to setup
create fresh conda environment 
```python
conda create -p venv python=3.10 -y
```
activate conda environment
```python
conda activate venv/
```
Install requirements
```python
pip install -r requirements.txt
```
Run the web app
```python
python app.py
```
To launch swagger ui
```python
http://localhost:8080/
```

## 🧑‍💻 Tech Used
1. Deep Learning
2. Hugging Face Models
3. Pytorch Lightning
4. Flask
5. Docker
6. GCP(Compute engine)

## 🏭 Industrial Use-cases 
1. Newsletters
2. Social media marketing

## 👋 Conclusion
The application have vast uses like summarizing a complete artical and providing a brief explanation of in compact text. It helps in better utilization of our precious time.
