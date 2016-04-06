##  BioModels Example

```python
import tellurium as te
r = te.loada('''
    //Created by libAntimony v2.7.0
    model *BIOMD0000000012()
      // Compartments and Species:
      ...
    end
''')

r.simulate(0,50,1000)
r.plot()
```

See https://gist.github.com/0u812/06c379ff7083c779440f for source