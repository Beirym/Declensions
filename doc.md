# Documentation

Documentation on working with the module - declensions.

# Import

```python
from declensions import decline
```

# Word transmission example

```python
first_version = decline(word='человек', quantity=22, endings={'first': 'ека', 'second': 'ек'}
print(first_version) # человека

second_version = decline(word='человек', quantity=15, endings={'first': 'ека', 'second': 'ек'}
print(second_version) # человек
```
