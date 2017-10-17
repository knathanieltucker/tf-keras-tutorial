# tf-keras-tutorial
An introduction to tensorflow via keras

## Floydhub Setup

This will be much easier than the local installation most of the time. The first step is to make an account over at [Floydhub](https://www.floydhub.com/). You will then want to create a project (see [here](https://docs.floydhub.com/getstarted/get_started_jupyter/#create-a-new-project) for more details). I would suggest that you name it: `tf-keras-tutorial`.

Once that is done you will need to download this repository:

```
git clone https://github.com/knathanieltucker/tf-keras-tutorial.git
cd tf-keras-tutorial
```

Install the floydhub cli:

```
pip install floyd-cli
```

Initialize the project:

```
floyd init tf-keras-tutorial
```

This may prompt you to login. And finally run:

```
floyd run --cpu --env keras:py2 --tensorboard --mode jupyter
```

And that should take you to a working notebook. At this point I would suggest you turn the job off and wait for class to turn it back on again!

## Local Setup

Follow guide [here](http://python-guide-pt-br.readthedocs.io/en/latest/dev/virtualenvs/#virtualenv) to set up basic virtual env. After, run:

`pip install -r requirements.txt`

to install all requirements.

Make sure that you can run `ipython notebook` in your virtual env.
