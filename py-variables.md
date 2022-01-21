# Exercises from [Mosh course](https://programmingwithmosh.com/python/python-exercises-and-questions-for-beginners/)

What is a variable?

What are the primitive built-in types in Python?

	- When should we use “”” (tripe quotes) to define strings?

Assuming (name = “John Smith”), what does name[1] return?

What about name[-2]?

What about name[1:-1]?

How to get the length of name?

	- What are the escape sequences in Python?

	- What is the result of f“{2+2}+{10%3}”?


	- Given (name = “john smith”), what will name.title() return?

	- What does name.strip() do?

What will name.find(“Smith”) return?

	- What will be the value of name after we call name.replace(“j”, “k”)?

How can we check to see if name contains “John”?

What are the 3 types of numbers in Python?

* [checking answers](https://github.com/Andrelamor/pai-ta-on/blob/main/app.py#L19)

# [Jupyter Notebook DataScience Academy](https://github.com/Andrelamor/PythonFundamentos/blob/master/Cap02/Notebooks/DSA-Python-Cap02-02-Variaveis.ipynb)
<a href="#top">(inicio)</a>

* [exercícios](https://github.com/Andrelamor/pai-ta-on/blob/main/variables.py)

#### Variáveis proibidas
<reservadas>
	<summary>Click to expand</summary>

---
False; 
class; 
finally; 
is; 
return; 
None; 
continue; 
for; 
lambda; 
try; 
True; 
def; 
from; 
nonlocal; 
while; 
and; 
del; 
global; 
not; 
with; 
as; 
elif; 
if; 
or; 
yield; 
assert; 
else; 
import; 
pass; 
break; 
except; 
in; 
raise 
---
</reservadas>

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