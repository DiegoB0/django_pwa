
# Simple Dj Ango-PWA Application

### This is a simple django project that uses service workers to catch static files so the user can see them offline

***

## Requirements

> - You'll need to have [Python](https://www.python.org/downloads/) installed. <br>
>    You can check if u have it installed with:
>
> ```python
>   python --version
> ```
>
> - Set [pip](https://pypi.org/project/pip/) in your environment variables. <br>
>    You can also check with a:
>
> ```python
>  pip --version
> ```

## Setup

1.- Clone the repository:

```bash
  git clone https://github.com/your-username/your-repository.git
  cd your-repository
```

2.- Create a virtual environment

```python
  python -m venv myvenv
```

3.- Activate the virtual environment

  - On Windows:
  ```powershell
    myvenv\Scripts\activate
  ```

  - On Linux
  ```bash
    source myvenv/bin/activate
  ```

4.- Install the dependencies

```python
  pip install -r requirements.txt
```

5.- Run the migrations

```python
  python manage.py migrate
```

6.- Run the server

```python
  python manage.py runserver
```
