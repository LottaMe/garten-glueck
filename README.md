# Geburtstagsgeschenk

## Setup:
In the core folder, first set up your python environment and activate it:

```
python3 -m venv env
source env/bin/activate
```

Then install the required packages:

```
pip install -r requirements.txt
```

go into the frontend folder and install the frontend dependencies:

```
cd frontend
npm install
```

## Start:
In the core folder run:

```
uvicorn main:app --reload
```

In another terminal in the core folder run:

```
cd frontend && npm run dev
```