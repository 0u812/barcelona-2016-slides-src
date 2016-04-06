##  Antimony Conversion

```python
import antimony as sb

sb.loadSBMLFile('input.xml')

print(sb.getModuleNames())
sbstr = sb.getAntimonyString(sb.getModuleNames()[-1])

with open('output.sb', 'w') as f:
  f.write(sbstr)
```
