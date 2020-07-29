<p align="center">
  <a href="https://fastapi.tiangolo.com"><img src="https://fastapi.tiangolo.com/img/logo-margin/logo-teal.png" alt="FastAPI"></a>
</p>
<p align="center">
    <em>FastAPI framework, Alta performance, fácil de aprender, coidifcação rádida, pronta pra ambiente de produção</em>
</p>
<p align="center">
<a href="https://github.com/tiangolo/fastapi/actions?query=workflow%3ATest" target="_blank">
    <img src="https://github.com/tiangolo/fastapi/workflows/Test/badge.svg" alt="Test">
</a>
<a href="https://codecov.io/gh/tiangolo/fastapi" target="_blank">
    <img src="https://img.shields.io/codecov/c/github/tiangolo/fastapi?color=%2334D058" alt="Coverage">
</a>
<a href="https://pypi.org/project/fastapi" target="_blank">
    <img src="https://img.shields.io/pypi/v/fastapi?color=%2334D058&label=pypi%20package" alt="Package version">
</a>
<a href="https://gitter.im/tiangolo/fastapi?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge" target="_blank">
    <img src="https://badges.gitter.im/tiangolo/fastapi.svg" alt="Join the chat at https://gitter.im/tiangolo/fastapi">
</a>
</p>

---

**Documentação**: <a href="https://fastapi.tiangolo.com" target="_blank">https://fastapi.tiangolo.com</a>

**Códifo fonte**: <a href="https://github.com/tiangolo/fastapi" target="_blank">https://github.com/tiangolo/fastapi</a>

---

FastAPI é uma moderna, rápida (alta performance), framework web para construir APIs com Python 3.6+ baseada nos padrões de tipagem do Python

Os recursos chaves são:

* **Rápido**: Altíssima performance, a altura de **NodeJS** e **Go** (obrigado a Starlette e Pydantic). [Uma das frameworks em python mais rápidas disponíveis](#performance).
* **Rápido de codar**: Aumenta a velocidade de desenvolvimento de recursos em cerca de 200 %a 300% *
* **Poucos bugs**: Reduz em cerca de 40% erros humanos (desenvolvedor). *
* **Intuitivo**: Ótimo editor de suporte. <abbr title="Também conhecido como auto-completar, auto-completador e IntelliSense">Auto completa</abbr> tudo. Menos tempo debugando.
* **Fácil**: Projetado para ser de fácil uso e aprendizado. Menos tempo lendo documentação.
* **Encurtador**: Minimize duplicação de código. Múltiplos recursos de cada declaração de paramêtro. Menos erros.
* **Robusto**: Tenha código pronto pra produção. Com documentação automática e interativa.
* **Baseado em padrão**: Baseado em (e totalmente compatível com) os padrões abertos das APIs:  <a href="https://github.com/OAI/OpenAPI-Specification" class="external-link" target="_blank">OpenAPI</a> (antes conhecido como Swagger) e <a href="http://json-schema.org/" class="external-link" target="_blank">JSON Schema</a>.

<small>* Estimação baseada a cerca de teste internos de um time de desenvolvimento, criando aplicações para produção. </small>

## Opiniões

"_[...] Eu estou usando **FastAPI** um monte esses dias. [...] na verdade eu estou planejando em coloca-la para uso em todo o meu time da **ML services na Microsoft**.  Alguns deles estão sendo intregrados no core do **Windows**" e em alguns produtos **Office**.

<div style="text-align: right; margin-right: 10%;">Kabir Khan - <strong>Microsoft</strong> <a href="https://github.com/tiangolo/fastapi/pull/26" target="_blank"><small>(ref)</small></a></div>

---
"_Nós adotampos a biblioteca **FastAPI** para gerar um servidor **REST** que pode ser consultado para obter **previsões**. [por Ludwig]_"

<div style="text-align: right; margin-right: 10%;">Piero Molino, Yaroslav Dudin, and Sai Sumanth Miryala - <strong>Uber</strong> <a href="https://eng.uber.com/ludwig-v0-2/" target="_blank"><small>(ref)</small></a></div>

---

"_A **Netflix** têm o prazer de anunciar a nossa framework de orquestração de **gerenciamento de crise** open-source! [feito em **FastAPI**]_"

<div style="text-align: right; margin-right: 10%;">Kevin Glisson, Marc Vilanova, Forest Monsen - <strong>Netflix</strong> <a href="https://netflixtechblog.com/introducing-dispatch-da4b8a2a8072" target="_blank"><small>(ref)</small></a></div>

---

"_Eu estou nas nuvens com o **FastAPI**". É tão divertido!_"

<div style="text-align: right; margin-right: 10%;">Brian Okken - <strong><a href="https://pythonbytes.fm/episodes/show/123/time-to-right-the-py-wrongs?time_in_sec=855" target="_blank">Python Bytes</a> podcast host</strong> <a href="https://twitter.com/brianokken/status/1112220079972728832" target="_blank"><small>(ref)</small></a></div>

---
"_Honestamente, o que você construiu parece super sólido e polido. De várias maneiras é o que eu queria **Hug** de ser - É realmente excitante de ver alguém construir isso._"

<div style="text-align: right; margin-right: 10%;">Timothy Crosley - <strong>Criador do<a href="http://www.hug.rest/" target="_blank"> Hug</a></strong> <a href="https://news.ycombinator.com/item?id=19455465" target="_blank"><small>(ref)</small></a></div>

---

"_Se você está procurando uma **framework moderna** para aprender a construir APIs REST, dê uma olhada na **FastAPI** [...]  É rápida, fácil de usar e fácil de aprender [...]_"

"_Nós trocamos para **FastAPI** nossas **APIs** [...] Eu acho que você vai gostar [...]_"

<div style="text-align: right; margin-right: 10%;">Ines Montani - Matthew Honnibal - <strong>Fundador da <a href="https://explosion.ai" target="_blank">Explosion AI</a> - Criadores da s<a href="https://spacy.io" target="_blank">spaCy</a></strong> <a href="https://twitter.com/_inesmontani/status/1144173225322143744" target="_blank"><small>(ref)</small></a> - <a href="https://twitter.com/honnibal/status/1144031421859655680" target="_blank"><small>(ref)</small></a></div>

---

## **Typer**, the FastAPI of CLIs

<a href="https://typer.tiangolo.com" target="_blank"><img src="https://typer.tiangolo.com/img/logo-margin/logo-margin-vector.svg" style="width: 20%;"></a>

Se você está construindo um  <abbr title="Command Line Interface">CLI</abbr> que será utilizado no terminal ao invés de uma web API, dê uma olhada no <a href="https://typer.tiangolo.com/" class="external-link" target="_blank">**Typer**</a>.

**Typer** é o pequeno irmão da FastAPI. E foi feito para ser o **FastAPI das CLIs**. ⌨️ 🚀

## Requerimentos

Python 3.6+

FastAPI está nos ombros de gigantes:

* <a href="https://www.starlette.io/" class="external-link" target="_blank">Starlette</a> para as partes web.
* <a href="https://pydantic-docs.helpmanual.io/" class="external-link" target="_blank">Pydantic</a> para as partes de dados.


## Instalação
<div class="termy">

```console
$ pip install fastapi

---> 100%
```

</div>

Você também vai precisar do ASGI server, para produção como <a href="http://www.uvicorn.org" class="external-link" target="_blank">Uvicorn</a> ou <a href="https://gitlab.com/pgjones/hypercorn" class="external-link" target="_blank">Hypercorn</a>.
<div class="termy">

```console
$ pip install uvicorn

---> 100%
```

</div>

## Exemplo

### Crie 

* Crie um arquivo `main.py` com:

```Python
from typing import Optional

from fastapi import FastAPI

app = FastAPI()


@app.get("/")
def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
def read_item(item_id: int, q: Optional[str] = None):
    return {"item_id": item_id, "q": q}
```

<details markdown="1">
<summary>Ou use <code>async def</code>...</summary>

Se o seu código usa `async` / `await`, use `async def`:

```Python hl_lines="9 14"
from typing import Optional

from fastapi import FastAPI

app = FastAPI()


@app.get("/")
async def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
async def read_item(item_id: int, q: Optional[str] = None):
    return {"item_id": item_id, "q": q}
```

**Nota**:

Se você não sabe cheque a seção _"In a hurry?"_ ("Tá com pressa?") Sobre <a href="https://fastapi.tiangolo.com/async/#in-a-hurry" target="_blank">`async` e `await` na documentação</a>.

</details>

### Rode o server

Rode o server com:

<div class="termy">

```console
$ uvicorn main:app --reload

INFO:     Uvicorn running on http://127.0.0.1:8000 (Press CTRL+C to quit)
INFO:     Started reloader process [28720]
INFO:     Started server process [28722]
INFO:     Waiting for application startup.
INFO:     Application startup complete.
```

</div>

<details markdown="1">
<summary>Sobre o comando <code>uvicorn main:app --reload</code>...</summary>

O comando `uvicorn main:app` se refere a::

* `main`: the file `main.py` (the Python "module").
* `app`: the object created inside of `main.py` with the line `app = FastAPI()`.
* `--reload`: make the server restart after code changes. Only do this for development.

</details>

### Cheque isso

Abra o navegador no: <a href="http://127.0.0.1:8000/items/5?q=somequery" class="external-link" target="_blank">http://127.0.0.1:8000/items/5?q=somequery</a>.

Você vai ver um JSON response como:

```JSON
{"item_id": 5, "q": "somequery"}
```

Você já criou uma API que:

* Recebe requisições HTTP no _camino_ `/` e `/items/{item_id}`.
* Ambos aceitam <em>operações</em> `GET` (Também conhecido como método HTTP_).
* O _caminho_ `/items/{item_id}` tem um _caminho como parametro_  o`item_id` que deve ser um`int`.
* O _caminho_ `/items/{item_id}` tem um `str` _query parameter_ `q`. que é opcional

###  Documentação interativa de API

Agora vá para <a href="http://127.0.0.1:8000/docs" class="external-link" target="_blank">http://127.0.0.1:8000/docs</a>.

Você vai ver a documentação interativa da API (fornecida pela <a href="https://github.com/swagger-api/swagger-ui" class="external-link" target="_blank">Swagger UI</a>):

![Swagger UI](https://fastapi.tiangolo.com/img/index/index-01-swagger-ui-simple.png)

### Documentação alternativa da API

E agora, vá para <a href="http://127.0.0.1:8000/redoc" class="external-link" target="_blank">http://127.0.0.1:8000/redoc</a>.

Você vai ver a documentação automática alternativa (fornecido por <a href="https://github.com/Rebilly/ReDoc" class="external-link" target="_blank">ReDoc</a>):

![ReDoc](https://fastapi.tiangolo.com/img/index/index-02-redoc-simple.png)

## Exemplo de upgrade

Agora modifica o arquivo `main.py` para receber um body de uma requisição `PUT`.

Declare o body usando tipagem python padrão, obrigado Pydantic.

```Python hl_lines="4  9 10 11 12  25 26 27"
from typing import Optional

from fastapi import FastAPI
from pydantic import BaseModel

app = FastAPI()


class Item(BaseModel):
    name: str
    price: float
    is_offer: Optional[bool] = None


@app.get("/")
def read_root():
    return {"Hello": "World"}


@app.get("/items/{item_id}")
def read_item(item_id: int, q: Optional[str] = None):
    return {"item_id": item_id, "q": q}


@app.put("/items/{item_id}")
def update_item(item_id: int, item: Item):
    return {"item_name": item.name, "item_id": item_id}
```

O server deve ser automaticamente recarregado (porque você adicionou  `--reload` ao `uvicorn` comando acima).

### Upgrade da documentação interativa da API

Agora vá para<a href="http://127.0.0.1:8000/docs" class="external-link" target="_blank">http://127.0.0.1:8000/docs</a>.

* A documentação interativa da API vai automaticamente atualizada, incluindo o novo body:

![Swagger UI](https://fastapi.tiangolo.com/img/index/index-03-swagger-02.png)

* Clique no botão "Try it out", isso vai permitir preencher os parametros e interagir diretamente com a API:

![Swagger UI interaction](https://fastapi.tiangolo.com/img/index/index-04-swagger-03.png)

* Então clique no botão "Execute", A interface do usuário vai se comunicar com a sua API, enviar parametros, pegar resultados e mostrar eles na tela:

![Swagger UI interaction](https://fastapi.tiangolo.com/img/index/index-05-swagger-04.png)

### Upgrade alternativo de documentação da API:

E agora, vá para <a href="http://127.0.0.1:8000/redoc" class="external-link" target="_blank">http://127.0.0.1:8000/redoc</a>.

* A documentação alternativa vai refletir em um novo query parameter e body:
![ReDoc](https://fastapi.tiangolo.com/img/index/index-06-redoc-02.png)

### Recaptulando

No sumário, você declarou **uma vez** os tipos dos parametros, body, etc. como funções com parametros.

Você vai fazer isso com tipagem Python padrão.

VocÇe não tem que aprender uma nova sintaxe, os métodos ou classes de uma biblioteca específica, etc.

Só **Python 3.6+** padrão.

Por exemplo para uma `int`:

```Python
item_id: int
```

ou para um mais complexo modelo `Item` :

```Python
item: Item
```
... e com essa única declaração você tem:

* Suporte de editor, incluindo:
    * Auto completação.
    * Checagem de tipos.
* Validação de dados:
    * Erros automáticos e claros quando os dados forem inválidos.
    * Validação até para objetos JSON profundamente aninhados.
* <abbr title="também conheco como: serialização, parsing, marshalling">Conversão</abbr> de dados de input: vindo da rede para pytho data e tipos. Lendo de:
    * JSON.
    * Path parameters.
    * Query parameters.
    * Cookies.
    * Headers.
    * Forms.
    * Files.
* <abbr title="também conheco como: serialização, parsing, marshalling">Conversão</abbr> de dados de output: convertendo para python data e tipos para dados de rede (as JSON):
    * Converte tipos Python (`str`, `int`, `float`, `bool`, `list`, etc).
    * Objetos `datetime`.
    * Objetos `UUID`.
    * Modelos de banco de dados.
    * ...e muito mais.
* Documentação automática e interativa, incluindo 2 interfaces de usuário alternativas:
    * Swagger UI.
    * ReDoc.

---

Voltando para exemplo de código anterior, **FastAPI** vai:

* Validar que tem um `item_id` no caminho para requisições `GET` e `PUT`.
* Valida que o `item_id` é do tipo `int` para requisições  `GET` e `PUT`.
    * Se não, o client vai ver um erro claro e útil.
* Checa se existe um query opcional nomeada como `q` (como em `http://127.0.0.1:8000/items/foo?q=somequery`) para requisições `GET`.
    * Como o parametro `q` é declarado como `= None`, ele é opcional.
    * Sem o `None` Ele vai ser requirido (como o body é em casos com `PUT`).
* Para requisições `PUT` para `/items/{item_id}`, Lê o body como JSON:
    * Checa que ele requer um atributo `name`, que deve ser uma `str`. 
    * Checa que ele requer um atributo `price`, que deve ser um `float`.
    * Checa que existe um atributo opcional `is_offer`, que deve ser um `bool`, se presente.
    * Tudo isso também iria funcionar para objetos JSON profundamente aninhados.
* Converte de JSON e para JSON automaticamente.
* Documenta tudo com OpenAPI, que pode ser usado para:
    * Sistema de documentação interativa.
    * Sistemas de client de geração de códigos, para várias linguagens de programação.
* Provê 2 interfaces web de documentações interativa.

---

Nós só arranhamos a superfície, mas você já pegou a ideia de como tudo funciona.

Tente mudar a linha com:

```Python
    return {"item_name": item.name, "item_id": item_id}
```

...from:

```Python
        ... "item_name": item.name ...
```

...para:

```Python
        ... "item_price": item.price ...
```

...e veja como o seu editor vai auto-completar os atributos e saber o tipo deles:

![editor support](https://fastapi.tiangolo.com/img/vscode-completion.png)

Para mais exemplos completos incluindo mais recursos, veja o <a href="https://fastapi.tiangolo.com/tutorial/">Tutorial - Guia de uso</a>.

**Alerta de Spoiler**: O tutorial - guia de uso inclui:

* Declaração de **parametros** de outros lugares diferentes : **headers**, **cookies**, **form fields** e **files**.
* Como setar **validation constraints** como `maximum_length` ou `regex`.
* Um sistema muito poderoso e fácil de usar **<abbr title="também conhecido como componentes, recursos, provedores, serviços e injetaveis">Inserção de dependencias</abbr>**.
* Segurança e autenticação, incluindo suporte para**OAuth2** com **JWT tokens** e autenticação **HTTP Basic**.
* Mais técnicas avançadas (mas igualmente fáceis) para declaração **Modelos JSON profundamente aninhados** (obrigado Pydantic).
* Muitos recursos extras (obrigado Starlette) como:
    * **WebSockets**
    * **GraphQL**
    * Teste fáceis baseados em `requests` e `pytest`
    * **CORS**
    * **Cookie Sessions**
    * ...e mais.

## Performance


Independentemente como o benchmarks da TechEmpower mostra aplicações **FastAPI** rodam Uvicorn como <a href="https://www.techempower.com/benchmarks/#section=test&runid=7464e520-0dc2-473d-bd34-dbdfd7e85911&hw=ph&test=query&l=zijzen-7" class="external-link" target="_blank">Umas das mais rápidas frameworks em python disponíveis </a>, somente abaixo de Starlette e Uvicorn (utilizados internamente pela FastAPI). (*)

Para entender mais sobre, veja a seção <a href="https://fastapi.tiangolo.com/benchmarks/" class="internal-link" target="_blank">Benchmarks</a>.

## Dependências opcionais

Usado por Pydantic:

* <a href="https://github.com/esnme/ultrajson" target="_blank"><code>ujson</code></a> - Para JSON rápidos<abbr title="convertendo a string que vem de uma requisição HTTP até dados python">"parsing"</abbr>.
* <a href="https://github.com/JoshData/python-email-validator" target="_blank"><code>email_validator</code></a> - para validação de emails

Usado por Starlette:

* <a href="http://docs.python-requests.org" target="_blank"><code>requests</code></a> - Requerido se você quer usar o `TestClient`.
* <a href="https://github.com/Tinche/aiofiles" target="_blank"><code>aiofiles</code></a> - Requerido se você quer usar o `FileResponse` ou `StaticFiles`.
* <a href="http://jinja.pocoo.org" target="_blank"><code>jinja2</code></a> - Requerido se você quer usar o template padrão de configuração.
* <a href="https://andrew-d.github.io/python-multipart/" target="_blank"><code>python-multipart</code></a> - Requerido se você quer usar o suporte dp <abbr title="convertendo a string que vem de uma requisição HTTP até dados python">"parsing"</abbr>, with `request.form()`.
* <a href="https://pythonhosted.org/itsdangerous/" target="_blank"><code>itsdangerous</code></a> - Requer `SessionMiddleware` para suporte.
* <a href="https://pyyaml.org/wiki/PyYAMLDocumentation" target="_blank"><code>pyyaml</code></a> - Requirido por Starlette `SchemaGenerator` suporte (Você provavelmente não precisa disso com FastAPI).
* <a href="https://graphene-python.org/" target="_blank"><code>graphene</code></a> - Requirido para `GraphQLApp` suporte.
* <a href="https://github.com/esnme/ultrajson" target="_blank"><code>ujson</code></a> - Requisido se você quer usar `UJSONResponse`.

Usados por FastAPI / Starlette:

* <a href="http://www.uvicorn.org" target="_blank"><code>uvicorn</code></a> - Para server que carrega e serve sua aplicação.
* <a href="https://github.com/ijl/orjson" target="_blank"><code>orjson</code></a> - Requirido se você quer usar `ORJSONResponse`.

Você pode install tudo isso com `pip install fastapi[all]`.

## Liçensa

Esse projeto é licenciado sob os termos da licença MIT.
