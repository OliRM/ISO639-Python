# ISO639-Python
ISO639-1/ISO639-2/ISO-Language Translator

## Usage:
```python
import ISO639

ISO639.from_1_to_2(code)
ISO639.from_1_to_language(code)
ISO639.from_2_to_1(code)
ISO639.from_2_to_language(code)
ISO639.from_language_to_1(language)
ISO639.from_language_to_2(language)
```

## Examples:
```python
from_1_to_2('tib')             # --> {'bo'}
from_2_to_1('bo')              # --> {'tib', 'bod'}
from_1_to_language('arm')      # --> {'Armenian'}
from_language_to_1('Armenian') # --> {'hye', 'arm'}
from_2_to_language('br')       # --> {'Breton'}
from_language_to_2('Breton')   # --> {'br'}
```
