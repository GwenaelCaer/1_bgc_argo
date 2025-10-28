# BGC-Argo Data Calibration & Qualification

### Colocation

Welcome! This repository features a series of Python Jupyter Notebooks that walk you through:

✅ Accessing BGC-Argo data  
✅ Accessing GlobColour data  
✅ Colating satelitte and In-Situ Data

---

## 🚀 Quickstart

### 1. Clone the Repository

```bash
git clone https://gitlab.ifremer.fr/odatis-public/vre/use-cases/1_bgc_argo.git
cd 1_bgc_argo
```

### 2. Set Up the Environment

Use the provided `ci/requirements/environment.yml` file to create a Conda environment:

```bash
conda env create -f ci/requirements/environment.yml
conda activate odatis-bgc-argo
```

(Optional) Install the kernel for Jupyter:

```bash
ipython kernel install --user --name=odatis-bgc-argo
```

### 3. Launch Jupyter

```bash
jupyter notebook
```

Your browser should open Jupyter. If not, copy-paste the URL from your terminal into a browser manually.

> 📌 Make sure you run `jupyter notebook` from **within** the repository folder, or some files might not be accessible.

---

## 🧪 Usage Notes

- Start with the [index.ipynb](.notebooks/index.ipynb) notebook.
- Notebooks are interactive – feel free to experiment!
- The project uses non-standard Python packages. Make sure to activate the `odatis-bgc-argo` environment each time before launching Jupyter.

---

## 📚 Documentation

To build the documentation locally:

```bash
conda env update -n odatis-bgc-argo -f ci/requirements/environment-dev.yml
conda activate odatis_docs
myst build --html
```

The documentation is available here:  
👉 [https://odatis-public.gitlab-pages.ifremer.fr/vre/use-cases/1_bgc_argo](https://odatis-public.gitlab-pages.ifremer.fr/vre/use-cases/1_bgc_argo)

---

## 📜 License

This project is licensed under the **GNU LGPL v3.0**.  
See the [LICENSE](./LICENSE) file for details.

---

## 👥 Authors

- **Gwenaël CAËR** - [CNRS / ODATIS](https://www.odatis-ocean.fr/en/)
- **Catherine SCHMECHTIG** - [CNRS / ODATIS](https://www.odatis-ocean.fr/en/)