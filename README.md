# 📞 Scraper de Telefones em Python

Este projeto é um **web scraper** desenvolvido em **Python** para coletar **números telefônicos** de anúncios de automóveis no site.  
Ele utiliza **requisições HTTP**, **parsing HTML** e **expressões regulares** para extrair os dados e salvar em um arquivo `.csv`.

---

## 🚀 Funcionalidades
- Faz requisições HTTP ao site de anúncios.
- Extrai links de anúncios de automóveis.
- Acessa cada anúncio e busca números telefônicos na descrição.
- Utiliza **threads** para acelerar o processo de coleta.
- Salva os números encontrados em `telefone.csv`.

---

## 🛠️ Tecnologias utilizadas
- [Python 3.x](https://www.python.org/)
- [Requests](https://pypi.org/project/requests/) – para requisições HTTP
- [BeautifulSoup (bs4)](https://pypi.org/project/beautifulsoup4/) – para parsing HTML
- [Regex (re)](https://docs.python.org/3/library/re.html) – para localizar padrões de números telefônicos
- [Threading](https://docs.python.org/3/library/threading.html) – para execução paralela

---

## 📦 Dependências

As bibliotecas necessárias estão listadas em `requirements.txt`:

```txt
beautifulsoup4==4.12.3
bs4==0.0.2
certifi==2024.8.30
charset-normalizer==3.4.0
idna==3.10
requests==2.32.3
soupsieve==2.6
urllib3==2.2.3
