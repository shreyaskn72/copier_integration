

## **Step 1 — Install Copier**

```bash
pip install copier
````

or

```bash
pipx install copier
```

---

## **Step 2 — Create a Project from the Template**

From outside the template folder, run:

```bash
copier copy ./python_hello ./my_hello_app
```

Example:

```bash
copier copy ./python_hello ./my_hello_app
```

Copier will ask:

```
project_folder_name
file_name
container_port (Container port exposed by the Flask app)


```

---

## **Step 3 — Run Your Generated App**

```bash
cd my_hello_app
python api.py
```

You should see:

```
* Running on all addresses (0.0.0.0)
 * Running on http://127.0.0.1:5000
```

