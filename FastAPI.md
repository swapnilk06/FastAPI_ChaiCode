# Fast API - Chai Code
[12-05-25]

FastAPI is a modern, fast (high-performance), web framework for building APIs with Python based on standard Python type hints.

### What we learn?
- [x] Fast API fast face overview
- [x] Build CRUD Operation
- [x] Showing how can fastly develop API? or along with documentation.


---------------

<br>

#### Overiew
- `Express` in -> JS
- `FastAPI` in -> Python
- Both gives same developer experience.
- Django is a good framework, 
	- but for pure API development, it is not an option. Instead, `REST API` is used as a hacky solution.
	- But not performace optimize.

<br>


> [!IMPORTANT]
> - In `JS express` gives same developer experience for fastly build API.
> - Under in `Python Fast API` gives same experience as JS express give.
> - Not only experience but, its `one of the industry standard`.

<br>

> [!TIP]
> - Any can work as Data Scientist or Python based web developement journey knowing of Fast API working is most important thing.
> - ALl industry are migrate in that or machine based consumption mostly in that Fast API.

<br>

### Fast API with doc
[FastAPI](https://fastapi.tiangolo.com/)
[Uvicorn](https://www.uvicorn.org/)

- Fast API needed some helper :-
- Also directly run through FastAPI but, mostly coder run `Uvicorn` web server.
- Fast API also with there inbulid web server - that build also on Uvicorn.
- 1] Most used of `Uvicorn` --> its basic `web server`(pure web server implementation).
- 2] For development of any python web application `one standard is all companies are use.` i.e. `Pydantic`
	- What work of pydantic? - Pydantic is `data validation library` for python.
	- `Data types in python are not well defined` i.e Python's Pydantic are fullfilled that shortage.
- Similar in JS, `Typescript` will fullfilled the shortage of types in JS. 
- Pydantic is more powerful.
- 3] Use `typing` module (core module of python)


<br>

## Build basic web application using `Fast API`, `Uvicorn`, `Pydantic`
1] Run cmd - 
- For create a virtual environment in Python.
- `.venv`(for hidden) or `venv` also can use boths
- `Virtual Env.` => for that package can move other system env or production env for same that.
```sh
python -m venv .venv
```
2] Activate Virtual Environment (in window bash) -
```sh
source .venv/Scripts/activate
```
- (.venv) => that showing environment activated.

3] Install Fast API & Uvicorn
```sh
pip install fastapi uvicorn
```


-------

> [!TIP]
>



### Next to learn?
- [x] Pydantic Crash course
- [x] Fast API setup