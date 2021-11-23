## പൈത്തണ്‍ പ്രോഗ്രാം റണ്‍ ചെയ്യുന്നതെങ്ങനെ?

### 1. ഇന്ററാക്ടീവ് ഇന്റര്‍പ്രെട്ടര്‍

ഇന്ററാക്ടീവ് ഇന്റര്‍പ്രെട്ടര്‍ ഉപയോഗിക്കാനായി നിങ്ങള്‍ക്ക് വിന്‍ഡോസില്‍

```
python
```

എന്ന കമാന്‍ഡ് ഉപയോഗിക്കാം. ലിനക്സ് ഡിസ്ട്രിബ്യൂഷനുകളില്‍

```
python3
```

എന്ന കമാന്‍ഡും ഉപയോഗിക്കാവുന്നതാണ്.

കമാന്‍ഡ് ഉപയോഗിച്ച് കഴിയുമ്പോള്‍ ചുവടെക്കാണുന്ന രീതിയില്‍ ഇന്ററാക്ടീവ് ഇന്റര്‍പ്രെട്ടര്‍ ഓപ്പണ്‍ ആകുന്നതാണ്.

```python
F:\MyPythonBook\PythonPointsToPonder>python
Python 3.9.6 (tags/v3.9.6:db3ff76, Jun 28 2021, 15:26:21) [MSC v.1929 64 bit (AMD64)] on win32
Type "help", "copyright", "credits" or "license" for more information.
>>>
```

ഈ റൈറ്റ് ആരോ `>>>` കാണുന്ന സ്ഥലത്തു നിങ്ങള്‍ക്ക് പ്രോഗ്രാം വരി വരിയായി എഴുതാവുന്നതാണ്. ഈ **മൂന്ന് ആരോ**കള്‍ നിങ്ങള്‍ ഇന്ററാക്ടീവ് ഇന്റര്‍പ്രെട്ടറില്‍ ആണെന്ന് സൂചിപ്പിക്കുന്നു. നിങ്ങള്‍ ഇവിടെ പ്രോഗ്രാമ്മിന്റെ ഓരോ വരിയെഴുതി `എന്റര്‍` കീ അമര്‍ത്തുമ്പോളും ആ ലൈനിന്റെ ഔട്ട്പുട്ട് താഴെത്തന്നെ കാണാനാകും. എന്നാല്‍ ഒരു കോഡ് ബ്ലോക്ക് ആണ് നിങ്ങള്‍ എഴുത്തുന്നത് എങ്കില്‍ ആ ബ്ലോക്ക് തീര്‍ന്നിട്ടില്ല എന്ന് കാട്ടുവാന്‍ ഇന്റര്‍പ്രെട്ടറില്‍ എലിപ്സിസ് അഥവാ `...` ആണ് ഉപയോഗിക്കുന്നത്.

ഉദാഹരണമായി

```python
>>> print("Hello world")
Hello world
```
നിങ്ങള്‍ക്ക് `print("Hello world")` എന്ന സ്റ്റേറ്റ്മെന്റ് റണ്‍ ചെയ്തതിന്റെ ഭാഗമായി **Hello world** എന്ന ഔട്ട്പുട്ട് കാണാവുന്നതാണ്.

```python
>>> a = True
>>> if a:
...     print("Hello")
... 
Hello
```

മുകളില്‍ `if` എന്ന കണ്ടീഷണല്‍ ബ്ലോക്ക് തുടങ്ങിയതിന്റെ ഭാഗമായി നിങ്ങള്‍ക്ക് എലിപ്സിസ് (`...`) കാണാവുന്നതാണ്.

### 2. പൈത്തണ്‍ സ്ക്രിപ്റ്റ് റണ്‍ ചെയ്യുന്നതെങ്ങനെ?

1. സ്ക്രിപ്റ്റ് `.py` എക്സ്റ്റെന്‍ഷനില്‍ ഉള്ള ഫയല്‍ ആയി സേവ് ചെയ്യുക.
2. വിന്‍ഡോസ് ആണ് ഉപയോഗിക്കുന്നത് എങ്കില്‍

```
python ...path\name_of_script.py
```
എന്ന  കമാന്‍ഡ് ഉപയോഗിച്ച് സ്ക്രിപ്റ്റ് റണ്‍ ചെയ്യാവുന്നതാണ്.

മറിച്ച് ലിനക്സ് ആണ് ഉപയോഗിക്കുന്നത് എങ്കില്‍

```
python3 .../path/name_of_script.py
```
