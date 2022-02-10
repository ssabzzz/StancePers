# StancePers (Cross-lingual Stance Detection using Multi-task Learning)
</br>
This is the accompanying repository of our "Cross-lingual Stance Detection" paper submitted to <a href="https://www.journals.elsevier.com/expert-systems-with-applications">Expert Systems with Applications journal</a>.

## Project Structure
```sh
.
├── docker
│   ├── CLEAN_BASE.ipynb
│   ├── CLEAN_MTL.ipynb
│   ├── README.md
│   └── requirements.txt
├── Dockerfile
├── post_trained_model
│   ├── config.json
│   ├── pytorch_model.bin
│   ├── README.md
│   └── training_args.bin
└── README.md


```

## Dataset 
 Until paper acceptance, you can apply for access to StancePers dataset by e-mail. In order to run the notebooks in the next section and the docker folder, you need the id of the dataset file.
 In any of the notebooks in this repo, search for `<FILE_ID>` and replace it with the id of the dataset.
 <strong>Once our paper got accepted in the journal, StancePers dataset will be made publicly available.</strong>
## Code
All experimens were run in a <a href="https://colab.research.google.com">Colab Environment</a> which offers free GPUs.
<a href="https://colab.research.google.com/drive/1_2kx3Z1rN65vWmNM2f59dd1QXVlGar5f?usp=sharing">MTL</a> and <a href="https://colab.research.google.com/drive/1uxxCExSbAcRo_0rMrns0l-uNjELwqsoj?usp=sharing">Base</a> are links to our saved colab notebooks.
A list of all currently-installed packages on Colab can be found in <a href="https://github.com/ssabzzz/StancePers/blob/main/docker/requirements.txt">requirements.txt</a> in the docker folder (unnecessary packages for running the notebooks on docker are commented out).
 
## Contact
Please send us an email if you have further questions or to request dataset. 
E-mail: z.saaberi@gmail.com
