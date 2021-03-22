# Recommended .boostignore file

Boost recommends to place the contents below in a file called `.boostignore` in the root of your projects. As the name implies, Boost will ignore these files and directories when scanning which will reduce the false positive rate.

```
# File & directory patterns added here will be ignored by Boost

# TESTS

# general
test/
tests/
unit/
unit_tests/
fixture/
fixtures/
spec/

# javascript
*.test.js
*.test.jsx
*.test.ts
*.test.tsx
*.spec.js
*.spec.jsx
*.spec.ts
*.spec.tsx
cypress/integration/

# python
*test_*.py
*_test.py
atest/
utest/

# go
*_test.go


# OTHER

node_modules/
build/
dist/
.git/
examples/
*.min.js
```
