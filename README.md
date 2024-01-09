Please install the dependencies with ```python==3.9```. You can use you package manager or ```conda``` to accomplish this task.

To install all the dependencies, run the following code:

```pip install -r requirements.txt```

Then go into ```run_main.sh``` file, and change the email address in the line  ```#SBATCH --mail-user=netid@nyu.edu``` to your email address.

Run the following code:

```sbatch run_main.sh```

More details on: https://huggingface.co/docs/transformers/training

the sample dataset:[Yelp review](https://huggingface.co/datasets/yelp_review_full/tree/main/yelp_review_full)

remember to replace the empty file inside folder ```yelp_review_full``` with the testing and training datasets
