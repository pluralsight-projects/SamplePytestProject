# SamplePytestProject

## Create Virtual Environment

In a terminal run the following commands from the root folder of the forked project. 

Windows
```
python -m venv .\venv
```

macOS & Linux
```
python -m venv ./venv
```

Once that completes, also run this command from the same folder.

Windows
```
\venv\Scripts\activate.bat
```

macOS & Linux
```
source venv/bin/activate
```

Now that you are working in the virtualenv, install the project dependencies with the following command.

```
pip install -r requirements.txt
```

## Verify Setup

In order to verify that everything is setup correctly, run the following command, which should show you the failing tests. This is good! We'll be fixing this test once we jump into the build step.

```
pytest
```

Every time you want to check your work locally you can type that command, and it will report the status of every task in the project.

# Solution

[sample/app.py](https://github.com/pluralsight-projects/SamplePytestProject/blob/solution/SamplePytestProject/app.py)