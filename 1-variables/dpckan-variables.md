# Variáveis no código das funções do dpckan
<a href="#top">(inicio)</a>


## dataset create

---
def create(ckan_host, ckan_key, datapackage, stop, metadata)
---

- [ckan_host](https://github.com/dados-mg/dpckan/blob/c8de5a8b3c5c1e6b9c47b8feff1e4cbf3189494d/dpckan/create_dataset.py#L18)

- [ckan_key](https://github.com/dados-mg/dpckan/blob/c8de5a8b3c5c1e6b9c47b8feff1e4cbf3189494d/dpckan/create_dataset.py#L23)

- [datapackage](https://github.com/dados-mg/dpckan/blob/c8de5a8b3c5c1e6b9c47b8feff1e4cbf3189494d/dpckan/create_dataset.py#L27)

---

run_dataset_validations(ckan_instance, local_datapackage)

dataset_create(ckan_instance, local_datapackage, metadata)

delete_dataset(ckan_instance, local_datapackage.name)

---

[local_datapackage](https://github.com/dados-mg/dpckan/blob/c8de5a8b3c5c1e6b9c47b8feff1e4cbf3189494d/dpckan/create_dataset.py#L37)

[ckan_instance](https://github.com/dados-mg/dpckan/blob/c8de5a8b3c5c1e6b9c47b8feff1e4cbf3189494d/dpckan/create_dataset.py#L38)


## dataset update

## resource create

---
def create_resource (ckan_host, ckan_key, datapackage, resource_name, stop)
---

[resource_name]()

## resource update