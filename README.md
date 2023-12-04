# Traductor de Notebooks de Jupyter

Este repositorio contiene un script de Python que permite traducir notebooks de Jupyter a diferentes idiomas.

El script utiliza el API de OpenAI para realizar las traducciones.

## Instalación

### Configura API de openAI

Para configurar la API de OpenAI, primero debe crear una cuenta en el sitio web de OpenAI. Una vez que haya creado una cuenta, deberá generar una API key. 

Una vez que haya generado una API key, deberá copiarla y pegarla en el archivo  `.env`  en el directorio raíz del proyecto. 

El archivo  `.env`  debe tener el siguiente formato:

```bash
OPENAI_API_KEY=<tu_api_key>
```

Una vez que haya configurado la API de OpenAI, puede comenzar a utilizar el script de Python para traducir notebooks de Jupyter.

Para instalar el script, clone el repositorio y ejecute el siguiente comando:

```bash
pip install -r requirements.txt
```
## Uso

Para traducir un notebook, ejecute el siguiente comando:

```bash
python traductor_notebook.py <archivo_notebook> <idioma>
```

El script creará un nuevo archivo llamado `mi_notebook_es.ipynb` con la traducción del notebook.

<img src="traduccion_2.jpeg">



## Contribuciones

Si desea contribuir al proyecto, puede enviar un pull request con sus cambios.

## Licencia

El proyecto está licenciado bajo la licencia MIT.