# Recommended .boostignore file

Boost recommends to place the contents below in a file called `.boostignore` in the root of your projects. As the name implies, Boost will ignore these files and directories when scanning which will reduce the false positive rate.

```
# File & directory patterns added here will be ignored by Boost

# TESTS
test/
tests/
atest/
utest/
unit/
unit_tests/
fixture/
fixtures/
spec/
*.test.*
*test_*.py
*_test.py
*_test.go


# DEPS
node_modules/
vendor/

# BUILD & STATIC
build/
dist/
static/
assets/

# DOCS & OTHER
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
