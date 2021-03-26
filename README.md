# Recommended .boostignore file

Boost recommends to place the contents below in a file called `.boostignore` in the root of your projects. As the name implies, Boost will ignore these files and directories when scanning which will reduce the false positive rate.

```
# File & directory patterns added here will be ignored by Boost

# TESTS
test/
tests/
unit/
unit_tests/
fixture/
fixtures/
spec/
*.test.js
*.test.jsx
*.test.ts
*.test.tsx
*.spec.js
*.spec.jsx
*.spec.ts
*.spec.tsx
cypress/integration/
*test_*.py
*_test.py
atest/
utest/
*_test.go


# BUILD, DOCS, & OTHERS
node_modules/
build/
dist/
.git/
examples/
*.min.js
*.rst
*.md
*.txt
*.adoc
*.mdx
*.sample
*.markdown
```
