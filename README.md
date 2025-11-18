

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

```

---

## **Step 3 — Run Your Generated App**

```bash
cd my_hello_app
python api.py
```

You should see:

```
Hello, World!
```

